---
title: SlideShowType
second_title: Aspose.Slides - dokumentacja API dla Javy
description: Podstawowe ustawienia pokazu slajdów.
type: docs
url: /pl/com.aspose.slides/slideshowtype/
---
**Dziedziczenie:**
java.lang.Object
```
public abstract class SlideShowType
```

Podstawowe ustawienia pokazu slajdów. Poprzednicy reprezentują typy pokazu slajdów: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Prezentowany przez prelegenta (pełny ekran) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Przeglądany przez indywidualnego użytkownika (okno) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Przeglądany w kiosku (pełny ekran)

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