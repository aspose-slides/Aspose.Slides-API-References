---
title: Shape
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị một hình dạng trên một slide.
type: docs
url: /vi/com.aspose.slides/shape/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Represents a shape on a slide.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Xác định xem hình dạng có phải là TextHolder_PPT hay không. |
| [getPlaceholder()](#getPlaceholder--) | Trả về placeholder cho một hình dạng. |
| [removePlaceholder()](#removePlaceholder--) | Xác định rằng hình dạng này không phải là placeholder. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Thêm một placeholder mới nếu không có và đặt thuộc tính placeholder thành một placeholder được chỉ định. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Trả về một hình dạng placeholder cơ bản (hình dạng từ bố cục và/hoặc slide mẫu mà hình dạng hiện tại được kế thừa). |
| [getCustomData()](#getCustomData--) | Trả về dữ liệu tùy chỉnh của hình dạng. |
| [getRawFrame()](#getRawFrame--) | Trả về hoặc đặt các thuộc tính khung hình dạng thô. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Trả về hoặc đặt các thuộc tính khung hình dạng thô. |
| [getFrame()](#getFrame--) | Trả về hoặc đặt các thuộc tính khung hình dạng. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Trả về hoặc đặt các thuộc tính khung hình dạng. |
| [getLineFormat()](#getLineFormat--) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng. |
| [getThreeDFormat()](#getThreeDFormat--) | Trả về đối tượng ThreeDFormat có các thuộc tính hiệu ứng 3D cho một hình dạng. |
| [getEffectFormat()](#getEffectFormat--) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một hình dạng. |
| [getFillFormat()](#getFillFormat--) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng. |
| [getImage()](#getImage--) | Trả về ảnh thu nhỏ của hình dạng. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Trả về ảnh thu nhỏ của hình dạng. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Trả về hoặc đặt siêu liên kết được định nghĩa cho cú nhấp chuột. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Trả về hoặc đặt siêu liên kết được định nghĩa cho cú nhấp chuột. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Trả về hoặc đặt siêu liên kết được định nghĩa cho việc di chuột qua. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Trả về hoặc đặt siêu liên kết được định nghĩa cho việc di chuột qua. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Trả về trình quản lý siêu liên kết. |
| [getHidden()](#getHidden--) | Xác định xem hình dạng có bị ẩn hay không. |
| [setHidden(boolean value)](#setHidden-boolean-) | Xác định xem hình dạng có bị ẩn hay không. |
| [getZOrderPosition()](#getZOrderPosition--) | Trả về vị trí của hình dạng trong thứ tự z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Trả về số lượng điểm kết nối trên hình dạng. |
| [getRotation()](#getRotation--) | Trả về hoặc đặt số độ mà hình dạng được chỉ định quay quanh trục z. |
| [setRotation(float value)](#setRotation-float-) | Trả về hoặc đặt số độ mà hình dạng được chỉ định quay quanh trục z. |
| [getX()](#getX--) | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm. |
| [setX(float value)](#setX-float-) | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm. |
| [getY()](#getY--) | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm. |
| [setY(float value)](#setY-float-) | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm. |
| [getWidth()](#getWidth--) | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm. |
| [setWidth(float value)](#setWidth-float-) | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm. |
| [getHeight()](#getHeight--) | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm. |
| [setHeight(float value)](#setHeight-float-) | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị trong chế độ đen-trắng. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị trong chế độ đen-trắng. |
| [getUniqueId()](#getUniqueId--) | Trả về một định danh nội bộ, phạm vi của bản trình chiếu, dành cho các add-in hoặc mã khác. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Trả về một định danh duy nhất có phạm vi slide, không đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. |
| [getAlternativeText()](#getAlternativeText--) | Trả về hoặc đặt văn bản thay thế liên quan tới một hình dạng. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Trả về hoặc đặt văn bản thay thế liên quan tới một hình dạng. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan tới một hình dạng. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan tới một hình dạng. |
| [getName()](#getName--) | Trả về hoặc đặt tên của một hình dạng. |
| [setName(String value)](#setName-java.lang.String-) | Trả về hoặc đặt tên của một hình dạng. |
| [isDecorative()](#isDecorative--) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí' (boolean Đọc/ghi). |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí' (boolean Đọc/ghi). |
| [getShapeLock()](#getShapeLock--) | Trả về các khóa của hình dạng. |
| [isGrouped()](#isGrouped--) | Xác định xem hình dạng có được nhóm hay không. |
| [getParentGroup()](#getParentGroup--) | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Lấy giới hạn trực quan của hình dạng được tính từ nội dung đã render. |
| [getSlide()](#getSlide--) | Trả về slide cha của một hình dạng. |
| [getPresentation()](#getPresentation--) | Trả về bản trình chiếu cha của một slide. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Xác định xem hình dạng có phải là TextHolder_PPT hay không. Chỉ đọc boolean.

**Trả về:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Trả về placeholder cho một hình dạng. Trả về null nếu hình dạng không có placeholder. Chỉ đọc [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Tạo một đối tượng lớp Presentation
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Truy cập slide đầu tiên
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Duyệt qua các shape để tìm placeholder
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Thay đổi văn bản trong mỗi placeholder
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Lưu bản trình chiếu vào đĩa
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // Duyệt qua slide
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint hiển thị "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Thêm phụ đề
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Xác định rằng hình dạng này không phải là placeholder.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Thêm một placeholder mới nếu không có và đặt thuộc tính placeholder thành một placeholder được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder để sao chép nội dung từ. |

**Trả về:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Mới \#getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Trả về một hình dạng placeholder cơ bản (hình dạng từ bố cục và/hoặc slide mẫu mà hình dạng hiện tại được kế thừa).

--------------------

> ```
> // lấy tất cả các hiệu ứng hoạt hình (master/layout/slide) của hình placeholder shape
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Một giá trị null được trả về nếu hình dạng hiện tại không được kế thừa.

**Trả về:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Trả về dữ liệu tùy chỉnh của hình dạng. Chỉ đọc [ICustomData](../../com.aspose.slides/icustomdata).

**Trả về:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Trả về hoặc đặt các thuộc tính khung hình dạng thô. Đọc/ghi [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //or
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Such code can lead to unclear situations. So restrictions had been added for using undefined values for IShape.getFrame(). Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not Float.NaN or NullableBool.NotDefined). Example code above now throws ArgumentException exception.
>  //This applies to these use cases:
>  IShape shape = ...;
>  shape.setFrame(...); // cannot be undefined
>  IShapeCollection shapes = ...;
>  // x, y, width, height parameters cannot be Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.{code}
> ```

**Trả về:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Trả về hoặc đặt các thuộc tính khung hình dạng thô. Đọc/ghi [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //or
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Such code can lead to unclear situations. So restrictions had been added for using undefined values for IShape.getFrame(). Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not Float.NaN or NullableBool.NotDefined). Example code above now throws ArgumentException exception.
>  //This applies to these use cases:
>  IShape shape = ...;
>  shape.setFrame(...); // cannot be undefined
>  IShapeCollection shapes = ...;
>  // x, y, width, height parameters cannot be Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.{code}
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Trả về hoặc đặt các thuộc tính khung hình dạng. Đọc/ghi [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Giá trị của mỗi thuộc tính của thể hiện IShapeFrame được trả về không được là undefined (không phải NaN hoặc NotDefined). Giá trị của mỗi thuộc tính của thể hiện IShapeFrame được gán phải không phải là undefined (phải không phải NaN hoặc NotDefined). Bạn có thể đặt giá trị undefined cho các thuộc tính của thể hiện RawFrame.

**Trả về:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Trả về hoặc đặt các thuộc tính khung hình dạng. Đọc/ghi [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Giá trị của mỗi thuộc tính của thể hiện IShapeFrame được trả về không được là undefined (không phải NaN hoặc NotDefined). Giá trị của mỗi thuộc tính của thể hiện IShapeFrame được gán phải không phải là undefined (phải không phải NaN hoặc NotDefined). Bạn có thể đặt giá trị undefined cho các thuộc tính của thể hiện RawFrame.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Trả về đối tượng **LineFormat** chứa các thuộc tính định dạng đường cho shape. Lưu ý: có thể trả về null đối với một số loại shape không có thuộc tính đường. **Chỉ đọc** [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Trả về đối tượng **ThreeDFormat** chứa các thuộc tính hiệu ứng 3D cho shape. Lưu ý: có thể trả về null đối với một số loại shape không có thuộc tính 3D. **Chỉ đọc** [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Trả về:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Trả về đối tượng **EffectFormat** chứa các hiệu ứng pixel được áp dụng cho shape. Lưu ý: có thể trả về null đối với một số loại shape không có thuộc tính hiệu ứng. **Chỉ đọc** [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Trả về:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Trả về đối tượng **FillFormat** chứa các thuộc tính định dạng tô màu cho shape. Lưu ý: có thể trả về null đối với một số loại shape không có thuộc tính tô màu. **Chỉ đọc** [IFillFormat](../../com.aspose.slides/ifillformat).

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Màu phụ 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Màu phụ 4, Nhẹ hơn 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Màu phụ 4, Nhẹ hơn 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Màu phụ 4, Nhẹ hơn 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Màu phụ 4, Đậm hơn 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Màu phụ 4, Đậm hơn 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Trả về hình thu nhỏ shape. Kiểu giới hạn hình thu nhỏ **ShapeThumbnailBounds.Shape** được sử dụng làm mặc định.

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Hình thu nhỏ shape.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Trả về hình thu nhỏ shape.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| bounds | int | Kiểu giới hạn hình thu nhỏ shape. |
| scaleX | float | Tỷ lệ X |
| scaleY | float | Tỷ lệ Y |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Hình thu nhỏ shape hoặc null trong trường hợp **ShapeThumbnailBounds.Appearance** được sử dụng và một shape không có thành phần hiển thị.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Lưu nội dung của shape dưới dạng tệp SVG.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Lưu nội dung của shape dưới dạng tệp SVG.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Các tùy chọn tạo SVG |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Trả về hoặc đặt siêu liên kết được định nghĩa cho lần nhấp chuột. **Đọc/ghi** [IHyperlink](../../com.aspose.slides/ihyperlink).

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Trả về hoặc đặt siêu liên kết được định nghĩa cho lần nhấp chuột. **Đọc/ghi** [IHyperlink](../../com.aspose.slides/ihyperlink).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Trả về hoặc đặt siêu liên kết được định nghĩa cho lần di chuột qua. **Đọc/ghi** [IHyperlink](../../com.aspose.slides/ihyperlink).

**Trả về:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Trả về hoặc đặt siêu liên kết được định nghĩa cho lần di chuột qua. **Đọc/ghi** [IHyperlink](../../com.aspose.slides/ihyperlink).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Trả về trình quản lý siêu liên kết. **Chỉ đọc** [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Trả về:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Xác định xem shape có bị ẩn hay không. **Đọc/ghi** boolean.

**Trả về:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Xác định xem shape có bị ẩn hay không. **Đọc/ghi** boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Trả về vị trí của shape trong thứ tự z. **Shapes[0]** trả về shape ở phía sau cùng của thứ tự z, và **Shapes[Shapes.Count - 1]** trả về shape ở phía trước cùng. **Chỉ đọc** int.

**Trả về:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Trả về số lượng vị trí kết nối trên shape. **Chỉ đọc** int.

**Trả về:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Trả về hoặc đặt số độ mà shape được quay quanh trục z. Giá trị dương nghĩa là quay theo chiều kim đồng hồ; giá trị âm nghĩa là quay ngược chiều kim đồng hồ. **Đọc/ghi** float.

--------------------

Giá trị trả về luôn được xác định (không phải Float.NaN). Giá trị được gán phải được xác định (không phải Float.NaN). Bạn có thể đặt giá trị không xác định cho các thuộc tính của đối tượng **RawFrame**.

**Trả về:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
Returns hoặc đặt số độ mà hình dạng được chỉ định xoay quanh trục z. Giá trị dương biểu thị xoay theo chiều kim đồng hồ; giá trị âm biểu thị xoay ngược chiều kim đồng hồ. Đọc/ghi float.

--------------------

Giá trị trả về luôn được xác định (không phải Float.NaN). Giá trị được gán phải được xác định (không phải Float.NaN). Bạn có thể đặt giá trị không xác định cho các thuộc tính của thể hiện RawFrame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```


Lấy hoặc đặt toạ độ x của góc trên-trái của hình, đo bằng điểm. Đọc/ghi float.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị được gán cũng phải được xác định; chỉ gán Float.NaN cho các thuộc tính của thể hiện RawFrame.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Lấy hoặc đặt toạ độ x của góc trên-trái của hình, đo bằng điểm. Đọc/ghi float.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị được gán cũng phải được xác định; chỉ gán Float.NaN cho các thuộc tính của thể hiện RawFrame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


Lấy hoặc đặt toạ độ y của góc trên-trái của hình, đo bằng điểm. Đọc/ghi float.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị được gán cũng phải được xác định; chỉ gán Float.NaN cho các thuộc tính của thể hiện RawFrame.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Lấy hoặc đặt toạ độ y của góc trên-trái của hình, đo bằng điểm. Đọc/ghi float.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị được gán cũng phải được xác định; chỉ gán Float.NaN cho các thuộc tính của thể hiện RawFrame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Lấy hoặc đặt chiều rộng của hình, đo bằng điểm. Đọc/ghi float.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị được gán cũng phải được xác định; chỉ gán Float.NaN cho các thuộc tính của thể hiện RawFrame.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Lấy hoặc đặt chiều rộng của hình, đo bằng điểm. Đọc/ghi float.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị được gán cũng phải được xác định; chỉ gán Float.NaN cho các thuộc tính của thể hiện RawFrame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Lấy hoặc đặt chiều cao của hình, đo bằng điểm. Đọc/ghi float.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị được gán cũng phải được xác định; chỉ gán Float.NaN cho các thuộc tính của thể hiện RawFrame.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Lấy hoặc đặt chiều cao của hình, đo bằng điểm. Đọc/ghi float.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị được gán cũng phải được xác định; chỉ gán Float.NaN cho các thuộc tính của thể hiện RawFrame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```


Thuộc tính chỉ định cách một hình sẽ được hiển thị trong chế độ đen-trắng. Đọc/ghi [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Returns:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```


Thuộc tính chỉ định cách một hình sẽ được hiển thị trong chế độ đen-trắng. Đọc/ghi [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```


Trả về định danh nội bộ, phạm vi bản trình bày, được dùng cho các add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình gán lại, không nên coi nó là khóa duy nhất lâu dài. Chỉ đọc long. Xem thêm \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Returns:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```


Trả về định danh duy nhất trong phạm vi slide, không thay đổi trong suốt vòng đời của hình và cho phép PowerPoint hoặc mã interop tham chiếu hình một cách đáng tin cậy từ bất kỳ nơi nào trong tài liệu. Chỉ đọc long. Xem thêm \#getUniqueId.getUniqueId.

**Returns:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Trả về hoặc đặt văn bản thay thế liên quan đến một hình. Đọc/ghi String.

**Returns:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Trả về hoặc đặt văn bản thay thế liên quan đến một hình. Đọc/ghi String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```


Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan đến một hình. Đọc/ghi String.

**Returns:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```


Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan đến một hình. Đọc/ghi String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```


Trả về hoặc đặt tên của một hình. Không được null. Sử dụng chuỗi rỗng nếu cần. Đọc/ghi String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Trả về hoặc đặt tên của một hình. Không được null. Sử dụng chuỗi rỗng nếu cần. Đọc/ghi String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```


Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí' Reed/write boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```


Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí' Reed/write boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```


Trả về các khóa của hình. Chỉ đọc [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Returns:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```


Xác định liệu hình có được nhóm hay không. Chỉ đọc boolean.

--------------------

Thuộc tính \#getParentGroup.getParentGroup trả về đối tượng GroupShape cha nếu hình được nhóm.

**Returns:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```


Trả về đối tượng GroupShape cha nếu hình được nhóm. Nếu không, trả về null. Chỉ đọc [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Thuộc tính \#isGrouped.isGrouped xác định liệu hình có được nhóm hay không.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```


Lấy giới hạn trực quan của hình được tính từ nội dung đã vẽ.

**Returns:**
java.awt.geom.Rectangle2D.Float - Một java.awt.geom.Rectangle2D.Float đại diện cho giới hạn trực quan của hình trong tọa độ slide.

--------------------

Hình chữ nhật trả về đại diện cho giới hạn theo trục của mọi nội dung do hình tạo ra trong không gian tọa độ slide. Các giới hạn này có thể khác với giới hạn mô hình của hình \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) và có thể chứa tọa độ âm nếu nội dung đã vẽ vượt ra ngoài gốc slide. Giới hạn trực quan tính đến các khía cạnh liên quan đến việc vẽ như biến đổi (ví dụ, xoay), độ rộng nét và các mối nối, bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố cục khác ảnh hưởng đến cách hình xuất hiện cuối cùng. Các giới hạn trả về không bị cắt theo hình chữ nhật slide.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Trả về slide cha của một hình. Chỉ đọc [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Trả về bản trình bày cha của một slide. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)