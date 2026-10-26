---
title: show_value property
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value thuộc tính
Đại diện cho hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ được chỉ định. 
True hiển thị giá trị phần trăm. False để ẩn.
Đọc/ghi **bool**.

### Ghi chú

Nếu phụ huynh của đối tượng DataLabelFormat này là một tập hợp DataLabelCollection của các nhãn dữ liệu thì
thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowValue cho các nhãn dữ liệu mới trong
tập hợp DataLabelCollection.
Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowValue
cho tất cả các nhãn dữ liệu trong tập hợp DataLabelCollection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" dẫn đến
tất cả DataLabels[i].ShowValue bằng val).

### Định nghĩa:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### Xem thêm
* lớp [`DataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/datalabelformat)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)