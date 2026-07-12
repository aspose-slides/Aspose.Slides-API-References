---
title: BrowsedAtKiosk
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Im Kiosk im Vollbildmodus angezeigt
type: docs
url: /de/com.aspose.slides/browsedatkiosk/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedAtKiosk extends SlideShowType
```

Im Kiosk angezeigt (Vollbild)

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BrowsedAtKiosk()](#BrowsedAtKiosk--) | Initialisiert eine neue Instanz der BrowsedAtKiosk-Klasse. |
### BrowsedAtKiosk() {#BrowsedAtKiosk--}
```
public BrowsedAtKiosk()
```


Initialisiert eine neue Instanz der BrowsedAtKiosk-Klasse.

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