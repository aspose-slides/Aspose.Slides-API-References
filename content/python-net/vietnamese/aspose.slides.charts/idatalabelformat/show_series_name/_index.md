---
title: show_series_name property
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name thuộc tính
Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên chuỗi cho các nhãn dữ liệu trên biểu đồ. 
True để hiển thị tên chuỗi. False để ẩn.
Đọc/ghi **bool**.

### Ghi chú

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu, thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của ShowSeriesName property cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho ShowSeriesName property của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ: "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" gây ra mọi DataLabels[i].ShowSeriesName bằng val).

### Định nghĩa:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```

### Xem thêm
* lớp [`IDataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)