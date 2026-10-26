---
title: equals method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/masterhandoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Xác định xem hai thể hiện IBaseSlide có bằng nhau hay không.
Giá trị trả về được tính dựa trên cấu trúc và nội dung tĩnh của slide.
Hai slide được coi là bằng nhau nếu tất cả các shapes, styles, texts, animation và các cài đặt khác, etc. đều bằng nhau. So sánh không tính đến các giá trị định danh duy nhất, ví dụ SlideId và nội dung động, ví dụ giá trị ngày hiện tại trong Date Placeholder.

### Trả về

**true**  nếu IBaseSlide được chỉ định bằng với IBaseSlide hiện tại; 
ngược lại, **false** .

```python
def equals(self, slide):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide) | IBaseSlide để so sánh với IBaseSlide hiện tại. |

### Xem thêm
* lớp [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide)
* lớp [`MasterHandoutSlide`](/slides/python-net/vi/aspose.slides/masterhandoutslide)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)