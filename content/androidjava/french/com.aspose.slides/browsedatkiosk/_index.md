---
title: BrowsedAtKiosk
second_title: Aspose.Slides pour Android via la référence API Java
description: Parcouru en kiosque plein écran
type: docs
url: /fr/com.aspose.slides/browsedatkiosk/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedAtKiosk extends SlideShowType
```

Parcouru en kiosque (plein écran)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [BrowsedAtKiosk()](#BrowsedAtKiosk--) | Initializes a new instance of the BrowsedAtKiosk class. |
### BrowsedAtKiosk() {#BrowsedAtKiosk--}
```
public BrowsedAtKiosk()


Initialise une nouvelle instance de la classe BrowsedAtKiosk.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```