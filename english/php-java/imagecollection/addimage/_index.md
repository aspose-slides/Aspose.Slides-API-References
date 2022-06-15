---
title: addImage
type: docs
weight: 10
url: /php-java/imagecollection/addimage/
---

# addImage(com.aspose.slides.IPPImage) method

 Adds a copy of an image from an another presentation.
 

##  Parameters

| name | description |
| --- | --- |
| imageSource | Source image. |

##  Returns
Added image.


# addImage(java.awt.image.BufferedImage) method

 Add an image to a presentation.
 

##  Parameters

| name | description |
| --- | --- |
| image | Image to add. This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation. |

##  Returns
Added image.


# addImage(java.io.InputStream) method

 Add an image to a presentation from stream.
 

##  Parameters

| name | description |
| --- | --- |
| stream | Stream to add image from. This method can add WMF/EMF metafiles to a presentation without converting them to raster PNG image. |

##  Returns
Added image.


# addImage(java.io.InputStream, int) method

 Creates and adds an image to a presentation from stream.
 

##  Parameters

| name | description |
| --- | --- |
| stream | Stream to add image file from. |
| loadingStreamBehavior | The behavior which will be applied to the stream. |

##  Returns
Added IPPImage.


# addImage(byte[]) method

 Adds an image to a presentation from specified buffer.
 

##  Parameters

| name | description |
| --- | --- |
| buffer | Buffer. |

##  Returns
Added image.


# addImage(com.aspose.slides.ISvgImage) method

 Add an image to a presentation from Svg object. 
 

##  Parameters

| name | description |
| --- | --- |
| svgImage | Svg image object ISvgImage |

##  Returns
Added image.

##  Exception
ArgumentNullException When svgImage parameter is null.


