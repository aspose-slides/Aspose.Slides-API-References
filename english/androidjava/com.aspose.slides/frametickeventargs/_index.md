---
title: FrameTickEventArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Represents arguments of the PresentationPlayer.FrameTick event.
type: docs
weight: 218
url: /androidjava/com.aspose.slides/frametickeventargs/
---
**Inheritance:**
java.lang.Object
```
public class FrameTickEventArgs
```

Represents arguments of the PresentationPlayer.FrameTick event.

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
>                      FileOutputStream fos = null;
>                      try {
>                          fos = new FileOutputStream(String.format("frame_%d.png", frameNumber[0]++));
>                          args.getFrame().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>                      } catch (IOException e) {
>                          throw new RuntimeException(e);
>                      } finally {
>                          if (fos != null) {
>                              try {
>                                  fos.close();
>                              } catch (IOException e) {
>                                  e.printStackTrace();
>                              }
>                          }
>                      }
>                  }
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
## Methods

| Method | Description |
| --- | --- |
| [getPlayer()](#getPlayer--) | Get the presentation player |
| [getFrame()](#getFrame--) | Get the current [PresentationPlayer](../../com.aspose.slides/presentationplayer) frame. |
### getPlayer() {#getPlayer--}
```
public final PresentationPlayer getPlayer()
```


Get the presentation player

**Returns:**
[PresentationPlayer](../../com.aspose.slides/presentationplayer)
### getFrame() {#getFrame--}
```
public final Bitmap getFrame()
```


Get the current [PresentationPlayer](../../com.aspose.slides/presentationplayer) frame.

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
>                      FileOutputStream fos = null;
>                      try {
>                          fos = new FileOutputStream(String.format("frame_%d.png", frameNumber[0]++));
>                          args.getFrame().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>                      } catch (IOException e) {
>                          throw new RuntimeException(e);
>                      } finally {
>                          if (fos != null) {
>                              try {
>                                  fos.close();
>                              } catch (IOException e) {
>                                  e.printStackTrace();
>                              }
>                          }
>                      }
>                  }
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

**Returns:**
android.graphics.Bitmap
