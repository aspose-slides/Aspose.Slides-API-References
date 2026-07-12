---
title: ForEach
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa un grupo de métodos destinados a iterar sobre diferentes objetos del modelo.
type: docs
url: /es/com.aspose.slides/foreach/
---
**Herencia:**
java.lang.Object
```
public class ForEach
```

Representa un grupo de métodos destinados a iterar sobre diferentes [Presentation](../../com.aspose.slides/presentation) objetos del modelo. Estos métodos pueden ser útiles si necesita iterar y cambiar el formato o contenido de algunos elementos de Presentation, p. ej. cambiar el formato de cada porción.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | Iterar cada \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) en el [Presentation](../../com.aspose.slides/presentation). |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | Iterar cada \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) en el [Presentation](../../com.aspose.slides/presentation). |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | Iterar cada \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) en el [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | Iterar cada [Shape](../../com.aspose.slides/shape) en el [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | Iterar cada  Shape  en el [Presentation](../../com.aspose.slides/presentation). |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | Iterar cada [Shape](../../com.aspose.slides/shape) en el [BaseSlide](../../com.aspose.slides/baseslide). |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | Iterar cada [Paragraph](../../com.aspose.slides/paragraph) en el [Presentation](../../com.aspose.slides/presentation). |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | Iterar cada [Paragraph](../../com.aspose.slides/paragraph) en el [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | Iterar cada [Portion](../../com.aspose.slides/portion) en el [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | Iterar cada [Portion](../../com.aspose.slides/portion) en el [Presentation](../../com.aspose.slides/presentation). |
### ForEach() {#ForEach--}
```
public ForEach()
```


### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```


Iterar cada \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) en el [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar las diapositivas |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | Callback que se invocará para cada diapositiva |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```


Iterar cada \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) en el [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.masterSlide(pres, new ForEach.ForEachMasterSlideCallback() {
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar las diapositivas maestras |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | Callback que se invocará para cada diapositiva maestra |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```


Iterar cada \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) en el [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.layoutSlide(pres, new ForEach.ForEachLayoutSlideCallback() {
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar las diapositivas de diseño |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | Callback que se invocará para cada diapositiva de diseño |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```


Iterar cada [Shape](../../com.aspose.slides/shape) en el [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, new ForEach.ForEachShapeCallback() {
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar las formas de diseño |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback que se invocará para cada forma

Las formas se iterarán en todo tipo de diapositivas - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) y \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```


Iterar cada  Shape  en el [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, true, new ForEach.ForEachShapeCallback() {
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar las formas de diseño |
| includeNotes | boolean | Bandera que indica si NotesSlides debe incluirse en el procesamiento. |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback que se invocará para cada forma

Las formas se iterarán en todo tipo de diapositivas - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) y [NotesSlide](../../com.aspose.slides/notesslide) si es necesario. |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```


Iterar cada [Shape](../../com.aspose.slides/shape) en el [BaseSlide](../../com.aspose.slides/baseslide).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | Diapositiva para iterar las formas de diseño |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback que se invocará para cada forma

[BaseSlide](../../com.aspose.slides/baseslide) es el tipo base para \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) y \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```


Iterar cada [Paragraph](../../com.aspose.slides/paragraph) en el [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, new ForEach.ForEachParagraphCallback() {
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar los párrafos |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback que se invocará para cada párrafo

Las formas se iterarán en todo tipo de diapositivas - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) y \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```


Iterar cada [Paragraph](../../com.aspose.slides/paragraph) en el [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, new ForEach.ForEachParagraphCallback() {
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar los párrafos |
| includeNotes | boolean | Bandera que indica si NotesSlides debe incluirse en el procesamiento. |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback que se invocará para cada párrafo

Las formas se iterarán en todo tipo de diapositivas - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) y [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```


Iterar cada [Portion](../../com.aspose.slides/portion) en el [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar las porciones |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Callback que se invocará para cada porción

Las porciones se iterarán en todo tipo de diapositivas - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) y \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```


Iterar cada [Portion](../../com.aspose.slides/portion) en el [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, true, new ForEach.ForEachPortionCallback() {
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation para iterar las porciones |
| includeNotes | boolean | Bandera que indica si NotesSlides debe incluirse en el procesamiento. |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Callback que se invocará para cada porción

Las porciones se iterarán en todo tipo de diapositivas - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) y [NotesSlide](../../com.aspose.slides/notesslide) |