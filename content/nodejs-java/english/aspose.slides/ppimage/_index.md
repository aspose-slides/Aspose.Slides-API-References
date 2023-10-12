---
title: PPImage
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/ppimage/
---

## PPImage class

 Represents an image in a presentation.
 
| Name | Description |
| --- | --- |
| dispose () | Disposes object. |


---


| Name | Description |
| --- | --- |
| getBinaryData () | Returns the copy of an image's data. Read-only byte[]. |

### Result
byte


---


| Name | Description |
| --- | --- |
| getContentType () | Returns a MIME type of an image, encoded in BinaryData( #getBinaryData). Read-only String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getHeight () | Returns a height of an image. Read-only int. |

### Result
int


---


| Name | Description |
| --- | --- |
| getSvgImage () | Returns or sets ISvgImage object ISvgImage This value indicates that this image has been created from SVG. |

### Result
SvgImage(../../svgimage)


---


| Name | Description |
| --- | --- |
| getSystemImage () | Returns the copy of an image. Read-only java.awt.image.BufferedImage. |

### Result
BufferedImage


---


| Name | Description |
| --- | --- |
| getWidth () | Returns a width of an image. Read-only int. |

### Result
int


---


| Name | Description |
| --- | --- |
| getX () | Returns a X-offset of an image. Read-only int. |

### Result
int


---


| Name | Description |
| --- | --- |
| getY () | Returns a Y-offset of an image. Read-only int. |

### Result
int


---


| Name | Description |
| --- | --- |
| hashCode () | Returns the hash code of an image. |

### Result
int


---


| Name | Description |
| --- | --- |
| replaceImage (byte[]) | Replaces image data. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| newImageData | byte[] | The new image's data. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentNullException | When newImageData parameter is null. |


---


| Name | Description |
| --- | --- |
| replaceImage (PPImage(../ppimage)) | Replaces image data. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| newImage | PPImage(../../ppimage) | The new IPPImage. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentNullException | When newImage parameter is null. |


---


| Name | Description |
| --- | --- |
| setSvgImage (SvgImage(../svgimage)) | Returns or sets ISvgImage object ISvgImage This value indicates that this image has been created from SVG. |


---


