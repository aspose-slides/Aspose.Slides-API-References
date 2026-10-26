---
title: SlideShowType
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: تنظیمات پایه نمایش اسلاید.
type: docs
url: /fa/com.aspose.slides/slideshowtype/
---
**ارث‌بری:**
java.lang.Object
```
public abstract class SlideShowType
```

تنظیمات پایه نمایش اسلاید. پیشینی‌ها انواع نمایش اسلاید را نشان می‌دهند: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) ارائه شده توسط سخنران (تمام صفحه) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) مشاهده توسط فرد (پنجره) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) مشاهده در کیوسک (تمام صفحه)

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