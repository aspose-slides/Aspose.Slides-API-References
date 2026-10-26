---
title: Paragraph
second_title: Tham chiếu API Aspose.Slides cho Java
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

## Các hàm khởi tạo

| Hành tạo | Mô tả |
| --- | --- |
| [Paragraph()](#Paragraph--) | Khởi tạo một thể hiện mới của lớp Paragraph với các thuộc tính mặc định. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Hàm khởi tạo sao chép khởi tạo một thể hiện mới của lớp Paragraph. |

## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPortions()](#getPortions--) | Trả về tập hợp các phần văn bản. |
| [getParagraphFormat()](#getParagraphFormat--) | Trả về đối tượng định dạng cho đoạn văn này. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Nối các đoạn chạy có cùng định dạng. |
| [getText()](#getText--) | Lấy hoặc đặt văn bản thuần của một đoạn văn. |
| [setText(String value)](#setText-java.lang.String-) | Lấy hoặc đặt văn bản thuần của một đoạn văn. |
| [getRect()](#getRect--) | Lấy tọa độ của hình chữ nhật bao quanh đoạn văn. |
| [getLinesCount()](#getLinesCount--) | Lấy số dòng trong một đoạn văn. |
| [getImage()](#getImage--) | Trả về một hình ảnh của đoạn văn. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Trả về một hình ảnh của đoạn văn với tỷ lệ đã chỉ định. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Chỉ định các thuộc tính phần sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Chỉ định các thuộc tính phần sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Trả về slide cha của một đoạn văn. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của một đoạn văn. |

### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Khởi tạo một thể hiện mới của lớp Paragraph với các thuộc tính mặc định.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Hàm khởi tạo sao chép khởi tạo một thể hiện mới của lớp Paragraph.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Trả về tập hợp các phần văn bản. Chỉ đọc [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Trả về:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Trả về đối tượng định dạng cho đoạn văn này. Chỉ đọc [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Đối tượng định dạng chứa các tham số định dạng được định nghĩa chỉ cho đoạn văn hiện tại, dữ liệu kế thừa không được áp dụng.

Để lấy các giá trị hiệu quả bao gồm các giá trị kế thừa, hãy sử dụng phương thức [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Trả về:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Nối các đoạn chạy có cùng định dạng.

### getText() {#getText--}
```
public final String getText()
```

Lấy hoặc đặt văn bản thuần của một đoạn văn. Đọc/ghi String.

Giá trị: Văn bản.

**Trả về:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Lấy hoặc đặt văn bản thuần của một đoạn văn. Đọc/ghi String.

Giá trị: Văn bản.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

Lấy tọa độ của hình chữ nhật bao quanh đoạn văn. Hình chữ nhật bao gồm tất cả các dòng văn bản trong đoạn, kể cả các dòng trống.

**Trả về:**
java.awt.geom.Rectangle2D.Float

### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
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
public final IImage getImage()
```

Trả về một hình ảnh của đoạn văn.

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
[IImage](../../com.aspose.slides/iimage) - Một hình ảnh chứa đoạn văn đã được render, hoặc null nếu không thể tìm thấy đoạn văn trong tập hợp cha, không có giới hạn render hợp lệ, hoặc xảy ra lỗi khi render hình ảnh.

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Trả về một hình ảnh của đoạn văn với tỷ lệ đã chỉ định.

--------------------

> ```
> Ví dụ sau cho thấy cách render mỗi đoạn văn trong hộp văn bản trên một slide thành hình ảnh với tỷ lệ tùy chỉnh:
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
| scaleX | float | Hệ số tỷ lệ ngang áp dụng cho hình ảnh đoạn văn. |
| scaleY | float | Hệ số tỷ lệ dọc áp dụng cho hình ảnh đoạn văn. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Một hình ảnh chứa đoạn văn đã được render, hoặc null nếu không thể tìm thấy đoạn văn trong tập hợp cha, không có giới hạn render hợp lệ, hoặc xảy ra lỗi khi render hình ảnh.

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Chỉ định các thuộc tính phần sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng.

**Trả về:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Chỉ định các thuộc tính phần sẽ được sử dụng nếu một phần khác được chèn sau phần cuối cùng.

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

Trả về slide cha của một đoạn văn. Chỉ đọc [BaseSlide](../../com.aspose.slides/baseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình bày cha của một đoạn văn. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)