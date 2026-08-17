---
title: ThreeDFormat
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les propriétés 3D.
type: docs
url: /fr/com.aspose.slides/threedformat/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

Représente les propriétés 3D.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Créer une instance de la classe Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Ajouter une forme en utilisant la méthode AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Définir le TextFrame et ses propriétés.
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Définir les propriétés ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Enregistrer le fichier Presentation.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Créer une instance de la classe Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Ajouter une forme en utilisant la méthode AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Définir le TextFrame et ses propriétés.
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Configurer FillFormat.FillType comme FillType.Gradient et définir les propriétés du dégradé.
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Définir les propriétés ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Enregistrer le fichier Presentation.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Créer une instance de la classe Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Ajouter une forme en utilisant la méthode AddAutoShape.
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Définir le TextFrame et ses propriétés.
>      shape.getTextFrame().setText("3D Text");
>      // Configurer FillFormat.FillType comme FillType.NoFill.
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Configurer la portion du TextFrame et définir les propriétés de PortionFormat.
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // Configurer l'effet de transformation WordArt « Arch Up ».
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Définir les propriétés ThreeDFormat de ITextFrame.
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Enregistrer le fichier Presentation.
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Renvoie ou définit la largeur d'un contour 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Renvoie ou définit la largeur d'un contour 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Renvoie ou définit la hauteur d'un effet d'extrusion. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Renvoie ou définit la hauteur d'un effet d'extrusion. |
| [getDepth()](#getDepth--) | Renvoie ou définit la profondeur d'une forme 3D. |
| [setDepth(double value)](#setDepth-double-) | Renvoie ou définit la profondeur d'une forme 3D. |
| [getBevelTop()](#getBevelTop--) | Renvoie ou définit le type d'un chanfrein 3D supérieur. |
| [getBevelBottom()](#getBevelBottom--) | Renvoie ou définit le type d'un chanfrein 3D inférieur. |
| [getContourColor()](#getContourColor--) | Renvoie ou définit la couleur d'un contour. |
| [getExtrusionColor()](#getExtrusionColor--) | Renvoie ou définit la couleur d'une extrusion. |
| [getCamera()](#getCamera--) | Renvoie ou définit les paramètres d'une caméra. |
| [getLightRig()](#getLightRig--) | Renvoie ou définit le type d'une lumière. |
| [getMaterial()](#getMaterial--) | Renvoie ou définit le type d'un matériau. |
| [setMaterial(int value)](#setMaterial-int-) | Renvoie ou définit le type d'un matériau. |
| [getEffective()](#getEffective--) | Obtient les données de formatage 3D effectives avec l'héritage appliqué. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

Renvoie ou définit la largeur d'un contour 3D. Lecture/écriture double.

**Renvoie:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

Renvoie ou définit la largeur d'un contour 3D. Lecture/écriture double.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

Renvoie ou définit la hauteur d'un effet d'extrusion. Lecture/écriture double.

**Renvoie:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

Renvoie ou définit la hauteur d'un effet d'extrusion. Lecture/écriture double.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```

Renvoie ou définit la profondeur d'une forme 3D. Lecture/écriture double.

**Renvoie:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

Renvoie ou définit la profondeur d'une forme 3D. Lecture/écriture double.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

Renvoie ou définit le type d'un chanfrein 3D supérieur. Lecture seule [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Renvoie:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

Renvoie ou définit le type d'un chanfrein 3D inférieur. Lecture seule [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Renvoie:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

Renvoie ou définit la couleur d'un contour. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

Renvoie ou définit la couleur d'une extrusion. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

Renvoie ou définit les paramètres d'une caméra. Lecture seule [ICamera](../../com.aspose.slides/icamera).

**Renvoie:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

Renvoie ou définit le type d'une lumière. Lecture seule [ILightRig](../../com.aspose.slides/ilightrig).

**Renvoie:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

Renvoie ou définit le type d'un matériau. Lecture/écriture [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Renvoie:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

Renvoie ou définit le type d'un matériau. Lecture/écriture [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

Obtient les données de formatage 3D effectives avec l'héritage appliqué.

--------------------

> ```
> Cet exemple montre comment obtenir les propriétés effectives pour la caméra, le système d'éclairage et le chanfrein supérieur de la forme.
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


**Renvoie:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - Un [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).