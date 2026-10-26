---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /el/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Η ενέργεια callback που θα κληθεί για κάθε #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) στο [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```


Η ενέργεια callback που θα κληθεί για κάθε #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) στο [BaseSlide](../../com.aspose.slides/baseslide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Τρέχουσα επαναληπτική παράγραφος |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Τρέχουσα επαναληπτική διαφάνεια |
| index | int | Δείκτης της τρέχουσας παραγράφου στη διαφάνεια |