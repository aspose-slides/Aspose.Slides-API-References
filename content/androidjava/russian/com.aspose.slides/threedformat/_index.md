---
title: ThreeDFormat
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет 3-D свойства.
type: docs
url: /ru/com.aspose.slides/threedformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

Представляет 3-D свойства.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Создайте экземпляр класса Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Добавьте фигуру, используя метод AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Определите TextFrame и его свойства.
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Определите свойства ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Сохраните файл Presentation.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Создайте экземпляр класса Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Добавьте фигуру, используя метод AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Определите TextFrame и его свойства.
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Настройте FillFormat.FillType как FillType.Gradient и определите свойства градиента.
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Определите свойства ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Сохраните файл Presentation.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Создайте экземпляр класса Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Добавьте фигуру, используя метод AddAutoShape.
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Определите TextFrame и его свойства.
>      shape.getTextFrame().setText("3D Text");
>      // Настройте FillFormat.FillType как FillType.NoFill.
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Настройте Portion в TextFrame и свойства PortionFormat.
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // Настройте трансформирующий эффект WordArt "Arch Up".
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Определите свойства ThreeDFormat у ITextFrame.
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Сохраните файл Presentation.
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Возвращает или задает ширину 3D контура. |
| [setContourWidth(double value)](#setContourWidth-double-) | Возвращает или задает ширину 3D контура. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Возвращает или задает высоту эффекта выдавливания. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Возвращает или задает высоту эффекта выдавливания. |
| [getDepth()](#getDepth--) | Возвращает или задает глубину 3D фигуры. |
| [setDepth(double value)](#setDepth-double-) | Возвращает или задает глубину 3D фигуры. |
| [getBevelTop()](#getBevelTop--) | Возвращает или задает тип верхней 3D фаски. |
| [getBevelBottom()](#getBevelBottom--) | Возвращает или задает тип нижней 3D фаски. |
| [getContourColor()](#getContourColor--) | Возвращает или задает цвет контура. |
| [getExtrusionColor()](#getExtrusionColor--) | Возвращает или задает цвет выдавливания. |
| [getCamera()](#getCamera--) | Возвращает или задает настройки камеры. |
| [getLightRig()](#getLightRig--) | Возвращает или задает тип света. |
| [getMaterial()](#getMaterial--) | Возвращает или задает тип материала. |
| [setMaterial(int value)](#setMaterial-int-) | Возвращает или задает тип материала. |
| [getEffective()](#getEffective--) | Получает эффективные данные 3D форматирования с примененным наследованием. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Версия. Только для чтения long.

**Возвращаемое значение:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```


Возвращает или задает ширину 3D контура. Чтение/запись double.

**Возвращаемое значение:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```


Возвращает или задает ширину 3D контура. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```


Возвращает или задает высоту эффекта выдавливания. Чтение/запись double.

**Возвращаемое значение:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```


Возвращает или задает высоту эффекта выдавливания. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```


Возвращает или задает глубину 3D фигуры. Чтение/запись double.

**Возвращаемое значение:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```


Возвращает или задает глубину 3D фигуры. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```


Только для чтения [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Возвращаемое значение:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```


Только для чтения [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Возвращаемое значение:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```


Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```


Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```


Только для чтения [ICamera](../../com.aspose.slides/icamera).

**Возвращаемое значение:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```


Только для чтения [ILightRig](../../com.aspose.slides/ilightrig).

**Возвращаемое значение:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```


Возвращает или задает тип материала. Чтение/запись [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Возвращаемое значение:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```


Возвращает или задает тип материала. Чтение/запись [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```


Получает эффективные данные 3D форматирования с примененным наследованием.

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


**Возвращаемое значение:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - Объект [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).