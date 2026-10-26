---
title: ForEach
second_title: Aspose.Slides Android के लिए, Java API संदर्भ के द्वारा
description: विभिन्न मॉडल ऑब्जेक्ट्स पर इटरेट करने के लिए निर्धारित मेथड्स के समूह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/foreach/
---
**विरासत:**
java.lang.Object
```
public class ForEach
```

विभिन्न [Presentation](../../com.aspose.slides/presentation) मॉडल ऑब्जेक्ट्स पर इटरेट करने के लिए निर्धारित मेथड्स का समूह दर्शाता है। ये मेथड्स उपयोगी हो सकते हैं यदि आपको Presentation के कुछ तत्वों के फ़ॉर्मेटिंग या सामग्री को इटरेट और बदलने की आवश्यकता हो, जैसे प्रत्येक भाग का फ़ॉर्मेटिंग बदलना।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | [Presentation](../../com.aspose.slides/presentation) में प्रत्येक \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) को दोहराएँ। |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | [Presentation](../../com.aspose.slides/presentation) में प्रत्येक \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) को दोहराएँ। |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | [Presentation](../../com.aspose.slides/presentation) में प्रत्येक \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) को दोहराएँ। |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | [Presentation](../../com.aspose.slides/presentation) में प्रत्येक [Shape](../../com.aspose.slides/shape) को दोहराएँ। |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | [Presentation](../../com.aspose.slides/presentation) में प्रत्येक  Shape  को दोहराएँ। |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | [BaseSlide](../../com.aspose.slides/baseslide) में प्रत्येक [Shape](../../com.aspose.slides/shape) को दोहराएँ। |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | [Presentation](../../com.aspose.slides/presentation) में प्रत्येक [Paragraph](../../com.aspose.slides/paragraph) को दोहराएँ। |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | [Presentation](../../com.aspose.slides/presentation) में प्रत्येक [Paragraph](../../com.aspose.slides/paragraph) को दोहराएँ। |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | [Presentation](../../com.aspose.slides/presentation) में प्रत्येक [Portion](../../com.aspose.slides/portion) को दोहराएँ। |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | [Presentation](../../com.aspose.slides/presentation) में प्रत्येक [Portion](../../com.aspose.slides/portion) को दोहराएँ। |
### ForEach() {#ForEach--}
```
public ForEach()
```

### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```

[Presentation](../../com.aspose.slides/presentation) में प्रत्येक \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) को दोहराएँ।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | स्लाइड्स को इटरेट करने के लिए Presentation |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | प्रत्येक स्लाइड के लिए कॉल किया जाएगा ऐसा कॉलबैक |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```

[Presentation](../../com.aspose.slides/presentation) में प्रत्येक \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) को दोहराएँ।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.masterSlide(pres, new ForEach.ForEachMasterSlideCallback() {
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | लेआउट स्लाइड्स को इटरेट करने के लिए Presentation |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | प्रत्येक मास्टर स्लाइड के लिए कॉल किया जाएगा ऐसा कॉलबैक |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```

[Presentation](../../com.aspose.slides/presentation) में प्रत्येक \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) को दोहराएँ।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.layoutSlide(pres, new ForEach.ForEachLayoutSlideCallback() {
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | लेआउट स्लाइड्स को इटरेट करने के लिए Presentation |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | प्रत्येक लेआउट स्लाइड के लिए कॉल किया जाएगा ऐसा कॉलबैक |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```

[Presentation](../../com.aspose.slides/presentation) में प्रत्येक [Shape](../../com.aspose.slides/shape) को दोहराएँ।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, new ForEach.ForEachShapeCallback() {
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | लेआउट शैप्स को इटरेट करने के लिए Presentation |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | प्रत्येक शैप के लिए कॉल किया जाएगा ऐसा कॉलबैक

Shapes सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) और \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```

[Presentation](../../com.aspose.slides/presentation) में प्रत्येक  Shape  को दोहराएँ।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, true, new ForEach.ForEachShapeCallback() {
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | लेआउट शैप्स को इटरेट करने के लिए Presentation |
| includeNotes | boolean | एक फ़्लैग जो इंगित करता है कि क्या NotesSlides को प्रोसेसिंग में शामिल किया जाना चाहिए। |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | प्रत्येक शैप के लिए कॉल किया जाएगा ऐसा कॉलबैक

Shapes सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) और [NotesSlide](../../com.aspose.slides/notesslide) यदि आवश्यक हो। |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

[BaseSlide](../../com.aspose.slides/baseslide) में प्रत्येक [Shape](../../com.aspose.slides/shape) को दोहराएँ।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | लेआउट शैप्स को इटरेट करने के लिए स्लाइड |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | प्रत्येक शैप के लिए कॉल किया जाएगा ऐसा कॉलबैक

[BaseSlide](../../com.aspose.slides/baseslide) सभी प्रकार की स्लाइड्स - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) और \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) के बेस टाइप है। |

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

[Presentation](../../com.aspose.slides/presentation) में प्रत्येक [Paragraph](../../com.aspose.slides/paragraph) को दोहराएँ।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, new ForEach.ForEachParagraphCallback() {
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | पैरेग्राफ़ को इटरेट करने के लिए Presentation |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | प्रत्येक पैरेग्राफ़ के लिए कॉल किया जाएगा ऐसा कॉलबैक

Shapes सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) और \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

[Presentation](../../com.aspose.slides/presentation) में प्रत्येक [Paragraph](../../com.aspose.slides/paragraph) को दोहराएँ।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, new ForEach.ForEachParagraphCallback() {
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | पैरेग्राफ़ को इटरेट करने के लिए Presentation |
| includeNotes | boolean | एक फ़्लैग जो इंगित करता है कि क्या NotesSlides को प्रोसेसिंग में शामिल किया जाना चाहिए। |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | प्रत्येक पैरेग्राफ़ के लिए कॉल किया जाएगा ऐसा कॉलबैक

Shapes सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) और [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

[Presentation](../../com.aspose.slides/presentation) में प्रत्येक [Portion](../../com.aspose.slides/portion) को दोहराएँ।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | पोर्शन को इटरेट करने के लिए Presentation |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | प्रत्येक पोर्शन के लिए कॉल किया जाएगा ऐसा कॉलबैक

Portions सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) और \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```

[Presentation](../../com.aspose.slides/presentation) में प्रत्येक [Portion](../../com.aspose.slides/portion) को दोहराएँ।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, true, new ForEach.ForEachPortionCallback() {
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | पोर्शन को इटरेट करने के लिए Presentation |
| includeNotes | boolean | एक फ़्लैग जो इंगित करता है कि क्या NotesSlides को प्रोसेसिंग में शामिल किया जाना चाहिए। |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | प्रत्येक पोर्शन के लिए कॉल किया जाएगा ऐसा कॉलबैक

Portions सभी प्रकार की स्लाइड्स में दोहराए जाएंगे - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) और [NotesSlide](../../com.aspose.slides/notesslide) |