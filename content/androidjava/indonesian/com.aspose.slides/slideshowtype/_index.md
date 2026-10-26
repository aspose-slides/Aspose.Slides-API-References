---
title: SlideShowType
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Pengaturan dasar pertunjukan slide.
type: docs
url: /id/com.aspose.slides/slideshowtype/
---
**Pewarisan:**
java.lang.Object
```
public abstract class SlideShowType
```

Pengaturan dasar pertunjukan slide. Ancestor mewakili tipe pertunjukan slide: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Ditampilkan oleh pembicara (layar penuh) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Dilihat oleh individu (jendela) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Dilihat di kiosk (layar penuh)

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
