---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Reference
description: Represents a player of the animation.
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
>          animationsGenerator.setNewAnimation(animationPlayer -> {
>              System.out.println(String.format("Animation total duration: %f", animationPlayer.getDuration()));
>              animationPlayer.setTimePosition(0);
>              animationPlayer.getFrame().save("firstFrame.png");
> 
>              animationPlayer.setTimePosition(animationPlayer.getDuration());
>              animationPlayer.getFrame().save("lastFrame.png");
>          });
>          animationsGenerator.run(presentation.getSlides());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


--------------------

[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) によって、その PresentationAnimationsGenerator.NewAnimation イベントを通じて生成されたアニメーション。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDuration()](#getDuration--) | アニメーションの期間を取得します [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | アニメーションの時間位置を期間内に設定します (\#getDuration.getDuration)。 |
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

アニメーションの時間位置を期間内に設定します (\#getDuration.getDuration)。

**パラメーター:**
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