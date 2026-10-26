---
title: IAutoShape
second_title: Aspose.Slides for Java API-referencia
description: Az AutoShape-et ábrázolja.
type: docs
url: /hu/com.aspose.slides/iautoshape/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Represents an AutoShape.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Visszaadja az AutoShape zárolásait. |
| [getTextFrame()](#getTextFrame--) | Visszaadja az AutoShape TextFrame objektumát. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Megállapítja, hogy ez az autóalak a dia háttérkitöltésével legyen-e kitöltve a stílus vagy kitöltési formátum helyett. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Megállapítja, hogy ez az autóalak a dia háttérkitöltésével legyen-e kitöltve a stílus vagy kitöltési formátum helyett. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Új TextFrame-et ad hozzá egy alakzathoz. |
| [isTextBox()](#isTextBox--) | Megadja, hogy az alakzat szövegdoboz-e. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Visszaadja az AutoShape zárolásait. Csak olvasható [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Visszatér:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Visszaadja az AutoShape TextFrame objektumát. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Megállapítja, hogy ez az autóalak a dia háttérkitöltésével legyen-e kitöltve a stílus vagy kitöltési formátum helyett. Olvasható/írható boolean.

**Visszatér:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Megállapítja, hogy ez az autóalak a dia háttérkitöltésével legyen-e kitöltve a stílus vagy kitöltési formátum helyett. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Új TextFrame-et ad hozzá egy alakzathoz. Ha az alakzat már rendelkezik TextFrame-mel, akkor egyszerűen megváltoztatja a szövegét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Alapértelmezett szöveg egy új TextFrame-hez. |

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe) - Új [ITextFrame](../../com.aspose.slides/itextframe) objektum.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Megadja, hogy az alakzat szövegdoboz-e.

--------------------

Ha egy alakzat nincs megadva szövegdobozként, az nem jelenti, hogy nem tartalmazhat szöveget. A szövegdoboz csupán egy speciális alakzat, amely speciális tulajdonságokkal rendelkezik.

**Visszatér:**
boolean