---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en hanterare som innehåller beteendet för sidfot-, datum-tid- och sidnummer-platshållare för alla bildtyper.
type: docs
url: /sv/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Representerar en hanterare som innehåller beteendet för sidfot-, datum-tid- och sidnummer-platshållare för alla bildtyper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Hämtar värde som indikerar att en sidfot-platshållare finns. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Hämtar värde som indikerar att en sidnummer-platshållare finns. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Hämtar värde som indikerar att en datum-tid-platshållare finns. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Ändrar synligheten för bildens sidfot-platshållare. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Ändrar synligheten för bildens sidnummer-platshållare. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Ändrar synligheten för bildens datum-tid-platshållare. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Ställer in text för bildens sidfot-platshållare. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Ställer in text för bildens datum-tid-platshållare. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```


Hämtar värde som indikerar att en sidfot-platshållare finns. Läs boolesk.

**Returnerar:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```


Hämtar värde som indikerar att en sidnummer-platshållare finns. Läs boolesk.

**Returnerar:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```


Hämtar värde som indikerar att en datum-tid-platshållare finns. Läs boolesk.

**Returnerar:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```


Ändrar synligheten för bildens sidfot-platshållare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör en sidfot-platshållare synlig, annars - döljer den. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```


Ändrar synligheten för bildens sidnummer-platshållare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör en sidnummer-platshållare synlig, annars - döljer den. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```


Ändrar synligheten för bildens datum-tid-platshållare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör en datum-tid-platshållare synlig, annars - döljer den. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```


Ställer in text för bildens sidfot-platshållare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```


Ställer in text för bildens datum-tid-platshållare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |