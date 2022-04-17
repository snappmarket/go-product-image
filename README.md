# go-product-image

This library provides SnappMarket product image url.

# Example

**Import**

     import (
         gopimg "github.com/snappmarket/go-product-image"
    )

**Usage**

    		imageStruct := gopimgs.ImageStruct{
    			FileName: &productImage.Filename,
    			ImageName: &productVariation.ImageName,
    			UserType: &productImage.UserType,
    		}
    
    		image = gopimgs.GetProductVariationThumbnailImage(imageStruct)
