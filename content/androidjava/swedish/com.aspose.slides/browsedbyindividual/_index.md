---
title: BrowsedByIndividual
second_title: Aspose.Slides för Android via Java API-referens
description: Fönster som bläddras av individ
type: docs
url: /sv/com.aspose.slides/browsedbyindividual/
---
**Arv:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Bläddrad av individ (fönster)

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
## Konstruktörer

| Constructor | Description |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Initierar en ny instans av klassen BrowsedByIndividual. |

## Metoder

| Method | Description |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Visa rullningslist i fönster |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Visa rullningslist i fönster |

### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

Initierar en ny instans av klassen BrowsedByIndividual.

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

Visa rullningslist i fönster

**Returnerar:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```

Visa rullningslist i fönster

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |