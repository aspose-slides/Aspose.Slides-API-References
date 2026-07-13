---
title: ThreeDFormat
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili properti 3-D.
type: docs
url: /id/com.aspose.slides/threedformat/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

Mewakili properti 3D.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Buat instance kelas Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Tambahkan bentuk menggunakan metode AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Definisikan TextFrame dan propertinya.
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Definisikan properti ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Simpan file Presentation.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Buat instance kelas Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Tambahkan bentuk menggunakan metode AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definisikan TextFrame dan propertinya.
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Konfigurasikan FillFormat.FillType menjadi FillType.Gradient dan definisikan properti gradien.
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Definisikan properti ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Simpan file Presentation.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Buat instance kelas Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Tambahkan bentuk menggunakan metode AddAutoShape.
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definisikan TextFrame dan propertinya.
>      shape.getTextFrame().setText("3D Text");
>      // Konfigurasikan FillFormat.FillType menjadi FillType.NoFill.
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Konfigurasikan Portion dari TextFrame dan atur properti PortionFormat.
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // siapkan efek transformasi WordArt "Arch Up".
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Definisikan properti ThreeDFormat dari ITextFrame.
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Simpan file Presentation.
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Mengembalikan atau mengatur lebar kontur 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Mengembalikan atau mengatur lebar kontur 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Mengembalikan atau mengatur tinggi efek ekstrusi. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Mengembalikan atau mengatur tinggi efek ekstrusi. |
| [getDepth()](#getDepth--) | Mengembalikan atau mengatur kedalaman bentuk 3D. |
| [setDepth(double value)](#setDepth-double-) | Mengembalikan atau mengatur kedalaman bentuk 3D. |
| [getBevelTop()](#getBevelTop--) | Mengembalikan atau mengatur tipe bevel 3D atas. |
| [getBevelBottom()](#getBevelBottom--) | Mengembalikan atau mengatur tipe bevel 3D bawah. |
| [getContourColor()](#getContourColor--) | Mengembalikan atau mengatur warna kontur. |
| [getExtrusionColor()](#getExtrusionColor--) | Mengembalikan atau mengatur warna ekstrusi. |
| [getCamera()](#getCamera--) | Mengembalikan atau mengatur pengaturan kamera. |
| [getLightRig()](#getLightRig--) | Mengembalikan atau mengatur tipe cahaya. |
| [getMaterial()](#getMaterial--) | Mengembalikan atau mengatur tipe material. |
| [setMaterial(int value)](#setMaterial-int-) | Mengembalikan atau mengatur tipe material. |
| [getEffective()](#getEffective--) | Mendapatkan data format 3D efektif dengan warisan yang diterapkan. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Baca-saja long.

**Mengembalikan:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

Mengembalikan atau mengatur lebar kontur 3D. Baca/tulis double.

**Mengembalikan:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

Mengembalikan atau mengatur lebar kontur 3D. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

Mengembalikan atau mengatur tinggi efek ekstrusi. Baca/tulis double.

**Mengembalikan:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

Mengembalikan atau mengatur tinggi efek ekstrusi. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public final double getDepth()
```

Mengembalikan atau mengatur kedalaman bentuk 3D. Baca/tulis double.

**Mengembalikan:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

Mengembalikan atau mengatur kedalaman bentuk 3D. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

Mengembalikan atau mengatur tipe bevel 3D atas. Baca-saja [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Mengembalikan:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

Mengembalikan atau mengatur tipe bevel 3D bawah. Baca-saja [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Mengembalikan:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

Mengembalikan atau mengatur warna kontur. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

Mengembalikan atau mengatur warna ekstrusi. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

Mengembalikan atau mengatur pengaturan kamera. Baca-saja [ICamera](../../com.aspose.slides/icamera).

**Mengembalikan:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

Mengembalikan atau mengatur tipe cahaya. Baca-saja [ILightRig](../../com.aspose.slides/ilightrig).

**Mengembalikan:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

Mengembalikan atau mengatur tipe material. Baca/tulis [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Mengembalikan:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

Mengembalikan atau mengatur tipe material. Baca/tulis [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

Mendapatkan data format 3D efektif dengan warisan yang diterapkan.

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

**Mengembalikan:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - Sebuah [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).