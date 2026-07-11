---
title: ILineFormat
second_title: Справочник API Aspose.Slides для Android через Java
description: Представляет формат линии.
type: docs
url: /ru/com.aspose.slides/ilineformat/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Представляет формат линии.

## Методы

| Метод | Описание |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Возвращает true, если формат линии не определён (как только созданный, по умолчанию). |
| [getFillFormat()](#getFillFormat--) | Возвращает формат заливки линии. |
| [getSketchFormat()](#getSketchFormat--) | Возвращает формат наброска линии. |
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
| [getMiterLimit()](#getMiterLimit--) | Возвращает или задаёт предел среза линии. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Возвращает или задаёт предел среза линии. |
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
| [getEffective()](#getEffective--) | Получает эффективные данные форматирования линии с учётом наследования. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Возвращает true, если формат линии не определён (как только созданный, по умолчанию). Только для чтения boolean.

**Возвращает:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Возвращает формат заливки линии. Только для чтения [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Возвращает:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Возвращает формат наброска линии. Только для чтения [ISketchFormat](../../com.aspose.slides/isketchformat).

**Возвращает:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Возвращает или задаёт ширину линии. Чтение/запись double.

**Возвращает:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Возвращает или задаёт ширину линии. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Возвращает или задаёт стиль штриха линии. Чтение/запись [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Возвращает:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Возвращает или задаёт стиль штриха линии. Чтение/запись [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Возвращает или задаёт пользовательский шаблон штриха. Чтение/запись float[].

**Возвращает:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Возвращает или задаёт пользовательский шаблон штриха. Чтение/запись float[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Возвращает или задаёт стиль окончания линии. Чтение/запись [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Возвращает:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Возвращает или задаёт стиль окончания линии. Чтение/запись [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Возвращает или задаёт стиль линии. Чтение/запись [LineStyle](../../com.aspose.slides/linestyle).

**Возвращает:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Возвращает или задаёт стиль линии. Чтение/запись [LineStyle](../../com.aspose.slides/linestyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Возвращает или задаёт выравнивание линии. Чтение/запись [LineAlignment](../../com.aspose.slides/linealignment).

**Возвращает:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Возвращает или задаёт выравнивание линии. Чтение/запись [LineAlignment](../../com.aspose.slides/linealignment).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Возвращает или задаёт стиль соединения линий. Чтение/запись [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Возвращает:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Возвращает или задаёт стиль соединения линий. Чтение/запись [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Возвращает или задаёт предел среза линии. Чтение/запись float.

**Возвращает:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Возвращает или задаёт предел среза линии. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Возвращает или задаёт стиль наконечника стрелки в начале линии. Чтение/запись [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Возвращает:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Возвращает или задаёт стиль наконечника стрелки в начале линии. Чтение/запись [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Возвращает или задаёт стиль наконечника стрелки в конце линии. Чтение/запись [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Возвращает:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Возвращает или задаёт стиль наконечника стрелки в конце линии. Чтение/запись [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Возвращает или задаёт ширину наконечника стрелки в начале линии. Чтение/запись [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Возвращает:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Возвращает или задаёт ширину наконечника стрелки в начале линии. Чтение/запись [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Возвращает или задаёт ширину наконечника стрелки в конце линии. Чтение/запись [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Возвращает:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Возвращает или задаёт ширину наконечника стрелки в конце линии. Чтение/запись [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Возвращает или задаёт длину наконечника стрелки в начале линии. Чтение/запись [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Возвращает:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Возвращает или задаёт длину наконечника стрелки в начале линии. Чтение/запись [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Возвращает или задаёт длину наконечника стрелки в конце линии. Чтение/запись [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Возвращает:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Возвращает или задаёт длину наконечника стрелки в конце линии. Чтение/запись [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Определяет, равны ли два экземпляра LineFormat.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat для сравнения с текущим LineFormat. |

**Возвращает:**
boolean — **true**, если указанный LineFormat равен текущему LineFormat; иначе — **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Получает эффективные данные форматирования линии с учётом наследования.

**Возвращает:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).