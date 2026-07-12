---
title: ThreeDFormat
second_title: Aspose.Slides Android számára a Java API hivatkozás
description: 3-D tulajdonságokat képvisel.
type: docs
url: /hu/com.aspose.slides/threedformat/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

3-D tulajdonságokat képvisel.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Hozzon létre egy példányt a Presentation osztályból.
>  Presentation pres = new Presentation();
>  try {
>      // Adjunk hozzá egy alakzatot az AddAutoShape metódus segítségével
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Definiálja a TextFrame-et és annak tulajdonságait
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Definiálja a ThreeDFormat tulajdonságait
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Mentse a Presentation fájlt
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Hozzon létre egy példányt a Presentation osztályból.
>  Presentation pres = new Presentation();
>  try {
>      // Adjunk hozzá egy alakzatot az AddAutoShape metódus segítségével
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definiálja a TextFrame-et és annak tulajdonságait
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Állítsa a FillFormat.FillType értékét FillType.Gradient-re, és definiálja a gradient tulajdonságait
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Definiálja a ThreeDFormat tulajdonságait
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Mentse a Presentation fájlt
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Hozzon létre egy példányt a Presentation osztályból.
>  Presentation pres = new Presentation();
>  try {
>      // Adjunk hozzá egy alakzatot az AddAutoShape metódus segítségével
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definiálja a TextFrame-et és annak tulajdonságait
>      shape.getTextFrame().setText("3D Text");
>      // Állítsa a FillFormat.FillType értékét FillType.NoFill-re
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Konfigurálja a TextFrame részét és a PortionFormat tulajdonságait
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // "Arch Up" WordArt transzformációs effektus beállítása
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Definiálja az ITextFrame ThreeDFormat tulajdonságait
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Mentse a Presentation fájlt
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Visszaadja vagy beállítja egy 3D kontúr szélességét. |
| [setContourWidth(double value)](#setContourWidth-double-) | Visszaadja vagy beállítja egy 3D kontúr szélességét. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Visszaadja vagy beállítja egy extrúziós hatás magasságát. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Visszaadja vagy beállítja egy extrúziós hatás magasságát. |
| [getDepth()](#getDepth--) | Visszaadja vagy beállítja egy 3D alak mélységét. |
| [setDepth(double value)](#setDepth-double-) | Visszaadja vagy beállítja egy 3D alak mélységét. |
| [getBevelTop()](#getBevelTop--) | Visszaadja vagy beállítja egy felső 3D levágás típusát. |
| [getBevelBottom()](#getBevelBottom--) | Visszaadja vagy beállítja egy alsó 3D levágás típusát. |
| [getContourColor()](#getContourColor--) | Visszaadja vagy beállítja egy kontúr színét. |
| [getExtrusionColor()](#getExtrusionColor--) | Visszaadja vagy beállítja egy extrúzió színét. |
| [getCamera()](#getCamera--) | Visszaadja vagy beállítja egy kamera beállításait. |
| [getLightRig()](#getLightRig--) | Visszaadja vagy beállítja egy fény típusát. |
| [getMaterial()](#getMaterial--) | Visszaadja vagy beállítja egy anyag típusát. |
| [setMaterial(int value)](#setMaterial-int-) | Visszaadja vagy beállítja egy anyag típusát. |
| [getEffective()](#getEffective--) | Lekéri a hatékony 3-D formázási adatokat az öröklődés alkalmazásával. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszaadja:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

Visszaadja vagy beállítja egy 3D kontúr szélességét. Olvasás/írás double.

**Visszaadja:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

Visszaadja vagy beállítja egy 3D kontúr szélességét. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

Visszaadja vagy beállítja egy extrúziós hatás magasságát. Olvasás/írás double.

**Visszaadja:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

Visszaadja vagy beállítja egy extrúziós hatás magasságát. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public final double getDepth()
```

Visszaadja vagy beállítja egy 3D alak mélységét. Olvasás/írás double.

**Visszaadja:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

Visszaadja vagy beállítja egy 3D alak mélységét. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

Visszaadja vagy beállítja egy felső 3D levágás típusát. Csak olvasható [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Visszaadja:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

Visszaadja vagy beállítja egy alsó 3D levágás típusát. Csak olvasható [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Visszaadja:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

Visszaadja vagy beállítja egy kontúr színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszaadja:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

Visszaadja vagy beállítja egy extrúzió színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszaadja:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

Visszaadja vagy beállítja egy kamera beállításait. Csak olvasható [ICamera](../../com.aspose.slides/icamera).

**Visszaadja:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

Visszaadja vagy beállítja egy fény típusát. Csak olvasható [ILightRig](../../com.aspose.slides/ilightrig).

**Visszaadja:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

Visszaadja vagy beállítja egy anyag típusát. Olvasás/írás [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Visszaadja:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

Visszaadja vagy beállítja egy anyag típusát. Olvasás/írás [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

Lekéri a hatékony 3-D formázási adatokat az öröklődés alkalmazásával.

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

**Visszaadja:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).