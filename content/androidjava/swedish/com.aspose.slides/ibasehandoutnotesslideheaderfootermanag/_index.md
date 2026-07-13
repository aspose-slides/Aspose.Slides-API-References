---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en manager som hanterar beteendet för platshållarna, inklusive rubrik-platshållare för alla typer av handout- och notesslides.
type: docs
url: /sv/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Representerar manager som håller beteendet för platshållarna, inklusive rubrik-platshållare för alla typer av handout- och notesslides.

--------------------

Det ursprungliga gränssnittsnamnet "IBaseHandoutNotesSlideHeaderFooterManager" trunkeras till "IBaseHandoutNotesSlideHeaderFooterManag" för COM-kompatibilitet (typnamnets längd får inte vara mer än 39).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Hämtar värde som indikerar att en rubrik-platshållare finns. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Ändrar synligheten för slide-rubrik-platshållaren. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Anger text till slide-rubrik-platshållaren. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

Hämtar värde som indikerar att en rubrik-platshållare finns. Läs boolean.

**Returnerar:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

Ändrar synligheten för slide-rubrik-platshållaren.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör en rubrik-platshållare synlig, annars - döljer den. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

Anger text till slide-rubrik-platshållaren.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att ange. |