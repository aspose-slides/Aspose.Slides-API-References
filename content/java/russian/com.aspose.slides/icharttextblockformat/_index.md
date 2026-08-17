---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Java API Reference
description: Represents formatting properties for chart text elements.
type: docs
url: /ru/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Представляет свойства форматирования элементов текста диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Возвращает или задает вертикальное привязывание текста в TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Возвращает или задает вертикальное привязывание текста в TextFrame. |
| [getCenterText()](#getCenterText--) | Если NullableBool.True, то текст должен быть центрирован по горизонтали в рамке. |
| [setCenterText(byte value)](#setCenterText-byte-) | Если NullableBool.True, то текст должен быть центрирован по горизонтали в рамке. |
| [getTextVerticalType()](#getTextVerticalType--) | Определяет ориентацию текста. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Определяет ориентацию текста. |
| [getMarginLeft()](#getMarginLeft--) | Возвращает или задает левый отступ (в пунктах) в TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Возвращает или задает левый отступ (в пунктах) в TextFrame. |
| [getMarginRight()](#getMarginRight--) | Возвращает или задает правый отступ (в пунктах) в TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Возвращает или задает правый отступ (в пунктах) в TextFrame. |
| [getMarginTop()](#getMarginTop--) | Возвращает или задает верхний отступ (в пунктах) в TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Возвращает или задает верхний отступ (в пунктах) в TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Возвращает или задает нижний отступ (в пунктах) в TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Возвращает или задает нижний отступ (в пунктах) в TextFrame. |
| [getWrapText()](#getWrapText--) | True, если текст переносится на полях TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True, если текст переносится на полях TextFrame. |
| [getAutofitType()](#getAutofitType--) | Возвращает или задает режим автоподгонки текста. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Возвращает или задает режим автоподгонки текста. |
| [getRotationAngle()](#getRotationAngle--) | Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего блока. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего блока. |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Возвращает или задает вертикальное привязывание текста в TextFrame. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Возвращаемое значение:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Возвращает или задает вертикальное привязывание текста в TextFrame. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Если NullableBool.True, то текст должен быть центрирован по горизонтали в рамке. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Если NullableBool.True, то текст должен быть центрирован по горизонтали в рамке. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Определяет ориентацию текста. Получаемое значение визуального вращения текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Возвращаемое значение:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Определяет ориентацию текста. Получаемое значение визуального вращения текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Возвращает или задает левый отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать определённое влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Чтение/запись double.

**Возвращаемое значение:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Возвращает или задает левый отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать определённое влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Возвращает или задает правый отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать определённое влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Чтение/запись double.

**Возвращаемое значение:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Возвращает или задает правый отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать определённое влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Возвращает или задает верхний отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать определённое влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Чтение/запись double.

**Возвращаемое значение:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Возвращает или задает верхний отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать определённое влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Возвращает или задает нижний отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать определённое влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Чтение/запись double.

**Возвращаемое значение:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Возвращает или задает нижний отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать определённое влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

True, если текст переносится на полях TextFrame. Изменение этого свойства может оказывать определённое влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2007/2013). Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

True, если текст переносится на полях TextFrame. Изменение этого свойства может оказывать определённое влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2007/2013). Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Возвращает или задает режим автоподгонки текста. Изменение этого свойства может оказывать определённое влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Чтение/запись [TextAutofitType](../../com.aspose.slides/textautofittype).

**Возвращаемое значение:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Возвращает или задает режим автоподгонки текста. Изменение этого свойства может оказывать определённое влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Чтение/запись [TextAutofitType](../../com.aspose.slides/textautofittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего блока. Если не указано, используется вращение сопутствующей фигуры. Если указано, то он применяется независимо от фигуры. То есть к фигуре может быть применено вращение, дополнительно к вращению самого текста. Получаемое значение визуального вращения текста суммируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Чтение/запись float.

--------------------

> ```
> Рассмотрим случай, когда к фигуре применяется вращение на 90 градусов по часовой стрелке. 
>  Кроме того, само текстовое поле имеет вращение на -90 градусов 
>  против часовой стрелки. Тогда получившаяся фигура будет выглядеть
>  повернутой, но текст внутри неё будет выглядеть так, будто он вообще не вращался.
```

**Возвращаемое значение:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего блока. Если не указано, используется вращение сопутствующей фигуры. Если указано, то он применяется независимо от фигуры. То есть к фигуре может быть применено вращение, дополнительно к вращению самого текста. Получаемое значение визуального вращения текста суммируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Чтение/запись float.

--------------------

> ```
> Рассмотрите случай, когда к фигуре применяется вращение на 90 градусов по часовой стрелке. 
>  В дополнение к этому, само текстовое поле имеет вращение на -90 градусов 
>  против часовой стрелки. Затем получившаяся фигура будет выглядеть
>  повернутой, но текст внутри неё будет выглядеть так, будто он вовсе не вращался.
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |