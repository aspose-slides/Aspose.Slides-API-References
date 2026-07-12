---
title: BrowsedByIndividual
second_title: Aspose.Slides for Android Java API hivatkozás
description: Egyéni böngészőablak
type: docs
url: /hu/com.aspose.slides/browsedbyindividual/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Egyéni böngészés (ablak)

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
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Új példányt hoz létre a BrowsedByIndividual osztályban. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Görgetősáv megjelenítése az ablakban |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Görgetősáv megjelenítése az ablakban |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

Új példányt hoz létre a BrowsedByIndividual osztályban.

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

Görgetősáv megjelenítése az ablakban

**Visszatér:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```

Görgetősáv megjelenítése az ablakban

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |