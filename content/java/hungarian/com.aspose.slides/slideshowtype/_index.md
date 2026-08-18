---
title: SlideShowType
second_title: Aspose.Slides for Java API referencia
description: Alapvető diavetítés beállítások.
type: docs
url: /hu/com.aspose.slides/slideshowtype/
---
**Öröklődés:**
java.lang.Object
```
public abstract class SlideShowType
```

Alapvető diavetítés beállítások. Az ősök a diavetítés típusait képviselik: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Előadó által bemutatott (teljes képernyő) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Felhasználó által böngészve (ablak) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Kioszkban böngészve (teljes képernyő)

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