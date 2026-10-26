---
title: separator property
second_title: Tham chiếu API cho Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## Thuộc tính Separator
Thiết lập hoặc trả về một Variant đại diện cho Separator được sử dụng cho các nhãn dữ liệu trên biểu đồ.
            Đọc/ghi **str**.

### Ghi chú
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            thuộc tính này lấy hoặc thiết lập giá trị mặc định của thuộc tính Separator cho các
            nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection.
            Đặt thuộc tính này với giá trị cũng sẽ thiết lập giá trị này cho thuộc tính Separator 
            cho tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection
            (ví dụ "DataLabels.DefaultDataLabelFormat.Separator = val;" gây ra 
            tất cả DataLabels[i].Separator bằng với giá trị val).

### Định nghĩa:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```

### Xem thêm
* lớp [`IDataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)