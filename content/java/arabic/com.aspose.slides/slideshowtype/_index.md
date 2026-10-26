---
title: SlideShowType
second_title: Aspose.Slides لـ Java مرجع API
description: إعدادات عرض الشرائح الأساسية.
type: docs
url: /ar/com.aspose.slides/slideshowtype/
---
**الوراثة:**
java.lang.Object
```
public abstract class SlideShowType
```

إعدادات عرض الشرائح الأساسية. تمثل الأجداد أنواع عرض الشرائح: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) عرض بواسطة متحدث (ملء الشاشة) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) تصفح بواسطة فرد (نافذة) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) تصفح في كشك (ملء الشاشة)

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