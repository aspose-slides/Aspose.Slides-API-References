---
title: ForEach
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un gruppo di metodi destinati a iterare su diversi oggetti modello.
type: docs
url: /it/com.aspose.slides/foreach/
---
**Ereditarietà:**
java.lang.Object
```
public class ForEach
```

Rappresenta un gruppo di metodi destinati a iterare su diversi oggetti modello [Presentation](../../com.aspose.slides/presentation). Questi metodi possono essere utili se è necessario iterare e modificare la formattazione o il contenuto di alcuni elementi di Presentation, ad es. modificare la formattazione di ogni porzione.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | Itera ciascuno \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) nel [Presentation](../../com.aspose.slides/presentation). |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | Itera ciascuno \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) nel [Presentation](../../com.aspose.slides/presentation). |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | Itera ciascuno \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) nel [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | Itera ciascuno [Shape](../../com.aspose.slides/shape) nel [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | Itera ciascuno  Shape  nel [Presentation](../../com.aspose.slides/presentation). |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | Itera ciascuno [Shape](../../com.aspose.slides/shape) nel [BaseSlide](../../com.aspose.slides/baseslide). |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | Itera ciascuno [Paragraph](../../com.aspose.slides/paragraph) nel [Presentation](../../com.aspose.slides/presentation). |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | Itera ciascuno [Paragraph](../../com.aspose.slides/paragraph) nel [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | Itera ciascuno [Portion](../../com.aspose.slides/portion) nel [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | Itera ciascuno [Portion](../../com.aspose.slides/portion) nel [Presentation](../../com.aspose.slides/presentation). |
### ForEach() {#ForEach--}
```
public ForEach()
```

### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```

Itera ciascuno \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) nel [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation per iterare le diapositive |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | Callback che verrà invocato per ogni diapositiva |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```

Itera ciascuno \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) nel [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.masterSlide(pres, new ForEach.ForEachMasterSlideCallback() {
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation per iterare le diapositive master |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | Callback che verrà invocato per ogni diapositiva master |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```

Itera ciascuno \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) nel [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.layoutSlide(pres, new ForEach.ForEachLayoutSlideCallback() {
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation per iterare le diapositive layout |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | Callback che verrà invocato per ogni diapositiva layout |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```

Itera ciascuno [Shape](../../com.aspose.slides/shape) nel [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, new ForEach.ForEachShapeCallback() {
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation per iterare le forme del layout |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback che verrà invocato per ogni forma

Le forme saranno iterate in tutti i tipi di diapositive - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) e \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```

Itera ciascuno  Shape  nel [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, true, new ForEach.ForEachShapeCallback() {
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation per iterare le forme del layout |
| includeNotes | boolean | Flag che indica se le diapositive note devono essere incluse nel processo. |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback che verrà invocato per ogni forma

Le forme saranno iterate in tutti i tipi di diapositive - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) e [NotesSlide](../../com.aspose.slides/notesslide) se necessario. |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

Itera ciascuno [Shape](../../com.aspose.slides/shape) nel [BaseSlide](../../com.aspose.slides/baseslide).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | Diapositiva per iterare le forme del layout |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback che verrà invocato per ogni forma

[BaseSlide](../../com.aspose.slides/baseslide) è il tipo base per \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) e \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

Itera ciascuno [Paragraph](../../com.aspose.slides/paragraph) nel [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, new ForEach.ForEachParagraphCallback() {
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation per iterare i paragrafi |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback che verrà invocato per ogni paragrafo

Le forme saranno iterate in tutti i tipi di diapositive - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) e \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

Itera ciascuno [Paragraph](../../com.aspose.slides/paragraph) nel [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, new ForEach.ForEachParagraphCallback() {
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation per iterare i paragrafi |
| includeNotes | boolean | Flag che indica se le diapositive note devono essere incluse nel processo. |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback che verrà invocato per ogni paragrafo

Le forme saranno iterate in tutti i tipi di diapositive - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) e [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

Itera ciascuno [Portion](../../com.aspose.slides/portion) nel [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation per iterare le porzioni |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Callback che verrà invocato per ogni porzione

Le porzioni saranno iterate in tutti i tipi di diapositive - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) e \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```

Itera ciascuno [Portion](../../com.aspose.slides/portion) nel [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, true, new ForEach.ForEachPortionCallback() {
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation per iterare le porzioni |
| includeNotes | boolean | Flag che indica se le diapositive note devono essere incluse nel processo. |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Callback che verrà invocato per ogni porzione

Le porzioni saranno iterate in tutti i tipi di diapositive - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) e [NotesSlide](../../com.aspose.slides/notesslide) |