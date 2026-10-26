---
title: ICommentCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị một bộ sưu tập các bình luận của một tác giả.
type: docs
url: /vi/com.aspose.slides/icommentcollection/
---
**Tất cả giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Biểu thị một bộ sưu tập các bình luận của một tác giả.

## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Thêm bình luận mới vào cuối bộ sưu tập. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Thêm bình luận hiện đại mới vào cuối bộ sưu tập. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Chèn bình luận mới vào bộ sưu tập tại chỉ mục đã chỉ định. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Chèn bình luận hiện đại mới vào bộ sưu tập tại chỉ mục đã chỉ định. |
| [toArray()](#toArray--) | Tạo và trả về một mảng chứa tất cả các bình luận. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tạo và trả về một mảng chứa các bình luận từ phạm vi đã chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã chỉ định trong bộ sưu tập. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Xóa lần xuất hiện đầu tiên của bình luận đã chỉ định trong bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các bình luận khỏi bộ sưu tập. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định. Chỉ đọc [IComment](../../com.aspose.slides/icomment).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Thêm bình luận mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản thuần của bình luận mới. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide trong bản trình chiếu nơi sẽ thêm bình luận mới. |
| position | java.awt.geom.Point2D.Float | Vị trí trên slide nơi sẽ thêm bình luận mới. |
| creationTime | java.util.Date | Thời gian tạo bình luận. |

**Giá trị trả về:**
[IComment](../../com.aspose.slides/icomment) - Bình luận đã thêm.

### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Thêm bình luận hiện đại mới vào cuối bộ sưu tập.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản thuần của bình luận hiện đại mới. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide trong bản trình chiếu nơi sẽ thêm bình luận hiện đại mới. |
| shape | [IShape](../../com.aspose.slides/ishape) | Hình dạng trên slide mà bình luận hiện đại mới được liên kết. |
| position | java.awt.geom.Point2D.Float | Vị trí trên slide nơi sẽ thêm bình luận hiện đại mới. |
| creationTime | java.util.Date | Thời gian tạo bình luận hiện đại. |

**Giá trị trả về:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Bình luận hiện đại đã thêm.

### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Chèn bình luận mới vào bộ sưu tập tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phần tử trong bộ sưu tập mà bình luận sẽ được chèn vào. |
| text | java.lang.String | Văn bản thuần của bình luận mới. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide trong bản trình chiếu nơi sẽ thêm bình luận mới. |
| position | java.awt.geom.Point2D.Float | Vị trí trên slide nơi sẽ thêm bình luận mới. |
| creationTime | java.util.Date | Thời gian tạo bình luận. |

**Giá trị trả về:**
[IComment](../../com.aspose.slides/icomment) - Bình luận đã chèn.

### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Chèn bình luận hiện đại mới vào bộ sưu tập tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phần tử trong bộ sưu tập mà bình luận hiện đại sẽ được chèn vào. |
| text | java.lang.String | Văn bản thuần của bình luận hiện đại mới. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide trong bản trình chiếu nơi sẽ thêm bình luận hiện đại mới. |
| shape | [IShape](../../com.aspose.slides/ishape) | Hình dạng trên slide mà bình luận hiện đại mới được liên kết. |
| position | java.awt.geom.Point2D.Float | Vị trí trên slide nơi sẽ thêm bình luận hiện đại mới. |
| creationTime | java.util.Date | Thời gian tạo bình luận hiện đại. |

**Giá trị trả về:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Bình luận hiện đại đã chèn.

### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

Tạo và trả về một mảng chứa tất cả các bình luận.

**Giá trị trả về:**
com.aspose.slides.IComment[] - Mảng của [IComment](../../com.aspose.slides/icomment).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

Tạo và trả về một mảng chứa các bình luận từ phạm vi đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| startIndex | int | Chỉ mục của bình luận đầu tiên để trả về. |
| count | int | Số lượng bình luận để trả về. |

**Giá trị trả về:**
com.aspose.slides.IComment[] - Mảng của [IComment](../../com.aspose.slides/icomment).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần xóa. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Xóa lần xuất hiện đầu tiên của bình luận đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Bình luận cần xóa khỏi bộ sưu tập. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các bình luận khỏi bộ sưu tập.