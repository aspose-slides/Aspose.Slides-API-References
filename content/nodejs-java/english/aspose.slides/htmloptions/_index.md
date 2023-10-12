---
title: HtmlOptions
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/htmloptions/
---

## HtmlOptions class

 Represents a HTML exporting options.
 
| [HtmlOptions]([VideoPlayerHtmlController]) | Creates a new HtmlOptions object specifiing callback. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| linkEmbedController | [VideoPlayerHtmlController] | Callback object which controls saving project. |

### Result
HtmlOptions


---


| [HtmlOptions]() | Creates a new HtmlOptions object for saving into single HTML file. |

### Result
HtmlOptions


---


| [getDeletePicturesCroppedAreas] () | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |

### Result
boolean


---


| [getHtmlFormatter] () | Returns or sets HTML template. Read/write IHtmlFormatter. |

### Result
[HtmlFormatter]


---


| [getJpegQuality] () | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 95. |

### Result
byte


---


| [getNotesCommentsLayouting] () | Provides options that control how notes and comments is placed in exported document. |

### Result
[NotesCommentsLayoutingOptions]


---


| [getPicturesCompression] () | Represents the pictures compression level |

### Result
int


---


| [getShowHiddenSlides] () | Specifies whether the generated document should include hidden slides or not. Default is false. |

### Result
boolean


---


| [getSlideImageFormat] () | Returns or sets slide image format options. Read/write ISlideImageFormat. |

### Result
[SlideImageFormat]


---


| [getSvgResponsiveLayout] () | True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. Read/write boolean. |

### Result
boolean


---


| [setDeletePicturesCroppedAreas] ([boolean]) | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |


---


| [setHtmlFormatter] ([HtmlFormatter]) | Returns or sets HTML template. Read/write IHtmlFormatter. |


---


| [setJpegQuality] ([byte]) | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 95. |


---


| [setPicturesCompression] ([int]) | Represents the pictures compression level |


---


| [setShowHiddenSlides] ([boolean]) | Specifies whether the generated document should include hidden slides or not. Default is false. |


---


| [setSlideImageFormat] ([SlideImageFormat]) | Returns or sets slide image format options. Read/write ISlideImageFormat. |


---


| [setSvgResponsiveLayout] ([boolean]) | True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. Read/write boolean. |


---


