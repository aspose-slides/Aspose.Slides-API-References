---
title: ThreeDFormat
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa propiedades 3-D.
type: docs
url: /es/com.aspose.slides/threedformat/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

Representa propiedades 3-D.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Cree una instancia de la clase Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Agregue una forma usando el método AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Defina TextFrame y sus propiedades.
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Defina las propiedades de ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Guarde el archivo de la presentación.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Cree una instancia de la clase Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Agregue una forma usando el método AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Defina TextFrame y sus propiedades.
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Configure FillFormat.FillType como FillType.Gradient y defina las propiedades del degradado.
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Defina las propiedades de ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Guarde el archivo de la presentación.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Cree una instancia de la clase Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Agregue una forma usando el método AddAutoShape.
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Defina TextFrame y sus propiedades.
>      shape.getTextFrame().setText("3D Text");
>      // Configure FillFormat.FillType como FillType.NoFill.
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Configure la porción de TextFrame y configure las propiedades de PortionFormat.
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // configure el efecto de transformación WordArt "Arch Up".
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Defina las propiedades de ThreeDFormat de ITextFrame.
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Guarde el archivo de la presentación.
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Devuelve o establece el ancho de un contorno 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Devuelve o establece el ancho de un contorno 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Devuelve o establece la altura de un efecto de extrusión. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Devuelve o establece la altura de un efecto de extrusión. |
| [getDepth()](#getDepth--) | Devuelve o establece la profundidad de una forma 3D. |
| [setDepth(double value)](#setDepth-double-) | Devuelve o establece la profundidad de una forma 3D. |
| [getBevelTop()](#getBevelTop--) | Devuelve o establece el tipo de bisel superior 3D. |
| [getBevelBottom()](#getBevelBottom--) | Devuelve o establece el tipo de bisel inferior 3D. |
| [getContourColor()](#getContourColor--) | Devuelve o establece el color de un contorno. |
| [getExtrusionColor()](#getExtrusionColor--) | Devuelve o establece el color de una extrusión. |
| [getCamera()](#getCamera--) | Devuelve o establece la configuración de una cámara. |
| [getLightRig()](#getLightRig--) | Devuelve o establece el tipo de una luz. |
| [getMaterial()](#getMaterial--) | Devuelve o establece el tipo de un material. |
| [setMaterial(int value)](#setMaterial-int-) | Devuelve o establece el tipo de un material. |
| [getEffective()](#getEffective--) | Obtiene los datos de formato 3D efectivos con la herencia aplicada. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

Devuelve o establece el ancho de un contorno 3D. Lectura/escritura double.

**Devuelve:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

Devuelve o establece el ancho de un contorno 3D. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

Devuelve o establece la altura de un efecto de extrusión. Lectura/escritura double.

**Devuelve:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

Devuelve o establece la altura de un efecto de extrusión. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```

Devuelve o establece la profundidad de una forma 3D. Lectura/escritura double.

**Devuelve:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

Devuelve o establece la profundidad de una forma 3D. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

Devuelve o establece el tipo de bisel superior 3D. Solo lectura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Devuelve:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

Devuelve o establece el tipo de bisel inferior 3D. Solo lectura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Devuelve:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

Devuelve o establece el color de un contorno. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

Devuelve o establece el color de una extrusión. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

Devuelve o establece la configuración de una cámara. Solo lectura [ICamera](../../com.aspose.slides/icamera).

**Devuelve:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

Devuelve o establece el tipo de una luz. Solo lectura [ILightRig](../../com.aspose.slides/ilightrig).

**Devuelve:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

Devuelve o establece el tipo de un material. Lectura/escritura [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Devuelve:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

Devuelve o establece el tipo de un material. Lectura/escritura [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

Obtiene los datos de formato 3D efectivos con la herencia aplicada.

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

**Devuelve:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - Un [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).