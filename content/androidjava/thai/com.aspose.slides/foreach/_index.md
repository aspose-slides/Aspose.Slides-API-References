---
title: ForEach
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แทนกลุ่มของเมธอดที่มีจุดประสงค์เพื่อทำซ้ำวัตถุโมเดลต่าง ๆ
type: docs
url: /th/com.aspose.slides/foreach/
---
**การสืบทอด:**
java.lang.Object
```
public class ForEach
```

แทนกลุ่มของเมธอดที่มีจุดประสงค์เพื่อทำซ้ำวัตถุโมเดล [Presentation](../../com.aspose.slides/presentation) ต่าง ๆ เมธอดเหล่านี้อาจเป็นประโยชน์หากคุณต้องการทำซ้ำและเปลี่ยนการจัดรูปแบบหรือเนื้อหาของส่วนประกอบบางอย่างใน Presentation เช่น เปลี่ยนการจัดรูปแบบของแต่ละ portion

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | ทำซ้ำแต่ละ \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) ใน [Presentation](../../com.aspose.slides/presentation). |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | ทำซ้ำแต่ละ \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) ใน [Presentation](../../com.aspose.slides/presentation). |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | ทำซ้ำแต่ละ \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) ใน [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | ทำซ้ำแต่ละ [Shape](../../com.aspose.slides/shape) ใน [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | ทำซ้ำแต่ละ  Shape  ใน [Presentation](../../com.aspose.slides/presentation). |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | ทำซ้ำแต่ละ [Shape](../../com.aspose.slides/shape) ใน [BaseSlide](../../com.aspose.slides/baseslide). |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | ทำซ้ำแต่ละ [Paragraph](../../com.aspose.slides/paragraph) ใน [Presentation](../../com.aspose.slides/presentation). |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | ทำซ้ำแต่ละ [Paragraph](../../com.aspose.slides/paragraph) ใน [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | ทำซ้ำแต่ละ [Portion](../../com.aspose.slides/portion) ใน [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | ทำซ้ำแต่ละ [Portion](../../com.aspose.slides/portion) ใน [Presentation](../../com.aspose.slides/presentation). |

### ForEach() {#ForEach--}
```
public ForEach()
```

### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```

ทำซ้ำแต่ละ \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) ใน [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation เพื่อทำซ้ำสไลด์ |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | Callback ที่จะถูกเรียกสำหรับแต่ละสไลด์ |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```

ทำซ้ำแต่ละ \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) ใน [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.masterSlide(pres, new ForEach.ForEachMasterSlideCallback() {
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation เพื่อทำซ้ำมาสเตอร์สไลด์ |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | Callback ที่จะถูกเรียกสำหรับแต่ละมาสเตอร์สไลด์ |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```

ทำซ้ำแต่ละ \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) ใน [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.layoutSlide(pres, new ForEach.ForEachLayoutSlideCallback() {
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation เพื่อทำซ้ำเลย์เอาต์สไลด์ |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | Callback ที่จะถูกเรียกสำหรับแต่ละเลย์เอาต์สไลด์ |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```

ทำซ้ำแต่ละ [Shape](../../com.aspose.slides/shape) ใน [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, new ForEach.ForEachShapeCallback() {
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation เพื่อทำซ้ำเลย์เอาต์รูปร่าง |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback ที่จะถูกเรียกสำหรับแต่ละรูปร่าง |

รูปร่างจะถูกทำซ้ำในสไลด์ทุกประเภท - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) และ \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```

ทำซ้ำแต่ละ  Shape  ใน [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, true, new ForEach.ForEachShapeCallback() {
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation เพื่อทำซ้ำเลย์เอาต์รูปร่าง |
| includeNotes | boolean | ธงที่ระบุว่าควรรวม NotesSlides ในการประมวลผลหรือไม่ |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback ที่จะถูกเรียกสำหรับแต่ละรูปร่าง |

รูปร่างจะถูกทำซ้ำในสไลด์ทุกประเภท - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) และ [NotesSlide](../../com.aspose.slides/notesslide) หากจำเป็น | 

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

ทำซ้ำแต่ละ [Shape](../../com.aspose.slides/shape) ใน [BaseSlide](../../com.aspose.slides/baseslide).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | สไลด์เพื่อทำซ้ำเลย์เอาต์รูปร่าง |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback ที่จะถูกเรียกสำหรับแต่ละรูปร่าง |

[BaseSlide](../../com.aspose.slides/baseslide) เป็นประเภทพื้นฐานสำหรับ \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) และ \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

ทำซ้ำแต่ละ [Paragraph](../../com.aspose.slides/paragraph) ใน [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, new ForEach.ForEachParagraphCallback() {
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation เพื่อทำซ้ำย่อหน้า |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback ที่จะถูกเรียกสำหรับแต่ละย่อหน้า |

รูปร่างจะถูกทำซ้ำในสไลด์ทุกประเภท - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) และ \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

ทำซ้ำแต่ละ [Paragraph](../../com.aspose.slides/paragraph) ใน [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, new ForEach.ForEachParagraphCallback() {
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation เพื่อทำซ้ำย่อหน้า |
| includeNotes | boolean | ธงที่ระบุว่าควรรวม NotesSlides ในการประมวลผลหรือไม่ |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback ที่จะถูกเรียกสำหรับแต่ละย่อหน้า |

รูปร่างจะถูกทำซ้ำในสไลด์ทุกประเภท - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) และ [NotesSlide](../../com.aspose.slides/notesslide) |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

ทำซ้ำแต่ละ [Portion](../../com.aspose.slides/portion) ใน [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation เพื่อทำซ้ำส่วนย่อย |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Callback ที่จะถูกเรียกสำหรับแต่ละส่วนย่อย |

ส่วนย่อยจะถูกทำซ้ำในสไลด์ทุกประเภท - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) และ \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```

ทำซ้ำแต่ละ [Portion](../../com.aspose.slides/portion) ใน [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, true, new ForEach.ForEachPortionCallback() {
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation เพื่อทำซ้ำส่วนย่อย |
| includeNotes | boolean | ธงที่ระบุว่าควรรวม NotesSlides ในการประมวลผลหรือไม่ |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Callback ที่จะถูกเรียกสำหรับแต่ละส่วนย่อย

ส่วนย่อยจะถูกทำซ้ำในสไลด์ทุกประเภท - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback), \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback), \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) และ [NotesSlide](../../com.aspose.slides/notesslide) |