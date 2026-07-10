---
title: IPdfOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 提供控制演示文稿以 PDF 格式保存方式的选项。
type: docs
url: /zh/com.aspose.slides/ipdfoptions/
---
**所有已实现的接口：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

提供控制演示文稿以 PDF 格式保存的选项。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | 指定文档中所有文本内容使用的压缩类型。 |
| [setTextCompression(int value)](#setTextCompression-int-) | 指定文档中所有文本内容使用的压缩类型。 |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | 指示是否必须为每个图像自动选择最有效的压缩（而不是默认压缩）。 |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | 指示是否必须为每个图像自动选择最有效的压缩（而不是默认压缩）。 |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | 若为 true，则嵌入 ASCII 字符 32-127 的 TrueType 字体。 |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | 若为 true，则嵌入 ASCII 字符 32-127 的 TrueType 字体。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | 返回或设置 Aspose.Slides 应视为通用的用户自定义字体族名称数组。 |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | 返回或设置 Aspose.Slides 应视为通用的用户自定义字体族名称数组。 |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | 确定是嵌入字体的所有字符还是仅嵌入使用的子集。 |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | 确定是嵌入字体的所有字符还是仅嵌入使用的子集。 |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | 指示当字体不支持粗体样式时，是否应将文本光栅化为位图并保存为 PDF。 |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | 指示当字体不支持粗体样式时，是否应将文本光栅化为位图并保存为 PDF。 |
| [getJpegQuality()](#getJpegQuality--) | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。 |
| [getCompliance()](#getCompliance--) | 生成的 PDF 文档的期望合规等级。 |
| [setCompliance(int value)](#setCompliance-int-) | 生成的 PDF 文档的期望合规等级。 |
| [getPassword()](#getPassword--) | 设置用户密码以保护 PDF 文档。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 设置用户密码以保护 PDF 文档。 |
| [getAccessPermissions()](#getAccessPermissions--) | 包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。 |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | 包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 若为 true，则将演示文稿中使用的所有元文件转换为 PNG 图像。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 若为 true，则将演示文稿中使用的所有元文件转换为 PNG 图像。 |
| [getSufficientResolution()](#getSufficientResolution--) | 返回或设置决定 PDF 文档中图像分辨率的值。 |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | 返回或设置决定 PDF 文档中图像分辨率的值。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 若为 true，则在每张幻灯片周围绘制黑色框架。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 若为 true，则在每张幻灯片周围绘制黑色框架。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getImageTransparentColor()](#getImageTransparentColor--) | 获取或设置图像的透明颜色。 |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | 获取或设置图像的透明颜色。 |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | 如果为 true，则将指定的透明颜色应用于图像。 |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | 如果为 true，则将指定的透明颜色应用于图像。 |
| [getInkOptions()](#getInkOptions--) | 提供控制导出文档中 Ink 对象外观的选项。 |
| [getIncludeOleData()](#getIncludeOleData--) | 若为 true，则将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。 |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | 若为 true，则将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。 |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

指定文档中所有文本内容使用的压缩类型。可读写 [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

默认值为 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**返回值：**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

指定文档中所有文本内容使用的压缩类型。可读写 [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

默认值为 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

指示是否必须为每个图像自动选择最有效的压缩（而不是默认压缩）。如果设置为 true，则演示文稿中的每个图像将选择最合适的压缩算法，这将导致生成的 PDF 文档体积更小。

--------------------

最佳图像压缩比的选择计算成本高且会占用额外的内存，并且此选项默认值为 false。

--------------------

默认值为 false。

**返回值：**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

指示是否必须为每个图像自动选择最有效的压缩（而不是默认压缩）。如果设置为 true，则演示文稿中的每个图像将选择最合适的压缩算法，这将导致生成的 PDF 文档体积更小。

--------------------

最佳图像压缩比的选择计算成本高且会占用额外的内存，并且此选项默认值为 false。

--------------------

默认值为 false。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

若为 true，则嵌入 ASCII 字符 32-127 的 TrueType 字体。对于字符代码大于 127 的字体始终嵌入。可读写布尔值。

--------------------

默认值为 **true**。

**返回值：**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

若为 true，则嵌入 ASCII 字符 32-127 的 TrueType 字体。对于字符代码大于 127 的字体始终嵌入。可读写布尔值。

--------------------

默认值为 **true**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

指定生成的文档是否应包含隐藏幻灯片。默认值为 false。

**返回值：**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

指定生成的文档是否应包含隐藏幻灯片。默认值为 false。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

返回或设置 Aspose.Slides 应视为通用的用户自定义字体族名称数组。可读写 String[]。

**返回值：**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

返回或设置 Aspose.Slides 应视为通用的用户自定义字体族名称数组。可读写 String[]。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

确定是否应嵌入字体的所有字符还是仅嵌入使用的子集。可读写布尔值。

--------------------

默认值为 **false**。

**返回值：**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

确定是否应嵌入字体的所有字符还是仅嵌入使用的子集。可读写布尔值。

--------------------

默认值为 **false**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

指示当字体不支持粗体样式时，文本是否应光栅化为位图并保存为 PDF。此方法可以提升某些字体在生成的 PDF 中的文本质量。可读写布尔值。

--------------------

默认值为 **false**。

**返回值：**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

指示当字体不支持粗体样式时，文本是否应光栅化为位图并保存为 PDF。此方法可以提升某些字体在生成的 PDF 中的文本质量。可读写布尔值。

--------------------

默认值为 **false**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

返回或设置决定 PDF 文档中 JPEG 图像质量的值。可读写 byte。

--------------------

仅在文档包含 JPEG 图像时生效。

使用此属性在以 PDF 格式保存时获取或设置文档中图像的质量。该值范围为 0 到 100，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。

默认值为 **100**。

**返回值：**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

返回或设置决定 PDF 文档中 JPEG 图像质量的值。可读写 byte。

--------------------

仅在文档包含 JPEG 图像时生效。

使用此属性在以 PDF 格式保存时获取或设置文档中图像的质量。该值范围为 0 到 100，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。

默认值为 **100**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

生成的 PDF 文档的期望合规等级。可读写 [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

默认值为 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**返回值：**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

生成的 PDF 文档的期望合规等级。可读写 [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

默认值为 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

设置用户密码以保护 PDF 文档。可读写 String。

**返回值：**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

设置用户密码以保护 PDF 文档。可读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。参见 [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)。

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

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

Gets or sets the image transparent color.

Value: The color of the image transparent.

**Returns:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Gets or sets the image transparent color.

Value: The color of the image transparent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

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

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Provides options that control the look of Ink objects in exported document. Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returns:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
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
public abstract void setIncludeOleData(boolean value)

若为 true，则将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。可读写布尔值。

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
默认值为  **false** .

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |