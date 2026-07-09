---
title: ForEach
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: "Biểu thị một nhóm các phương thức nhằm lặp lại các đối tượng mô hình Presentation../aspose.slides/presentation khác nhau. Các phương thức này có thể hữu ích nếu bạn cần lặp lại và thay đổi định dạng hoặc nội dung của một số yếu tố Presentation, ví dụ: thay đổi định dạng của từng phần."
type: docs
weight: 7900
url: /vi/aspose.slides.lowcode/foreach/
---
## Lớp ForEach

Biểu thị một nhóm các phương thức nhằm lặp lại các đối tượng mô hình [`Presentation`](../../aspose.slides/presentation) khác nhau. Những phương thức này có thể hữu ích nếu bạn cần lặp lại và thay đổi một số định dạng hoặc nội dung của các yếu tố trong Presentation, ví dụ: thay đổi định dạng của từng phần.

```csharp
public static class ForEach
```

## Phương thức

| Tên | Mô tả |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Duyệt từng [`LayoutSlide`](./layoutslide) trong [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Duyệt từng [`MasterSlide`](./masterslide) trong [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Duyệt từng [`Paragraph`](./paragraph) trong [`Presentation`](../../aspose.slides/presentation). Các Shape sẽ được duyệt trong tất cả các loại slide - [`Slide`](./slide), [`MasterSlide`](./masterslide) và [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Duyệt từng [`Paragraph`](./paragraph) trong [`Presentation`](../../aspose.slides/presentation). Các Shape sẽ được duyệt trong tất cả các loại slide - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) và [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Duyệt từng [`Portion`](./portion) trong [`Presentation`](../../aspose.slides/presentation). Các Portion sẽ được duyệt trong tất cả các loại slide - [`Slide`](./slide), [`MasterSlide`](./masterslide) và [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Duyệt từng [`Portion`](./portion) trong [`Presentation`](../../aspose.slides/presentation). Các Portion sẽ được duyệt trong tất cả các loại slide - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) và [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Duyệt từng [`Shape`](./shape) trong [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) là kiểu cơ sở cho [`Slide`](./slide), [`MasterSlide`](./masterslide) và [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Duyệt từng [`Shape`](./shape) trong [`Presentation`](../../aspose.slides/presentation). Các Shape sẽ được duyệt trong tất cả các loại slide - [`Slide`](./slide), [`MasterSlide`](./masterslide) và [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Duyệt từng [`Shape`](./shape) trong [`Presentation`](../../aspose.slides/presentation). Các Shape sẽ được duyệt trong tất cả các loại slide - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) và [`NotesSlide`](../../aspose.slides/notesslide) nếu cần. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Duyệt từng [`Slide`](./slide) trong [`Presentation`](../../aspose.slides/presentation). |

## Các thành viên khác

| Tên | Mô tả |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback sẽ được gọi cho mỗi [`LayoutSlide`](./layoutslide) trong [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback sẽ được gọi cho mỗi [`MasterSlide`](./masterslide) trong [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback sẽ được gọi cho mỗi [`Paragraph`](./paragraph) trên [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback sẽ được gọi cho mỗi [`Portion`](./portion) trong [`Paragraph`](./paragraph) trên [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback sẽ được gọi cho mỗi [`Shape`](./shape) trong [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback sẽ được gọi cho mỗi [`Slide`](./slide) trong [`Presentation`](../../aspose.slides/presentation). |

### Ví dụ

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

### Xem thêm

* không gian tên [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->