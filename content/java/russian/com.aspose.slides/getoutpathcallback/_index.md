---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /ru/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## Методы

| Метод | Описание |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Обратный вызов, который будет вызываться для каждого [Slide](../../com.aspose.slides/slide), ожидается возвращаемый путь вывода. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

Обратный вызов, который будет вызываться для каждого [Slide](../../com.aspose.slides/slide), ожидается возвращаемый путь вывода.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | Текущий перебираемый слайд |
| index | int | Индекс текущего слайда |

**Возвращаемое значение:**
java.lang.String