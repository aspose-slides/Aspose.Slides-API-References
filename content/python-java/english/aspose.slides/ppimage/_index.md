---
title: PPImage
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/ppimage/
---

## PPImage class

 Represents an image in a presentation.
 
### dispose {#dispose}

| Name | Description |
| --- | --- |
| dispose() | Disposes object. |


---


### getBinaryData {#getBinaryData}

| Name | Description |
| --- | --- |
| getBinaryData() | Returns the copy of an image's data. Read-only byte[]. |

 **Returns:**
byte


---


### getContentType {#getContentType}

| Name | Description |
| --- | --- |
| getContentType() | Returns a MIME type of an image, encoded in BinaryData( #getBinaryData). Read-only String. |

 **Returns:**
String


---


### getHeight {#getHeight}

| Name | Description |
| --- | --- |
| getHeight() | Returns a height of an image. Read-only int. |

 **Returns:**
int


---


### getImage {#getImage}

| Name | Description |
| --- | --- |
| getImage() | Returns the copy of an image. Read-only IImage. |

 **Returns:**
SlidesImage


---


### getSvgImage {#getSvgImage}

| Name | Description |
| --- | --- |
| getSvgImage() | Returns or sets ISvgImage object ISvgImage This value indicates that this image has been created from SVG. |

 **Returns:**
[SvgImage](../svgimage)


---


### getSystemImage {#getSystemImage}

| Name | Description |
| --- | --- |
| getSystemImage() | Returns the copy of an image. Read-only java.awt.image.BufferedImage. |

 **Returns:**
BufferedImage


---


### getWidth {#getWidth}

| Name | Description |
| --- | --- |
| getWidth() | Returns a width of an image. Read-only int. |

 **Returns:**
int


---


### getX {#getX}

| Name | Description |
| --- | --- |
| getX() | Returns a X-offset of an image. Read-only int. |

 **Returns:**
int


---


### getY {#getY}

| Name | Description |
| --- | --- |
| getY() | Returns a Y-offset of an image. Read-only int. |

 **Returns:**
int


---


### hashCode {#hashCode}

| Name | Description |
| --- | --- |
| hashCode() | Returns the hash code of an image. |

 **Returns:**
int


---


### replaceImage {#replaceImage}

| Name | Description |
| --- | --- |
| replaceImage(byte[]) | Replaces image data. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| newImageData | byte[] | The new image's data. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | When newImageData parameter is null. |


---


### replaceImage {#replaceImage}

| Name | Description |
| --- | --- |
| replaceImage([IImage](../iimage)) | Replaces image data. Attention: when Image is metafile - it will be rasterized. Use replaceImage(byte[]) instead |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| newImage | [IImage](../iimage) | The new image. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | When newImage parameter is null. |


---


### replaceImage {#replaceImage}

| Name | Description |
| --- | --- |
| replaceImage([PPImage](../ppimage)) | Replaces image data. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| newImage | [PPImage](../ppimage) | The new IPPImage. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | When newImage parameter is null. |


---


### setSvgImage {#setSvgImage}

| Name | Description |
| --- | --- |
| setSvgImage([SvgImage](../svgimage)) | Returns or sets ISvgImage object ISvgImage This value indicates that this image has been created from SVG. |


---


