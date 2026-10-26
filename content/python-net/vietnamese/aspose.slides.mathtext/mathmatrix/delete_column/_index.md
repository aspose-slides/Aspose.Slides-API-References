---
title: delete_column method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Xóa cột đã chỉ định


```python
def delete_column(self, column_index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| column_index | **int** | Chỉ mục bắt đầu từ 0 của cột cần xóa. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Khi bạn cố gắng xóa cột duy nhất cuối cùng trong ma trận |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Nếu columnIndex nhỏ hơn 0 hoặc lớn hơn hoặc bằng ColumnCount |



### Xem thêm
* lớp [`MathMatrix`](/slides/python-net/vi/aspose.slides.mathtext/mathmatrix)
* module [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)