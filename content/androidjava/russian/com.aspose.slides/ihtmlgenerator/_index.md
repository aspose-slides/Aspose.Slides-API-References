---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: HTML-генератор.
type: docs
url: /ru/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

HTML-генератор.
## Методы

| Метод | Описание |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Добавляет отформатированный HTML-текст. |
| [addHtml(char[] html)](#addHtml-char---) | Добавляет отформатированный HTML-текст. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Добавляет отформатированный HTML-текст. |
| [addText(String text)](#addText-java.lang.String-) | Добавляет обычный текст в HTML-файлы, заменяя специальные символы на HTML-сущности. |
| [addText(char[] text)](#addText-char---) | Добавляет обычный текст в HTML-файлы, заменяя специальные символы на HTML-сущности. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Добавляет обычный текст в HTML-файлы, заменяя специальные символы на HTML-сущности. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Кавычит значение атрибута и добавляет его в HTML-файл. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Кавычит значение атрибута и добавляет его в HTML-файл. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Кавычит значение атрибута и добавляет его в HTML-файл. |
| [getSlideImageSize()](#getSlideImageSize--) | Возвращает размер изображения слайда. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Возвращает единицу измерения, в которой указан размер изображения слайда. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Возвращает CSS-код единицы измерения, в которой указан размер изображения слайда. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Возвращает индекс ранее отрисованного слайда или -1, если отрисовывается первый слайд. |
| [getSlideIndex()](#getSlideIndex--) | Возвращает индекс текущего отрисовываемого слайда. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Возвращает индекс слайда, который будет отрисован после текущего, или -1, если текущий — последний. |

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
| startIndex | int | Начальный индекс части, которую требуется добавить. |
| length | int | Длина части, которую требуется добавить. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```


Добавляет обычный текст в HTML-файлы, заменяя специальные символы на HTML-сущности. Переводы строк и пробелы не заменяются.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для добавления. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```


Добавляет обычный текст в HTML-файлы, заменяя специальные символы на HTML-сущности. Переводы строк и пробелы не заменяются.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | char[] | Текст для добавления. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```


Добавляет обычный текст в HTML-файлы, заменяя специальные символы на HTML-сущности. Переводы строк и пробелы не заменяются.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | char[] | Текст для добавления. |
| startIndex | int | Начальный индекс части, которую требуется добавить. |
| length | int | Длина части, которую требуется добавить. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```


Кавычит значение атрибута и добавляет его в HTML-файл.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строка со значением атрибута. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```


Кавычит значение атрибута и добавляет его в HTML-файл.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char[] | Строка со значением атрибута. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```


Кавычит значение атрибута и добавляет его в HTML-файл.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char[] | Строка со значением атрибута. |
| startIndex | int | Начальный индекс части, которую требуется добавить. |
| length | int | Длина части, которую требуется добавить. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```


Возвращает размер изображения слайда. Только для чтения [SizeF](../../com.aspose.slides.android/sizef).

**Возвращаемое значение:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```


Возвращает единицу измерения, в которой указан размер изображения слайда. Только для чтения [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Возвращаемое значение:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```


Возвращает CSS-код единицы измерения, в которой указан размер изображения слайда. Только для чтения String.

**Возвращаемое значение:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```


Возвращает индекс ранее отрисованного слайда или -1, если отрисовывается первый слайд. Только для чтения int.

**Возвращаемое значение:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```


Возвращает индекс текущего отрисовываемого слайда. Только для чтения int.

**Возвращаемое значение:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```


Возвращает индекс слайда, который будет отрисован после текущего, или -1, если текущий — последний. Только для чтения int.

**Возвращаемое значение:**
int