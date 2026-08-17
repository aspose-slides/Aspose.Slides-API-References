---
title: IHtmlGenerator
second_title: Aspose.Slides for Java API Reference
description: Html generator.
type: docs
url: /ru/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

Генератор HTML.
## Методы

| Метод | Описание |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Добавляет отформатированный HTML-текст. |
| [addHtml(char[] html)](#addHtml-char---) | Добавляет отформатированный HTML-текст. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Добавляет отформатированный HTML-текст. |
| [addText(String text)](#addText-java.lang.String-) | Добавляет обычный текст в файлы HTML, заменяя специальные символы HTML-сущностями. |
| [addText(char[] text)](#addText-char---) | Добавляет обычный текст в файлы HTML, заменяя специальные символы HTML-сущностями. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Добавляет обычный текст в файлы HTML, заменяя специальные символы HTML-сущностями. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Оборачивает значение атрибута в кавычки и добавляет его в файл HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Оборачивает значение атрибута в кавычки и добавляет его в файл HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Оборачивает значение атрибута в кавычки и добавляет его в файл HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | Возвращает размер изображения слайда. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Возвращает единицу измерения, в которой указана размер изображения слайда. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Возвращает CSS-код единицы измерения, в которой указана размер изображения слайда. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Возвращает индекс ранее отрисованного слайда или -1, если отрисовывается первый слайд. |
| [getSlideIndex()](#getSlideIndex--) | Возвращает индекс текущего отрисовываемого слайда. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Возвращает индекс слайда, который будет отрисован после текущего, или -1, если отрисовывается последний слайд. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

Добавляет отформатированный HTML-текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| html | java.lang.String | Текст для добавления. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

Добавляет отформатированный HTML-текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| html | char[] | Текст для добавления. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

Добавляет отформатированный HTML-текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| html | char[] | Текст для добавления. |
| startIndex | int | Начальный индекс добавляемой части. |
| length | int | Длина добавляемой части. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

Добавляет обычный текст в файлы HTML, заменяя специальные символы HTML-сущностями. Разрывы строк и пробелы не заменяются.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для добавления. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Добавляет обычный текст в файлы HTML, заменяя специальные символы HTML-сущностями. Разрывы строк и пробелы не заменяются.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | char[] | Текст для добавления. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Добавляет обычный текст в файлы HTML, заменяя специальные символы HTML-сущностями. Разрывы строк и пробелы не заменяются.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | char[] | Текст для добавления. |
| startIndex | int | Начальный индекс добавляемой части. |
| length | int | Длина добавляемой части. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Оборачивает значение атрибута в кавычки и добавляет его в файл HTML.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строка значения атрибута. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Оборачивает значение атрибута в кавычки и добавляет его в файл HTML.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char[] | Строка значения атрибута. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Оборачивает значение атрибута в кавычки и добавляет его в файл HTML.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char[] | Строка значения атрибута. |
| startIndex | int | Начальный индекс добавляемой части. |
| length | int | Длина добавляемой части. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract Dimension2D getSlideImageSize()
```

Возвращает размер изображения слайда. Только для чтения java.awt.geom.Dimension2D.

**Возвращает:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Возвращает единицу измерения, в которой указан размер изображения слайда. Только для чтения [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Возвращает:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Возвращает CSS-код единицы измерения, в которой указан размер изображения слайда. Только для чтения String.

**Возвращает:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Возвращает индекс ранее отрисованного слайда или -1, если отрисовывается первый слайд. Только для чтения int.

**Возвращает:**
int
### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Возвращает индекс текущего отрисовываемого слайда. Только для чтения int.

**Возвращает:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Возвращает индекс слайда, который будет отрисован после текущего, или -1, если отрисовывается последний слайд. Только для чтения int.

**Возвращает:**
int