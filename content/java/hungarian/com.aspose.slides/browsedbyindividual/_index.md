---
title: BrowsedByIndividual
second_title: Aspose.Slides Java API referencia
description: Egyéni böngészőablak
type: docs
url: /hu/com.aspose.slides/browsedbyindividual/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Egyénileg böngészve (ablak)

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
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Új példány inicializálása a BrowsedByIndividual osztályból. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Görgetősáv megjelenítése ablakban |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Görgetősáv megjelenítése ablakban |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


Új példány inicializálása a BrowsedByIndividual osztályból.

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


Görgetősáv megjelenítése ablakban

**Visszatérési érték:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Görgetősáv megjelenítése ablakban

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |