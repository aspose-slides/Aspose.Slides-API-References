---
title: add_from_html method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Thêm văn bản từ chuỗi html được chỉ định vào bộ sưu tập.


```python
def add_from_html(self, text):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| text | **str** | Văn bản HTML. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Thêm văn bản từ chuỗi html được chỉ định vào bộ sưu tập.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| text | **str** | Văn bản HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/iexternalresourceresolver) | Đối tượng callback resolver, giải quyết các URI và lấy các đối tượng được tham chiếu. |
| uri | **str** | URI để thêm tài liệu HTML. Được sử dụng để giải quyết các liên kết tương đối. |

### Ghi chú

Việc chỉ định resolver có thể tiềm ẩn một lỗ hổng bảo mật. Hãy sử dụng một cách thận trọng.



### Xem thêm
* lớp [`IExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/iexternalresourceresolver)
* lớp [`IParagraphCollection`](/slides/python-net/vi/aspose.slides/iparagraphcollection)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)