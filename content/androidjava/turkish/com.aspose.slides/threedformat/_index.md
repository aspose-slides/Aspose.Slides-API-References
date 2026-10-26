---
title: ThreeDFormat
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: 3-D özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/threedformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

3-D özelliklerini temsil eder.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Presentation sınıfının bir örneğini oluştur.
>  Presentation pres = new Presentation();
>  try {
>      // AddAutoShape yöntemiyle bir şekil ekle
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // TextFrame'i ve özelliklerini tanımla
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // ThreeDFormat özelliklerini tanımla
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Presentation dosyasını kaydet
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Presentation sınıfının bir örneğini oluştur.
>  Presentation pres = new Presentation();
>  try {
>      // AddAutoShape yöntemiyle bir şekil ekle
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // TextFrame'i ve özelliklerini tanımla
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // FillFormat.FillType'ı FillType.Gradient olarak ayarla ve gradient özelliklerini tanımla
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // ThreeDFormat özelliklerini tanımla
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Presentation dosyasını kaydet
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Presentation sınıfının bir örneğini oluştur.
>  Presentation pres = new Presentation();
>  try {
>      // AddAutoShape yöntemiyle bir şekil ekle
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // TextFrame'i ve özelliklerini tanımla
>      shape.getTextFrame().setText("3D Text");
>      // FillFormat.FillType'ı FillType.NoFill olarak ayarla
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // TextFrame'in Portion'ını yapılandır ve PortionFormat özelliklerini ayarla
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // "Arch Up" WordArt dönüşüm etkisini ayarla
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // ITextFrame'in ThreeDFormat özelliklerini tanımla
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Presentation dosyasını kaydet
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | 3D konturun genişliğini döndürür veya ayarlar. |
| [setContourWidth(double value)](#setContourWidth-double-) | 3D konturun genişliğini döndürür veya ayarlar. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Ekstrüzyon etkisinin yüksekliğini döndürür veya ayarlar. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Ekstrüzyon etkisinin yüksekliğini döndürür veya ayarlar. |
| [getDepth()](#getDepth--) | 3D şeklin derinliğini döndürür veya ayarlar. |
| [setDepth(double value)](#setDepth-double-) | 3D şeklin derinliğini döndürür veya ayarlar. |
| [getBevelTop()](#getBevelTop--) | Üst 3D köşe tipini döndürür veya ayarlar. |
| [getBevelBottom()](#getBevelBottom--) | Alt 3D köşe tipini döndürür veya ayarlar. |
| [getContourColor()](#getContourColor--) | Konturun rengini döndürür veya ayarlar. |
| [getExtrusionColor()](#getExtrusionColor--) | Ekstrüzyonun rengini döndürür veya ayarlar. |
| [getCamera()](#getCamera--) | Kameranın ayarlarını döndürür veya ayarlar. |
| [getLightRig()](#getLightRig--) | Işığın tipini döndürür veya ayarlar. |
| [getMaterial()](#getMaterial--) | Malzemenin tipini döndürür veya ayarlar. |
| [setMaterial(int value)](#setMaterial-int-) | Malzemenin tipini döndürür veya ayarlar. |
| [getEffective()](#getEffective--) | Kalıtım uygulandıktan sonra etkili 3-D biçimlendirme verilerini alır. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Sürüm. Salt-okunur long.

**Döndürür:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```


3D konturun genişliğini döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```


3D konturun genişliğini döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```


Ekstrüzyon etkisinin yüksekliğini döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```


Ekstrüzyon etkisinin yüksekliğini döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public final double getDepth()
```


3D şeklin derinliğini döndürür veya ayarlar. Okunur/yazılır double.

**Döndürür:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```


3D şeklin derinliğini döndürür veya ayarlar. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```


Üst 3D köşe tipini döndürür veya ayarlar. Salt-okunur [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Döndürür:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```


Alt 3D köşe tipini döndürür veya ayarlar. Salt-okunur [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Döndürür:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```


Konturun rengini döndürür veya ayarlar. Salt-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```


Ekstrüzyonun rengini döndürür veya ayarlar. Salt-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```


Kameranın ayarlarını döndürür veya ayarlar. Salt-okunur [ICamera](../../com.aspose.slides/icamera).

**Döndürür:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```


Işığın tipini döndürür veya ayarlar. Salt-okunur [ILightRig](../../com.aspose.slides/ilightrig).

**Döndürür:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```


Malzemenin tipini döndürür veya ayarlar. Okunur/yazılır [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Döndürür:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```


Malzemenin tipini döndürür veya ayarlar. Okunur/yazılır [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```


Kalıtım uygulandıktan sonra etkili 3-D biçimlendirme verilerini alır.

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


**Döndürür:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - Bir [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).