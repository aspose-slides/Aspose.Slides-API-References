---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Android via Java API Reference
description: يمثل مشغلاً للرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

يمثل مشغلاً للرسوم المتحركة.

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

الرسوم المتحركة التي تم إنشاؤها بواسطة [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) عبر حدث PresentationAnimationsGenerator.NewAnimation الخاص به.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDuration()](#getDuration--) | Get animation duration [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Set the animation time position within the  Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Get the frame for the current time position previously set with the \#setTimePosition(double).setTimePosition(double) method. |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

الحصول على مدة الرسوم المتحركة [ms]

**القيمة المرجعة:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

ضبط موضع وقت الرسوم المتحركة داخل المدة (\#getDuration.getDuration).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| time | double | موضع الوقت. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

الحصول على الإطار للموضع الزمني الحالي الذي تم ضبطه مسبقًا باستخدام طريقة \#setTimePosition(double).setTimePosition(double).

**القيمة المرجعة:**
[IImage](../../com.aspose.slides/iimage) - صورة الإطار