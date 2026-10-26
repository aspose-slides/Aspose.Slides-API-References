---
title: show_series_name property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name thuộc tính
Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên series cho các nhãn dữ liệu trên biểu đồ. 
            True để hiển thị tên series. False để ẩn.
            Đọc/ghi **bool**.

### Ghi chú

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection các nhãn dữ liệu thì
            thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowSeriesName cho các nhãn dữ liệu mới trong DataLabelCollection.
            Đặt thuộc tính này với giá trị cũng đặt giá trị này cho thuộc tính ShowSeriesName cho tất cả các nhãn dữ liệu trong DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" cause to 
            all DataLabels[i].ShowSeriesName is equal to val).

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
* lớp [`DataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)