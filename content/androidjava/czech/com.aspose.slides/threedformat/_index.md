---
title: ThreeDFormat
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Reprezentuje 3-D vlastnosti.
type: docs
url: /cs/com.aspose.slides/threedformat/
---
**Dědičnost:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**  
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)  
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

Representuje 3-D vlastnosti.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Vytvořte instanci třídy Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Přidejte tvar pomocí metody AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Definujte TextFrame a jeho vlastnosti.
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Definujte vlastnosti ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Uložte soubor Presentation.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Vytvořte instanci třídy Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Přidejte tvar pomocí metody AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definujte TextFrame a jeho vlastnosti.
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Nastavte FillFormat.FillType na FillType.Gradient a definujte vlastnosti gradientu.
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Definujte vlastnosti ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Uložte soubor Presentation.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Vytvořte instanci třídy Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Přidejte tvar pomocí metody AddAutoShape.
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Definujte TextFrame a jeho vlastnosti.
>      shape.getTextFrame().setText("3D Text");
>      // Nastavte FillFormat.FillType na FillType.NoFill.
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Nakonfigurujte část TextFrame a nastavte vlastnosti PortionFormat.
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // nastaven \"Arch Up\" WordArt transform effect
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Definujte vlastnosti ThreeDFormat pro ITextFrame.
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Uložte soubor Presentation.
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metody

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Vrací nebo nastavuje šířku 3-D kontury. |
| [setContourWidth(double value)](#setContourWidth-double-) | Vrací nebo nastavuje šířku 3-D kontury. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Vrací nebo nastavuje výšku efektu extruze. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Vrací nebo nastavuje výšku efektu extruze. |
| [getDepth()](#getDepth--) | Vrací nebo nastavuje hloubku 3-D tvaru. |
| [setDepth(double value)](#setDepth-double-) | Vrací nebo nastavuje hloubku 3-D tvaru. |
| [getBevelTop()](#getBevelTop--) | Vrací nebo nastavuje typ horního 3-D zkosení. |
| [getBevelBottom()](#getBevelBottom--) | Vrací nebo nastavuje typ spodního 3-D zkosení. |
| [getContourColor()](#getContourColor--) | Vrací nebo nastavuje barvu kontury. |
| [getExtrusionColor()](#getExtrusionColor--) | Vrací nebo nastavuje barvu extruze. |
| [getCamera()](#getCamera--) | Vrací nebo nastavuje nastavení kamery. |
| [getLightRig()](#getLightRig--) | Vrací nebo nastavuje typ osvětlení. |
| [getMaterial()](#getMaterial--) | Vrací nebo nastavuje typ materiálu. |
| [setMaterial(int value)](#setMaterial-int-) | Vrací nebo nastavuje typ materiálu. |
| [getEffective()](#getEffective--) | Získává efektivní data formátování 3-D s aplikovanou dědičností. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**  
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

Vrací nebo nastavuje šířku 3-D kontury. Číst/Zapisovat double.

**Vrací:**  
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

Vrací nebo nastavuje šířku 3-D kontury. Číst/Zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

Vrací nebo nastavuje výšku efektu extruze. Číst/Zapisovat double.

**Vrací:**  
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

Vrací nebo nastavuje výšku efektu extruze. Číst/Zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public final double getDepth()
```

Vrací nebo nastavuje hloubku 3-D tvaru. Číst/Zapisovat double.

**Vrací:**  
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

Vrací nebo nastavuje hloubku 3-D tvaru. Číst/Zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

Vrací nebo nastavuje typ horního 3-D zkosení. Pouze pro čtení [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Vrací:**  
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

Vrací nebo nastavuje typ spodního 3-D zkosení. Pouze pro čtení [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Vrací:**  
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

Vrací nebo nastavuje barvu kontury. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

Vrací nebo nastavuje barvu extruze. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

Vrací nebo nastavuje nastavení kamery. Pouze pro čtení [ICamera](../../com.aspose.slides/icamera).

**Vrací:**  
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

Vrací nebo nastavuje typ osvětlení. Pouze pro čtení [ILightRig](../../com.aspose.slides/ilightrig).

**Vrací:**  
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

Vrací nebo nastavuje typ materiálu. Číst/Zapisovat [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Vrací:**  
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

Vrací nebo nastavuje typ materiálu. Číst/Zapisovat [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

Získává efektivní data formátování 3-D s aplikovanou dědičností.

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


**Vrací:**  
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).