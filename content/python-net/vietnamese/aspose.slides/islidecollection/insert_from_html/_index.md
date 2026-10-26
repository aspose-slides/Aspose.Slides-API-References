---
title: insert_from_html method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

### Giá trị trả về

Các slide đã thêm



```python
def insert_from_html(self, index, html_text):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Vị trí chèn. |
| html_text | **str** | HTML để thêm. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

### Giá trị trả về

Các slide đã thêm



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Vị trí chèn. |
| html_stream | **io.RawIOBase** | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

### Giá trị trả về

Các slide đã thêm



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Vị trí chèn. |
| html_text | **str** | HTML để thêm. |
| use_slide_with_index_as_start | **bool** | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục được chỉ định.<br/><br/>Nếu **true** , thì việc chèn dữ liệu sẽ bắt đầu từ không gian trống trên slide có chỉ mục được chỉ định.<br/><br/>Nếu **false** , thì dữ liệu sẽ được thêm vào các slide đã tạo. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

### Giá trị trả về

Các slide đã thêm



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Vị trí chèn. |
| html_stream | **io.RawIOBase** | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |
| use_slide_with_index_as_start | **bool** | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục được chỉ định.<br/><br/>Nếu **true** , thì việc chèn dữ liệu sẽ bắt đầu từ không gian trống trên slide có chỉ mục được chỉ định.<br/><br/>Nếu **false** , thì dữ liệu sẽ được thêm vào các slide đã tạo. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

### Giá trị trả về

Các slide đã thêm.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Vị trí chèn. |
| html_text | **str** | HTML để thêm. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/iexternalresourceresolver) | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là None thì tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | **str** | URI của HTML được chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

### Giá trị trả về

Các slide đã thêm.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Vị trí chèn. |
| html_stream | **io.RawIOBase** | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/iexternalresourceresolver) | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là None thì tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | **str** | URI của HTML được chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

### Giá trị trả về

Các slide đã thêm.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Vị trí chèn. |
| html_text | **str** | HTML để thêm. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/iexternalresourceresolver) | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là None thì tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | **str** | URI của HTML được chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |
| use_slide_with_index_as_start | **bool** | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục được chỉ định.<br/><br/>Nếu **true** , thì việc chèn dữ liệu sẽ bắt đầu từ không gian trống trên slide có chỉ mục được chỉ định.<br/><br/>Nếu **false** , thì dữ liệu sẽ được thêm vào các slide đã tạo. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

### Giá trị trả về

Các slide đã thêm.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Vị trí chèn. |
| html_stream | **io.RawIOBase** | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/iexternalresourceresolver) | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là None thì tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | **str** | URI của HTML được chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |
| use_slide_with_index_as_start | **bool** | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục được chỉ định.<br/><br/>Nếu **true** , thì việc chèn dữ liệu sẽ bắt đầu từ không gian trống trên slide có chỉ mục được chỉ định.<br/><br/>Nếu **false** , thì dữ liệu sẽ được thêm vào các slide đã tạo. |



### Xem thêm
* class [`IExternalResourceResolver`](/slides/python-net/vi/aspose.slides.importing/iexternalresourceresolver)
* class [`ISlideCollection`](/slides/python-net/vi/aspose.slides/islidecollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)