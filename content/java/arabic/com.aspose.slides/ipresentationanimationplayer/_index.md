---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides لمرجع API Java
description: يمثل مشغلًا للرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

يمثل مشغلًا للرسوم المتحركة.

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

الرسوم المتحركة التي تم إنشاؤها بواسطة [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) عبر حدث PresentationAnimationsGenerator.NewAnimation الخاص به.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDuration()](#getDuration--) | الحصول على مدة الرسوم المتحركة [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | تعيين موضع وقت الرسوم المتحركة داخل المدة (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | الحصول على الإطار للموضع الزمني الحالي الذي تم تعيينه مسبقًا باستخدام طريقة \#setTimePosition(double).setTimePosition(double). |

### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

الحصول على مدة الرسوم المتحركة [ms]

**القيمة المرتجعة:**
double

### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

تعيين موضع وقت الرسوم المتحركة داخل المدة (\#getDuration.getDuration).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| time | double | موضع الوقت. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

الحصول على الإطار للموضع الزمني الحالي الذي تم تعيينه مسبقًا باستخدام طريقة \#setTimePosition(double).setTimePosition(double).

**القيمة المرتجعة:**
[IImage](../../com.aspose.slides/iimage) - صورة الإطار