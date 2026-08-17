---
title: ILineFormatEffectiveData
second_title: Справочник API Aspose.Slides для Java
description: Неизменяемый объект, содержащий свойства эффективного форматирования линии.
type: docs
url: /ru/com.aspose.slides/ilineformateffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Неизменяемый объект, содержащий свойства эффективного форматирования линии.

--------------------

Этот интерфейс используется вместе с интерфейсом [ILineFormat](../../com.aspose.slides/ilineformat) для возврата эффективных значений форматирования с применённым наследованием.
## Методы

| Метод | Описание |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Возвращает формат заливки линии. |
| [getSketchFormat()](#getSketchFormat--) | Возвращает формат штриха линии. |
| [getWidth()](#getWidth--) | Возвращает ширину линии. |
| [getDashStyle()](#getDashStyle--) | Возвращает стиль пунктировки линии. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Возвращает пользовательский шаблон пунктировки. |
| [getCapStyle()](#getCapStyle--) | Возвращает стиль конца линии. |
| [getStyle()](#getStyle--) | Возвращает стиль линии. |
| [getAlignment()](#getAlignment--) | Возвращает выравнивание линии. |
| [getJoinStyle()](#getJoinStyle--) | Возвращает стиль соединения линий. |
| [getMiterLimit()](#getMiterLimit--) | Возвращает ограничение скоса линии. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Возвращает стиль стрелки в начале линии. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Возвращает стиль стрелки в конце линии. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Возвращает ширину стрелки в начале линии. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Возвращает ширину стрелки в конце линии. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Возвращает длину стрелки в начале линии. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Возвращает длину стрелки в конце линии. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Определяет, равны ли два экземпляра ILineFormatEffectiveData. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Возвращает формат заливки линии. Только для чтения [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Возвращает:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Возвращает формат штриха линии. Только для чтения [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Возвращает:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Возвращает ширину линии. Только для чтения double.

**Возвращает:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Возвращает стиль пунктировки линии. Только для чтения [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Возвращает:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Возвращает пользовательский шаблон пунктировки. Только для чтения float[].

**Возвращает:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Возвращает стиль конца линии. Только для чтения [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Возвращает:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Возвращает стиль линии. Только для чтения [LineStyle](../../com.aspose.slides/linestyle).

**Возвращает:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Возвращает выравнивание линии. Только для чтения [LineAlignment](../../com.aspose.slides/linealignment).

**Возвращает:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Возвращает стиль соединения линий. Только для чтения [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Возвращает:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Возвращает ограничение скоса линии. Только для чтения float.

**Возвращает:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Возвращает стиль стрелки в начале линии. Только для чтения [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Возвращает:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Возвращает стиль стрелки в конце линии. Только для чтения [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Возвращает:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Возвращает ширину стрелки в начале линии. Только для чтения [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Возвращает:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Возвращает ширину стрелки в конце линии. Только для чтения [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Возвращает:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Возвращает длину стрелки в начале линии. Только для чтения [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Возвращает:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Возвращает длину стрелки в конце линии. Только для чтения [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Возвращает:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


Определяет, равны ли два экземпляра ILineFormatEffectiveData.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | ILineFormatEffectiveData, с которым сравнивается текущий ILineFormatEffectiveData. |

**Возвращает:**
boolean - **true**, если указанный ILineFormatEffectiveData равен текущему ILineFormatEffectiveData; иначе **false**.