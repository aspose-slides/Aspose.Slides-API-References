---
title: ForEach
second_title: Aspose.Sildes for .NET API リファレンス
description: さまざまな Presentation../aspose.slides/presentation モデルオブジェクトを反復処理することを目的としたメソッドのグループを表します。これらのメソッドは、Presentation の要素の書式やコンテンツを反復処理して変更する必要がある場合、たとえば各部分の書式を変更する際に便利です。
type: docs
weight: 7900
url: /ja/aspose.slides.lowcode/foreach/
---
## ForEach クラス

さまざまな [`Presentation`](../../aspose.slides/presentation) モデルオブジェクトを反復処理することを目的としたメソッドのグループを表します。これらのメソッドは、Presentation の要素の書式や内容を反復処理して変更する必要がある場合、たとえば各部分の書式を変更する場合に便利です。

```csharp
public static class ForEach
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | [`Presentation`](../../aspose.slides/presentation) の各 [`LayoutSlide`](./layoutslide) を反復処理します。 |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | [`Presentation`](../../aspose.slides/presentation) の各 [`MasterSlide`](./masterslide) を反復処理します。 |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | [`Presentation`](../../aspose.slides/presentation) の各 [`Paragraph`](./paragraph) を反復処理します。すべてのスライドタイプ（[`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide)）でシェイプが反復処理されます。 |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | [`Presentation`](../../aspose.slides/presentation) の各 [`Paragraph`](./paragraph) を反復処理します。すべてのスライドタイプ（[`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide)、[`NotesSlide`](../../aspose.slides/notesslide)）でシェイプが反復処理されます。 |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | [`Presentation`](../../aspose.slides/presentation) の各 [`Portion`](./portion) を反復処理します。すべてのスライドタイプ（[`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide)）でポーションが反復処理されます。 |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | [`Presentation`](../../aspose.slides/presentation) の各 [`Portion`](./portion) を反復処理します。すべてのスライドタイプ（[`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide)、[`NotesSlide`](../../aspose.slides/notesslide)）でポーションが反復処理されます。 |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | [`BaseSlide`](../../aspose.slides/baseslide) の各 [`Shape`](./shape) を反復処理します。[`BaseSlide`](../../aspose.slides/baseslide) は [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide) の基底タイプです。 |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | [`Presentation`](../../aspose.slides/presentation) の各 [`Shape`](./shape) を反復処理します。すべてのスライドタイプ（[`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide)）でシェイプが反復処理されます。 |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | [`Presentation`](../../aspose.slides/presentation) の各 [`Shape`](./shape) を反復処理します。すべてのスライドタイプ（[`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide)、[`NotesSlide`](../../aspose.slides/notesslide)）でシェイプが必要に応じて反復処理されます。 |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | [`Presentation`](../../aspose.slides/presentation) の各 [`Slide`](./slide) を反復処理します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | [`Presentation`](../../aspose.slides/presentation) の各 [`LayoutSlide`](./layoutslide) に対して呼び出されるコールバックです。 |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | [`Presentation`](../../aspose.slides/presentation) の各 [`MasterSlide`](./masterslide) に対して呼び出されるコールバックです。 |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | [`BaseSlide`](../../aspose.slides/baseslide) の各 [`Paragraph`](./paragraph) に対して呼び出されるコールバックです。 |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | [`BaseSlide`](../../aspose.slides/baseslide) の [`Paragraph`](./paragraph) にある各 [`Portion`](./portion) に対して呼び出されるコールバックです。 |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | [`Presentation`](../../aspose.slides/presentation) の各 [`Shape`](./shape) に対して呼び出されるコールバックです。 |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | [`Presentation`](../../aspose.slides/presentation) の各 [`Slide`](./slide) に対して呼び出されるコールバックです。 |

### 例

```csharp
using (Presentation presentation = new Presentation("pres.pptx"))
{
   ForEach.Portion(presentation, (portion, para, slide, index) =>
   {
       portion.PortionFormat.LatinFont = new FontData("Times New Roman");
   });
  
   presentation.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### 参照

* 名前空間 [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->