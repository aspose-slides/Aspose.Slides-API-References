---
title: IMasterLayoutSlideCollection
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn tập hợp tất cả các slide bố cục của master slide đã định nghĩa.
type: docs
url: /vi/com.aspose.slides/imasterlayoutslidecollection/
---
**Tất cả các Interface được triển khai:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Biểu diễn một tập hợp các slide bố cục của master slide đã định nghĩa. Kế thừa giao diện ILayoutSlideCollection với các phương thức để thêm/chèn/xóa/nhân bản các slide bố cục trong ngữ cảnh của các tập hợp slide bố cục riêng lẻ của master.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Thêm một bản sao của một slide bố cục được chỉ định vào cuối bộ sưu tập. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Chèn một bản sao của một slide bố cục được chỉ định vào vị trí xác định trong bộ sưu tập. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Thêm một slide bố cục mới vào cuối bộ sưu tập. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Chèn một slide bố cục mới vào vị trí xác định trong bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục được chỉ định trong bộ sưu tập. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Di chuyển slide bố cục từ bộ sưu tập tới vị trí xác định. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Thêm một bản sao của một slide bố cục được chỉ định vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide để nhân bản. |

--------------------

1) Layout mới sẽ được liên kết với master slide cha cho bộ sưu tập slide bố cục này. Do đó đây là tương tự của sao chép/dán với tùy chọn "Use Destination Theme" trong PowerPoint. 2) Tương tự của phương thức này là phương thức [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) được truy cập thông qua thuộc tính [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Kết quả trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide được thêm.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Chèn một bản sao của một slide bố cục được chỉ định vào vị trí xác định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của slide mới. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide để nhân bản. |

--------------------

Layout mới sẽ được liên kết với master slide cha cho bộ sưu tập slide bố cục này. Do đó đây là tương tự của sao chép/dán với tùy chọn "Use Destination Theme" trong PowerPoint.

**Kết quả trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide được chèn.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Thêm một slide bố cục mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| layoutType | byte | Kiểu bố cục cho một bố cục mới. Các kiểu bố cục được hỗ trợ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Các kiểu bố cục khác hiện không được hỗ trợ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Tên cho một bố cục mới. Nếu tên đã được sử dụng, sẽ ném ra ArgumentException. Nếu tham số null được truyền, tên sẽ được tạo tự động dựa trên kiểu bố cục đã truyền (ví dụ "Title Slide" hoặc "1\_Title Slide", "2\_..", v.v.). |

--------------------

1) Bố cục đã thêm cho giá trị SlideLayoutType.Custom của layoutType không chứa bất kỳ placeholder nào và không có hình dạng. 2) Tương tự của phương thức này là phương thức [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) được truy cập qua thuộc tính [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Kết quả trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide được thêm.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Chèn một slide bố cục mới vào vị trí xác định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của slide mới. |
| layoutType | byte | Kiểu bố cục cho một bố cục mới. Các kiểu bố cục được hỗ trợ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Các kiểu bố cục khác hiện không được hỗ trợ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Tên cho một bố cục mới. Nếu tên đã được sử dụng, sẽ ném ra ArgumentException. Nếu tham số null được truyền, tên sẽ được tạo tự động dựa trên kiểu bố cục đã truyền (ví dụ "Title Slide" hoặc "1\_Title Slide", "2\_..", v.v.). |

--------------------

Bố cục đã chèn cho giá trị SlideLayoutType.Custom của layoutType không chứa bất kỳ placeholder nào và không có hình dạng.

**Kết quả trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide được chèn.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ mục được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần xóa. |

--------------------

1) Để tránh ném PptxEditException, hãy kiểm tra thuộc tính HasDependingSlides của layout trước. 2) Bạn cũng có thể sử dụng phương thức [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) để đơn giản hoá mã.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Di chuyển slide bố cục từ bộ sưu tập đến vị trí xác định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục mục tiêu. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide để di chuyển. |