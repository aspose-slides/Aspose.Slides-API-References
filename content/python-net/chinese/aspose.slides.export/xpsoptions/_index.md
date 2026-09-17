---
title: XpsOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/xpsoptions/
---
## XpsOptions 类

提供控制演示文稿以 XPS 格式保存的选项。

**继承:**[`XpsOptions`](/slides/python-net/zh/aspose.slides.export/xpsoptions) → [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)

XpsOptions 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.export/xpsoptions/__init__/#) | 默认构造函数。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/xpsoptions/warning_callback/) | 返回或设置一个对象，该对象接收警告并决定加载过程是继续还是中止。<br/>            读/写 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/xpsoptions/progress_callback/) | 表示用于保存进度更新（以百分比）的回调对象。<br/>            参见 [`IProgressCallback`](/slides/python-net/zh/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/xpsoptions/default_regular_font/) | 返回或设置在未找到源字体时使用的字体。<br/>            读写 **str**。 |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/xpsoptions/gradient_style/) | 返回或设置渐变的视觉样式。<br/>            读/写 [`GradientStyle`](/slides/python-net/zh/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/xpsoptions/skip_java_script_links/) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。 <br/>            读/写 **bool**。 默认值为 **false** 。 |
| [`show_hidden_slides`](/slides/python-net/zh/aspose.slides.export/xpsoptions/show_hidden_slides/) | 指定生成的文档是否应包含隐藏幻灯片。<br/>            默认是 `false`。 |
| [`save_metafiles_as_png`](/slides/python-net/zh/aspose.slides.export/xpsoptions/save_metafiles_as_png/) | 设为 true 将把演示文稿中使用的所有元文件转换为 PNG 图像。<br/>            读/写 **bool**。 |
| [`draw_slides_frame`](/slides/python-net/zh/aspose.slides.export/xpsoptions/draw_slides_frame/) | 设为 true 将在每个幻灯片周围绘制黑色框架。<br/>             读/写 **bool**。 |


### 另见
* 类 [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)
* 类 [`XpsOptions`](/slides/python-net/zh/aspose.slides.export/xpsoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)