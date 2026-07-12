---
title: PresentationAnimationsGenerator
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa un generador de las animaciones en el .
type: docs
url: /es/com.aspose.slides/presentationanimationsgenerator/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
com.aspose.ms.System.IDisposable
```
public class PresentationAnimationsGenerator implements System.IDisposable
```

Representa un generador de animaciones en el [Presentation](../../com.aspose.slides/presentation).

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PresentationAnimationsGenerator(Presentation presentation)](#PresentationAnimationsGenerator-com.aspose.slides.Presentation-) | Crea una nueva instancia del [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [PresentationAnimationsGenerator(Size frameSize)](#PresentationAnimationsGenerator-com.aspose.slides.android.Size-) | Crea una nueva instancia del [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [PresentationAnimationsGenerator(SizeF frameSize)](#PresentationAnimationsGenerator-com.aspose.slides.android.SizeF-) | Crea una nueva instancia del [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
## Métodos

| Método | Descripción |
| --- | --- |
| [dispose()](#dispose--) | Descarta la instancia del [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator). |
| [getFrameSize()](#getFrameSize--) | Obtiene el tamaño del marco. |
| [getDefaultDelay()](#getDefaultDelay--) | Obtiene o establece el tiempo de retardo predeterminado [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Obtiene o establece el tiempo de retardo predeterminado [ms]. |
| [getIncludeHiddenSlides()](#getIncludeHiddenSlides--) | Obtiene o establece si se deben incluir diapositivas ocultas. |
| [setIncludeHiddenSlides(boolean value)](#setIncludeHiddenSlides-boolean-) | Obtiene o establece si se deben incluir diapositivas ocultas. |
| [getExportedSlides()](#getExportedSlides--) | Obtiene el número de diapositivas exportadas. |
| [setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)](#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-) | Establece un nuevo evento de animación. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--) | Ejecuta la generación de eventos de animación para cada diapositiva. |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-) | Ejecuta la generación de eventos de animación para cada diapositiva. |
### PresentationAnimationsGenerator(Presentation presentation) {#PresentationAnimationsGenerator-com.aspose.slides.Presentation-}
```
public PresentationAnimationsGenerator(Presentation presentation)
```

Crea una nueva instancia del [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | El tamaño del marco se establecerá de acuerdo con el [Presentation.getSlideSize](../../com.aspose.slides/presentation\#getSlideSize) |

### PresentationAnimationsGenerator(Size frameSize) {#PresentationAnimationsGenerator-com.aspose.slides.android.Size-}
```
public PresentationAnimationsGenerator(Size frameSize)
```

Crea una nueva instancia del [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| frameSize | [Size](../../com.aspose.slides.android/size) | El tamaño del marco. |

### PresentationAnimationsGenerator(SizeF frameSize) {#PresentationAnimationsGenerator-com.aspose.slides.android.SizeF-}
```
public PresentationAnimationsGenerator(SizeF frameSize)
```

Crea una nueva instancia del [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| frameSize | [SizeF](../../com.aspose.slides.android/sizef) | El tamaño del marco. |

### dispose() {#dispose--}
```
public final void dispose()
```

Descarta la instancia del [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator).

### getFrameSize() {#getFrameSize--}
```
public Size getFrameSize()
```

Obtiene el tamaño del marco.

**Devuelve:**
[Size](../../com.aspose.slides.android/size)
### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

Obtiene o establece el tiempo de retardo predeterminado [ms].

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1s
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Devuelve:** int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Obtiene o establece el tiempo de retardo predeterminado [ms].

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1s
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getIncludeHiddenSlides() {#getIncludeHiddenSlides--}
```
public final boolean getIncludeHiddenSlides()
```

Obtiene o establece si se deben incluir diapositivas ocultas.

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

**Devuelve:** boolean
### setIncludeHiddenSlides(boolean value) {#setIncludeHiddenSlides-boolean-}
```
public final void setIncludeHiddenSlides(boolean value)
```

Obtiene o establece si se deben incluir diapositivas ocultas.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getExportedSlides() {#getExportedSlides--}
```
public final int getExportedSlides()
```

Obtiene el número de diapositivas exportadas.

**Devuelve:** int
### setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim) {#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-}
```
public void setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)
```

Establece un nuevo evento de animación.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| anim | [NewAnimation](../../com.aspose.slides/newanimation) | Evento de animación. |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)
```

Ejecuta la generación de eventos de animación para cada diapositiva.

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
>                      // manejar nueva animación
>                  }
>              });
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      // manejar tick de cuadro dentro de la nueva animación
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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)
```

Ejecuta la generación de eventos de animación para cada diapositiva.

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
>          if (presentation != null) presentation.dispose();
>      }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |
| fps | int |  |
| onFrame | [FrameTick](../../com.aspose.slides/frametick) |  |