---
title: PdfOptions
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/pdfoptions/
---

## PdfOptions class

 Provides options that control how a presentation is saved in Pdf format.
 
| Name | Description |
| --- | --- |
| PdfOptions() | Default function. |

### Result
PdfOptions


---


| Name | Description |
| --- | --- |
| getAccessPermissions () | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See PdfAccessPermissions. |

### Result
int


---


| Name | Description |
| --- | --- |
| getAdditionalCommonFontFamilies () | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[]. |

### Result
String


---


| Name | Description |
| --- | --- |
| getApplyImageTransparent () | Applies the specified transparent color to an image if true. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getBestImagesCompressionRatio () | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. Best image compression ratio selection is computationally expensive and takes an additional amount of RAM, and this option is false by default. Default is false. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getCompliance () | Desired conformance level for generated PDF document. Read/write PdfCompliance. Default is PdfCompliance#Pdf17. |

### Result
int


---


| Name | Description |
| --- | --- |
| getDrawSlidesFrame () | True to draw black frame around each slide. Read/write boolean. Default is false. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getEmbedFullFonts () | Determines if all characters of font should be embedded or only used subset. Read/write boolean. Default is false. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getEmbedTrueTypeFontsForASCII () | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. Fonts for character codes greater than 127 are always embedded. Common fonts list includes PDF's base 14 fonts and additional user specified fonts. Read/write boolean. Default is true. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getImageTransparentColor () | Gets or sets the image transparent color. Value: The color of the image transparent. |

### Result
Color


---


| Name | Description |
| --- | --- |
| getJpegQuality () | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 100. |

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
| getPassword () | Setting user password to protect the PDF document. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getSaveMetafilesAsPng () | True to convert all metafiles used in a presentation to the PNG images. Read/write boolean. Default is true. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getShowHiddenSlides () | Specifies whether the generated document should include hidden slides or not. Default is false. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getSufficientResolution () | Returns or sets a value determining resolution of images inside PDF document. Read/write float. Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect. Property affects on file size, time of export and image quality. The default value is 96. |

### Result
float


---


| Name | Description |
| --- | --- |
| getTextCompression () | Specifies compression type to be used for all textual content in the document. Read/write PdfTextCompression. Default is PdfTextCompression#Flate. |

### Result
int


---


| Name | Description |
| --- | --- |
| setAccessPermissions (int) | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See PdfAccessPermissions. |


---


| Name | Description |
| --- | --- |
| setAdditionalCommonFontFamilies (java.lang.String[]) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[]. |


---


| Name | Description |
| --- | --- |
| setApplyImageTransparent (boolean) | Applies the specified transparent color to an image if true. |


---


| Name | Description |
| --- | --- |
| setBestImagesCompressionRatio (boolean) | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. Best image compression ratio selection is computationally expensive and takes an additional amount of RAM, and this option is false by default. Default is false. |


---


| Name | Description |
| --- | --- |
| setCompliance (int) | Desired conformance level for generated PDF document. Read/write PdfCompliance. Default is PdfCompliance#Pdf17. |


---


| Name | Description |
| --- | --- |
| setDrawSlidesFrame (boolean) | True to draw black frame around each slide. Read/write boolean. Default is false. |


---


| Name | Description |
| --- | --- |
| setEmbedFullFonts (boolean) | Determines if all characters of font should be embedded or only used subset. Read/write boolean. Default is false. |


---


| Name | Description |
| --- | --- |
| setEmbedTrueTypeFontsForASCII (boolean) | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. Fonts for character codes greater than 127 are always embedded. Common fonts list includes PDF's base 14 fonts and additional user specified fonts. Read/write boolean. Default is true. |


---


| Name | Description |
| --- | --- |
| setImageTransparentColor (Color) | Gets or sets the image transparent color. Value: The color of the image transparent. |


---


| Name | Description |
| --- | --- |
| setJpegQuality (byte) | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 100. |


---


| Name | Description |
| --- | --- |
| setPassword (String) | Setting user password to protect the PDF document. Read/write String. |


---


| Name | Description |
| --- | --- |
| setSaveMetafilesAsPng (boolean) | True to convert all metafiles used in a presentation to the PNG images. Read/write boolean. Default is true. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible. |


---


| Name | Description |
| --- | --- |
| setShowHiddenSlides (boolean) | Specifies whether the generated document should include hidden slides or not. Default is false. |


---


| Name | Description |
| --- | --- |
| setSufficientResolution (float) | Returns or sets a value determining resolution of images inside PDF document. Read/write float. Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect. Property affects on file size, time of export and image quality. The default value is 96. |


---


| Name | Description |
| --- | --- |
| setTextCompression (int) | Specifies compression type to be used for all textual content in the document. Read/write PdfTextCompression. Default is PdfTextCompression#Flate. |


---


