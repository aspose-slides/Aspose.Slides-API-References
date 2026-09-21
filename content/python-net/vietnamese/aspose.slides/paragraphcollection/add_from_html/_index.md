---
title: add_from_html method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/paragraphcollection/add_from_html/
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
| resolver | [`IExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/iexternalresourceresolver) | Đối tượng callback Resolver mà giải quyết URI và lấy các đối tượng được tham chiếu. |
| uri | **str** | URI để thêm tài liệu HTML. Được sử dụng để giải quyết các liên kết tương đối. |

### Ghi chú

Việc chỉ định resolver có thể tiềm ẩn một lỗ hổng. Hãy sử dụng cẩn thận.

### Xem thêm
* class [`IExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/iexternalresourceresolver)
* class [`ParagraphCollection`](/slides/python-net/vi/aspose.slides/paragraphcollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)