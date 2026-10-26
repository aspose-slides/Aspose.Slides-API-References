---
title: overlap property
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## overlap thuộc tính
Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%).
            Đây là thuộc tính không chỉ của series này mà còn của tất cả các series trong nhóm series cha.
            Đây là một phép chiếu của thuộc tính thích hợp trong nhóm series cha, do đó thuộc tính này chỉ đọc.
            Để thay đổi giá trị, sử dụng thuộc tính read/write ParentSeriesGroup.Overlap.
            Chỉ đọc **int**.

### Ghi chú

Overlap xác định mức độ chồng lấn hoặc khoảng cách giữa các thanh và cột dưới dạng phần trăm chiều rộng của chúng:
            - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời).
            - 0%: Các thanh được đặt cạnh nhau mà không có chồng lấn hoặc khoảng cách.
            - 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau).
            Đây là một phép chiếu của thuộc tính ParentSeriesGroup.Overlap.

### Định nghĩa:
```python
@property
def overlap(self):
    ...
```

### Xem thêm
* lớp [`IChartSeries`](/slides/python-net/vi/aspose.slides.charts/ichartseries)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)