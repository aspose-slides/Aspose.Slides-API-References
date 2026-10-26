---
title: BrowsedAtKiosk
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Được duyệt trên một kiosk ở chế độ toàn màn hình
type: docs
url: /vi/com.aspose.slides/browsedatkiosk/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedAtKiosk extends SlideShowType
```

Được duyệt trên một kiosk (toàn màn hình)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Các hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [BrowsedAtKiosk()](#BrowsedAtKiosk--) | Khởi tạo một thể hiện mới của lớp BrowsedAtKiosk. |
### BrowsedAtKiosk() {#BrowsedAtKiosk--}
```
public BrowsedAtKiosk()
```


Khởi tạo một thể hiện mới của lớp BrowsedAtKiosk.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```