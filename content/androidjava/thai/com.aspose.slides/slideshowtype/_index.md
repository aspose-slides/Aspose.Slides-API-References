---
title: SlideShowType
second_title: อ้างอิง API ของ Java สำหรับ Aspose.Slides บน Android
description: การตั้งค่าการแสดงสไลด์พื้นฐาน.
type: docs
url: /th/com.aspose.slides/slideshowtype/
---
**สืบทอด:**
java.lang.Object
```
public abstract class SlideShowType
```

การตั้งค่าการแสดงสไลด์พื้นฐาน. บรรพบุรุษเป็นตัวแทนประเภทของการแสดงสไลด์: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) แสดงโดยผู้บรรยาย (เต็มหน้าจอ) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) แสดงโดยบุคคล (หน้าต่าง) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) แสดงที่คีออส (เต็มหน้าจอ)

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