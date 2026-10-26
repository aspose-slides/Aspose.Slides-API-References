---
title: ThreeDFormat
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงคุณสมบัติ 3-D.
type: docs
url: /th/com.aspose.slides/threedformat/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

แสดงคุณสมบัติ 3-D.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // เพิ่มรูปด้วยเมธอด AddAutoShape
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // กำหนด TextFrame และคุณสมบัติต่างๆ
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
>      // เพิ่มรูปด้วยเมธอด AddAutoShape
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // กำหนด TextFrame และคุณสมบัติต่างๆ
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
>      // เพิ่มรูปด้วยเมธอด AddAutoShape
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // กำหนด TextFrame และคุณสมบัตุต่างๆ
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
| [getContourWidth()](#getContourWidth--) | คืนค่า หรือกำหนดความกว้างของคอนทัวร์ 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | คืนค่า หรือกำหนดความกว้างของคอนทัวร์ 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | คืนค่า หรือกำหนดความสูงของเอฟเฟกต์การดันออก. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | คืนค่า หรือกำหนดความสูงของเอฟเฟกต์การดันออก. |
| [getDepth()](#getDepth--) | คืนค่า หรือกำหนดความลึกของรูปทรง 3D. |
| [setDepth(double value)](#setDepth-double-) | คืนค่า หรือกำหนดความลึกของรูปทรง 3D. |
| [getBevelTop()](#getBevelTop--) | คืนค่า หรือกำหนดประเภทของบีเวิลด้านบน 3D. |
| [getBevelBottom()](#getBevelBottom--) | คืนค่า หรือกำหนดประเภทของบีเวิลด้านล่าง 3D. |
| [getContourColor()](#getContourColor--) | คืนค่า หรือกำหนดสีของคอนทัวร์. |
| [getExtrusionColor()](#getExtrusionColor--) | คืนค่า หรือกำหนดสีของการดันออก. |
| [getCamera()](#getCamera--) | คืนค่า หรือกำหนดการตั้งค่าของกล้อง. |
| [getLightRig()](#getLightRig--) | คืนค่า หรือกำหนดประเภทของแสง. |
| [getMaterial()](#getMaterial--) | คืนค่า หรือกำหนดประเภทของวัสดุ. |
| [setMaterial(int value)](#setMaterial-int-) | คืนค่า หรือกำหนดประเภทของวัสดุ. |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบ 3-D ที่มีผลอย่างมีประสิทธิภาพพร้อมการสืบทอดที่นำไปใช้. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

คืนค่า หรือกำหนดความกว้างของคอนทัวร์ 3D. อ่าน/เขียน double.

**คืนค่า:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

คืนค่า หรือกำหนดความกว้างของคอนทัวร์ 3D. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

คืนค่า หรือกำหนดความสูงของเอฟเฟกต์การดันออก. อ่าน/เขียน double.

**คืนค่า:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

คืนค่า หรือกำหนดความสูงของเอฟเฟกต์การดันออก. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public final double getDepth()
```

คืนค่า หรือกำหนดความลึกของรูปทรง 3D. อ่าน/เขียน double.

**คืนค่า:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

คืนค่า หรือกำหนดความลึกของรูปทรง 3D. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

คืนค่า หรือกำหนดประเภทของบีเวิลด้านบน 3D. อ่านอย่างเดียว [IShapeBevel](../../com.aspose.slides/ishapebevel).

**คืนค่า:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

คืนค่า หรือกำหนดประเภทของบีเวิลด้านล่าง 3D. อ่านอย่างเดียว [IShapeBevel](../../com.aspose.slides/ishapebevel).

**คืนค่า:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

คืนค่า หรือกำหนดสีของคอนทัวร์. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

คืนค่า หรือกำหนดสีของการดันออก. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

คืนค่า หรือกำหนดการตั้งค่าของกล้อง. อ่านอย่างเดียว [ICamera](../../com.aspose.slides/icamera).

**คืนค่า:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

คืนค่า หรือกำหนดประเภทของแสง. อ่านอย่างเดียว [ILightRig](../../com.aspose.slides/ilightrig).

**คืนค่า:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

คืนค่า หรือกำหนดประเภทของวัสดุ. อ่าน/เขียน [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**คืนค่า:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

คืนค่า หรือกำหนดประเภทของวัสดุ. อ่าน/เขียน [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบ 3-D ที่มีผลอย่างมีประสิทธิภาพพร้อมการสืบทอดที่นำไปใช้.

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

**คืนค่า:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - หนึ่ง [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).