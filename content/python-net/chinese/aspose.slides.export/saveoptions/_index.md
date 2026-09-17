---
title: SaveOptions class
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/saveoptions/
---
## SaveOptions 类

抽象类，包含控制演示文稿保存方式的选项。

SaveOptions 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/saveoptions/warning_callback/) | 返回或设置一个对象，该对象接收警告并决定加载过程是继续还是中止。<br/>            读/写 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/saveoptions/progress_callback/) | 表示一个用于保存进度更新（以百分比表示）的回调对象。<br/>            参见 [`IProgressCallback`](/slides/python-net/zh/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/saveoptions/default_regular_font/) | 返回或设置在未找到源字体时使用的字体。<br/>            读写 **str**. |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/saveoptions/gradient_style/) | 返回或设置渐变的视觉样式。<br/>            读/写 [`GradientStyle`](/slides/python-net/zh/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/saveoptions/skip_java_script_links/) | 指定在保存演示文稿时是否跳过包含 JavaScript 调用的超链接。<br/>            读/写 **bool**. 默认值为 **false** . |

### 另请参见
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)