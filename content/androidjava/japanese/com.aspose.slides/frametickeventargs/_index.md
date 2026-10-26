---
title: FrameTickEventArgs
second_title: Aspose.Slides for Android の Java API リファレンス
description: PresentationPlayer.FrameTick イベントの引数を表します。
type: docs
url: /ja/com.aspose.slides/frametickeventargs/
---
**継承:**
java.lang.Object
```
public class FrameTickEventArgs
```

PresentationPlayer.FrameTick イベントの引数を表します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              final int[] frameNumber = {0};
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
>              }});
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPlayer()](#getPlayer--) | プレゼンテーション プレーヤーを取得します |
| [getFrame()](#getFrame--) | 現在の [PresentationPlayer](../../com.aspose.slides/presentationplayer) フレームを取得します |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


プレゼンテーション プレーヤーを取得します

**戻り値:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```


現在の [PresentationPlayer](../../com.aspose.slides/presentationplayer) フレームを取得します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              final int[] frameNumber = {0};
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
>              }});
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[IImage](../../com.aspose.slides/iimage)