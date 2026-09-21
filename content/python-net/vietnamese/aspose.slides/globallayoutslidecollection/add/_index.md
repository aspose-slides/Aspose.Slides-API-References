---
title: add method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Thêm một slide bố cục mới vào bản trình bày.

### Giá trị trả về

Slide đã được thêm.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/vi/aspose.slides/imasterslide) | Master slide for a new layout. |
| layout_type | [`SlideLayoutType`](/slides/python-net/vi/aspose.slides/slidelayouttype) | Kiểu bố cục cho một bố cục mới.<br/><br/>            Các kiểu bố cục được hỗ trợ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Các kiểu bố cục khác hiện không được hỗ trợ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Tên cho một bố cục mới. Nếu tên đã được sử dụng, ArgumentException sẽ được ném.<br/><br/>            Nếu tham số None được truyền vào thì tên sẽ được tạo tự động dựa trên kiểu bố cục đã truyền <br/><br/>            (ví dụ "Title Slide" hoặc "1_Title Slide", "2_..", v.v.). |

### Ghi chú

1) Bố cục đã thêm cho giá trị SlideLayoutType.Custom của `layout_type` 
            không chứa bất kỳ placeholder nào và không có hình dạng.
2) Tương đương của phương thức này là phương thức **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste**
            được truy cập bằng thuộc tính [`IMasterSlide.layout_slides`](/slides/python-net/vi/aspose.slides/imasterslide/layout_slides).

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Được ném nếu giá trị không hỗ trợ của tham số `layout_type` được truyền. Các kiểu bố cục hiện không được hỗ trợ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Được ném nếu `master` là None. |
| **RuntimeError(Proxy error(ArgumentException))** | Được ném nếu `master` thuộc về bản trình bày khác. |
| **RuntimeError(Proxy error(ArgumentException))** | Được ném nếu giá trị tên bố cục `layout_name` đã được sử dụng trong <br/>            bộ sưu tập các bố cục của `master`. |



### Xem thêm
* lớp [`GlobalLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/globallayoutslidecollection)
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`IMasterSlide`](/slides/python-net/vi/aspose.slides/imasterslide)
* liệt kê [`SlideLayoutType`](/slides/python-net/vi/aspose.slides/slidelayouttype)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)