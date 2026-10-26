---
title: SlideShowType
second_title: Aspose.Slides Android için Java API Referansı aracılığıyla
description: Temel slayt gösterisi ayarları.
type: docs
url: /tr/com.aspose.slides/slideshowtype/
---
**Kalıtım:**
java.lang.Object
```
public abstract class SlideShowType
```

Temel slayt gösterisi ayarları. Atalar, slayt gösterisi türlerini temsil eder: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Konuşmacı tarafından sunulur (tam ekran) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Birey tarafından görüntülenir (pencere) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Kiosk'ta görüntülenir (tam ekran)

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