---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ru/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## Методы

| Метод | Описание |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Обратный вызов, который будет вызван для каждого [Slide](../../com.aspose.slides/slide), ожидается возвращённый путь вывода. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

Обратный вызов, который будет вызван для каждого [Slide](../../com.aspose.slides/slide), ожидается возвращённый путь вывода.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | Текущий обрабатываемый слайд |
| index | int | Индекс текущего слайда |

**Возвращаемое значение:**
java.lang.String