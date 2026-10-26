---
title: ThreeDFormat
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر خواص سه‌بعدی است.
type: docs
url: /fa/com.aspose.slides/threedformat/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)  
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

خواص سه‌بعدی را نشان می‌دهد.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Create an instance of Presentation class.
>  // یک نمونه از کلاس Presentation ایجاد کنید.
>  Presentation pres = new Presentation();
>  try {
>      // Add a shape using AddAutoShape method
>      // یک شکل با استفاده از متد AddAutoShape اضافه کنید.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Define TextFrame and its properties
>      // TextFrame و ویژگی‌های آن را تعریف کنید.
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Define ThreeDFormat Properties
>      // ویژگی‌های ThreeDFormat را تعریف کنید.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Save the Presentation file
>      // فایل Presentation را ذخیره کنید.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Create an instance of Presentation class.
>  // یک نمونه از کلاس Presentation ایجاد کنید.
>  Presentation pres = new Presentation();
>  try {
>      // Add a shape using AddAutoShape method
>      // یک شکل با استفاده از متد AddAutoShape اضافه کنید.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Define TextFrame and its properties
>      // TextFrame و ویژگی‌های آن را تعریف کنید.
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Configure FillFormat.FillType as FillType.Gradient and define gradient properties
>      // FillFormat.FillType را به FillType.Gradient تنظیم کنید و ویژگی‌های گرادیان را تعریف کنید.
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Define ThreeDFormat Properties
>      // ویژگی‌های ThreeDFormat را تعریف کنید.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Save the Presentation file
>      // فایل Presentation را ذخیره کنید.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Create an instance of Presentation class.
>  // یک نمونه از کلاس Presentation ایجاد کنید.
>  Presentation pres = new Presentation();
>  try {
>      // Add a shape using AddAutoShape method
>      // یک شکل با استفاده از متد AddAutoShape اضافه کنید.
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Define TextFrame and its properties
>      // TextFrame و ویژگی‌های آن را تعریف کنید.
>      shape.getTextFrame().setText("3D Text");
>      // Configure FillFormat.FillType as FillType.NoFill
>      // FillFormat.FillType را به FillType.NoFill تنظیم کنید.
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Configure Portion of TextFrame and configure properties of PortionFormat
>      // بخش TextFrame را تنظیم کنید و ویژگی‌های PortionFormat را پیکربندی کنید.
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // setup "Arch Up" WordArt transform effect
>      // تنظیم اثر تبدیل WordArt "Arch Up"
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Define ThreeDFormat Properties of ITextFrame
>      // ویژگی‌های ThreeDFormat برای ITextFrame را تعریف کنید.
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Save the Presentation file
>      // فایل Presentation را ذخیره کنید.
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## متدها

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | عرض یک کانتور 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [setContourWidth(double value)](#setContourWidth-double-) | عرض یک کانتور 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [getExtrusionHeight()](#getExtrusionHeight--) | ارتفاع یک اثر برآمدگی را برمی‌گرداند یا تنظیم می‌کند. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | ارتفاع یک اثر برآمدگی را برمی‌گرداند یا تنظیم می‌کند. |
| [getDepth()](#getDepth--) | عمق یک شکل 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [setDepth(double value)](#setDepth-double-) | عمق یک شکل 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [getBevelTop()](#getBevelTop--) | نوع یک bevel بالا 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [getBevelBottom()](#getBevelBottom--) | نوع یک bevel پایین 3D را برمی‌گرداند یا تنظیم می‌کند. |
| [getContourColor()](#getContourColor--) | رنگ یک کانتور را برمی‌گرداند یا تنظیم می‌کند. |
| [getExtrusionColor()](#getExtrusionColor--) | رنگ یک برآمدگی را برمی‌گرداند یا تنظیم می‌کند. |
| [getCamera()](#getCamera--) | تنظیمات یک دوربین را برمی‌گرداند یا تنظیم می‌کند. |
| [getLightRig()](#getLightRig--) | نوع یک نور را برمی‌گرداند یا تنظیم می‌کند. |
| [getMaterial()](#getMaterial--) | نوع یک ماده را برمی‌گرداند یا تنظیم می‌کند. |
| [setMaterial(int value)](#setMaterial-int-) | نوع یک ماده را برمی‌گرداند یا تنظیم می‌کند. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی موثر 3-D را با وراثت اعمال‌شده دریافت می‌کند. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**بازگشت:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

عرض یک کانتور 3D را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

عرض یک کانتور 3D را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

ارتفاع یک اثر برآمدگی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

ارتفاع یک اثر برآمدگی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public final double getDepth()
```

عمق یک شکل 3D را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**بازگشت:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

عمق یک شکل 3D را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی double.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

نوع یک bevel بالا 3D را برمی‌گرداند یا تنظیم می‌کند. فقط خواندنی [IShapeBevel](../../com.aspose.slides/ishapebevel).

**بازگشت:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

نوع یک bevel پایین 3D را برمی‌گرداند یا تنظیم می‌کند. فقط خواندنی [IShapeBevel](../../com.aspose.slides/ishapebevel).

**بازگشت:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

رنگ یک کانتور را برمی‌گرداند یا تنظیم می‌کند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

رنگ یک برآمدگی را برمی‌گرداند یا تنظیم می‌کند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

تنظیمات یک دوربین را برمی‌گرداند یا تنظیم می‌کند. فقط خواندنی [ICamera](../../com.aspose.slides/icamera).

**بازگشت:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

نوع یک نور را برمی‌گرداند یا تنظیم می‌کند. فقط خواندنی [ILightRig](../../com.aspose.slides/ilightrig).

**بازگشت:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

نوع یک ماده را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**بازگشت:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

نوع یک ماده را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی موثر 3-D را با وراثت اعمال‌شده دریافت می‌کند.

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

**بازگشت:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - یک [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).