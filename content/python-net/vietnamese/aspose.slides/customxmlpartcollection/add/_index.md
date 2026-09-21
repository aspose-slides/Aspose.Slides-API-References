---
title: add method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
Thêm phần xml tùy chỉnh mới.

### Trả về

Phần xml tùy chỉnh đã được tạo.



```python
def add(self, xml_string):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| xml_string | **str** | Chuỗi xml của phần mới cần thêm. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString là `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString rỗng hoặc dữ liệu xml không hợp lệ. |


## add(self, xml_data) {#bytes}
Thêm phần xml tùy chỉnh mới.

### Trả về

Phần xml tùy chỉnh đã được tạo.



```python
def add(self, xml_data):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| xml_data | **bytes** | Dữ liệu xml của phần mới cần thêm. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData là `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData rỗng hoặc không hợp lệ. |


## add(self, input_stream) {#iorawiobase}
Thêm phần xml tùy chỉnh mới.

### Trả về

Phần xml tùy chỉnh đã được tạo.



```python
def add(self, input_stream):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | inputStream chứa dữ liệu xml của phần mới cần thêm. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream là `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Dữ liệu trong inputStream rỗng hoặc không hợp lệ. |



### Xem thêm
* lớp [`CustomXmlPartCollection`](/slides/python-net/vi/aspose.slides/customxmlpartcollection)
* lớp [`ICustomXmlPart`](/slides/python-net/vi/aspose.slides/icustomxmlpart)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)