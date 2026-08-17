---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /el/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Η callback θα κληθεί για κάθε [Slide](../../com.aspose.slides/slide), η διαδρομή εξόδου αναμένεται να επιστραφεί. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

Η callback θα κληθεί για κάθε [Slide](../../com.aspose.slides/slide), η διαδρομή εξόδου αναμένεται να επιστραφεί.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | Τρέχουσα διαφάνεια |
| index | int | Δείκτης της τρέχουσας διαφάνειας |

**Τιμή επιστροφής:**
java.lang.String