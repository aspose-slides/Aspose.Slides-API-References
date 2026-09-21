---
title: show_legend_key property
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key thuộc tính
Đại diện cho hành vi hiển thị khóa chú thích của nhãn dữ liệu trong biểu đồ đã chỉ định.
            True nếu khóa chú thích của nhãn dữ liệu hiển thị.
            Đọc/ghi **bool**.

### Ghi chú

Nếu cha của đối tượng DataLabelFormat này là một collection DataLabelCollection chứa các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowLegendKey cho các nhãn dữ liệu mới trong collection DataLabelCollection.
            Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLegendKey của tất cả các nhãn dữ liệu trong collection DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" gây ra 
            all DataLabels[i].ShowLegendKey is equal to val).

### Định nghĩa:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### Xem thêm
* lớp [`IDataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)