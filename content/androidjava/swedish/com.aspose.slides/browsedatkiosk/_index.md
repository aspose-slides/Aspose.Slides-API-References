---
title: BrowsedAtKiosk
second_title: Aspose.Slides för Android via Java API-referens
description: Visas på en kiosk i helskärm
type: docs
url: /sv/com.aspose.slides/browsedatkiosk/
---
**Arv:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedAtKiosk extends SlideShowType
```

Visas i kiosk (fullskärm)

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
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [BrowsedAtKiosk()](#BrowsedAtKiosk--) | Initierar en ny instans av klassen BrowsedAtKiosk. |
### BrowsedAtKiosk() {#BrowsedAtKiosk--}
```
public BrowsedAtKiosk()
```

Initierar en ny instans av klassen BrowsedAtKiosk.

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