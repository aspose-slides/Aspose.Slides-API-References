---
title: Convert class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.lowcode/convert/
---
## Convert 类

表示一组旨在转换 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) 的方法。

Convert 类型公开以下成员：

## 方法

| 方法 | 描述 |
| :- | :- |
| [`to_pdf(pres_path, out_path)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_pdf/#str-str) | 将 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) 转换为 PDF。 |
| [`to_pdf(pres_path, out_path, options)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_pdf/#str-str-asposeslidesexportipdfoptions) | 将 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) 转换为 PDF。 |
| [`to_pdf(pres, out_path)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_pdf/#presentation-str) | 将 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) 转换为 PDF。 |
| [`to_pdf(pres, out_path, options)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_pdf/#presentation-str-asposeslidesexportipdfoptions) | 将 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) 转换为 PDF。 |
| [`to_svg(pres_path)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_svg/#str) | 将 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) 转换为 SVG。 |
| [`to_svg(pres, options)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_svg/#presentation-asposeslidesexportisvgoptions) | 将 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) 转换为 SVG。 |
| [`to_jpeg(pres, output_file_name)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_jpeg/#presentation-str) | 将输入演示文稿转换为一组 JPEG 格式的图像。<br/>如果输出文件名为 "myPath/myFilename.jpeg"，<br/>结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，其中 N 是幻灯片编号。 |
| [`to_jpeg(pres, output_file_name, image_size)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_jpeg/#presentation-str-asposepydrawingsize) | 将输入演示文稿转换为一组 JPEG 格式的图像。<br/>如果输出文件名为 "myPath/myFilename.jpeg"，<br/>结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，其中 N 是幻灯片编号。 |
| [`to_jpeg(pres, output_file_name, scale, options)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_jpeg/#presentation-str-float-asposeslidesexportirenderingoptions) | 将输入演示文稿转换为一组 JPEG 格式的图像。<br/>如果输出文件名为 "myPath/myFilename.jpeg"，<br/>结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，其中 N 是幻灯片编号。 |
| [`to_png(pres, output_file_name)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_png/#presentation-str) | 将输入演示文稿转换为一组 PNG 格式的图像。<br/>如果输出文件名为 "myPath/myFilename.png"，<br/>结果将保存为一组 "myPath/myFilename_N.png" 文件，其中 N 是幻灯片编号。 |
| [`to_png(pres, output_file_name, image_size)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_png/#presentation-str-asposepydrawingsize) | 将输入演示文稿转换为一组 PNG 格式的图像。<br/>如果输出文件名为 "myPath/myFilename.png"，<br/>结果将保存为一组 "myPath/myFilename_N.png" 文件，其中 N 是幻灯片编号。 |
| [`to_png(pres, output_file_name, scale, options)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_png/#presentation-str-float-asposeslidesexportirenderingoptions) | 将输入演示文稿转换为一组 PNG 格式的图像。<br/>如果输出文件名为 "myPath/myFilename.png"，<br/>结果将保存为一组 "myPath/myFilename_N.png" 文件，其中 N 是幻灯片编号。 |
| [`to_tiff(pres, output_file_name)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_tiff/#presentation-str) | 将输入演示文稿转换为一组 TIFF 格式的图像。<br/>如果输出文件名为 "myPath/myFilename.tiff"，<br/>结果将保存为一组 "myPath/myFilename_N.tiff" 文件，其中 N 是幻灯片编号。 |
| [`to_tiff(pres, output_file_name, options, multipage)`](/slides/python-net/zh/aspose.slides.lowcode/convert/to_tiff/#presentation-str-asposeslidesexportitiffoptions-bool) | 将输入演示文稿转换为带自定义选项的 TIFF 格式。<br/>如果输出文件名为 "myPath/myFilename.tiff" 且 `multipage` 为 `false`，<br/>结果将保存为一组 "myPath/myFilename_N.tiff" 文件，其中 N 是幻灯片编号。<br/>否则，如果 `multipage` 为 `true`，结果将是一个多页的 "myPath/myFilename.tiff" 文档。 |
| [`auto_by_extension(pres_path, out_path)`](/slides/python-net/zh/aspose.slides.lowcode/convert/auto_by_extension/#str-str) | 使用传入的输出路径扩展名来确定所需的导出格式并转换 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)。 |

### 另见
* 类 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)
* 模块 [`aspose.slides.lowcode`](/slides/python-net/zh/aspose.slides.lowcode)
* 库 [`Aspose.Slides`](/slides/python-net)