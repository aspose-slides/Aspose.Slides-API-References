---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides för Java API-referens
description: Representerar en manager som hanterar beteendet för platshållarna, inklusive header-platshållare för alla typer av handout- och notes-slides.
type: docs
url: /sv/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Representerar en manager som håller beteendet för platshållarna, inklusive header-platshållare för alla typer av handout- och notes-slides.

--------------------

Original interface name "IBaseHandoutNotesSlideHeaderFooterManager" is trancuted to "IBaseHandoutNotesSlideHeaderFooterManag" for COM compatibility (type name length must be not more than 39).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Hämtar värdet som indikerar att en header-platshållare finns. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Ändrar slide-header-platshållarens synlighet. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Ställer in text för slide-header-platshållaren. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Hämtar värdet som indikerar att en header-platshållare finns. Läs boolean.

**Returnerar:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


Ändrar slide-header-platshållarens synlighet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör en header-platshållare synlig, annars – döljer den. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Ställer in text för slide-header-platshållaren.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Texten att ange. |