---
title: SlideUtil class
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides.util/slideutil/
---
## SlideUtil 类

提供帮助在演示文稿中搜索形状和文本的方法。

SlideUtil 类型公开以下成员：

## 方法

| Method | Description |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/zh/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | 在 PPTX 演示文稿中通过替代文本查找形状。 |
| [`find_shape(slide, alt_text)`](/slides/python-net/zh/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | 在 PPTX 演示文稿的幻灯片上通过替代文本查找形状。 |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/zh/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | 更改幻灯片上所有形状的位置。将形状对齐到幻灯片的边距或边缘<br/>            或相互对齐。 |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/zh/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | 更改幻灯片上所选形状的位置。将形状对齐到幻灯片的边距或边缘<br/>            或相互对齐。 |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/zh/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | 更改组形状内部所有形状的位置。将形状对齐到幻灯片的边距或边缘<br/>            或相互对齐。 |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/zh/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | 更改组形状内部所选形状的位置。将形状对齐到幻灯片的边距或边缘<br/>            或相互对齐。 |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/zh/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | 搜索指定幻灯片上匹配给定占位符类型的所有形状。 |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/zh/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | 在演示文稿中查找并替换具有指定格式的文本 |
| [`get_all_text_boxes(slide)`](/slides/python-net/zh/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | 返回 PPTX 演示文稿中幻灯片上的所有文本框。 |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/zh/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | 返回指定幻灯片上包含给定文本的所有文本框。 |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/zh/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | 返回 PPTX 演示文稿中的所有文本框。 |
| [`to_save_format(format)`](/slides/python-net/zh/aspose.slides.util/slideutil/to_save_format/#sourceformat) | 将源文件格式转换为相应的 [`SaveFormat`](/slides/python-net/zh/aspose.slides.export/saveformat)。 |

### 另请参阅
* 模块 [`aspose.slides.util`](/slides/python-net/zh/aspose.slides.util)
* 库 [`Aspose.Slides`](/slides/python-net)