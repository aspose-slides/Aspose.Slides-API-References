---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ru/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## Методы

| Метод | Описание |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | Обратный вызов, который будет вызываться для каждого [Shape](../../com.aspose.slides/shape) в [Presentation](../../com.aspose.slides/presentation). |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


Обратный вызов, который будет вызываться для каждого [Shape](../../com.aspose.slides/shape) в [Presentation](../../com.aspose.slides/presentation).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | Текущая фигура |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Текущий слайд |
| index | int | Индекс текущего макетного слайда |