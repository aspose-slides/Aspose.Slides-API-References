---
title: ModernComment
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một bình luận trên slide.
type: docs
url: /vi/com.aspose.slides/moderncomment/
---
**Kế thừa:**  
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Tất cả các giao diện được triển khai:**  
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject  
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

Biểu diễn một comment trên slide.

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
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShape()](#getShape--) | Trả về một shape được liên kết với comment. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Lấy hoặc đặt vị trí bắt đầu của vùng chọn văn bản trong khung văn bản nếu comment được liên kết với AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Lấy hoặc đặt vị trí bắt đầu của vùng chọn văn bản trong khung văn bản nếu comment được liên kết với AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Lấy hoặc đặt độ dài vùng chọn văn bản trong khung văn bản nếu comment được liên kết với AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Lấy hoặc đặt độ dài vùng chọn văn bản trong khung văn bản nếu comment được liên kết với AutoShape. |
| [getStatus()](#getStatus--) | Lấy hoặc đặt trạng thái của comment. |
| [setStatus(byte value)](#setStatus-byte-) | Lấy hoặc đặt trạng thái của comment. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```

Trả về một shape được liên kết với comment. Chỉ đọc [IShape](../../com.aspose.slides/ishape).

**Trả về:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

Lấy hoặc đặt vị trí bắt đầu của vùng chọn văn bản trong khung văn bản nếu comment được liên kết với AutoShape. Đọc/ghi int.

**Trả về:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

Lấy hoặc đặt vị trí bắt đầu của vùng chọn văn bản trong khung văn bản nếu comment được liên kết với AutoShape. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

Lấy hoặc đặt độ dài vùng chọn văn bản trong khung văn bản nếu comment được liên kết với AutoShape. Đọc/ghi int.

**Trả về:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

Lấy hoặc đặt độ dài vùng chọn văn bản trong khung văn bản nếu comment được liên kết với AutoShape. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public final byte getStatus()
```

Lấy hoặc đặt trạng thái của comment. Đọc/ghi [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Trả về:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

Lấy hoặc đặt trạng thái của comment. Đọc/ghi [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject