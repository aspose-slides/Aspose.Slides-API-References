---
title: IAutoShape
second_title: Aspose.Slides Android számára Java API referencián keresztül
description: Ábrázolja az AutoShape-t.
type: docs
url: /hu/com.aspose.slides/iautoshape/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Ábrázolja az AutoShape-t.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Returns AutoShape's locks. |
| [getTextFrame()](#getTextFrame--) | Returns TextFrame object for the AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Adds a new TextFrame to a shape. |
| [isTextBox()](#isTextBox--) | Specifies if the shape is a text box. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```

Visszaadja az AutoShape zárolásait. **Csak olvasható** [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Visszatér:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Visszaadja a TextFrame objektumot az AutoShape-hez. **Csak olvasható** [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```

Meghatározza, hogy ez az autoshape a dia háttérkitöltésével legyen-e kitöltve a stílus vagy a kitöltési formátum által megadott helyett. **Olvasás/írás boolean.**

**Visszatér:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

Meghatározza, hogy ez az autoshape a dia háttérkitöltésével legyen-e kitöltve a stílus vagy a kitöltési formátum által megadott helyett. **Olvasás/írás boolean.**

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```

Új TextFrame-et ad a formához. Ha a forma már rendelkezik TextFrame-mel, akkor egyszerűen megváltoztatja annak szövegét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Default text for a new TextFrame. |
**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe) - Új [ITextFrame](../../com.aspose.slides/itextframe) objektum.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```

Megadja, hogy a forma szövegdoboz-e.

--------------------

Ha a forma nincs megadva szövegdobozként, ez nem jelenti, hogy ne tartalmazhatna szöveget. A szövegdoboz csupán egy speciális forma, amelynek sajátos tulajdonságai vannak.

**Visszatér:**
boolean