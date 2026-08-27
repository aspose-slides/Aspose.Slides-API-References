---
title: SVGOptions
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/svgoptions/
---
## SVGOptions 类

表示 SVG 选项。

### SVGOptions {#SVGOptions}

| 名称 | 描述 |
| --- | --- |
| SVGOptions() | 初始化 SVGOptions 类的新实例。 |

**返回：**  
SVGOptions


---


### SVGOptions {#SVGOptions}

| 名称 | 描述 |
| --- | --- |
| SVGOptions([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | 初始化 SVGOptions 类的新实例，指定链接嵌入控制器对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| linkEmbedController | [VideoPlayerHtmlController](../videoplayerhtmlcontroller) | 链接嵌入控制器引用。链接嵌入控制器是一个委托对象，负责决定资源（例如图像）是需要嵌入还是作为外部资源引用。 |

**返回：**  
SVGOptions


---


### getDefault {#getDefault}

| 名称 | 描述 |
| --- | --- |
| getDefault () | 返回默认设置。只读 SVGOptions。 |

**返回：**  
SVGOptions


---


### getDeletePicturesCroppedAreas {#getDeletePicturesCroppedAreas}

| 名称 | 描述 |
| --- | --- |
| getDeletePicturesCroppedAreas () | 布尔标志指示裁剪的部分是否保留在文档中。如果为 true，则裁剪的部分将被移除；如果为 false，则它们将在文档中序列化（这可能导致文件更大）。 |

**返回：**  
boolean


---


### getDisable3DText {#getDisable3DText}

| 名称 | 描述 |
| --- | --- |
| getDisable3DText () | 确定 SVG 中是否禁用 3D 文本。读/写 boolean。 |

**返回：**  
boolean


---


### getDisableFontLigatures {#getDisableFontLigatures}

| 名称 | 描述 |
| --- | --- |
| getDisableFontLigatures () | 获取或设置一个值，指示文本是否在渲染时不使用连字。设置为 true 时，连字将在渲染输出中被禁用。默认情况下，此属性为 false。 |

**返回：**  
boolean


---


### getDisableGradientSplit {#getDisableGradientSplit}

| 名称 | 描述 |
| --- | --- |
| getDisableGradientSplit () | 禁用 FromCornerX 和 FromCenter 渐变的拆分。读/写 boolean。 |

**返回：**  
boolean


---


### getDisableLineEndCropping {#getDisableLineEndCropping}

| 名称 | 描述 |
| --- | --- |
| getDisableLineEndCropping () | SVG 1.1 缺少为标记定义内嵌的能力。Aspose.Slides SVG 写入引擎为此问题提供了解决方案：它会裁剪带箭头的线段末端，以免线段与标记重叠。此选项可关闭该行为。读/写 boolean。 |

**返回：**  
boolean


---


### getExternalFontsHandling {#getExternalFontsHandling}

| 名称 | 描述 |
| --- | --- |
| getExternalFontsHandling () | 确定外部加载字体的处理方式。读/写 SvgExternalFontsHandling。 |

**返回：**  
int


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
| getJpegQuality () | 确定 JPEG 编码质量。读/写 int。 |

**返回：**  
int


---


### getMetafileRasterizationDpi {#getMetafileRasterizationDpi}

| 名称 | 描述 |
| --- | --- |
| getMetafileRasterizationDpi () | 返回或设置元文件光栅化的最低分辨率限制。读/写 int。 |

**返回：**  
int


---


### getPicturesCompression {#getPicturesCompression}

| 名称 | 描述 |
| --- | --- |
| getPicturesCompression () | 表示图片压缩级别 |

**返回：**  
int


---


### getShapeFormattingController {#getShapeFormattingController}

| 名称 | 描述 |
| --- | --- |
| getShapeFormattingController () | 返回并设置一个回调接口，允许用户控制形状转换。读/写 ISvgShapeFormattingController。 |

**返回：**  
[VideoPlayerHtmlController](../videoplayerhtmlcontroller)


---


### getSimple {#getSimple}

| 名称 | 描述 |
| --- | --- |
| getSimple () | 返回用于生成最简洁、最小 SVG 文件的设置。只读 SVGOptions。 |

**返回：**  
SVGOptions


---


### getUseFrameRotation {#getUseFrameRotation}

| 名称 | 描述 |
| --- | --- |
| getUseFrameRotation () | 确定在渲染时是否执行指定的形状旋转。读/写 boolean。默认值为 true。 |

**返回：**  
boolean


---


### getUseFrameSize {#getUseFrameSize}

| 名称 | 描述 |
| --- | --- |
| getUseFrameSize () | 确定文本框是否会包含在渲染区域中。读/写 boolean。默认值为 false。 |

**返回：**  
boolean


---


### getVectorizeText {#getVectorizeText}

| 名称 | 描述 |
| --- | --- |
| getVectorizeText () | 确定幻灯片上的文本是否会保存为图形。读/写 boolean。 |

**返回：**  
boolean


---


### getWYSIWYG {#getWYSIWYG}

| 名称 | 描述 |
| --- | --- |
| getWYSIWYG () | 返回用于生成最精确 SVG 文件的设置。只读 SVGOptions。 |

**返回：**  
SVGOptions


---


### setDeletePicturesCroppedAreas {#setDeletePicturesCroppedAreas}

| 名称 | 描述 |
| --- | --- |
| setDeletePicturesCroppedAreas (boolean) | 布尔标志指示裁剪的部分是否保留在文档中。如果为 true，则裁剪的部分将被移除；如果为 false，则它们将在文档中序列化（这可能导致文件更大）。 |

**返回：**  
void


---


### setDisable3DText {#setDisable3DText}

| 名称 | 描述 |
| --- | --- |
| setDisable3DText (boolean) | 确定 SVG 中是否禁用 3D 文本。读/写 boolean。 |

**返回：**  
void


---


### setDisableFontLigatures {#setDisableFontLigatures}

| 名称 | 描述 |
| --- | --- |
| setDisableFontLigatures (boolean) | 获取或设置一个值，指示文本是否在渲染时不使用连字。设置为 true 时，连字将在渲染输出中被禁用。默认情况下，此属性为 false。 |

**返回：**  
void


---


### setDisableGradientSplit {#setDisableGradientSplit}

| 名称 | 描述 |
| --- | --- |
| setDisableGradientSplit (boolean) | 禁用 FromCornerX 和 FromCenter 渐变的拆分。读/写 boolean。 |

**返回：**  
void


---


### setDisableLineEndCropping {#setDisableLineEndCropping}

| 名称 | 描述 |
| --- | --- |
| setDisableLineEndCropping (boolean) | SVG 1.1 缺少为标记定义内嵌的能力。Aspose.Slides SVG 写入引擎为此问题提供了解决方案：它会裁剪带箭头的线段末端，以免线段与标记重叠。此选项可关闭该行为。读/写 boolean。 |

**返回：**  
void


---


### setExternalFontsHandling {#setExternalFontsHandling}

| 名称 | 描述 |
| --- | --- |
| setExternalFontsHandling (int) | 确定外部加载字体的处理方式。读/写 SvgExternalFontsHandling。 |

**返回：**  
void


---


### setJpegQuality {#setJpegQuality}

| 名称 | 描述 |
| --- | --- |
| setJpegQuality (int) | 确定 JPEG 编码质量。读/写 int。 |

**返回：**  
void


---


### setMetafileRasterizationDpi {#setMetafileRasterizationDpi}

| 名称 | 描述 |
| --- | --- |
| setMetafileRasterizationDpi (int) | 返回或设置元文件光栅化的最低分辨率限制。读/写 int。 |

**返回：**  
void


---


### setPicturesCompression {#setPicturesCompression}

| 名称 | 描述 |
| --- | --- |
| setPicturesCompression (int) | 表示图片压缩级别 |

**返回：**  
void


---


### setShapeFormattingController {#setShapeFormattingController}

| 名称 | 描述 |
| --- | --- |
| setShapeFormattingController ([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | 返回并设置一个回调接口，允许用户控制形状转换。读/写 ISvgShapeFormattingController。 |

**返回：**  
void


---


### setUseFrameRotation {#setUseFrameRotation}

| 名称 | 描述 |
| --- | --- |
| setUseFrameRotation (boolean) | 确定在渲染时是否执行指定的形状旋转。读/写 boolean。默认值为 true。 |

**返回：**  
void


---


### setUseFrameSize {#setUseFrameSize}

| 名称 | 描述 |
| --- | --- |
| setUseFrameSize (boolean) | 确定文本框是否会包含在渲染区域中。读/写 boolean。默认值为 false。 |

**返回：**  
void


---


### setVectorizeText {#setVectorizeText}

| 名称 | 描述 |
| --- | --- |
| setVectorizeText (boolean) | 确定幻灯片上的文本是否会保存为图形。读/写 boolean。 |

**返回：**  
void


---