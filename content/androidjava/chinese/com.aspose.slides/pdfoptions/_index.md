---
title: PdfOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 提供用于控制演示文稿以 Pdf 格式保存的选项。
type: docs
url: /zh/com.aspose.slides/pdfoptions/
---
**继承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有实现的接口：**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

提供用于控制演示文稿以 Pdf 格式保存的选项。

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // 实例化 PdfOptions 类
>      PdfOptions pdfOptions = new PdfOptions();
>      // 设置 Jpeg 质量
>      pdfOptions.setJpegQuality((byte)90);
>      // 设置元文件的行为
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // 设置文本压缩级别
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // 定义 PDF 标准
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // 将演示文稿保存为 PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // 实例化表示 PowerPoint 文件的 Presentation 类
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // 实例化 PdfOptions 类
>      PdfOptions pdfOptions = new PdfOptions();
>      // 添加隐藏幻灯片
>      pdfOptions.setShowHiddenSlides(true);
>      // 将演示文稿保存为 PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // 实例化表示 PowerPoint 文件的 Presentation 对象
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // 实例化 PdfOptions 类
>      PdfOptions pdfOptions = new PdfOptions();
>      // 设置 PDF 密码和访问权限
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // 将演示文稿保存为 PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // 实例化表示演示文稿文件的 Presentation 对象
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // 设置幻灯片类型和大小
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Default constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Provides options that control the look of Ink objects in exported document. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getTextCompression()](#getTextCompression--) | Specifies compression type to be used for all textual content in the document. |
| [setTextCompression(int value)](#setTextCompression-int-) | Specifies compression type to be used for all textual content in the document. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Determines if all characters of font should be embedded or only used subset. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Determines if all characters of font should be embedded or only used subset. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indicates whether text should be rasterized as a bitmap and saved to PDF when the font does not support bold styling. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indicates whether text should be rasterized as a bitmap and saved to PDF when the font does not support bold styling. |
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
| [getImageTransparentColor()](#getImageTransparentColor--) | Gets or sets the image transparent color. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Gets or sets the image transparent color. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Applies the specified transparent color to an image if true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Applies the specified transparent color to an image if true. |
| [getIncludeOleData()](#getIncludeOleData--) | True to convert all OLE data from the presentation to embedded files in the resulting PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True to convert all OLE data from the presentation to embedded files in the resulting PDF. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Default constructor.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Provides options that control the look of Ink objects in exported document. Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returns:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Specifies compression type to be used for all textual content in the document. Read/write [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Default is [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Returns:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
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
public final boolean getBestImagesCompressionRatio()
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
public final void setBestImagesCompressionRatio(boolean value)
```

Indicates if the most effective compression (instead

...

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. Fonts for character codes greater than 127 are always embedded. Common fonts list includes PDF's base 14 fonts and additional user specified fonts. Read/write boolean.

--------------------

Default is **true**.

**Returns:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

确定 Aspose.Slides 是否会为 ASCII（33..127 代码范围）文本嵌入常用字体。字符代码大于 127 的字体始终会被嵌入。常用字体列表包括 PDF 的基本 14 种字体以及用户指定的其他字体。Read/write boolean.

--------------------

Default is **true**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```
Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[].

**Returns:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```
Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```
Determines if all characters of font should be embedded or only used subset. Read/write boolean.

--------------------

Default is **false**.

**Returns:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Determines if all characters of font should be embedded or only used subset. Read/write boolean.

--------------------

Default is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Indicates whether text should be rasterized as a bitmap and saved to PDF when the font does not support bold styling. This approach can enhance the quality of text in the resulting PDF for certain fonts. Read/write boolean.

--------------------

Default is **false**.

**Returns:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Indicates whether text should be rasterized as a bitmap and saved to PDF when the font does not support bold styling. This approach can enhance the quality of text in the resulting PDF for certain fonts. Read/write boolean.

--------------------

Default is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
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
public final void setJpegQuality(byte value)
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
public final int getCompliance()
```

Desired conformance level for generated PDF document. Read/write [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Default is [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
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
public final String getPassword()
```


Setting user password to protect the PDF document. Read/write String.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Setting user password to protect the PDF document. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
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
public final void setAccessPermissions(int value)
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
public final boolean getSaveMetafilesAsPng()
```
 
True to convert all metafiles used in a presentation to the PNG images. Read/write boolean.

--------------------

Default is **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible.

**Returns:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
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
public final float getSufficientResolution()
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
public final void setSufficientResolution(float value)
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
public final boolean getDrawSlidesFrame()
```

True to draw black frame around each slide. Read/write boolean.

--------------------

Default is **false**.

**Returns:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


True to draw black frame around each slide. Read/write boolean.

--------------------

Default is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

Gets or sets the image transparent color.

Value: The color of the image transparent.

**Returns:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

Gets or sets the image transparent color.

Value: The color of the image transparent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```


Applies the specified transparent color to an image if true.

**Returns:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Applies the specified transparent color to an image if true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```
 
True to convert all OLE data from the presentation to embedded files in the resulting PDF. Read/write  boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Default is  **false** .

**Returns:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)


将所有 OLE 数据从演示文稿转换为生成的 PDF 中的嵌入文件。读/写  boolean 。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

默认是  **false** 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |