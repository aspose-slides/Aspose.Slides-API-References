---
title: addImage
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/aspose.slides/imagecollection/addimage/
---

## addImage([PPImage](../../ppimage) imageSource)  method

 Adds a copy of an image from an another presentation.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| imageSource | [PPImage](../../ppimage) | Source image. |

### Returns
[PPImage](../../ppimage)


---


## addImage(BufferedImage image)  method

 Add an image to a presentation.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| image | BufferedImage | Image to add. This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation. |

### Returns
[PPImage](../../ppimage)


---


## addImage(InputStream stream)  method

 Add an image to a presentation from stream.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Stream to add image from. This method can add WMF/EMF metafiles to a presentation without converting them to raster PNG image. |

### Returns
[PPImage](../../ppimage)


---


## addImage(InputStream stream, int loadingStreamBehavior)  method

 Creates and adds an image to a presentation from stream.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Stream to add image file from. |
| loadingStreamBehavior | int | The behavior which will be applied to the stream. |

### Returns
[PPImage](../../ppimage)


---


## addImage(byte[] buffer)  method

 Adds an image to a presentation from specified buffer.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

### Returns
[PPImage](../../ppimage)


---


## addImage([SvgImage](../../svgimage) svgImage)  method

 Add an image to a presentation from Svg object. 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| svgImage | [SvgImage](../../svgimage) | Svg image object ISvgImage |

### Returns
[PPImage](../../ppimage)

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentNullException | When svgImage parameter is null. |


---


