---
title: ForEach
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um grupo de métodos destinados a iterar sobre diferentes objetos de modelo.
type: docs
url: /pt/com.aspose.slides/foreach/
---
**Herança:**
java.lang.Object
```
public class ForEach
```

Representa um grupo de métodos destinados a iterar sobre diferentes [Presentation](../../com.aspose.slides/presentation) objetos de modelo. Esses métodos podem ser úteis se você precisar iterar e alterar a formatação ou o conteúdo de alguns elementos da Presentation, por exemplo, mudar a formatação de cada porção.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | Iterar cada \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) no [Presentation](../../com.aspose.slides/presentation). |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | Iterar cada \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) no [Presentation](../../com.aspose.slides/presentation). |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | Iterar cada \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) no [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | Iterar cada [Shape](../../com.aspose.slides/shape) no [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | Iterar cada  Shape  no [Presentation](../../com.aspose.slides/presentation). |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | Iterar cada [Shape](../../com.aspose.slides/shape) no [BaseSlide](../../com.aspose.slides/baseslide). |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | Iterar cada [Paragraph](../../com.aspose.slides/paragraph) no [Presentation](../../com.aspose.slides/presentation). |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | Iterar cada [Paragraph](../../com.aspose.slides/paragraph) no [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | Iterar cada [Portion](../../com.aspose.slides/portion) no [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | Iterar cada [Portion](../../com.aspose.slides/portion) no [Presentation](../../com.aspose.slides/presentation). |
### ForEach() {#ForEach--}
```
public ForEach()
```


### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```


Iterar cada \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) no [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar slides |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | Callback que será invocado para cada slide |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```


Iterar cada \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) no [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.masterSlide(pres, new ForEach.ForEachMasterSlideCallback() {
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar master slides |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | Callback que será invocado para cada master slide |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```


Iterar cada \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) no [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.layoutSlide(pres, new ForEach.ForEachLayoutSlideCallback() {
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar layout slides |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | Callback que será invocado para cada layout slide |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```


Iterar cada [Shape](../../com.aspose.slides/shape) no [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, new ForEach.ForEachShapeCallback() {
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar layout shapes |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback que será invocado para cada shape

Shapes serão iterados em todos os tipos de slides - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) e \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```


Iterar cada  Shape  no [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, true, new ForEach.ForEachShapeCallback() {
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar layout shapes |
| includeNotes | boolean | Flag que indica se NotesSlides devem ser incluídos no processamento. |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback que será invocado para cada shape

Shapes serão iterados em todos os tipos de slides - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) e [NotesSlide](../../com.aspose.slides/notesslide) se necessário. |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```


Iterar cada [Shape](../../com.aspose.slides/shape) no [BaseSlide](../../com.aspose.slides/baseslide).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | Slide para iterar layout shapes |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback que será invocado para cada shape

[BaseSlide](../../com.aspose.slides/baseslide) é o tipo base para \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) e \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```


Iterar cada [Paragraph](../../com.aspose.slides/paragraph) no [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, new ForEach.ForEachParagraphCallback() {
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar paragraphs |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback que será invocado para cada paragraph

Shapes serão iterados em todos os tipos de slides - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) e \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```


Iterar cada [Paragraph](../../com.aspose.slides/paragraph) no [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, new ForEach.ForEachParagraphCallback() {
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar paragraphs |
| includeNotes | boolean | Flag que indica se NotesSlides devem ser incluídos no processamento. |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback que será invocado para cada paragraph

Shapes serão iterados em todos os tipos de slides - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) e [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```


Iterar cada [Portion](../../com.aspose.slides/portion) no [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar portions |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Callback que será invocado para cada portion

Portions serão iterados em todos os tipos de slides - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) e \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```


Iterar cada [Portion](../../com.aspose.slides/portion) no [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, true, new ForEach.ForEachPortionCallback() {
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar portions |
| includeNotes | boolean | Flag que indica se NotesSlides devem ser incluídos no processamento. |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Callback que será invocado para cada portion

Portions serão iterados em todos os tipos de slides - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) e [NotesSlide](../../com.aspose.slides/notesslide) |