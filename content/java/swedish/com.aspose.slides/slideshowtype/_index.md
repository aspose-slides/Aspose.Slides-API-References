---
title: SlideShowType
second_title: Aspose.Slides för Java API-referens
description: Grundläggande bildspelsinställningar.
type: docs
url: /sv/com.aspose.slides/slideshowtype/
---
**Arv:**
java.lang.Object
```
public abstract class SlideShowType
```

Grundläggande bildspelsinställningar. Förfäder representerar typer av bildspelet: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Presenteras av en talare (fullskärm) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Bläddras av en individ (fönster) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Bläddras på en kiosk (fullskärm)

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