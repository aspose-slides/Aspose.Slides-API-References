---
title: ForEach
second_title: Aspose.Slides के लिए Java API संदर्भ
description: विभिन्न मॉडल वस्तुओं पर इटेरेट करने के लिए अभिप्रेत मेथड्स के एक समूह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/foreach/
---
**विरासत:**  
java.lang.Object  
```
public class ForEach
```

विभिन्न [Presentation](../../com.aspose.slides/presentation) मॉडल वस्तुओं पर इटरिटेड करने के लिए अभिप्रेत मेथड्स का एक समूह दर्शाता है। ये मेथड्स उपयोगी हो सकते हैं यदि आपको कुछ Presentation के तत्वों का फ़ॉर्मेटिंग या सामग्री बदलनी हो, उदाहरण के लिए प्रत्येक पोर्शन का फ़ॉर्मेट बदलना।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, (portion, para, slide, index) ->
>          portion.getPortionFormat().setLatinFont(new FontData("Times New Roman")));
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | प्रत्येक \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें। |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | प्रत्येक \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें। |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | प्रत्येक \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें। |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | प्रत्येक [Shape](../../com.aspose.slides/shape) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें। |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | प्रत्येक  Shape  को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें। |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | प्रत्येक [Shape](../../com.aspose.slides/shape) को [BaseSlide](../../com.aspose.slides/baseslide) में इटेरेट करें। |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | प्रत्येक [Paragraph](../../com.aspose.slides/paragraph) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें। |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | प्रत्येक [Paragraph](../../com.aspose.slides/paragraph) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें। |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | प्रत्येक [Portion](../../com.aspose.slides/portion) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें। |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | प्रत्येक [Portion](../../com.aspose.slides/portion) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें। |
### ForEach() {#ForEach--}
```
public ForEach()
```

### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```

प्रत्येक \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, (slide, index) ->
>          slide.setName(String.format("Slide #%d", index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation को स्लाइड्स पर इटेरेट करने के लिए |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | प्रत्येक स्लाइड के लिए बुलाया जाएगा ऐसा कॉलबैक |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```

प्रत्येक \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.masterSlide(pres, (slide, index) ->
>          slide.setName(String.format("Master Slide #%d", index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation को मास्टर स्लाइड्स पर इटेरेट करने के लिए |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | प्रत्येक मास्टर स्लाइड के लिए बुलाया जाएगा ऐसा कॉलबैक |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```

प्रत्येक \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.layoutSlide(pres, (layoutSlide, index) ->
>          layoutSlide.setName(String.format("Layout Slide #%d", index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation को लेआउट स्लाइड्स पर इटेरेट करने के लिए |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | प्रत्येक लेआउट स्लाइड के लिए बुलाया जाएगा ऐसा कॉलबैक |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```

प्रत्येक [Shape](../../com.aspose.slides/shape) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, (shape, slide, index) ->
>          System.out.println(String.format("%s, index: %d", shape.getName(), index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation को लेआउट शैप्स पर इटेरेट करने के लिए |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | प्रत्येक शैप के लिए बुलाया जाएगा ऐसा कॉलबैक |

Shapes सभी प्रकार की स्लाइड्स में इटेरेट किए जाएंगे - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) और \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```

प्रत्येक  Shape  को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, true, (shape, slide, index) ->
>          System.out.println(String.format("%s, index: %d", shape.getName(), index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation को लेआउट शैप्स पर इटेरेट करने के लिए |
| includeNotes | boolean | यह फ़्लैग दर्शाता है कि क्या NotesSlides को प्रोसेसिंग में शामिल किया जाना चाहिए। |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | प्रत्येक शैप के लिए बुलाया जाएगा ऐसा कॉलबैक |

Shapes सभी प्रकार की स्लाइड्स में इटेरेट किए जाएंगे - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) और [NotesSlide](../../com.aspose.slides/notesslide) यदि आवश्यक हो। |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

प्रत्येक [Shape](../../com.aspose.slides/shape) को [BaseSlide](../../com.aspose.slides/baseslide) में इटेरेट करें।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, (slide, index) ->
>          ForEach.shape(slide, (shape, baseSlide, shapeIndex) ->
>                  System.out.println(String.format("%s, index: %d", shape.getName(), shapeIndex))));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | स्लाइड को लेआउट शैप्स पर इटेरेट करने के लिए |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | प्रत्येक शैप के लिए बुलाया जाएगा ऐसा कॉलबैक |

[BaseSlide](../../com.aspose.slides/baseslide) बेस टाइप है \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) और \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

प्रत्येक [Paragraph](../../com.aspose.slides/paragraph) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, (para, slide, index) ->
>          System.out.println(String.format("%s, index: %d", para.getText(), index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation को पैराग्राफ़्स पर इटेरेट करने के लिए |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | प्रत्येक पैराग्राफ़ के लिए बुलाया जाएगा ऐसा कॉलबैक |

Shapes सभी प्रकार की स्लाइड्स में इटेरेट किए जाएंगे - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) और \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

प्रत्येक [Paragraph](../../com.aspose.slides/paragraph) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, (para, slide, index) ->
>          System.out.println(String.format("%s, index: %d", para.getText(), index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation को पैराग्राफ़्स पर इटेरेट करने के लिए |
| includeNotes | boolean | यह फ़्लैग दर्शाता है कि क्या NotesSlides को प्रोसेसिंग में शामिल किया जाना चाहिए। |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | प्रत्येक पैराग्राफ़ के लिए बुलाया जाएगा ऐसा कॉलबैक |

Shapes सभी प्रकार की स्लाइड्स में इटेरेट किए जाएंगे - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) और [NotesSlide](../../com.aspose.slides/notesslide)

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

प्रत्येक [Portion](../../com.aspose.slides/portion) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, (portion, para, slide, index) ->
>          System.out.println(String.format("%s, index: %d", portion.getText(), index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation को पोर्शन पर इटेरेट करने के लिए |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | प्रत्येक पोर्शन के लिए बुलाया जाएगा ऐसा कॉलबैक |

Portions सभी प्रकार की स्लाइड्स में इटेरेट किए जाएंगे - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) और \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```

प्रत्येक [Portion](../../com.aspose.slides/portion) को [Presentation](../../com.aspose.slides/presentation) में इटेरेट करें।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, true, (portion, para, slide, index) ->
>          System.out.println(String.format("%s, index: %d", portion.getText(), index)));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation को पोर्शन पर इटेरेट करने के लिए |
| includeNotes | boolean | यह फ़्लैग दर्शाता है कि क्या NotesSlides को प्रोसेसिंग में शामिल किया जाना चाहिए। |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | प्रत्येक पोर्शन के लिए बुलाया जाएगा ऐसा कॉलबैक |

Portions सभी प्रकार की स्लाइड्स में इटेरेट किए जाएंगे - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) और [NotesSlide](../../com.aspose.slides/notesslide) |