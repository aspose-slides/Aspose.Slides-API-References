---
title: number_format property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format thuộc tính
Đại diện cho chuỗi định dạng cho đối tượng DataLabels.
Đọc/ghi **str**.

### Ghi chú

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection of data labels, thì thuộc tính này lấy hoặc đặt giá trị mặc định của NumberFormat property cho các nhãn dữ liệu mới trong DataLabelCollection collection.
Khi thuộc tính này được đặt một giá trị, giá trị đó cũng được đặt cho NumberFormat property cho tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" causes all DataLabels[i].NumberFormat to equal to val).

### Định nghĩa:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```

### Xem thêm
* lớp [`IDataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)