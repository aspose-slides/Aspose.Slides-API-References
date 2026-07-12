---
title: BrowsedAtKiosk
second_title: Aspose.Slides Android-hoz a Java API Referencián keresztül
description: Teljes képernyőn böngészve egy kioszkon
type: docs
url: /hu/com.aspose.slides/browsedatkiosk/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedAtKiosk extends SlideShowType
```

Kijelzőn böngészve (teljes képernyő)

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
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [BrowsedAtKiosk()](#BrowsedAtKiosk--) | Inicializál egy új példányt a BrowsedAtKiosk osztályból. |
### BrowsedAtKiosk() {#BrowsedAtKiosk--}
```
public BrowsedAtKiosk()
```

Inicializál egy új példányt a BrowsedAtKiosk osztályból.

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