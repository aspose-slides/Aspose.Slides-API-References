---
title: PresentedBySpeaker
second_title: Aspose.Slides 適用於 Android 透過 Java API 參考
description: 演講者呈現（全螢幕）
type: docs
url: /zh-hant/com.aspose.slides/presentedbyspeaker/
---
**繼承:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

演講者呈現（全螢幕）

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
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | 初始化 PresentedBySpeaker 類別的新執行個體。 |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```


初始化 PresentedBySpeaker 類別的新執行個體。

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