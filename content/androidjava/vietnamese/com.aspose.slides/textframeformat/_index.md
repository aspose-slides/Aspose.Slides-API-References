---
title: TextFrameFormat
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Chứa các thuộc tính formatTextFrameFormatting của TextFrames.
type: docs
url: /vi/com.aspose.slides/textframeformat/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Chứa các thuộc tính formatTextFrameFormatting của TextFrame.
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Khởi tạo một thể hiện mới của lớp [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Trả về kiểu dáng của văn bản. |
| [getThreeDFormat()](#getThreeDFormat--) | Trả về đối tượng ThreeDFormat biểu thị các thuộc tính hiệu ứng 3D cho văn bản. |
| [getMarginLeft()](#getMarginLeft--) | Trả về hoặc đặt lề trái (điểm) trong TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Trả về hoặc đặt lề trái (điểm) trong TextFrame. |
| [getMarginRight()](#getMarginRight--) | Trả về hoặc đặt lề phải (điểm) trong TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Trả về hoặc đặt lề phải (điểm) trong TextFrame. |
| [getMarginTop()](#getMarginTop--) | Trả về hoặc đặt lề trên (điểm) trong TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Trả về hoặc đặt lề trên (điểm) trong TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Trả về hoặc đặt lề dưới (điểm) trong TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Trả về hoặc đặt lề dưới (điểm) trong TextFrame. |
| [getWrapText()](#getWrapText--) | Đúng nếu văn bản được bọc ở các lề của TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Đúng nếu văn bản được bọc ở các lề của TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Trả về hoặc đặt văn bản neo dọc trong TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Trả về hoặc đặt văn bản neo dọc trong TextFrame. |
| [getCenterText()](#getCenterText--) | Nếu NullableBool.True thì văn bản nên được căn giữa trong hộp theo chiều ngang. |
| [setCenterText(byte value)](#setCenterText-byte-) | Nếu NullableBool.True thì văn bản nên được căn giữa trong hộp theo chiều ngang. |
| [getTextVerticalType()](#getTextVerticalType--) | Xác định hướng văn bản. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Xác định hướng văn bản. |
| [getAutofitType()](#getAutofitType--) | Trả về hoặc đặt chế độ tự động vừa của văn bản. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Trả về hoặc đặt chế độ tự động vừa của văn bản. |
| [getColumnCount()](#getColumnCount--) | Trả về hoặc đặt số cột trong khu vực văn bản. |
| [setColumnCount(int value)](#setColumnCount-int-) | Trả về hoặc đặt số cột trong khu vực văn bản. |
| [getColumnSpacing()](#getColumnSpacing--) | Trả về hoặc đặt khoảng cách giữa các cột văn bản trong khu vực văn bản (đơn vị điểm). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Trả về hoặc đặt khoảng cách giữa các cột văn bản trong khu vực văn bản (đơn vị điểm). |
| [getRotationAngle()](#getRotationAngle--) | Chỉ định góc quay tùy chỉnh được áp dụng cho văn bản trong khung bao. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Chỉ định góc quay tùy chỉnh được áp dụng cho văn bản trong khung bao. |
| [getTransform()](#getTransform--) | Lấy hoặc đặt hình dạng bọc văn bản. |
| [setTransform(byte value)](#setTransform-byte-) | Lấy hoặc đặt hình dạng bọc văn bản. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Lấy hoặc đặt việc giữ văn bản phẳng ngay cả khi đã áp dụng hiệu ứng Xoay 3-D. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Lấy hoặc đặt việc giữ văn bản phẳng ngay cả khi đã áp dụng hiệu ứng Xoay 3-D. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng khung văn bản hiệu quả với kế thừa đã được áp dụng. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```


Khởi tạo một thể hiện mới của lớp [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```


Phiên bản. Kiểu long chỉ-đọc.

**Trả về:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```


Trả về kiểu dáng của văn bản. Chỉ-đọc [ITextStyle](../../com.aspose.slides/itextstyle).

**Trả về:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```


Trả về đối tượng ThreeDFormat biểu thị các thuộc tính hiệu ứng 3D cho văn bản. Chỉ-đọc [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Đặt biến đổi văn bản
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Đặt Extrusion
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Đặt Contour
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Đặt độ sâu
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Đặt vật liệu
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Đặt ánh sáng
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Đặt kiểu camera
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```


Trả về hoặc đặt lề trái (điểm) trong TextFrame. Đọc/ghi double.

**Trả về:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```


Trả về hoặc đặt lề trái (điểm) trong TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```


Trả về hoặc đặt lề phải (điểm) trong TextFrame. Đọc/ghi double.

**Trả về:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```


Trả về hoặc đặt lề phải (điểm) trong TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```


Trả về hoặc đặt lề trên (điểm) trong TextFrame. Đọc/ghi double.

**Trả về:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```


Trả về hoặc đặt lề trên (điểm) trong TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


Trả về hoặc đặt lề dưới (điểm) trong TextFrame. Đọc/ghi double.

**Trả về:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```


Trả về hoặc đặt lề dưới (điểm) trong TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```


Đúng nếu văn bản được bọc ở các lề của TextFrame. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```


Đúng nếu văn bản được bọc ở các lề của TextFrame. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```


Trả về hoặc đặt văn bản neo dọc trong TextFrame. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Trả về:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```


Trả về hoặc đặt văn bản neo dọc trong TextFrame. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```


Nếu NullableBool.True thì văn bản nên được căn giữa trong hộp theo chiều ngang. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```


Nếu NullableBool.True thì văn bản nên được căn giữa trong hộp theo chiều ngang. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


Xác định hướng văn bản. Giá trị kết quả của góc quay trực quan được tổng hợp từ thuộc tính này và góc tùy chỉnh trong thuộc tính RotationAngle. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Trả về:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


Xác định hướng văn bản. Giá trị kết quả của góc quay trực quan được tổng hợp từ thuộc tính này và góc tùy chỉnh trong thuộc tính RotationAngle. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```


Trả về hoặc đặt chế độ tự động vừa của văn bản. Đọc/ghi [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```


Trả về hoặc đặt chế độ tự động vừa của văn bản. Đọc/ghi [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```


Trả về hoặc đặt số cột trong khu vực văn bản. Giá trị này phải là số dương. Nếu không, giá trị sẽ được đặt về 0. Giá trị 0 có nghĩa là không xác định. Đọc/ghi int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```


Trả về hoặc đặt số cột trong khu vực văn bản. Giá trị này phải là số dương. Nếu không, giá trị sẽ được đặt về 0. Giá trị 0 có nghĩa là không xác định. Đọc/ghi int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```


Trả về hoặc đặt khoảng cách giữa các cột văn bản trong khu vực văn bản (đơn vị điểm). Giá trị này chỉ áp dụng khi có hơn 1 cột. Giá trị này phải là số dương. Nếu không, giá trị sẽ được đặt về 0. Đọc/ghi double.

**Trả về:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```


Trả về hoặc đặt khoảng cách giữa các cột văn bản trong khu vực văn bản (đơn vị điểm). Giá trị này chỉ áp dụng khi có hơn 1 cột. Giá trị này phải là số dương. Nếu không, giá trị sẽ được đặt về 0. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```


Chỉ định góc quay tùy chỉnh được áp dụng cho văn bản trong khung bao. Nếu không chỉ định, sẽ sử dụng góc quay của hình dạng đi kèm. Nếu chỉ định, sẽ được áp dụng độc lập với hình dạng. Nghĩa là hình dạng có thể có góc quay riêng, đồng thời văn bản cũng có góc quay riêng. Giá trị kết quả của góc quay trực quan được tổng hợp từ thuộc tính này và loại dọc đã định trước trong thuộc tính TextVerticalType. Đọc/ghi float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Trả về:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```


Chỉ định góc quay tùy chỉnh được áp dụng cho văn bản trong khung bao. Nếu không chỉ định, sẽ sử dụng góc quay của hình dạng đi kèm. Nếu chỉ định, sẽ được áp dụng độc lập với hình dạng. Nghĩa là hình dạng có thể có góc quay riêng, đồng thời văn bản cũng có góc quay riêng. Giá trị kết quả của góc quay trực quan được tổng hợp từ thuộc tính này và loại dọc đã định trước trong thuộc tính TextVerticalType. Đọc/ghi float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```


Lấy hoặc đặt hình dạng bọc văn bản. Đọc/ghi [TextShapeType](../../com.aspose.slides/textshapetype).

**Trả về:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```


Lấy hoặc đặt hình dạng bọc văn bản. Đọc/ghi [TextShapeType](../../com.aspose.slides/textshapetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```


Lấy hoặc đặt việc giữ văn bản phẳng ngay cả khi đã áp dụng hiệu ứng Xoay 3-D. Đọc/ghi boolean.

**Trả về:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```


Lấy hoặc đặt việc giữ văn bản phẳng ngay cả khi đã áp dụng hiệu ứng Xoay 3-D. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```


Lấy dữ liệu định dạng khung văn bản hiệu quả với kế thừa đã được áp dụng.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).