---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Диаграмма работает с ограниченным набором свойств формата текста.
type: docs
url: /ru/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Диаграмма работает с ограниченным набором свойств формата текста. Интерфейсы IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat описывают этот ограниченный набор.
## Методы

| Метод | Описание |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Возвращает формат для элементов текста диаграммы. |
| [getParagraphFormat()](#getParagraphFormat--) | Возвращает формат абзаца. |
| [getPortionFormat()](#getPortionFormat--) | Возвращает формат части. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Копирует формат текста в указанный текстовый фрейм. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Копирует формат текста из указанного текстового фрейма. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


Возвращает формат для элементов текста диаграммы. Только для чтения [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Возвращаемое значение:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


Возвращает формат абзаца. Только для чтения [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Возвращаемое значение:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


Возвращает формат части. Только для чтения [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Возвращаемое значение:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


Копирует формат текста в указанный текстовый фрейм.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Текстовый фрейм, в который копируется формат текста. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


Копирует формат текста из указанного текстового фрейма.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Текстовый фрейм, из которого копируется формат текста. |