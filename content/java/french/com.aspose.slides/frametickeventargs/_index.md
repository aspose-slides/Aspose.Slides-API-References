---
title: FrameTickEventArgs
second_title: Aspose.Slides pour Java Référence de l'API
description: Représente les arguments de l'événement PresentationPlayer.FrameTick.
type: docs
url: /fr/com.aspose.slides/frametickeventargs/
---
**Héritage:**  
java.lang.Object  
```
public class FrameTickEventArgs
```

Représente les arguments de l'événement PresentationPlayer.FrameTick.

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

## Méthodes

| Méthode | Description |
| --- | --- |
| [getPlayer()](#getPlayer--) | Obtient le lecteur de présentation |
| [getFrame()](#getFrame--) | Obtient la trame [PresentationPlayer](../../com.aspose.slides/presentationplayer) actuelle. |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```

Obtient le lecteur de présentation

**Renvoie:**  
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```

Obtient la trame [PresentationPlayer](../../com.aspose.slides/presentationplayer) actuelle.

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


**Renvoie:**  
[IImage](../../com.aspose.slides/iimage)