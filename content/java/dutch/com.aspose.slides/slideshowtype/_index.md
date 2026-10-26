---
title: SlideShowType
second_title: Aspose.Slides voor Java API-referentie
description: Basis slide-showinstellingen.
type: docs
url: /nl/com.aspose.slides/slideshowtype/
---
**Erfenis:**
java.lang.Object
```
public abstract class SlideShowType
```

Basis slide-showinstellingen. Voorouders vertegenwoordigen typen van de dia-show: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Voorstelling door een spreker (volledig scherm) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Bekeken door een individu (venster) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Bekeken op een kiosk (volledig scherm)

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