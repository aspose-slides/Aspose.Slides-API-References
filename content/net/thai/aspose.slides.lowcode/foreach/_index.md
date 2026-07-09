---
title: ForEach
second_title: Aspose.Sildes สำหรับ .NET การอ้างอิง API
description: เป็นตัวแทนของกลุ่มเมธอดที่ออกแบบมาเพื่อวนซ้ำ over ต่าง ๆ ของวัตถุ Presentation../aspose.slides/presentation model objects. เมธอดเหล่านี้อาจมีประโยชน์หากคุณต้องการวนซ้ำและเปลี่ยนแปลงการจัดรูปแบบหรือเนื้อหาของบางส่วนของ Presentation เช่น เปลี่ยนการจัดรูปแบบของแต่ละ portion.
type: docs
weight: 7900
url: /th/aspose.slides.lowcode/foreach/
---
## คลาส ForEach

Represents a group of methods intended to iterate over different [`Presentation`](../../aspose.slides/presentation) model objects. These methods can be useful if you need to iterate and change some Presentation' elements formatting or content, e.g. change each portion formatting.

```csharp
public static class ForEach
```

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | วนซ้ำแต่ละ [`LayoutSlide`](./layoutslide) ใน [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | วนซ้ำแต่ละ [`MasterSlide`](./masterslide) ใน [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | วนซ้ำแต่ละ [`Paragraph`](./paragraph) ใน [`Presentation`](../../aspose.slides/presentation). รูปร่างจะถูกวนซ้ำในสไลด์ทุกประเภท - [`Slide`](./slide), [`MasterSlide`](./masterslide) และ [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | วนซ้ำแต่ละ [`Paragraph`](./paragraph) ใน [`Presentation`](../../aspose.slides/presentation). รูปร่างจะถูกวนซ้ำในสไลด์ทุกประเภท - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) และ [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | วนซ้ำแต่ละ [`Portion`](./portion) ใน [`Presentation`](../../aspose.slides/presentation). Portion จะถูกวนซ้ำในสไลด์ทุกประเภท - [`Slide`](./slide), [`MasterSlide`](./masterslide) และ [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | วนซ้ำแต่ละ [`Portion`](./portion) ใน [`Presentation`](../../aspose.slides/presentation). Portions จะถูกวนซ้ำในสไลด์ทุกประเภท - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) และ [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | วนซ้ำแต่ละ [`Shape`](./shape) ใน [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) เป็นประเภทพื้นฐานสำหรับ [`Slide`](./slide), [`MasterSlide`](./masterslide) และ [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | วนซ้ำแต่ละ [`Shape`](./shape) ใน [`Presentation`](../../aspose.slides/presentation). รูปร่างจะถูกวนซ้ำในสไลด์ทุกประเภท - [`Slide`](./slide), [`MasterSlide`](./masterslide) และ [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | วนซ้ำแต่ละ [`Shape`](./shape) ใน [`Presentation`](../../aspose.slides/presentation). รูปร่างจะถูกวนซ้ำในสไลด์ทุกประเภท - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) และ [`NotesSlide`](../../aspose.slides/notesslide) หากต้องการ. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | วนซ้ำแต่ละ [`Slide`](./slide) ใน [`Presentation`](../../aspose.slides/presentation). |

## สมาชิกอื่น

| ชื่อ | คำอธิบาย |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback ที่จะถูกเรียกใช้สำหรับแต่ละ [`LayoutSlide`](./layoutslide) ใน [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback ที่จะถูกเรียกใช้สำหรับแต่ละ [`MasterSlide`](./masterslide) ใน [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback ที่จะถูกเรียกใช้สำหรับแต่ละ [`Paragraph`](./paragraph) บน [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback ที่จะถูกเรียกใช้สำหรับแต่ละ [`Portion`](./portion) ใน [`Paragraph`](./paragraph) บน [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback ที่จะถูกเรียกใช้สำหรับแต่ละ [`Shape`](./shape) ใน [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback ที่จะถูกเรียกใช้สำหรับแต่ละ [`Slide`](./slide) ใน [`Presentation`](../../aspose.slides/presentation). |

### ตัวอย่าง

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

### ดูเพิ่มเติม

* เนมสเปซ [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->