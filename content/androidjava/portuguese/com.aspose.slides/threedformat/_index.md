---
title: ThreeDFormat
second_title: Aspose.Slides para Android via Java API Reference
description: Representa propriedades 3-D.
type: docs
url: /pt/com.aspose.slides/threedformat/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

Representa propriedades 3-D.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Crie uma instância da classe Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Adicione uma forma usando o método AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Defina o TextFrame e suas propriedades.
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Defina as propriedades ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Salve o arquivo Presentation.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Crie uma instância da classe Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Adicione uma forma usando o método AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Defina o TextFrame e suas propriedades.
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Configure FillFormat.FillType como FillType.Gradient e defina as propriedades do gradiente.
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Defina as propriedades ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Salve o arquivo Presentation.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Crie uma instância da classe Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Adicione uma forma usando o método AddAutoShape.
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Defina o TextFrame e suas propriedades.
>      shape.getTextFrame().setText("3D Text");
>      // Configure FillFormat.FillType como FillType.NoFill.
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Configure a porção do TextFrame e configure as propriedades de PortionFormat.
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // configure o efeito de transformação WordArt "Arch Up".
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Defina as propriedades ThreeDFormat de ITextFrame.
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Salve o arquivo Presentation.
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Retorna ou define a largura de um contorno 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Retorna ou define a largura de um contorno 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Retorna ou define a altura de um efeito de extrusão. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Retorna ou define a altura de um efeito de extrusão. |
| [getDepth()](#getDepth--) | Retorna ou define a profundidade de uma forma 3D. |
| [setDepth(double value)](#setDepth-double-) | Retorna ou define a profundidade de uma forma 3D. |
| [getBevelTop()](#getBevelTop--) | Retorna ou define o tipo de bisel superior 3D. |
| [getBevelBottom()](#getBevelBottom--) | Retorna ou define o tipo de bisel inferior 3D. |
| [getContourColor()](#getContourColor--) | Retorna ou define a cor de um contorno. |
| [getExtrusionColor()](#getExtrusionColor--) | Retorna ou define a cor de uma extrusão. |
| [getCamera()](#getCamera--) | Retorna ou define as configurações de uma câmera. |
| [getLightRig()](#getLightRig--) | Retorna ou define o tipo de luz. |
| [getMaterial()](#getMaterial--) | Retorna ou define o tipo de material. |
| [setMaterial(int value)](#setMaterial-int-) | Retorna ou define o tipo de material. |
| [getEffective()](#getEffective--) | Obtém dados de formatação 3-D efetivos com a herança aplicada. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long

### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

Retorna ou define a largura de um contorno 3D. Leitura/gravação double.

**Retorna:**
double

### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

Retorna ou define a largura de um contorno 3D. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

Retorna ou define a altura de um efeito de extrusão. Leitura/gravação double.

**Retorna:**
double

### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

Retorna ou define a altura de um efeito de extrusão. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```

Retorna ou define a profundidade de uma forma 3D. Leitura/gravação double.

**Retorna:**
double

### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

Retorna ou define a profundidade de uma forma 3D. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

Retorna ou define o tipo de bisel superior 3D. Somente leitura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retorna:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

Retorna ou define o tipo de bisel inferior 3D. Somente leitura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retorna:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

Retorna ou define a cor de um contorno. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

Retorna ou define a cor de uma extrusão. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

Retorna ou define as configurações de uma câmera. Somente leitura [ICamera](../../com.aspose.slides/icamera).

**Retorna:**
[ICamera](../../com.aspose.slides/icamera)

### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

Retorna ou define o tipo de luz. Somente leitura [ILightRig](../../com.aspose.slides/ilightrig).

**Retorna:**
[ILightRig](../../com.aspose.slides/ilightrig)

### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

Retorna ou define o tipo de material. Leitura/gravação [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Retorna:**
int

### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

Retorna ou define o tipo de material. Leitura/gravação [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

Obtém dados de formatação 3-D efetivos com a herança aplicada.

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


**Retorna:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - Um [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).