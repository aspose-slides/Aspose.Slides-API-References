---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a player of the animation.
type: docs
url: /es/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Representa un reproductor de la animación.

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

Animaciones generadas por [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) a través de su evento PresentationAnimationsGenerator.NewAnimation.

## Métodos

| Método | Descripción |
| --- | --- |
| [getDuration()](#getDuration--) | Obtener la duración de la animación [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Establecer la posición temporal de la animación dentro de la Duración (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Obtener el fotograma para la posición temporal actual previamente establecida con el método \#setTimePosition(double).setTimePosition(double). |

### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

Obtener la duración de la animación [ms]

**Devuelve:**
double

### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

Establecer la posición temporal de la animación dentro de la Duración (\#getDuration.getDuration).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| time | double | Posición de tiempo. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

Obtener el fotograma para la posición temporal actual previamente establecida con el método \#setTimePosition(double).setTimePosition(double).

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Imagen del fotograma