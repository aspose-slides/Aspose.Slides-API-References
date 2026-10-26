---
title: ThreeDFormat
second_title: Riferimento API Aspose.Slides per Android via Java
description: Rappresenta le proprietà 3-D.
type: docs
url: /it/com.aspose.slides/threedformat/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

Rappresenta le proprietà 3-D.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Create an instance of Presentation class.
>  Presentation pres = new Presentation();
>  try {
>      // Add a shape using AddAutoShape method
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Define TextFrame and its properties
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Define ThreeDFormat Properties
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Save the Presentation file
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Create an instance of Presentation class.
>  Presentation pres = new Presentation();
>  try {
>      // Add a shape using AddAutoShape method
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Define TextFrame and its properties
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Configure FillFormat.FillType as FillType.Gradient and define gradient properties
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Define ThreeDFormat Properties
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Save the Presentation file
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Create an instance of Presentation class.
>  Presentation pres = new Presentation();
>  try {
>      // Add a shape using AddAutoShape method
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Define TextFrame and its properties
>      shape.getTextFrame().setText("3D Text");
>      // Configure FillFormat.FillType as FillType.NoFill
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Configure Portion of TextFrame and configure properties of PortionFormat
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // setup "Arch Up" WordArt transform effect
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Define ThreeDFormat Properties of ITextFrame
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Save the Presentation file
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Restituisce o imposta la larghezza di un contorno 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Restituisce o imposta la larghezza di un contorno 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Restituisce o imposta l'altezza di un effetto di estrusione. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Restituisce o imposta l'altezza di un effetto di estrusione. |
| [getDepth()](#getDepth--) | Restituisce o imposta la profondità di una forma 3D. |
| [setDepth(double value)](#setDepth-double-) | Restituisce o imposta la profondità di una forma 3D. |
| [getBevelTop()](#getBevelTop--) | Restituisce o imposta il tipo di una smussatura 3D superiore. |
| [getBevelBottom()](#getBevelBottom--) | Restituisce o imposta il tipo di una smussatura 3D inferiore. |
| [getContourColor()](#getContourColor--) | Restituisce o imposta il colore di un contorno. |
| [getExtrusionColor()](#getExtrusionColor--) | Restituisce o imposta il colore di un'estrusione. |
| [getCamera()](#getCamera--) | Restituisce o imposta le impostazioni di una fotocamera. |
| [getLightRig()](#getLightRig--) | Restituisce o imposta il tipo di una luce. |
| [getMaterial()](#getMaterial--) | Restituisce o imposta il tipo di un materiale. |
| [setMaterial(int value)](#setMaterial-int-) | Restituisce o imposta il tipo di un materiale. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione 3-D efficaci con l'ereditarietà applicata. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Solo lettura long.

**Restituisce:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

Restituisce o imposta la larghezza di un contorno 3D. Lettura/scrittura double.

**Restituisce:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

Restituisce o imposta la larghezza di un contorno 3D. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

Restituisce o imposta l'altezza di un effetto di estrusione. Lettura/scrittura double.

**Restituisce:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

Restituisce o imposta l'altezza di un effetto di estrusione. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```

Restituisce o imposta la profondità di una forma 3D. Lettura/scrittura double.

**Restituisce:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

Restituisce o imposta la profondità di una forma 3D. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

Restituisce o imposta il tipo di una smussatura 3D superiore. Solo lettura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Restituisce:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

Restituisce o imposta il tipo di una smussatura 3D inferiore. Solo lettura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Restituisce:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

Restituisce o imposta il colore di un contorno. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

Restituisce o imposta il colore di un'estrusione. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

Restituisce o imposta le impostazioni di una fotocamera. Solo lettura [ICamera](../../com.aspose.slides/icamera).

**Restituisce:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

Restituisce o imposta il tipo di una luce. Solo lettura [ILightRig](../../com.aspose.slides/ilightrig).

**Restituisce:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

Restituisce o imposta il tipo di un materiale. Lettura/scrittura [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Restituisce:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

Restituisce o imposta il tipo di un materiale. Lettura/scrittura [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

Ottiene i dati di formattazione 3-D efficaci con l'ereditarietà applicata.

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

**Restituisce:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).