---
title: ThreeDFormat
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn các thuộc tính 3D.
type: docs
url: /vi/com.aspose.slides/threedformat/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

Biểu diễn các thuộc tính 3D.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Tạo một thể hiện của lớp Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Thêm một hình dạng bằng phương thức AddAutoShape
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Định nghĩa TextFrame và các thuộc tính của nó
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Định nghĩa các thuộc tính ThreeDFormat
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Lưu tệp Presentation
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Tạo một thể hiện của lớp Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Thêm một hình dạng bằng phương thức AddAutoShape
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Định nghĩa TextFrame và các thuộc tính của nó
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Cấu hình FillFormat.FillType thành FillType.Gradient và định nghĩa các thuộc tính gradient
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Định nghĩa các thuộc tính ThreeDFormat
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Lưu tệp Presentation
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Tạo một thể hiện của lớp Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Thêm một hình dạng bằng phương thức AddAutoShape
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Định nghĩa TextFrame và các thuộc tính của nó
>      shape.getTextFrame().setText("3D Text");
>      // Cấu hình FillFormat.FillType thành FillType.NoFill
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Cấu hình Phần của TextFrame và thiết lập các thuộc tính của PortionFormat
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // Thiết lập hiệu ứng biến đổi WordArt "Arch Up"
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Định nghĩa các thuộc tính ThreeDFormat của ITextFrame
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Lưu tệp Presentation
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Trả về hoặc đặt độ rộng của một đường viền 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Trả về hoặc đặt độ rộng của một đường viền 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Trả về hoặc đặt độ cao của một hiệu ứng đùn. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Trả về hoặc đặt độ cao của một hiệu ứng đùn. |
| [getDepth()](#getDepth--) | Trả về hoặc đặt độ sâu của một hình dạng 3D. |
| [setDepth(double value)](#setDepth-double-) | Trả về hoặc đặt độ sâu của một hình dạng 3D. |
| [getBevelTop()](#getBevelTop--) | Trả về hoặc đặt kiểu của góc chêm trên 3D. |
| [getBevelBottom()](#getBevelBottom--) | Trả về hoặc đặt kiểu của góc chêm dưới 3D. |
| [getContourColor()](#getContourColor--) | Trả về hoặc đặt màu của đường viền. |
| [getExtrusionColor()](#getExtrusionColor--) | Trả về hoặc đặt màu của đùn. |
| [getCamera()](#getCamera--) | Trả về hoặc đặt cài đặt của máy ảnh. |
| [getLightRig()](#getLightRig--) | Trả về hoặc đặt kiểu của ánh sáng. |
| [getMaterial()](#getMaterial--) | Trả về hoặc đặt kiểu của vật liệu. |
| [setMaterial(int value)](#setMaterial-int-) | Trả về hoặc đặt kiểu của vật liệu. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng 3D hiệu quả với kế thừa đã được áp dụng. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Phiên bản. Chỉ-đọc long.

**Trả về:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```


Trả về hoặc đặt độ rộng của một đường viền 3D. Đọc/ghi double.

**Trả về:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```


Trả về hoặc đặt độ rộng của một đường viền 3D. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```


Trả về hoặc đặt độ cao của một hiệu ứng đùn. Đọc/ghi double.

**Trả về:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```


Trả về hoặc đặt độ cao của một hiệu ứng đùn. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public final double getDepth()
```


Trả về hoặc đặt độ sâu của một hình dạng 3D. Đọc/ghi double.

**Trả về:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```


Trả về hoặc đặt độ sâu của một hình dạng 3D. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```


Trả về hoặc đặt kiểu của góc chêm trên 3D. Chỉ-đọc [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Trả về:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```


Trả về hoặc đặt kiểu của góc chêm dưới 3D. Chỉ-đọc [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Trả về:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```


Trả về hoặc đặt màu của đường viền. Chỉ-đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```


Trả về hoặc đặt màu của đùn. Chỉ-đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```


Trả về hoặc đặt cài đặt của máy ảnh. Chỉ-đọc [ICamera](../../com.aspose.slides/icamera).

**Trả về:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```


Trả về hoặc đặt kiểu của ánh sáng. Chỉ-đọc [ILightRig](../../com.aspose.slides/ilightrig).

**Trả về:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```


Trả về hoặc đặt kiểu của vật liệu. Đọc/ghi [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Trả về:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```


Trả về hoặc đặt kiểu của vật liệu. Đọc/ghi [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```


Lấy dữ liệu định dạng 3D hiệu quả với kế thừa đã được áp dụng.

--------------------

> ```
> This example demonstrates how to get effective properties for camera, light rig and shape's top bevel.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try 
>  {
>      IThreeDFormatEffectiveData threeDEffectiveData = pres.getSlides().get_Item(0).getShapes().get_Item(0).getThreeDFormat().getEffective();
>      System.out.println("= Effective camera properties =");
>      System.out.println("Type: " + threeDEffectiveData.getCamera().getCameraType());
>      System.out.println("Field of view: " + threeDEffectiveData.getCamera().getFieldOfViewAngle());
>      System.out.println("Zoom: " + threeDEffectiveData.getCamera().getZoom());
>      System.out.println("= Effective light rig properties =");
>      System.out.println("Type: " + threeDEffectiveData.getLightRig().getLightType());
>      System.out.println("Direction: " + threeDEffectiveData.getLightRig().getDirection());
>      System.out.println("= Effective shape's top face relief properties =");
>      System.out.println("Type: " + threeDEffectiveData.getBevelTop().getBevelType());
>      System.out.println("Width: " + threeDEffectiveData.getBevelTop().getWidth());
>      System.out.println("Height: " + threeDEffectiveData.getBevelTop().getHeight());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).