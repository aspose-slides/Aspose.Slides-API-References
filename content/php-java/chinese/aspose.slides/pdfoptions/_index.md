---
title: PdfOptions
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/pdfoptions/
---
## PdfOptions 类

提供控制演示文稿以 Pdf 格式保存方式的选项。

### PdfOptions {#PdfOptions}

| 名称 | 描述 |
| --- | --- |
| PdfOptions() | 默认函数。 |

**返回：**  
PdfOptions


---


### getAccessPermissions {#getAccessPermissions}

| 名称 | 描述 |
| --- | --- |
| getAccessPermissions () | 包含一组标志，指定在以用户访问权限打开文档时应授予的访问权限。参见 PdfAccessPermissions。 |

**返回：**  
int


---


### getAdditionalCommonFontFamilies {#getAdditionalCommonFontFamilies}

| 名称 | 描述 |
| --- | --- |
| getAdditionalCommonFontFamilies () | 返回或设置 Aspose.Slides 应视为通用的字体系列的用户自定义名称数组。读/写 String[]. |

**返回：**  
String


---


### getApplyImageTransparent {#getApplyImageTransparent}

| 名称 | 描述 |
| --- | --- |
| getApplyImageTransparent () | True 将指定的透明颜色应用于图像。 |

**返回：**  
boolean


---


### getBestImagesCompressionRatio {#getBestImagesCompressionRatio}

| 名称 | 描述 |
| --- | --- |
| getBestImagesCompressionRatio () | 指示是否应自动为每个图像选择最有效的压缩（而非默认压缩）。如果设置为 true，则为演示文稿中的每个图像选择最合适的压缩算法，从而使生成的 PDF 文档体积更小。最佳图像压缩比的选择计算量大且占用额外内存，默认值为 false。 |

**返回：**  
boolean


---


### getCompliance {#getCompliance}

| 名称 | 描述 |
| --- | --- |
| getCompliance () | 生成的 PDF 文档的期望合规级别。读/写 PdfCompliance。默认值为 PdfCompliance#Pdf17。 |

**返回：**  
int


---


### getDrawSlidesFrame {#getDrawSlidesFrame}

| 名称 | 描述 |
| --- | --- |
| getDrawSlidesFrame () | True 表示在每张幻灯片周围绘制黑色框架。读/写 boolean。默认值为 false。 |

**返回：**  
boolean


---


### getEmbedFullFonts {#getEmbedFullFonts}

| 名称 | 描述 |
| --- | --- |
| getEmbedFullFonts () | 确定是嵌入字体的所有字符还是仅嵌入使用的子集。读/写 boolean。默认值为 false。 |

**返回：**  
boolean


---


### getEmbedTrueTypeFontsForASCII {#getEmbedTrueTypeFontsForASCII}

| 名称 | 描述 |
| --- | --- |
| getEmbedTrueTypeFontsForASCII () | 确定 Aspose.Slides 是否为 ASCII（33..127 码位）文本嵌入通用字体。码位大于 127 的字符始终嵌入。通用字体列表包括 PDF 的基本 14 种字体以及用户指定的额外字体。读/写 boolean。默认值为 true。 |

**返回：**  
boolean


---


### getImageTransparentColor {#getImageTransparentColor}

| 名称 | 描述 |
| --- | --- |
| getImageTransparentColor () | 获取或设置图像的透明颜色。值：图像的透明颜色。 |

**返回：**  
Color


---


### getIncludeOleData {#getIncludeOleData}

| 名称 | 描述 |
| --- | --- |
| getIncludeOleData () | True 将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。读/写 boolean。默认值为 false。 |

**返回：**  
boolean


---


### getInkOptions {#getInkOptions}

| 名称 | 描述 |
| --- | --- |
| getInkOptions () | 提供控制导出文档中 Ink 对象外观的选项。只读 IInkOptions |

**返回：**  
[InkOptions](../inkoptions)


---


### getJpegQuality {#getJpegQuality}

| 名称 | 描述 |
| --- | --- |
| getJpegQuality () | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。读/写 byte。仅在文档包含 JPEG 图像时生效。使用此属性可在以 PDF 格式保存时获取或设置图像质量。取值范围 0~100，0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。默认值为 100。 |

**返回：**  
byte


---


### getPassword {#getPassword}

| 名称 | 描述 |
| --- | --- |
| getPassword () | 设置用于保护 PDF 文档的用户密码。读/写 String。 |

**返回：**  
String


---


### getRasterizeUnsupportedFontStyles {#getRasterizeUnsupportedFontStyles}

