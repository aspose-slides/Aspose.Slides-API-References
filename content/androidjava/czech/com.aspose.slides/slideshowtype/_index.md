---
title: SlideShowType
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Základní nastavení prezentace.
type: docs
url: /cs/com.aspose.slides/slideshowtype/
---
**Dědičnost:**
java.lang.Object
```
public abstract class SlideShowType
```

Základní nastavení prezentace. Předci představují typy prezentace: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Prezentováno přednášejícím (celá obrazovka) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Prohlíženo jednotlivcem (okno) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Prohlíženo na kiosku (celá obrazovka)

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