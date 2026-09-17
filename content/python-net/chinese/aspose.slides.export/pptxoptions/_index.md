---
title: PptxOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/pptxoptions/
---
## PptxOptions 类

表示用于保存 OpenXml 演示文稿 (PPTX, PPSX, POTX, PPTM, PPSM, POTM) 的选项。

**继承:**[`PptxOptions`](/slides/python-net/zh/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)

PptxOptions 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.export/pptxoptions/__init__/#) | 创建 PptxOptions 的新实例 |

## 属性

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/zh/aspose.slides.export/pptxoptions/warning_callback/) | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。<br/>            读/写 [`IWarningCallback`](/slides/python-net/zh/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/zh/aspose.slides.export/pptxoptions/progress_callback/) | 表示用于保存进度更新（百分比）的回调对象。<br/>            参见 [`IProgressCallback`](/slides/python-net/zh/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/zh/aspose.slides.export/pptxoptions/default_regular_font/) | 返回或设置在未找到源字体时使用的字体。<br/>            读写 **str**. |
| [`gradient_style`](/slides/python-net/zh/aspose.slides.export/pptxoptions/gradient_style/) | 返回或设置渐变的视觉样式。<br/>            读/写 [`GradientStyle`](/slides/python-net/zh/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/zh/aspose.slides.export/pptxoptions/skip_java_script_links/) | 指定在保存演示文稿时是否跳过包含 JavaScript 调用的超链接。<br/>            读/写 **bool**. 默认值为 **false** . |
| [`conformance`](/slides/python-net/zh/aspose.slides.export/pptxoptions/conformance/) | 指定演示文稿文档符合的合规性类。<br/>            默认值为 [`Conformance.ECMA_376_2006`](/slides/python-net/zh/aspose.slides.export/conformance/ECMA_376_2006) |
| [`zip_64_mode`](/slides/python-net/zh/aspose.slides.export/pptxoptions/zip_64_mode/) | 指定演示文稿文档是否使用 ZIP64 格式。<br/>            默认值为 [`Zip64Mode.IF_NECESSARY`](/slides/python-net/zh/aspose.slides.export/zip64mode/IF_NECESSARY) |
| [`refresh_thumbnail`](/slides/python-net/zh/aspose.slides.export/pptxoptions/refresh_thumbnail/) | 指定是否刷新演示文稿缩略图。<br/>            读/写 **bool**.<br/>            默认值为 **true** . |
| [`compression_level`](/slides/python-net/zh/aspose.slides.export/pptxoptions/compression_level/) | 指定保存演示文稿文档时使用的压缩级别。<br/>            默认值为 [`CompressionLevel.LEVEL6`](/slides/python-net/zh/aspose.slides.export/compressionlevel/LEVEL6). |

### 另请参见
* 类 [`PptxOptions`](/slides/python-net/zh/aspose.slides.export/pptxoptions)
* 类 [`SaveOptions`](/slides/python-net/zh/aspose.slides.export/saveoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)