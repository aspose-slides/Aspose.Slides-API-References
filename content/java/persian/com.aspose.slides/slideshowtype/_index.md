---
title: SlideShowType
second_title: مرجع API Aspose.Slides برای Java
description: تنظیمات پایه نمایش اسلاید.
type: docs
url: /fa/com.aspose.slides/slideshowtype/
---
**ارث‌بری:**
java.lang.Object
```
public abstract class SlideShowType
```

تنظیمات پایه نمایش اسلاید. اجداد نشان‌دهنده انواع نمایش اسلاید هستند: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) ارائه توسط سخنران (تمام صفحه) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) مرور توسط فرد (پنجره) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) مرور در کیوسک (تمام صفحه)

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