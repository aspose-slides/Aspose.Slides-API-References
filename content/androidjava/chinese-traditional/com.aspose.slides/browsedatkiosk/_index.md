---
title: BrowsedAtKiosk
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 在資訊站點上全螢幕瀏覽
type: docs
url: /zh-hant/com.aspose.slides/browsedatkiosk/
---
**繼承:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedAtKiosk extends SlideShowType
```

在資訊站點上瀏覽（全螢幕）

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
## 建構子

| 建構子 | 描述 |
| --- | --- |
| [BrowsedAtKiosk()](#BrowsedAtKiosk--) | 初始化 BrowsedAtKiosk 類別的新執行個體。 |
### BrowsedAtKiosk() {#BrowsedAtKiosk--}
```
public BrowsedAtKiosk()
```


初始化 BrowsedAtKiosk 類別的新執行個體。

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