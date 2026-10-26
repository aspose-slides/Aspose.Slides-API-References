---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides के लिए Android पर Java API रेफ़रेंस
description: एनिमेशन का प्लेयर दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

एनिमेशन का प्लेयर दर्शाता है।

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

एनिमेशन जो [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) द्वारा उसके PresentationAnimationsGenerator.NewAnimation इवेंट के माध्यम से उत्पन्न किए गए हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getDuration()](#getDuration--) | Get animation duration [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | Set the animation time position within the  Duration (\#getDuration.getDuration). |
| [getFrame()](#getFrame--) | Get the frame for the current time position previously set with the \#setTimePosition(double).setTimePosition(double) method. |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```

एनिमेशन की अवधि मिलिसेकंड में प्राप्त करें

**रिटर्न:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```

एनिमेशन की अवधि के भीतर समय स्थिति सेट करें (\#getDuration.getDuration).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| time | double | समय स्थिति। |
### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```

पिछले सेट किए गए \#setTimePosition(double).setTimePosition(double) मेथड से वर्तमान समय स्थिति के लिए फ्रेम प्राप्त करें।

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - फ़्रेम छवि