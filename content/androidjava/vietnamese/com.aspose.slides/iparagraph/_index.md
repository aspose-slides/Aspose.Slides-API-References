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

| Phương thức | Mô tả |
| --- | --- |
| [getPortions()](#getPortions--) | Trả về bộ sưu tập các phần văn bản. |
| [getParagraphFormat()](#getParagraphFormat--) | Trả về đối tượng định dạng cho đoạn văn này. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Nối các run có cùng định dạng. |
| [getText()](#getText--) | Lấy hoặc đặt văn bản thuần của một đoạn văn. |
| [setText(String value)](#setText-java.lang.String-) | Lấy hoặc đặt văn bản thuần của một đoạn văn. |
| [getRect()](#getRect--) | Lấy tọa độ của hình chữ nhật bao quanh đoạn văn. |
| [getLinesCount()](#getLinesCount--) | Lấy số dòng trong một đoạn văn. |
| [getImage()](#getImage--) | Trả về hình ảnh của đoạn văn. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Trả về hình ảnh của đoạn văn với tỷ lệ đã chỉ định. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Chỉ định các thuộc tính phần sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Chỉ định các thuộc tính phần sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


Trả về bộ sưu tập các phần văn bản. Chỉ đọc [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Trả về:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


Trả về đối tượng định dạng cho đoạn văn này. Chỉ đọc [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

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


Lấy hoặc đặt văn bản thuần của một đoạn văn. Đọc/ghi String.

Giá trị: Văn bản.

**Trả về:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Lấy hoặc đặt văn bản thuần của một đoạn văn. Đọc/ghi String.

Giá trị: Văn bản.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```


Lấy tọa độ của hình chữ nhật bao quanh đoạn văn. Hình chữ nhật bao gồm tất cả các dòng văn bản trong đoạn, bao gồm cả các dòng trống.

**Trả về:**
android.graphics.RectF - Hình chữ nhật bao quanh đoạn văn android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```


Lấy số dòng trong một đoạn văn.

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
int - Số dòng trong một đoạn văn
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Trả về hình ảnh của đoạn văn.

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Một hình ảnh chứa đoạn văn đã được vẽ, hoặc null nếu không tìm thấy đoạn văn trong bộ sưu tập cha, không có giới hạn vẽ hợp lệ, hoặc xảy ra lỗi khi vẽ hình ảnh.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```


Trả về hình ảnh của đoạn văn với tỷ lệ đã chỉ định.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| scaleX | float | Yếu tố tỷ lệ ngang được áp dụng cho hình ảnh đoạn văn. |
| scaleY | float | Yếu tố tỷ lệ dọc được áp dụng cho hình ảnh đoạn văn. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Một hình ảnh chứa đoạn văn đã được vẽ, hoặc null nếu không tìm thấy đoạn văn trong bộ sưu tập cha, không có giới hạn vẽ hợp lệ, hoặc xảy ra lỗi khi vẽ hình ảnh.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Chỉ định các thuộc tính phần sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng.

**Trả về:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Chỉ định các thuộc tính phần sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  