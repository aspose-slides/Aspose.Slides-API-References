---
title: ForEach.ForEachLayoutSlideCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ru/com.aspose.slides/foreach.foreachlayoutslidecallback/
---```
public static interface ForEach.ForEachLayoutSlideCallback
```
## Методы

| Метод | Описание |
| --- | --- |
| [invoke(LayoutSlide layoutSlide, int index)](#invoke-com.aspose.slides.LayoutSlide-int-) | Колбэк, который будет вызван для каждой \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) в [Presentation](../../com.aspose.slides/presentation). |
### invoke(LayoutSlide layoutSlide, int index) {#invoke-com.aspose.slides.LayoutSlide-int-}
```
public abstract void invoke(LayoutSlide layoutSlide, int index)
```

Колбэк, который будет вызван для каждой \#layoutSlide(Presentation,ForEachLayoutSlideCallback).layoutSlide(Presentation,ForEachLayoutSlideCallback) в [Presentation](../../com.aspose.slides/presentation).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layoutSlide | [LayoutSlide](../../com.aspose.slides/layoutslide) | Текущий перебираемый шаблонный слайд |
| index | int | Индекс текущего шаблонного слайда |