| 名称 | 描述 |
| --- | --- |
| getRasterizeUnsupportedFontStyles () | 指示当字体不支持粗体样式时，是否将文本光栅化为位图并保存至 PDF。此方法可提升某些字体在生成的 PDF 中的文本质量。读/写 boolean。默认值为 false。 |

**返回：**  
boolean


---


### getSaveMetafilesAsPng {#getSaveMetafilesAsPng}

| 名称 | 描述 |
| --- | --- |
| getSaveMetafilesAsPng () | True 将演示文稿中使用的所有元文件转换为 PNG 图像。读/写 boolean。默认值为 true。PDF 文档可以包含矢量图形和光栅图像。如果 SaveMetafilesAsPng 为 true，则源元文件图像转换为 PNG 格式并以光栅图像保存到 PDF；如果为 false，则源元文件转换为 PDF 矢量图形。两种方式各有优缺点。例如，元文件转换为 PNG 时，文档缩放可能导致质量损失；转换为 PDF 矢量图形时，PDF 查看工具可能出现性能问题。 |

**返回：**  
boolean


---


### getShowHiddenSlides {#getShowHiddenSlides}

| 名称 | 描述 |
| --- | --- |
| getShowHiddenSlides () | 指定生成的文档是否应包含隐藏幻灯片。默认值为 false。 |

**返回：**  
boolean


---


### getSlidesLayoutOptions {#getSlidesLayoutOptions}

| 名称 | 描述 |
| --- | --- |
| getSlidesLayoutOptions () | 获取或设置导出演示文稿时幻灯片在页面上的布局模式 ISlidesLayoutOptions。 |

**返回：**  
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), [HandoutLayoutingOptions](../handoutlayoutingoptions)


---


### getSufficientResolution {#getSufficientResolution}

| 名称 | 描述 |
| --- | --- |
| getSufficientResolution () | 返回或设置决定 PDF 文档中图像分辨率的值。读/写 float。值：此参数的效果取决于多个因素。算法会根据属性值、源图像尺寸和图像框尺寸获取最佳输出图像大小。使用相近的属性值可能得到相同结果。建议使用 16 或 32 的步长以获得明显效果。属性会影响文件大小、导出时间和图像质量。默认值为 96。 |

**返回：**  
float


---


### getTextCompression {#getTextCompression}

| 名称 | 描述 |
| --- | --- |
| getTextCompression () | 指定文档中所有文本内容使用的压缩类型。读/写 PdfTextCompression。默认值为 PdfTextCompression#Flate。 |

**返回：**  
int


---


### setAccessPermissions {#setAccessPermissions}

| 名称 | 描述 |
| --- | --- |
| setAccessPermissions (int) | 包含一组标志，指定在以用户访问权限打开文档时应授予的访问权限。参见 PdfAccessPermissions。 |

**返回：**  
void


---


### setAdditionalCommonFontFamilies {#setAdditionalCommonFontFamilies}

| 名称 | 描述 |
| --- | --- |
| setAdditionalCommonFontFamilies (java.lang.String[]) | 返回或设置 Aspose.Slides 应视为通用的字体系列的用户自定义名称数组。读/写 String[]. |

**返回：**  
void


---


### setApplyImageTransparent {#setApplyImageTransparent}

| 名称 | 描述 |
| --- | --- |
| setApplyImageTransparent (boolean) | True 将指定的透明颜色应用于图像。 |

**返回：**  
void


---


### setBestImagesCompressionRatio {#setBestImagesCompressionRatio}

| 名称 | 描述 |
| --- | --- |
| setBestImagesCompressionRatio (boolean) | 指示是否应自动为每个图像选择最有效的压缩（而非默认压缩）。如果设置为 true，则为演示文稿中的每个图像选择最合适的压缩算法，从而使生成的 PDF 文档体积更小。最佳图像压缩比的选择计算量大且占用额外内存，默认值为 false。 |

**返回：**  
void


---


### setCompliance {#setCompliance}

| 名称 | 描述 |
| --- | --- |
| setCompliance (int) | 生成的 PDF 文档的期望合规级别。读/写 PdfCompliance。默认值为 PdfCompliance#Pdf17。 |

**返回：**  
void


---


### setDrawSlidesFrame {#setDrawSlidesFrame}

| 名称 | 描述 |
| --- | --- |
| setDrawSlidesFrame (boolean) | True 表示在每张幻灯片周围绘制黑色框架。读/写 boolean。默认值为 false。 |

**返回：**  
void


---


### setEmbedFullFonts {#setEmbedFullFonts}

