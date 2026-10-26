---
title: ChartTextFormat
second_title: Aspose.Slides для Android через Java API справочник
description: Указывает форматирование текста по умолчанию для элементов текста диаграммы.
type: docs
url: /ru/com.aspose.slides/charttextformat/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

Указывает форматирование текста по умолчанию для элементов текста диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Копирует формат текста в указанный текстовый кадр. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Копирует формат текста из указанного текстового кадра. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. Только для чтения [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Возвращаемое значение:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. Только для чтения [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Возвращаемое значение:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. Только для чтения [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Возвращаемое значение:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


Копирует формат текста в указанный текстовый кадр.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Текстовый кадр, в который копируется формат текста. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


Копирует формат текста из указанного текстового кадра.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Текстовый кадр, из которого копируется формат текста. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject