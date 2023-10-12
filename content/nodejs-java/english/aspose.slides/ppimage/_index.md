---
title: PPImage
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/ppimage/
---

## PPImage class

 Represents an image in a presentation.
 
###dispose{#dispose}

| Name | Description |
| --- | --- |
| dispose () | Disposes object. |


---


###getBinaryData{#getBinaryData}

| Name | Description |
| --- | --- |
| getBinaryData () | Returns the copy of an image's data. Read-only byte[]. |

 **Result**
byte


---


###getContentType{#getContentType}

| Name | Description |
| --- | --- |
| getContentType () | Returns a MIME type of an image, encoded in BinaryData( #getBinaryData). Read-only String. |

 **Result**
String


---


###getHeight{#getHeight}

| Name | Description |
| --- | --- |
| getHeight () | Returns a height of an image. Read-only int. |

 **Result**
int


---


###getSvgImage{#getSvgImage}

| Name | Description |
| --- | --- |
| getSvgImage () | Returns or sets ISvgImage object ISvgImage This value indicates that this image has been created from SVG. |

 **Result**
[SvgImage](../svgimage)


---


###getSystemImage{#getSystemImage}

| Name | Description |
| --- | --- |
| getSystemImage () | Returns the copy of an image. Read-only java.awt.image.BufferedImage. |

 **Result**
BufferedImage


---


###getWidth{#getWidth}

| Name | Description |
| --- | --- |
| getWidth () | Returns a width of an image. Read-only int. |

 **Result**
int


---


###getX{#getX}

| Name | Description |
| --- | --- |
| getX () | Returns a X-offset of an image. Read-only int. |

 **Result**
int


---


###getY{#getY}

| Name | Description |
| --- | --- |
| getY () | Returns a Y-offset of an image. Read-only int. |

 **Result**
int


---


###hashCode{#hashCode}

| Name | Description |
| --- | --- |
| hashCode () | Returns the hash code of an image. |

 **Result**
int


---


###replaceImage{#replaceImage}

| Name | Description |
| --- | --- |
| replaceImage (byte[]) | Replaces image data. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| newImageData | byte[] | The new image's data. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | When newImageData parameter is null. |


---


###replaceImage{#replaceImage}

| Name | Description |
| --- | --- |
| replaceImage ([PPImage](../ppimage)) | Replaces image data. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| newImage | [PPImage](../ppimage) | The new IPPImage. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | When newImage parameter is null. |


---


###setSvgImage{#setSvgImage}

| Name | Description |
| --- | --- |
| setSvgImage ([SvgImage](../svgimage)) | Returns or sets ISvgImage object ISvgImage This value indicates that this image has been created from SVG. |


---


