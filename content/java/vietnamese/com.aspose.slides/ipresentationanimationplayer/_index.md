---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Reference
description: Represents a player of the animation.
type: docs
url: /vi/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Biểu diễn một trình phát hoạt ảnh.

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

Các hoạt ảnh được tạo bởi [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) thông qua sự kiện PresentationAnimationsGenerator.NewAnimation của nó.
## Phương thức

| Method | Description |
| --- | --- |
| [getDuration()](#getDuration--) | Lấy thời lượng hoạt ảnh [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Đặt vị trí thời gian của hoạt ảnh trong Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Lấy khung hình cho vị trí thời gian hiện tại đã được đặt trước đó bằng phương thức \#setTimePosition(double).setTimePosition(double). |

### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

Lấy thời lượng hoạt ảnh [ms]

**Trả về:**
double

### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

Đặt vị trí thời gian của hoạt ảnh trong Duration (\#getDuration.getDuration).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| time | double | Vị trí thời gian. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

Lấy khung hình cho vị trí thời gian hiện tại đã được đặt trước đó bằng phương thức \#setTimePosition(double).setTimePosition(double).

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Hình ảnh khung