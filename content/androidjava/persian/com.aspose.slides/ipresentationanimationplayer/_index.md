---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Android via Java API Reference
description: نماینده‌ای برای انیمیشن.
type: docs
url: /fa/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

نماینده‌ای برای انیمیشن.

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

انیمیشن‌ها توسط [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) از طریق رخداد PresentationAnimationsGenerator.NewAnimation تولید می‌شوند.

## متدها

| متد | توضیح |
| --- | --- |
| [getDuration()](#getDuration--) | دریافت مدت زمان انیمیشن [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | تنظیم موقعیت زمان انیمیشن در داخل مدت زمان (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | دریافت فریم برای موقعیت زمانی فعلی که قبلاً با متد \#setTimePosition(double).setTimePosition(double) تنظیم شده است. |
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

تنظیم موقعیت زمان انیمیشن در داخل مدت زمان (\#getDuration.getDuration).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| time | double | موقعیت زمان. |
### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

دریافت فریم برای موقعیت زمانی فعلی که قبلاً با متد \#setTimePosition(double).setTimePosition(double) تنظیم شده است.

**باز می‌گرداند:**
[IImage](../../com.aspose.slides/iimage) - تصویر فریم