---
title: ForEach
second_title: Aspose.Slides for Java API Referansı
description: Farklı model nesneleri üzerinde yineleme yapmak amaçlı bir yöntem grubunu temsil eder.
type: docs
url: /tr/com.aspose.slides/foreach/
---
**Kalıtım:**
java.lang.Object
```
public class ForEach
```

Farklı [Presentation](../../com.aspose.slides/presentation) model nesneleri üzerinde döngü yapmak için tasarlanmış bir yöntem grubu temsil eder. Bu yöntemler, bazı Presentation öğelerinin biçimlendirmesini veya içeriğini yineleyerek değiştirmek istediğinizde faydalı olabilir, örn. her bölümün biçimini değiştirmek.

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
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | [Presentation](../../com.aspose.slides/presentation) içinde her \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) öğesini yinele. |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | [Presentation](../../com.aspose.slides/presentation) içinde her \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) öğesini yinele. |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | [Presentation](../../com.aspose.slides/presentation) içinde her \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) öğesini yinele. |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | [Presentation](../../com.aspose.slides/presentation) içinde her [Shape](../../com.aspose.slides/shape) öğesini yinele. |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | [Presentation](../../com.aspose.slides/presentation) içinde her Shape öğesini yinele. |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | [BaseSlide](../../com.aspose.slides/baseslide) içinde her [Shape](../../com.aspose.slides/shape) öğesini yinele. |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | [Presentation](../../com.aspose.slides/presentation) içinde her [Paragraph](../../com.aspose.slides/paragraph) öğesini yinele. |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | [Presentation](../../com.aspose.slides/presentation) içinde her [Paragraph](../../com.aspose.slides/paragraph) öğesini yinele. |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | [Presentation](../../com.aspose.slides/presentation) içinde her [Portion](../../com.aspose.slides/portion) öğesini yinele. |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | [Presentation](../../com.aspose.slides/presentation) içinde her [Portion](../../com.aspose.slides/portion) öğesini yinele. |
### ForEach() {#ForEach--}
```
public ForEach()
```

### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```

[Presentation](../../com.aspose.slides/presentation) içinde her \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) öğesini yinele.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Slaytları yinelemek için Presentation |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | Her slayt için çağrılacak geri arama |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```

[Presentation](../../com.aspose.slides/presentation) içinde her \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) öğesini yinele.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Master slaytları yinelemek için Presentation |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | Her master slayt için çağrılacak geri arama |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```

[Presentation](../../com.aspose.slides/presentation) içinde her \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) öğesini yinele.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Layout slaytlarını yinelemek için Presentation |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | Her layout slayt için çağrılacak geri arama |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```

[Presentation](../../com.aspose.slides/presentation) içinde her [Shape](../../com.aspose.slides/shape) öğesini yinele.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Layout şekillerini yinelemek için Presentation |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Her şekil için çağrılacak geri arama |

Şekiller, tüm slayt tiplerinde yineleyecektir - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) ve \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```

[Presentation](../../com.aspose.slides/presentation) içinde her Shape öğesini yinele.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Layout şekillerini yinelemek için Presentation |
| includeNotes | boolean | Not slaytlarının işleme dahil edilip edilmeyeceğini belirten işaret. |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Her şekil için çağrılacak geri arama |

Şekiller, tüm slayt tiplerinde yineleyecektir - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) ve [NotesSlide](../../com.aspose.slides/notesslide) gerektiğinde. |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

[BaseSlide](../../com.aspose.slides/baseslide) içinde her [Shape](../../com.aspose.slides/shape) öğesini yinele.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | Layout şekillerini yinelemek için Slide |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Her şekil için çağrılacak geri arama |

[BaseSlide](../../com.aspose.slides/baseslide), \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) ve \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) için temel tiptir.

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

[Presentation](../../com.aspose.slides/presentation) içinde her [Paragraph](../../com.aspose.slides/paragraph) öğesini yinele.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Paragrafları yinelemek için Presentation |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Her paragraf için çağrılacak geri arama |

Şekiller, tüm slayt tiplerinde yineleyecektir - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) ve \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

[Presentation](../../com.aspose.slides/presentation) içinde her [Paragraph](../../com.aspose.slides/paragraph) öğesini yinele.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Paragrafları yinelemek için Presentation |
| includeNotes | boolean | Not slaytlarının işleme dahil edilip edilmeyeceğini belirten işaret. |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Her paragraf için çağrılacak geri arama |

Şekiller, tüm slayt tiplerinde yineleyecektir - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) ve [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

[Presentation](../../com.aspose.slides/presentation) içinde her [Portion](../../com.aspose.slides/portion) öğesini yinele.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bölümleri yinelemek için Presentation |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Her bölüm için çağrılacak geri arama |

Bölümler, tüm slayt tiplerinde yineleyecektir - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) ve \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```

[Presentation](../../com.aspose.slides/presentation) içinde her [Portion](../../com.aspose.slides/portion) öğesini yinele.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bölümleri yinelemek için Presentation |
| includeNotes | boolean | Not slaytlarının işleme dahil edilip edilmeyeceğini belirten işaret. |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Her bölüm için çağrılacak geri arama |

Bölümler, tüm slayt tiplerinde yineleyecektir - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) ve [NotesSlide](../../com.aspose.slides/notesslide) |