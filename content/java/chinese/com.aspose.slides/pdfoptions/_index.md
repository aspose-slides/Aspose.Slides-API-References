---
title: PdfOptions
second_title: Aspose.Slides for Java API 参考
description: 提供控制演示文稿以 PDF 格式保存的选项。
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

提供控制演示文稿以 PDF 格式保存的选项。

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // 实例化 PdfOptions 类
>      PdfOptions pdfOptions = new PdfOptions();
>      // 设置 JPEG 质量
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
>  // 实例化表示演示文件的 Presentation 对象
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // 设置幻灯片类型和尺寸
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

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | 默认构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getInkOptions()](#getInkOptions--) | 提供控制导出文档中 Ink 对象外观的选项。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [getTextCompression()](#getTextCompression--) | 指定文档中所有文本内容使用的压缩类型。 |
| [setTextCompression(int value)](#setTextCompression-int-) | 指定文档中所有文本内容使用的压缩类型。 |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | 指示是否应自动为每个图像选择最有效的压缩（而不是默认压缩）。 |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | 指示是否应自动为每个图像选择最有效的压缩（而不是默认压缩）。 |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | 确定 Aspose.Slides 是否会嵌入 ASCII（33..127 代码范围）文本的常用字体。 |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | 确定 Aspose.Slides 是否会嵌入 ASCII（33..127 代码范围）文本的常用字体。 |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | 获取或设置 Aspose.Slides 应视为常用的用户自定义字体族名称数组。 |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | 获取或设置 Aspose.Slides 应视为常用的用户自定义字体族名称数组。 |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | 确定是否应嵌入字体的全部字符或仅使用子集。 |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | 确定是否应嵌入字体的全部字符或仅使用子集。 |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | 指示当字体不支持粗体样式时，文本是否应光栅化为位图并保存为 PDF。 |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | 指示当字体不支持粗体样式时，文本是否应光栅化为位图并保存为 PDF。 |
| [getJpegQuality()](#getJpegQuality--) | 获取或设置决定 PDF 文档中 JPEG 图像质量的数值。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | 获取或设置决定 PDF 文档中 JPEG 图像质量的数值。 |
| [getCompliance()](#getCompliance--) | 生成的 PDF 文档所需的合规级别。 |
| [setCompliance(int value)](#setCompliance-int-) | 生成的 PDF 文档所需的合规级别。 |
| [getPassword()](#getPassword--) | 设置用户密码以保护 PDF 文档。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 设置用户密码以保护 PDF 文档。 |
| [getAccessPermissions()](#getAccessPermissions--) | 包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。 |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | 包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。 |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 为 true 时将演示文稿中使用的所有元文件转换为 PNG 图像。 |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 为 true 时将演示文稿中使用的所有元文件转换为 PNG 图像。 |
| [getSufficientResolution()](#getSufficientResolution--) | 获取或设置决定 PDF 文档中图像分辨率的数值。 |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | 获取或设置决定 PDF 文档中图像分辨率的数值。 |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 为 true 时在每个幻灯片周围绘制黑色框架。 |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 为 true 时在每个幻灯片周围绘制黑色框架。 |
| [getImageTransparentColor()](#getImageTransparentColor--) | 获取或设置图像的透明颜色。 |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | 获取或设置图像的透明颜色。 |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | 若为 true，则将指定的透明颜色应用于图像。 |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | 若为 true，则将指定的透明颜色应用于图像。 |
| [getIncludeOleData()](#getIncludeOleData--) | 为 true 时将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。 |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | 为 true 时将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。 |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

默认构造函数。

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

提供控制导出文档中 Ink 对象外观的选项。**只读** [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回：**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

指定生成的文档是否应包含隐藏幻灯片。默认值为 false。

**返回：**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

指定生成的文档是否应包含隐藏幻灯片。默认值为 false。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

指定文档中所有文本内容使用的压缩类型。**读写** [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

默认值为 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**返回：**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

指定文档中所有文本内容使用的压缩类型。**读写** [PdfTextCompression](../../com.aspose.slides/pdftextcompression)。

--------------------

默认值为 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

指示是否应自动为每个图像选择最有效的压缩（而不是默认压缩）。如果设置为 true，则针对演示文稿中的每个图像将选择最合适的压缩算法，从而减小生成的 PDF 文档的大小。

--------------------

最佳图像压缩比选择计算量大且会占用额外的内存，默认情况下此选项为 false。

--------------------

默认值为 false。

**返回：**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

指示是否应自动为每个图像选择最有效的压缩（而不是默认压缩）。如果设置为 true，则针对演示文稿中的每个图像将选择最合适的压缩算法，从而减小生成的 PDF 文档的大小。

--------------------

最佳图像压缩比选择计算量大且会占用额外的内存，默认情况下此选项为 false。

--------------------

默认值为 false。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

确定 Aspose.Slides 是否会嵌入 ASCII（33..127 代码范围）文本的常用字体。代码大于 127 的字符始终嵌入。常用字体列表包括 PDF 的基本 14 种字体以及用户指定的附加字体。**读写** boolean。

--------------------

默认值为 **true**。

**返回：**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

确定 Aspose.Slides 是否会嵌入 ASCII（33..127 代码范围）文本的常用字体。代码大于 127 的字符始终嵌入。常用字体列表包括 PDF 的基本 14 种字体以及用户指定的附加字体。**读写** boolean。

--------------------

默认值为 **true**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

获取或设置 Aspose.Slides 应视为常用的用户自定义字体族名称数组。**读写** String[]。

**返回：**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

获取或设置 Aspose.Slides 应视为常用的用户自定义字体族名称数组。**读写** String[]。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

确定是否应嵌入字体的全部字符或仅使用子集。**读写** boolean。

--------------------

默认值为 **false**。

**返回：**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

确定是否应嵌入字体的全部字符或仅使用子集。**读写** boolean。

--------------------

默认值为 **false**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

指示当字体不支持粗体样式时，文本是否应光栅化为位图并保存为 PDF。此方法可在某些字体下提升 PDF 中文本的质量。**读写** boolean。

--------------------

默认值为 **false**。

**返回：**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

指示当字体不支持粗体样式时，文本是否应光栅化为位图并保存为 PDF。此方法可在某些字体下提升 PDF 中文本的质量。**读写** boolean。

--------------------

默认值为 **false**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

获取或设置决定 PDF 文档中 JPEG 图像质量的数值。**读写** byte。

--------------------

仅当文档包含 JPEG 图像时生效。

使用此属性可在以 PDF 格式保存文档时获取或设置图像的质量。取值范围为 0 到 100，0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。

默认值为 **100**。

**返回：**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

获取或设置决定 PDF 文档中 JPEG 图像质量的数值。**读写** byte。

--------------------

仅当文档包含 JPEG 图像时生效。

使用此属性可在以 PDF 格式保存文档时获取或设置图像的质量。取值范围为 0 到 100，0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。

默认值为 **100**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

生成的 PDF 文档所需的合规级别。**读写** [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

默认值为 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**返回：**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

生成的 PDF 文档所需的合规级别。**读写** [PdfCompliance](../../com.aspose.slides/pdfcompliance)。

--------------------

默认值为 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

设置用户密码以保护 PDF 文档。**读写** String。

**返回：**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

设置用户密码以保护 PDF 文档。**读写** String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
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
public final void setAccessPermissions(int value)
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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

为 true 时将演示文稿中使用的所有元文件转换为 PNG 图像。**读写** boolean。

--------------------

默认值为 **true**。Pdf 文档可以包含矢量图形和光栅图像。如果 SaveMetafilesAsPng 设置为 true，则源元文件图像将转换为 PNG 格式并作为光栅图像保存到 Pdf 中；如果设置为 false，则源元文件将转换为 Pdf 矢量图形。两种方式各有优缺点。例如，将元文件转换为 PNG 时，在文档缩放过程中可能会出现质量损失；将元文件转换为 Pdf 矢量图形时，Pdf 查看工具可能出现性能问题。

**返回：**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

为 true 时将演示文稿中使用的所有元文件转换为 PNG 图像。**读写** boolean。

--------------------

默认值为 **true**。Pdf 文档可以包含矢量图形和光栅图像。如果 SaveMetafilesAsPng 设置为 true，则源元文件图像将转换为 PNG 格式并作为光栅图像保存到 Pdf 中；如果设置为 false，则源元文件将转换为 Pdf 矢量图形。两种方式各有优缺点。例如，将元文件转换为 PNG 时，在文档缩放过程中可能会出现质量损失；将元文件转换为 Pdf 矢量图形时，Pdf 查看工具可能出现性能问题。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

获取或设置决定 PDF 文档中图像分辨率的数值。**读写** float。

值：此参数的效果取决于多个因素。算法会根据属性值、源图像大小和图像框大小来获取最佳输出图像尺寸。使用相似的属性值可能得到相同的结果。建议使用 16 或 32 的步长以获得可见效果。

--------------------

属性会影响文件大小、导出时间和图像质量。

默认值为 **96**。

**返回：**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

获取或设置决定 PDF 文档中图像分辨率的数值。**读写** float。

值：此参数的效果取决于多个因素。算法会根据属性值、源图像大小和图像框大小来获取最佳输出图像尺寸。使用相似的属性值可能得到相同的结果。建议使用 16 或 32 的步长以获得可见效果。

--------------------

属性会影响文件大小、导出时间和图像质量。

默认值为 **96**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

为 true 时在每个幻灯片周围绘制黑色框架。**读写** boolean。

--------------------

默认值为 **false**。

**返回：**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

为 true 时在每个幻灯片周围绘制黑色框架。**读写** boolean。

--------------------

默认值为 **false**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

获取或设置图像的透明颜色。

值：图像透明的颜色。

**返回：**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

获取或设置图像的透明颜色。

值：图像透明的颜色。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

若为 true，则将指定的透明颜色应用于图像。

**返回：**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

若为 true，则将指定的透明颜色应用于图像。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

为 true 时将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。**读写**  boolean 。

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

默认值为  **false** 。

**返回：**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

为 true 时将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。**读写**  boolean 。

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

默认值为  **false** 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |