---
title: ForEach
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 다양한 Presentation../aspose.slides/presentation 모델 객체를 반복하도록 설계된 메서드 그룹을 나타냅니다. 이러한 메서드는 Presentation 요소의 서식이나 내용을 반복하고 변경해야 할 때, 예를 들어 각 부분 서식을 변경하는 경우에 유용합니다.
type: docs
weight: 7900
url: /ko/aspose.slides.lowcode/foreach/
---
## ForEach 클래스

다양한 [`Presentation`](../../aspose.slides/presentation) 모델 객체를 반복하도록 설계된 메서드 그룹을 나타냅니다. 이러한 메서드는 Presentation 요소의 서식이나 내용을 반복적으로 변경해야 할 때, 예를 들어 각 부분 서식을 변경하는 경우에 유용합니다.

```csharp
public static class ForEach
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | [`Presentation`](../../aspose.slides/presentation)에서 각 [`LayoutSlide`](./layoutslide)를 반복합니다. |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | [`Presentation`](../../aspose.slides/presentation)에서 각 [`MasterSlide`](./masterslide)를 반복합니다. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | [`Presentation`](../../aspose.slides/presentation)에서 각 [`Paragraph`](./paragraph)를 반복합니다. 도형은 모든 종류의 슬라이드 - [`Slide`](./slide), [`MasterSlide`](./masterslide) 및 [`LayoutSlide`](./layoutslide)에서 반복됩니다. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | [`Presentation`](../../aspose.slides/presentation)에서 각 [`Paragraph`](./paragraph)를 반복합니다. 도형은 모든 종류의 슬라이드 - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) 및 [`NotesSlide`](../../aspose.slides/notesslide)에서 반복됩니다. |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | [`Presentation`](../../aspose.slides/presentation)에서 각 [`Portion`](./portion)를 반복합니다. 구획은 모든 종류의 슬라이드 - [`Slide`](./slide), [`MasterSlide`](./masterslide) 및 [`LayoutSlide`](./layoutslide)에서 반복됩니다. |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | [`Presentation`](../../aspose.slides/presentation)에서 각 [`Portion`](./portion)를 반복합니다. 구획은 모든 종류의 슬라이드 - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) 및 [`NotesSlide`](../../aspose.slides/notesslide)에서 반복됩니다. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | [`BaseSlide`](../../aspose.slides/baseslide)에서 각 [`Shape`](./shape)를 반복합니다. [`BaseSlide`](../../aspose.slides/baseslide)는 [`Slide`](./slide), [`MasterSlide`](./masterslide) 및 [`LayoutSlide`](./layoutslide)의 기본 유형입니다. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | [`Presentation`](../../aspose.slides/presentation)에서 각 [`Shape`](./shape)를 반복합니다. 도형은 모든 종류의 슬라이드 - [`Slide`](./slide), [`MasterSlide`](./masterslide) 및 [`LayoutSlide`](./layoutslide)에서 반복됩니다. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | [`Presentation`](../../aspose.slides/presentation)에서 각 [`Shape`](./shape)를 반복합니다. 필요에 따라 도형은 모든 종류의 슬라이드 - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) 및 [`NotesSlide`](../../aspose.slides/notesslide)에서 반복됩니다. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | [`Presentation`](../../aspose.slides/presentation)에서 각 [`Slide`](./slide)를 반복합니다. |

## 기타 멤버

| 이름 | 설명 |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | 각 [`LayoutSlide`](./layoutslide)에 대해 [`Presentation`](../../aspose.slides/presentation)에서 호출되는 콜백입니다. |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | 각 [`MasterSlide`](./masterslide)에 대해 [`Presentation`](../../aspose.slides/presentation)에서 호출되는 콜백입니다. |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | 각 [`Paragraph`](./paragraph)에 대해 [`BaseSlide`](../../aspose.slides/baseslide)에서 호출되는 콜백입니다. |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | [`Paragraph`](./paragraph)의 [`BaseSlide`](../../aspose.slides/baseslide)에 있는 [`Portion`](./portion)마다 호출되는 콜백입니다. |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | 각 [`Shape`](./shape)에 대해 [`Presentation`](../../aspose.slides/presentation)에서 호출되는 콜백입니다. |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | 각 [`Slide`](./slide)에 대해 [`Presentation`](../../aspose.slides/presentation)에서 호출되는 콜백입니다. |

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

### 참조

* 네임스페이스 [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->