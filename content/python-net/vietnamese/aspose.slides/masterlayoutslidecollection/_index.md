---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection lớp

Đại diện cho một tập hợp các slide bố cục của slide chủ đã xác định.  
Kế thừa lớp LayoutSlideCollection với các phương thức để thêm/chèn/xóa/nhân bản/sắp xếp lại các slide bố cục trong ngữ cảnh của các bộ sưu tập riêng lẻ của các slide bố cục của slide chủ.

**Kế thừa:**[`MasterLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/vi/aspose.slides/layoutslidecollection)

Kiểu MasterLayoutSlideCollection cung cấp các thành viên sau:

## Bộ chỉ mục

| Tên | Mô tả |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Trả về slide bố cục đầu tiên của loại được chỉ định.<br/>Loại slide bố cục cần tìm.[`LayoutSlide`](/slides/python-net/vi/aspose.slides/layoutslide) với loại được chỉ định hoặc None nếu không tìm thấy layout nào. |
| [`remove(self, value)`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Xóa một layout khỏi bộ sưu tập. |
| [`remove_unused(self)`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Xóa các slide bố cục không sử dụng (các slide bố cục có HasDependingSlides bằng false). |
| [`add_clone(self, source_layout)`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | Thêm một bản sao của slide bố cục đã chỉ định vào cuối bộ sưu tập. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | Chèn một bản sao của slide bố cục đã chỉ định vào vị trí được chỉ định trong bộ sưu tập. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Thêm một slide bố cục mới vào cuối bộ sưu tập. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Chèn một slide bố cục mới vào vị trí được chỉ định trong bộ sưu tập. |
| [`remove_at(self, index)`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Xóa phần tử tại chỉ mục được chỉ định trong bộ sưu tập. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Di chuyển slide bố cục từ bộ sưu tập đến vị trí được chỉ định. |

### Xem Thêm
* lớp [`LayoutSlideCollection`](/slides/python-net/vi/aspose.slides/layoutslidecollection)
* lớp [`MasterLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)