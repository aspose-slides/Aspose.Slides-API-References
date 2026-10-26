---
title: SlideShowType
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cài đặt trình chiếu cơ bản.
type: docs
url: /vi/com.aspose.slides/slideshowtype/
---
**Kế thừa:**
java.lang.Object
```
public abstract class SlideShowType
```

Cài đặt trình chiếu cơ bản. Các tổ tiên đại diện cho các loại trình chiếu: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) Được trình bày bởi một người thuyết trình (toàn màn hình) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) Được xem bởi cá nhân (cửa sổ) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) Được xem tại kios (toàn màn hình)

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