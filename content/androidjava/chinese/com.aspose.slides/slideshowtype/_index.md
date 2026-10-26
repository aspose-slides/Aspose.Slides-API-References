---
title: SlideShowType
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 基本幻灯片放映设置。
type: docs
url: /zh/com.aspose.slides/slideshowtype/
---
**继承:**  
java.lang.Object  
```
public abstract class SlideShowType
```

基本幻灯片放映设置。祖先表示幻灯片放映的类型：[PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) 由演讲者呈现（全屏） [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) 个人浏览（窗口） [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) 在自助终端浏览（全屏）

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