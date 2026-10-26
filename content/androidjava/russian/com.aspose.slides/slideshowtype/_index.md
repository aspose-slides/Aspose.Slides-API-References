---
title: SlideShowType
second_title: Aspose.Slides для Android через справочник Java API
description: Базовые настройки слайдшоу.
type: docs
url: /ru/com.aspose.slides/slideshowtype/
---
**Наследование:**
java.lang.Object
```
public abstract class SlideShowType
```

Базовые настройки слайдшоу. Потомки представляют типы слайдшоу: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Предоставлено спикером (полный экран) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Просмотрено индивидуально (окно) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Просмотрено в киоске (полный экран)

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