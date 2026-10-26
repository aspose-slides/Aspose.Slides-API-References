---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /ru/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства форматирования текстового фрейма.

--------------------

Этот интерфейс используется вместе с интерфейсом [ITextFrameFormat](../../com.aspose.slides/itextframeformat) для возврата эффективных значений форматирования с применением наследования.
## Методы

| Методы | Описание |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Возвращает эффективный стиль текста. |
| [getMarginLeft()](#getMarginLeft--) | Возвращает левый отступ (в пунктах) в TextFrame. |
| [getMarginRight()](#getMarginRight--) | Возвращает правый отступ (в пунктах) в TextFrame. |
| [getMarginTop()](#getMarginTop--) | Возвращает верхний отступ (в пунктах) в TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Возвращает нижний отступ (в пунктах) в TextFrame. |
| [getWrapText()](#getWrapText--) | Возвращает, оборачивается ли текст у отступов TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Возвращает вертикальное привязывание текста в TextFrame. |
| [getCenterText()](#getCenterText--) | Возвращает, следует ли выровнять текст по горизонтали в рамке. |
| [getTextVerticalType()](#getTextVerticalType--) | Возвращает ориентацию текста. |
| [getAutofitType()](#getAutofitType--) | Возвращает режим автоподгонки текста. |
| [getColumnCount()](#getColumnCount--) | Указывает количество столбцов текста в ограничивающем прямоугольнике. |
| [getColumnSpacing()](#getColumnSpacing--) | Указывает расстояние между столбцами текста в текстовой области (в пунктах). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

Возвращает эффективный стиль текста. Только для чтения [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Возвращаемое значение:**  
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Возвращает левый отступ (в пунктах) в TextFrame. Только для чтения double.

**Возвращаемое значение:**  
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Возвращает правый отступ (в пунктах) в TextFrame. Только для чтения double.

**Возвращаемое значение:**  
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Возвращает верхний отступ (в пунктах) в TextFrame. Только для чтения double.

**Возвращаемое значение:**  
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Возвращает нижний отступ (в пунктах) в TextFrame. Только для чтения double.

**Возвращаемое значение:**  
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

Возвращает, оборачивается ли текст у отступов TextFrame. Только для чтения boolean.

**Возвращаемое значение:**  
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Возвращает вертикальное привязывание текста в TextFrame. Только для чтения [TextAnchorType](../../com.aspose.slides/textanchortype).

**Возвращаемое значение:**  
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

Возвращает, следует ли выровнять текст по горизонтали в рамке. Только для чтения boolean.

**Возвращаемое значение:**  
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Возвращает ориентацию текста. Только для чтения [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Возвращаемое значение:**  
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Возвращает режим автоподгонки текста. Только для чтения [TextAutofitType](../../com.aspose.slides/textautofittype).

**Возвращаемое значение:**  
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Указывает количество столбцов текста в ограничивающем прямоугольнике. Только для чтения int.

**Возвращаемое значение:**  
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

Указывает расстояние между столбцами текста в текстовой области (в пунктах). Только для чтения float.

**Возвращаемое значение:**  
float