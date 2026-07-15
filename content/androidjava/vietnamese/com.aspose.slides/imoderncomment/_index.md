---
title: IModernComment
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu thị một comment trên slide.
type: docs
url: /vi/com.aspose.slides/imoderncomment/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Biểu thị một comment trên slide.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShape()](#getShape--) | Trả về một shape liên kết với comment. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Trả về hoặc đặt vị trí bắt đầu của việc chọn văn bản trong text frame nếu comment được liên kết với AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Trả về hoặc đặt vị trí bắt đầu của việc chọn văn bản trong text frame nếu comment được liên kết với AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Trả về hoặc đặt độ dài của việc chọn văn bản trong text frame nếu comment được liên kết với AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Trả về hoặc đặt độ dài của việc chọn văn bản trong text frame nếu comment được liên kết với AutoShape. |
| [getStatus()](#getStatus--) | Trả về hoặc đặt trạng thái của comment. |
| [setStatus(byte value)](#setStatus-byte-) | Trả về hoặc đặt trạng thái của comment. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


Trả về một shape liên kết với comment. Chỉ đọc [IShape](../../com.aspose.slides/ishape).

**Trả về:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


Trả về hoặc đặt vị trí bắt đầu của việc chọn văn bản trong text frame nếu comment được liên kết với AutoShape. Đọc/ghi int.

**Trả về:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


Trả về hoặc đặt vị trí bắt đầu của việc chọn văn bản trong text frame nếu comment được liên kết với AutoShape. Đọc/ghi int.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


Trả về hoặc đặt độ dài của việc chọn văn bản trong text frame nếu comment được liên kết với AutoShape. Đọc/ghi int.

**Trả về:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


Trả về hoặc đặt độ dài của việc chọn văn bản trong text frame nếu comment được liên kết với AutoShape. Đọc/ghi int.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


Trả về hoặc đặt trạng thái của comment. Đọc/ghi [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Trả về:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


Trả về hoặc đặt trạng thái của comment. Đọc/ghi [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |