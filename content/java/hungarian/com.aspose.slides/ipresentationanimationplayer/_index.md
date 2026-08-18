---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Reference
description: Az animáció lejátszóját reprezentálja.
type: docs
url: /hu/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Az animáció lejátszóját reprezentálja.

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

Az [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) által generált animációk a PresentationAnimationsGenerator.NewAnimation eseményen keresztül.
## Metódusok

| Method | Description |
| --- | --- |
| [getDuration()](#getDuration--) | Az animáció időtartamának lekérése [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Beállítja az animáció időpozícióját a Duration (\#getDuration.getDuration) belül. |
| [getFrame()](#getFrame--) | Lekéri az aktuális időpozícióhoz tartozó képkockát, amelyet korábban a \#setTimePosition(double).setTimePosition(double) metódussal állított be. |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```


Az animáció időtartamának lekérése [ms]

**Visszatérési érték:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```


Beállítja az animáció időpozícióját a Duration (\#getDuration.getDuration) belül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| time | double | Időpozíció. |
### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```


Lekéri az aktuális időpozícióhoz tartozó képkockát, amelyet korábban a \#setTimePosition(double).setTimePosition(double) metódussal állított be.

**Visszatérési érték:**
[IImage](../../com.aspose.slides/iimage) - Képkocka kép