---
title: show_category_name property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name thuộc tính
Mô tả hành vi hiển thị tên danh mục nhãn dữ liệu của biểu đồ được chỉ định.
            True để hiển thị tên danh mục cho các nhãn dữ liệu trên biểu đồ. False để ẩn.
            Đọc/ghi **bool**.

### Ghi chú

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì
            thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowCategoryName cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection.
            Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowCategoryName
            của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection
            (tức là "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" gây ra
            tất cả DataLabels[i].ShowCategoryName bằng với val).

### Định nghĩa:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### Xem thêm
* lớp [`DataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)