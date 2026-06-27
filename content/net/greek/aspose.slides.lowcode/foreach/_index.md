---
title: ForEach
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται για επανάληψη πάνω σε διαφορετικά αντικείμενα μοντέλου Presentation../aspose.slides/presentation. Αυτές οι μέθοδοι μπορούν να είναι χρήσιμες εάν χρειάζεται να κάνετε επανάληψη και να αλλάξετε τη μορφοποίηση ή το περιεχόμενο ορισμένων στοιχείων του Presentation, π.χ. την αλλαγή της μορφοποίησης κάθε τμήματος.
type: docs
weight: 7880
url: /el/aspose.slides.lowcode/foreach/
---
## Κλάση ForEach

Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται για επανάληψη πάνω σε διαφορετικά [`Presentation`](../../aspose.slides/presentation) μοντέλα αντικειμένων. Αυτές οι μέθοδοι μπορούν να είναι χρήσιμες εάν χρειάζεται να κάνετε επανάληψη και αλλαγή στη μορφοποίηση ή το περιεχόμενο στοιχείων του Presentation, π.χ. αλλαγή της μορφοποίησης κάθε τμήματος.

```csharp
public static class ForEach
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Επανάληψη κάθε [`LayoutSlide`](./layoutslide) στο [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Επανάληψη κάθε [`MasterSlide`](./masterslide) στο [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Επανάληψη κάθε [`Paragraph`](./paragraph) στο [`Presentation`](../../aspose.slides/presentation). Τα σχήματα θα επαναληφθούν σε όλους τους τύπους διαφανειών - [`Slide`](./slide), [`MasterSlide`](./masterslide) και [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Επανάληψη κάθε [`Paragraph`](./paragraph) στο [`Presentation`](../../aspose.slides/presentation). Τα σχήματα θα επαναληφθούν σε όλους τους τύπους διαφανειών - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) και [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Επανάληψη κάθε [`Portion`](./portion) στο [`Presentation`](../../aspose.slides/presentation). Τα τμήματα θα επαναληφθούν σε όλους τους τύπους διαφανειών - [`Slide`](./slide), [`MasterSlide`](./masterslide) και [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Επανάληψη κάθε [`Portion`](./portion) στο [`Presentation`](../../aspose.slides/presentation). Τα τμήματα θα επαναληφθούν σε όλους τους τύπους διαφανειών - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) και [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Επανάληψη κάθε [`Shape`](./shape) στη [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) είναι ο βασικός τύπος για [`Slide`](./slide), [`MasterSlide`](./masterslide) και [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Επανάληψη κάθε [`Shape`](./shape) στο [`Presentation`](../../aspose.slides/presentation). Τα σχήματα θα επαναληφθούν σε όλους τους τύπους διαφανειών - [`Slide`](./slide), [`MasterSlide`](./masterslide) και [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Επανάληψη κάθε [`Shape`](./shape) στο [`Presentation`](../../aspose.slides/presentation). Τα σχήματα θα επαναληφθούν σε όλους τους τύπους διαφανειών - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) και [`NotesSlide`](../../aspose.slides/notesslide) εφόσον χρειαστεί. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Επανάληψη κάθε [`Slide`](./slide) στο [`Presentation`](../../aspose.slides/presentation). |

## Άλλα μέλη

| Όνομα | Περιγραφή |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback που θα κληθεί για κάθε [`LayoutSlide`](./layoutslide) στο [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback που θα κληθεί για κάθε [`MasterSlide`](./masterslide) στο [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback που θα κληθεί για κάθε [`Paragraph`](./paragraph) στο [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback που θα κληθεί για κάθε [`Portion`](./portion) στο [`Paragraph`](./paragraph) στο [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback που θα κληθεί για κάθε [`Shape`](./shape) στο [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback που θα κληθεί για κάθε [`Slide`](./slide) στο [`Presentation`](../../aspose.slides/presentation). |

### Παραδείγματα

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

### Δείτε επίσης

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->