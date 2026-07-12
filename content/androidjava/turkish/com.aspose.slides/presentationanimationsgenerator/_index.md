---
title: PresentationAnimationsGenerator
second_title: Aspose.Slides for Android Java API Referansı
description: Animasyonların bir üreteci olarak temsil eder.
type: docs
url: /tr/com.aspose.slides/presentationanimationsgenerator/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
com.aspose.ms.System.IDisposable
```
public class PresentationAnimationsGenerator implements System.IDisposable
```

[Presentation](../../com.aspose.slides/presentation) içindeki animasyonların bir üreteci olarak temsil eder.

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
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PresentationAnimationsGenerator(Presentation presentation)](#PresentationAnimationsGenerator-com.aspose.slides.Presentation-) | Yeni bir [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) örneği oluşturur. |
| [PresentationAnimationsGenerator(Size frameSize)](#PresentationAnimationsGenerator-com.aspose.slides.android.Size-) | Yeni bir [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) örneği oluşturur. |
| [PresentationAnimationsGenerator(SizeF frameSize)](#PresentationAnimationsGenerator-com.aspose.slides.android.SizeF-) | Yeni bir [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) örneği oluşturur. |
## Metotlar

| Metod | Açıklama |
| --- | --- |
| [dispose()](#dispose--) | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) örneğini serbest bırakır. |
| [getFrameSize()](#getFrameSize--) | Kare boyutunu alır. |
| [getDefaultDelay()](#getDefaultDelay--) | Varsayılan gecikme süresini [ms] alır veya ayarlar. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Varsayılan gecikme süresini [ms] alır veya ayarlar. |
| [getIncludeHiddenSlides()](#getIncludeHiddenSlides--) | Gizli slaytların dahil edilip edilmediğini alır veya ayarlar. |
| [setIncludeHiddenSlides(boolean value)](#setIncludeHiddenSlides-boolean-) | Gizli slaytların dahil edilip edilmediğini alır veya ayarlar. |
| [getExportedSlides()](#getExportedSlides--) | Dışa aktarılan slayt sayısını alır. |
| [setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)](#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-) | Yeni bir animasyon olayı ayarlar. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--) | Her slayt için animasyon olayı üretimini çalıştırır. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-) | Her slayt için animasyon olayı üretimini çalıştırır. |
### PresentationAnimationsGenerator(Presentation presentation) {#PresentationAnimationsGenerator-com.aspose.slides.Presentation-}
```
public PresentationAnimationsGenerator(Presentation presentation)
```

Yeni bir [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) örneği oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Kare boyutu, [Presentation.getSlideSize](../../com.aspose.slides/presentation\#getSlideSize) doğrultusunda ayarlanacaktır. |

### PresentationAnimationsGenerator(Size frameSize) {#PresentationAnimationsGenerator-com.aspose.slides.android.Size-}
```
public PresentationAnimationsGenerator(Size frameSize)
```

Yeni bir [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) örneği oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frameSize | [Size](../../com.aspose.slides.android/size) | Kare boyutu. |

### PresentationAnimationsGenerator(SizeF frameSize) {#PresentationAnimationsGenerator-com.aspose.slides.android.SizeF-}
```
public PresentationAnimationsGenerator(SizeF frameSize)
```

Yeni bir [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) örneği oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frameSize | [SizeF](../../com.aspose.slides.android/sizef) | Kare boyutu. |

### dispose() {#dispose--}
```
public final void dispose()
```

[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) örneğini serbest bırakır.

### getFrameSize() {#getFrameSize--}
```
public Size getFrameSize()
```

Kare boyutunu alır.

**Döndürür:**
[Size](../../com.aspose.slides.android/size)
### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

Varsayılan gecikme süresini [ms] alır veya ayarlar.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1sn
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Döndürür:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Varsayılan gecikme süresini [ms] alır veya ayarlar.

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1sn
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getIncludeHiddenSlides() {#getIncludeHiddenSlides--}
```
public final boolean getIncludeHiddenSlides()
```

Gizli slaytların dahil edilip edilmediğini alır veya ayarlar.

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

**Döndürür:**
boolean
### setIncludeHiddenSlides(boolean value) {#setIncludeHiddenSlides-boolean-}
```
public final void setIncludeHiddenSlides(boolean value)
```

Gizli slaytların dahil edilip edilmediğini alır veya ayarlar.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getExportedSlides() {#getExportedSlides--}
```
public final int getExportedSlides()
```

Dışa aktarılan slayt sayısını alır.

**Döndürür:**
int
### setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim) {#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-}
```
public void setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)
```

Yeni bir animasyon olayı ayarlar.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anim | [NewAnimation](../../com.aspose.slides/newanimation) | Animasyon olayı. |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)
```

Her slayt için animasyon olayı üretimini çalıştırır.

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
>                      // yeni animasyonu işle
>                  }
>              });
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      // yeni animasyon içinde çerçeve tikini işle
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


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)
```

Her slayt için animasyon olayı üretimini çalıştırır.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |
| fps | int |  |
| onFrame | [FrameTick](../../com.aspose.slides/frametick) |  |