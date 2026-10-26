---
title: PptOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/pptoptions/
---
## PptOptions 类

提供控制演示文稿以 PPT 格式保存方式的选项。

**Inheritance:**[`PptOptions`](/slides/python-net/zh/aspose.slides.export/pptoptions) → [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)

PptOptions 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.export/pptoptions/__init__/#) |  |

## 属性

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/pptoptions/warning_callback/) | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。<br/>            读/写 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/pptoptions/progress_callback/) | 表示用于保存进度更新（百分比）的回调对象。<br/>            参见 [`IProgressCallback`](/slides/python-net/zh/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/pptoptions/default_regular_font/) | 返回或设置在未找到源字体时使用的字体。<br/>            读写 **str**. |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/pptoptions/gradient_style/) | 返回或设置渐变的视觉样式。<br/>            读/写 [`GradientStyle`](/slides/python-net/zh/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/pptoptions/skip_java_script_links/) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。 <br/>            读/写 **bool**。默认值为 **false** . |
| [`root_directory_clsid`](/slides/python-net/zh/aspose.slides.export/pptoptions/root_directory_clsid/) | 表示存储在根目录项中的对象类 GUID（CLSID）。可用于文档应用程序的 COM<br/>            激活。<br/>            默认值为 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，对应于 'Microsoft Powerpoint.Slide.8'. |


### 另请参见
* 类 [`PptOptions`](/slides/python-net/zh/aspose.slides.export/pptoptions)
* 类 [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)