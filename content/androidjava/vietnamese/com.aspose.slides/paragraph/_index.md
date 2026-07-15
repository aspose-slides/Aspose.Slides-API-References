---
title: Paragraph
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một đoạn văn bản.
type: docs
url: /vi/com.aspose.slides/paragraph/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Biểu diễn một đoạn văn bản.
## Khởi tạo

| Constructor | Mô tả |
| --- | --- |
| [Paragraph()](#Paragraph--) | Khởi tạo một thể hiện mới của lớp Paragraph với các thuộc tính mặc định. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Hàm tạo sao chép khởi tạo một thể hiện mới của một lớp Paragraph. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPortions()](#getPortions--) | Trả về bộ sưu tập các đoạn văn bản. |
| [getParagraphFormat()](#getParagraphFormat--) | Trả về đối tượng định dạng cho đoạn văn này. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Nối các đoạn có cùng định dạng. |
| [getText()](#getText--) | Lấy hoặc đặt văn bản thuần của một đoạn. |
| [setText(String value)](#setText-java.lang.String-) | Lấy hoặc đặt văn bản thuần của một đoạn. |
| [getRect()](#getRect--) | Lấy tọa độ của hình chữ nhật bao quanh đoạn. |
| [getLinesCount()](#getLinesCount--) | Lấy số dòng trong một đoạn. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Xác định các thuộc tính phần sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Xác định các thuộc tính phần sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Trả về slide cha của một đoạn. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của một đoạn. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Khởi tạo một thể hiện mới của lớp Paragraph với các thuộc tính mặc định.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Hàm tạo sao chép khởi tạo một thể hiện mới của lớp Paragraph.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Trả về bộ sưu tập các đoạn văn bản. Chỉ đọc [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Trả về:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Trả về đối tượng định dạng cho đoạn văn này. Chỉ đọc [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Đối tượng định dạng chứa các tham số định dạng được định nghĩa chỉ cho đoạn hiện tại, dữ liệu kế thừa không được áp dụng.

Để lấy các giá trị hiệu lực bao gồm cả những giá trị kế thừa, hãy sử dụng phương thức [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Trả về:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Nối các đoạn có cùng định dạng.

### getText() {#getText--}
```
public final String getText()
```

Lấy hoặc đặt văn bản thuần của một đoạn. Đọc/ghi String.

Giá trị: Văn bản.

**Trả về:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Lấy hoặc đặt văn bản thuần của một đoạn. Đọc/ghi String.

Giá trị: Văn bản.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

Lấy tọa độ của hình chữ nhật bao quanh đoạn. Hình chữ nhật bao gồm tất cả các dòng văn bản trong đoạn, kể cả các dòng trống.

**Trả về:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

Lấy số dòng trong một đoạn.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
int - Số dòng trong một đoạn
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Xác định các thuộc tính phần sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng.

**Trả về:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Xác định các thuộc tính phần sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của một đoạn. Chỉ đọc [BaseSlide](../../com.aspose.slides/baseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình bày cha của một đoạn. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)