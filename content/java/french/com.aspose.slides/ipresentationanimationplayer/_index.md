---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides pour Java – Référence de l'API
description: Représente un lecteur de l'animation.
type: docs
url: /fr/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Représente un lecteur de l'animation.

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

Animations générées par [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) via son événement PresentationAnimationsGenerator.NewAnimation.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getDuration()](#getDuration--) | Obtenir la durée de l'animation [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Définir la position temporelle de l'animation dans la Durée (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Obtenir la trame pour la position temporelle actuelle précédemment définie avec la méthode \#setTimePosition(double).setTimePosition(double). |

### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

Obtenir la durée de l'animation [ms]

**Retourne :**
double

### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

Définir la position temporelle de l'animation dans la Durée (\#getDuration.getDuration).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| time | double | Position temporelle. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

Obtenir la trame pour la position temporelle actuelle précédemment définie avec la méthode \#setTimePosition(double).setTimePosition(double).

**Retourne :**
[IImage](../../com.aspose.slides/iimage) - Image de la trame