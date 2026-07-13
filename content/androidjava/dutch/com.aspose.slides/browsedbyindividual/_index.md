---
title: BrowsedByIndividual
second_title: Aspose.Slides voor Android via Java API-referentie
description: Weergegeven in individueel venster
type: docs
url: /nl/com.aspose.slides/browsedbyindividual/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Gebruikt door individu (venster)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructeurs

| Constructor | Beschrijving |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Initialiseert een nieuw exemplaar van de BrowsedByIndividual klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Scrollbalk tonen in venster |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Scrollbalk tonen in venster |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


Initialiseert een nieuw exemplaar van de BrowsedByIndividual klasse.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```


Scrollbalk tonen in venster

**Retourwaarde:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Scrollbalk tonen in venster

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |