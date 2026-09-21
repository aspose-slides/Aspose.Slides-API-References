---
title: insert method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Chèn một slide bố cục mới vào vị trí được chỉ định trong bộ sưu tập.

### Trả về

Slide đã được chèn.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ số của slide mới. |
| layout_type | [`SlideLayoutType`](/slides/python-net/vi/aspose.slides/slidelayouttype) | Kiểu bố cục cho một bố cục mới.<br/><br/>            Các kiểu bố cục được hỗ trợ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Các kiểu bố cục khác hiện không được hỗ trợ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Tên cho một bố cục mới. Nếu tên đã được sử dụng, ArgumentException sẽ được ném.<br/><br/>            Nếu truyền tham số None, thì tên sẽ được tạo tự động dựa trên kiểu bố cục đã truyền <br/><br/>            (ví dụ “Title Slide” hoặc “1_Title Slide”, “2_..”, v.v.). |

### Ghi chú

Bố cục đã chèn cho giá trị SlideLayoutType.Custom của `layout_type` không chứa chỗ giữ chỗ và không có hình dạng nào.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Bị ném nếu giá trị không được hỗ trợ của tham số `layout_type` được truyền. Các kiểu bố cục hiện không được hỗ trợ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném nếu giá trị tên bố cục `layout_name` đã được sử dụng trong <br/>            bộ sưu tập các bố cục này. |

### Xem thêm
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`MasterLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection)
* liệt kê [`SlideLayoutType`](/slides/python-net/vi/aspose.slides/slidelayouttype)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)