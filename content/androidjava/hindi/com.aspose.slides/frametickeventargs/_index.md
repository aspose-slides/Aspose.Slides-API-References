---
title: FrameTickEventArgs
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: PresentationPlayer.FrameTick इवेंट के तर्क का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/frametickeventargs/
---
**विरासत:**
java.lang.Object
```
public class FrameTickEventArgs
```

PresentationPlayer.FrameTick इवेंट के तर्क का प्रतिनिधित्व करता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              final int[] frameNumber = {0};
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
>              }});
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## विधियां

| मेथड | विवरण |
| --- | --- |
| [getPlayer()](#getPlayer--) | प्रेजेंटेशन प्लेयर प्राप्त करें |
| [getFrame()](#getFrame--) | वर्तमान [PresentationPlayer](../../com.aspose.slides/presentationplayer) फ्रेम प्राप्त करें। |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```

प्रेजेंटेशन प्लेयर प्राप्त करें

**रिटर्न्स:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```

वर्तमान [PresentationPlayer](../../com.aspose.slides/presentationplayer) फ्रेम प्राप्त करें।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              final int[] frameNumber = {0};
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
>              }});
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न्स:**
[IImage](../../com.aspose.slides/iimage)