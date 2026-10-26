---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ru/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## Методы

| Метод | Описание |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Обратный вызов, который будет вызван для каждого \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) на [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

Обратный вызов, который будет вызван для каждого \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) на [BaseSlide](../../com.aspose.slides/baseslide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | Текущий перебираемый фрагмент |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Текущий перебираемый абзац |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Текущий перебираемый слайд |
| index | int | Индекс текущего абзаца на слайде |