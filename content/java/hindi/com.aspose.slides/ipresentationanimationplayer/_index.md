---
title: IPresentationAnimationPlayer
second_title: Aspose.Slides for Java API Reference
description: एनीमेशन का एक प्लेयर दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ipresentationanimationplayer/
---```
public interface IPresentationAnimationPlayer
```

एनीमेशन का एक प्लेयर दर्शाता है।

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

[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) द्वारा उसके PresentationAnimationsGenerator.NewAnimation इवेंट के माध्यम से उत्पन्न एनीमेशन।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getDuration()](#getDuration--) | एनीमेशन अवधि प्राप्त करें [ms] |
| [setTimePosition(double time)](#setTimePosition-double-) | एनीमेशन समय स्थिति को अवधि (\#getDuration.getDuration) के भीतर सेट करें। |
| [getFrame()](#getFrame--) | पहले \#setTimePosition(double).setTimePosition(double) विधि द्वारा सेट की गई वर्तमान समय स्थिति के लिए फ्रेम प्राप्त करें। |
### getDuration() {#getDuration--}
```
public abstract double getDuration()
```


एनीमेशन अवधि प्राप्त करें [ms]

**रिटर्न:**
double
### setTimePosition(double time) {#setTimePosition-double-}
```
public abstract void setTimePosition(double time)
```


एनीमेशन समय स्थिति को अवधि (\#getDuration.getDuration) के भीतर सेट करें。

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| time | double | समय स्थिति। |

### getFrame() {#getFrame--}
```
public abstract IImage getFrame()
```


पहले \#setTimePosition(double).setTimePosition(double) विधि द्वारा सेट की गई वर्तमान समय स्थिति के लिए फ्रेम प्राप्त करें।

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - फ़्रेम छवि