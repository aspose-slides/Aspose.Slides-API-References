---
title: IPdfOptions
second_title: Aspose.Slides for Java API Reference
description: Provides options that control how a presentation is saved in Pdf format.
type: docs
weight: 962
url: /java/com.aspose.slides/ipdfoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Provides options that control how a presentation is saved in Pdf format.
## Methods

| Method | Description |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Specifies compression type to be used for all textual content in the document. |
| [setTextCompression(int value)](#setTextCompression-int-) | Specifies compression type to be used for all textual content in the document. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True to embed true type fonts for ASCII characters 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True to embed true type fonts for ASCII characters 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Determines if all characters of font should be embedded or only used subset. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Determines if all characters of font should be embedded or only used subset. |
| [getJpegQuality()](#getJpegQuality--) | Returns or sets a value determining the quality of the JPEG images inside PDF document. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Returns or sets a value determining the quality of the JPEG images inside PDF document. |
| [getCompliance()](#getCompliance--) | Desired conformance level for generated PDF document. |
| [setCompliance(int value)](#setCompliance-int-) | Desired conformance level for generated PDF document. |
| [getPassword()](#getPassword--) | Setting user password to protect the PDF document. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Setting user password to protect the PDF document. |
| [getAccessPermissions()](#getAccessPermissions--) | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True to convert all metafiles used in a presentation to the PNG images. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True to convert all metafiles used in a presentation to the PNG images. |
| [getSufficientResolution()](#getSufficientResolution--) | Returns or sets a value determining resolution of images inside PDF document. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Returns or sets a value determining resolution of images inside PDF document. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True to draw black frame around each slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True to draw black frame around each slide. |
| [getNotesCommentsLayouting()](#getNotesCommentsLayouting--) | Provides options that control how notes and comments is placed in exported document. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Gets or sets the image transparent color. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Gets or sets the image transparent color. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Applies the specified transparent color to an image if true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Applies the specified transparent color to an image if true. |
### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```


Specifies compression type to be used for all textual content in the document. Read/write [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Default is [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Returns:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```


Specifies compression type to be used for all textual content in the document. Read/write [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Default is [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```


Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document.

--------------------

Best image compression ratio selection is computationally expensive and takes an additional amount of RAM, and this option is false by default.

--------------------

Default is false.

**Returns:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```


Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document.

--------------------

Best image compression ratio selection is computationally expensive and takes an additional amount of RAM, and this option is false by default.

--------------------

Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```


True to embed true type fonts for ASCII characters 32-127. Fonts for character codes greater than 127 are always embedded. Read/write boolean.

--------------------

Default is **true**.

**Returns:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```


True to embed true type fonts for ASCII characters 32-127. Fonts for character codes greater than 127 are always embedded. Read/write boolean.

--------------------

Default is **true**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```


Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[].

**Returns:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```


Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```


Determines if all characters of font should be embedded or only used subset. Read/write boolean.

--------------------

Default is **false**.

**Returns:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```


Determines if all characters of font should be embedded or only used subset. Read/write boolean.

--------------------

Default is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```


Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte.

--------------------

Has effect only when a document contains JPEG images.

Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **100**.

**Returns:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```


Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write byte.

--------------------

Has effect only when a document contains JPEG images.

Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **100**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```


Desired conformance level for generated PDF document. Read/write [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Default is [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```


Desired conformance level for generated PDF document. Read/write [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Default is [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


Setting user password to protect the PDF document. Read/write String.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```


Setting user password to protect the PDF document. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```


Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```


Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```


True to convert all metafiles used in a presentation to the PNG images. Read/write boolean.

--------------------

Default is **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible.

**Returns:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```


True to convert all metafiles used in a presentation to the PNG images. Read/write boolean.

--------------------

Default is **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```


Returns or sets a value determining resolution of images inside PDF document. Read/write float.

Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect.

--------------------

Property affects on file size, time of export and image quality.

The default value is **96**.

**Returns:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```


Returns or sets a value determining resolution of images inside PDF document. Read/write float.

Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect.

--------------------

Property affects on file size, time of export and image quality.

The default value is **96**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```


True to draw black frame around each slide. Read/write boolean.

--------------------

Default is **false**.

**Returns:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```


True to draw black frame around each slide. Read/write boolean.

--------------------

Default is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNotesCommentsLayouting() {#getNotesCommentsLayouting--}
```
public abstract INotesCommentsLayoutingOptions getNotesCommentsLayouting()
```


Provides options that control how notes and comments is placed in exported document.

**Returns:**
[INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions)
### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Color getImageTransparentColor()
```


Gets or sets the image transparent color.

Value: The color of the image transparent.

**Returns:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```


Gets or sets the image transparent color.

Value: The color of the image transparent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```


Applies the specified transparent color to an image if true.

**Returns:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```


Applies the specified transparent color to an image if true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

