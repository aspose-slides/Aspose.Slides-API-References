---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een manager voor die het gedrag van de placeholders bevat, inclusief een header placeholder voor alle typen handout- en notitieslides.
type: docs
url: /nl/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Stelt de manager voor die het gedrag van de placeholders bevat, inclusief header placeholder voor alle typen handout- en notitieslides.
Originele interface-naam "IBaseHandoutNotesSlideHeaderFooterManager" is afgekapt tot "IBaseHandoutNotesSlideHeaderFooterManag" voor COM-compatibiliteit (type-naam lengte mag niet meer dan 39 zijn).
## Methoden
| Method | Description |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Haalt de waarde op die aangeeft dat een header placeholder aanwezig is. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Wijzigt de zichtbaarheid van de header placeholder van de slide. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Stelt de tekst in voor de header placeholder van de slide. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Haalt de waarde op die aangeeft dat een header placeholder aanwezig is. Lees boolean.

**Retour:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van de slide-header placeholder.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt een header placeholder zichtbaar, anders - verbergt deze. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

Stelt de tekst in voor de slide-header placeholder.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Te zetten tekst. |