---
title: Sequence class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.animation/sequence/
---
## Lớp Sequence

Biểu diễn chuỗi (tập hợp các hiệu ứng).

Kiểu Sequence cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`count`](/slides/python-net/vi/aspose.slides.animation/sequence/count/) | Trả về số lượng hiệu ứng trong một chuỗi.<br/>            Chỉ-đọc **int**. |
| [`trigger_shape`](/slides/python-net/vi/aspose.slides.animation/sequence/trigger_shape/) | Trả về hoặc đặt mục tiêu hình cho chuỗi INTERACTIVE.<br/>            Nếu chuỗi không tương tác thì trả về None.<br/>            Đọc/ghi [`IShape`](/slides/python-net/vi/aspose.slides/ishape). |

Trả về một hiệu ứng tại chỉ số được chỉ định.

## Bộ chỉ mục

| Tên | Mô tả |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides.animation/sequence/__getitem__/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/vi/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Thêm hiệu ứng mới vào cuối chuỗi. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/vi/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Thêm hiệu ứng hoạt hình mới cho đoạn văn vào cuối chuỗi. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/vi/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Thêm hiệu ứng hoạt hình biểu đồ mới cho danh mục hoặc chuỗi vào cuối chuỗi. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/vi/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Thêm hiệu ứng hoạt hình biểu đồ mới cho các phần tử trong danh mục hoặc chuỗi vào cuối chuỗi. |
| [`remove(self, item)`](/slides/python-net/vi/aspose.slides.animation/sequence/remove/#ieffect) | Xóa hiệu ứng được chỉ định khỏi bộ sưu tập. |
| [`remove_at(self, index)`](/slides/python-net/vi/aspose.slides.animation/sequence/remove_at/#int) | Xóa một hiệu ứng khỏi bộ sưu tập. |
| [`clear(self)`](/slides/python-net/vi/aspose.slides.animation/sequence/clear/#) | Xóa tất cả các hiệu ứng khỏi bộ sưu tập. |
| [`remove_by_shape(self, shape)`](/slides/python-net/vi/aspose.slides.animation/sequence/remove_by_shape/#ishape) | Xóa hiệu ứng cho hình đã chỉ định. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/vi/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | Trả về mảng các hiệu ứng cho hình đã chỉ định. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/vi/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | Trả về mảng các hiệu ứng cho đoạn văn đã chỉ định. |
| [`get_count(self, shape)`](/slides/python-net/vi/aspose.slides.animation/sequence/get_count/#ishape) | Trả về số lượng hiệu ứng cho hình đã chỉ định. |

### Xem Thêm
* mô-đun [`aspose.slides.animation`](/slides/python-net/vi/aspose.slides.animation)
* thư-viện [`Aspose.Slides`](/slides/python-net)