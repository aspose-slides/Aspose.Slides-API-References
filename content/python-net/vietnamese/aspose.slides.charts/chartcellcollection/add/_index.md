---
title: add method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Thêm ô mới vào bộ sưu tập.

```python
def add(self, cell):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell) | Ô mới để thêm. |

## add(self, value) {#any}
Tạo [`ChartDataCell`](/slides/python-net/vi/aspose.slides.charts/chartdatacell) từ giá trị được chỉ định và thêm nó vào bộ sưu tập.

```python
def add(self, value):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| value | **any** | Giá trị. |

### Ghi chú

Phương thức này thêm bảng tính có tên AUTO_DATA và thêm tất cả các giá trị vào đó. Nếu bạn sử dụng [`ChartDataWorkbook`](/slides/python-net/vi/aspose.slides.charts/chartdataworkbook) để thêm hoặc chỉnh sửa giá trị Cell, hãy chắc chắn rằng bạn không sử dụng bảng tính này
Số lượng tối đa các giá trị được thêm bằng phương thức này không được vượt quá 16711680

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | nếu vượt quá giới hạn |

### Xem thêm
* lớp [`ChartCellCollection`](/slides/python-net/vi/aspose.slides.charts/chartcellcollection)
* lớp [`ChartDataCell`](/slides/python-net/vi/aspose.slides.charts/chartdatacell)
* lớp [`ChartDataWorkbook`](/slides/python-net/vi/aspose.slides.charts/chartdataworkbook)
* lớp [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)