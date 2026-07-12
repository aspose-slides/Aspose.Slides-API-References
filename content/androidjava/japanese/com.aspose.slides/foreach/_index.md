---
title: ForEach
second_title: Aspose.Slides for Android の Java API リファレンス
description: さまざまなモデルオブジェクトを反復処理することを目的としたメソッドのグループを表します。
type: docs
url: /ja/com.aspose.slides/foreach/
---
**継承:**  
java.lang.Object  
```
public class ForEach
```

さまざまな [Presentation](../../com.aspose.slides/presentation) モデル オブジェクトを反復処理することを目的としたメソッドのグループを表します。これらのメソッドは、Presentation の要素の書式や内容を反復して変更する必要がある場合、たとえば各 portion の書式を変更する場合に役立ちます。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ForEach()](#ForEach--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)](#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-) | [Presentation](../../com.aspose.slides/presentation) 内の \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) を反復処理します。 |
| [masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)](#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-) | [Presentation](../../com.aspose.slides/presentation) 内の \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) を反復処理します。 |
| [layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)](#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-) | [Presentation](../../com.aspose.slides/presentation) 内の \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) を反復処理します。 |
| [shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-) | [Presentation](../../com.aspose.slides/presentation) 内の [Shape](../../com.aspose.slides/shape) を反復処理します。 |
| [shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-) | [Presentation](../../com.aspose.slides/presentation) 内の Shape を反復処理します。 |
| [shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)](#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-) | [BaseSlide](../../com.aspose.slides/baseslide) 内の [Shape](../../com.aspose.slides/shape) を反復処理します。 |
| [paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-) | [Presentation](../../com.aspose.slides/presentation) 内の [Paragraph](../../com.aspose.slides/paragraph) を反復処理します。 |
| [paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)](#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-) | [Presentation](../../com.aspose.slides/presentation) 内の [Paragraph](../../com.aspose.slides/paragraph) を反復処理します。 |
| [portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-) | [Presentation](../../com.aspose.slides/presentation) 内の [Portion](../../com.aspose.slides/portion) を反復処理します。 |
| [portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)](#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-) | [Presentation](../../com.aspose.slides/presentation) 内の [Portion](../../com.aspose.slides/portion) を反復処理します。 |
### ForEach() {#ForEach--}
```
public ForEach()
```

### slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide) {#slide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachSlideCallback-}
```
public static void slide(Presentation pres, ForEach.ForEachSlideCallback forEachSlide)
```

[Presentation](../../com.aspose.slides/presentation) 内の \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback) を反復処理します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | スライドを反復処理する Presentation |
| forEachSlide | [ForEachSlideCallback](../../com.aspose.slides/foreachslidecallback) | 各スライドについて呼び出されるコールバック |

### masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide) {#masterSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachMasterSlideCallback-}
```
public static void masterSlide(Presentation pres, ForEach.ForEachMasterSlideCallback forEachMasterSlide)
```

[Presentation](../../com.aspose.slides/presentation) 内の \#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) を反復処理します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.masterSlide(pres, new ForEach.ForEachMasterSlideCallback() {
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | マスタースライドを反復処理する Presentation |
| forEachMasterSlide | [ForEachMasterSlideCallback](../../com.aspose.slides/foreachmasterslidecallback) | 各マスター スライドに対して呼び出されるコールバック |

### layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide) {#layoutSlide-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachLayoutSlideCallback-}
```
public static void layoutSlide(Presentation pres, ForEach.ForEachLayoutSlideCallback forEachLayoutSlide)
```

