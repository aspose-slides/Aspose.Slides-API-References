---
title: ThreeDFormat
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงถึงคุณสมบัติ 3-มิติ.
type: docs
url: /th/com.aspose.slides/threedformat/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**ทั้งหมดที่ทำตามอินเตอร์เฟส:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

แสดงคุณสมบัติ 3-มิติ.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // เพิ่มรูปร่างโดยใช้เมธอด AddAutoShape method
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // กำหนด TextFrame และคุณสมบัติของมัน
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // กำหนดคุณสมบัติ ThreeDFormat
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // บันทึกไฟล์ Presentation
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // เพิ่มรูปร่างโดยใช้เมธอด AddAutoShape method
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // กำหนด TextFrame และคุณสมบัติของมัน
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // กำหนด FillFormat.FillType เป็น FillType.Gradient และกำหนดคุณสมบัติของ gradient
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // กำหนดคุณสมบัติ ThreeDFormat
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // บันทึกไฟล์ Presentation
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // เพิ่มรูปร่างโดยใช้เมธอด AddAutoShape method
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // กำหนด TextFrame และคุณสมบัติของมัน
>      shape.getTextFrame().setText("3D Text");
>      // กำหนด FillFormat.FillType เป็น FillType.NoFill
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // กำหนด Portion ของ TextFrame และกำหนดคุณสมบัติของ PortionFormat
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // ตั้งค่าเอฟเฟกต์การแปลง WordArt "Arch Up"
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // กำหนดคุณสมบัติ ThreeDFormat ของ ITextFrame
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // บันทึกไฟล์ Presentation
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | คืนค่า หรือ ตั้งค่าความกว้างของคอนทัวร์ 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | คืนค่า หรือ ตั้งค่าความกว้างของคอนทัวร์ 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | คืนค่า หรือ ตั้งค่าความสูงของเอฟเฟกต์ extrusion. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | คืนค่า หรือ ตั้งค่าความสูงของเอฟเฟกต์ extrusion. |
| [getDepth()](#getDepth--) | คืนค่า หรือ ตั้งค่าความลึกของรูปร่าง 3D. |
| [setDepth(double value)](#setDepth-double-) | คืนค่า หรือ ตั้งค่าความลึกของรูปร่าง 3D. |
| [getBevelTop()](#getBevelTop--) | คืนค่า หรือ ตั้งค่าประเภทของ bevel 3D ด้านบน. |
| [getBevelBottom()](#getBevelBottom--) | คืนค่า หรือ ตั้งค่าประเภทของ bevel 3D ด้านล่าง. |
| [getContourColor()](#getContourColor--) | คืนค่า หรือ ตั้งค่าสีของคอนทัวร์. |
| [getExtrusionColor()](#getExtrusionColor--) | คืนค่า หรือ ตั้งค่าสีของ extrusion. |
| [getCamera()](#getCamera--) | คืนค่า หรือ ตั้งค่าการตั้งค่าของกล้อง. |
| [getLightRig()](#getLightRig--) | คืนค่า หรือ ตั้งค่าประเภทของแสง. |
| [getMaterial()](#getMaterial--) | คืนค่า หรือ ตั้งค่าประเภทของวัสดุ. |
| [setMaterial(int value)](#setMaterial-int-) | คืนค่า หรือ ตั้งค่าประเภทของวัสดุ. |
| [getEffective()](#getEffective--) | ดึงข้อมูลการจัดรูปแบบ 3-มิติที่มีผลโดยมีการสืบทอดใช้. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**Returns:**
long

### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

คืนค่า หรือ ตั้งค่าความกว้างของคอนทัวร์ 3D. อ่าน/เขียน double.

**Returns:**
double

### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

คืนค่า หรือ ตั้งค่าความกว้างของคอนทัวร์ 3D. อ่าน/เขียน double.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

คืนค่า หรือ ตั้งค่าความสูงของเอฟเฟกต์ extrusion. อ่าน/เขียน double.

**Returns:**
double

### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

คืนค่า หรือ ตั้งค่าความสูงของเอฟเฟกต์ extrusion. อ่าน/เขียน double.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```

คืนค่า หรือ ตั้งค่าความลึกของรูปร่าง 3D. อ่าน/เขียน double.

**Returns:**
double

### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

คืนค่า หรือ ตั้งค่าความลึกของรูปร่าง 3D. อ่าน/เขียน double.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

คืนค่า หรือ ตั้งค่าประเภทของ bevel 3D ด้านบน. อ่านอย่างเดียว [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Returns:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

คืนค่า หรือ ตั้งค่าประเภทของ bevel 3D ด้านล่าง. อ่านอย่างเดียว [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Returns:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

คืนค่า หรือ ตั้งค่าสีของคอนทัวร์. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

คืนค่า หรือ ตั้งค่าสีของ extrusion. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

คืนค่า หรือ ตั้งค่าการตั้งค่าของกล้อง. อ่านอย่างเดียว [ICamera](../../com.aspose.slides/icamera).

**Returns:**
[ICamera](../../com.aspose.slides/icamera)

### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

คืนค่า หรือ ตั้งค่าประเภทของแสง. อ่านอย่างเดียว [ILightRig](../../com.aspose.slides/ilightrig).

**Returns:**
[ILightRig](../../com.aspose.slides/ilightrig)

### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

คืนค่า หรือ ตั้งค่าประเภทของวัสดุ. อ่าน/เขียน [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Returns:**
int

### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

คืนค่า หรือ ตั้งค่าประเภทของวัสดุ. อ่าน/เขียน [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

ดึงข้อมูลการจัดรูปแบบ 3-มิติที่มีผลโดยมีการสืบทอดใช้.

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

**Returns:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).