---
title: PresentationAnimationsGenerator
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một bộ tạo các hoạt ảnh trong .
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

Đại diện cho một bộ tạo các hoạt ảnh trong [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
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
| [PresentationAnimationsGenerator(Dimension frameSize)](#PresentationAnimationsGenerator-java.awt.Dimension-) | Tạo một thể hiện mới của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [PresentationAnimationsGenerator(Dimension2D frameSize)](#PresentationAnimationsGenerator-java.awt.geom.Dimension2D-) | Tạo một thể hiện mới của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [dispose()](#dispose--) | Giải phóng thể hiện của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [getFrameSize()](#getFrameSize--) | Lấy kích thước khung. |
| [getDefaultDelay()](#getDefaultDelay--) | Lấy hoặc thiết lập thời gian trễ mặc định [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Lấy hoặc thiết lập thời gian trễ mặc định [ms]. |
| [getIncludeHiddenSlides()](#getIncludeHiddenSlides--) | Lấy hoặc thiết lập xem có bao gồm các slide ẩn hay không. |
| [setIncludeHiddenSlides(boolean value)](#setIncludeHiddenSlides-boolean-) | Lấy hoặc thiết lập xem có bao gồm các slide ẩn hay không. |
| [getExportedSlides()](#getExportedSlides--) | Lấy số lượng slide đã xuất. |
| [setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)](#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-) | Thiết lập một sự kiện hoạt ảnh mới. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--) | Chạy việc tạo các sự kiện hoạt ảnh cho mỗi slide. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-) | Chạy việc tạo các sự kiện hoạt ảnh cho mỗi slide. |
### PresentationAnimationsGenerator(Presentation presentation) {#PresentationAnimationsGenerator-com.aspose.slides.Presentation-}
```
public PresentationAnimationsGenerator(Presentation presentation)
```

Tạo một thể hiện mới của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Kích thước khung sẽ được thiết lập phù hợp với [Presentation.getSlideSize](../../com.aspose.slides/presentation\#getSlideSize) |

### PresentationAnimationsGenerator(Dimension frameSize) {#PresentationAnimationsGenerator-java.awt.Dimension-}
```
public PresentationAnimationsGenerator(Dimension frameSize)
```

Tạo một thể hiện mới của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| frameSize | java.awt.Dimension | Kích thước khung. |

### PresentationAnimationsGenerator(Dimension2D frameSize) {#PresentationAnimationsGenerator-java.awt.geom.Dimension2D-}
```
public PresentationAnimationsGenerator(Dimension2D frameSize)
```

Tạo một thể hiện mới của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| frameSize | java.awt.geom.Dimension2D | Kích thước khung. |

### dispose() {#dispose--}
```
public final void dispose()
```

Giải phóng thể hiện của [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

### getFrameSize() {#getFrameSize--}
```
public Dimension getFrameSize()
```

Lấy kích thước khung.

**Giá trị trả về:**
java.awt.Dimension
### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

Lấy hoặc thiết lập thời gian trễ mặc định [ms].

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

**Giá trị trả về:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Lấy hoặc thiết lập thời gian trễ mặc định [ms].

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

Lấy hoặc thiết lập xem có bao gồm các slide ẩn hay không.

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

**Giá trị trả về:**
boolean
### setIncludeHiddenSlides(boolean value) {#setIncludeHiddenSlides-boolean-}
```
public final void setIncludeHiddenSlides(boolean value)
```

Lấy hoặc thiết lập xem có bao gồm các slide ẩn hay không.

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

**Giá trị trả về:**
int
### setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim) {#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-}
```
public void setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)
```

Thiết lập một sự kiện hoạt ảnh mới.

--------------------

> ```
> Presentation presentation = new Presentation("SimpleAnimations.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setNewAnimation(animationPlayer -> {
>              System.out.println(String.format("Animation total duration: %f", animationPlayer.getDuration()));
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

Chạy việc tạo các sự kiện hoạt ảnh cho mỗi slide.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              animationsGenerator.setNewAnimation(animationPlayer ->
>              {
>                  // xử lý hoạt ảnh mới
>              });
>              player.setFrameTick((sender, args) ->
>              {
>                  // xử lý tick khung trong hoạt ảnh mới
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

Chạy việc tạo các sự kiện hoạt ảnh cho mỗi slide.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.run(presentation.getSlides(), 33, (player, playerArgs) ->
>          {
>              player.setFrameTick((sender, args) ->
>              {
>                  try {
>                      ImageIO.write(args.getFrame(), "PNG", new java.io.File("frame_" + sender.getFrameIndex() + ".png"));
>                  } catch (IOException e) {
>                      throw new RuntimeException(e);
>                  }
>              });
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