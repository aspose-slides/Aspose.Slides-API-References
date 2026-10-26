---
title: overlap property
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## thuộc tính overlap
Xác định mức độ chồng lấp của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% đến 100%).
            Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha.
            Đây là một phép chiếu của thuộc tính tương ứng trong nhóm chuỗi cha, do đó thuộc tính này chỉ đọc.
            Để thay đổi giá trị, sử dụng thuộc tính **ParentSeriesGroup.Overlap** đọc/ghi.
            Chỉ đọc **int**.

### Ghi chú

Overlap xác định mức độ chồng lấp hoặc khoảng cách giữa các thanh và cột tính theo phần trăm độ rộng của chúng:
            - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời).
            - 0%: Các thanh được đặt cạnh nhau mà không chồng lấp hoặc cách nhau.
            - 100%: Chồng lấp tối đa (các thanh hoàn toàn chồng lên nhau).
            Đây là một phép chiếu của thuộc tính **ParentSeriesGroup.Overlap**.

### Định nghĩa:
```python
@property
def overlap(self):
    ...
```

### Xem thêm
* lớp [`ChartSeries`](/slides/python-net/vi/aspose.slides.charts/chartseries)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)