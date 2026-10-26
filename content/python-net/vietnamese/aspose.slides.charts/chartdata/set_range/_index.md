---
title: set_range method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Đặt phạm vi dữ liệu cho biểu đồ. Các chuỗi và danh mục sẽ được cập nhật dựa trên phạm vi dữ liệu mới.
Nếu số lượng chuỗi trong phạm vi dữ liệu lớn hơn số lượng chuỗi trong dữ liệu biểu đồ thì các chuỗi bổ sung có cùng kiểu với chuỗi cuối cùng trong bộ sưu tập hiện tại sẽ được thêm vào cuối bộ sưu tập.

```python
def set_range(self, formula):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| formula | **str** | Công thức phạm vi dữ liệu ô. Ví dụ: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula là None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kiểu biểu đồ không được hỗ trợ |
| **RuntimeError(Proxy error(ArgumentException))** | formula có định dạng không đúng. |

### Xem thêm
* lớp [`ChartData`](/slides/python-net/vi/aspose.slides.charts/chartdata)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)