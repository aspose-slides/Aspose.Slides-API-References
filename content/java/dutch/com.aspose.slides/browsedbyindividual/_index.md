---
title: BrowsedByIndividual
second_title: Aspose.Slides voor Java API-referentie
description: Bladeren per individueel venster
type: docs
url: /nl/com.aspose.slides/browsedbyindividual/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Blader per individu (venster)

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
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Initialiseert een nieuw exemplaar van de BrowsedByIndividual-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Scrollbalk weergeven in venster |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Scrollbalk weergeven in venster |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


Initialiseert een nieuw exemplaar van de BrowsedByIndividual-klasse.

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


Scrollbalk weergeven in venster

**Retourwaarde:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Scrollbalk weergeven in venster

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |