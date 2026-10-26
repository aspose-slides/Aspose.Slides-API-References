---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een manager voor die het gedrag van de placeholders bevat, inclusief de header-placeholder voor alle typen handout- en notitieslides.
type: docs
url: /nl/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Stelt een manager voor die het gedrag van de placeholders bevat, inclusief de header-placeholder voor alle typen handout- en notitieslides.

--------------------

De oorspronkelijke interfacenaam "IBaseHandoutNotesSlideHeaderFooterManager" is afgekapt tot "IBaseHandoutNotesSlideHeaderFooterManag" voor COM-compatibiliteit (de type-naam mag niet langer dan 39 tekens zijn).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Haalt de waarde op die aangeeft dat een header-placeholder aanwezig is. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Wijzigt de zichtbaarheid van de header-placeholder op de slide. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Stelt de tekst in voor de header-placeholder op de slide. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Haalt de waarde op die aangeeft dat een header-placeholder aanwezig is. Lees boolean.

**Retourneert:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


Wijzigt de zichtbaarheid van de header-placeholder op de slide.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt een header-placeholder zichtbaar, anders - verbergt deze. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Stelt de tekst in voor de header-placeholder op de slide.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Te zetten tekst. |