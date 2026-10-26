---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Reference
description: Mewakili pemutar animasi.
type: docs
url: /id/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Mewakili pemutar animasi.

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

Animasi yang dihasilkan oleh [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) melalui peristiwa PresentationAnimationsGenerator.NewAnimation.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDuration()](#getDuration--) | Mendapatkan durasi animasi [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Atur posisi waktu animasi dalam Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Dapatkan frame untuk posisi waktu saat ini yang sebelumnya diatur dengan metode \#setTimePosition(double).setTimePosition(double). |

### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

Dapatkan durasi animasi [ms]

**Mengembalikan:**
double

### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

Atur posisi waktu animasi dalam Duration (\#getDuration.getDuration).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| time | double | Posisi waktu. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

Dapatkan frame untuk posisi waktu saat ini yang sebelumnya diatur dengan metode \#setTimePosition(double).setTimePosition(double).

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - gambar frame