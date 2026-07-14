---
title: ForEach
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهنده یک گروه از متدهاست که برای تکرار بر روی اشیاء مدل متفاوت طراحی شده‌اند.
type: docs
url: /fa/com.aspose.slides/foreach/
---
**ارث‌بری:**
java.lang.Object
```
public class ForEach
```

نمایش‌دهنده مجموعه‌ای از متدهاست که برای تکرار بر روی اشیاء مدل [Presentation](../../com.aspose.slides/presentation) متفاوت طراحی شده‌اند. این متدها می‌توانند مفید باشند اگر نیاز داشته باشید که بر روی عناصر Presentation تکرار کنید و قالب‌بندی یا محتوا را تغییر دهید، به عنوان مثال قالب‌بندی هر بخش را تغییر دهید.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | تکرار هر \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) در [Presentation](../../com.aspose.slides/presentation). |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | تکرار هر \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) در [Presentation](../../com.aspose.slides/presentation). |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | تکرار هر \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) در [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | تکرار هر [Shape](../../com.aspose.slides/shape) در [Presentation](../../com.aspose.slides/presentation). |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | تکرار هر  Shape  در [Presentation](../../com.aspose.slides/presentation). |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | تکرار هر [Shape](../../com.aspose.slides/shape) در [BaseSlide](../../com.aspose.slides/baseslide). |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | تکرار هر [Paragraph](../../com.aspose.slides/paragraph) در [Presentation](../../com.aspose.slides/presentation). |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | تکرار هر [Paragraph](../../com.aspose.slides/paragraph) در [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | تکرار هر [Portion](../../com.aspose.slides/portion) در [Presentation](../../com.aspose.slides/presentation). |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | تکرار هر [Portion](../../com.aspose.slides/portion) در [Presentation](../../com.aspose.slides/presentation). |
### ForEach() {#ForEach--}
```
public ForEach()
```


### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```


تکرار هر \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) در [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار اسلایدها |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | Callback که برای هر اسلاید فراخوانی می‌شود |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```


تکرار هر \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) در [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.masterSlide(pres, new ForEach.ForEachMasterSlideCallback() {
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار اسلایدهای اصلی |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | Callback که برای هر اسلاید اصلی فراخوانی می‌شود |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```


تکرار هر \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) در [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.layoutSlide(pres, new ForEach.ForEachLayoutSlideCallback() {
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار اسلایدهای چیدمان |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | Callback که برای هر اسلاید چیدمان فراخوانی می‌شود |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```


تکرار هر [Shape](../../com.aspose.slides/shape) در [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, new ForEach.ForEachShapeCallback() {
> ```


**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار اشکال چیدمان |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback که برای هر شکل فراخوانی می‌شود

اکنون اشکال در تمام انواع اسلایدها - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) تکرار می‌شوند |

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```


تکرار هر  Shape  در [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, true, new ForEach.ForEachShapeCallback() {
> ```


**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار اشکال چیدمان |
| includeNotes | boolean | پرچمی که نشان می‌دهد آیا اسلایدهای یادداشت باید در پردازش گنجانده شوند. |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback که برای هر شکل فراخوانی می‌شود

اکنون اشکال در تمام انواع اسلایدها - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)، \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) و [NotesSlide](../../com.aspose.slides/notesslide) در صورت نیاز تکرار می‌شوند. |

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```


تکرار هر [Shape](../../com.aspose.slides/shape) در [BaseSlide](../../com.aspose.slides/baseslide).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```


**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | اسلاید برای تکرار اشکال چیدمان |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | Callback که برای هر شکل فراخوانی می‌شود

[BaseSlide](../../com.aspose.slides/baseslide) پایه‌ای برای \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) است.

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```


تکرار هر [Paragraph](../../com.aspose.slides/paragraph) در [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, new ForEach.ForEachParagraphCallback() {
> ```


**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار پاراگراف‌ها |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback که برای هر پاراگراف فراخوانی می‌شود

اکنون اشکال در تمام انواع اسلایدها - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) تکرار می‌شوند |

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```


تکرار هر [Paragraph](../../com.aspose.slides/paragraph) در [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, new ForEach.ForEachParagraphCallback() {
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار پاراگراف‌ها |
| includeNotes | boolean | پرچمی که نشان می‌دهد آیا اسلایدهای یادداشت باید در پردازش گنجانده شوند. |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | Callback که برای هر پاراگراف فراخوانی می‌شود

اکنون اشکال در تمام انواع اسلایدها - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)، \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) و [NotesSlide](../../com.aspose.slides/notesslide) تکرار می‌شوند |

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```


تکرار هر [Portion](../../com.aspose.slides/portion) در [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار بخش‌ها |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Callback که برای هر بخش فراخوانی می‌شود

اکنون بخش‌ها در تمام انواع اسلایدها - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) و \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) تکرار می‌شوند |

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```


تکرار هر [Portion](../../com.aspose.slides/portion) در [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, true, new ForEach.ForEachPortionCallback() {
> ```


**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentation برای تکرار بخش‌ها |
| includeNotes | boolean | پرچمی که نشان می‌دهد آیا اسلایدهای یادداشت باید در پردازش گنجانده شوند. |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | Callback که برای هر بخش فراخوانی می‌شود

اکنون بخش‌ها در تمام انواع اسلایدها - \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)، \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)، \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) و [NotesSlide](../../com.aspose.slides/notesslide) تکرار می‌شوند |