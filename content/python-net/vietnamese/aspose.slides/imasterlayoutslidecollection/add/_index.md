---
title: add method
second_title: Aspose.Slides cho Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Thêm một slide bố cục mới vào cuối bộ sưu tập.

### Trả về

Slide đã thêm.



```python
def add(self, layout_type, layout_name):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/vi/aspose.slides/slidelayouttype) | Kiểu bố cục cho một bố cục mới.<br/><br/>            Các loại bố cục được hỗ trợ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Các loại bố cục khác hiện chưa được hỗ trợ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Tên cho một bố cục mới. Nếu tên đã được sử dụng, sẽ ném ArgumentException.<br/><br/>            Nếu truyền tham số None thì tên sẽ được tạo tự động dựa trên kiểu bố cục đã truyền <br/><br/>            (ví dụ “Title Slide” hoặc “1_Title Slide”, “2_..”, v.v.). |

### Ghi chú

1) Bố cục đã thêm cho giá trị SlideLayoutType.Custom của `layout_type` không chứa placeholder và không có shape.  
2) Tương tự của phương thức này là phương thức **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** được truy cập bằng thuộc tính [`IPresentation.layout_slides`](/slides/python-net/vi/aspose.slides/ipresentation/layout_slides).

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Ném nếu giá trị không hỗ trợ của tham số `layout_type` được truyền. Các loại bố cục không được hỗ trợ hiện tại: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Ném nếu giá trị `layout_name` đã tồn tại trong bộ sưu tập các bố cục này. |



### Xem thêm
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`IMasterLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/imasterlayoutslidecollection)
* liệt kê [`SlideLayoutType`](/slides/python-net/vi/aspose.slides/slidelayouttype)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)