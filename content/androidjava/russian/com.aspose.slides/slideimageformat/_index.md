---
title: SlideImageFormat
second_title: Aspose.Slides для Android через справочник Java API
description: Определяет формат, в котором изображение слайда будет сохранено при экспорте презентации в HTML.
type: docs
url: /ru/com.aspose.slides/slideimageformat/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Определяет формат, в котором изображение слайда будет сохранено при экспорте презентации в HTML.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Слайды должны быть сохранены в формате SVG. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Слайды должны быть преобразованы в растровое изображение. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

Слайды должны быть сохранены в формате SVG.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Параметры для экспорта SVG. |

**Возвращаемое значение:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - объект [SlideImageFormat](../../com.aspose.slides/slideimageformat).

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

Слайды должны быть преобразованы в растровое изображение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scale | float | Коэффициент масштабирования выходного изображения. |
| imageFormat | int | Формат получаемого изображения (например, PNG, JPEG). |

**Возвращаемое значение:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -