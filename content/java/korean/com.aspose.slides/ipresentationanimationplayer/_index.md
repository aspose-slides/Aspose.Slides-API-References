---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Reference
description: Represents a player of the animation.
type: docs
url: /ko/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

애니메이션 플레이어를 나타냅니다.

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

[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator)에 의해 생성된 애니메이션은 해당 PresentationAnimationsGenerator.NewAnimation 이벤트를 통해 발생합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDuration()](#getDuration--) | Get animation duration [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Set the animation time position within the  Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Get the frame for the current time position previously set with the \#setTimePosition(double).setTimePosition(double) method. |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

애니메이션 지속 시간 [ms] 가져오기

**반환값:**  
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

애니메이션 시간 위치를 지속 시간 내에 설정합니다 (\#getDuration.getDuration).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| time | double | 시간 위치. |
### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

이전에 \#setTimePosition(double).setTimePosition(double) 메서드로 설정된 현재 시간 위치에 대한 프레임을 가져옵니다.

**반환값:**  
[IImage](../../com.aspose.slides/iimage) - 프레임 이미지