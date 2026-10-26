---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a player of the animation.
type: docs
url: /th/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

เป็นตัวเล่นของการแอนิเมชัน

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

การแอนิเมชันที่สร้างโดย [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) ผ่านเหตุการณ์ PresentationAnimationsGenerator.NewAnimation ของมัน.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDuration()](#getDuration--) | รับระยะเวลาการแอนิเมชัน [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | ตั้งตำแหน่งเวลาการแอนิเมชันภายใน Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | รับเฟรมสำหรับตำแหน่งเวลาปัจจุบันที่ตั้งไว้ก่อนหน้านี้ด้วยเมธอด \#setTimePosition(double).setTimePosition(double). |

### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

รับระยะเวลาการแอนิเมชัน [ms]

**คืนค่า:**
double

### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

ตั้งตำแหน่งเวลาการแอนิเมชันภายใน Duration (\#getDuration.getDuration).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| time | double | ตำแหน่งเวลา. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

รับเฟรมสำหรับตำแหน่งเวลาปัจจุบันที่ตั้งไว้ก่อนหน้านี้ด้วยเมธอด \#setTimePosition(double).setTimePosition(double) method.

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - ภาพเฟรม