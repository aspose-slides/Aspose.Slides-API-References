---
title: IShape
second_title: Aspose.Slides dla Androida - odwołanie do API Java
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
| [isTextHolder()](#isTextHolder--) | Określa, czy kształt jest TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Zwraca placeholder dla kształtu. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [removePlaceholder()](#removePlaceholder--) | Definiuje, że ten kształt nie jest placeholderem. |
| [getCustomData()](#getCustomData--) | Zwraca niestandardowe dane kształtu. |
| [getRawFrame()](#getRawFrame--) | Zwraca lub ustawia właściwości surowej ramki kształtu. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Zwraca lub ustawia właściwości surowej ramki kształtu. |
| [getFrame()](#getFrame--) | Zwraca lub ustawia właściwości ramki kształtu. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Zwraca lub ustawia właściwości ramki kształtu. |
| [getLineFormat()](#getLineFormat--) | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu. |
| [getThreeDFormat()](#getThreeDFormat--) | Zwraca obiekt ThreeDFormat zawierający właściwości formatowania linii dla kształtu. |
| [getEffectFormat()](#getEffectFormat--) | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu. |
| [getFillFormat()](#getFillFormat--) | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu. |
| [getImage()](#getImage--) | Zwraca miniaturkę kształtu. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Zwraca miniaturkę kształtu. |
| [getHidden()](#getHidden--) | Określa, czy kształt jest ukryty. |
| [setHidden(boolean value)](#setHidden-boolean-) | Określa, czy kształt jest ukryty. |
| [getZOrderPosition()](#getZOrderPosition--) | Zwraca pozycję kształtu w kolejności Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Zwraca liczbę miejsc połączeń na kształcie. |
| [getRotation()](#getRotation--) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi Z. |
| [setRotation(float value)](#setRotation-float-) | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi Z. |
| [getX()](#getX--) | Pobiera lub ustawia współrzędną X lewego górnego rogu kształtu, mierzoną w punktach. |
| [setX(float value)](#setX-float-) | Pobiera lub ustawia współrzędną X lewego górnego rogu kształtu, mierzoną w punktach. |
| [getY()](#getY--) | Pobiera lub ustawia współrzędną Y lewego górnego rogu kształtu, mierzoną w punktach. |
| [setY(float value)](#setY-float-) | Pobiera lub ustawia współrzędną Y lewego górnego rogu kształtu, mierzoną w punktach. |
| [getWidth()](#getWidth--) | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach. |
| [setWidth(float value)](#setWidth-float-) | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach. |
| [getHeight()](#getHeight--) | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach. |
| [setHeight(float value)](#setHeight-float-) | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach. |
| [getAlternativeText()](#getAlternativeText--) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Zwraca lub ustawia tekst alternatywny powiązany z kształtem. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem. |
| [getName()](#getName--) | Zwraca lub ustawia nazwę kształtu. |
| [setName(String value)](#setName-java.lang.String-) | Zwraca lub ustawia nazwę kształtu. |
| [isDecorative()](#isDecorative--) | Pobiera lub ustawia opcję 'Mark as decorative' odczyt/zapis boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Pobiera lub ustawia opcję 'Mark as decorative' odczyt/zapis boolean. |
| [getShapeLock()](#getShapeLock--) | Zwraca blokady kształtu. |
| [getUniqueId()](#getUniqueId--) | Zwraca wewnętrzny, prezentacją scoped identyfikator przeznaczony do użycia przez dodatki lub inny kod. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Zwraca unikalny identyfikator scoped na slajd, który pozostaje stały przez cały okres życia kształtu i pozwala PowerPointowi lub kodowi interopowy niezawodnie odwoływać się do kształtu z dowolnego miejsca w dokumencie. |
| [isGrouped()](#isGrouped--) | Określa, czy kształt jest grupowany. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. |
| [getParentGroup()](#getParentGroup--) | Zwraca obiekt parent GroupShape, jeśli kształt jest grupowany. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Zapisuje zawartość Shape jako plik SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Zapisuje zawartość Shape jako plik SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Zwraca podstawowy kształt placeholder (kształt z układu i/lub slajdu wzorcowego, z którego dziedziczy bieżący kształt). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Określa, czy kształt jest TextHolder. Tylko do odczytu boolean.

**Zwraca:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Zwraca placeholder dla kształtu. Tylko do odczytu [IPlaceholder](../../com.aspose.slides/iplaceholder).

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
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder, z którego kopiować zawartość. |

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

Zwraca niestandardowe dane kształtu. Tylko do odczytu [ICustomData](../../com.aspose.slides/icustomdata).

**Zwraca:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Zwraca lub ustawia właściwości surowej ramki kształtu. odczyt/zapis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //lub
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Taki kod może prowadzić do niejasnych sytuacji. Dlatego wprowadzono ograniczenia dotyczące używania niezdefiniowanych wartości dla IShape.getFrame(). Wartości x, y, width, height, flipH, flipV i rotationAngle muszą być zdefiniowane (nie Float.NaN ani NullableBool.NotDefined). Powyższy przykład kodu teraz rzuca wyjątek ArgumentException.
>  //Dotyczy to następujących przypadków użycia:
>  IShape shape = ...;
>  shape.setFrame(...); // nie może być niezdefiniowane
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

**Zwraca:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Zwraca lub ustawia właściwości surowej ramki kształtu. odczyt/zapis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Kod, który próbuje przypisać niezdefiniowaną ramkę do IShape.getFrame(), nie ma sensu w ogólnym przypadku (szczególnie gdy nadrzędny GroupShape jest wielokrotnie zagnieżdżony w innych GroupShape-ach). Na przykład:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //lub
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Taki kod może prowadzić do niejasnych sytuacji. Dlatego wprowadzono ograniczenia dotyczące używania niezdefiniowanych wartości dla IShape.getFrame(). Wartości x, y, width, height, flipH, flipV i rotationAngle muszą być zdefiniowane (nie Float.NaN ani NullableBool.NotDefined). Powyższy przykład kodu teraz rzuca wyjątek ArgumentException.
>  //Dotyczy to następujących przypadków użycia:
>  IShape shape = ...;
>  shape.setFrame(...); // nie może być niezdefiniowane
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
>  Jednak właściwości ramki IShape.RawFrame mogą być niezdefiniowane. Ma to sens, gdy kształt jest powiązany z placeholderem. Wtedy niezdefiniowane wartości ramki kształtu są nadpisywane z nadrzędnego placeholdera. Jeśli nie ma nadrzędnego placeholdera dla tego kształtu, kształt używa wartości domyślnych przy obliczaniu efektywnej ramki na podstawie IShape.RawFrame. Domyślne wartości to 0 oraz NullableBool.False dla x, y, width, height, flipH, flipV i rotationAngle. Na przykład:
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

Zwraca lub ustawia właściwości ramki kształtu. odczyt/zapis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Wartość każdej właściwości zwróconej instancji IShapeFrame nie jest niezdefiniowana (nie jest NaN ani NotDefined). Wartość każdej właściwości przypisanej instancji IShapeFrame musi nie być niezdefiniowana (musi nie być NaN ani NotDefined). Można ustawiać niezdefiniowane wartości dla właściwości instancji RawFrame.

**Zwraca:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Zwraca lub ustawia właściwości ramki kształtu. odczyt/zapis [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Wartość każdej właściwości zwróconej instancji IShapeFrame nie jest niezdefiniowana (nie jest NaN ani NotDefined). Wartość każdej właściwości przypisanej instancji IShapeFrame musi nie być niezdefiniowana (musi nie być NaN ani NotDefined). Można ustawiać niezdefiniowane wartości dla właściwości instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu. Tylko do odczytu [ILineFormat](../../com.aspose.slides/ilineformat).

**Zwraca:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Zwraca obiekt ThreeDFormat zawierający właściwości formatowania linii dla kształtu. Tylko do odczytu [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Zwraca:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu. Tylko do odczytu [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Zwraca:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Zwraca miniaturkę kształtu. Domyślnie używany jest typ ShapeThumbnailBounds.Shape do określenia granic miniaturki kształtu.

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Zwraca miniaturkę kształtu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| bounds | int | Typ granic miniaturki kształtu. |
| scaleX | float | Skala X |
| scaleY | float | Skala Y |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Miniaturka kształtu lub null w przypadku, gdy użyto ShapeThumbnailBounds.Appearance i kształt nie ma widocznych elementów.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Określa, czy kształt jest ukryty. odczyt/zapis boolean.

**Zwraca:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Określa, czy kształt jest ukryty. odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Zwraca pozycję kształtu w kolejności Z. Shapes[0] zwraca kształt z tyłu kolejności Z, a Shapes[Shapes.Count - 1] zwraca kształt z przodu kolejności Z. Tylko do odczytu int.

**Zwraca:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Zwraca liczbę miejsc połączeń na kształcie. Tylko do odczytu int.

**Zwraca:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi Z. Dodatnia wartość oznacza obrót zgodny z ruchem wskazówek zegara; ujemna wartość oznacza obrót przeciwny do ruchu wskazówek zegara. odczyt/zapis float.

--------------------

Zwracana wartość jest zawsze zdefiniowana (nie jest Float.NaN). Przypisana wartość musi być zdefiniowana (nie Float.NaN). Można ustawiać niezdefiniowane wartości dla właściwości instancji RawFrame.

**Zwraca:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi Z. Dodatnia wartość oznacza obrót zgodny z ruchem wskazówek zegara; ujemna wartość oznacza obrót przeciwny do ruchu wskazówek zegara. odczyt/zapis float.

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

Pobiera lub ustawia współrzędną X lewego górnego rogu kształtu, mierzoną w punktach. odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Wartość przypisywana musi być również zdefiniowana; przypisuj Float.NaN tylko właściwościom instancji RawFrame.

**Zwraca:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Pobiera lub ustawia współrzędną X lewego górnego rogu kształtu, mierzoną w punktach. odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Wartość przypisywana musi być również zdefiniowana; przypisuj Float.NaN tylko właściwościom instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Pobiera lub ustawia współrzędną Y lewego górnego rogu kształtu, mierzoną w punktach. odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Wartość przypisywana musi być również zdefiniowana; przypisuj Float.NaN tylko właściwościom instancji RawFrame.

**Zwraca:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Pobiera lub ustawia współrzędną Y lewego górnego rogu kształtu, mierzoną w punktach. odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Wartość przypisywana musi być również zdefiniowana; przypisuj Float.NaN tylko właściwościom instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Pobiera lub ustawia szerokość kształtu, mierzoną w punktach. odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Wartość przypisywana musi być również zdefiniowana; przypisuj Float.NaN tylko właściwościom instancji RawFrame.

**Zwraca:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Pobiera lub ustawia szerokość kształtu, mierzoną w punktach. odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Wartość przypisywana musi być również zdefiniowana; przypisuj Float.NaN tylko właściwościom instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Pobiera lub ustawia wysokość kształtu, mierzoną w punktach. odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Wartość przypisywana musi być również zdefiniowana; przypisuj Float.NaN tylko właściwościom instancji RawFrame.

**Zwraca:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Pobiera lub ustawia wysokość kształtu, mierzoną w punktach. odczyt/zapis float.

--------------------

Wartość zwracana jest zawsze zdefiniowana i nigdy nie jest Float.NaN. Wartość przypisywana musi być również zdefiniowana; przypisuj Float.NaN tylko właściwościom instancji RawFrame.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Zwraca lub ustawia tekst alternatywny powiązany z kształtem. odczyt/zapis String.

**Zwraca:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Zwraca lub ustawia tekst alternatywny powiązany z kształtem. odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem. odczyt/zapis String.

**Zwraca:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem. odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Zwraca lub ustawia nazwę kształtu. odczyt/zapis String.

**Zwraca:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Zwraca lub ustawia nazwę kształtu. odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Pobiera lub ustawia opcję 'Mark as decorative' odczyt/zapis boolean.

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

Pobiera lub ustawia opcję 'Mark as decorative' odczyt/zapis boolean.

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

Zwraca blokady kształtu. Tylko do odczytu [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Zwraca:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Zwraca wewnętrzny identyfikator scoped na prezentację, przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz. Tylko do odczytu long. Zobacz także \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Zwraca:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long ... (the ... part is not provided in the input and cannot be translated)
```

Zwraca unikalny identyfikator scoped na slajd, który pozostaje stały przez cały okres życia kształtu i pozwala PowerPointowi lub kodowi interopowy niezawodnie odwoływać się do kształtu z dowolnego miejsca w dokumencie. Tylko do odczytu long. Zobacz także \#getUniqueId.getUniqueId.

**Zwraca:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Określa, czy kształt jest grupowany. Tylko do odczytu boolean.

--------------------

Właściwość \#getParentGroup.getParentGroup zwraca obiekt parent GroupShape, jeśli kształt jest grupowany.

**Zwraca:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. odczyt/zapis [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Zwraca:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. odczyt/zapis [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Zwraca obiekt parent GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [IGroupShape](../../com.aspose.slides/igroupshape).

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

Zwraca podstawowy kształt placeholder (kształt z układu i/lub slajdu wzorcowego, z którego dziedziczy bieżący kształt).

--------------------

> ```
> // pobierz wszystkie (master/layout/slide) animowane efekty kształtu zastępczego
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


Zwrócony jest null, jeśli bieżący kształt nie jest dziedziczony.

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)