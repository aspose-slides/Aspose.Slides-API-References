---
title: PresentationAnimationsGenerator
second_title: Aspose.Slides के Java API संदर्भ
description: यह . में एनीमेशन का जेनरेटर दर्शाता है।
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

[Presentation](../../com.aspose.slides/presentation) में एनीमेशन का जेनरेटर दर्शाता है।

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
## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [PresentationAnimationsGenerator(Presentation presentation)](#PresentationAnimationsGenerator-com.aspose.slides.Presentation-) | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) का नया उदाहरण बनाता है। |
| [PresentationAnimationsGenerator(Dimension frameSize)](#PresentationAnimationsGenerator-java.awt.Dimension-) | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) का नया उदाहरण बनाता है। |
| [PresentationAnimationsGenerator(Dimension2D frameSize)](#PresentationAnimationsGenerator-java.awt.geom.Dimension2D-) | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) का नया उदाहरण बनाता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [dispose()](#dispose--) | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) का उदाहरण नष्ट करता है। |
| [getFrameSize()](#getFrameSize--) | फ़्रेम आकार प्राप्त करता है। |
| [getDefaultDelay()](#getDefaultDelay--) | डिफ़ॉल्ट देरी समय [ms] प्राप्त या सेट करता है। |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | डिफ़ॉल्ट देरी समय [ms] प्राप्त या सेट करता है। |
| [getIncludeHiddenSlides()](#getIncludeHiddenSlides--) | छुपी हुई स्लाइड्स को शामिल करना है या नहीं, प्राप्त या सेट करता है। |
| [setIncludeHiddenSlides(boolean value)](#setIncludeHiddenSlides-boolean-) | छुपी हुई स्लाइड्स को शामिल करना है या नहीं, प्राप्त या सेट करता है। |
| [getExportedSlides()](#getExportedSlides--) | निर्यातित स्लाइड्स की गिनती प्राप्त करता है। |
| [setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)](#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-) | नया एनीमेशन इवेंट सेट करता है। |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--) | प्रत्येक स्लाइड के लिए एनीमेशन इवेंट जेनरेशन चलाता है। |
| [run(System.Collections.Generic.IGenericEnumerable<ISlide> slides, int fps, PresentationPlayer.FrameTick onFrame)](#run-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.ISlide--int-com.aspose.slides.PresentationPlayer.FrameTick-) | प्रत्येक स्लाइड के लिए एनीमेशन इवेंट जेनरेशन चलाता है। |
### PresentationAnimationsGenerator(Presentation presentation) {#PresentationAnimationsGenerator-com.aspose.slides.Presentation-}
```
public PresentationAnimationsGenerator(Presentation presentation)
```

[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) का नया उदाहरण बनाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | फ़्रेम आकार [Presentation.getSlideSize](../../com.aspose.slides/presentation\#getSlideSize) के अनुरूप सेट किया जाएगा। |
### PresentationAnimationsGenerator(Dimension frameSize) {#PresentationAnimationsGenerator-java.awt.Dimension-}
```
public PresentationAnimationsGenerator(Dimension frameSize)
```

[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) का नया उदाहरण बनाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| frameSize | java.awt.Dimension | फ़्रेम आकार। |
### PresentationAnimationsGenerator(Dimension2D frameSize) {#PresentationAnimationsGenerator-java.awt.geom.Dimension2D-}
```
public PresentationAnimationsGenerator(Dimension2D frameSize)
```

[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) का नया उदाहरण बनाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| frameSize | java.awt.geom.Dimension2D | फ़्रेम आकार। |
### dispose() {#dispose--}
```
public final void dispose()
```

[PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) का उदाहरण नष्ट करता है।

### getFrameSize() {#getFrameSize--}
```
public Dimension getFrameSize()
```

फ़्रेम आकार प्राप्त करता है।

**वापसी मान:**
java.awt.Dimension
### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

डिफ़ॉल्ट देरी समय [ms] प्राप्त या सेट करता है।

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

**वापसी मान:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

डिफ़ॉल्ट देरी समय [ms] प्राप्त या सेट करता है।

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

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getIncludeHiddenSlides() {#getIncludeHiddenSlides--}
```
public final boolean getIncludeHiddenSlides()
```

छुपी हुई स्लाइड्स को शामिल करना है या नहीं, प्राप्त या सेट करता है।

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

**वापसी मान:**
boolean
### setIncludeHiddenSlides(boolean value) {#setIncludeHiddenSlides-boolean-}
```
public final void setIncludeHiddenSlides(boolean value)
```

छुपी हुई स्लाइड्स को शामिल करना है या नहीं, प्राप्त या सेट करता है।

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

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getExportedSlides() {#getExportedSlides--}
```
public final int getExportedSlides()
```

निर्यातित स्लाइड्स की गिनती प्राप्त करता है।

**वापसी मान:**
int
### setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim) {#setNewAnimation-com.aspose.slides.PresentationAnimationsGenerator.NewAnimation-}
```
public void setNewAnimation(PresentationAnimationsGenerator.NewAnimation anim)
```

नया एनीमेशन इवेंट सेट करता है।

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

**परामीटर:**
| परामीटर | प्रकार | विवरण |
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
>              animationsGenerator.setNewAnimation(animationPlayer ->
>              {
>                  // नई एनीमेशन को संभालें
>              });
>              player.setFrameTick((sender, args) ->
>              {
>                  // नई एनीमेशन के भीतर फ्रेम टिक को संभालें
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

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slides | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.ISlide> |  |
| fps | int |  |
| onFrame | [FrameTick](../../com.aspose.slides/frametick) |  |