---
title: BrowsedAtKiosk
second_title: Aspose.Slides dla Androida – odwołanie do API Java
description: Przeglądane w kiosku w trybie pełnoekranowym
type: docs
url: /pl/com.aspose.slides/browsedatkiosk/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedAtKiosk extends SlideShowType
```

Przeglądane w kiosku (pełny ekran)

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
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [BrowsedAtKiosk()](#BrowsedAtKiosk--) | Inicjalizuje nową instancję klasy BrowsedAtKiosk. |
### BrowsedAtKiosk() {#BrowsedAtKiosk--}
```
public BrowsedAtKiosk()
```


Inicjalizuje nową instancję klasy BrowsedAtKiosk.

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