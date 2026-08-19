---
title: PresentationAnimationsGenerator
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili generator animasi dalam .
type: docs
url: /id/com.aspose.slides/presentationanimationsgenerator/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.IDisposable
```
public class PresentationAnimationsGenerator implements System.IDisposable
```

Mewakili generator animasi dalam [Presentation](../../com.aspose.slides/presentation).

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
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PresentationAnimationsGenerator(Presentation presentation)](#PresentationAnimationsGenerator-com.aspose.slides.Presentation-) | Membuat instance baru dari [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [PresentationAnimationsGenerator(Dimension frameSize)](#PresentationAnimationsGenerator-java.awt.Dimension-) | Membuat instance baru dari [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [PresentationAnimationsGenerator(Dimension2D frameSize)](#PresentationAnimationsGenerator-java.awt.geom.Dimension2D-) | Membuat instance baru dari [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [dispose()](#dispose--) | Membuang instance dari [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [getFrameSize()](#getFrameSize--) | Mendapatkan ukuran frame. |
| [getDefaultDelay()](#getDefaultDelay--) | Mendapatkan atau mengatur waktu tunda default [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Mendapatkan atau mengatur waktu tunda default [ms]. |
| [getIncludeHiddenSlides()](#getIncludeHiddenSlides--) | Mendapatkan atau mengatur apakah slide tersembunyi harus disertakan. |
| [setIncludeHiddenSlides(boolean value)](#setIncludeHiddenSlides-boolean-) | Mendapatkan atau mengatur apakah slide tersembunyi harus disertakan. |
| [getExportedSlides()](#getExportedSlides--) | Mendapatkan jumlah slide yang diekspor. |
| [setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)](#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-) | Menetapkan event animasi baru. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--) | Jalankan pembuatan event animasi untuk setiap slide. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-) | Jalankan pembuatan event animasi untuk setiap slide. |
### PresentationAnimationsGenerator(Presentation presentation) {#PresentationAnimationsGenerator-com.aspose.slides.Presentation-}
```
public PresentationAnimationsGenerator(Presentation presentation)
```

Membuat instance baru dari [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Ukuran frame akan diatur sesuai dengan [Presentation.getSlideSize](../../com.aspose.slides/presentation\#getSlideSize) |

### PresentationAnimationsGenerator(Dimension frameSize) {#PresentationAnimationsGenerator-java.awt.Dimension-}
```
public PresentationAnimationsGenerator(Dimension frameSize)
```

Membuat instance baru dari [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| frameSize | java.awt.Dimension | Ukuran frame. |

### PresentationAnimationsGenerator(Dimension2D frameSize) {#PresentationAnimationsGenerator-java.awt.geom.Dimension2D-}
```
public PresentationAnimationsGenerator(Dimension2D frameSize)
```

Membuat instance baru dari [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| frameSize | java.awt.geom.Dimension2D | Ukuran frame. |

### dispose() {#dispose--}
```
public final void dispose()
```

Membuang instance dari [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

### getFrameSize() {#getFrameSize--}
```
public Dimension getFrameSize()
```

Mendapatkan ukuran frame.

**Mengembalikan:**
java.awt.Dimension
### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

Mendapatkan atau mengatur waktu tunda default [ms].

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1 dtk
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Mengembalikan:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Mendapatkan atau mengatur waktu tunda default [ms].

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1 dtk
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getIncludeHiddenSlides() {#getIncludeHiddenSlides--}
```
public final boolean getIncludeHiddenSlides()
```

Mendapatkan atau mengatur apakah slide tersembunyi harus disertakan.

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

**Mengembalikan:**
boolean
### setIncludeHiddenSlides(boolean value) {#setIncludeHiddenSlides-boolean-}
```
public final void setIncludeHiddenSlides(boolean value)
```

Mendapatkan atau mengatur apakah slide tersembunyi harus disertakan.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getExportedSlides() {#getExportedSlides--}
```
public final int getExportedSlides()
```

Mendapatkan jumlah slide yang diekspor.

**Mengembalikan:**
int
### setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim) {#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-}
```
public void setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)
```

Menetapkan event animasi baru.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| anim | [NewAnimation](../../com.aspose.slides/newanimation) | Event animasi. |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)
```

Jalankan pembuatan event animasi untuk setiap slide.

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
>                  // menangani animasi baru
>              });
>              player.setFrameTick((sender, args) ->
>              {
>                  // menangani frame tick dalam animasi baru
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


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)
```

Jalankan pembuatan event animasi untuk setiap slide.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |
| fps | int |  |
| onFrame | [FrameTick](../../com.aspose.slides/frametick) |  |