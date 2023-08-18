---
title: addImage
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/imagecollection/addimage/
---

## addImage([PPImage](../../ppimage) imageSource)  function

 Adds a copy of an image from an another presentation.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| imageSource | [PPImage](../../ppimage) | Source image. |

### Result
[PPImage](../../ppimage)


---


## addImage(BufferedImage image)  function

 Add an image to a presentation.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| image | BufferedImage | Image to add. This function converts WMF/EMF metafiles to raster PNG image before inserting to a presentation. |

### Result
[PPImage](../../ppimage)


---


## addImageFromStream (ImageCollection imagecollection, ReadStream stream, Function callback)  function

 Add an image to a presentation from stream.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| imagecollection | ImageCollection  | link to self |
| stream | ReadStream | Stream to add image from. This function can add WMF/EMF metafiles to a presentation without converting them to raster PNG image. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[PPImage](../../ppimage)


---


## addImageFromStream (ImageCollection imagecollection, ReadStream stream, int loadingStreamBehavior, Function callback)  function

 Creates and adds an image to a presentation from stream.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| imagecollection | ImageCollection  | link to self |
| stream | ReadStream | Stream to add image file from. |
| loadingStreamBehavior | int | The behavior which will be applied to the stream. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[PPImage](../../ppimage)


---


## addImage(byte[] buffer)  function

 Adds an image to a presentation from specified buffer.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

### Result
[PPImage](../../ppimage)


---


## addImage([SvgImage](../../svgimage) svgImage)  function

 Add an image to a presentation from Svg object. 
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| svgImage | [SvgImage](../../svgimage) | Svg image object ISvgImage |

### Result
[PPImage](../../ppimage)

### Error

| Error | Condition |
| --- | --- |
 | ArgumentNullException | When svgImage parameter is null. |


---


