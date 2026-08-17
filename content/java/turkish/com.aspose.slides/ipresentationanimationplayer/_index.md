---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Referansı
description: Animasyonun bir oynatıcısını temsil eder.
type: docs
url: /tr/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

Animasyonun bir oynatıcısını temsil eder.

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

[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) tarafından PresentationAnimationsGenerator.NewAnimation olayı aracılığıyla oluşturulan animasyonlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDuration()](#getDuration--) | Animasyon süresini [ms] olarak al |
| [setTimePosition(double time)](#setTimePosition-double-) | Süre içinde animasyon zaman konumunu ayarla (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Daha önce \#setTimePosition(double).setTimePosition(double) yöntemiyle ayarlanan mevcut zaman konumu için çerçeveyi al |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```


Animasyon süresini [ms] olarak al

**Döndürür:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```


Süre içinde animasyon zaman konumunu ayarla (\#getDuration.getDuration).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| time | double | Zaman konumu. |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```


Mevcut zaman konumu için daha önce \#setTimePosition(double).setTimePosition(double) yöntemiyle ayarlanan çerçeveyi al.

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Kare görüntüsü