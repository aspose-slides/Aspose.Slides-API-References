---
title: PresentationPlayer
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวเล่นของแอนิเมชันที่เชื่อมโยงกับ .
type: docs
url: /th/com.aspose.slides/presentationplayer/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.ms.System.IDisposable
```
public class PresentationPlayer implements System.IDisposable
```

เป็นตัวเล่นของแอนิเมชันที่เชื่อมโยงกับ [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          // เล่นแอนิเมชันที่ 33 FPS
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
>          // เล่นแอนิเมชันที่ 45 FPS
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

## ตัวสร้าง

| Constructor | คำอธิบาย |
| --- | --- |
| [PresentationPlayer(PresentationAnimationsGenerator generator, double fps)](#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-) | สร้างอินสตานซ์ใหม่ของ [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [dispose()](#dispose--) | ทำลายอินสตานซ์ของ [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
| [getFrameIndex()](#getFrameIndex--) | รับดัชนีเฟรม. |
| [setFrameTick(PresentationPlayer.FrameTick event)](#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-) | ตั้งค่าเหตุการณ์ tick ของเฟรมใหม่. |
### PresentationPlayer(PresentationAnimationsGenerator generator, double fps) {#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-}
```
public PresentationPlayer(PresentationAnimationsGenerator generator, double fps)
```


สร้างอินสตานซ์ใหม่ของ [PresentationPlayer](../../com.aspose.slides/presentationplayer).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| generator | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) | ตัวสร้างแอนิเมชันการนำเสนอ |
| fps | double | จำนวนเฟรมต่อวินาที (FPS) |

### dispose() {#dispose--}
```
public final void dispose()
```


ทำลายอินสตานซ์ของ [PresentationPlayer](../../com.aspose.slides/presentationplayer).

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


รับดัชนีเฟรม.

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


**ค่าที่คืน:**
int
### setFrameTick(PresentationPlayer.FrameTick event) {#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public void setFrameTick(PresentationPlayer.FrameTick event)
```


ตั้งค่าเหตุการณ์ tick ของเฟรมใหม่.

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


--------------------

เกิดขึ้นเมื่อแต่ละเฟรมของแอนิเมชันที่สร้างโดย [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) ถูกสร้างโดยผู้เล่น.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| event | [FrameTick](../../com.aspose.slides/frametick) | เหตุการณ์ tick ของเฟรม. |