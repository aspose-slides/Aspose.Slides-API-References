---
title: from_argb method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
Tạo một màu từ giá trị ARGB 32-bit.

### Trả về

Màu được tạo từ giá trị đã chỉ định.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| argb | **int** | Giá trị xác định giá trị ARGB 32-bit (có dấu hoặc không dấu). |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **ValueError** | Giá trị thành phần nhỏ hơn 0 hoặc lớn hơn 255. |
| **TypeError** | Số lượng hoặc kiểu đối số không đúng. |


## from_argb(alpha, base_color) {#int-color}
Tạo một màu từ giá trị alpha và màu nền đã chỉ định.

### Trả về

Màu được tạo từ các giá trị đã chỉ định.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| alpha | **int** | Giá trị thành phần alpha. Các giá trị hợp lệ từ 0 đến 255. |
| base_color | [`Color`](/slides/python-net/vi/aspose.slides/color) | Màu dùng để tạo màu mới. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **ValueError** | Giá trị thành phần nhỏ hơn 0 hoặc lớn hơn 255. |
| **TypeError** | Số lượng hoặc kiểu đối số không đúng. |


## from_argb(red, green, blue) {#int-int-int}
Tạo một màu không trong suốt (alpha là 255) từ các giá trị đỏ, xanh lá và xanh dương đã chỉ định.

### Trả về

Màu được tạo từ các giá trị đã chỉ định.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| red | **int** | Giá trị thành phần đỏ. Các giá trị hợp lệ từ 0 đến 255. |
| green | **int** | Giá trị thành phần xanh lá. Các giá trị hợp lệ từ 0 đến 255. |
| blue | **int** | Giá trị thành phần xanh dương. Các giá trị hợp lệ từ 0 đến 255. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **ValueError** | Giá trị thành phần nhỏ hơn 0 hoặc lớn hơn 255. |
| **TypeError** | Số lượng hoặc kiểu đối số không đúng. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Tạo một màu từ bốn giá trị thành phần ARGB (alpha, đỏ, xanh lá và xanh dương).

### Trả về

Màu được tạo từ các giá trị đã chỉ định.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| alpha | **int** | Giá trị thành phần alpha. Các giá trị hợp lệ từ 0 đến 255. |
| red | **int** | Giá trị thành phần đỏ. Các giá trị hợp lệ từ 0 đến 255. |
| green | **int** | Giá trị thành phần xanh lá. Các giá trị hợp lệ từ 0 đến 255. |
| blue | **int** | Giá trị thành phần xanh dương. Các giá trị hợp lệ từ 0 đến 255. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **ValueError** | Giá trị thành phần nhỏ hơn 0 hoặc lớn hơn 255. |
| **TypeError** | Số lượng hoặc kiểu đối số không đúng. |



### Xem thêm
* lớp [`Color`](/slides/python-net/vi/aspose.slides/color)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)