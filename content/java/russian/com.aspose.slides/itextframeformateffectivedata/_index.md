---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Неизменяемый объект, содержащий эффективные свойства форматирования текстового фрейма.
type: docs
url: /ru/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства форматирования текстового фрейма.

--------------------

Этот интерфейс используется вместе с интерфейсом [ITextFrameFormat](../../com.aspose.slides/itextframeformat) для возврата эффективных значений форматирования с применением наследования.
## Методы

| Метод | Описание |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Возвращает эффективный стиль текста. |
| [getMarginLeft()](#getMarginLeft--) | Возвращает левый отступ (в пунктах) в TextFrame. |
| [getMarginRight()](#getMarginRight--) | Возвращает правый отступ (в пунктах) в TextFrame. |
| [getMarginTop()](#getMarginTop--) | Возвращает верхний отступ (в пунктах) в TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Возвращает нижний отступ (в пунктах) в TextFrame. |
| [getWrapText()](#getWrapText--) | Возвращает, оборачивается ли текст у границ TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Возвращает вертикальный тип привязки текста в TextFrame. |
| [getCenterText()](#getCenterText--) | Возвращает, следует ли центрировать текст в коробке по горизонтали. |
| [getTextVerticalType()](#getTextVerticalType--) | Возвращает ориентацию текста. |
| [getAutofitType()](#getAutofitType--) | Возвращает режим автоматической подгонки текста. |
| [getColumnCount()](#getColumnCount--) | Указывает количество столбцов текста в ограничивающем прямоугольнике. |
| [getColumnSpacing()](#getColumnSpacing--) | Указывает расстояние между столбцами текста в области текста (в пунктах). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

Возвращает эффективный стиль текста. Только для чтения [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Возвращает:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Возвращает левый отступ (в пунктах) в TextFrame. Только для чтения double.

**Возвращает:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Возвращает правый отступ (в пунктах) в TextFrame. Только для чтения double.

**Возвращает:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Возвращает верхний отступ (в пунктах) в TextFrame. Только для чтения double.

**Возвращает:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Возвращает нижний отступ (в пунктах) в TextFrame. Только для чтения double.

**Возвращает:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

Возвращает, оборачивается ли текст у границ TextFrame. Только для чтения boolean.

**Возвращает:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Возвращает вертикальный тип привязки текста в TextFrame. Только для чтения [TextAnchorType](../../com.aspose.slides/textanchortype).

**Возвращает:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

Возвращает, следует ли центрировать текст в коробке по горизонтали. Только для чтения boolean.

**Возвращает:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Возвращает ориентацию текста. Только для чтения [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Возвращает:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Возвращает режим автоматической подгонки текста. Только для чтения [TextAutofitType](../../com.aspose.slides/textautofittype).

**Возвращает:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Указывает количество столбцов текста в ограничивающем прямоугольнике. Только для чтения int.

**Возвращает:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

Указывает расстояние между столбцами текста в области текста (в пунктах). Только для чтения float.

**Возвращает:**
float