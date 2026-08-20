---
title: ForEach
second_title: Aspose.Slides for Java API 레퍼런스
description: 다양한 모델 객체를 반복하도록 설계된 메서드 그룹을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/foreach/
---
**상속:**
java.lang.Object
```
public class ForEach
```

다양한 [Presentation](../../com.aspose.slides/presentation) 모델 객체를 반복하도록 설계된 메서드 그룹을 나타냅니다. 프레젠테이션 요소의 서식이나 내용을 반복하면서 변경해야 하는 경우, 예를 들어 각 포션의 서식을 변경하는 경우 등에 이러한 메서드가 유용할 수 있습니다.

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
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | 각 \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다. |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | 각 \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다. |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | 각 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다. |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | 각 [Shape](../../com.aspose.slides/shape)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다. |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | 각 Shape을 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다. |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | 각 [Shape](../../com.aspose.slides/shape)를 [BaseSlide](../../com.aspose.slides/baseslide)에서 반복합니다. |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | 각 [Paragraph](../../com.aspose.slides/paragraph)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다. |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | 각 [Paragraph](../../com.aspose.slides/paragraph)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다. |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | 각 [Portion](../../com.aspose.slides/portion)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다. |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | 각 [Portion](../../com.aspose.slides/portion)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다. |
### ForEach() {#ForEach--}
```
public ForEach()
```

### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```

각 \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다.

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
**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 슬라이드를 반복하기 위한 Presentation |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | 각 슬라이드에 대해 호출되는 콜백 |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```

각 \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다.

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
**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 마스터 슬라이드를 반복하기 위한 Presentation |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | 각 마스터 슬라이드에 대해 호출되는 콜백 |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```

각 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다.

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
**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 레이아웃 슬라이드를 반복하기 위한 Presentation |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | 각 레이아웃 슬라이드에 대해 호출되는 콜백 |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```

각 [Shape](../../com.aspose.slides/shape)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다.

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
**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 레이아웃 Shape를 반복하기 위한 Presentation |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 각 Shape에 대해 호출되는 콜백

모든 유형의 슬라이드에서 Shape가 반복됩니다 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 및 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```

각 Shape을 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다.

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
**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 레이아웃 Shape를 반복하기 위한 Presentation |
| includeNotes | boolean | NotesSlides를 처리에 포함시킬지 여부를 나타내는 플래그 |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 각 Shape에 대해 호출되는 콜백

모든 유형의 슬라이드에서 Shape가 반복됩니다 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 및 [NotesSlide](../../com.aspose.slides/notesslide)(필요한 경우) |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

각 [Shape](../../com.aspose.slides/shape)를 [BaseSlide](../../com.aspose.slides/baseslide)에서 반복합니다.

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
**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | Layout Shape를 반복하기 위한 Slide |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 각 Shape에 대해 호출되는 콜백

[BaseSlide](../../com.aspose.slides/baseslide)는 \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 및 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback)의 기본 유형입니다.

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

각 [Paragraph](../../com.aspose.slides/paragraph)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다.

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
**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 문단을 반복하기 위한 Presentation |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | 각 문단에 대해 호출되는 콜백

모든 유형의 슬라이드에서 Shape가 반복됩니다 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 및 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

각 [Paragraph](../../com.aspose.slides/paragraph)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다.

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
**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 문단을 반복하기 위한 Presentation |
| includeNotes | boolean | NotesSlides를 처리에 포함시킬지 여부를 나타내는 플래그 |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | 각 문단에 대해 호출되는 콜백

모든 유형의 슬라이드에서 Shape가 반복됩니다 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 및 [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

각 [Portion](../../com.aspose.slides/portion)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다.

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
**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 포션을 반복하기 위한 Presentation |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | 각 포션에 대해 호출되는 콜백

포션은 모든 유형의 슬라이드에서 반복됩니다 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) 및 \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```

각 [Portion](../../com.aspose.slides/portion)를 [Presentation](../../com.aspose.slides/presentation)에서 반복합니다.

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
**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 포션을 반복하기 위한 Presentation |
| includeNotes | boolean | NotesSlides를 처리에 포함시킬지 여부를 나타내는 플래그 |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | 각 포션에 대해 호출되는 콜백

포션은 모든 유형의 슬라이드에서 반복됩니다 - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) 및 [NotesSlide](../../com.aspose.slides/notesslide) |