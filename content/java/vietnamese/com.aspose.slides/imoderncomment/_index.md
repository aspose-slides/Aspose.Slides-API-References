---
title: IModernComment
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một chú thích trên slide.
type: docs
url: /vi/com.aspose.slides/imoderncomment/
---
**Tất cả các giao diện đã thực thi:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Biểu diễn một chú thích trên slide.

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
| [getShape()](#getShape--) | Trả về một shape liên quan tới chú thích. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Trả về hoặc đặt vị trí bắt đầu của vùng chọn văn bản trong khung văn bản nếu chú thích được liên kết với AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Trả về hoặc đặt vị trí bắt đầu của vùng chọn văn bản trong khung văn bản nếu chú thích được liên kết với AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Trả về hoặc đặt độ dài của vùng chọn văn bản trong khung văn bản nếu chú thích được liên kết với AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Trả về hoặc đặt độ dài của vùng chọn văn bản trong khung văn bản nếu chú thích được liên kết với AutoShape. |
| [getStatus()](#getStatus--) | Trả về hoặc đặt trạng thái của chú thích. |
| [setStatus(byte value)](#setStatus-byte-) | Trả về hoặc đặt trạng thái của chú thích. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


Trả về một shape liên quan tới chú thích. Chỉ đọc [IShape](../../com.aspose.slides/ishape).

**Trả về:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


Trả về hoặc đặt vị trí bắt đầu của vùng chọn văn bản trong khung văn bản nếu chú thích được liên kết với AutoShape. Đọc/ghi int.

**Trả về:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


Trả về hoặc đặt vị trí bắt đầu của vùng chọn văn bản trong khung văn bản nếu chú thích được liên kết với AutoShape. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


Trả về hoặc đặt độ dài của vùng chọn văn bản trong khung văn bản nếu chú thích được liên kết với AutoShape. Đọc/ghi int.

**Trả về:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


Trả về hoặc đặt độ dài của vùng chọn văn bản trong khung văn bản nếu chú thích được liên kết với AutoShape. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


Trả về hoặc đặt trạng thái của chú thích. Đọc/ghi [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Trả về:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


Trả về hoặc đặt trạng thái của chú thích. Đọc/ghi [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |