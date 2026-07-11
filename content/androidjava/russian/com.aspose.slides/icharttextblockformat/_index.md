---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет свойства форматирования элементов текста диаграммы.
type: docs
url: /ru/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Представляет свойства форматирования элементов текста диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Возвращает или задаёт вертикальное привязывание текста в TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Возвращает или задаёт вертикальное привязывание текста в TextFrame. |
| [getCenterText()](#getCenterText--) | Если NullableBool.True, то текст должен центрироваться в коробке по горизонтали. |
| [setCenterText(byte value)](#setCenterText-byte-) | Если NullableBool.True, то текст должен центрироваться в коробке по горизонтали. |
| [getTextVerticalType()](#getTextVerticalType--) | Определяет ориентацию текста. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Определяет ориентацию текста. |
| [getMarginLeft()](#getMarginLeft--) | Возвращает или задаёт левый отступ (в пунктах) в TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Возвращает или задаёт левый отступ (в пунктах) в TextFrame. |
| [getMarginRight()](#getMarginRight--) | Возвращает или задаёт правый отступ (в пунктах) в TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Возвращает или задаёт правый отступ (в пунктах) в TextFrame. |
| [getMarginTop()](#getMarginTop--) | Возвращает или задаёт верхний отступ (в пунктах) в TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Возвращает или задаёт верхний отступ (в пунктах) в TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Возвращает или задаёт нижний отступ (в пунктах) в TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Возвращает или задаёт нижний отступ (в пунктах) в TextFrame. |
| [getWrapText()](#getWrapText--) | Истина, если текст переносится по отступам TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Истина, если текст переносится по отступам TextFrame. |
| [getAutofitType()](#getAutofitType--) | Возвращает или задаёт режим автоматической подгонки текста. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Возвращает или задаёт режим автоматической подгонки текста. |
| [getRotationAngle()](#getRotationAngle--) | Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Возвращает или задаёт вертикальное привязывание текста в TextFrame. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Возвращает:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Возвращает или задаёт вертикальное привязывание текста в TextFrame. Чтение/запись [TextAnchorType](../../com.aspose.slides/textanchortype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Если NullableBool.True, то текст должен центрироваться в коробке по горизонтали. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Если NullableBool.True, то текст должен центрироваться в коробке по горизонтали. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Определяет ориентацию текста. Итоговое значение визуального поворота текста получено из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Возвращает:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Определяет ориентацию текста. Итоговое значение визуального поворота текста получено из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Возвращает или задаёт левый отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 влияние отсутствует). Чтение/запись double.

**Возвращает:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Возвращает или задаёт левый отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 влияние отсутствует). Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Возвращает или задаёт правый отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 влияние отсутствует). Чтение/запись double.

**Возвращает:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Возвращает или задаёт правый отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 влияние отсутствует). Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Возвращает или задаёт верхний отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 влияние отсутствует). Чтение/запись double.

**Возвращает:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Возвращает или задаёт верхний отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 влияние отсутствует). Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Возвращает или задаёт нижний отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 влияние отсутствует). Чтение/запись double.

**Возвращает:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Возвращает или задаёт нижний отступ (в пунктах) в TextFrame. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 влияние отсутствует). Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Истина, если текст переносится по отступам TextFrame. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2007/2013). Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Истина, если текст переносится по отступам TextFrame. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2007/2013). Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Возвращает или задаёт режим автоматической подгонки текста. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 влияние отсутствует). Чтение/запись [TextAutofitType](../../com.aspose.slides/textautofittype).

**Возвращает:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Возвращает или задаёт режим автоматической подгонки текста. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: DataLabel и DataLabelFormat (полная поддержка в PowerPoint 2013; в PowerPoint 2007 влияние отсутствует). Чтение/запись [TextAutofitType](../../com.aspose.slides/textautofittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. Если не указан, используется поворот сопутствующей фигуры. Если указан, применяется независимо от фигуры. Таким образом, к фигуре можно применить поворот, а к самому тексту — свой поворот. Итоговое значение визуального поворота текста получено из этого свойства и предустановленного вертикального типа в свойстве TextVerticalType. Чтение/запись float.

--------------------

> ```
> Рассмотрим случай, когда к фигуре применён поворот на 90 градусов по часовой стрелке. 
>  В дополнение к этому, сам текстовый блок имеет поворот на -90 градусов 
>  против часовой стрелки. Затем получившаяся фигура будет выглядеть так, что
>  будет повёрнута, но текст внутри неё будет выглядеть так, как будто он вовсе не был повёрнут.
> ```


**Возвращает:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. Если не указан, используется поворот сопутствующей фигуры. Если указан, применяется независимо от фигуры. Таким образом, к фигуре можно применить поворот, а к самому тексту — свой поворот. Итоговое значение визуального поворота текста получено из этого свойства и предустановленного вертикального типа в свойстве TextVerticalType. Чтение/запись float.

--------------------

> ```
> Рассмотрите случай, когда к фигуре применён поворот на 90 градусов по часовой стрелке. 
>  В дополнение к этому, сам текстовый блок имеет поворот на -90 градусов 
>  против часовой стрелки, применённый к нему. Затем получающаяся фигура будет выглядеть так, что
>  будет повёрнутой, но текст внутри неё будет выглядеть так, будто он совсем не был повёрнут.
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |