---
title: FrameTickEventArgs
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa os argumentos do evento PresentationPlayer.FrameTick.
type: docs
url: /pt/com.aspose.slides/frametickeventargs/
---
**Herança:**
java.lang.Object
```
public class FrameTickEventArgs
```

Representa os argumentos do evento PresentationPlayer.FrameTick.

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

## Métodos

| Método | Descrição |
| --- | --- |
| [getPlayer()](#getPlayer--) | Obter o reprodutor de apresentação |
| [getFrame()](#getFrame--) | Obter o quadro atual [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


Obter o reprodutor de apresentação

**Retorna:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final IImage getFrame()
```


Obter o quadro atual [PresentationPlayer](../../com.aspose.slides/presentationplayer).

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


**Retorna:**
[IImage](../../com.aspose.slides/iimage)