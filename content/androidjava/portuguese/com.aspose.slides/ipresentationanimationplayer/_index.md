---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um player da animação.
type: docs
url: /pt/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Representa um player da animação.

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

Animações geradas por [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) via seu evento PresentationAnimationsGenerator.NewAnimation.

## Métodos

| Método | Descrição |
| --- | --- |
| [getDuration()](#getDuration--) | Obter a duração da animação [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Definir a posição de tempo da animação dentro da Duração (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Obter o quadro para a posição de tempo atual previamente definido com o método \#setTimePosition(double).setTimePosition(double). |

### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

Obter a duração da animação [ms]

**Returns:**
double

### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

Definir a posição de tempo da animação dentro da Duração (\#getDuration.getDuration).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| time | double | Posição de tempo. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

Obter o quadro para a posição de tempo atual previamente definido com o método \#setTimePosition(double).setTimePosition(double).

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Imagem do quadro