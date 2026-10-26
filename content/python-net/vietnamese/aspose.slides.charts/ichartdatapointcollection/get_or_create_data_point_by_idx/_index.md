---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Nếu bộ sưu tập đã chứa điểm dữ liệu với chỉ mục `index` thì trả về điểm dữ liệu này.
            Nếu bộ sưu tập không chứa điểm dữ liệu với chỉ mục `index`==N
            (khi số lượng điểm dữ liệu trong bộ sưu tập này ít hơn hoặc bằng N)
            thì thêm các điểm dữ liệu thiếu và trả về điểm cuối cùng (có chỉ mục yêu cầu).
            Ví dụ, các chỉ mục của bộ sưu tập là {0, 1, 2}, và chỉ mục được yêu cầu là 5.
            Khi đó phương thức thêm các điểm dữ liệu thiếu: {0, 1, 2, 3, 4, 5}. Và trả về điểm dữ liệu với chỉ mục 5.

### Trả về

Trả về điểm dữ liệu với chỉ mục đã yêu cầu.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục. |



### Xem thêm
* lớp [`IChartDataPoint`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint)
* lớp [`IChartDataPointCollection`](/slides/python-net/vi/aspose.slides.charts/ichartdatapointcollection)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)