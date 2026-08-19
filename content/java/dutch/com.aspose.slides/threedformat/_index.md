---
title: ThreeDFormat
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt 3-D-eigenschappen.
type: docs
url: /nl/com.aspose.slides/threedformat/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

Representeert 3-D-eigenschappen.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Maak een instantie van de Presentation-klasse.
>  Presentation pres = new Presentation();
>  try {
>      // Voeg een vorm toe met de AddAutoShape-methode.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Definieer TextFrame en de eigenschappen.
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Definieer ThreeDFormat-eigenschappen.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Sla het Presentatiebestand op.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Maak een instantie van de Presentation-klasse.
>  Presentation pres = new Presentation();
>  try {
>      // Voeg een vorm toe met de AddAutoShape-methode.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definieer TextFrame en de eigenschappen.
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Stel FillFormat.FillType in op FillType.Gradient en definieer gradienteigenschappen.
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Definieer ThreeDFormat-eigenschappen.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Sla het Presentatiebestand op.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Maak een instantie van de Presentation-klasse.
>  Presentation pres = new Presentation();
>  try {
>      // Voeg een vorm toe met de AddAutoShape-methode.
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definieer TextFrame en de eigenschappen.
>      shape.getTextFrame().setText("3D Text");
>      // Stel FillFormat.FillType in op FillType.NoFill.
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Configureer een Portie van TextFrame en configureer de eigenschappen van PortionFormat.
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // stel "Arch Up" WordArt-transformatie-effect in.
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Definieer ThreeDFormat-eigenschappen van ITextFrame.
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Sla het Presentatiebestand op.
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Geeft de breedte van een 3D-contour terug of stelt deze in. Lezen/Schrijven double. |
| [setContourWidth(double value)](#setContourWidth-double-) | Geeft de breedte van een 3D-contour terug of stelt deze in. Lezen/Schrijven double. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Geeft de hoogte van een extrusie-effect terug of stelt deze in. Lezen/Schrijven double. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Geeft de hoogte van een extrusie-effect terug of stelt deze in. Lezen/Schrijven double. |
| [getDepth()](#getDepth--) | Geeft de diepte van een 3D-vorm terug of stelt deze in. Lezen/Schrijven double. |
| [setDepth(double value)](#setDepth-double-) | Geeft de diepte van een 3D-vorm terug of stelt deze in. Lezen/Schrijven double. |
| [getBevelTop()](#getBevelTop--) | Geeft het type van een bovenste 3D-afschuining terug of stelt dit in. |
| [getBevelBottom()](#getBevelBottom--) | Geeft het type van een onderste 3D-afschuining terug of stelt dit in. |
| [getContourColor()](#getContourColor--) | Geeft de kleur van een contour terug of stelt deze in. |
| [getExtrusionColor()](#getExtrusionColor--) | Geeft de kleur van een extrusie terug of stelt deze in. |
| [getCamera()](#getCamera--) | Geeft de instellingen van een camera terug of stelt deze in. |
| [getLightRig()](#getLightRig--) | Geeft het type van een licht terug of stelt dit in. |
| [getMaterial()](#getMaterial--) | Geeft het type van een materiaal terug of stelt dit in. |
| [setMaterial(int value)](#setMaterial-int-) | Geeft het type van een materiaal terug of stelt dit in. |
| [getEffective()](#getEffective--) | Haalt effectieve 3-D-opmaakgegevens op met de toegepaste erfenis. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Retour:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```


Geeft de breedte van een 3D-contour terug of stelt deze in. Lezen/Schrijven double.

**Retour:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```


Geeft de breedte van een 3D-contour terug of stelt deze in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```


Geeft de hoogte van een extrusie-effect terug of stelt deze in. Lezen/Schrijven double.

**Retour:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```


Geeft de hoogte van een extrusie-effect terug of stelt deze in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public final double getDepth()
```


Geeft de diepte van een 3D-vorm terug of stelt deze in. Lezen/Schrijven double.

**Retour:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```


Geeft de diepte van een 3D-vorm terug of stelt deze in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```


Geeft het type van een bovenste 3D-afschuining terug of stelt dit in. Alleen-lezen [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retour:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```


Geeft het type van een onderste 3D-afschuining terug of stelt dit in. Alleen-lezen [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retour:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```


Geeft de kleur van een contour terug of stelt deze in. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```


Geeft de kleur van een extrusie terug of stelt deze in. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```


Geeft de instellingen van een camera terug of stelt deze in. Alleen-lezen [ICamera](../../com.aspose.slides/icamera).

**Retour:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```


Geeft het type van een licht terug of stelt dit in. Alleen-lezen [ILightRig](../../com.aspose.slides/ilightrig).

**Retour:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```


Geeft het type van een materiaal terug of stelt dit in. Lezen/Schrijven [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Retour:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```


Geeft het type van een materiaal terug of stelt dit in. Lezen/Schrijven [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```


Haalt effectieve 3-D-opmaakgegevens op met de toegepaste erfenis.

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

**Retour:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - een [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).