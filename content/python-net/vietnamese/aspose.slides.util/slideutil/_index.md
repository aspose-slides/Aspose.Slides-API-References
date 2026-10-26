---
title: SlideUtil class
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.util/slideutil/
---
## SlideUtil lớp

Cung cấp các phương thức giúp tìm kiếm các hình dạng và văn bản trong một bản trình chiếu.

Kiểu SlideUtil khai báo các thành viên sau:

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`find_shape(pres, alt_text)`](/slides/python-net/vi/aspose.slides.util/slideutil/find_shape/#ipresentation-str) | Tìm hình dạng theo văn bản thay thế trong bản trình chiếu PPTX. |
| [`find_shape(slide, alt_text)`](/slides/python-net/vi/aspose.slides.util/slideutil/find_shape/#ibaseslide-str) | Tìm hình dạng theo văn bản thay thế trên một slide trong bản trình chiếu PPTX. |
| [`align_shapes(alignment_type, align_to_slide, slide)`](/slides/python-net/vi/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide) | Thay đổi vị trí của tất cả các hình dạng trên slide. Căn chỉnh các hình dạng với lề hoặc cạnh của slide<br/>            hoặc căn chúng tương đối với nhau. |
| [`align_shapes(alignment_type, align_to_slide, slide, shape_indexes)`](/slides/python-net/vi/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-ibaseslide-listint) | Thay đổi vị trí của các hình dạng đã chọn trên slide. Căn chỉnh các hình dạng với lề hoặc cạnh của slide<br/>             hoặc căn chúng tương đối với nhau. |
| [`align_shapes(alignment_type, align_to_slide, group_shape)`](/slides/python-net/vi/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape) | Thay đổi vị trí của tất cả các hình dạng trong nhóm hình dạng. Căn chỉnh các hình dạng với lề hoặc cạnh của slide<br/>            hoặc căn chúng tương đối với nhau. |
| [`align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes)`](/slides/python-net/vi/aspose.slides.util/slideutil/align_shapes/#shapesalignmenttype-bool-igroupshape-listint) | Thay đổi vị trí của các hình dạng đã chọn trong nhóm hình dạng. Căn chỉnh các hình dạng với lề hoặc cạnh của slide<br/>            hoặc căn chúng tương đối với nhau. |
| [`find_shapes_by_placeholder_type(slide, placeholder_type)`](/slides/python-net/vi/aspose.slides.util/slideutil/find_shapes_by_placeholder_type/#ibaseslide-placeholdertype) | Tìm kiếm tất cả các hình dạng trên slide được chỉ định phù hợp với loại placeholder đã cho. |
| [`find_and_replace_text(presentation, with_masters, find, replace, format)`](/slides/python-net/vi/aspose.slides.util/slideutil/find_and_replace_text/#ipresentation-bool-str-str-portionformat) | Tìm và thay thế văn bản trong bản trình chiếu bằng định dạng đã cho |
| [`get_all_text_boxes(slide)`](/slides/python-net/vi/aspose.slides.util/slideutil/get_all_text_boxes/#ibaseslide) | Trả về tất cả các khung văn bản trên một slide trong bản trình chiếu PPTX. |
| [`get_text_boxes_contains_text(slide, text, check_placeholder_text)`](/slides/python-net/vi/aspose.slides.util/slideutil/get_text_boxes_contains_text/#ibaseslide-str-bool) | Trả về tất cả các khung văn bản trên slide được chỉ định chứa văn bản đã cho. |
| [`get_all_text_frames(pres, with_masters)`](/slides/python-net/vi/aspose.slides.util/slideutil/get_all_text_frames/#ipresentation-bool) | Trả về tất cả các khung văn bản trong bản trình chiếu PPTX. |
| [`to_save_format(format)`](/slides/python-net/vi/aspose.slides.util/slideutil/to_save_format/#sourceformat) | Chuyển đổi định dạng tệp nguồn sang [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) tương ứng. |

### Xem thêm
* module [`aspose.slides.util`](/slides/python-net/vi/aspose.slides.util)
* thư viện [`Aspose.Slides`](/slides/python-net)