---
title: delete_row method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Xóa hàng được chỉ định


```python
def delete_row(self, row_index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| row_index | **int** | Chỉ mục dựa trên số 0 của hàng cần xóa. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Khi bạn cố gắng xóa hàng duy nhất cuối cùng trong ma trận |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Nếu rowIndex nhỏ hơn 0 hoặc lớn hơn hoặc bằng RowCount |



### Xem thêm
* lớp [`MathMatrix`](/slides/python-net/vi/aspose.slides.mathtext/mathmatrix)
* mô-đun [`aspose.slides.mathtext`](/slides/python-net/vi/aspose.slides.mathtext)
* thư viện [`Aspose.Slides`](/slides/python-net)