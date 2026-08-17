---
title: SlideShowType
second_title: Aspose.Slides for Java API リファレンス
description: 基本的なスライドショー設定。
type: docs
url: /ja/com.aspose.slides/slideshowtype/
---
**継承:**
java.lang.Object
```
public abstract class SlideShowType
```

基本的なスライドショー設定です。先祖はスライドショーのタイプを表します: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) スピーカーが提示 (全画面) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) 個人が閲覧 (ウィンドウ) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) キオスクで閲覧 (全画面)

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
