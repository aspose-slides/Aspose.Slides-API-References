---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: 
type: docs
url: /el/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Η callback που θα κληθεί για κάθε [Shape](../../com.aspose.slides/shape) στο [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

Η callback που θα κληθεί για κάθε [Shape](../../com.aspose.slides/shape) στο [Presentation](../../com.aspose.slides/presentation).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Τρέχον επαναλαμβανόμενο σχήμα |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Τρέχουσα επαναλαμβανόμενη διαφάνεια |
| index | int | Δείκτης της τρέχουσας διαφάνειας διάταξης |