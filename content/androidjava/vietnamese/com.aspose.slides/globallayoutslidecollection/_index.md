---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho một bộ sưu tập tất cả các slide bố cục trong bài trình chiếu.
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

Đại diện cho một bộ sưu tập tất cả các slide bố cục trong bài trình chiếu. Kế thừa lớp LayoutSlideCollection với các phương thức để thêm/sao chép slide bố cục trong ngữ cảnh hợp nhất các bộ sưu tập riêng lẻ của các slide bố cục của master.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Thêm một bản sao của slide bố cục được chỉ định vào bài trình chiếu. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Thêm một bản sao của slide bố cục được chỉ định vào bài trình chiếu. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Thêm một slide bố cục mới vào bài trình chiếu. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Thêm một bản sao của slide bố cục được chỉ định vào bài trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide để sao chép. |

--------------------

Trong quá trình sao chép một bố cục giữa các bài trình chiếu khác nhau, master của bố cục có thể cũng được sao chép để giữ định dạng nguồn. Một registry nội bộ được sử dụng để theo dõi các master được sao chép tự động nhằm ngăn việc tạo nhiều bản sao của cùng một master slide. Việc sao chép thủ công các master slide sẽ không bị ngăn chặn và cũng không được ghi nhận.

**Giá trị trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide đã được thêm.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Thêm một bản sao của slide bố cục được chỉ định vào bài trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide để sao chép. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide cho một bố cục mới. |

--------------------

1) Bố cục mới sẽ được liên kết với master đã định nghĩa trong bài trình chiếu đích. Vì vậy đây là tương đương với thao tác sao chép/dán với tùy chọn "Use Destination Theme" trong PowerPoint. 2) Phương pháp tương đương của phương thức này là phương thức [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) được truy cập qua thuộc tính ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Giá trị trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide đã được thêm.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Thêm một slide bố cục mới vào bài trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide cho một bố cục mới. |
| layoutType | byte | Kiểu bố cục cho một bố cục mới. Các kiểu bố cục được hỗ trợ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Tên cho một bố cục mới. Nếu tên đã được sử dụng, sẽ ném ra ArgumentException. Nếu tham số null được truyền vào, thì tên sẽ được tự động tạo dựa trên kiểu bố cục đã truyền (ví dụ "Title Slide" hoặc "1_Title Slide", "2_..", v.v.). |

--------------------

1) Bố cục được thêm cho giá trị SlideLayoutType.Custom của layoutType không chứa placeholder và không có hình dạng. 2) Phương pháp tương đương của phương thức này là phương thức [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) được truy cập qua thuộc tính ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Giá trị trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide đã được thêm.