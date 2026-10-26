---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho một tập hợp của tất cả các slide bố cục trong bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/igloballayoutslidecollection/
---
**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Đại diện cho một tập hợp của tất cả các slide bố cục trong bản trình chiếu. Mở rộng giao diện ILayoutSlideCollection với các phương thức để thêm/nhân bản slide bố cục trong bối cảnh hợp nhất các bộ sưu tập riêng lẻ của slide bố cục của master.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Thêm một bản sao của slide bố cục được chỉ định vào bản trình chiếu. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Thêm một bản sao của slide bố cục được chỉ định vào bản trình chiếu. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Thêm một slide bố cục mới vào bản trình chiếu. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Thêm một bản sao của slide bố cục được chỉ định vào bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide cần nhân bản.

--------------------

Khi nhân bản một bố cục giữa các bản trình chiếu khác nhau, master của bố cục cũng có thể được nhân bản để giữ định dạng nguồn. Thư mục nội bộ được sử dụng để theo dõi các master được nhân bản tự động nhằm ngăn việc tạo nhiều bản sao của cùng một slide master. Việc nhân bản thủ công các slide master sẽ không bị ngăn cản hoặc đăng ký. |

**Giá trị trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide đã thêm.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Thêm một bản sao của slide bố cục được chỉ định vào bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide cần nhân bản. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide master cho một bố cục mới.

--------------------

Bố cục mới sẽ được liên kết với master đã định nghĩa trong bản trình chiếu đích. Vì vậy đây là tương tự của việc sao chép/dán với tùy chọn "Use Destination Theme" trong PowerPoint. |

**Giá trị trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide đã thêm.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Thêm một slide bố cục mới vào bản trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide master cho một bố cục mới. |
| layoutType | byte | Kiểu bố cục cho một bố cục mới. Các kiểu bố cục được hỗ trợ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Các kiểu bố cục khác hiện không được hỗ trợ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Tên cho một bố cục mới. Nếu tên đã được sử dụng, sẽ ném ra ArgumentException. Nếu tham số null được truyền, thì tên sẽ được tạo tự động dựa trên kiểu bố cục đã truyền (ví dụ "Title Slide" hoặc "1_Title Slide", "2_..", v.v.). |

--------------------

1) Bố cục được thêm cho giá trị SlideLayoutType.Custom của layoutType không chứa placeholder và không có hình dạng. 2) Tương tự của phương thức này là phương thức [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) được truy cập bằng thuộc tính ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Giá trị trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide đã thêm.