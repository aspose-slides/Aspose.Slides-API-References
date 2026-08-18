---
title: ThreeDFormat
second_title: Aspose.Slides für Java API Referenz
description: Stellt 3-D-Eigenschaften dar.
type: docs
url: /de/com.aspose.slides/threedformat/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

Stellt 3-D Eigenschaften dar.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Erstelle eine Instanz der Presentation-Klasse.
>  Presentation pres = new Presentation();
>  try {
>      // Füge eine Form mit der Methode AddAutoShape hinzu.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Definiere TextFrame und dessen Eigenschaften
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Definiere ThreeDFormat-Eigenschaften
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Speichere die Präsentationsdatei
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Erstelle eine Instanz der Presentation-Klasse.
>  Presentation pres = new Presentation();
>  try {
>      // Füge eine Form mit der Methode AddAutoShape hinzu.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definiere TextFrame und dessen Eigenschaften
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Konfiguriere FillFormat.FillType als FillType.Gradient und definiere die Gradient-Eigenschaften
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Definiere ThreeDFormat-Eigenschaften
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Speichere die Präsentationsdatei
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Erstelle eine Instanz der Presentation-Klasse.
>  Presentation pres = new Presentation();
>  try {
>      // Füge eine Form mit der Methode AddAutoShape hinzu.
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definiere TextFrame und dessen Eigenschaften
>      shape.getTextFrame().setText("3D Text");
>      // Konfiguriere FillFormat.FillType als FillType.NoFill
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Konfiguriere Portion des TextFrames und die Eigenschaften von PortionFormat
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // Richte den WordArt-Transformations-Effekt "Arch Up" ein.
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Definiere ThreeDFormat-Eigenschaften von ITextFrame
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Speichere die Präsentationsdatei
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Liest oder setzt die Breite eines 3D-Konturs. |
| [setContourWidth(double value)](#setContourWidth-double-) | Liest oder setzt die Breite eines 3D-Konturs. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Liest oder setzt die Höhe eines Extrusionseffekts. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Liest oder setzt die Höhe eines Extrusionseffekts. |
| [getDepth()](#getDepth--) | Liest oder setzt die Tiefe einer 3D-Form. |
| [setDepth(double value)](#setDepth-double-) | Liest oder setzt die Tiefe einer 3D-Form. |
| [getBevelTop()](#getBevelTop--) | Liest oder setzt den Typ einer oberen 3D-Fase. |
| [getBevelBottom()](#getBevelBottom--) | Liest oder setzt den Typ einer unteren 3D-Fase. |
| [getContourColor()](#getContourColor--) | Liest oder setzt die Farbe eines Konturs. |
| [getExtrusionColor()](#getExtrusionColor--) | Liest oder setzt die Farbe einer Extrusion. |
| [getCamera()](#getCamera--) | Liest oder setzt die Einstellungen einer Kamera. |
| [getLightRig()](#getLightRig--) | Liest oder setzt den Typ eines Lichts. |
| [getMaterial()](#getMaterial--) | Liest oder setzt den Typ eines Materials. |
| [setMaterial(int value)](#setMaterial-int-) | Liest oder setzt den Typ eines Materials. |
| [getEffective()](#getEffective--) | Liest wirksame 3-D-Formatierungsdaten mit angewandter Vererbung. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur lesbar long.

**Rückgabewert:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```


Liest oder setzt die Breite eines 3D-Konturs. Lesen/Schreiben double.

**Rückgabewert:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```


Liest oder setzt die Breite eines 3D-Konturs. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```


Liest oder setzt die Höhe eines Extrusionseffekts. Lesen/Schreiben double.

**Rückgabewert:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```


Liest oder setzt die Höhe eines Extrusionseffekts. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public final double getDepth()
```


Liest oder setzt die Tiefe einer 3D-Form. Lesen/Schreiben double.

**Rückgabewert:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```


Liest oder setzt die Tiefe einer 3D-Form. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```


Liest oder setzt den Typ einer oberen 3D-Fase. Nur lesbar [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Rückgabewert:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```


Liest oder setzt den Typ einer unteren 3D-Fase. Nur lesbar [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Rückgabewert:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```


Liest oder setzt die Farbe eines Konturs. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```


Liest oder setzt die Farbe einer Extrusion. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```


Liest oder setzt die Einstellungen einer Kamera. Nur lesbar [ICamera](../../com.aspose.slides/icamera).

**Rückgabewert:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```


Liest oder setzt den Typ eines Lichts. Nur lesbar [ILightRig](../../com.aspose.slides/ilightrig).

**Rückgabewert:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```


Liest oder setzt den Typ eines Materials. Lesen/Schreiben [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Rückgabewert:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```


Liest oder setzt den Typ eines Materials. Lesen/Schreiben [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```


Liest wirksame 3-D-Formatierungsdaten mit angewandter Vererbung.

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

**Rückgabewert:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).