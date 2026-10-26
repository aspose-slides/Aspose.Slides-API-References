---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ru/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## Методы

| Метод | Описание |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | Обратный вызов, который будет вызван для каждого \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) на [BaseSlide](../../com.aspose.slides/baseslide). |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```


Обратный вызов, который будет вызван для каждого \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) на [BaseSlide](../../com.aspose.slides/baseslide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | Текущий обрабатываемый абзац |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | Текущий обрабатываемый слайд |
| index | int | Индекс текущего абзаца на слайде |