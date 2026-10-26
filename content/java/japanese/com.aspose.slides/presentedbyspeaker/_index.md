---
title: PresentedBySpeaker
second_title: Aspose.Slides for Java API リファレンス
description: スピーカーによる全画面表示
type: docs
url: /ja/com.aspose.slides/presentedbyspeaker/
---
**継承:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

スピーカーによって提示 (全画面)

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
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | PresentedBySpeaker クラスの新しいインスタンスを初期化します。 |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```


PresentedBySpeaker クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```