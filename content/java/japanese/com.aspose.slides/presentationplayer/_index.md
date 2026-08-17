---
title: PresentationPlayer
second_title: Aspose.Slides の Java API リファレンス
description: アニメーションに関連付けられたプレーヤーを表します。
type: docs
url: /ja/com.aspose.slides/presentationplayer/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
com.aspose.ms.System.IDisposable  
```
public class PresentationPlayer implements System.IDisposable
```

[Presentation](../../com.aspose.slides/presentation) に関連付けられたアニメーションのプレーヤーを表します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          // 33 FPSでアニメーションを再生
>          PresentationPlayer player33 = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player33.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("33fps/frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player33 != null) player33.dispose();
>          }
>          // 45 FPSでアニメーションを再生
>          PresentationPlayer player45 = new PresentationPlayer(animationsGenerator, 45);
>          try {
>              player45.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("45fps/frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player45 != null) player45.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PresentationPlayer(PresentationAnimationsGenerator generator, double fps)](#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-) | [PresentationPlayer](../../com.aspose.slides/presentationplayer) の新しいインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [dispose()](#dispose--) | [PresentationPlayer](../../com.aspose.slides/presentationplayer) のインスタンスを破棄します。 |
| [getFrameIndex()](#getFrameIndex--) | フレームインデックスを取得します。 |
| [setFrameTick(PresentationPlayer.FrameTick event)](#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-) | 新しいフレームティックイベントを設定します。 |
### PresentationPlayer(PresentationAnimationsGenerator generator, double fps) {#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-}
```
public PresentationPlayer(PresentationAnimationsGenerator generator, double fps)
```

[PresentationPlayer](../../com.aspose.slides/presentationplayer) の新しいインスタンスを作成します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| generator | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) | プレゼンテーション アニメーション ジェネレーター |
| fps | double | 秒あたりのフレーム数 (FPS) |

### dispose() {#dispose--}
```
public final void dispose()
```

[PresentationPlayer](../../com.aspose.slides/presentationplayer) のインスタンスを破棄します。

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```

フレームインデックスを取得します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
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
int
### setFrameTick(PresentationPlayer.FrameTick event) {#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public void setFrameTick(PresentationPlayer.FrameTick event)
```

新しいフレームティックイベントを設定します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
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

--------------------

[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) によって作成されたアニメーションの各フレームがプレーヤーによって生成されるときに発生します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| event | [FrameTick](../../com.aspose.slides/frametick) | フレームティックイベント。 |