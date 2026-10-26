---
title: PresentedBySpeaker
second_title: Tham chiếu API Aspose.Slides cho Java
description: Được trình bày bởi người nói toàn màn hình
type: docs
url: /vi/com.aspose.slides/presentedbyspeaker/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Được trình bày bởi người nói (toàn màn hình)

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Khởi tạo một thể hiện mới của lớp PresentedBySpeaker. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```

Khởi tạo một thể hiện mới của lớp PresentedBySpeaker.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```