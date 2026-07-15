---
title: PresentationPlayer
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn trình phát các hoạt ảnh liên quan đến .
type: docs
url: /vi/com.aspose.slides/presentationplayer/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.IDisposable
```
public class PresentationPlayer implements System.IDisposable
```

Biểu diễn trình phát các hoạt ảnh liên quan đến [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          // Phát hoạt ảnh với 33 FPS
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
>          // Phát hoạt ảnh với 45 FPS
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

## Các hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [PresentationPlayer(PresentationAnimationsGenerator generator, double fps)](#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-) | Tạo một thể hiện mới của [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [dispose()](#dispose--) | Giải phóng thể hiện của [PresentationPlayer](../../com.aspose.slides/presentationplayer). |
| [getFrameIndex()](#getFrameIndex--) | Lấy chỉ số khung. |
| [setFrameTick(PresentationPlayer.FrameTick event)](#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-) | Đặt một sự kiện tick khung mới. |
### PresentationPlayer(PresentationAnimationsGenerator generator, double fps) {#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-}
```
public PresentationPlayer(PresentationAnimationsGenerator generator, double fps)
```


Tạo một thể hiện mới của [PresentationPlayer](../../com.aspose.slides/presentationplayer).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| generator | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) | Trình tạo hoạt ảnh trình chiếu |
| fps | double | Khung hình trên giây (FPS) |

### dispose() {#dispose--}
```
public final void dispose()
```


Giải phóng thể hiện của [PresentationPlayer](../../com.aspose.slides/presentationplayer).

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


Lấy chỉ số khung.

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


**Trả về:**
int
### setFrameTick(PresentationPlayer.FrameTick event) {#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public void setFrameTick(PresentationPlayer.FrameTick event)
```


Đặt một sự kiện tick khung mới.

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
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Xảy ra khi mỗi khung của hoạt ảnh được tạo bởi [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) được phát sinh bởi trình phát.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| event | [FrameTick](../../com.aspose.slides/frametick) | Sự kiện tick khung. |