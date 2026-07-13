---
title: IXpsOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i XPS-format.
type: docs
url: /sv/com.aspose.slides/ixpsoptions/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Tillhandahåller alternativ som styr hur en presentation sparas i XPS-format.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True för att konvertera alla metafiler som används i en presentation till PNG-bilder. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True för att konvertera alla metafiler som används i en presentation till PNG-bilder. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True för att rita en svart ram runt varje bild. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True för att rita en svart ram runt varje bild. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läs/skriv boolean.

--------------------

Standard är **true**.

**Returnerar:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läs/skriv boolean.

--------------------

Standard är **true**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True för att rita en svart ram runt varje bild. Läs/skriv boolean.

--------------------

Standard är **false**.

**Returnerar:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True för att rita en svart ram runt varje bild. Läs/skriv boolean.

--------------------

Standard är **false**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**.

**Returnerar:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |