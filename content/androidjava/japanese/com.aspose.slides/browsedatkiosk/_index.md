---
title: BrowsedAtKiosk
second_title: Java APIリファレンスによるAndroid向けAspose.Slides
description: キオスクで全画面表示
type: docs
url: /ja/com.aspose.slides/browsedatkiosk/
---
**継承:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedAtKiosk extends SlideShowType
```

キオスクで閲覧（全画面）

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

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BrowsedAtKiosk()](#BrowsedAtKiosk--) | BrowsedAtKiosk クラスの新しいインスタンスを初期化します。 |
### BrowsedAtKiosk() {#BrowsedAtKiosk--}
```
public BrowsedAtKiosk()
```

BrowsedAtKiosk クラスの新しいインスタンスを初期化します。

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