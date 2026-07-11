---
title: LineFormat
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет формат линии.
type: docs
url: /ru/com.aspose.slides/lineformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Представляет формат линии.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Возвращает true, если формат линии не определён (только что создан, по умолчанию). |
| [getFillFormat()](#getFillFormat--) | Возвращает формат заполнения линии. |
| [getSketchFormat()](#getSketchFormat--) | Возвращает формат эскиза линии. |
| [getWidth()](#getWidth--) | Возвращает или задаёт ширину линии. |
| [setWidth(double value)](#setWidth-double-) | Возвращает или задаёт ширину линии. |
| [getDashStyle()](#getDashStyle--) | Возвращает или задаёт стиль штриха линии. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Возвращает или задаёт стиль штриха линии. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Возвращает или задаёт пользовательский шаблон штриха. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Возвращает или задаёт пользовательский шаблон штриха. |
| [getCapStyle()](#getCapStyle--) | Возвращает или задаёт стиль окончания линии. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Возвращает или задаёт стиль окончания линии. |
| [getStyle()](#getStyle--) | Возвращает или задаёт стиль линии. |
| [setStyle(byte value)](#setStyle-byte-) | Возвращает или задаёт стиль линии. |
| [getAlignment()](#getAlignment--) | Возвращает или задаёт выравнивание линии. |
| [setAlignment(byte value)](#setAlignment-byte-) | Возвращает или задаёт выравнивание линии. |
| [getJoinStyle()](#getJoinStyle--) | Возвращает или задаёт стиль соединения линий. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Возвращает или задаёт стиль соединения линий. |
| [getMiterLimit()](#getMiterLimit--) | Возвращает или задаёт предел среза (miter limit) линии. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Возвращает или задаёт предел среза (miter limit) линии. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Возвращает или задаёт стиль наконечника стрелки в начале линии. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Возвращает или задаёт стиль наконечника стрелки в начале линии. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Возвращает или задаёт стиль наконечника стрелки в конце линии. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Возвращает или задаёт стиль наконечника стрелки в конце линии. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Возвращает или задаёт ширину наконечника стрелки в начале линии. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Возвращает или задаёт ширину наконечника стрелки в начале линии. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Возвращает или задаёт ширину наконечника стрелки в конце линии. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Возвращает или задаёт ширину наконечника стрелки в конце линии. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Возвращает или задаёт длину наконечника стрелки в начале линии. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Возвращает или задаёт длину наконечника стрелки в начале линии. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Возвращает или задаёт длину наконечника стрелки в конце линии. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Возвращает или задаёт длину наконечника стрелки в конце линии. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Определяет, равны ли два экземпляра LineFormat. |
| [getEffective()](#getEffective--) | Получает данные эффективного форматирования линии с учётом наследования. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращаемое значение:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Сравнивает с указанным объектом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Возвращаемое значение:**
boolean
### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

Возвращает true, если формат линии не определён (только что создан, по умолчанию). Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

Возвращает формат заполнения линии. Только для чтения [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Возвращаемое значение:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

Возвращает формат эскиза линии. Только для чтения [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Возвращаемое значение:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Возвращает или задаёт ширину линии. Чтение/запись double.

**Возвращаемое значение:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Возвращает или задаёт ширину линии. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

Возвращает или задаёт стиль штриха линии. Чтение/запись [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Возвращаемое значение:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

Возвращает или задаёт стиль штриха линии. Чтение/запись [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

Возвращает или задаёт пользовательский шаблон штриха. Чтение/запись float[].

**Возвращаемое значение:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

Возвращает или задаёт пользовательский шаблон штриха. Чтение/запись float[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

Возвращает или задаёт стиль окончания линии. Чтение/запись [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Возвращаемое значение:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

Возвращает или задаёт стиль окончания линии. Чтение/запись [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public final byte getStyle()
```

Возвращает или задаёт стиль линии. Чтение/запись [LineStyle](../../com.aspose.slides/linestyle).

**Возвращаемое значение:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

Возвращает или задаёт стиль линии. Чтение/запись [LineStyle](../../com.aspose.slides/linestyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

Возвращает или задаёт выравнивание линии. Чтение/запись [LineAlignment](../../com.aspose.slides/linealignment).

**Возвращаемое значение:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

Возвращает или задаёт выравнивание линии. Чтение/запись [LineAlignment](../../com.aspose.slides/linealignment).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

Возвращает или задаёт стиль соединения линий. Чтение/запись [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Возвращаемое значение:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

Возвращает или задаёт стиль соединения линий. Чтение/запись [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

Возвращает или задаёт предел среза (miter limit) линии. Чтение/запись float.

**Возвращаемое значение:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

Возвращает или задаёт предел среза (miter limit) линии. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

Возвращает или задаёт стиль наконечника стрелки в начале линии. Чтение/запись [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Возвращаемое значение:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

Возвращает или задаёт стиль наконечника стрелки в начале линии. Чтение/запись [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

Возвращает или задаёт стиль наконечника стрелки в конце линии. Чтение/запись [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Возвращаемое значение:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

Возвращает или задаёт стиль наконечника стрелки в конце линии. Чтение/запись [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

Возвращает или задаёт ширину наконечника стрелки в начале линии. Чтение/запись [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Возвращаемое значение:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

Возвращает или задаёт ширину наконечника стрелки в начале линии. Чтение/запись [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

Возвращает или задаёт ширину наконечника стрелки в конце линии. Чтение/запись [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Возвращаемое значение:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

Возвращает или задаёт ширину наконечника стрелки в конце линии. Чтение/запись [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

Возвращает или задаёт длину наконечника стрелки в начале линии. Чтение/запись [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Возвращаемое значение:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

Возвращает или задаёт длину наконечника стрелки в начале линии. Чтение/запись [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

Возвращает или задаёт длину наконечника стрелки в конце линии. Чтение/запись [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Возвращаемое значение:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

Возвращает или задаёт длину наконечника стрелки в конце линии. Чтение/запись [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

Определяет, равны ли два экземпляра LineFormat.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat для сравнения с текущим LineFormat. |

**Возвращаемое значение:**
boolean - **true**, если указанный LineFormat равен текущему LineFormat; иначе **false**.
### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

Получает данные эффективного форматирования линии с учётом наследования.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).