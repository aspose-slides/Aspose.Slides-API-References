---
title: addImage
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/imagecollection/addimage/
---

## addImage([PPImage](../../PPImage) imageSource)  method

 Adds a copy of an image from an another presentation.
 

### Parameters

| Name | Description |
| --- | --- |
| imageSource | Source image. |

### Returns
Added image.


---


## addImage(BufferedImage image)  method

 Add an image to a presentation.
 

### Parameters

| Name | Description |
| --- | --- |
| image | Image to add. This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation. |

### Returns
Added image.


---


## addImage(InputStream stream)  method

 Add an image to a presentation from stream.
 

### Parameters

| Name | Description |
| --- | --- |
| stream | Stream to add image from. This method can add WMF/EMF metafiles to a presentation without converting them to raster PNG image. |

### Returns
Added image.


---


## addImage(InputStream stream, int loadingStreamBehavior)  method

 Creates and adds an image to a presentation from stream.
 

### Parameters

| Name | Description |
| --- | --- |
| stream | Stream to add image file from. |
| loadingStreamBehavior | The behavior which will be applied to the stream. |

### Returns
Added IPPImage.


---


## addImage(byte[] buffer)  method

 Adds an image to a presentation from specified buffer.
 

### Parameters

| Name | Description |
| --- | --- |
| buffer | Buffer. |

### Returns
Added image.


---


## addImage([SvgImage](../../SvgImage) svgImage)  method

 Add an image to a presentation from Svg object. 
 

### Parameters

| Name | Description |
| --- | --- |
| svgImage | Svg image object ISvgImage |

### Returns
Added image.

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentNullException | When svgImage parameter is null. |


---


