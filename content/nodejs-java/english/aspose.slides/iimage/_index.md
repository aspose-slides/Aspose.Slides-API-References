---
title: IImage
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/iimage/
---

## IImage class

 Represents a raster or vector image.
 
 This interface provides a common abstraction for handling both raster and vector images.  
 Implementations may vary depending on the underlying image type.
 
### IImage {#IImage}

| Name | Description |
| --- | --- |
| IImage() |  |

 **Returns:**
IImage


---


### getHeight {#getHeight}

| Name | Description |
| --- | --- |
| getHeight () | Gets the height of the image in pixels. |

 **Returns:**
int


---


### getSize {#getSize}

| Name | Description |
| --- | --- |
| getSize () | Gets the size of the image. |

 **Returns:**
Dimension


---


### getWidth {#getWidth}

| Name | Description |
| --- | --- |
| getWidth () | Gets the width of the image in pixels. |

 **Returns:**
int


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String) | Saves the image to a file. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| filename | String | The path to the file where the image will be saved. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int) | Saves the image to a file in the specified format. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| filename | String | The path to the file where the image will be saved. |
| format | int | The image format. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (IImage, WriteStream, int) | Saves the image to a stream in the specified format. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| iimage | IImage  | link to self |
| stream | WriteStream | The stream where the image will be saved. |
| format | int | The image format. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, int) | Saves the image to a file in the specified format and quality. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| filename | String | The path to the file where the image will be saved. |
| format | int | The image format. |
| quality | int | The quality of the saved image (0 to 100). This parameter only affects saving in ImageFormat#Jpeg; for all other formats, it is ignored. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (IImage, WriteStream, int, int) | Saves the image to a stream in the specified format and quality. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| iimage | IImage  | link to self |
| stream | WriteStream | The stream where the image will be saved. |
| format | int | The image format. |
| quality | int | The quality of the saved image (0 to 100). This parameter only affects saving in ImageFormat#Jpeg; for all other formats, it is ignored. |


---


