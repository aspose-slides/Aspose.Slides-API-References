---
title: ForEach
second_title: Aspose.Sildes for .NET API リファレンス
description: 異なる Presentation../aspose.slides/presentation モデルオブジェクトを反復処理することを目的としたメソッドのグループを表します。これらのメソッドは、Presentation の要素の書式やコンテンツを反復して変更する必要がある場合、たとえば各部分の書式を変更する際に便利です。
type: docs
weight: 7880
url: /ja/aspose.slides.lowcode/foreach/
---
## ForEach クラス

異なる [`Presentation`](../../aspose.slides/presentation) モデルオブジェクトを反復処理することを目的としたメソッドのグループを表します。これらのメソッドは、Presentation の要素の書式や内容を反復して変更する必要がある場合に便利です。例えば、各部分の書式を変更するなどです。

```csharp
public static class ForEach
```

## メソッド

| Name | Description |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | 各 [`LayoutSlide`](./layoutslide) を [`Presentation`](../../aspose.slides/presentation) 内で反復処理します。 |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | 各 [`MasterSlide`](./masterslide) を [`Presentation`](../../aspose.slides/presentation) 内で反復処理します。 |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | 各 [`Paragraph`](./paragraph) を [`Presentation`](../../aspose.slides/presentation) 内で反復処理します。シェイプはすべてのスライドタイプ – [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide) で反復処理されます。 |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | 各 [`Paragraph`](./paragraph) を [`Presentation`](../../aspose.slides/presentation) 内で反復処理します。シェイプはすべてのスライドタイプ – [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide)、[`NotesSlide`](../../aspose.slides/notesslide) で反復処理されます。 |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | 各 [`Portion`](./portion) を [`Presentation`](../../aspose.slides/presentation) 内で反復処理します。部分はすべてのスライドタイプ – [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide) で反復処理されます。 |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | 各 [`Portion`](./portion) を [`Presentation`](../../aspose.slides/presentation) 内で反復処理します。部分はすべてのスライドタイプ – [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide)、[`NotesSlide`](../../aspose.slides/notesslide) で反復処理されます。 |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | 各 [`Shape`](./shape) を [`BaseSlide`](../../aspose.slides/baseslide) 内で反復処理します。[`BaseSlide`](../../aspose.slides/baseslide) は [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide) の基底型です。 |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | 各 [`Shape`](./shape) を [`Presentation`](../../aspose.slides/presentation) 内で反復処理します。シェイプはすべてのスライドタイプ – [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide) で反復処理されます。 |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | 各 [`Shape`](./shape) を [`Presentation`](../../aspose.slides/presentation) 内で反復処理します。シェイプはすべてのスライドタイプ – [`Slide`](./slide)、[`MasterSlide`](./masterslide)、[`LayoutSlide`](./layoutslide)、[`NotesSlide`](../../aspose.slides/notesslide) で必要に応じて反復処理されます。 |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | 各 [`Slide`](./slide) を [`Presentation`](../../aspose.slides/presentation) 内で反復処理します。 |

## その他のメンバー

| Name | Description |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | 各 [`LayoutSlide`](./layoutslide) を [`Presentation`](../../aspose.slides/presentation) で呼び出すコールバックです。 |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | 各 [`MasterSlide`](./masterslide) を [`Presentation`](../../aspose.slides/presentation) で呼び出すコールバックです。 |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | 各 [`Paragraph`](./paragraph) を [`BaseSlide`](../../aspose.slides/baseslide) 上で呼び出すコールバックです。 |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | 各 [`Portion`](./portion) を [`Paragraph`](./paragraph) の [`BaseSlide`](../../aspose.slides/baseslide) 上で呼び出すコールバックです。 |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | 各 [`Shape`](./shape) を [`Presentation`](../../aspose.slides/presentation) で呼び出すコールバックです。 |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | 各 [`Slide`](./slide) を [`Presentation`](../../aspose.slides/presentation) で呼び出すコールバックです。 |

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