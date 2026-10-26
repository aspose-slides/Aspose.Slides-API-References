---
title: IAutoShape
second_title: Aspose.Slides for Android - odniesienie do API Java
description: Reprezentuje AutoShape.
type: docs
url: /pl/com.aspose.slides/iautoshape/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Reprezentuje AutoShape.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Zwraca blokady AutoShape. |
| [getTextFrame()](#getTextFrame--) | Zwraca obiekt TextFrame dla AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Określa, czy ten autoshape powinien być wypełniony tłem slajdu zamiast określonego przez styl lub format wypełnienia. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Określa, czy ten autoshape powinien być wypełniony tłem slajdu zamiast określonego przez styl lub format wypełnienia. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Dodaje nowy TextFrame do kształtu. |
| [isTextBox()](#isTextBox--) | Określa, czy kształt jest polem tekstowym. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Zwraca blokady AutoShape. Tylko do odczytu [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Zwraca:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Zwraca obiekt TextFrame dla AutoShape. Tylko do odczytu [ITextFrame](../../com.aspose.slides/itextframe).

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Określa, czy ten autoshape powinien być wypełniony tłem slajdu zamiast określonego przez styl lub format wypełnienia. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Określa, czy ten autoshape powinien być wypełniony tłem slajdu zamiast określonego przez styl lub format wypełnienia. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Dodaje nowy TextFrame do kształtu. Jeśli kształt już ma TextFrame, po prostu zmienia jego tekst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Domyślny tekst dla nowego TextFrame. |

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe) - Nowy [ITextFrame](../../com.aspose.slides/itextframe) obiekt.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Określa, czy kształt jest polem tekstowym.

--------------------

Jeśli kształt nie jest określony jako pole tekstowe, nie oznacza to, że nie może mieć do niego dołączonego tekstu. Pole tekstowe jest po prostu specjalnym kształtem o określonych właściwościach.

**Zwraca:**
boolean