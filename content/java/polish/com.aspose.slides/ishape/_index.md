---
title: IShape
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje kształt na slajdzie.
type: docs
url: /pl/com.aspose.slides/ishape/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Reprezentuje kształt na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Determines whether the shape is TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Returns the placeholder for a shape. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [removePlaceholder()](#removePlaceholder--) | Defines that this shape isn't a placeholder. |
| [getCustomData()](#getCustomData--) | Returns the shape's custom data. |
| [getRawFrame()](#getRawFrame--) | Returns or sets the raw shape frame's properties. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Returns or sets the raw shape frame's properties. |
| [getFrame()](#getFrame--) | Returns or sets the shape frame's properties. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Returns or sets the shape frame's properties. |
| [getLineFormat()](#getLineFormat--) | Returns the LineFormat object that contains line formatting properties for a shape. |
| [getThreeDFormat()](#getThreeDFormat--) | Returns the ThreeDFormat object that contains line formatting properties for a shape. |
| [getEffectFormat()](#getEffectFormat--) | Returns the EffectFormat object which contains pixel effects applied to a shape. |
| [getFillFormat()](#getFillFormat--) | Returns the FillFormat object that contains fill formatting properties for a shape. |
| [getImage()](#getImage--) | Returns shape thumbnail. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Returns shape thumbnail. |
| [getHidden()](#getHidden--) | Determines whether the shape is hidden. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determines whether the shape is hidden. |
| [getZOrderPosition()](#getZOrderPosition--) | Returns the position of a shape in the z-order. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Returns the number of connection sites on the shape. |
| [getRotation()](#getRotation--) | Returns or sets the number of degrees the specified shape is rotated around the z-axis. |
| [setRotation(float value)](#setRotation-float-) | Returns or sets the number of degrees the specified shape is rotated around the z-axis. |
| [getX()](#getX--) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. |
| [setX(float value)](#setX-float-) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. |
| [getY()](#getY--) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. |
| [setY(float value)](#setY-float-) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. |
| [getWidth()](#getWidth--) | Gets or sets the width of the shape, measured in points. |
| [setWidth(float value)](#setWidth-float-) | Gets or sets the width of the shape, measured in points. |
| [getHeight()](#getHeight--) | Gets or sets the height of the shape, measured in points. |
| [setHeight(float value)](#setHeight-float-) | Gets or sets the height of the shape, measured in points. |
| [getAlternativeText()](#getAlternativeText--) | Returns or sets the alternative text associated with a shape. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Returns or sets the alternative text associated with a shape. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Returns or sets the title of alternative text associated with a shape. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Returns or sets the title of alternative text associated with a shape. |
| [getName()](#getName--) | Returns or sets the name of a shape. |
| [setName(String value)](#setName-java.lang.String-) | Returns or sets the name of a shape. |
| [isDecorative()](#isDecorative--) | Gets or sets 'Mark as decorative' option Reed/write boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Gets or sets 'Mark as decorative' option Reed/write boolean. |
| [getShapeLock()](#getShapeLock--) | Returns shape's locks. |
| [getUniqueId()](#getUniqueId--) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. |
| [isGrouped()](#isGrouped--) | Determines whether the shape is grouped. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Property specifies how a shape will render in black-and-white display mode.. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Property specifies how a shape will render in black-and-white display mode.. |
| [getParentGroup()](#getParentGroup--) | Returns parent GroupShape object if shape is grouped. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Saves content of Shape as SVG file. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Saves content of Shape as SVG file. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). |
### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Określa, czy kształt jest TextHolder. **Tylko do odczytu** boolean.

**Zwraca:**
boolean
### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Zwraca placeholder dla kształtu. **Tylko do odczytu** [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Zwraca:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)
### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder, z którego kopiowana jest zawartość. |

**Zwraca:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New [IPlaceholder](../../com.aspose.slides/iplaceholder).
### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Definiuje, że ten kształt nie jest placeholderem.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Zwraca własne dane kształtu. **Tylko do odczytu** [ICustomData](../../com.aspose.slides/icustomdata).

**Zwraca:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Zwraca lub ustawia właściwości surowej ramki kształtu. **Odczyt/zapis** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //lub
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Taki kod może prowadzić do niejasnych sytuacji. Dlatego dodano ograniczenia dotyczące używania nieokreślonych wartości w IShape.getFrame(). Wartości x, y, width, height, flipH, flipV i rotationAngle muszą być określone (nie Float.NaN ani NullableBool.NotDefined). Powyższy przykład kodu teraz rzuca wyjątek ArgumentException.
>  //Dotyczy to następujących przypadków użycia:
>  IShape shape = ...;
>  shape.setFrame(...); // nie może być nieokreślone
>  IShapeCollection shapes = ...;
>  // parametry x, y, width, height nie mogą być Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // kształt jest powiązany z placeholderem
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // teraz kształt dziedziczy wartości x, y, height, flipH, flipV z placeholdera i nadpisuje width=100 oraz rotationAngle=0.
> ```


**Zwraca:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Zwraca lub ustawia właściwości surowej ramki kształtu. **Odczyt/zapis** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //lub
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Taki kod może prowadzić do niejasnych sytuacji. Dlatego wprowadzono ograniczenia dotyczące używania nieokreślonych wartości w IShape.getFrame(). Wartości x, y, width, height, flipH, flipV i rotationAngle muszą być określone (nie Float.NaN ani NullableBool.NotDefined). Powyższy przykład kodu teraz wyrzuca wyjątek ArgumentException.
>  //Dotyczy to następujących przypadków użycia:
>  IShape shape = ...;
>  shape.setFrame(...); // nie może być nieokreślone
>  IShapeCollection shapes = ...;
>  // parametry x, y, width, height nie mogą być Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // kształt jest powiązany z placeholderem
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // teraz kształt dziedziczy wartości x, y, height, flipH, flipV z placeholdera i nadpisuje width=100 oraz rotationAngle=0.
```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Zwraca lub ustawia właściwości ramki kształtu. **Odczyt/zapis** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Wartość każdej właściwości zwróconej instancji IShapeFrame nie jest niezdefiniowana (nie jest NaN ani NotDefined). Wartość każdej właściwości przypisanej instancji IShapeFrame musi być zdefiniowana (nie NaN ani NotDefined). Można ustawiać niezdefiniowane wartości dla właściwości instancji RawFrame.

**Zwraca:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Zwraca lub ustawia właściwości ramki kształtu. **Odczyt/zapis** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Wartość każdej właściwości zwróconej instancji IShapeFrame nie jest niezdefiniowana (nie jest NaN ani NotDefined). Wartość każdej właściwości przypisanej instancji IShapeFrame musi być zdefiniowana (nie NaN ani NotDefined). Można ustawiać niezdefiniowane wartości dla właściwości instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu. **Tylko do odczytu** [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Zwraca obiekt ThreeDFormat zawierający właściwości formatowania linii dla kształtu. **Tylko do odczytu** [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Zwraca:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu. **Tylko do odczytu** [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Zwraca:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu. **Tylko do odczytu** [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Zwraca miniaturę kształtu. Domyślnie używany jest typ ShapeThumbnailBounds.Shape.

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Zwraca miniaturę kształtu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| bounds | int | Typ granic miniatury kształtu. |
| scaleX | float | Skala X |
| scaleY | float | Skala Y |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail albo null, gdy użyto ShapeThumbnailBounds.Appearance i kształt nie ma widocznych elementów.
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Określa, czy kształt jest ukryty. **Odczyt/zapis** boolean.

**Zwraca:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Określa, czy kształt jest ukryty. **Odczyt/zapis** boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Zwraca pozycję kształtu w kolejności z-order. Shapes[0] zwraca kształt z tyłu, a Shapes[Shapes.Count - 1] zwraca kształt z przodu. **Tylko do odczytu** int.

**Zwraca:**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Zwraca liczbę miejsc połączeń na kształcie. **Tylko do odczytu** int.

**Zwraca:**
int
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna – obrót przeciwny. **Odczyt/zapis** float.

--------------------

Zwracana wartość jest zawsze zdefiniowana (nie jest Float.NaN). Przypisana wartość musi być zdefiniowana (nie Float.NaN). Można ustawiać niezdefiniowane wartości dla właściwości instancji RawFrame.

**Zwraca:**
float
### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna – obrót przeciwny. **Odczyt/zapis** float.

--------------------

Zwracana wartość jest zawsze zdefiniowana (nie jest Float.NaN). Przypisana wartość musi być zdefiniowana (nie Float.NaN). Można ustawiać niezdefiniowane wartości dla właściwości instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. **Odczyt/zapis** float.

--------------------

Zwracana wartość jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Przypisana wartość musi być również zdefiniowana; Float.NaN można przypisać wyłącznie właściwościom instancji RawFrame.

**Zwraca:**
float
### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. **Odczyt/zapis** float.

--------------------

Zwracana wartość jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Przypisana wartość musi być również zdefiniowana; Float.NaN można przypisać wyłącznie właściwościom instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. **Odczyt/zapis** float.

--------------------

Zwracana wartość jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Przypisana wartość musi być również zdefiniowana; Float.NaN można przypisać wyłącznie właściwościom instancji RawFrame.

**Zwraca:**
float
### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. **Odczyt/zapis** float.

--------------------

Zwracana wartość jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Przypisana wartość musi być również zdefiniowana; Float.NaN można przypisać wyłącznie właściwościom instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Pobiera lub ustawia szerokość kształtu, mierzoną w punktach. **Odczyt/zapis** float.

--------------------

Zwracana wartość jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Przypisana wartość musi być również zdefiniowana; Float.NaN można przypisać wyłącznie właściwościom instancji RawFrame.

**Zwraca:**
float
### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Pobiera lub ustawia szerokość kształtu, mierzoną w punktach. **Odczyt/zapis** float.

--------------------

Zwracana wartość jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Przypisana wartość musi być również zdefiniowana; Float.NaN można przypisać wyłącznie właściwościom instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Pobiera lub ustawia wysokość kształtu, mierzoną w punktach. **Odczyt/zapis** float.

--------------------

Zwracana wartość jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Przypisana wartość musi być również zdefiniowana; Float.NaN można przypisać wyłącznie właściwościom instancji RawFrame.

**Zwraca:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Pobiera lub ustawia wysokość kształtu, mierzoną w punktach. **Odczyt/zapis** float.

--------------------

Zwracana wartość jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Przypisana wartość musi być również zdefiniowana; Float.NaN można przypisać wyłącznie właściwościom instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Zwraca lub ustawia alternatywny tekst powiązany z kształtem. **Odczyt/zapis** String.

**Zwraca:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Zwraca lub ustawia alternatywny tekst powiązany z kształtem. **Odczyt/zapis** String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Zwraca lub ustawia tytuł alternatywnego tekstu powiązanego z kształtem. **Odczyt/zapis** String.

**Zwraca:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Zwraca lub ustawia tytuł alternatywnego tekstu powiązanego z kształtem. **Odczyt/zapis** String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Zwraca lub ustawia nazwę kształtu. **Odczyt/zapis** String.

**Zwraca:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Zwraca lub ustawia nazwę kształtu. **Odczyt/zapis** String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Pobiera lub ustawia opcję „Mark as decorative”. **Odczyt/zapis** boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

Pobiera lub ustawia opcję „Mark as decorative”. **Odczyt/zapis** boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

Zwraca blokady kształtu. **Tylko do odczytu** [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Zwraca:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Zwraca wewnętrzny identyfikator prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być zmieniona przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz. **Tylko do odczytu** long. Zobacz także \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Zwraca:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Zwraca unikalny identyfikator w ramach slajdu, który pozostaje stały przez cały okres życia kształtu i pozwala PowerPointowi lub kodowi interop niezawodnie odwoływać się do kształtu z dowolnego miejsca dokumentu. **Tylko do odczytu** long. Zobacz także \#getUniqueId.getUniqueId.

**Zwraca:**
long
### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Określa, czy kształt jest grupowany. **Tylko do odczytu** boolean.

--------------------

Właściwość \#getParentGroup.getParentGroup zwraca obiekt parent GroupShape, jeśli kształt jest grupowany.

**Zwraca:**
boolean
### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. **Odczyt/zapis** [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Zwraca:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. **Odczyt/zapis** [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Zwraca obiekt parent GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca null. **Tylko do odczytu** [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Właściwość \#isGrouped.isGrouped określa, czy kształt jest grupowany.

**Zwraca:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Zapisuje zawartość Shape jako plik SVG.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Zapisuje zawartość Shape jako plik SVG.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opcje generowania SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Zwraca podstawowy placeholder shape (shape z układu i/lub slajdu master, z którego dziedziczony jest bieżący kształt).

--------------------

> ```
> // pobierz wszystkie (master/layout/slide) animowane efekty kształtu placeholder
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Zwracane jest null, jeśli bieżący kształt nie jest dziedziczony.

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)