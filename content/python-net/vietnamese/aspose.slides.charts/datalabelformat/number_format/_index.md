---
title: number_format property
second_title: Tài liệu tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format thuộc tính
Biểu diễn chuỗi định dạng cho đối tượng DataLabels.
            Đọc/ghi **str**.


### Ghi chú

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection chứa các nhãn dữ liệu, thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính NumberFormat cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection.
            Khi thuộc tính này được đặt bằng một giá trị, giá trị đó cũng được đặt cho thuộc tính NumberFormat của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ: "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" làm cho tất cả DataLabels[i].NumberFormat bằng val).

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
* lớp [`DataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)