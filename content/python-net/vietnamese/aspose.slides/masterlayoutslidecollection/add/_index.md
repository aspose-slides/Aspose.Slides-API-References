---
title: add method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/masterlayoutslidecollection/add/
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
| layout_type | [`SlideLayoutType`](/slides/python-net/vi/aspose.slides/slidelayouttype) | Loại bố cục cho một bố cục mới.<br/><br/>            Các loại bố cục được hỗ trợ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Các loại bố cục khác hiện không được hỗ trợ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Tên cho một bố cục mới. Nếu tên đã được sử dụng, ArgumentException sẽ được ném.<br/><br/>            Nếu tham số None được truyền, tên sẽ được tạo tự động dựa trên loại bố cục đã truyền <br/><br/>            (ví dụ "Title Slide" hoặc "1_Title Slide", "2_..", v.v.). |

### Ghi chú

1) Bố cục đã thêm cho giá trị SlideLayoutType.Custom của `layout_type` không chứa placeholder và không có hình dạng.  
2) Tương tự của phương thức này là phương thức **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** được truy cập bằng thuộc tính [`IPresentation.layout_slides`](/slides/python-net/vi/aspose.slides/ipresentation/layout_slides).

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Được ném nếu giá trị không được hỗ trợ của tham số `layout_type` được truyền. Các loại bố cục hiện không được hỗ trợ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Được ném nếu giá trị tên bố cục `layout_name` đã được sử dụng trong <br/>            bộ sưu tập các bố cục này. |

### Xem thêm
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`MasterLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/vi/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)