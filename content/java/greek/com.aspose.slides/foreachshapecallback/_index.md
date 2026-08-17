---  
title: ForEach.ForEachShapeCallback  
second_title: Aspose.Slides for Java API Reference  
description:   
type: docs  
url: /el/com.aspose.slides/foreach.foreachshapecallback/  
---```
public static interface ForEach.ForEachShapeCallback
```  
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Callback that will be invoked for each [Shape](../../com.aspose.slides/shape) in the [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

Ανακλήση που θα κληθεί για κάθε [Shape](../../com.aspose.slides/shape) στο [Presentation](../../com.aspose.slides/presentation).

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Τρέχουσα επεξεργασμένη μορφή |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Τρέχουσα επεξεργασμένη διαφάνεια |
| index | int | Δείκτης της τρέχουσας διαφάνειας διάταξης |