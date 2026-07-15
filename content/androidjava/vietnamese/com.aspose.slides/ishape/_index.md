---
title: IShape
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Đại diện cho một hình dạng trên slide.
type: docs
url: /vi/com.aspose.slides/ishape/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Đại diện cho một hình dạng trên slide.
## Phương thức

| Method | Description |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Xác định xem hình dạng có phải là TextHolder hay không. |
| [getPlaceholder()](#getPlaceholder--) | Trả về placeholder cho một hình dạng. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Thêm một placeholder mới nếu không tồn tại và đặt các thuộc tính placeholder thành một placeholder được chỉ định. |
| [removePlaceholder()](#removePlaceholder--) | Xác định rằng hình dạng này không phải là placeholder. |
| [getCustomData()](#getCustomData--) | Trả về dữ liệu tùy chỉnh của hình dạng. |
| [getRawFrame()](#getRawFrame--) | Trả về hoặc thiết lập các thuộc tính khung hình dạng thô. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Trả về hoặc thiết lập các thuộc tính khung hình dạng thô. |
| [getFrame()](#getFrame--) | Trả về hoặc thiết lập các thuộc tính khung hình dạng. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Trả về hoặc thiết lập các thuộc tính khung hình dạng. |
| [getLineFormat()](#getLineFormat--) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng. |
| [getThreeDFormat()](#getThreeDFormat--) | Trả về đối tượng ThreeDFormat chứa các thuộc tính định dạng đường cho một hình dạng. |
| [getEffectFormat()](#getEffectFormat--) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một hình dạng. |
| [getFillFormat()](#getFillFormat--) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng. |
| [getImage()](#getImage--) | Trả về hình thu nhỏ của hình dạng. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Trả về hình thu nhỏ của hình dạng. |
| [getHidden()](#getHidden--) | Xác định xem hình dạng có bị ẩn hay không. |
| [setHidden(boolean value)](#setHidden-boolean-) | Xác định xem hình dạng có bị ẩn hay không. |
| [getZOrderPosition()](#getZOrderPosition--) | Trả về vị trí của một hình dạng trong thứ tự z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Trả về số lượng vị trí kết nối trên hình dạng. |
| [getRotation()](#getRotation--) | Trả về hoặc thiết lập số độ mà hình dạng được xoay quanh trục z. |
| [setRotation(float value)](#setRotation-float-) | Trả về hoặc thiết lập số độ mà hình dạng được xoay quanh trục z. |
| [getX()](#getX--) | Lấy hoặc đặt tọa độ x của góc trên bên trái của hình dạng, tính bằng điểm. |
| [setX(float value)](#setX-float-) | Lấy hoặc đặt tọa độ x của góc trên bên trái của hình dạng, tính bằng điểm. |
| [getY()](#getY--) | Lấy hoặc đặt tọa độ y của góc trên bên trái của hình dạng, tính bằng điểm. |
| [setY(float value)](#setY-float-) | Lấy hoặc đặt tọa độ y của góc trên bên trái của hình dạng, tính bằng điểm. |
| [getWidth()](#getWidth--) | Lấy hoặc đặt chiều rộng của hình dạng, tính bằng điểm. |
| [setWidth(float value)](#setWidth-float-) | Lấy hoặc đặt chiều rộng của hình dạng, tính bằng điểm. |
| [getHeight()](#getHeight--) | Lấy hoặc đặt chiều cao của hình dạng, tính bằng điểm. |
| [setHeight(float value)](#setHeight-float-) | Lấy hoặc đặt chiều cao của hình dạng, tính bằng điểm. |
| [getAlternativeText()](#getAlternativeText--) | Trả về hoặc thiết lập văn bản thay thế liên quan đến một hình dạng. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Trả về hoặc thiết lập văn bản thay thế liên quan đến một hình dạng. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên quan đến một hình dạng. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên quan đến một hình dạng. |
| [getName()](#getName--) | Trả về hoặc thiết lập tên của một hình dạng. |
| [setName(String value)](#setName-java.lang.String-) | Trả về hoặc thiết lập tên của một hình dạng. |
| [isDecorative()](#isDecorative--) | Lấy hoặc đặt tùy chọn 'Mark as decorative' Boolean đọc/ghi. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Lấy hoặc đặt tùy chọn 'Mark as decorative' Boolean đọc/ghi. |
| [getShapeLock()](#getShapeLock--) | Trả về các khóa của hình dạng. |
| [getUniqueId()](#getUniqueId--) | Trả về một định danh nội bộ, phạm vi bản trình chiếu, được dùng cho các add-in hoặc mã khác. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Trả về một định danh duy nhất có phạm vi slide, không thay đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. |
| [isGrouped()](#isGrouped--) | Xác định xem hình dạng có được nhóm không. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị trong chế độ đen trắng. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị trong chế độ đen trắng. |
| [getParentGroup()](#getParentGroup--) | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Trả về một shape placeholder cơ bản (shape từ bố cục và/hoặc slide master mà shape hiện tại được kế thừa). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Xác định xem hình dạng có phải là TextHolder hay không. Boolean chỉ đọc.

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Trả về placeholder cho một hình dạng. Chỉ đọc [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Trả về:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Thêm một placeholder mới nếu không tồn tại và đặt các thuộc tính placeholder thành một placeholder được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder để sao chép nội dung. |

**Trả về:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Xác định rằng hình dạng này không phải là placeholder.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Trả về dữ liệu tùy chỉnh của hình dạng. Chỉ đọc [ICustomData](../../com.aspose.slides/icustomdata).

**Trả về:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Trả về hoặc thiết lập các thuộc tính khung hình dạng thô. Đọc/ghi [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //hoặc
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Mã như vậy có thể dẫn đến các tình huống không rõ ràng. Do đó đã thêm các ràng buộc khi sử dụng các giá trị chưa định nghĩa cho IShape.getFrame(). Các giá trị x, y, width, height, flipH, flipV và rotationAngle phải được định nghĩa (không phải Float.NaN hoặc NullableBool.NotDefined). Mã mẫu trên hiện sẽ ném ngoại lệ ArgumentException.
>  //Áp dụng cho các trường hợp sử dụng sau:
>  IShape shape = ...;
>  shape.setFrame(...); // không được để là undefined
>  IShapeCollection shapes = ...;
>  // các tham số x, y, width, height không được là Float.NaN:
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape được liên kết với placeholder
> 
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // bây giờ shape kế thừa các giá trị x, y, height, flipH, flipV từ placeholder và ghi đè width=100 và rotationAngle=0.
```


**Trả về:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Trả về hoặc thiết lập các thuộc tính khung hình dạng thô. Đọc/ghi [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //hoặc
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Mã như vậy có thể dẫn đến các tình huống không rõ ràng. Do đó đã thêm các ràng buộc khi sử dụng các giá trị chưa xác định cho IShape.getFrame(). Các giá trị x, y, width, height, flipH, flipV và rotationAngle phải được xác định (không phải Float.NaN hoặc NullableBool.NotDefined). Mã mẫu trên hiện sẽ ném ngoại lệ ArgumentException.
>  //Áp dụng cho các trường hợp sử dụng sau:
>  IShape shape = ...;
>  shape.setFrame(...); // không được là chưa xác định
>  IShapeCollection shapes = ...;
>  // các tham số x, y, width, height không được là Float.NaN:
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // bây giờ shape kế thừa các giá trị x, y, height, flipH, flipV từ placeholder và ghi đè width=100 và rotationAngle=0.
```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Trả về hoặc thiết lập các thuộc tính khung hình dạng. Đọc/ghi [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Giá trị của mỗi thuộc tính trong thể hiện IShapeFrame được trả về không phải là undefined (không phải NaN hoặc NotDefined). Giá trị của mỗi thuộc tính trong thể hiện IShapeFrame được gán phải không phải undefined (phải không phải NaN hoặc NotDefined). Bạn có thể đặt các giá trị undefined cho các thuộc tính của thể hiện RawFrame.

**Trả về:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Trả về hoặc thiết lập các thuộc tính khung hình dạng. Đọc/ghi [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Giá trị của mỗi thuộc tính trong thể hiện IShapeFrame được trả về không phải là undefined (không phải NaN hoặc NotDefined). Giá trị của mỗi thuộc tính trong thể hiện IShapeFrame được gán phải không phải undefined (phải không phải NaN hoặc NotDefined). Bạn có thể đặt các giá trị undefined cho các thuộc tính của thể hiện RawFrame.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng. Chỉ đọc [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Trả về đối tượng ThreeDFormat chứa các thuộc tính định dạng đường cho một hình dạng. Chỉ đọc [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Trả về:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một hình dạng. Chỉ đọc [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Trả về:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Trả về hình thu nhỏ của hình dạng. Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho phạm vi hình thu nhỏ.

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Hình thu nhỏ của shape.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Trả về hình thu nhỏ của hình dạng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| bounds | int | Kiểu phạm vi hình thu nhỏ. |
| scaleX | float | Tỷ lệ X |
| scaleY | float | Tỷ lệ Y |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Hình thu nhỏ của shape hoặc null trong trường hợp ShapeThumbnailBounds.Appearance được sử dụng và hình dạng không có phần tử hiển thị.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Xác định xem hình dạng có bị ẩn hay không. Boolean đọc/ghi.

**Trả về:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Xác định xem hình dạng có bị ẩn hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Trả về vị trí của một hình dạng trong thứ tự z. Shapes[0] trả về shape ở phía sau cùng, và Shapes[Shapes.Count - 1] trả về shape ở phía trước cùng. Int chỉ đọc.

**Trả về:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Trả về số lượng vị trí kết nối trên hình dạng. Int chỉ đọc.

**Trả về:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Trả về hoặc thiết lập số độ mà hình dạng được xoay quanh trục z. Giá trị dương biểu thị xoay theo chiều kim đồng hồ; giá trị âm biểu thị xoay ngược chiều kim đồng hồ. Float đọc/ghi.

--------------------

Giá trị trả về luôn được xác định (không phải Float.NaN). Giá trị gán phải được xác định (không phải Float.NaN). Bạn có thể đặt giá trị undefined cho các thuộc tính của thể hiện RawFrame.

**Trả về:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Trả về hoặc thiết lập số độ mà hình dạng được xoay quanh trục z. Giá trị dương biểu thị xoay theo chiều kim đồng hồ; giá trị âm biểu thị xoay ngược chiều kim đồng hồ. Float đọc/ghi.

--------------------

Giá trị trả về luôn được xác định (không phải Float.NaN). Giá trị gán phải được xác định (không phải Float.NaN). Bạn có thể đặt giá trị undefined cho các thuộc tính của thể hiện RawFrame.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Lấy hoặc đặt tọa độ x của góc trên bên trái của hình dạng, tính bằng điểm. Float đọc/ghi.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị gán cũng phải được xác định; chỉ đặt Float.NaN cho các thuộc tính của một thể hiện RawFrame.

**Trả về:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Lấy hoặc đặt tọa độ x của góc trên bên trái của hình dạng, tính bằng điểm. Float đọc/ghi.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị gán cũng phải được xác định; chỉ đặt Float.NaN cho các thuộc tính của một thể hiện RawFrame.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Lấy hoặc đặt tọa độ y của góc trên bên trái của hình dạng, tính bằng điểm. Float đọc/ghi.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị gán cũng phải được xác định; chỉ đặt Float.NaN cho các thuộc tính của một thể hiện RawFrame.

**Trả về:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Lấy hoặc đặt tọa độ y của góc trên bên trái của hình dạng, tính bằng điểm. Float đọc/ghi.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị gán cũng phải được xác định; chỉ đặt Float.NaN cho các thuộc tính của một thể hiện RawFrame.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Lấy hoặc đặt chiều rộng của hình dạng, tính bằng điểm. Float đọc/ghi.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị gán cũng phải được xác định; chỉ đặt Float.NaN cho các thuộc tính của một thể hiện RawFrame.

**Trả về:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Lấy hoặc đặt chiều rộng của hình dạng, tính bằng điểm. Float đọc/ghi.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị gán cũng phải được xác định; chỉ đặt Float.NaN cho các thuộc tính của một thể hiện RawFrame.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Lấy hoặc đặt chiều cao của hình dạng, tính bằng điểm. Float đọc/ghi.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị gán cũng phải được xác định; chỉ đặt Float.NaN cho các thuộc tính của một thể hiện RawFrame.

**Trả về:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Lấy hoặc đặt chiều cao của hình dạng, tính bằng điểm. Float đọc/ghi.

--------------------

Giá trị trả về luôn được xác định và không bao giờ là Float.NaN. Giá trị gán cũng phải được xác định; chỉ đặt Float.NaN cho các thuộc tính của một thể hiện RawFrame.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Trả về hoặc thiết lập văn bản thay thế liên quan đến một hình dạng. String đọc/ghi.

**Trả về:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Trả về hoặc thiết lập văn bản thay thế liên quan đến một hình dạng. String đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên quan đến một hình dạng. String đọc/ghi.

**Trả về:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên quan đến một hình dạng. String đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Trả về hoặc thiết lập tên của một hình dạng. String đọc/ghi.

**Trả về:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Trả về hoặc thiết lập tên của một hình dạng. String đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Lấy hoặc đặt tùy chọn 'Mark as decorative' Boolean đọc/ghi.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

Lấy hoặc đặt tùy chọn 'Mark as decorative' Boolean đọc/ghi.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

Trả về các khóa của hình dạng. Chỉ đọc [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Trả về:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Trả về một định danh nội bộ, phạm vi bản trình chiếu, được thiết kế cho các add-in hoặc mã khác. Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, nó không nên được coi là khóa duy nhất bền vững. Long chỉ đọc. Xem thêm \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Trả về:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Trả về một định danh duy nhất có phạm vi slide, không thay đổi trong suốt vòng đời của hình dạng và cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu. Long chỉ đọc. Xem thêm \#getUniqueId.getUniqueId.

**Trả về:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Xác định xem hình dạng có được nhóm không. Boolean chỉ đọc.

--------------------

Thuộc tính \#getParentGroup.getParentGroup trả về đối tượng GroupShape cha nếu hình dạng được nhóm.

**Trả về:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Thuộc tính chỉ định cách một hình dạng sẽ hiển thị trong chế độ đen trắng. Đọc/ghi [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Trả về:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Thuộc tính chỉ định cách một hình dạng sẽ hiển thị trong chế độ đen trắng. Đọc/ghi [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không, trả về null. Chỉ đọc [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Thuộc tính \#isGrouped.isGrouped xác định xem hình dạng có được nhóm không.

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Lưu nội dung của Shape dưới dạng tệp SVG.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Lưu nội dung của Shape dưới dạng tệp SVG.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng đích |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Tùy chọn tạo SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Trả về một shape placeholder cơ bản (shape từ bố cục và/hoặc slide master mà shape hiện tại được kế thừa).

--------------------

> ```
> // lấy tất cả các hiệu ứng hoạt hình (master/layout/slide) của shape placeholder
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

Trả về null nếu hình dạng hiện tại không được kế thừa.

**Trả về:**
[IShape](../../com.aspose.slides/ishape)