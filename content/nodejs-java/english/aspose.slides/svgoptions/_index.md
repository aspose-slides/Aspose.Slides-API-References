---
title: SVGOptions
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/svgoptions/
---

## SVGOptions class

 Represents an SVG options.
 
| [SVGOptions]() | Initializes a new instance of the SVGOptions class. |

### Result
SVGOptions


---


| [SVGOptions]([VideoPlayerHtmlController]) | Initializes a new instance of the SVGOptions class specifying the link embedding controller object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| linkEmbedController | [VideoPlayerHtmlController] | The link embedding controller reference. Link embedding controller is a delegate object that is responsible for making decisions if resources (such as images) need to be embedded or referenced as external resources. |

### Result
SVGOptions


---


| [getDefault] () Returns default settings. Read-only SVGOptions. |

### Result
SVGOptions


---


| [getDeletePicturesCroppedAreas] () A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |

### Result
boolean


---


| [getDisable3DText] () Determines whether the 3D text is disabled in SVG. Read/write boolean. |

### Result
boolean


---


| [getDisableGradientSplit] () Disables splitting FromCornerX and FromCenter gradients. Read/write boolean. |

### Result
boolean


---


| [getDisableLineEndCropping] () SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean. |

### Result
boolean


---


| [getExternalFontsHandling] () Determines a way of handling externally loaded fonts. Read/write SvgExternalFontsHandling. |

### Result
int


---


| [getJpegQuality] () Determines JPEG encoding quality. Read/write int. |

### Result
int


---


| [getMetafileRasterizationDpi] () Returns or sets the lower resolution limit for metafile rasterization. Read/write int. |

### Result
int


---


| [getPicturesCompression] () Represents the pictures compression level |

### Result
int


---


| [getShapeFormattingController] () Returns and sets a callback interface which allows user to control shape conversion. Read/write ISvgShapeFormattingController. |

### Result
[VideoPlayerHtmlController]


---


| [getSimple] () Returns settings for simpliest and smallest SVG file generation. Read-only SVGOptions. |

### Result
SVGOptions


---


| [getUseFrameRotation] () Determines whether to perform the specified rotation of the shape when rendering or not. Read/write boolean. Default value is true. |

### Result
boolean


---


| [getUseFrameSize] () Determines whether the text frame will be included in a rendering area or not. Read/write boolean. Default value is false. |

### Result
boolean


---


| [getVectorizeText] () Determines whether the text on a slide will be saved as graphics. Read/write boolean. |

### Result
boolean


---


| [getWYSIWYG] () Returns settings for most accurate SVG file generation. Read-only SVGOptions. |

### Result
SVGOptions


---


| [setDeletePicturesCroppedAreas] ([boolean]) A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |


---


| [setDisable3DText] ([boolean]) Determines whether the 3D text is disabled in SVG. Read/write boolean. |


---


| [setDisableGradientSplit] ([boolean]) Disables splitting FromCornerX and FromCenter gradients. Read/write boolean. |


---


| [setDisableLineEndCropping] ([boolean]) SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write boolean. |


---


| [setExternalFontsHandling] ([int]) Determines a way of handling externally loaded fonts. Read/write SvgExternalFontsHandling. |


---


| [setJpegQuality] ([int]) Determines JPEG encoding quality. Read/write int. |


---


| [setMetafileRasterizationDpi] ([int]) Returns or sets the lower resolution limit for metafile rasterization. Read/write int. |


---


| [setPicturesCompression] ([int]) Represents the pictures compression level |


---


| [setShapeFormattingController] ([VideoPlayerHtmlController]) Returns and sets a callback interface which allows user to control shape conversion. Read/write ISvgShapeFormattingController. |


---


| [setUseFrameRotation] ([boolean]) Determines whether to perform the specified rotation of the shape when rendering or not. Read/write boolean. Default value is true. |


---


| [setUseFrameSize] ([boolean]) Determines whether the text frame will be included in a rendering area or not. Read/write boolean. Default value is false. |


---


| [setVectorizeText] ([boolean]) Determines whether the text on a slide will be saved as graphics. Read/write boolean. |


---


