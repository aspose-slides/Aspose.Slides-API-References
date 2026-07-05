---
title: ForEach
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึงกลุ่มของเมธอดที่มีจุดประสงค์เพื่อวนซ้ำเหนือวัตถุโมเดล Presentation../aspose.slides/presentation ที่ต่างกัน. เมธอดเหล่านี้อาจเป็นประโยชน์หากคุณต้องการวนซ้ำและเปลี่ยนรูปแบบหรือเนื้อหาของบางองค์ประกอบ Presentation เช่น การเปลี่ยนรูปแบบของแต่ละส่วน.
type: docs
weight: 7900
url: /th/aspose.slides.lowcode/foreach/
---
## ForEach คลาส

แทนกลุ่มของเมธอดที่มีจุดประสงค์เพื่อวนซ้ำเหนือวัตถุโมเดล [`Presentation`](../../aspose.slides/presentation) ต่างๆ เมธอดเหล่านี้อาจเป็นประโยชน์หากคุณต้องการวนซ้ำและเปลี่ยนรูปแบบหรือเนื้อหาขององค์ประกอบบางส่วนของ Presentation เช่น เปลี่ยนรูปแบบของแต่ละส่วน

```csharp
public static class ForEach
```

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | วนซ้ำแต่ละ [`LayoutSlide`](./layoutslide) ใน [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | วนซ้ำแต่ละ [`MasterSlide`](./masterslide) ใน [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | วนซ้ำแต่ละ [`Paragraph`](./paragraph) ใน [`Presentation`](../../aspose.slides/presentation). รูปร่างจะถูกวนซ้ำในทุกประเภทของสไลด์ - [`Slide`](./slide), [`MasterSlide`](./masterslide) และ [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | วนซ้ำแต่ละ [`Paragraph`](./paragraph) ใน [`Presentation`](../../aspose.slides/presentation). รูปร่างจะถูกวนซ้ำในทุกประเภทของสไลด์ - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) และ [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | วนซ้ำแต่ละ [`Portion`](./portion) ใน [`Presentation`](../../aspose.slides/presentation). ส่วนจะถูกวนซ้ำในทุกประเภทของสไลด์ - [`Slide`](./slide), [`MasterSlide`](./masterslide) และ [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | วนซ้ำแต่ละ [`Portion`](./portion) ใน [`Presentation`](../../aspose.slides/presentation). ส่วนจะถูกวนซ้ำในทุกประเภทของสไลด์ - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) และ [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | วนซ้ำแต่ละ [`Shape`](./shape) ใน [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) เป็นประเภทพื้นฐานสำหรับ [`Slide`](./slide), [`MasterSlide`](./masterslide) และ [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | วนซ้ำแต่ละ [`Shape`](./shape) ใน [`Presentation`](../../aspose.slides/presentation). รูปร่างจะถูกวนซ้ำในทุกประเภทของสไลด์ - [`Slide`](./slide), [`MasterSlide`](./masterslide) และ [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | วนซ้ำแต่ละ [`Shape`](./shape) ใน [`Presentation`](../../aspose.slides/presentation). รูปร่างจะถูกวนซ้ำในทุกประเภทของสไลด์ - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) และ [`NotesSlide`](../../aspose.slides/notesslide) หากจำเป็น. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | วนซ้ำแต่ละ [`Slide`](./slide) ใน [`Presentation`](../../aspose.slides/presentation). |

## สมาชิกอื่น

| ชื่อ | คำอธิบาย |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [`LayoutSlide`](./layoutslide) ใน [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [`MasterSlide`](./masterslide) ใน [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [`Paragraph`](./paragraph) บน [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [`Portion`](./portion) ใน [`Paragraph`](./paragraph) บน [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [`Shape`](./shape) ใน [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | คอลแบ็กที่จะถูกเรียกสำหรับแต่ละ [`Slide`](./slide) ใน [`Presentation`](../../aspose.slides/presentation). |

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

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->