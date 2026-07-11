---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /el/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Callback που θα κληθεί για κάθε \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) στο [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

Callback που θα κληθεί για κάθε \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) στο [BaseSlide](../../com.aspose.slides/baseslide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Τρέχον επαναλαμβανόμενο τμήμα |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Τρέχουσα επαναλαμβανόμενη παράγραφος |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Τρέχουσα επαναλαμβανόμενη διαφάνεια |
| index | int | Δείκτης της τρέχουσας παραγράφου στη διαφάνεια |