---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a player of the animation.
type: docs
url: /el/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Αναπαριστά ένα πρόγραμμα αναπαραγωγής της κίνησης.

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

Κινήσεις που δημιουργήθηκαν από [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) μέσω του γεγονότος PresentationAnimationsGenerator.NewAnimation.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDuration()](#getDuration--) | Λαμβάνει τη διάρκεια της κίνησης [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Ορίζει τη θέση χρόνου της κίνησης εντός της Διάρκειας (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Λαμβάνει το πλαίσιο για τη τρέχουσα θέση χρόνου που έχει οριστεί προηγουμένως με τη μέθοδο \#setTimePosition(double).setTimePosition(double). |

### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

Λαμβάνει τη διάρκεια της κίνησης [ms]

**Επιστρέφει:**
double

### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

Ορίζει τη θέση χρόνου της κίνησης εντός της Διάρκειας (\#getDuration.getDuration).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| time | double | Θέση χρόνου. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

Λαμβάνει το πλαίσιο για τη τρέχουσα θέση χρόνου που έχει οριστεί προηγουμένως με τη μέθοδο \#setTimePosition(double).setTimePosition(double).

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Εικόνα πλαισίου