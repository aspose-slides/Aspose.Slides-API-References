---
title: SlideShowType
second_title: Aspose.Slides for Java API Reference
description: Base slide show settings.
type: docs
weight: 511
url: /java/com.aspose.slides/slideshowtype/
---
**Inheritance:**
java.lang.Object
```
public abstract class SlideShowType
```

Base slide show settings. Ancestors represent types of the slide show: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Presented by a speaker (full screen) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Browsed by individual (window) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Browsed at a kiosk (full screen)

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
