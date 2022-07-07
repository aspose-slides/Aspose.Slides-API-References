---
title: addImage
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/imagecollection/addimage/
---

## addImage([PPImage](../../ppimage) imageSource)  method

 Adds a copy of an image from an another presentation.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| imageSource | PPImage | Source image. |

### Returns
Added image.


---


## addImage(BufferedImage image)  method

 Add an image to a presentation.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| image | BufferedImage | Image to add. This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation. |

### Returns
Added image.


---


## addImage(InputStream stream)  method

 Add an image to a presentation from stream.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Stream to add image from. This method can add WMF/EMF metafiles to a presentation without converting them to raster PNG image. |

### Returns
Added image.


---


## addImage(InputStream stream, int loadingStreamBehavior)  method

 Creates and adds an image to a presentation from stream.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Stream to add image file from. |
| loadingStreamBehavior | int | The behavior which will be applied to the stream. |

### Returns
Added IPPImage.


---


## addImage(byte[] buffer)  method

 Adds an image to a presentation from specified buffer.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

### Returns
Added image.


---


## addImage([SvgImage](../../svgimage) svgImage)  method

 Add an image to a presentation from Svg object. 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| svgImage | SvgImage | Svg image object ISvgImage |

### Returns
Added image.

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentNullException | When svgImage parameter is null. |


---


