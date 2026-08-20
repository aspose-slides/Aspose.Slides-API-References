---
title: PresentedBySpeaker
second_title: Aspose.Slides for Java API 參考
description: 由演講者全螢幕呈現
type: docs
url: /zh-hant/com.aspose.slides/presentedbyspeaker/
---
**繼承：**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

由演講者呈現（全螢幕）

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
## 建構子

| 建構子 | 說明 |
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