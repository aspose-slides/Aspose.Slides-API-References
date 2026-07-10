---
title: PresentedBySpeaker
second_title: Aspose.Slides for Android via Java API 参考
description: 由演讲者全屏呈现
type: docs
url: /zh/com.aspose.slides/presentedbyspeaker/
---
**继承：**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

由演讲者呈现（全屏）

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres == null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Initializes a new instance of the PresentedBySpeaker class. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()

初始化 PresentedBySpeaker 类的新实例。

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