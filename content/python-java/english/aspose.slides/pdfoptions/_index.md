---
title: PdfOptions
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/pdfoptions/
---

## PdfOptions class

 Provides options that control how a presentation is saved in Pdf format.
 
### PdfOptions {#PdfOptions}

| Name | Description |
| --- | --- |
| PdfOptions() | Default constructor. |

 **Result:**
PdfOptions


---


### getAccessPermissions {#getAccessPermissions}

| Name | Description |
| --- | --- |
| getAccessPermissions() | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See PdfAccessPermissions. |

 **Result:**
int


---


### getAdditionalCommonFontFamilies {#getAdditionalCommonFontFamilies}

| Name | Description |
| --- | --- |
| getAdditionalCommonFontFamilies() | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[]. |

 **Result:**
String


---


### getApplyImageTransparent {#getApplyImageTransparent}

| Name | Description |
| --- | --- |
| getApplyImageTransparent() | Applies the specified transparent color to an image if true. |

 **Result:**
boolean


---


### getBestImagesCompressionRatio {#getBestImagesCompressionRatio}

| Name | Description |
| --- | --- |
| getBestImagesCompressionRatio() | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. Best image compression ratio selection is computationally expensive and takes an additional amount of RAM, and this option is false by default. Default is false. |

 **Result:**
boolean


---


### getCompliance {#getCompliance}

| Name | Description |
| --- | --- |
| getCompliance() | Desired conformance level for generated PDF document. Read/write PdfCompliance. Default is PdfCompliance#Pdf17. |

 **Result:**
int


---


### getDefaultRegularFont {#getDefaultRegularFont}

| Name | Description |
| --- | --- |
| getDefaultRegularFont() | Returns or sets font used in case source font is not found. Read-write String. |

 **Result:**
String


---


### getDrawSlidesFrame {#getDrawSlidesFrame}

| Name | Description |
| --- | --- |
| getDrawSlidesFrame() | True to draw black frame around each slide. Read/write boolean. Default is false. |

 **Result:**
boolean


---


### getEmbedFullFonts {#getEmbedFullFonts}

| Name | Description |
| --- | --- |
| getEmbedFullFonts() | Determines if all characters of font should be embedded or only used subset. Read/write boolean. Default is false. |

 **Result:**
boolean


---


### getEmbedTrueTypeFontsForASCII {#getEmbedTrueTypeFontsForASCII}

| Name | Description |
| --- | --- |
| getEmbedTrueTypeFontsForASCII() | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. Fonts for character codes greater than 127 are always embedded. Common fonts list includes PDF's base 14 fonts and additional user specified fonts. Read/write boolean. Default is true. |

 **Result:**
boolean


---


### getImageTransparentColor {#getImageTransparentColor}

| Name | Description |
| --- | --- |
| getImageTransparentColor() | Gets or sets the image transparent color. Value: The color of the image transparent. |

 **Result:**
Color


---


### getInkOptions {#getInkOptions}

| Name | Description |
| --- | --- |
| getInkOptions() | Provides options that control the look of Ink objects in exported document. Read-only IInkOptions |

 **Result:**
[InkOptions](../inkoptions)


---


### getJpegQuality {#getJpegQuality}

| Name | Description |
| --- | --- |
| getJpegQuality() | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 100. |

 **Result:**
byte


---


### getNotesCommentsLayouting {#getNotesCommentsLayouting}

| Name | Description |
| --- | --- |
| getNotesCommentsLayouting() | Provides options that control how notes and comments is placed in exported document. |

 **Result:**
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)


---


### getPassword {#getPassword}

| Name | Description |
| --- | --- |
| getPassword() | Setting user password to protect the PDF document. Read/write String. |

 **Result:**
String


---


### getProgressCallback {#getProgressCallback}

| Name | Description |
| --- | --- |
| getProgressCallback() | Represents a callback object for saving progress updates in percentage. See IProgressCallback. |

 **Result:**
IProgressCallback


---


### getSaveMetafilesAsPng {#getSaveMetafilesAsPng}

| Name | Description |
| --- | --- |
| getSaveMetafilesAsPng() | True to convert all metafiles used in a presentation to the PNG images. Read/write boolean. Default is true. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible. |

 **Result:**
boolean


---


### getShowHiddenSlides {#getShowHiddenSlides}

| Name | Description |
| --- | --- |
| getShowHiddenSlides() | Specifies whether the generated document should include hidden slides or not. Default is false. |

 **Result:**
boolean


---


### getSlidesLayoutOptions {#getSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| getSlidesLayoutOptions() | Gets or sets the mode in which slides are placed on the page when exporting a presentation ISlidesLayoutOptions. |

 **Result:**
[HandoutLayoutingOptions](../handoutlayoutingoptions), [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)


---


### getSufficientResolution {#getSufficientResolution}

| Name | Description |
| --- | --- |
| getSufficientResolution() | Returns or sets a value determining resolution of images inside PDF document. Read/write float. Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect. Property affects on file size, time of export and image quality. The default value is 96. |

 **Result:**
