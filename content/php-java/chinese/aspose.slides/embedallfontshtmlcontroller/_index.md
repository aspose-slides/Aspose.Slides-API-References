---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController 类

 用于在 WOFF 格式中嵌入所有演示文稿字体的格式化控制器类。

### EmbedAllFontsHtmlController {#EmbedAllFontsHtmlController}

| 名称 | 描述 |
| --- | --- |
| EmbedAllFontsHtmlController() | 创建新实例 |

 **返回值:**  
EmbedAllFontsHtmlController


---


### EmbedAllFontsHtmlController {#EmbedAllFontsHtmlController}

| 名称 | 描述 |
| --- | --- |
| EmbedAllFontsHtmlController(java.lang.String[]) | 创建新实例 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | 要从嵌入中排除的字体 |

 **返回值:**  
EmbedAllFontsHtmlController


---


### writeAllFonts {#writeAllFonts}

| 名称 | 描述 |
| --- | --- |
| writeAllFonts ([HtmlGenerator](../htmlgenerator), [Presentation](../presentation)) | 将包含在 Presentation 中的所有字体写入。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| presentation | [Presentation](../presentation) | 当前正在渲染的 Presentation。 |

 **返回值:**  
void


---


### writeDocumentEnd {#writeDocumentEnd}

| 名称 | 描述 |
| --- | --- |
| writeDocumentEnd ([HtmlGenerator](../htmlgenerator), [Presentation](../presentation)) | 用于写入 HTML 文档页脚。每次演示文稿转换调用一次。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| presentation | [Presentation](../presentation) | 当前正在渲染的 Presentation。 |

 **返回值:**  
void


---


### writeDocumentStart {#writeDocumentStart}

| 名称 | 描述 |
| --- | --- |
| writeDocumentStart ([HtmlGenerator](../htmlgenerator), [Presentation](../presentation)) | 用于写入 HTML 文档头部。每次演示文稿转换调用一次。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| presentation | [Presentation](../presentation) | 当前正在渲染的 Presentation。 |

 **返回值:**  
void


---


### writeFont {#writeFont}

| 名称 | 描述 |
| --- | --- |
| writeFont ([HtmlGenerator](../htmlgenerator), [FontData](../fontdata), [FontData](../fontdata), String, String, byte[]) | 将数据以 base64 形式写入 HTML 文档本身 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | HTML 生成器 |
| originalFont | [FontData](../fontdata) | 要序列化的 Font |
| substitutedFont | [FontData](../fontdata) | 替代 Font（如果发生字体替换），否则为 null |
| fontStyle | String | 字体样式 |
| fontWeight | String | 字体粗细 |
| fontData | byte[] | 字体数据 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [GraphicalObject](../graphicalobject)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [GraphicalObject](../graphicalobject) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [Connector](../connector)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [Connector](../connector) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [Shape](../shape)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [Shape](../shape) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [SmartArtShape](../smartartshape)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [SmartArtShape](../smartartshape) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [Table](../table)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [Table](../table) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [Ink](../ink)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [Ink](../ink) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [SummaryZoomFrame](../summaryzoomframe)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [SummaryZoomFrame](../summaryzoomframe) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [GeometryShape](../geometryshape)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [GeometryShape](../geometryshape) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [SummaryZoomSection](../summaryzoomsection)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [SummaryZoomSection](../summaryzoomsection) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [ZoomFrame](../zoomframe)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [ZoomFrame](../zoomframe) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [OleObjectFrame](../oleobjectframe)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [OleObjectFrame](../oleobjectframe) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [VideoFrame](../videoframe)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [VideoFrame](../videoframe) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [SmartArt](../smartart)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [SmartArt](../smartart) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [GroupShape](../groupshape)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [GroupShape](../groupshape) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [InkActions](../inkactions)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [InkActions](../inkactions) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [AutoShape](../autoshape)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [AutoShape](../autoshape) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [PictureFrame](../pictureframe)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，将会结束当前 slide 图像的生成，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [PictureFrame](../pictureframe) | 最后渲染的 Shape。 |

 **返回值:**  
void


---


### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [SectionZoomFrame](../sectionzoomframe)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [SectionZoomFrame](../sectionzoomframe) | 已渲染的最后一个形状。 |

**返回：**  
void


---

### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [Chart](../chart)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [Chart](../chart) | 已渲染的最后一个形状。 |

**返回：**  
void


---

### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [AudioFrame](../audioframe)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [AudioFrame](../audioframe) | 已渲染的最后一个形状。 |

**返回：**  
void


---

### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [ZoomObject](../zoomobject)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [ZoomObject](../zoomobject) | 已渲染的最后一个形状。 |

**返回：**  
void


---

### writeShapeEnd {#writeShapeEnd}

| 名称 | 描述 |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [LegacyDiagram](../legacydiagram)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [LegacyDiagram](../legacydiagram) | 已渲染的最后一个形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [GraphicalObject](../graphicalobject)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [GraphicalObject](../graphicalobject) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [Connector](../connector)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [Connector](../connector) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [Shape](../shape)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [Shape](../shape) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [SmartArtShape](../smartartshape)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [SmartArtShape](../smartartshape) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [Table](../table)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [Table](../table) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [Ink](../ink)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [Ink](../ink) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [SummaryZoomFrame](../summaryzoomframe)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [SummaryZoomFrame](../summaryzoomframe) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [GeometryShape](../geometryshape)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [GeometryShape](../geometryshape) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [SummaryZoomSection](../summaryzoomsection)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [SummaryZoomSection](../summaryzoomsection) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [ZoomFrame](../zoomframe)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [ZoomFrame](../zoomframe) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [OleObjectFrame](../oleobjectframe)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [OleObjectFrame](../oleobjectframe) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [VideoFrame](../videoframe)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [VideoFrame](../videoframe) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [SmartArt](../smartart)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [SmartArt](../smartart) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [GroupShape](../groupshape)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [GroupShape](../groupshape) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [InkActions](../inkactions)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [InkActions](../inkactions) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [AutoShape](../autoshape)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [AutoShape](../autoshape) | 即将渲染的形状。 |

**返回：**  
void


---

### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [PictureFrame](../pictureframe)) | 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始生成新图像。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [PictureFrame](../pictureframe) | 即将渲染的 shape。 |

**返回值:**
void


---


### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [SectionZoomFrame](../sectionzoomframe)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，当前 slide 图像生成将完成，插入添加的 html 片段，并在之前的图像之上开始生成新图像。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [SectionZoomFrame](../sectionzoomframe) | 即将渲染的 shape。 |

**返回值:**
void


---


### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [Chart](../chart)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，当前 slide 图像生成将完成，插入添加的 html 片段，并在之前的图像之上开始生成新图像。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [Chart](../chart) | 即将渲染的 shape。 |

**返回值:**
void


---


### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [AudioFrame](../audioframe)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，当前 slide 图像生成将完成，插入添加的 html 片段，并在之前的图像之上开始生成新图像。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [AudioFrame](../audioframe) | 即将渲染的 shape。 |

**返回值:**
void


---


### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [ZoomObject](../zoomobject)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，当前 slide 图像生成将完成，插入添加的 html 片段，并在之前的图像之上开始生成新图像。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [ZoomObject](../zoomobject) | 即将渲染的 shape。 |

**返回值:**
void


---


### writeShapeStart {#writeShapeStart}

| 名称 | 描述 |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [LegacyDiagram](../legacydiagram)) | 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，当前 slide 图像生成将完成，插入添加的 html 片段，并在之前的图像之上开始生成新图像。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| shape | [LegacyDiagram](../legacydiagram) | 即将渲染的 shape。 |

**返回值:**
void


---


### writeSlideEnd {#writeSlideEnd}

| 名称 | 描述 |
| --- | --- |
| writeSlideEnd ([HtmlGenerator](../htmlgenerator), [Slide](../slide)) | 用于写入 html slide 页脚。每个 slide 调用一次。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| slide | [Slide](../slide) | 当前正在渲染的 slide。 |

**返回值:**
void


---


### writeSlideStart {#writeSlideStart}

| 名称 | 描述 |
| --- | --- |
| writeSlideStart ([HtmlGenerator](../htmlgenerator), [Slide](../slide)) | 用于写入 html slide 标头。每个 slide 调用一次。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | 输出对象。 |
| slide | [Slide](../slide) | 当前正在渲染的 slide。 |

**返回值:**
void


---