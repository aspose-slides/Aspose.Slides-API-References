---
title: CommentCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một tập hợp các bình luận của một tác giả.
type: docs
url: /vi/com.aspose.slides/commentcollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Biểu diễn một tập hợp các bình luận của một tác giả.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số lượng phần tử thực tế chứa trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Thêm bình luận mới vào cuối bộ sưu tập. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Thêm bình luận hiện đại mới vào cuối bộ sưu tập. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Chèn bình luận mới vào bộ sưu tập tại chỉ mục đã chỉ định. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Chèn bình luận hiện đại mới vào bộ sưu tập tại chỉ mục đã chỉ định. |
| [toArray()](#toArray--) | Tạo và trả về một mảng chứa tất cả các bình luận. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tạo và trả về một mảng chứa các bình luận từ phạm vi đã chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã chỉ định trong bộ sưu tập. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Xóa lần xuất hiện đầu tiên của bình luận đã chỉ định trong bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả bình luận khỏi bộ sưu tập. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Tìm một bình luận trong bộ sưu tập theo chỉ mục. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết liệu việc truy cập bộ sưu tập có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một gốc đồng bộ. |
### size() {#size--}
```
public final int size()
```

Lấy số lượng phần tử thực tế chứa trong bộ sưu tập. Chỉ đọc  int .

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định. Chỉ đọc [Comment](../../com.aspose.slides/comment).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Thêm bình luận mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản thuần của bình luận mới. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide trong bản trình chiếu nơi sẽ thêm bình luận mới. |
| position | java.awt.geom.Point2D.Float | Vị trí trên slide nơi sẽ thêm bình luận mới. |
| creationTime | java.util.Date | Thời gian tạo bình luận. |

**Trả về:**
[IComment](../../com.aspose.slides/icomment) - Bình luận đã thêm.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
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
| shape | [IShape](../../com.aspose.slides/ishape) | Hình trên slide mà bình luận hiện đại mới được gắn kết. |
| position | java.awt.geom.Point2D.Float | Vị trí trên slide nơi sẽ thêm bình luận hiện đại mới. |
| creationTime | java.util.Date | Thời gian tạo bình luận hiện đại. |

**Trả về:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Bình luận hiện đại đã thêm.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Chèn bình luận mới vào bộ sưu tập tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phần tử trong bộ sưu tập mà bình luận sẽ được chèn. |
| text | java.lang.String | Văn bản thuần của bình luận mới. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide trong bản trình chiếu nơi sẽ thêm bình luận mới. |
| position | java.awt.geom.Point2D.Float | Vị trí trên slide nơi sẽ thêm bình luận mới. |
| creationTime | java.util.Date | Thời gian tạo bình luận. |

**Trả về:**
[IComment](../../com.aspose.slides/icomment) - Bình luận đã chèn.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Chèn bình luận hiện đại mới vào bộ sưu tập tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phần tử trong bộ sưu tập mà bình luận hiện đại sẽ được chèn. |
| text | java.lang.String | Văn bản thuần của bình luận hiện đại mới. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide trong bản trình chiếu nơi sẽ thêm bình luận hiện đại mới. |
| shape | [IShape](../../com.aspose.slides/ishape) | Hình trên slide mà bình luận hiện đại mới được gắn kết. |
| position | java.awt.geom.Point2D.Float | Vị trí trên slide nơi sẽ thêm bình luận hiện đại mới. |
| creationTime | java.util.Date | Thời gian tạo bình luận hiện đại. |

**Trả về:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Bình luận hiện đại đã chèn.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

Tạo và trả về một mảng chứa tất cả các bình luận.

**Trả về:**
com.aspose.slides.IComment[] - Mảng của [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Tạo và trả về một mảng chứa các bình luận từ phạm vi đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| startIndex | int | Chỉ mục của bình luận đầu tiên cần trả về. |
| count | int | Số lượng bình luận cần trả về. |

**Trả về:**
com.aspose.slides.IComment[] - Mảng của [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần xóa. |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Xóa lần xuất hiện đầu tiên của bình luận đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Bình luận cần xóa khỏi bộ sưu tập. |
### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả bình luận khỏi bộ sưu tập.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Một IGenericEnumerator có thể được dùng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Tìm một bình luận trong bộ sưu tập theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| idx | int | Chỉ mục duy nhất của bình luận cần tìm  int . |

**Trả về:**
[IComment](../../com.aspose.slides/icomment) - Bình luận được tìm thấy hoặc null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ bộ sưu tập vào mảng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết liệu việc truy cập bộ sưu tập có được đồng bộ (thread-safe) hay không. Chỉ đọc  boolean .

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một gốc đồng bộ. Chỉ đọc  Object .

**Trả về:**
java.lang.Object