---
title: SlideUtil class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.util/slideutil/
---
## SlideUtil 類別

提供可協助在簡報中搜尋形狀與文字的方法。

SlideUtil 類型公開以下成員：

## 方法

| 方法 | 說明 |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/zh-hant/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | 在 PPTX 簡報中以替代文字尋找形狀。 |
| [`find_shape(slide, alt_text)`](/slides/python-net/zh-hant/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | 在 PPTX 簡報的投影片上以替代文字尋找形狀。 |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/zh-hant/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | 變更投影片上所有形狀的位置。將形狀對齊至投影片的邊緣或邊框<br/>            或相對於彼此對齊。 |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/zh-hant/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | 變更投影片上選取形狀的位置。將形狀對齊至投影片的邊緣或邊框<br/>            或相對於彼此對齊。 |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/zh-hant/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | 變更群組形狀內所有形狀的位置。將形狀對齊至投影片的邊緣或邊框<br/>            或相對於彼此對齊。 |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/zh-hant/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | 變更群組形狀內選取形狀的位置。將形狀對齊至投影片的邊緣或邊框<br/>            或相對於彼此對齊。 |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/zh-hant/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | 搜尋指定投影片上所有符合給定占位符類型的形狀。 |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/zh-hant/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | 在簡報中以給定格式尋找並取代文字 |
| [`get_all_text_boxes(slide)`](/slides/python-net/zh-hant/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | 取得 PPTX 簡報中投影片上的所有文字框。 |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/zh-hant/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | 取得指定投影片中包含給定文字的所有文字框。 |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/zh-hant/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | 取得 PPTX 簡報中的所有文字框。 |
| [`to_save_format(format)`](/slides/python-net/zh-hant/aspose.slides.util/slideutil/to_save_format/#sourceformat) | 將來源檔案格式轉換為相對應的 [`SaveFormat`](/slides/python-net/zh-hant/aspose.slides.export/saveformat)。 |

### 另請參閱
* 模組 [`aspose.slides.util`](/slides/python-net/zh-hant/aspose.slides.util)
* 函式庫 [`Aspose.Slides`](/slides/python-net)