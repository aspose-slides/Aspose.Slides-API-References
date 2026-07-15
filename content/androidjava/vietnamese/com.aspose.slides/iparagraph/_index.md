---
title: IParagraph
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một đoạn văn bản.
type: docs
url: /vi/com.aspose.slides/iparagraph/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Đại diện cho một đoạn văn bản.
## Phương thức

| Method | Description |
| --- | --- |
| [getPortions()](#getPortions--) | Trả về bộ sưu tập các đoạn văn bản. |
| [getParagraphFormat()](#getParagraphFormat--) | Trả về đối tượng định dạng cho đoạn này. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Nối các run có cùng định dạng. |
| [getText()](#getText--) | Lấy hoặc đặt văn bản thuần của một đoạn. |
| [setText(String value)](#setText-java.lang.String-) | Lấy hoặc đặt văn bản thuần của một đoạn. |
| [getRect()](#getRect--) | Lấy tọa độ của hình chữ nhật bao quanh đoạn. |
| [getLinesCount()](#getLinesCount--) | Lấy số dòng trong một đoạn. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Xác định các thuộc tính phần mà sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Xác định các thuộc tính phần mà sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


Trả về bộ sưu tập các đoạn văn bản. Chỉ đọc [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Trả về:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


Trả về đối tượng định dạng cho đoạn này. Chỉ đọc [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Trả về:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Nối các run có cùng định dạng.

### getText() {#getText--}
```
public abstract String getText()
```


Lấy hoặc đặt văn bản thuần của một đoạn. Đọc/ghi String.

Value: Văn bản.

**Trả về:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Lấy hoặc đặt văn bản thuần của một đoạn. Đọc/ghi String.

Value: Văn bản.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```


Lấy tọa độ của hình chữ nhật bao quanh đoạn. Hình chữ nhật bao gồm tất cả các dòng văn bản trong đoạn, kể cả các dòng trống.

**Trả về:**
android.graphics.RectF - Hình chữ nhật bao quanh đoạn android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Xác định các thuộc tính phần mà sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng.

**Trả về:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Xác định các thuộc tính phần mà sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |