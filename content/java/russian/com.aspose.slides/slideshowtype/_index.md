---
title: SlideShowType
second_title: Aspose.Slides для Java — справка по API
description: Базовые настройки слайд-шоу.
type: docs
url: /ru/com.aspose.slides/slideshowtype/
---
**Наследование:**
java.lang.Object
```
public abstract class SlideShowType
```

Базовые настройки слайд-шоу. Предки представляют типы слайд-шоу: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Представляется спикером (полный экран) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Просматривается индивидуально (окно) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Просматривается в киоске (полный экран)

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