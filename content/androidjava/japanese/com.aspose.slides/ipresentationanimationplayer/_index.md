---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Android via Java API Reference
description: アニメーションのプレーヤーを表します。
type: docs
url: /ja/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

アニメーションのプレーヤーを表します。

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      {
>          animationsGenerator.setNewAnimation(new PresentationAnimationsGenerator.NewAnimation() {
>              public void invoke(IPresentationAnimationPlayer animationPlayer) {
>                  System.out.println(String.format("Animation total duration: %f", animationPlayer.getDuration()));
>                  animationPlayer.setTimePosition(0);
>                  animationPlayer.getFrame().save("firstFrame.png");
> 
>                  animationPlayer.setTimePosition(animationPlayer.getDuration());
>                  animationPlayer.getFrame().save("lastFrame.png");
>          }});
>          animationsGenerator.run(presentation.getSlides());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) によって生成されたアニメーション。PresentationAnimationsGenerator.NewAnimation イベントを介しています。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDuration()](#getDuration--) | アニメーションの期間を取得します [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Duration 内のアニメーション時間位置を設定します（\#getDuration.getDuration）。 |
| [getFrame()](#getFrame--) | 以前に \#setTimePosition(double).setTimePosition(double) メソッドで設定された現在の時間位置のフレームを取得します。 |

### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

アニメーションの期間を取得します [ms]

**戻り値:**
double

### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

Duration 内のアニメーション時間位置を設定します（\#getDuration.getDuration）。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| time | double | 時間位置。 |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

以前に \#setTimePosition(double).setTimePosition(double) メソッドで設定された現在の時間位置のフレームを取得します。

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - フレーム画像