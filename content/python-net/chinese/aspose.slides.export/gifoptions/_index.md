---
title: GifOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/gifoptions/
---
## GifOptions 类

表示 GIF 导出选项。

**继承:**[`GifOptions`](/slides/python-net/zh/aspose.slides.export/gifoptions) → [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)

GifOptions 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.export/gifoptions/__init__/#) | 初始化 GifOptions 类的新实例。 |

## 属性

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/gifoptions/warning_callback/) | 返回或设置一个接收警告并决定加载过程是否继续或中止的对象。<br/>            读/写 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/gifoptions/progress_callback/) | 表示用于保存进度更新（以百分比表示）的回调对象。<br/>            参见 [`IProgressCallback`](/slides/python-net/zh/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/gifoptions/default_regular_font/) | 返回或设置在未找到源字体时使用的字体。<br/>            读写 **str**。 |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/gifoptions/gradient_style/) | 返回或设置渐变的视觉样式。<br/>            读/写 [`GradientStyle`](/slides/python-net/zh/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/gifoptions/skip_java_script_links/) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。 <br/>            读/写 **bool**。默认值为 **false** 。 |
| [`frame_size`](/slides/python-net/zh/aspose.slides.export/gifoptions/frame_size/) | 获取或设置帧大小。 |
| [`export_hidden_slides`](/slides/python-net/zh/aspose.slides.export/gifoptions/export_hidden_slides/) | 确定是否导出隐藏幻灯片。<br/>            默认值为 false。 |
| [`transition_fps`](/slides/python-net/zh/aspose.slides.export/gifoptions/transition_fps/) | 获取或设置过渡 FPS [frames/sec]<br/>            默认值为 25。 |
| [`default_delay`](/slides/python-net/zh/aspose.slides.export/gifoptions/default_delay/) | 获取或设置默认延迟时间 [ms]。如果未设置 [`ISlideShowTransition.advance_after_time`](/slides/python-net/zh/aspose.slides/islideshowtransition/advance_after_time)，将使用该值。<br/>            默认值为 1000。 |

### 另见
* 类 [`GifOptions`](/slides/python-net/zh/aspose.slides.export/gifoptions)
* 类 [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)