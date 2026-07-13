---
title: ThreeDFormat
second_title: Aspose.Slides dla Androida - dokumentacja Java API
description: Reprezentuje właściwości 3-D.
type: docs
url: /pl/com.aspose.slides/threedformat/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

Reprezentuje właściwości 3-D.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Utwórz instancję klasy Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Dodaj kształt przy użyciu metody AddAutoShape method
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Zdefiniuj TextFrame i jego właściwości
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Zdefiniuj właściwości ThreeDFormat
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Zapisz plik Presentation
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Utwórz instancję klasy Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Dodaj kształt przy użyciu metody AddAutoShape method
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Zdefiniuj TextFrame i jego właściwości
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Skonfiguruj FillFormat.FillType jako FillType.Gradient i zdefiniuj właściwości gradientu
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Zdefiniuj właściwości ThreeDFormat
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Zapisz plik Presentation
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Utwórz instancję klasy Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Dodaj kształt przy użyciu metody AddAutoShape method
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Zdefiniuj TextFrame i jego właściwości
>      shape.getTextFrame().setText("3D Text");
>      // Skonfiguruj FillFormat.FillType jako FillType.NoFill
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Skonfiguruj Portion w TextFrame i ustaw właściwości PortionFormat
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // ustaw efekt transformacji WordArt "Arch Up"
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Zdefiniuj właściwości ThreeDFormat dla ITextFrame
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Zapisz plik Presentation
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Zwraca lub ustawia szerokość obrysu 3D. Odczyt/zapis double. |
| [setContourWidth(double value)](#setContourWidth-double-) | Zwraca lub ustawia szerokość obrysu 3D. Odczyt/zapis double. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Zwraca lub ustawia wysokość efektu ekstruzji. Odczyt/zapis double. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Zwraca lub ustawia wysokość efektu ekstruzji. Odczyt/zapis double. |
| [getDepth()](#getDepth--) | Zwraca lub ustawia głębokość kształtu 3D. Odczyt/zapis double. |
| [setDepth(double value)](#setDepth-double-) | Zwraca lub ustawia głębokość kształtu 3D. Odczyt/zapis double. |
| [getBevelTop()](#getBevelTop--) | Zwraca lub ustawia typ górnego 3D bevel. |
| [getBevelBottom()](#getBevelBottom--) | Zwraca lub ustawia typ dolnego 3D bevel. |
| [getContourColor()](#getContourColor--) | Zwraca lub ustawia kolor obrysu. |
| [getExtrusionColor()](#getExtrusionColor--) | Zwraca lub ustawia kolor ekstruzji. |
| [getCamera()](#getCamera--) | Zwraca lub ustawia ustawienia kamery. |
| [getLightRig()](#getLightRig--) | Zwraca lub ustawia typ światła. |
| [getMaterial()](#getMaterial--) | Zwraca lub ustawia typ materiału. |
| [setMaterial(int value)](#setMaterial-int-) | Zwraca lub ustawia typ materiału. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane formatowania 3-D z zastosowanym dziedziczeniem. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long

### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

Zwraca lub ustawia szerokość obrysu 3D. Odczyt/zapis double.

**Zwraca:**
double

### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

Zwraca lub ustawia szerokość obrysu 3D. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

Zwraca lub ustawia wysokość efektu ekstruzji. Odczyt/zapis double.

**Zwraca:**
double

### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

Zwraca lub ustawia wysokość efektu ekstruzji. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```

Zwraca lub ustawia głębokość kształtu 3D. Odczyt/zapis double.

**Zwraca:**
double

### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

Zwraca lub ustawia głębokość kształtu 3D. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

Zwraca lub ustawia typ górnego 3D bevel. Tylko do odczytu [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Zwraca:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

Zwraca lub ustawia typ dolnego 3D bevel. Tylko do odczytu [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Zwraca:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

Zwraca lub ustawia kolor obrysu. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

Zwraca lub ustawia kolor ekstruzji. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

Zwraca lub ustawia ustawienia kamery. Tylko do odczytu [ICamera](../../com.aspose.slides/icamera).

**Zwraca:**
[ICamera](../../com.aspose.slides/icamera)

### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

Zwraca lub ustawia typ światła. Tylko do odczytu [ILightRig](../../com.aspose.slides/ilightrig).

**Zwraca:**
[ILightRig](../../com.aspose.slides/ilightrig)

### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

Zwraca lub ustawia typ materiału. Odczyt/zapis [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Zwraca:**
int

### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

Zwraca lub ustawia typ materiału. Odczyt/zapis [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

Pobiera efektywne dane formatowania 3-D z zastosowanym dziedziczeniem.

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

**Zwraca:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).