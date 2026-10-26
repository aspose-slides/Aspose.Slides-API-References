---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Contains the TextFrames formatting properties.
type: docs
url: /vi/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Chứa các thuộc tính định dạng của TextFrame.

## Phương thức

| Method | Description |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Trả về kiểu văn bản. |
| [getMarginLeft()](#getMarginLeft--) | Trả về hoặc đặt lề trái (điểm) trong một TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Trả về hoặc đặt lề trái (điểm) trong một TextFrame. |
| [getMarginRight()](#getMarginRight--) | Trả về hoặc đặt lề phải (điểm) trong một TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Trả về hoặc đặt lề phải (điểm) trong một TextFrame. |
| [getMarginTop()](#getMarginTop--) | Trả về hoặc đặt lề trên (điểm) trong một TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Trả về hoặc đặt lề trên (điểm) trong một TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Trả về hoặc đặt lề dưới (điểm) trong một TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Trả về hoặc đặt lề dưới (điểm) trong một TextFrame. |
| [getWrapText()](#getWrapText--) | Đúng nếu văn bản được cuộn tại lề của TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Đúng nếu văn bản được cuộn tại lề của TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Trả về hoặc đặt đoạn văn bản neo dọc trong một TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Trả về hoặc đặt đoạn văn bản neo dọc trong một TextFrame. |
| [getCenterText()](#getCenterText--) | Nếu NullableBool.True thì văn bản nên được căn giữa trong hộp theo chiều ngang. |
| [setCenterText(byte value)](#setCenterText-byte-) | Nếu NullableBool.True thì văn bản nên được căn giữa trong hộp theo chiều ngang. |
| [getTextVerticalType()](#getTextVerticalType--) | Xác định hướng văn bản. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Xác định hướng văn bản. |
| [getAutofitType()](#getAutofitType--) | Trả về hoặc đặt chế độ tự động vừa khớp của văn bản. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Trả về hoặc đặt chế độ tự động vừa khớp của văn bản. |
| [getColumnCount()](#getColumnCount--) | Trả về hoặc đặt số cột trong khu vực văn bản. |
| [setColumnCount(int value)](#setColumnCount-int-) | Trả về hoặc đặt số cột trong khu vực văn bản. |
| [getColumnSpacing()](#getColumnSpacing--) | Trả về hoặc đặt khoảng cách giữa các cột văn bản trong khu vực văn bản (đơn vị điểm). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Trả về hoặc đặt khoảng cách giữa các cột văn bản trong khu vực văn bản (đơn vị điểm). |
| [getThreeDFormat()](#getThreeDFormat--) | Trả về đối tượng ThreeDFormat đại diện cho các thuộc tính hiệu ứng 3D cho một văn bản. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Trả về hoặc đặt việc giữ văn bản hoàn toàn ra khỏi cảnh 3D. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Trả về hoặc đặt việc giữ văn bản hoàn toàn ra khỏi cảnh 3D. |
| [getRotationAngle()](#getRotationAngle--) | Xác định góc quay tùy chỉnh được áp dụng cho văn bản trong hộp giới hạn. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Xác định góc quay tùy chỉnh được áp dụng cho văn bản trong hộp giới hạn. |
| [getTransform()](#getTransform--) | Lấy hoặc đặt hình dạng cuộn văn bản. |
| [setTransform(byte value)](#setTransform-byte-) | Lấy hoặc đặt hình dạng cuộn văn bản. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng khung văn bản hiệu quả với việc kế thừa đã được áp dụng. |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

Trả về kiểu văn bản. Chỉ đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Trả về hoặc đặt lề trái (điểm) trong một TextFrame. Đọc/ghi double.

**Trả về:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Trả về hoặc đặt lề trái (điểm) trong một TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Trả về hoặc đặt lề phải (điểm) trong một TextFrame. Đọc/ghi double.

**Trả về:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Trả về hoặc đặt lề phải (điểm) trong một TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Trả về hoặc đặt lề trên (điểm) trong một TextFrame. Đọc/ghi double.

**Trả về:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Trả về hoặc đặt lề trên (điểm) trong một TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Trả về hoặc đặt lề dưới (điểm) trong một TextFrame. Đọc/ghi double.

**Trả về:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Trả về hoặc đặt lề dưới (điểm) trong một TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Đúng nếu văn bản được cuộn tại lề của TextFrame. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Đúng nếu văn bản được cuộn tại lề của TextFrame. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Trả về hoặc đặt đoạn văn bản neo dọc trong một TextFrame. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Trả về:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Trả về hoặc đặt đoạn văn bản neo dọc trong một TextFrame. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Nếu NullableBool.True thì văn bản nên được căn giữa trong hộp theo chiều ngang. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Nếu NullableBool.True thì văn bản nên được căn giữa trong hộp theo chiều ngang. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Xác định hướng văn bản. Giá trị kết quả của góc quay hiển thị văn bản được tổng hợp từ thuộc tính này và góc tùy chỉnh trong thuộc tính RotationAngle. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Trả về:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Xác định hướng văn bản. Giá trị kết quả của góc quay hiển thị văn bản được tổng hợp từ thuộc tính này và góc tùy chỉnh trong thuộc tính RotationAngle. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Trả về hoặc đặt chế độ tự động vừa khớp của văn bản. Đọc/ghi [TextAutofitType](../../com.aspose.slides/textautofittype).

**Trả về:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Trả về hoặc đặt chế độ tự động vừa khớp của văn bản. Đọc/ghi [TextAutofitType](../../com.aspose.slides/textautofittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Trả về hoặc đặt số cột trong khu vực văn bản. Giá trị này phải là số dương. Nếu không, giá trị sẽ được đặt thành 0. Giá trị 0 có nghĩa là không xác định. Đọc/ghi int.

**Trả về:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Trả về hoặc đặt số cột trong khu vực văn bản. Giá trị này phải là số dương. Nếu không, giá trị sẽ được đặt thành 0. Giá trị 0 có nghĩa là không xác định. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Trả về hoặc đặt khoảng cách giữa các cột văn bản trong khu vực văn bản (đơn vị điểm). Điều này chỉ áp dụng khi có nhiều hơn 1 cột. Giá trị này phải là số dương. Nếu không, giá trị sẽ được đặt thành 0. Đọc/ghi double.

**Trả về:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Trả về hoặc đặt khoảng cách giữa các cột văn bản trong khu vực văn bản (đơn vị điểm). Điều này chỉ áp dụng khi có nhiều hơn 1 cột. Giá trị này phải là số dương. Nếu không, giá trị sẽ được đặt thành 0. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Trả về đối tượng ThreeDFormat đại diện cho các thuộc tính hiệu ứng 3D cho một văn bản. Chỉ đọc [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Set text transformation
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Set Extrusion
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Set Contour
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Set Depth
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Set Material
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Set Lighting
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Set camera type
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

Trả về hoặc đặt việc giữ văn bản hoàn toàn ra khỏi cảnh 3D. Đọc/ghi boolean.

**Trả về:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

Trả về hoặc đặt việc giữ văn bản hoàn toàn ra khỏi cảnh 3D. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Xác định góc quay tùy chỉnh được áp dụng cho văn bản trong hộp giới hạn. Nếu không được chỉ định, góc quay của hình dạng đi kèm sẽ được sử dụng. Nếu được chỉ định, thì sẽ được áp dụng độc lập với hình dạng. Nghĩa là hình dạng có thể có góc quay riêng ngoài góc quay áp dụng cho văn bản. Giá trị kết quả của góc quay hiển thị văn bản được tổng hợp từ thuộc tính này và loại dọc định trước trong thuộc tính TextVerticalType. Đọc/ghi float.

--------------------

> ```
> Xem trường hợp khi một hình có góc quay 90 độ theo chiều kim đồng hồ được áp dụng. 
>  Thêm vào đó, phần thân văn bản tự nó có góc quay -90 độ ngược chiều kim đồng hồ được áp dụng. 
>  Khi đó, hình tạo ra sẽ trông như bị quay nhưng văn bản bên trong nó sẽ trông như thể chưa bị quay chút nào. 
> ```


**Trả về:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Xác định góc quay tùy chỉnh được áp dụng cho văn bản trong hộp giới hạn. Nếu không được chỉ định, góc quay của hình dạng đi kèm sẽ được sử dụng. Nếu được chỉ định, thì sẽ được áp dụng độc lập với hình dạng. Nghĩa là hình dạng có thể có góc quay riêng ngoài góc quay áp dụng cho văn bản. Giá trị kết quả của góc quay hiển thị văn bản được tổng hợp từ thuộc tính này và loại dọc định trước trong thuộc tính TextVerticalType. Đọc/ghi float.

--------------------

> ```
> Xem trường hợp khi một hình có góc quay 90 độ theo chiều kim đồng hồ được áp dụng cho nó. 
>  Thêm vào đó, phần thân văn bản tự nó có góc quay -90 độ 
>  ngược chiều kim đồng hồ được áp dụng cho nó. Khi đó, hình tạo ra sẽ trông như
>  được quay nhưng văn bản bên trong nó sẽ trông như thể chưa bị quay chút nào.
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Lấy hoặc đặt hình dạng cuộn văn bản. Đọc/ghi [TextShapeType](../../com.aspose.slides/textshapetype).

**Trả về:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Lấy hoặc đặt hình dạng cuộn văn bản. Đọc/ghi [TextShapeType](../../com.aspose.slides/textshapetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

Lấy dữ liệu định dạng khung văn bản hiệu quả với việc kế thừa đã được áp dụng.

**Trả về:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).