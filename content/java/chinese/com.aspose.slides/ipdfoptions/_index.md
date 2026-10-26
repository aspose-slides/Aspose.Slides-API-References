---
title: IPdfOptions
second_title: Aspose.Slides for Java API 参考
description: 提供控制演示文稿以 PDF 格式保存方式的选项。
type: docs
url: /zh/com.aspose.slides/ipdfoptions/
---
**所有实现的接口：**
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
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | 指示是否应自动为每个图像选择最有效的压缩（而非默认压缩）。 |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | 指示是否应自动为每个图像选择最有效的压缩（而非默认压缩）。 |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | 设置为 true 时，将嵌入 ASCII 字符 32-127 的 TrueType 字体。 |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | 设置为 true 时，将嵌入 ASCII 字符 32-127 的 TrueType 字体。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | 返回或设置 Aspose.Slides 应视为通用的、用户定义的字体族名称数组。 |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | 返回或设置 Aspose.Slides 应视为通用的、用户定义的字体族名称数组。 |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | 确定是嵌入字体的所有字符还是仅嵌入使用的子集。 |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | 确定是嵌入字体的所有字符还是仅嵌入使用的子集。 |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | 指示当字体不支持粗体样式时，文本是否应栅格化为位图并保存为 PDF。 |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | 指示当字体不支持粗体样式时，文本是否应栅格化为位图并保存为 PDF。 |
| [getJpegQuality()](#getJpegQuality--) | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。 |
| [getCompliance()](#getCompliance--) | 生成的 PDF 文档所需的合规级别。 |
| [setCompliance(int value)](#setCompliance-int-) | 生成的 PDF 文档所需的合规级别。 |
| [getPassword()](#getPassword--) | 设置用户密码以保护 PDF 文档。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 设置用户密码以保护 PDF 文档。 |
| [getAccessPermissions()](#getAccessPermissions--) | 包含一组标志，指定在以用户访问打开文档时应授予的访问权限。 |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | 包含一组标志，指定在以用户访问打开文档时应授予的访问权限。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 设置为 true 时，将演示文稿中使用的所有元文件转换为 PNG 图像。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 设置为 true 时，将演示文稿中使用的所有元文件转换为 PNG 图像。 |
| [getSufficientResolution()](#getSufficientResolution--) | 返回或设置决定 PDF 文档中图像分辨率的值。 |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | 返回或设置决定 PDF 文档中图像分辨率的值。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 设置为 true 时，在每张幻灯片周围绘制黑色框架。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 设置为 true 时，在每张幻灯片周围绘制黑色框架。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置导出演示文稿时幻灯片在页面上的布局模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置导出演示文稿时幻灯片在页面上的布局模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getImageTransparentColor()](#getImageTransparentColor--) | 获取或设置图像的透明颜色。 |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | 获取或设置图像的透明颜色。 |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | 如果为 true，则将指定的透明颜色应用于图像。 |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | 如果为 true，则将指定的透明颜色应用于图像。 |
| [getInkOptions()](#getInkOptions--) | 提供控制导出文档中 Ink 对象外观的选项。 |
| [getIncludeOleData()](#getIncludeOleData--) | 设置为 true 时，将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。 |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | 设置为 true 时，将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。 |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

指定文档中所有文本内容使用的压缩类型。 可读写 [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

默认是 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**返回值：**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

指定文档中所有文本内容使用的压缩类型。 可读写 [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

默认是 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

指示是否应自动为每个图像选择最有效的压缩（而非默认压缩）。如果设置为 true，则演示文稿中的每个图像都会选择最合适的压缩算法，从而降低生成的 PDF 文档的大小。

--------------------

最佳图像压缩比例的选择计算量大且会占用额外的内存，默认情况下此选项为 false。

--------------------

默认是 false。

**返回值：**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

指示是否应自动为每个图像选择最有效的压缩（而非默认压缩）。如果设置为 true，则演示文稿中的每个图像都会选择最合适的压缩算法，从而降低生成的 PDF 文档的大小。

--------------------

最佳图像压缩比例的选择计算量大且会占用额外的内存，默认情况下此选项为 false。

--------------------

默认是 false。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

设置为 true 时，将嵌入 ASCII 字符 32-127 的 TrueType 字体。字符代码大于 127 的字体始终嵌入。 可读写 boolean。

--------------------

默认是 **true**。

**返回值：**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

设置为 true 时，将嵌入 ASCII 字符 32-127 的 TrueType 字体。字符代码大于 127 的字体始终嵌入。 可读写 boolean。

--------------------

默认是 **true**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

指定生成的文档是否应包含隐藏幻灯片。默认是 false。

**返回值：**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

指定生成的文档是否应包含隐藏幻灯片。默认是 false。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

返回或设置 Aspose.Slides 应视为通用的、用户定义的字体族名称数组。 可读写 String[]。

**返回值：**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

返回或设置 Aspose.Slides 应视为通用的、用户定义的字体族名称数组。 可读写 String[]。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

确定是嵌入字体的所有字符还是仅嵌入使用的子集。 可读写 boolean。

--------------------

默认是 **false**。

**返回值：**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

确定是嵌入字体的所有字符还是仅嵌入使用的子集。 可读写 boolean。

--------------------

默认是 **false**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

指示当字体不支持粗体样式时，文本是否应栅格化为位图并保存为 PDF。此方法可在某些字体下提升生成 PDF 的文本质量。 可读写 boolean。

--------------------

默认是 **false**。

**返回值：**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

指示当字体不支持粗体样式时，文本是否应栅格化为位图并保存为 PDF。此方法可在某些字体下提升生成 PDF 的文本质量。 可读写 boolean。

--------------------

默认是 **false**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

返回或设置决定 PDF 文档中 JPEG 图像质量的值。 可读写 byte。

--------------------

仅在文档包含 JPEG 图像时生效。

使用此属性在保存为 PDF 时获取或设置文档中图像的质量。取值范围为 0 到 100，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。

默认值为 **100**。

**返回值：**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

返回或设置决定 PDF 文档中 JPEG 图像质量的值。 可读写 byte。

--------------------

仅在文档包含 JPEG 图像时生效。

使用此属性在保存为 PDF 时获取或设置文档中图像的质量。取值范围为 0 到 100，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。

默认值为 **100**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

生成的 PDF 文档所需的合规级别。 可读写 [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

默认是 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**返回值：**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

生成的 PDF 文档所需的合规级别。 可读写 [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

默认是 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

设置用户密码以保护 PDF 文档。 可读写 String。

**返回值：**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

设置用户密码以保护 PDF 文档。 可读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

包含一组标志，指定在以用户访问打开文档时应授予的访问权限。参见 [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)。

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

**返回值：**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

包含一组标志，指定在以用户访问打开文档时应授予的访问权限。参见 [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

设置为 true 时，将演示文稿中使用的所有元文件转换为 PNG 图像。 可读写 boolean。

--------------------

默认是 **true**。Pdf 文档可以包含矢量图形和栅格图像。如果 SaveMetafilesAsPng 设置为 true，则源元文件图像将转换为 PNG 格式并作为栅格图像保存到 Pdf。如果 SaveMetafilesAsPng 设置为 false，则源元文件将转换为 Pdf 矢量图形。每种方式都有优缺点。例如，元文件转换为 PNG 时，在文档缩放过程中可能出现质量损失；转换为 Pdf 矢量图形时，Pdf 查看工具可能出现性能问题。

**返回值：**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

设置为 true 时，将演示文稿中使用的所有元文件转换为 PNG 图像。 可读写 boolean。

--------------------

默认是 **true**。Pdf 文档可以包含矢量图形和栅格图像。如果 SaveMetafilesAsPng 设置为 true，则源元文件图像将转换为 PNG 格式并作为栅格图像保存到 Pdf。如果 SaveMetafilesAsPng 设置为 false，则源元文件将转换为 Pdf 矢量图形。每种方式都有优缺点。例如，元文件转换为 PNG 时，在文档缩放过程中可能出现质量损失；转换为 Pdf 矢量图形时，Pdf 查看工具可能出现性能问题。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

返回或设置决定 PDF 文档中图像分辨率的值。 可读写 float。

值：此参数的效果取决于多个因素。算法会根据属性值、源图像尺寸和图像框尺寸来获取最佳输出图像大小。使用相似的属性值可能得到相同结果。建议使用 16 或 32 的步长以获得可见效果。

--------------------

属性影响文件大小、导出时间和图像质量。

默认值为 **96**。

**返回值：**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

返回或设置决定 PDF 文档中图像分辨率的值。 可读写 float。

值：此参数的效果取决于多个因素。算法会根据属性值、源图像尺寸和图像框尺寸来获取最佳输出图像大小。使用相似的属性值可能得到相同结果。建议使用 16 或 32 的步长以获得可见效果。

--------------------

属性影响文件大小、导出时间和图像质量。

默认值为 **96**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

设置为 true 时，在每张幻灯片周围绘制黑色框架。 可读写 boolean。

--------------------

默认是 **false**。

**返回值：**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

设置为 true 时，在每张幻灯片周围绘制黑色框架。 可读写 boolean。

--------------------

默认是 **false**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

获取或设置导出演示文稿时幻灯片在页面上的布局模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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


**返回值：**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

获取或设置导出演示文稿时幻灯片在页面上的布局模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> 示例：
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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Color getImageTransparentColor()
```

获取或设置图像的透明颜色。

值：图像的透明颜色。

**返回值：**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

获取或设置图像的透明颜色。

值：图像的透明颜色。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

如果为 true，则将指定的透明颜色应用于图像。

**返回值：**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

如果为 true，则将指定的透明颜色应用于图像。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

提供控制导出文档中 Ink 对象外观的选项。 只读 [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回值：**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

设置为 true 时，将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。 可读写 boolean 。

--------------------

> ```
> 示例：
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

默认是 **false**。

**返回值：**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

设置为 true 时，将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。 可读写 boolean 。

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

默认是 **false**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |