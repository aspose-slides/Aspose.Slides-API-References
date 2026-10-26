---
title: RenderingOptions class
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides.export/renderingoptions/
---
## RenderingOptions 类

提供控制演示文稿/幻灯片渲染方式的选项。

**继承：**[`RenderingOptions`](/slides/python-net/zh/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)

RenderingOptions 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.export/renderingoptions/__init__/#) | 默认构造函数。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/renderingoptions/warning_callback/) | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。<br/>            读/写 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/renderingoptions/progress_callback/) | 表示用于以百分比保存进度更新的回调对象。<br/>            参见 [`IProgressCallback`](/slides/python-net/zh/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/renderingoptions/default_regular_font/) | 返回或设置在未找到源字体时使用的字体。<br/>            读/写 **str**。 |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/renderingoptions/gradient_style/) | 返回或设置渐变的视觉样式。<br/>            读/写 [`GradientStyle`](/slides/python-net/zh/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/renderingoptions/skip_java_script_links/) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。<br/>            读/写 **bool**。 默认值为 **false**。 |
| [`slides_layout_options`](/slides/python-net/zh/aspose.slides.export/renderingoptions/slides_layout_options/) | 获取或设置在导出演示文稿 [`ISlidesLayoutOptions`](/slides/python-net/zh/aspose.slides.export/islideslayoutoptions) 时幻灯片在页面上的放置模式。 |
| [`ink_options`](/slides/python-net/zh/aspose.slides.export/renderingoptions/ink_options/) | 提供控制导出文档中 Ink 对象外观的选项。<br/>            只读 [`IInkOptions`](/slides/python-net/zh/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/zh/aspose.slides.export/renderingoptions/disable_font_ligatures/) | 获取或设置一个值，用于指示文本是否在渲染时不使用连字。<br/>            设置为 `true` 时，渲染输出将禁用连字。默认情况下，此属性设置为 `false`。 |


### 另请参阅
* 类 [`RenderingOptions`](/slides/python-net/zh/aspose.slides.export/renderingoptions)
* 类 [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)