---
title: add method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
Thêm phần xml tùy chỉnh mới.

### Giá trị trả về

Đã tạo phần xml tùy chỉnh.



```python
def add(self, xml_data):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| xml_data | **bytes** | Dữ liệu xml của phần mới sẽ được thêm. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData là `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData rỗng hoặc không hợp lệ. |


## add(self, xml_string) {#str}
Thêm phần xml tùy chỉnh mới.

### Giá trị trả về

Đã tạo phần xml tùy chỉnh.



```python
def add(self, xml_string):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| xml_string | **str** | Chuỗi xml của phần mới sẽ được thêm. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString là `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString rỗng hoặc dữ liệu xml không hợp lệ. |


## add(self, input_stream) {#iorawiobase}
Thêm phần xml tùy chỉnh mới.

### Giá trị trả về

Đã tạo phần xml tùy chỉnh.



```python
def add(self, input_stream):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | Luồng inputStream chứa dữ liệu xml của phần mới sẽ được thêm. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream là `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Dữ liệu trong inputStream rỗng hoặc không hợp lệ. |



### Xem thêm
* lớp [`ICustomXmlPart`](/slides/python-net/vi/aspose.slides/icustomxmlpart)
* lớp [`ICustomXmlPartCollection`](/slides/python-net/vi/aspose.slides/icustomxmlpartcollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)