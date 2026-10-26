---
title: SlideShowType
second_title: Aspose.Slides för Android via Java API-referens
description: Grundläggande inställningar för bildspelet.
type: docs
url: /sv/com.aspose.slides/slideshowtype/
---
**Arv:**
java.lang.Object
```
public abstract class SlideShowType
```

Basinställningar för bildspelet. Förfäder representerar typer av bildspelet: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Visas av en talare (helskärm) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Bläddras av en individ (fönster) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Bläddras på en kiosk (helskärm)

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
