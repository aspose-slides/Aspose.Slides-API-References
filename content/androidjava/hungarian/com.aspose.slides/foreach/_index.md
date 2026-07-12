---
title: ForEach
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Egy olyan metóduscsoportot képvisel, amely különböző modellobjektumok felett történő iterálásra szolgál.
type: docs
url: /hu/com.aspose.slides/foreach/
---
**Öröklés:**
java.lang.Object
```
public class ForEach
```

Csoportot képvisel a módszerek, amelyek különböző [Presentation](../../com.aspose.slides/presentation) modellobjektumokon való iterálásra lettek tervezve. Ezek a módszerek hasznosak lehetnek, ha iterálnod kell és módosítanod kell a Presentation elemeinek formázását vagy tartalmát, például minden részlet formázását.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | Iterál minden \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) a(z) [Presentation](../../com.aspose.slides/presentation)-ben. |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | Iterál minden \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) a(z) [Presentation](../../com.aspose.slides/presentation)-ban. |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | Iterál minden \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) a(z) [Presentation](../../com.aspose.slides/presentation)-ban. |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | Iterál minden [Shape](../../com.aspose.slides/shape) a(z) [Presentation](../../com.aspose.slides/presentation)-ban. |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | Iterál minden  Shape  a(z) [Presentation](../../com.aspose.slides/presentation)-ben. |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | Iterál minden [Shape](../../com.aspose.slides/shape) a(z) [BaseSlide](../../com.aspose.slides/baseslide)-ban. |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | Iterál minden [Paragraph](../../com.aspose.slides/paragraph) a(z) [Presentation](../../com.aspose.slides/presentation)-ban. |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | Iterál minden [Paragraph](../../com.aspose.slides/paragraph) a(z) [Presentation](../../com.aspose.slides/presentation)-ban. |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | Iterál minden [Portion](../../com.aspose.slides/portion) a(z) [Presentation](../../com.aspose.slides/presentation)-ban. |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | Iterál minden [Portion](../../com.aspose.slides/portion) a(z) [Presentation](../../com.aspose.slides/presentation)-ban. |
### ForEach() {#ForEach--}
```
public ForEach()
```


### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```


Iterál minden \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) a(z) [Presentation](../../com.aspose.slides/presentation)-ben.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation a diák iterálásához |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | Visszahívás, amely minden diára meghívásra kerül |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```


Iterál minden \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) a(z) [Presentation](../../com.aspose.slides/presentation)-ban.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.masterSlide(pres, new ForEach.ForEachMasterSlideCallback() {
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation a mesterdiák iterálásához |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | Visszahívás, amely minden mesterdiára meghívásra kerül |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```


Iterál minden \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) a(z) [Presentation](../../com.aspose.slides/presentation)-ban.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.layoutSlide(pres, new ForEach.ForEachLayoutSlideCallback() {
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation a elrendezésdiák iterálásához |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | Visszahívás, amely minden elrendezésdiára meghívásra kerül |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```


Iterál minden [Shape](../../com.aspose.slides/shape) a(z) [Presentation](../../com.aspose.slides/presentation)-ban.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, new ForEach.ForEachShapeCallback() {
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation a elrendezés alakzatok iterálásához |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Visszahívás, amely minden alakzatra meghívásra kerül

--------------------

Az alakzatok minden típusú dián iterálódnak - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) és \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```


Iterál minden  Shape  a(z) [Presentation](../../com.aspose.slides/presentation)-ban.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, true, new ForEach.ForEachShapeCallback() {
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation a elrendezés alakzatok iterálásához |
| includeNotes | boolean | Jelző, amely meghatározza, hogy a NotesSlides bele legyenek vonva a feldolgozásba. |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Visszahívás, amely minden alakzatra meghívásra kerül

--------------------

Az alakzatok minden típusú dián iterálódnak - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) és [NotesSlide](../../com.aspose.slides/notesslide) ha szükséges. |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```


Iterál minden [Shape](../../com.aspose.slides/shape) a(z) [BaseSlide](../../com.aspose.slides/baseslide)-ban.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | Dia az elrendezés alakzatok iterálásához |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Visszahívás, amely minden alakzatra meghívásra kerül

--------------------

[BaseSlide](../../com.aspose.slides/baseslide) az alap típus a \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) és \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) számára |

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```


Iterál minden [Paragraph](../../com.aspose.slides/paragraph) a(z) [Presentation](../../com.aspose.slides/presentation)-ban.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, new ForEach.ForEachParagraphCallback() {
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation a bekezdések iterálásához |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Visszahívás, amely minden bekezdésre meghívásra kerül

--------------------

Az alakzatok minden típusú dián iterálódnak - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) és \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```


Iterál minden [Paragraph](../../com.aspose.slides/paragraph) a(z) [Presentation](../../com.aspose.slides/presentation)-ban.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, new ForEach.ForEachParagraphCallback() {
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation a bekezdések iterálásához |
| includeNotes | boolean | Jelző, amely meghatározza, hogy a NotesSlides bele legyenek vonva a feldolgozásba. |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Visszahívás, amely minden bekezdésre meghívásra kerül

--------------------

Az alakzatok minden típusú dián iterálódnak - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) és [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```


Iterál minden [Portion](../../com.aspose.slides/portion) a(z) [Presentation](../../com.aspose.slides/presentation)-ban.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation a részletek iterálásához |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Visszahívás, amely minden részletre meghívásra kerül

--------------------

A részletek minden típusú dián iterálódnak - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) és \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```


Iterál minden [Portion](../../com.aspose.slides/portion) a(z) [Presentation](../../com.aspose.slides/presentation)-ban.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, true, new ForEach.ForEachPortionCallback() {
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation a részletek iterálásához |
| includeNotes | boolean | Jelző, amely meghatározza, hogy a NotesSlides bele legyenek vonva a feldolgozásba. |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Visszahívás, amely minden részletre meghívásra kerül

--------------------

A részletek minden típusú dián iterálódnak - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) és [NotesSlide](../../com.aspose.slides/notesslide) |