---
title: ForEach
second_title: Aspose.Sildes untuk .NET Referensi API
description: Mewakili sekelompok metode yang ditujukan untuk mengiterasi berbagai objek model Presentation../aspose.slides/presentation. Metode ini dapat berguna bila Anda perlu mengiterasi dan mengubah format atau konten beberapa elemen Presentation, misalnya mengubah format setiap bagian.
type: docs
weight: 7900
url: /id/aspose.slides.lowcode/foreach/
---
## kelas ForEach

Mewakili sekelompok metode yang ditujukan untuk mengiterasi berbagai objek model [`Presentation`](../../aspose.slides/presentation). Metode ini dapat berguna jika Anda perlu mengiterasi dan mengubah format atau konten beberapa elemen Presentation, misalnya mengubah format setiap bagian.

```csharp
public static class ForEach
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iterasi setiap [`LayoutSlide`](./layoutslide) dalam [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iterasi setiap [`MasterSlide`](./masterslide) dalam [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iterasi setiap [`Paragraph`](./paragraph) dalam [`Presentation`](../../aspose.slides/presentation). Bentuk akan diiterasi dalam semua jenis slide - [`Slide`](./slide), [`MasterSlide`](./masterslide) dan [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iterasi setiap [`Paragraph`](./paragraph) dalam [`Presentation`](../../aspose.slides/presentation). Bentuk akan diiterasi dalam semua jenis slide - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) dan [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iterasi setiap [`Portion`](./portion) dalam [`Presentation`](../../aspose.slides/presentation). Bagian akan diiterasi dalam semua jenis slide - [`Slide`](./slide), [`MasterSlide`](./masterslide) dan [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iterasi setiap [`Portion`](./portion) dalam [`Presentation`](../../aspose.slides/presentation). Bagian akan diiterasi dalam semua jenis slide - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) dan [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iterasi setiap [`Shape`](./shape) dalam [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) adalah tipe dasar untuk [`Slide`](./slide), [`MasterSlide`](./masterslide) dan [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iterasi setiap [`Shape`](./shape) dalam [`Presentation`](../../aspose.slides/presentation). Bentuk akan diiterasi dalam semua jenis slide - [`Slide`](./slide), [`MasterSlide`](./masterslide) dan [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iterasi setiap [`Shape`](./shape) dalam [`Presentation`](../../aspose.slides/presentation). Bentuk akan diiterasi dalam semua jenis slide - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) dan [`NotesSlide`](../../aspose.slides/notesslide) jika diperlukan. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iterasi setiap [`Slide`](./slide) dalam [`Presentation`](../../aspose.slides/presentation). |

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback yang akan dipanggil untuk setiap [`LayoutSlide`](./layoutslide) dalam [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback yang akan dipanggil untuk setiap [`MasterSlide`](./masterslide) dalam [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback yang akan dipanggil untuk setiap [`Paragraph`](./paragraph) pada [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback yang akan dipanggil untuk setiap [`Portion`](./portion) dalam [`Paragraph`](./paragraph) pada [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback yang akan dipanggil untuk setiap [`Shape`](./shape) dalam [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback yang akan dipanggil untuk setiap [`Slide`](./slide) dalam [`Presentation`](../../aspose.slides/presentation). |

### Contoh

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

### Lihat Juga

* ruang nama [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->