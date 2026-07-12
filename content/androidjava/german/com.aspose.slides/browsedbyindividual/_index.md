---
title: BrowsedByIndividual
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Einzelne Ansicht im Fenster
type: docs
url: /de/com.aspose.slides/browsedbyindividual/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Browsed by individual (window)

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Initialisiert eine neue Instanz der Klasse BrowsedByIndividual. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Scrollleiste im Fenster anzeigen |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Scrollleiste im Fenster anzeigen |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


Initialisiert eine neue Instanz der Klasse BrowsedByIndividual.

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


Scrollleiste im Fenster anzeigen

**Rückgabewert:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Scrollleiste im Fenster anzeigen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |