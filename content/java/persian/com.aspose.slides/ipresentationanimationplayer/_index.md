---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Reference
description: Represents a player of the animation.
type: docs
url: /fa/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

نشان‌دهنده یک پخش‌کنندهٔ انیمیشن است.

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

انیمیشن‌ها توسط [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) از طریق رویداد PresentationAnimationsGenerator.NewAnimation تولید می‌شوند.

## متدها

| متد | توضیح |
| --- | --- |
| [getDuration()](#getDuration--) | دریافت مدت زمان انیمیشن [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | تنظیم موقعیت زمانی انیمیشن درون مدت زمان (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | دریافت فریم برای موقعیت زمانی فعلی که پیش از آن با متد \#setTimePosition(double).setTimePosition(double) تنظیم شده است. |

### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

دریافت مدت زمان انیمیشن [ms]

**باز می‌گرداند:**
double

### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

تنظیم موقعیت زمانی انیمیشن درون مدت زمان (\#getDuration.getDuration).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| time | double | موقعیت زمانی. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

دریافت فریم برای موقعیت زمانی فعلی که پیش از آن با متد \#setTimePosition(double).setTimePosition(double) تنظیم شده است.

**باز می‌گرداند:**
[IImage](../../com.aspose.slides/iimage) - تصویر فریم