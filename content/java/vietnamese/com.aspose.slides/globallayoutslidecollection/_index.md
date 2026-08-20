---
title: GlobalLayoutSlideCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một bộ sưu tập của tất cả các slide bố cục trong bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/globallayoutslidecollection/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Biểu diễn một bộ sưu tập của tất cả các slide bố cục trong bản trình chiếu. Kế thừa lớp LayoutSlideCollection với các phương thức để thêm/nhân bản slide bố cục trong ngữ cảnh hợp nhất các bộ sưu tập riêng lẻ của các slide bố cục của master.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Thêm một bản sao của slide bố cục được chỉ định vào bản trình chiếu. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Thêm một bản sao của slide bố cục được chỉ định vào bản trình chiếu. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Thêm một slide bố cục mới vào bản trình chiếu. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Thêm một bản sao của slide bố cục được chỉ định vào bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide để nhân bản. 

--------------------

Khi sao chép một bố cục giữa các bản trình chiếu khác nhau, master của bố cục cũng có thể được sao chép để giữ định dạng nguồn. Registry nội bộ được sử dụng để theo dõi các master được sao chép tự động nhằm ngăn tạo nhiều bản sao của cùng một slide master. Việc sao chép thủ công các slide master sẽ không bị ngăn cản cũng không được ghi nhận. 

**Giá trị trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide đã thêm.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Thêm một bản sao của slide bố cục được chỉ định vào bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide để nhân bản. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide master cho một bố cục mới. 

--------------------

1) Bố cục mới sẽ được liên kết với master đã định nghĩa trong bản trình chiếu đích. Do đó đây là tương tự của sao chép/dán với tùy chọn "Use Destination Theme" trong PowerPoint. 2) Tương tự của phương thức này là phương thức [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) được truy cập bằng thuộc tính ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). 

**Giá trị trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide đã thêm.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Thêm một slide bố cục mới vào bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide master cho một bố cục mới. |
| layoutType | byte | Kiểu bố cục cho một bố cục mới. Các kiểu bố cục được hỗ trợ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Các kiểu bố cục khác hiện không được hỗ trợ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Tên cho một bố cục mới. Nếu tên đã được sử dụng, sẽ ném ArgumentException. Nếu truyền tham số null, thì tên sẽ được tạo tự động dựa trên kiểu bố cục đã truyền (ví dụ "Title Slide" hoặc "1_Title Slide", "2_..", v.v.). 

--------------------

1) Bố cục đã thêm cho giá trị SlideLayoutType.Custom của layoutType không chứa placeholder và không có hình dạng. 2) Tương tự của phương thức này là phương thức [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) được truy cập bằng thuộc tính ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). 

**Giá trị trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide đã thêm.