float


---


### getTextCompression {#getTextCompression}

| Name | Description |
| --- | --- |
| getTextCompression() | Specifies compression type to be used for all textual content in the document. Read/write PdfTextCompression. Default is PdfTextCompression#Flate. |

 **Result:**
int


---


### getWarningCallback {#getWarningCallback}

| Name | Description |
| --- | --- |
| getWarningCallback() | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |

 **Result:**
IWarningCallback


---


### setAccessPermissions {#setAccessPermissions}

| Name | Description |
| --- | --- |
| setAccessPermissions(int) | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See PdfAccessPermissions. |


---


### setAdditionalCommonFontFamilies {#setAdditionalCommonFontFamilies}

| Name | Description |
| --- | --- |
| setAdditionalCommonFontFamilies(java.lang.String[]) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[]. |


---


### setApplyImageTransparent {#setApplyImageTransparent}

| Name | Description |
| --- | --- |
| setApplyImageTransparent(boolean) | Applies the specified transparent color to an image if true. |


---


### setBestImagesCompressionRatio {#setBestImagesCompressionRatio}

| Name | Description |
| --- | --- |
| setBestImagesCompressionRatio(boolean) | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. Best image compression ratio selection is computationally expensive and takes an additional amount of RAM, and this option is false by default. Default is false. |


---


### setCompliance {#setCompliance}

| Name | Description |
| --- | --- |
| setCompliance(int) | Desired conformance level for generated PDF document. Read/write PdfCompliance. Default is PdfCompliance#Pdf17. |


---


### setDefaultRegularFont {#setDefaultRegularFont}

| Name | Description |
| --- | --- |
| setDefaultRegularFont(String) | Returns or sets font used in case source font is not found. Read-write String. |


---


### setDrawSlidesFrame {#setDrawSlidesFrame}

| Name | Description |
| --- | --- |
| setDrawSlidesFrame(boolean) | True to draw black frame around each slide. Read/write boolean. Default is false. |


---


### setEmbedFullFonts {#setEmbedFullFonts}

| Name | Description |
| --- | --- |
| setEmbedFullFonts(boolean) | Determines if all characters of font should be embedded or only used subset. Read/write boolean. Default is false. |


---


### setEmbedTrueTypeFontsForASCII {#setEmbedTrueTypeFontsForASCII}

| Name | Description |
| --- | --- |
| setEmbedTrueTypeFontsForASCII(boolean) | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. Fonts for character codes greater than 127 are always embedded. Common fonts list includes PDF's base 14 fonts and additional user specified fonts. Read/write boolean. Default is true. |


---


### setImageTransparentColor {#setImageTransparentColor}

| Name | Description |
| --- | --- |
| setImageTransparentColor(Color) | Gets or sets the image transparent color. Value: The color of the image transparent. |


---


### setJpegQuality {#setJpegQuality}

| Name | Description |
| --- | --- |
| setJpegQuality(byte) | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte. Has effect only when a document contains JPEG images. Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 100. |


---


### setPassword {#setPassword}

| Name | Description |
| --- | --- |
| setPassword(String) | Setting user password to protect the PDF document. Read/write String. |


---


### setProgressCallback {#setProgressCallback}

| Name | Description |
| --- | --- |
| setProgressCallback([IProgressCallback](../iprogresscallback)) | Represents a callback object for saving progress updates in percentage. See IProgressCallback. |


---


### setSaveMetafilesAsPng {#setSaveMetafilesAsPng}

| Name | Description |
| --- | --- |
| setSaveMetafilesAsPng(boolean) | True to convert all metafiles used in a presentation to the PNG images. Read/write boolean. Default is true. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible. |


---


### setShowHiddenSlides {#setShowHiddenSlides}

| Name | Description |
| --- | --- |
| setShowHiddenSlides(boolean) | Specifies whether the generated document should include hidden slides or not. Default is false. |


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| setSlidesLayoutOptions([HandoutLayoutingOptions](../handoutlayoutingoptions)) | Gets or sets the mode in which slides are placed on the page when exporting a presentation ISlidesLayoutOptions. |


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| setSlidesLayoutOptions([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | Gets or sets the mode in which slides are placed on the page when exporting a presentation ISlidesLayoutOptions. |


---


### setSufficientResolution {#setSufficientResolution}

| Name | Description |
| --- | --- |
| setSufficientResolution(float) | Returns or sets a value determining resolution of images inside PDF document. Read/write float. Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect. Property affects on file size, time of export and image quality. The default value is 96. |


---


### setTextCompression {#setTextCompression}

| Name | Description |
| --- | --- |
| setTextCompression(int) | Specifies compression type to be used for all textual content in the document. Read/write PdfTextCompression. Default is PdfTextCompression#Flate. |


---


### setWarningCallback {#setWarningCallback}

| Name | Description |
| --- | --- |
| setWarningCallback([IWarningCallback](../iwarningcallback)) | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |


---


