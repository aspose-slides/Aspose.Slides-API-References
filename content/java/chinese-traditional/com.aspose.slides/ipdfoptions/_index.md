---
title: IPdfOptions
second_title: Aspose.Slides for Java API 參考
description: 提供控制演示文稿以 PDF 格式保存的選項。
type: docs
url: /zh-hant/com.aspose.slides/ipdfoptions/
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
| [getTextCompression()](#getTextCompression--) | 指定文件中所有文字内容使用的压缩类型。 |
| [setTextCompression(int value)](#setTextCompression-int-) | 指定文件中所有文字内容使用的压缩类型。 |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | 指示是否必须自动为每个图像选择最有效的压缩（而非默认压缩）。 |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | 指示是否必须自动为每个图像选择最有效的压缩（而非默认压缩）。 |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | 設定為 True 以嵌入 ASCII 字元 32-127 的 TrueType 字型。 |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | 設定為 True 以嵌入 ASCII 字元 32-127 的 TrueType 字型。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文件是否应包含隐藏幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文件是否应包含隐藏幻灯片。 |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | 返回或设置一个字符串数组，包含用户自定义的字体族名称，Aspose.Slides 应将其视为通用字体。 |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | 返回或设置一个字符串数组，包含用户自定义的字体族名称，Aspose.Slides 应将其视为通用字体。 |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | 确定是嵌入字体的所有字符还是仅嵌入使用的子集。 |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | 确定是嵌入字体的所有字符还是仅嵌入使用的子集。 |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | 指示当字体不支持粗体样式时，文本是否应以位图形式栅格化并保存为 PDF。 |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | 指示当字体不支持粗体样式时，文本是否应以位图形式栅格化并保存为 PDF。 |
| [getJpegQuality()](#getJpegQuality--) | 返回或设置决定 PDF 文档内 JPEG 图像质量的值。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | 返回或设置决定 PDF 文档内 JPEG 图像质量的值。 |
| [getCompliance()](#getCompliance--) | 生成的 PDF 文档的期望符合级别。 |
| [setCompliance(int value)](#setCompliance-int-) | 生成的 PDF 文档的期望符合级别。 |
| [getPassword()](#getPassword--) | 设置用户密码以保护 PDF 文档。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 设置用户密码以保护 PDF 文档。 |
| [getAccessPermissions()](#getAccessPermissions--) | 包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。 |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | 包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 設定為 True 以将演示文稿中使用的所有元文件转换为 PNG 图像。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 設定為 True 以将演示文稿中使用的所有元文件转换为 PNG 图像。 |
| [getSufficientResolution()](#getSufficientResolution--) | 返回或设置决定 PDF 文档内图像分辨率的值。 |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | 返回或设置决定 PDF 文档内图像分辨率的值。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 設定為 True 以在每张幻灯片周围绘制黑色框。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 設定為 True 以在每张幻灯片周围绘制黑色框。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getImageTransparentColor()](#getImageTransparentColor--) | 获取或设置图像的透明颜色。 |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | 获取或设置图像的透明颜色。 |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | 如果为 True，则将指定的透明颜色应用于图像。 |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | 如果为 True，则将指定的透明颜色应用于图像。 |
| [getInkOptions()](#getInkOptions--) | 提供控制导出文档中 Ink 对象外观的选项。 |
| [getIncludeOleData()](#getIncludeOleData--) | 設定為 True 将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。 |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | 設定為 True 将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。 |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

指定文件中所有文字内容使用的压缩类型。讀寫 [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

預設值為 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**返回：**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

指定文件中所有文字内容使用的压缩类型。讀寫 [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

預設值為 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

指示是否必须自动为每个图像选择最有效的压缩（而非默认压缩）。如果设为 True，则演示文稿中的每个图像都会选择最合适的压缩算法，从而使生成的 PDF 文档体积更小。

--------------------

最佳图像压缩比的选择计算成本高且会占用额外的内存，默认情况下此选项为 False。

--------------------

預設值為 False。

**返回：**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

指示是否必须自动为每个图像选择最有效的压缩（而非默认压缩）。如果设为 True，则演示文稿中的每个图像都会选择最合适的压缩算法，从而使生成的 PDF 文档体积更小。

--------------------

最佳图像压缩比的选择计算成本高且会占用额外的内存，默认情况下此选项为 False。

--------------------

預設值為 False。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

設定為 True 以嵌入 ASCII 字元 32-127 的 TrueType 字型。字元代码大于 127 的字型始终嵌入。讀寫 boolean。

--------------------

預設值為 **true**。

**返回：**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

設定為 True 以嵌入 ASCII 字元 32-127 的 TrueType 字型。字元代码大于 127 的字型始终嵌入。讀寫 boolean。

--------------------

預設值為 **true**。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

指定生成的文件是否应包含隐藏幻灯片。預設值為 False。

**返回：**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

指定生成的文件是否应包含隐藏幻灯片。預設值為 False。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

返回或设置一个字符串数组，包含用户自定义的字体族名称，Aspose.Slides 应将其视为通用字体。讀寫 String[]。

**返回：**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

返回或设置一个字符串数组，包含用户自定义的字体族名称，Aspose.Slides 应将其视为通用字体。讀寫 String[]。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

確定是嵌入字体的所有字符还是仅嵌入使用的子集。讀寫 boolean。

--------------------

預設值為 **false**。

**返回：**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

確定是嵌入字体的所有字符还是仅嵌入使用的子集。讀寫 boolean。

--------------------

預設值為 **false**。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

指示当字体不支持粗体样式时，文本是否应以位图形式栅格化并保存为 PDF。这种做法可以提升某些字体在生成的 PDF 中的文本质量。讀寫 boolean。

--------------------

預設值為 **false**。

**返回：**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

指示当字体不支持粗体样式时，文本是否应以位图形式栅格化并保存为 PDF。这种做法可以提升某些字体在生成的 PDF 中的文本质量。讀寫 boolean。

--------------------

預設值為 **false**。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

返回或设置决定 PDF 文档内 JPEG 图像质量的值。讀寫 byte。

--------------------

仅在文档包含 JPEG 图像时生效。

使用此属性可在以 PDF 格式保存文档时获取或设置图像的质量。取值范围为 0 到 100，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。

預設值為 **100**。

**返回：**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

返回或设置决定 PDF 文档内 JPEG 图像质量的值。讀寫 byte。

--------------------

仅在文档包含 JPEG 图像时生效。

使用此属性可在以 PDF 格式保存文档时获取或设置图像的质量。取值范围为 0 到 100，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。

預設值為 **100**。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

生成的 PDF 文档的期望符合级别。讀寫 [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

預設值為 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**返回：**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

生成的 PDF 文档的期望符合级别。讀寫 [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

預設值為 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

设置用户密码以保护 PDF 文档。讀寫 String。

**返回：**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

设置用户密码以保护 PDF 文档。讀寫 String。

**參數：**
| 參數 | 類型 | 描述 |
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

**返回：**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
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

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

設定為 True 以将演示文稿中使用的所有元文件转换为 PNG 图像。讀寫 boolean。

--------------------

預設值為 **true**。Pdf 文档可以包含矢量图形和光栅图像。如果 SaveMetafilesAsPng 设置为 true，则源元文件图像会转换为 PNG 格式并作为光栅图像保存到 Pdf。如果 SaveMetafilesAsPng 设置为 false，则源元文件会转换为 Pdf 矢量图形。两种方式各有优缺点。例如，转换为 PNG 可能在文档缩放时导致一定的质量损失；转换为 Pdf 矢量图形可能导致 Pdf 查看工具的性能问题。

**返回：**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

設定為 True 以将演示文稿中使用的所有元文件转换为 PNG 图像。讀寫 boolean。

--------------------

預設值為 **true**。Pdf 文档可以包含矢量图形和光栅图像。如果 SaveMetafilesAsPng 设置为 true，则源元文件图像会转换为 PNG 格式并作为光栅图像保存到 Pdf。如果 SaveMetafilesAsPng 设置为 false，则源元文件会转换为 Pdf 矢量图形。两种方式各有优缺点。例如，转换为 PNG 可能在文档缩放时导致一定的质量损失；转换为 Pdf 矢量图形可能导致 Pdf 查看工具的性能问题。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

返回或设置决定 PDF 文档内图像分辨率的值。讀寫 float。

值：此参数的效果取决于多个因素。算法会根据属性值、源图像大小以及图像框大小尝试获得最佳输出图像尺寸。使用相似的属性值可能会得到相同的结果。建议使用 16 或 32 的步长以获得可见效果。

--------------------

属性会影响文件大小、导出时间和图像质量。

預設值為 **96**。

**返回：**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

返回或设置决定 PDF 文档内图像分辨率的值。讀寫 float。

值：此参数的效果取决于多个因素。算法会根据属性值、源图像大小以及图像框大小尝试获得最佳输出图像尺寸。使用相似的属性值可能会得到相同的结果。建议使用 16 或 32 的步长以获得可见效果。

--------------------

属性会影响文件大小、导出时间和图像质量。

預設值為 **96**。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

設定為 True 以在每张幻灯片周围绘制黑色框。讀寫 boolean。

--------------------

預設值為 **false**。

**返回：**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

設定為 True 以在每张幻灯片周围绘制黑色框。讀寫 boolean。

--------------------

預設值為 **false**。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

获取或设置导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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

**返回：**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

获取或设置导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Color getImageTransparentColor()
```

获取或设置图像的透明颜色。

值：图像的透明颜色。

**返回：**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

获取或设置图像的透明颜色。

值：图像的透明颜色。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

如果为 True，则将指定的透明颜色应用于图像。

**返回：**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

如果为 True，则将指定的透明颜色应用于图像。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

提供控制导出文档中 Ink 对象外观的选项。唯讀 [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回：**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

設定為 True 将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。讀寫 boolean 。

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

預設值為  **false** 。

**返回：**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

設定為 True 将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。讀寫 boolean 。

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

預設值為  **false** 。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |