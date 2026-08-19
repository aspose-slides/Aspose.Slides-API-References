---
title: BrowsedAtKiosk
second_title: Aspose.Slides för Java API-referens
description: Visad i en kiosk i helskärm
type: docs
url: /sv/com.aspose.slides/browsedatkiosk/
---
**Arv:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedAtKiosk extends SlideShowType
```

Visad i en kiosk (fullskärm)

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

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BrowsedAtKiosk()](#BrowsedAtKiosk--) | Initialiserar en ny instans av klassen BrowsedAtKiosk. |
### BrowsedAtKiosk() {#BrowsedAtKiosk--}
```
public BrowsedAtKiosk()
```

Initialiserar en ny instans av klassen BrowsedAtKiosk.

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