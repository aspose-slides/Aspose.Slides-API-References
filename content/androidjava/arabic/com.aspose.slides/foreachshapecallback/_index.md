---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ar/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## الطرق

| Method | Description |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | سيتم استدعاء الدالة لكل [Shape](../../com.aspose.slides/shape) في [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

سيتم استدعاء الدالة لكل [Shape](../../com.aspose.slides/shape) في [Presentation](../../com.aspose.slides/presentation).

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | الشكل الحالي المتكرر |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | الشريحة الحالية المتكررة |
| index | int | فهرس الشريحة الحالية في التخطيط |