---
title: FrameTickEventArgs
second_title: Aspose.Slides για την Java API Αναφορά
description: Αναπαριστά τα επιχειρήματα του γεγονότος PresentationPlayer.FrameTick.
type: docs
url: /el/com.aspose.slides/frametickeventargs/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class FrameTickEventArgs
```

Αντιπροσωπεύει τα επιχειρήματα του γεγονότος PresentationPlayer.FrameTick.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              final int[] frameNumber = {0};
>              player.setFrameTick((sender, args) -> {
>                  args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
>              });
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

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPlayer()](#getPlayer--) | Λαμβάνει τον παίκτη παρουσίασης |
| [getFrame()](#getFrame--) | Λαμβάνει το τρέχον [PresentationPlayer](../../com.aspose.slides/presentationplayer) πλαίσιο. |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


Λαμβάνει τον παίκτη παρουσίασης

**Επιστρέφει:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```


Λαμβάνει το τρέχον [PresentationPlayer](../../com.aspose.slides/presentationplayer) πλαίσιο.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              final int[] frameNumber = {0};
>              player.setFrameTick((sender, args) -> {
>                  args.getFrame().save(String.format("frame_%d.png", frameNumber[0]++));
>              });
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

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage)