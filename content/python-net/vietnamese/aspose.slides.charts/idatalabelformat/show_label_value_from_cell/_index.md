---
title: show_label_value_from_cell property
second_title: Aspose.Slides for Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell thuộc tính
Biểu thị hành vi hiển thị giá trị ô nhãn dữ liệu của biểu đồ đã chỉ định. 
            True hiển thị giá trị ô. False để ẩn.
            Đọc/ghi **bool**.

### Ghi chú

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì
            thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelValueFromCell cho các nhãn dữ liệu mới
            trong bộ sưu tập DataLabelCollection.
            Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelValueFromCell
            cho tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" gây ra
            tất cả DataLabels[i].ShowLabelValueFromCell bằng val).

### Định nghĩa:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```

### Xem thêm
* lớp [`IDataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)