---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Reference
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

Animaciones generadas por [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) a través de su evento PresentationAnimationsGenerator.NewAnimation event.
## Métodos

| Método | Descripción |
| --- | --- |
| [getDuration()](#getDuration--) | Obtiene la duración de la animación [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Establece la posición de tiempo de la animación dentro de la Duración (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Obtiene el fotograma para la posición de tiempo actual previamente establecida con el método \#setTimePosition(double).setTimePosition(double) method. |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

Obtiene la duración de la animación [ms]

**Devuelve:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

Establece la posición de tiempo de la animación dentro de la Duración (\#getDuration.getDuration).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| time | double | Posición de tiempo. |
### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

Obtiene el fotograma para la posición de tiempo actual previamente establecida con el método \#setTimePosition(double).setTimePosition(double) method.

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Imagen del fotograma