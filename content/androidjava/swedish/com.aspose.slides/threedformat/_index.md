---
title: ThreeDFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar 3-D-egenskaper.
type: docs
url: /sv/com.aspose.slides/threedformat/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

Representerar 3-D-egenskaper.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Skapa en instans av Presentation-klassen.
>  Presentation pres = new Presentation();
>  try {
>      // Lägg till en form med metoden AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Definiera TextFrame och dess egenskaper.
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Definiera ThreeDFormat-egenskaper.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Spara presentationsfilen.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Skapa en instans av Presentation-klassen.
>  Presentation pres = new Presentation();
>  try {
>      // Lägg till en form med metoden AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definiera TextFrame och dess egenskaper.
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Konfigurera FillFormat.FillType som FillType.Gradient och definiera gradientegenskaper.
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Definiera ThreeDFormat-egenskaper.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Spara presentationsfilen.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Skapa en instans av Presentation-klassen.
>  Presentation pres = new Presentation();
>  try {
>      // Lägg till en form med metoden AddAutoShape.
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definiera TextFrame och dess egenskaper.
>      shape.getTextFrame().setText("3D Text");
>      // Konfigurera FillFormat.FillType som FillType.NoFill.
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Konfigurera Portion av TextFrame och konfigurer egenskaper för PortionFormat.
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // ställ in "Arch Up" WordArt-transformseffekten.
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Definiera ThreeDFormat-egenskaper för ITextFrame.
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Spara presentationsfilen.
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Returnerar eller anger bredden på en 3D-kontur. |
| [setContourWidth(double value)](#setContourWidth-double-) | Returnerar eller anger bredden på en 3D-kontur. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Returnerar eller anger höjden på en extruderingseffekt. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Returnerar eller anger höjden på en extruderingseffekt. |
| [getDepth()](#getDepth--) | Returnerar eller anger djupet på en 3D-form. |
| [setDepth(double value)](#setDepth-double-) | Returnerar eller anger djupet på en 3D-form. |
| [getBevelTop()](#getBevelTop--) | Returnerar eller anger typen av en topp-3D-fasning. |
| [getBevelBottom()](#getBevelBottom--) | Returnerar eller anger typen av en botten-3D-fasning. |
| [getContourColor()](#getContourColor--) | Returnerar eller anger färgen på en kontur. |
| [getExtrusionColor()](#getExtrusionColor--) | Returnerar eller anger färgen på en extrudering. |
| [getCamera()](#getCamera--) | Returnerar eller anger inställningarna för en kamera. |
| [getLightRig()](#getLightRig--) | Returnerar eller anger typen av ett ljus. |
| [getMaterial()](#getMaterial--) | Returnerar eller anger typen av ett material. |
| [setMaterial(int value)](#setMaterial-int-) | Returnerar eller anger typen av ett material. |
| [getEffective()](#getEffective--) | Hämtar effektiv 3-D-formateringsdata med arv tillämpat. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Läs-endast long.

**Returnerar:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```


Returnerar eller anger bredden på en 3D-kontur. Läs-/skriv double.

**Returnerar:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```


Returnerar eller anger bredden på en 3D-kontur. Läs-/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```


Returnerar eller anger höjden på en extruderingseffekt. Läs-/skriv double.

**Returnerar:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```


Returnerar eller anger höjden på en extruderingseffekt. Läs-/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```


Returnerar eller anger djupet på en 3D-form. Läs-/skriv double.

**Returnerar:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```


Returnerar eller anger djupet på en 3D-form. Läs-/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```


Returnerar eller anger typen av en topp-3D-fasning. Läs-endast [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Returnerar:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```


Returnerar eller anger typen av en botten-3D-fasning. Läs-endast [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Returnerar:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```


Returnerar eller anger färgen på en kontur. Läs-endast [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```


Returnerar eller anger färgen på en extrudering. Läs-endast [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```


Returnerar eller anger inställningarna för en kamera. Läs-endast [ICamera](../../com.aspose.slides/icamera).

**Returnerar:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```


Returnerar eller anger typen av ett ljus. Läs-endast [ILightRig](../../com.aspose.slides/ilightrig).

**Returnerar:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```


Returnerar eller anger typen av ett material. Läs-/skriv [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Returnerar:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```


Returnerar eller anger typen av ett material. Läs-/skriv [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```


Hämtar effektiv 3-D-formateringsdata med arv tillämpat.

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

**Returnerar:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - En [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).