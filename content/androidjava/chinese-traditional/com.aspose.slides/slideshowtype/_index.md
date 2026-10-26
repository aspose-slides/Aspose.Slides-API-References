---
title: SlideShowType
second_title: Aspose.Slides for Android via Java API 參考文件
description: 基本投影片放映設定。
type: docs
url: /zh-hant/com.aspose.slides/slideshowtype/
---
**繼承:**
java.lang.Object
```
public abstract class SlideShowType
```

基本投影片放映設定。祖先代表投影片放映的類型: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) 由講者呈現（全螢幕） [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) 個人瀏覽（視窗） [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) 在資訊站瀏覽（全螢幕）

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