| 名称 | 描述 |
| --- | --- |
| setEmbedFullFonts (boolean) | 确定是嵌入字体的所有字符还是仅嵌入使用的子集。读/写 boolean。默认值为 false。 |

**返回：**  
void


---


### setEmbedTrueTypeFontsForASCII {#setEmbedTrueTypeFontsForASCII}

| 名称 | 描述 |
| --- | --- |
| setEmbedTrueTypeFontsForASCII (boolean) | 确定 Aspose.Slides 是否为 ASCII（33..127 码位）文本嵌入通用字体。码位大于 127 的字符始终嵌入。通用字体列表包括 PDF 的基本 14 种字体以及用户指定的额外字体。读/写 boolean。默认值为 true。 |

**返回：**  
void


---


### setImageTransparentColor {#setImageTransparentColor}

| 名称 | 描述 |
| --- | --- |
| setImageTransparentColor (Color) | 获取或设置图像的透明颜色。值：图像的透明颜色。 |

**返回：**  
void


---


### setIncludeOleData {#setIncludeOleData}

| 名称 | 描述 |
| --- | --- |
| setIncludeOleData (boolean) | True 将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。读/写 boolean。默认值为 false。 |

**返回：**  
void


---


### setJpegQuality {#setJpegQuality}

| 名称 | 描述 |
| --- | --- |
| setJpegQuality (byte) | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。读/写 byte。仅在文档包含 JPEG 图像时生效。使用此属性可在以 PDF 格式保存时获取或设置图像质量。取值范围 0~100，0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。默认值为 100。 |

**返回：**  
void


---


### setPassword {#setPassword}

| 名称 | 描述 |
| --- | --- |
| setPassword (String) | 设置用于保护 PDF 文档的用户密码。读/写 String。 |

**返回：**  
void


---


### setRasterizeUnsupportedFontStyles {#setRasterizeUnsupportedFontStyles}

| 名称 | 描述 |
| --- | --- |
| setRasterizeUnsupportedFontStyles (boolean) | 指示当字体不支持粗体样式时，是否将文本光栅化为位图并保存至 PDF。此方法可提升某些字体在生成的 PDF 中的文本质量。读/写 boolean。默认值为 false。 |

**返回：**  
void


---


### setSaveMetafilesAsPng {#setSaveMetafilesAsPng}

| 名称 | 描述 |
| --- | --- |
| setSaveMetafilesAsPng (boolean) | True 将演示文稿中使用的所有元文件转换为 PNG 图像。读/写 boolean。默认值为 true。PDF 文档可以包含矢量图形和光栅图像。如果 SaveMetafilesAsPng 为 true，则源元文件图像转换为 PNG 格式并以光栅图像保存到 PDF；如果为 false，则源元文件转换为 PDF 矢量图形。两种方式各有优缺点。例如，元文件转换为 PNG 时，文档缩放可能导致质量损失；转换为 PDF 矢量图形时，PDF 查看工具可能出现性能问题。 |

**返回：**  
void


---


### setShowHiddenSlides {#setShowHiddenSlides}

| 名称 | 描述 |
| --- | --- |
| setShowHiddenSlides (boolean) | 指定生成的文档是否应包含隐藏幻灯片。默认值为 false。 |

**返回：**  
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| 名称 | 描述 |
| --- | --- |
| setSlidesLayoutOptions ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | 获取或设置导出演示文稿时幻灯片在页面上的布局模式 ISlidesLayoutOptions。 |

**返回：**  
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| 名称 | 描述 |
| --- | --- |
| setSlidesLayoutOptions ([HandoutLayoutingOptions](../handoutlayoutingoptions)) | 获取或设置导出演示文稿时幻灯片在页面上的布局模式 ISlidesLayoutOptions。 |

**返回：**  
void


---


### setSufficientResolution {#setSufficientResolution}

| 名称 | 描述 |
| --- | --- |
| setSufficientResolution (float) | 返回或设置决定 PDF 文档中图像分辨率的值。读/写 float。值：此参数的效果取决于多个因素。算法会根据属性值、源图像尺寸和图像框尺寸获取最佳输出图像大小。使用相近的属性值可能得到相同结果。建议使用 16 或 32 的步长以获得明显效果。属性会影响文件大小、导出时间和图像质量。默认值为 96。 |

**返回：**  
void


---


### setTextCompression {#setTextCompression}

| 名称 | 描述 |
| --- | --- |
| setTextCompression (int) | 指定文档中所有文本内容使用的压缩类型。读/写 PdfTextCompression。默认值为 PdfTextCompression#Flate。 |

**返回：**  
void


---