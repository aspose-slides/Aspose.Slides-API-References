---
title: ForEach
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται για επανάληψη πάνω σε διαφορετικά αντικείμενα μοντέλου Presentation../aspose.slides/presentation. Αυτές οι μέθοδοι μπορούν να είναι χρήσιμες εάν χρειάζεται να επαναλάβετε και να αλλάξετε τη διαμόρφωση ή το περιεχόμενο ορισμένων στοιχείων του Presentation, π.χ. να αλλάξετε τη διαμόρφωση του κάθε τμήματος.
type: docs
weight: 7900
url: /el/aspose.slides.lowcode/foreach/
---
## ForEach κλάση

Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται για επανάληψη πάνω σε διαφορετικά [`Presentation`](../../aspose.slides/presentation) μοντέλο αντικείμενα. Αυτές οι μέθοδοι μπορούν να είναι χρήσιμες εάν χρειάζεται να επαναλάβετε και να αλλάξετε τη διαμόρφωση ή το περιεχόμενο ορισμένων στοιχείων του Presentation, π.χ. να αλλάξετε τη διαμόρφωση κάθε τμήματος.

```csharp
public static class ForEach
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Επανάληψη κάθε [`LayoutSlide`](./layoutslide) στο [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Επανάληψη κάθε [`MasterSlide`](./masterslide) στο [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Επανάληψη κάθε [`Paragraph`](./paragraph) στο [`Presentation`](../../aspose.slides/presentation). Τα σχήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - [`Slide`](./slide), [`MasterSlide`](./masterslide) και [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Επανάληψη κάθε [`Paragraph`](./paragraph) στο [`Presentation`](../../aspose.slides/presentation). Τα σχήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) και [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Επανάληψη κάθε [`Portion`](./portion) στο [`Presentation`](../../aspose.slides/presentation). Τα τμήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - [`Slide`](./slide), [`MasterSlide`](./masterslide) και [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Επανάληψη κάθε [`Portion`](./portion) στο [`Presentation`](../../aspose.slides/presentation). Τα τμήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) και [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Επανάληψη κάθε [`Shape`](./shape) στο [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) είναι ο βασικός τύπος για [`Slide`](./slide), [`MasterSlide`](./masterslide) και [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Επανάληψη κάθε [`Shape`](./shape) στο [`Presentation`](../../aspose.slides/presentation). Τα σχήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - [`Slide`](./slide), [`MasterSlide`](./masterslide) και [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Επανάληψη κάθε [`Shape`](./shape) στο [`Presentation`](../../aspose.slides/presentation). Τα σχήματα θα επαναλαμβάνονται σε όλους τους τύπους διαφανειών - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) και [`NotesSlide`](../../aspose.slides/notesslide) εάν χρειάζεται. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Επανάληψη κάθε [`Slide`](./slide) στο [`Presentation`](../../aspose.slides/presentation). |

## Άλλα Μέλη

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

* χώρο ονομάτων [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->