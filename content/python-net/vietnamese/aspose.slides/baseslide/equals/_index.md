---
title: equals method
second_title: Aspose.Slides cho Python qua .NET Tham khảo API
description: 
type: docs
url: /vi/aspose.slides/baseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Xác định xem hai đối tượng IBaseSlide có bằng nhau hay không.
            Giá trị trả về được tính dựa trên cấu trúc và nội dung tĩnh của slide.
            Hai slide bằng nhau nếu tất cả các shape, style, text, animation và các cài đặt khác, v.v. đều bằng nhau. So sánh không tính đến các giá trị định danh duy nhất, ví dụ SlideId, và nội dung động, ví dụ giá trị ngày hiện tại trong Date Placeholder.

### Giá trị trả về

**true** nếu IBaseSlide được chỉ định bằng với IBaseSlide hiện tại; 
            nếu không, **false** .



```python
def equals(self, slide):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide) | IBaseSlide để so sánh với IBaseSlide hiện tại. |



### Xem thêm
* lớp [`BaseSlide`](/slides/python-net/vi/aspose.slides/baseslide)
* lớp [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)