---
title: ForEach
second_title: Aspose.Sildes for .NET API リファレンス
description: さまざまな Presentation../aspose.slides/presentation モデル オブジェクトを反復処理することを目的としたメソッドのグループを表します。これらのメソッドは、Presentation の要素の書式やコンテンツを反復して変更する必要がある場合に便利です。例として各部分の書式を変更できます。
type: docs
weight: 7920
url: /ja/aspose.slides.lowcode/foreach/
---
## ForEach クラス

異なる [`Presentation`](../../aspose.slides/presentation) モデル オブジェクトを反復処理することを目的としたメソッドのグループを表します。これらのメソッドは、Presentation の要素の書式や内容を反復して変更する必要がある場合に便利です。たとえば、各部分の書式を変更することができます。

```csharp
public static class ForEach
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | [`Presentation`](../../aspose.slides/presentation) 内の各 [`LayoutSlide`](./layoutslide) を反復処理します。 |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | [`Presentation`](../../aspose.slides/presentation) 内の各 [`MasterSlide`](./masterslide) を反復処理します。 |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | [`Presentation`](../../aspose.slides/presentation) 内の各 [`Paragraph`](./paragraph) を反復処理します。シェイプはすべてのスライドタイプ - [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide) で反復処理されます。 |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | [`Presentation`](../../aspose.slides/presentation) 内の各 [`Paragraph`](./paragraph) を反復処理します。シェイプはすべてのスライドタイプ - [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide)、[`NotesSlide`](../../aspose.slides/notesslide) で反復処理されます。 |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | [`Presentation`](../../aspose.slides/presentation) 内の各 [`Portion`](./portion) を反復処理します。部分はすべてのスライドタイプ - [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide) で反復処理されます。 |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | [`Presentation`](../../aspose.slides/presentation) 内の各 [`Portion`](./portion) を反復処理します。部分はすべてのスライドタイプ - [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide)、[`NotesSlide`](../../aspose.slides/notesslide) で反復処理されます。 |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | [`BaseSlide`](../../aspose.slides/baseslide) 内の各 [`Shape`](./shape) を反復処理します。[`BaseSlide`](../../aspose.slides/baseslide) は [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide) の基底タイプです。 |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | [`Presentation`](../../aspose.slides/presentation) 内の各 [`Shape`](./shape) を反復処理します。シェイプはすべてのスライドタイプ - [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide) で反復処理されます。 |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | [`Presentation`](../../aspose.slides/presentation) 内の各 [`Shape`](./shape) を反復処理します。シェイプは必要に応じて、すべてのスライドタイプ - [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide)、[`NotesSlide`](../../aspose.slides/notesslide) で反復処理されます。 |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | [`Presentation`](../../aspose.slides/presentation) 内の各 [`Slide`](./slide) を反復処理します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | [`Presentation`](../../aspose.slides/presentation) 内の各 [`LayoutSlide`](./layoutslide) に対して呼び出されるコールバックです。 |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | [`Presentation`](../../aspose.slides/presentation) 内の各 [`MasterSlide`](./masterslide) に対して呼び出されるコールバックです。 |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | [`BaseSlide`](../../aspose.slides/baseslide) 上の各 [`Paragraph`](./paragraph) に対して呼び出されるコールバックです。 |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | [`BaseSlide`](../../aspose.slides/baseslide) 上の [`Paragraph`](./paragraph) 内の各 [`Portion`](./portion) に対して呼び出されるコールバックです。 |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | [`Presentation`](../../aspose.slides/presentation) 内の各 [`Shape`](./shape) に対して呼び出されるコールバックです。 |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | [`Presentation`](../../aspose.slides/presentation) 内の各 [`Slide`](./slide) に対して呼び出されるコールバックです。 |

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

### 関連項目

* 名前空間 [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->