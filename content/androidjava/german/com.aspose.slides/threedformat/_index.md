---
title: ThreeDFormat
second_title: Aspose.Slides für Android über Java API Referenz
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

Stellt 3-D-Eigenschaften dar.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Erstelle eine Instanz der Presentation-Klasse.
>  Presentation pres = new Presentation();
>  try {
>      // Füge eine Form mit der Methode AddAutoShape hinzu
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Definiere TextFrame und seine Eigenschaften
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
>      // Füge eine Form mit der Methode AddAutoShape hinzu
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definiere TextFrame und seine Eigenschaften
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Konfiguriere FillFormat.FillType als FillType.Gradient und definiere Gradient-Eigenschaften
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
>      // Füge eine Form mit der Methode AddAutoShape hinzu
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definiere TextFrame und seine Eigenschaften
>      shape.getTextFrame().setText("3D Text");
>      // Konfiguriere FillFormat.FillType als FillType.NoFill
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Konfiguriere Portion von TextFrame und die Eigenschaften von PortionFormat
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // Richte den WordArt-Transformations-Effekt "Arch Up" ein
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
| [getContourWidth()](#getContourWidth--) | Gibt die Breite eines 3D-Konturs zurück oder legt sie fest. |
| [setContourWidth(double value)](#setContourWidth-double-) | Gibt die Breite eines 3D-Konturs zurück oder legt sie fest. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Gibt die Höhe eines Extrusionseffekts zurück oder legt sie fest. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Gibt die Höhe eines Extrusionseffekts zurück oder legt sie fest. |
| [getDepth()](#getDepth--) | Gibt die Tiefe einer 3D-Form zurück oder legt sie fest. |
| [setDepth(double value)](#setDepth-double-) | Gibt die Tiefe einer 3D-Form zurück oder legt sie fest. |
| [getBevelTop()](#getBevelTop--) | Gibt den Typ einer oberen 3D-Abrundung zurück oder legt ihn fest. |
| [getBevelBottom()](#getBevelBottom--) | Gibt den Typ einer unteren 3D-Abrundung zurück oder legt ihn fest. |
| [getContourColor()](#getContourColor--) | Gibt die Farbe eines Konturs zurück oder legt sie fest. |
| [getExtrusionColor()](#getExtrusionColor--) | Gibt die Farbe einer Extrusion zurück oder legt sie fest. |
| [getCamera()](#getCamera--) | Gibt die Einstellungen einer Kamera zurück oder legt sie fest. |
| [getLightRig()](#getLightRig--) | Gibt den Typ eines Lichts zurück oder legt ihn fest. |
| [getMaterial()](#getMaterial--) | Gibt den Typ eines Materials zurück oder legt ihn fest. |
| [setMaterial(int value)](#setMaterial-int-) | Gibt den Typ eines Materials zurück oder legt ihn fest. |
| [getEffective()](#getEffective--) | Ermittelt effektive 3-D-Formatierungsdaten mit angewandter Vererbung. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur lesbar long.

**Rückgabe:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```


Gibt die Breite eines 3D-Konturs zurück oder legt sie fest. Lese-/Schreibzugriff double.

**Rückgabe:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```


Gibt die Breite eines 3D-Konturs zurück oder legt sie fest. Lese-/Schreibzugriff double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```


Gibt die Höhe eines Extrusionseffekts zurück oder legt sie fest. Lese-/Schreibzugriff double.

**Rückgabe:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```


Gibt die Höhe eines Extrusionseffekts zurück oder legt sie fest. Lese-/Schreibzugriff double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```


Gibt die Tiefe einer 3D-Form zurück oder legt sie fest. Lese-/Schreibzugriff double.

**Rückgabe:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```


Gibt die Tiefe einer 3D-Form zurück oder legt sie fest. Lese-/Schreibzugriff double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```


Gibt den Typ einer oberen 3D-Abrundung zurück oder legt ihn fest. Nur lesbar [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Rückgabe:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```


Gibt den Typ einer unteren 3D-Abrundung zurück oder legt ihn fest. Nur lesbar [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Rückgabe:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```


Gibt die Farbe eines Konturs zurück oder legt sie fest. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```


Gibt die Farbe einer Extrusion zurück oder legt sie fest. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```


Gibt die Einstellungen einer Kamera zurück oder legt sie fest. Nur lesbar [ICamera](../../com.aspose.slides/icamera).

**Rückgabe:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```


Gibt den Typ eines Lichts zurück oder legt ihn fest. Nur lesbar [ILightRig](../../com.aspose.slides/ilightrig).

**Rückgabe:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```


Gibt den Typ eines Materials zurück oder legt ihn fest. Lese-/Schreibzugriff [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Rückgabe:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```


Gibt den Typ eines Materials zurück oder legt ihn fest. Lese-/Schreibzugriff [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```


Ermittelt effektive 3-D-Formatierungsdaten mit angewandter Vererbung.

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


**Rückgabe:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).