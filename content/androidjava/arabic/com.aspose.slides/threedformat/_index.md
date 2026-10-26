---
title: ThreeDFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل خصائص ثلاثية الأبعاد.
type: docs
url: /ar/com.aspose.slides/threedformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

يمثل خصائص ثلاثية الأبعاد.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // إنشاء كائن من فئة Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // إضافة شكل باستخدام طريقة AddAutoShape method
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // تعريف TextFrame وخصائصه
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // تعريف خصائص ThreeDFormat
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // حفظ ملف Presentation
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // إنشاء كائن من فئة Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // إضافة شكل باستخدام طريقة AddAutoShape method
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // تعريف TextFrame وخصائصه
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // تكوين FillFormat.FillType كـ FillType.Gradient وتعريف خصائص التدرج اللوني
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // تعريف خصائص ThreeDFormat
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // حفظ ملف Presentation
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // إنشاء كائن من فئة Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // إضافة شكل باستخدام طريقة AddAutoShape method
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // تعريف TextFrame وخصائصه
>      shape.getTextFrame().setText("3D Text");
>      // تكوين FillFormat.FillType كـ FillType.NoFill
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // تكوين جزء من TextFrame وتكوين خصائص PortionFormat
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // إعداد تأثير تحويل WordArt "Arch Up"
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // تعريف خصائص ThreeDFormat لـ ITextFrame
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // حفظ ملف Presentation
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | يعيد أو يحدد عرض حد ثلاثي الأبعاد. |
| [setContourWidth(double value)](#setContourWidth-double-) | يعيد أو يحدد عرض حد ثلاثي الأبعاد. |
| [getExtrusionHeight()](#getExtrusionHeight--) | يعيد أو يحدد ارتفاع تأثير البثق. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | يعيد أو يحدد ارتفاع تأثير البثق. |
| [getDepth()](#getDepth--) | يعيد أو يحدد عمق الشكل ثلاثي الأبعاد. |
| [setDepth(double value)](#setDepth-double-) | يعيد أو يحدد عمق الشكل ثلاثي الأبعاد. |
| [getBevelTop()](#getBevelTop--) | يعيد أو يحدد نوع الحافة الثلاثية الأبعاد العليا. |
| [getBevelBottom()](#getBevelBottom--) | يعيد أو يحدد نوع الحافة الثلاثية الأبعاد السفلية. |
| [getContourColor()](#getContourColor--) | يعيد أو يحدد لون الحد. |
| [getExtrusionColor()](#getExtrusionColor--) | يعيد أو يحدد لون البثق. |
| [getCamera()](#getCamera--) | يعيد أو يحدد إعدادات الكاميرا. |
| [getLightRig()](#getLightRig--) | يعيد أو يحدد نوع الإضاءة. |
| [getMaterial()](#getMaterial--) | يعيد أو يحدد نوع المادة. |
| [setMaterial(int value)](#setMaterial-int-) | يعيد أو يحدد نوع المادة. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق ثلاثية الأبعاد الفعّالة مع تطبيق الوراثة. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط من نوع long.

**الإرجاع:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

يعيد أو يحدد عرض حد ثلاثي الأبعاد. قراءة/كتابة من نوع double.

**الإرجاع:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

يعيد أو يحدد عرض حد ثلاثي الأبعاد. قراءة/كتابة من نوع double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

يعيد أو يحدد ارتفاع تأثير البثق. قراءة/كتابة من نوع double.

**الإرجاع:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

يعيد أو يحدد ارتفاع تأثير البثق. قراءة/كتابة من نوع double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public final double getDepth()
```

يعيد أو يحدد عمق الشكل ثلاثي الأبعاد. قراءة/كتابة من نوع double.

**الإرجاع:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

يعيد أو يحدد عمق الشكل ثلاثي الأبعاد. قراءة/كتابة من نوع double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

يعيد أو يحدد نوع الحافة الثلاثية الأبعاد العليا. قراءة فقط [IShapeBevel](../../com.aspose.slides/ishapebevel).

**الإرجاع:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

يعيد أو يحدد نوع الحافة الثلاثية الأبعاد السفلية. قراءة فقط [IShapeBevel](../../com.aspose.slides/ishapebevel).

**الإرجاع:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

يعيد أو يحدد لون الحد. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

يعيد أو يحدد لون البثق. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

يعيد أو يحدد إعدادات الكاميرا. قراءة فقط [ICamera](../../com.aspose.slides/icamera).

**الإرجاع:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

يعيد أو يحدد نوع الإضاءة. قراءة فقط [ILightRig](../../com.aspose.slides/ilightrig).

**الإرجاع:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

يعيد أو يحدد نوع المادة. قراءة/كتابة [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**الإرجاع:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

يعيد أو يحدد نوع المادة. قراءة/كتابة [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

يحصل على بيانات تنسيق ثلاثية الأبعاد الفعّالة مع تطبيق الوراثة.

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

**الإرجاع:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).