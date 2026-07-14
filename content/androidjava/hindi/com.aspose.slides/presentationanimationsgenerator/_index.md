---
title: PresentationAnimationsGenerator
second_title: Aspose.Slides for Android जावा API संदर्भ के माध्यम से
description: एनिमेशन का जेनरेटर दर्शाता है।
type: docs
url: /hi/com.aspose.slides/presentationanimationsgenerator/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.IDisposable
```
public class PresentationAnimationsGenerator implements System.IDisposable
```

[Presentation](../../com.aspose.slides/presentation) में एनीमेशन जेनरेटर का प्रतिनिधित्व करता है।

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
## निर्माता

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PresentationAnimationsGenerator(Presentation presentation)](#PresentationAnimationsGenerator-com.aspose.slides.Presentation-) | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) की नई इंस्टैंस बनाता है। |
| [PresentationAnimationsGenerator(Size frameSize)](#PresentationAnimationsGenerator-com.aspose.slides.android.Size-) | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) की नई इंस्टैंस बनाता है। |
| [PresentationAnimationsGenerator(SizeF frameSize)](#PresentationAnimationsGenerator-com.aspose.slides.android.SizeF-) | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) की नई इंस्टैंस बनाता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [dispose()](#dispose--) | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) की इंस्टैंस को नष्ट करता है। |
| [getFrameSize()](#getFrameSize--) | फ़्रेम आकार प्राप्त करता है। |
| [getDefaultDelay()](#getDefaultDelay--) | डिफ़ॉल्ट देरी समय [ms] को प्राप्त या सेट करता है। |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | डिफ़ॉल्ट देरी समय [ms] को प्राप्त या सेट करता है। |
| [getIncludeHiddenSlides()](#getIncludeHiddenSlides--) | छिपी स्लाइड्स को शामिल करना चाहिए या नहीं, प्राप्त या सेट करता है। |
| [setIncludeHiddenSlides(boolean value)](#setIncludeHiddenSlides-boolean-) | छिपी स्लाइड्स को शामिल करना चाहिए या नहीं, प्राप्त या सेट करता है। |
| [getExportedSlides()](#getExportedSlides--) | निर्यातित स्लाइड्स की संख्या प्राप्त करता है। |
| [setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)](#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-) | एक नया एनीमेशन इवेंट सेट करता है। |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--) | प्रत्येक स्लाइड के लिए एनीमेशन इवेंट जेनरेशन चलाता है। |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-) | प्रत्येक स्लाइड के लिए एनीमेशन इवेंट जेनरेशन चलाता है। |
### PresentationAnimationsGenerator(Presentation presentation) {#PresentationAnimationsGenerator-com.aspose.slides.Presentation-}
```
public PresentationAnimationsGenerator(Presentation presentation)
```


[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) की नई इंस्टैंस बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | फ़्रेम आकार [Presentation.getSlideSize](../../com.aspose.slides/presentation\#getSlideSize) के अनुसार सेट किया जाएगा |

### PresentationAnimationsGenerator(Size frameSize) {#PresentationAnimationsGenerator-com.aspose.slides.android.Size-}
```
public PresentationAnimationsGenerator(Size frameSize)
```


[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) की नई इंस्टैंस बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| frameSize | [Size](../../com.aspose.slides.android/size) | फ़्रेम आकार। |

### PresentationAnimationsGenerator(SizeF frameSize) {#PresentationAnimationsGenerator-com.aspose.slides.android.SizeF-}
```
public PresentationAnimationsGenerator(SizeF frameSize)
```


[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) की नई इंस्टैंस बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| frameSize | [SizeF](../../com.aspose.slides.android/sizef) | फ़्रेम आकार। |

### dispose() {#dispose--}
```
public final void dispose()
```


[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) की इंस्टैंस को नष्ट करता है।

### getFrameSize() {#getFrameSize--}
```
public Size getFrameSize()
```


फ़्रेम आकार प्राप्त करता है।

**वापसी:**
[Size](../../com.aspose.slides.android/size)
### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```


डिफ़ॉल्ट देरी समय [ms] को प्राप्त या सेट करता है।

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1 सेकंड
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**वापसी:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```


डिफ़ॉल्ट देरी समय [ms] को प्राप्त या सेट करता है।

--------------------

> ```
> Presentation presentation = new Presentation("animated.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(presentation.getSlideSize().getSize());
>      try {
>          animationsGenerator.setDefaultDelay(1000); // 1 सेकंड
>          // ...
>          animationsGenerator.run(presentation.getSlides());
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getIncludeHiddenSlides() {#getIncludeHiddenSlides--}
```
public final boolean getIncludeHiddenSlides()
```


छिपी स्लाइड्स को शामिल करना चाहिए या नहीं, प्राप्त या सेट करता है।

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

**वापसी:**
boolean
### setIncludeHiddenSlides(boolean value) {#setIncludeHiddenSlides-boolean-}
```
public final void setIncludeHiddenSlides(boolean value)
```


छिपी स्लाइड्स को शामिल करना चाहिए या नहीं, प्राप्त या सेट करता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getExportedSlides() {#getExportedSlides--}
```
public final int getExportedSlides()
```


निर्यातित स्लाइड्स की संख्या प्राप्त करता है।

**वापसी:**
int
### setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim) {#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-}
```
public void setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)
```


एक नया एनीमेशन इवेंट सेट करता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| anim | [NewAnimation](../../com.aspose.slides/newanimation) | एनीमेशन इवेंट। |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)
```


प्रत्येक स्लाइड के लिए एनीमेशन इवेंट जेनरेशन चलाता है।

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
>                      // नई एनीमेशन को संभालें
>                  }
>              });
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      // नई एनीमेशन के भीतर फ्रेम टिक को संभालें
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


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |

### run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame) {#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public final void run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)
```


प्रत्येक स्लाइड के लिए एनीमेशन इवेंट जेनरेशन चलाता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |
| fps | int |  |
| onFrame | [FrameTick](../../com.aspose.slides/frametick) |  |