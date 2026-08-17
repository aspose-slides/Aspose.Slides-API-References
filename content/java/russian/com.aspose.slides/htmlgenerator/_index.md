---
title: HtmlGenerator
second_title: Aspose.Slides для Java API Reference
description: Генератор HTML.
type: docs
url: /ru/com.aspose.slides/htmlgenerator/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Генератор HTML.
## Методы

| Метод | Описание |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Добавляет отформатированный HTML-текст. |
| [addHtml(char[] html)](#addHtml-char---) | Добавляет отформатированный HTML-текст. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Добавляет отформатированный HTML-текст. |
| [addText(String text)](#addText-java.lang.String-) | Добавляет обычный текст в HTML-файлы, заменяя специальные символы на HTML-сущности. |
| [addText(char[] text)](#addText-char---) | Добавляет обычный текст в HTML-файлы, заменяя специальные символы на HTML-сущности. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Добавляет обычный текст в HTML-файлы, заменяя специальные символы на HTML-сущности. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Обрамляет значение атрибута кавычками и добавляет его в HTML-файл. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Обрамляет значение атрибута кавычками и добавляет его в HTML-файл. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Обрамляет значение атрибута кавычками и добавляет его в HTML-файл. |
| [getSlideImageSize()](#getSlideImageSize--) | Возвращает размер изображения слайда. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Возвращает единицу измерения, в которой указан размер изображения слайда. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Возвращает CSS-код единицы измерения, в которой указан размер изображения слайда. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Возвращает индекс ранее отрендеренного слайда или -1, если рендерится первый слайд. |
| [getSlideIndex()](#getSlideIndex--) | Возвращает индекс текущего рендерящегося слайда. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Возвращает индекс слайда, который будет отрендерен после текущего слайда, или -1, если сейчас рендерится последний слайд. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Добавляет отформатированный HTML-текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| html | java.lang.String | Текст для добавления. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Добавляет отформатированный HTML-текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| html | char[] | Текст для добавления. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

Добавляет отформатированный HTML-текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| html | char[] | Текст для добавления. |
| startIndex | int | Начальный индекс части для добавления. |
| length | int | Длина части для добавления. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

Добавляет обычный текст в HTML-файлы, заменяя специальные символы на HTML-сущности. Переводы строк и пробелы не заменяются.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для добавления. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Добавляет обычный текст в HTML-файлы, заменяя специальные символы на HTML-сущности. Переводы строк и пробелы не заменяются.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | char[] | Текст для добавления. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Добавляет обычный текст в HTML-файлы, заменяя специальные символы на HTML-сущности. Переводы строк и пробелы не заменяются.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | char[] | Текст для добавления. |
| startIndex | int | Начальный индекс части для добавления. |
| length | int | Длина части для добавления. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

Обрамляет значение атрибута кавычками и добавляет его в HTML-файл.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строка значения атрибута. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Обрамляет значение атрибута кавычками и добавляет его в HTML-файл.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char[] | Строка значения атрибута. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Обрамляет значение атрибута кавычками и добавляет его в HTML-файл.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char[] | Строка значения атрибута. |
| startIndex | int | Начальный индекс части для добавления. |
| length | int | Длина части для добавления. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```

Возвращает размер изображения слайда. Только для чтения java.awt.geom.Dimension2D.

**Возвращаемое значение:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Возвращает единицу измерения, в которой указан размер изображения слайда. Только для чтения [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Возвращаемое значение:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Возвращает CSS-код единицы измерения, в которой указан размер изображения слайда. Только для чтения String.

**Возвращаемое значение:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Возвращает индекс ранее отрендеренного слайда или -1, если рендерится первый слайд. Только для чтения int.

**Возвращаемое значение:**
int

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Возвращает индекс текущего рендерящегося слайда. Только для чтения int.

**Возвращаемое значение:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Возвращает индекс слайда, который будет отрендерен после текущего слайда, или -1, если сейчас рендерится последний слайд. Только для чтения int.

**Возвращаемое значение:**
int