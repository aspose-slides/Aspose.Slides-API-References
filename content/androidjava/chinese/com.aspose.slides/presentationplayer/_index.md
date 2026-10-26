---
title: PresentationPlayer
second_title: Aspose.Slides for Android via Java API 参考
description: 表示与 . 关联的动画播放器。
type: docs
url: /zh/com.aspose.slides/presentationplayer/
---
**继承：**
java.lang.Object

**所有已实现的接口：**
com.aspose.ms.System.IDisposable
```
public class PresentationPlayer implements System.IDisposable
```

表示与 [Presentation](../../com.aspose.slides/presentation) 相关的动画播放器。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          // Play animation with 33 FPS
>          PresentationPlayer player33 = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player33.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      FileOutputStream fos = null;
>                      try {
>                          fos = new FileOutputStream("33fps/frame_" + sender.getFrameIndex() + ".png");
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
>              if (player33 != null) player33.dispose();
>          }
>          // Play animation with 45 FPS
>          PresentationPlayer player45 = new PresentationPlayer(animationsGenerator, 45);
>          try {
>              player45.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      FileOutputStream fos = null;
>                      try {
>                          fos = new FileOutputStream("45fps/frame_" + sender.getFrameIndex() + ".png");
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
>              if (player45 != null) player45.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationPlayer(PresentationAnimationsGenerator generator, double fps)](#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-) | Creates new instance of the [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
## Methods

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) | Disposes the instance of the [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
| [getFrameIndex()](#getFrameIndex--) | Gets the frame index. |
| [setFrameTick(PresentationPlayer.FrameTick event)](#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-) | Set a new frame tick event. |
### PresentationPlayer(PresentationAnimationsGenerator generator, double fps) {#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-}
```
public PresentationPlayer(PresentationAnimationsGenerator generator, double fps)
```


Creates new instance of the [PresentationPlayer](../../com.aspose.slides/presentationplayer).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) | Presentation animations generator |
| fps | double | Frames per second (FPS) |

### dispose() {#dispose--}
```
public final void dispose()
```

Disposes the instance of the [PresentationPlayer](../../com.aspose.slides/presentationplayer).

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```

Gets the frame index.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      FileOutputStream fos = null;
>                      try {
>                          fos = new FileOutputStream("frame_" + sender.getFrameIndex() + ".png");
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
int
### setFrameTick(PresentationPlayer.FrameTick event) {#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public void setFrameTick(PresentationPlayer.FrameTick event)


设置新的帧滴事件。

--------------------

Presentation pres = new Presentation("pres.pptx");
 try {
     PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
     try {
         PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
         try {
             player.setFrameTick(new PresentationPlayer.FrameTick() {
                 public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
                     FileOutputStream fos = null;
                     try {
                         fos = new FileOutputStream("frame_" + sender.getFrameIndex() + ".png");
                         args.getFrame().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
                     } catch (IOException e) {
                         throw new RuntimeException(e);
                     } finally {
                         if (fos != null) {
                             try {
                                 fos.close();
                             } catch (IOException e) {
                                 e.printStackTrace();
                             }
                         }
                     }
                 }
             });
             animationsGenerator.run(pres.getSlides());
         } finally {
             if (player != null) player.dispose();
         }
     } finally {
         if (animationsGenerator != null) animationsGenerator.dispose();
     }
 } finally {
     if (pres != null) pres.dispose();
 }

--------------------

在播放器生成由 [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) 创建的动画的每一帧时发生。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| event | [FrameTick](../../com.aspose.slides/frametick) | 帧滴事件。 |