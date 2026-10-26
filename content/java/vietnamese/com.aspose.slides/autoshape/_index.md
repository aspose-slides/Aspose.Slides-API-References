---
title: AutoShape
second_title: Tham chiếu API Java của Aspose.Slides
description: Biểu diễn một AutoShape.
type: docs
url: /vi/com.aspose.slides/autoshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Biểu diễn một AutoShape.
## Phương thức

| Method | Description |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Trả về các khóa của shape. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Trả về các khóa của autoshape. |
| [getTextFrame()](#getTextFrame--) | Trả về đối tượng TextFrame cho AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Xác định xem autoshape này có nên được tô đầy bằng nền của slide thay vì được chỉ định bởi kiểu hoặc định dạng tô màu hay không. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Xác định xem autoshape này có nên được tô đầy bằng nền của slide thay vì được chỉ định bởi kiểu hoặc định dạng tô màu hay không. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Thêm một TextFrame mới vào shape. |
| [isTextBox()](#isTextBox--) | Xác định xem shape có phải là một hộp văn bản hay không. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Trả về các khóa của shape. Chỉ đọc [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Kết quả trả về:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Trả về các khóa của autoshape. Chỉ đọc [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Kết quả trả về:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Trả về đối tượng TextFrame cho AutoShape. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Kết quả trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Xác định xem autoshape này có nên được tô đầy bằng nền của slide thay vì được chỉ định bởi kiểu hoặc định dạng tô màu hay không. Đọc/ghi boolean.

**Kết quả trả về:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Xác định xem autoshape này có nên được tô đầy bằng nền của slide thay vì được chỉ định bởi kiểu hoặc định dạng tô màu hay không. Đọc/ghi boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Thêm một TextFrame mới vào shape. Nếu shape đã có TextFrame thì chỉ thay đổi văn bản của nó.

--------------------

> ```
> The following sample code shows how to add watermark text in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape watermarkShape = slide.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
>      ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to create Text Box on Slide.
>  
>  // Khởi tạo Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Lấy slide đầu tiên trong bản trình chiếu
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Thêm một AutoShape với loại được đặt là Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Thêm TextFrame vào Rectangle
>      ashp.addTextFrame(" ");
>      // Truy cập khung văn bản
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Tạo đối tượng Paragraph cho khung văn bản
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Tạo đối tượng Portion cho đoạn văn
>      IPortion portion = para.getPortions().get_Item(0);
>      // Đặt văn bản
>      portion.setText("Aspose TextBox");
>      // Lưu bản trình chiếu vào đĩa
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Lấy slide đầu tiên trong bản trình chiếu
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Thêm một AutoShape với loại được đặt là Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Thêm TextFrame vào Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Lấy định dạng văn bản của TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Xác định số cột trong TextFrame
>      format.setColumnCount(3);
>      // Xác định khoảng cách giữa các cột
>      format.setColumnSpacing(10);
>      // Lưu bản trình chiếu
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Văn bản mặc định cho TextFrame mới. |

**Kết quả trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

Xác định xem shape có phải là một hộp văn bản hay không.

--------------------

Nếu shape không được chỉ định là một hộp văn bản không có nghĩa là nó không thể có văn bản gắn vào. Một hộp văn bản chỉ là một shape đặc biệt với các thuộc tính cụ thể.

**Kết quả trả về:**
boolean