[Presentation](../../com.aspose.slides/presentation) 内の \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) を反復処理します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.layoutSlide(pres, new ForEach.ForEachLayoutSlideCallback() {
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | レイアウトスライドを反復処理する Presentation |
| forEachLayoutSlide | [ForEachLayoutSlideCallback](../../com.aspose.slides/foreachlayoutslidecallback) | 各レイアウト スライドに対して呼び出されるコールバック |

### shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, ForEach.ForEachShapeCallback forEachShape)
```

[Presentation](../../com.aspose.slides/presentation) 内の [Shape](../../com.aspose.slides/shape) を反復処理します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, new ForEach.ForEachShapeCallback() {
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | レイアウトシェイプを反復処理する Presentation |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 各シェイプに対して呼び出されるコールバック |

シェイプはすべての種類のスライド、\#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) および \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) で反復処理されます。

### shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(Presentation pres, boolean includeNotes, ForEach.ForEachShapeCallback forEachShape)
```

[Presentation](../../com.aspose.slides/presentation) 内の Shape を反復処理します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.shape(pres, true, new ForEach.ForEachShapeCallback() {
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | レイアウトシェイプを反復処理する Presentation |
| includeNotes | boolean | 処理に NotesSlides を含めるかどうかを示すフラグ |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 各シェイプに対して呼び出されるコールバック |

シェイプはすべての種類のスライド、\#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)、\#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) と、必要に応じて [NotesSlide](../../com.aspose.slides/notesslide) でも反復処理されます。

### shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape) {#shape-com.aspose.slides.BaseSlide-com.aspose.slides.ForEach.ForEachShapeCallback-}
```
public static void shape(BaseSlide baseSlide, ForEach.ForEachShapeCallback forEachShape)
```

[BaseSlide](../../com.aspose.slides/baseslide) 内の [Shape](../../com.aspose.slides/shape) を反復処理します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.slide(pres, new ForEach.ForEachSlideCallback() {
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseSlide | [BaseSlide](../../com.aspose.slides/baseslide) | レイアウトシェイプを反復処理するスライド |
| forEachShape | [ForEachShapeCallback](../../com.aspose.slides/foreachshapecallback) | 各シェイプに対して呼び出されるコールバック

[BaseSlide](../../com.aspose.slides/baseslide) は \#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) および \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) の基底型です。

### paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, ForEach.ForEachParagraphCallback forEachParagraph)
```

[Presentation](../../com.aspose.slides/presentation) 内の [Paragraph](../../com.aspose.slides/paragraph) を反復処理します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, new ForEach.ForEachParagraphCallback() {
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 段落を反復処理する Presentation |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | 各段落に対して呼び出されるコールバック

段落はすべての種類のスライド、\#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) と \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) で反復処理されます。

### paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph) {#paragraph-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachParagraphCallback-}
```
public static void paragraph(Presentation pres, boolean includeNotes, ForEach.ForEachParagraphCallback forEachParagraph)
```

[Presentation](../../com.aspose.slides/presentation) 内の [Paragraph](../../com.aspose.slides/paragraph) を反復処理します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.paragraph(pres, true, new ForEach.ForEachParagraphCallback() {
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 段落を反復処理する Presentation |
| includeNotes | boolean | 処理に NotesSlides を含めるかどうかを示すフラグ |
| forEachParagraph | [ForEachParagraphCallback](../../com.aspose.slides/foreachparagraphcallback) | 各段落に対して呼び出されるコールバック

段落はすべての種類のスライド、\#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)、\#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) と [NotesSlide](../../com.aspose.slides/notesslide) で反復処理されます。

### portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, ForEach.ForEachPortionCallback forEachPortion)
```

[Presentation](../../com.aspose.slides/presentation) 内の [Portion](../../com.aspose.slides/portion) を反復処理します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, new ForEach.ForEachPortionCallback() {
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ポーションを反復処理する Presentation |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | 各ポーションに対して呼び出されるコールバック

ポーションはすべての種類のスライド、\#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback) と \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) で反復処理されます。

### portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion) {#portion-com.aspose.slides.Presentation-boolean-com.aspose.slides.ForEach.ForEachPortionCallback-}
```
public static void portion(Presentation pres, boolean includeNotes, ForEach.ForEachPortionCallback forEachPortion)
```

[Presentation](../../com.aspose.slides/presentation) 内の [Portion](../../com.aspose.slides/portion) を反復処理します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      ForEach.portion(pres, true, new ForEach.ForEachPortionCallback() {
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ポーションを反復処理する Presentation |
| includeNotes | boolean | 処理に NotesSlides を含めるかどうかを示すフラグ |
| forEachPortion | [ForEachPortionCallback](../../com.aspose.slides/foreachportioncallback) | 各ポーションに対して呼び出されるコールバック

ポーションはすべての種類のスライド、\#slide(Presentation,ForEachSlideCallback).slide(Presentation,ForEachSlideCallback)、\#masterSlide(Presentation,ForEachMasterSlideCallback).masterSlide(Presentation,ForEachMasterSlideCallback)、\#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) と [NotesSlide](../../com.aspose.slides/notesslide) で反復処理されます。