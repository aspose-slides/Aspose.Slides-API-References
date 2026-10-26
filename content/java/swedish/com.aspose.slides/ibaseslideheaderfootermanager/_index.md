---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides för Java API-referens
description: Representerar en manager som hanterar beteendet för sidfot-, datum-tid- och sidnummer-platshållare för alla bildtyper.
type: docs
url: /sv/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Representerar en manager som hanterar beteendet för sidfot-, datum-tid- och sidnummer-platshållare för alla bildtyper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Hämtar värde som indikerar att en sidfot-platshållare finns. Läs boolean. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Hämtar värde som indikerar att en sidnummer-platshållare finns. Läs boolean. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Hämtar värde som indikerar att en datum-tid-platshållare finns. Läs boolean. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Ändrar synlighet för bildens sidfot-platshållare. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Ändrar synlighet för bildens sidnummer-platshållare. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Ändrar synlighet för bildens datum-tid-platshållare. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Sätter text till bildens sidfot-platshållare. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Sätter text till bildens datum-tid-platshållare. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Hämtar värde som indikerar att en sidfot-platshållare finns. Läs boolean.

**Returnerar:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Hämtar värde som indikerar att en sidnummer-platshållare finns. Läs boolean.

**Returnerar:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Hämtar värde som indikerar att en datum-tid-platshållare finns. Läs boolean.

**Returnerar:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Ändrar synlighet för bildens sidfot-platshållare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör en sidfot-platshållare synlig, annars - döljer den. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Ändrar synlighet för bildens sidnummer-platshållare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör en sidnummer-platshållare synlig, annars - döljer den. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Ändrar synlighet för bildens datum-tid-platshållare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör en datum-tid-platshållare synlig, annars - döljer den. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Sätter text till bildens sidfot-platshållare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Sätter text till bildens datum-tid-platshållare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |