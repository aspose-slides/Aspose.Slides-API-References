---
title: SlideShowType
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: إعدادات عرض الشرائح الأساسية.
type: docs
url: /ar/com.aspose.slides/slideshowtype/
---
**الوراثة:**
java.lang.Object
```
public abstract class SlideShowType
```

إعدادات عرض الشرائح الأساسية. تمثل الأسلاف أنواع عرض الشرائح: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) مُقدَّم من قبل متحدث (ملء الشاشة) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) تم تصفحه بواسطة فرد (نافذة) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) تم تصفحه في كشك (ملء الشاشة)

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