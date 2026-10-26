---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu thị một trình phát hoạt ảnh.
type: docs
url: /vi/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Biểu thị một trình phát hoạt ảnh.

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

Hoạt ảnh được tạo bởi [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) thông qua sự kiện PresentationAnimationsGenerator.NewAnimation của nó.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getDuration()](#getDuration--) | Lấy thời lượng hoạt ảnh [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Đặt vị trí thời gian của hoạt ảnh trong Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Lấy khung cho vị trí thời gian hiện tại đã được đặt trước đó bằng phương thức \#setTimePosition(double).setTimePosition(double) method. |
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


Lấy khung cho vị trí thời gian hiện tại đã được đặt trước đó bằng phương thức \#setTimePosition(double).setTimePosition(double).

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Hình khung