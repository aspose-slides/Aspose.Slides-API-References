---
title: PresentationAnimationsGenerator
second_title: Aspose.Slides Androidhoz Java API Referencia
description: Az animációk generátorát képviseli a .
type: docs
url: /hu/com.aspose.slides/presentationanimationsgenerator/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
com.aspose.ms.System.IDisposable
```
public class PresentationAnimationsGenerator implements System.IDisposable
```

A [Presentation](../../com.aspose.slides/presentation) animációinak generátorát képviseli.

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
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PresentationAnimationsGenerator(Presentation presentation)](#PresentationAnimationsGenerator-com.aspose.slides.Presentation-) | Létrehoz egy új példányt a [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator)-ból. |
| [PresentationAnimationsGenerator(Size frameSize)](#PresentationAnimationsGenerator-com.aspose.slides.android.Size-) | Létrehoz egy új példányt a [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator)-ból. |
| [PresentationAnimationsGenerator(SizeF frameSize)](#PresentationAnimationsGenerator-com.aspose.slides.android.SizeF-) | Létrehoz egy új példányt a [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator)-ból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [dispose()](#dispose--) | Felszabadítja a [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) példányt. |
| [getFrameSize()](#getFrameSize--) | Lekéri a keret méretét. |
| [getDefaultDelay()](#getDefaultDelay--) | Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. |
| [getIncludeHiddenSlides()](#getIncludeHiddenSlides--) | Lekéri vagy beállítja, hogy a rejtett diák legyenek-e belefoglalva. |
| [setIncludeHiddenSlides(boolean value)](#setIncludeHiddenSlides-boolean-) | Lekéri vagy beállítja, hogy a rejtett diák legyenek-e belefoglalva. |
| [getExportedSlides()](#getExportedSlides--) | Lekéri az exportált diák számát. |
| [setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)](#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-) | Beállít egy új animációs eseményt. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--) | Futtatja az animációs események generálását minden diához. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-) | Futtatja az animációs események generálását minden diához. |
### PresentationAnimationsGenerator(Presentation presentation) {#PresentationAnimationsGenerator-com.aspose.slides.Presentation-}
```
public PresentationAnimationsGenerator(Presentation presentation)
```


Létrehoz egy új példányt a [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator)-ból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | A keret mérete a [Presentation.getSlideSize](../../com.aspose.slides/presentation\#getSlideSize)-nek megfelelően lesz beállítva. |

### PresentationAnimationsGenerator(Size frameSize) {#PresentationAnimationsGenerator-com.aspose.slides.android.Size-}
```
public PresentationAnimationsGenerator(Size frameSize)
```


Létrehoz egy új példányt a [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator)-ból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| frameSize | [Size](../../com.aspose.slides.android/size) | A keret mérete. |

### PresentationAnimationsGenerator(SizeF frameSize) {#PresentationAnimationsGenerator-com.aspose.slides.android.SizeF-}
```
public PresentationAnimationsGenerator(SizeF frameSize)
```


Létrehoz egy új példányt a [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator)-ból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| frameSize | [SizeF](../../com.aspose.slides.android/sizef) | A keret mérete. |

### dispose() {#dispose--}
```
public final void dispose()
```


Felszabadítja a [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) példányt.

### getFrameSize() {#getFrameSize--}
```
public Size getFrameSize()
```


Lekéri a keret méretét.

**Visszatér:**
[Size](../../com.aspose.slides.android/size)
### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```


Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms].

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1 mp
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Visszatér:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```


Beállítja az alapértelmezett késleltetési időt [ms].

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1 mp
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getIncludeHiddenSlides() {#getIncludeHiddenSlides--}
```
public final boolean getIncludeHiddenSlides()
```


Lekéri vagy beállítja, hogy a rejtett diák legyenek-e belefoglalva.

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

**Visszatér:**
boolean
### setIncludeHiddenSlides(boolean value) {#setIncludeHiddenSlides-boolean-}
```
public final void setIncludeHiddenSlides(boolean value)
```


Beállítja, hogy a rejtett diák legyenek-e belefoglalva.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getExportedSlides() {#getExportedSlides--}
```
public final int getExportedSlides()
```


Lekéri az exportált diák számát.

**Visszatér:**
int
### setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim) {#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-}
```
public void setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)
```


Beállít egy új animációs eseményt.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| anim | [NewAnimation](../../com.aspose.slides/newanimation) | Animációs esemény. |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)
```


Futtatja az animációs események generálását minden diához.

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
>                      // új animáció kezelése
>                  }
>              });
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      // új animációban a frame tick kezelése
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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)
```


Futtatja az animációs események generálását minden diához.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |
| fps | int |  |
| onFrame | [FrameTick](../../com.aspose.slides/frametick) |  |