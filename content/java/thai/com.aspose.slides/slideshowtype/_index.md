---
title: SlideShowType
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: การตั้งค่าการแสดงสไลด์พื้นฐาน.
type: docs
url: /th/com.aspose.slides/slideshowtype/
---
**การสืบทอด:**
java.lang.Object
```
public abstract class SlideShowType
```

การตั้งค่าการแสดงสไลด์พื้นฐาน. ตัวชี้บรรพบุรุษแสดงประเภทของการแสดงสไลด์: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) แสดงโดยผู้พูด (เต็มหน้าจอ) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) เรียกดูโดยบุคคล (หน้าต่าง) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) เรียกดูในคีออส (เต็มหน้าจอ)

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