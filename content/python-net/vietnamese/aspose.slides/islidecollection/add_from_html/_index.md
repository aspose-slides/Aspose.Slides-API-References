---
title: add_from_html method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/islidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

### Returns
Các slide đã được thêm



```python
def add_from_html(self, html_text):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| html_text | **str** | HTML để thêm. |


## add_from_html(self, html_stream) {#iorawiobase}
Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

### Returns
Các slide đã được thêm



```python
def add_from_html(self, html_stream):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

### Returns
Các slide đã được thêm.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| html_text | **str** | HTML để thêm. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/iexternalresourceresolver) | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là None, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | **str** | Một URI của HTML đã chỉ định. Được dùng để giải quyết các liên kết tương đối. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

### Returns
Các slide đã được thêm.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/iexternalresourceresolver) | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là None, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | **str** | Một URI của HTML đã chỉ định. Được dùng để giải quyết các liên kết tương đối. |



### See Also
* lớp [`IExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/iexternalresourceresolver)
* lớp [`ISlideCollection`](/slides/python-net/vi/aspose.slides/islidecollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)