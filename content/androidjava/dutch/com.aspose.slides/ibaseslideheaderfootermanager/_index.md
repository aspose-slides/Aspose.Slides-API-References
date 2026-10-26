---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides voor Android via Java API-referentie
description: Representatie van de manager die het gedrag van de voettekst-, datum-tijd- en paginanummer-plaatsaanduidingen voor alle diatypes beheert.
type: docs
url: /nl/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Representatie van de manager die het gedrag van de voettekst-, datum-tijd- en paginanummer-plaatsaanduiders voor alle diatypes beheert.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Haalt de waarde op die aangeeft dat een voettekst-plaatsaanduiding aanwezig is. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Haalt de waarde op die aangeeft dat een paginanummer-plaatsaanduiding aanwezig is. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Haalt de waarde op die aangeeft dat een datum-tijd-plaatsaanduiding aanwezig is. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Wijzigt de zichtbaarheid van de voettekst-plaatsaanduiding van de dia. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Wijzigt de zichtbaarheid van de paginanummer-plaatsaanduiding van de dia. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Wijzigt de zichtbaarheid van de datum-tijd-plaatsaanduiding van de dia. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Stelt de tekst in voor de voettekst-plaatsaanduiding van de dia. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Stelt de tekst in voor de datum-tijd-plaatsaanduiding van de dia. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```


Haalt de waarde op die aangeeft dat een voettekst-plaatsaanduiding aanwezig is. Lees boolean.

**Retourneert:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```


Haalt de waarde op die aangeeft dat een paginanummer-plaatsaanduiding aanwezig is. Lees boolean.

**Retourneert:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```


Haalt de waarde op die aangeeft dat een datum-tijd-plaatsaanduiding aanwezig is. Lees boolean.

**Retourneert:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```


Wijzigt de zichtbaarheid van de voettekst-plaatsaanduiding van de dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt een voettekst-plaatsaanduiding zichtbaar, anders - verbergt deze. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```


Wijzigt de zichtbaarheid van de paginanummer-plaatsaanduiding van de dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt een paginanummer-plaatsaanduiding zichtbaar, anders - verbergt deze. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```


Wijzigt de zichtbaarheid van de datum-tijd-plaatsaanduiding van de dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt een datum-tijd-plaatsaanduiding zichtbaar, anders - verbergt deze. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```


Stelt de tekst in voor de voettekst-plaatsaanduiding van de dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | In te stellen tekst. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```


Stelt de tekst in voor de datum-tijd-plaatsaanduiding van de dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | In te stellen tekst. |