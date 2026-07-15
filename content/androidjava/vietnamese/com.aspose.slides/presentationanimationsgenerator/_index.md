---
title: PresentationAnimationsGenerator
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một trình tạo các hoạt ảnh trong .
type: docs
url: /vi/com.aspose.slides/presentationanimationsgenerator/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.IDisposable
```
public class PresentationAnimationsGenerator implements System.IDisposable
```

Đại diện cho một trình tạo các hoạt ảnh trong [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("animated.pptx");
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
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [PresentationAnimationsGenerator(Presentation presentation)](#PresentationAnimationsGenerator-com.aspose.slides.Presentation-) | Tạo một thể hiện mới của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [PresentationAnimationsGenerator(Size frameSize)](#PresentationAnimationsGenerator-com.aspose.slides.android.Size-) | Tạo một thể hiện mới của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [PresentationAnimationsGenerator(SizeF frameSize)](#PresentationAnimationsGenerator-com.aspose.slides.android.SizeF-) | Tạo một thể hiện mới của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [dispose()](#dispose--) | Giải phóng thể hiện của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [getFrameSize()](#getFrameSize--) | Lấy kích thước khung. |
| [getDefaultDelay()](#getDefaultDelay--) | Lấy hoặc đặt thời gian trễ mặc định [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Lấy hoặc đặt thời gian trễ mặc định [ms]. |
| [getIncludeHiddenSlides()](#getIncludeHiddenSlides--) | Lấy hoặc đặt nếu các slide ẩn nên được bao gồm. |
| [setIncludeHiddenSlides(boolean value)](#setIncludeHiddenSlides-boolean-) | Lấy hoặc đặt nếu các slide ẩn nên được bao gồm. |
| [getExportedSlides()](#getExportedSlides--) | Lấy số lượng slide đã xuất. |
| [setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)](#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-) | Đặt một sự kiện hoạt ảnh mới. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--) | Chạy việc tạo sự kiện hoạt ảnh cho mỗi slide. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-) | Chạy việc tạo sự kiện hoạt ảnh cho mỗi slide. |
### PresentationAnimationsGenerator(Presentation presentation) {#PresentationAnimationsGenerator-com.aspose.slides.Presentation-}
```
public PresentationAnimationsGenerator(Presentation presentation)
```

Tạo một thể hiện mới của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Kích thước khung sẽ được đặt phù hợp với [Presentation.getSlideSize](../../com.aspose.slides/presentation\#getSlideSize) |

### PresentationAnimationsGenerator(Size frameSize) {#PresentationAnimationsGenerator-com.aspose.slides.android.Size-}
```
public PresentationAnimationsGenerator(Size frameSize)
```

Tạo một thể hiện mới của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| frameSize | [Size](../../com.aspose.slides.android/size) | Kích thước khung. |

### PresentationAnimationsGenerator(SizeF frameSize) {#PresentationAnimationsGenerator-com.aspose.slides.android.SizeF-}
```
public PresentationAnimationsGenerator(SizeF frameSize)
```

Tạo một thể hiện mới của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| frameSize | [SizeF](../../com.aspose.slides.android/sizef) | Kích thước khung. |

### dispose() {#dispose--}
```
public final void dispose()
```

Giải phóng thể hiện của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

### getFrameSize() {#getFrameSize--}
```
public Size getFrameSize()
```

Lấy kích thước khung.

**Trả về:**
[Size](../../com.aspose.slides.android/size)
### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

Lấy hoặc đặt thời gian trễ mặc định [ms].

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1 giây
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Trả về:** int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Lấy hoặc đặt thời gian trễ mặc định [ms].

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1 giây
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getIncludeHiddenSlides() {#getIncludeHiddenSlides--}
```
public final boolean getIncludeHiddenSlides()
```

Lấy hoặc đặt nếu các slide ẩn nên được bao gồm.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setIncludeHiddenSlides(false);
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Trả về:** boolean
### setIncludeHiddenSlides(boolean value) {#setIncludeHiddenSlides-boolean-}
```
public final void setIncludeHiddenSlides(boolean value)
```

Lấy hoặc đặt nếu các slide ẩn nên được bao gồm.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setIncludeHiddenSlides(false);
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getExportedSlides() {#getExportedSlides--}
```
public final int getExportedSlides()
```

Lấy số lượng slide đã xuất.

**Trả về:** int
### setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim) {#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-}
```
public void setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)
```

Đặt một sự kiện hoạt ảnh mới.

--------------------

> ```
> Presentation presentation = new Presentation("SimpleAnimations.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setNewAnimation(new PresentationAnimationsGenerator.NewAnimation() {
>              public void invoke(IPresentationAnimationPlayer animationPlayer) {
>                  System.out.println(String.format("Animation total duration: %f", animationPlayer.getDuration()));
>              }
>          });
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| anim | [NewAnimation](../../com.aspose.slides/newanimation) | Sự kiện hoạt ảnh. |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)
```

Chạy việc tạo sự kiện hoạt ảnh cho mỗi slide.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              animationsGenerator.setNewAnimation(new PresentationAnimationsGenerator.NewAnimation() {
>                  public void invoke(IPresentationAnimationPlayer animationPlayer) {
>                      // xử lý hoạt ảnh mới
>                  }
>              });
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      // xử lý tick khung trong hoạt ảnh mới
>                  }
>              });
>              animationsGenerator.run(presentation.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)
```

Chạy việc tạo sự kiện hoạt ảnh cho mỗi slide.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.run(presentation.getSlides(), 33, new PresentationPlayer.FrameTick() {
>              public void invoke(PresentationPlayer player, FrameTickEventArgs playerArgs) {
>                  player.setFrameTick(new PresentationPlayer.FrameTick() {
>                      public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                          FileOutputStream fos = null;
>                          try {
>                              fos = new FileOutputStream("frame_" + sender.getFrameIndex() + ".png");
>                              args.getFrame().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>                          } catch (IOException e) {
>                              throw new RuntimeException(e);
>                          } finally {
>                              if (fos != null) {
>                                  try {
>                                      fos.close();
>                                  } catch (IOException e) {
>                                      e.printStackTrace();
>                                  }
>                              }
>                          }
>                      }
>                  });
>              }
>          });
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |
| fps | int |  |
| onFrame | [FrameTick](../../com.aspose.slides/frametick) |  |