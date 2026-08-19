---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /fa/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## متدها

| متد | توضیح |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Callback که برای هر [Shape](../../com.aspose.slides/shape) در [Presentation](../../com.aspose.slides/presentation) فراخوانی می‌شود. |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```

Callback که برای هر [Shape](../../com.aspose.slides/shape) در [Presentation](../../com.aspose.slides/presentation) فراخوانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | شکل فعلی در حال تکرار |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | اسلاید فعلی در حال تکرار |
| index | int | اندیس اسلاید لایه‌بندی جاری |