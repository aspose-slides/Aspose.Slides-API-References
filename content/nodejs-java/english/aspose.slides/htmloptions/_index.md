---
title: HtmlOptions
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/htmloptions/
---

## HtmlOptions class

 Represents a HTML exporting options.
 
| Name | Description |
| --- | --- |
| HtmlOptions(VideoPlayerHtmlController(../videoplayerhtmlcontroller)) | Creates a new HtmlOptions object specifiing callback. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| linkEmbedController | VideoPlayerHtmlController(../../videoplayerhtmlcontroller) | Callback object which controls saving project. |

### Result
HtmlOptions


---


| Name | Description |
| --- | --- |
| HtmlOptions() | Creates a new HtmlOptions object for saving into single HTML file. |

### Result
HtmlOptions


---


| Name | Description |
| --- | --- |
| getDeletePicturesCroppedAreas () | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getHtmlFormatter () | Returns or sets HTML template. Read/write IHtmlFormatter. |

### Result
HtmlFormatter(../../htmlformatter)


---


| Name | Description |
| --- | --- |
| getJpegQuality () | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 95. |

### Result
byte


---


| Name | Description |
| --- | --- |
| getNotesCommentsLayouting () | Provides options that control how notes and comments is placed in exported document. |

### Result
NotesCommentsLayoutingOptions(../../notescommentslayoutingoptions)


---


| Name | Description |
| --- | --- |
| getPicturesCompression () | Represents the pictures compression level |

### Result
int


---


| Name | Description |
| --- | --- |
| getShowHiddenSlides () | Specifies whether the generated document should include hidden slides or not. Default is false. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getSlideImageFormat () | Returns or sets slide image format options. Read/write ISlideImageFormat. |

### Result
SlideImageFormat(../../slideimageformat)


---


| Name | Description |
| --- | --- |
| getSvgResponsiveLayout () | True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| setDeletePicturesCroppedAreas (boolean) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |


---


| Name | Description |
| --- | --- |
| setHtmlFormatter (HtmlFormatter(../htmlformatter)) | Returns or sets HTML template. Read/write IHtmlFormatter. |


---


| Name | Description |
| --- | --- |
| setJpegQuality (byte) | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 95. |


---


| Name | Description |
| --- | --- |
| setPicturesCompression (int) | Represents the pictures compression level |


---


| Name | Description |
| --- | --- |
| setShowHiddenSlides (boolean) | Specifies whether the generated document should include hidden slides or not. Default is false. |


---


| Name | Description |
| --- | --- |
| setSlideImageFormat (SlideImageFormat(../slideimageformat)) | Returns or sets slide image format options. Read/write ISlideImageFormat. |


---


| Name | Description |
| --- | --- |
| setSvgResponsiveLayout (boolean) | True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. Read/write boolean. |


---


