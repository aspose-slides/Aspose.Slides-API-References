---
title: SlideShowType
second_title: Aspose.Slides für Java API-Referenz
description: Grundlegende Diashow-Einstellungen.
type: docs
url: /de/com.aspose.slides/slideshowtype/
---
**Vererbung:**
java.lang.Object
```
public abstract class SlideShowType
```

Grundlegende Diashow-Einstellungen. Vorfahren stellen die Typen der Diashow dar: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Präsentiert von einem Redner (Vollbild) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Von einer Einzelperson durchsucht (Fenster) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) An einem Kiosk durchsucht (Vollbild)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>      pres.save("PresentedBySpeaker.pptx", SaveFormat.Pptx);
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("BrowsedByIndividual.pptx", SaveFormat.Pptx);
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
>      pres.save("BrowsedAtKiosk.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```