---
title: IHtmlFormattingController class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController 类

控制 html 文件的生成。

IHtmlFormattingController 类型公开以下成员：

## 方法

| 方法 | 描述 |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/zh/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | 用于写入 html 文档头部。每次演示转换调用一次。 |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/zh/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | 用于写入 html 文档页脚。每次演示转换调用一次。 |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/zh/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | 用于写入 html 幻灯片头部。每个幻灯片调用一次。 |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/zh/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | 用于写入 html 幻灯片页脚。每个幻灯片调用一次。 |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/zh/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | 在形状渲染前调用。每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像生成将结束，插入添加的 html 片段，并在之前的图像之上开始新的图像。 |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/zh/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | 在形状渲染前调用。每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像生成将结束，插入添加的 html 片段，并在之前的图像之上开始新的图像。 |


### 另请参见
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)