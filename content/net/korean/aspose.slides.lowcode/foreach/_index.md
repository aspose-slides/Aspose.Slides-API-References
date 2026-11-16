---
title: ForEach
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 다양한 Presentation../aspose.slides/presentation 모델 객체를 반복하도록 설계된 메서드 그룹을 나타냅니다. 이러한 메서드는 Presentation 요소의 서식이나 콘텐츠를 반복적으로 변경해야 할 때, 예를 들어 각 구획의 서식을 변경하는 경우에 유용합니다.
type: docs
weight: 7920
url: /ko/aspose.slides.lowcode/foreach/
---
## ForEach 클래스

다양한 [`Presentation`](../../aspose.slides/presentation) 모델 객체를 반복하도록 설계된 메서드 그룹을 나타냅니다. 프레젠테이션 요소의 서식이나 내용을 반복적으로 변경해야 할 때, 예를 들어 각 구획의 서식을 변경하는 경우에 유용하게 사용할 수 있습니다.

```csharp
public static class ForEach
```

## 메서드

| Name | Description |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | 각 [`LayoutSlide`](./layoutslide)을 [`Presentation`](../../aspose.slides/presentation)에서 반복합니다. |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | 각 [`MasterSlide`](./masterslide)를 [`Presentation`](../../aspose.slides/presentation)에서 반복합니다. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | 각 [`Paragraph`](./paragraph)를 [`Presentation`](../../aspose.slides/presentation)에서 반복합니다. 도형은 모든 종류의 슬라이드—[`Slide`](./slide), [`MasterSlide`](./masterslide) 및 [`LayoutSlide`](./layoutslide)—에서 반복됩니다. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | 각 [`Paragraph`](./paragraph)를 [`Presentation`](../../aspose.slides/presentation)에서 반복합니다. 도형은 모든 종류의 슬라이드—[`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) 및 [`NotesSlide`](../../aspose.slides/notesslide)—에서 반복됩니다. |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | 각 [`Portion`](./portion)를 [`Presentation`](../../aspose.slides/presentation)에서 반복합니다. 구획은 모든 종류의 슬라이드—[`Slide`](./slide), [`MasterSlide`](./masterslide) 및 [`LayoutSlide`](./layoutslide)—에서 반복됩니다. |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | 각 [`Portion`](./portion)를 [`Presentation`](../../aspose.slides/presentation)에서 반복합니다. 구획은 모든 종류의 슬라이드—[`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) 및 [`NotesSlide`](../../aspose.slides/notesslide)—에서 반복됩니다. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | 각 [`Shape`](./shape)를 [`BaseSlide`](../../aspose.slides/baseslide)에서 반복합니다. [`BaseSlide`](../../aspose.slides/baseslide)는 [`Slide`](./slide), [`MasterSlide`](./masterslide) 및 [`LayoutSlide`](./layoutslide)의 기본 유형입니다. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | 각 [`Shape`](./shape)를 [`Presentation`](../../aspose.slides/presentation)에서 반복합니다. 도형은 모든 종류의 슬라이드—[`Slide`](./slide), [`MasterSlide`](./masterslide) 및 [`LayoutSlide`](./layoutslide)—에서 반복됩니다. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | 각 [`Shape`](./shape)를 [`Presentation`](../../aspose.slides/presentation)에서 반복합니다. 필요에 따라 도형은 모든 종류의 슬라이드—[`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) 및 [`NotesSlide`](../../aspose.slides/notesslide)—에서 반복됩니다. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | 각 [`Slide`](./slide)를 [`Presentation`](../../aspose.slides/presentation)에서 반복합니다. |

## 기타 멤버

| Name | Description |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | [`Presentation`](../../aspose.slides/presentation)의 각 [`LayoutSlide`](./layoutslide)에 대해 호출되는 콜백입니다. |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | [`Presentation`](../../aspose.slides/presentation)의 각 [`MasterSlide`](./masterslide)에 대해 호출되는 콜백입니다. |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | [`BaseSlide`](../../aspose.slides/baseslide)의 각 [`Paragraph`](./paragraph)에 대해 호출되는 콜백입니다. |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | [`BaseSlide`](../../aspose.slides/baseslide)의 [`Paragraph`](./paragraph)에 있는 각 [`Portion`](./portion)에 대해 호출되는 콜백입니다. |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | [`Presentation`](../../aspose.slides/presentation)의 각 [`Shape`](./shape)에 대해 호출되는 콜백입니다. |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | [`Presentation`](../../aspose.slides/presentation)의 각 [`Slide`](./slide)에 대해 호출되는 콜백입니다. |

### 예제

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

### 관련 항목

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->