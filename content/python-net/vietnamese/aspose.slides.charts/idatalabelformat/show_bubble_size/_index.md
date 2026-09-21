---
title: show_bubble_size property
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size thuộc tính
Biểu thị hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trong biểu đồ được chỉ định. 
            True hiển thị giá trị kích thước bong bóng. False để ẩn.
            Đọc/ghi **bool**.


### Ghi chú

Nếu phần tử cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection gồm các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowBubbleSize cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection.
            Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowBubbleSize của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" khiến tất cả DataLabels[i].ShowBubbleSize bằng val).

### Định nghĩa:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```


### Xem thêm
* lớp [`IDataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)