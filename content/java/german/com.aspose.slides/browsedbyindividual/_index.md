---
title: BrowsedByIndividual
second_title: Aspose.Slides für Java API-Referenz
description: Einzelperson-Browserfenster
type: docs
url: /de/com.aspose.slides/browsedbyindividual/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Durchsucht von Einzelperson (Fenster)

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

**Rückgabe:**
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