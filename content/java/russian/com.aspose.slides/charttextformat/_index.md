---
title: ChartTextFormat
second_title: Справочник API Aspose.Slides для Java
description: Задает форматирование текста по умолчанию для текстовых элементов диаграммы.
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

Задает форматирование текста по умолчанию для текстовых элементов диаграммы.
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

**Возвращает:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```

ParagraphFormat. Только для чтения [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Возвращает:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```

PortionFormat. Только для чтения [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Возвращает:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```

Копирует формат текста в указанный текстовый кадр.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Текстовый кадр, в который копировать формат текста. |
### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```

Копирует формат текста из указанного текстового кадра.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Текстовый кадр, из которого копировать формат текста. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject