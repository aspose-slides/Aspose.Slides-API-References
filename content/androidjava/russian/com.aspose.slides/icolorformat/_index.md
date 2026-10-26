---
title: IColorFormat
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет цвет, используемый в презентации.
type: docs
url: /ru/com.aspose.slides/icolorformat/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Представляет цвет, используемый в презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getColorType()](#getColorType--) | Возвращает или задаёт метод определения цвета. |
| [setColorType(int value)](#setColorType-int-) | Возвращает или задаёт метод определения цвета. |
| [getColor()](#getColor--) | Возвращает полученный цвет (с учётом всех применённых преобразований цвета). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Возвращает полученный цвет (с учётом всех применённых преобразований цвета). |
| [getPresetColor()](#getPresetColor--) | Возвращает или задаёт предустановленный цвет. |
| [setPresetColor(int value)](#setPresetColor-int-) | Возвращает или задаёт предустановленный цвет. |
| [getSystemColor()](#getSystemColor--) | Возвращает или задаёт цвет, определённый системной таблицей цветов. |
| [setSystemColor(int value)](#setSystemColor-int-) | Возвращает или задаёт цвет, определённый системной таблицей цветов. |
| [getSchemeColor()](#getSchemeColor--) | Возвращает или задаёт цвет, определённый схемой цветов. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Возвращает или задаёт цвет, определённый схемой цветов. |
| [getR()](#getR--) | Возвращает или задаёт красный компонент цвета. |
| [setR(byte value)](#setR-byte-) | Возвращает или задаёт красный компонент цвета. |
| [getG()](#getG--) | Возвращает или задаёт зелёный компонент цвета. |
| [setG(byte value)](#setG-byte-) | Возвращает или задаёт зелёный компонент цвета. |
| [getB()](#getB--) | Возвращает или задаёт синий компонент цвета. |
| [setB(byte value)](#setB-byte-) | Возвращает или задаёт синий компонент цвета. |
| [getFloatR()](#getFloatR--) | Возвращает или задаёт красный компонент цвета. |
| [setFloatR(float value)](#setFloatR-float-) | Возвращает или задаёт красный компонент цвета. |
| [getFloatG()](#getFloatG--) | Возвращает или задаёт зелёный компонент цвета. |
| [setFloatG(float value)](#setFloatG-float-) | Возвращает или задаёт зелёный компонент цвета. |
| [getFloatB()](#getFloatB--) | Возвращает или задаёт синий компонент цвета. |
| [setFloatB(float value)](#setFloatB-float-) | Возвращает или задаёт синий компонент цвета. |
| [getHue()](#getHue--) | Возвращает или задаёт компонент оттенка цвета в представлении HSL. |
| [setHue(float value)](#setHue-float-) | Возвращает или задаёт компонент оттенка цвета в представлении HSL. |
| [getSaturation()](#getSaturation--) | Возвращает или задаёт компонент насыщенности цвета в представлении HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Возвращает или задаёт компонент насыщенности цвета в представлении HSL. |
| [getLuminance()](#getLuminance--) | Возвращает или задаёт компонент яркости цвета в представлении HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Возвращает или задаёт компонент яркости цвета в представлении HSL. |
| [getColorTransform()](#getColorTransform--) | Возвращает коллекцию преобразований цвета, применённых к цвету. |
| [toString(int format)](#toString-int-) | Возвращает строку, представляющую текущий формат цвета. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Копировать формат цвета из "color". |

### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Возвращает или задаёт метод определения цвета. Чтение/запись [ColorType](../../com.aspose.slides/colortype).

**Возвращаемое значение:**
int

### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Возвращает или задаёт метод определения цвета. Чтение/запись [ColorType](../../com.aspose.slides/colortype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Возвращает полученный цвет (с учётом всех применённых преобразований цвета). Устанавливает RGB-цвета и очищает все преобразования цвета. Чтение/запись java.lang.Integer.

**Возвращаемое значение:**
java.lang.Integer

### setColor(java.lang.Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

Возвращает полученный цвет (с учётом всех применённых преобразований цвета). Устанавливает RGB-цвета и очищает все преобразования цвета. Чтение/запись java.lang.Integer.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Возвращает или задаёт предустановленный цвет. Чтение/запись [PresetColor](../../com.aspose.slides/presetcolor).

**Возвращаемое значение:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Возвращает или задаёт предустановленный цвет. Чтение/запись [PresetColor](../../com.aspose.slides/presetcolor).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Возвращает или задаёт цвет, определённый системной таблицей цветов. Чтение/запись [SystemColor](../../com.aspose.slides/systemcolor).

**Возвращаемое значение:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Возвращает или задаёт цвет, определённый системной таблицей цветов. Чтение/запись [SystemColor](../../com.aspose.slides/systemcolor).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Возвращает или задаёт цвет, определённый схемой цветов. Чтение/запись [SchemeColor](../../com.aspose.slides/schemecolor).

**Возвращаемое значение:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Возвращает или задаёт цвет, определённый схемой цветов. Чтение/запись [SchemeColor](../../com.aspose.slides/schemecolor).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

Возвращает или задаёт красный компонент цвета. Все преобразования цвета игнорируются. Чтение/запись byte.

**Возвращаемое значение:**
byte

### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Возвращает или задаёт красный компонент цвета. Все преобразования цвета игнорируются. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

Возвращает или задаёт зелёный компонент цвета. Все преобразования цвета игнорируются. Чтение/запись byte.

**Возвращаемое значение:**
byte

### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Возвращает или задаёт зелёный компонент цвета. Все преобразования цвета игнорируются. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

Возвращает или задаёт синий компонент цвета. Все преобразования цвета игнорируются. Чтение/запись byte.

**Возвращаемое значение:**
byte

### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Возвращает или задаёт синий компонент цвета. Все преобразования цвета игнорируются. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Возвращает или задаёт красный компонент цвета. Все преобразования цвета игнорируются. Чтение/запись float.

**Возвращаемое значение:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Возвращает или задаёт красный компонент цвета. Все преобразования цвета игнорируются. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Возвращает или задаёт зелёный компонент цвета. Все преобразования цвета игнорируются. Чтение/запись float.

**Возвращаемое значение:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Возвращает или задаёт зелёный компонент цвета. Все преобразования цвета игнорируются. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Возвращает или задаёт синий компонент цвета. Все преобразования цвета игнорируются. Чтение/запись float.

**Возвращаемое значение:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Возвращает или задаёт синий компонент цвета. Все преобразования цвета игнорируются. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

Возвращает или задаёт компонент оттенка цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/запись float.

**Возвращаемое значение:**
float

### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Возвращает или задаёт компонент оттенка цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Возвращает или задаёт компонент насыщенности цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/запись float.

**Возвращаемое значение:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Возвращает или задаёт компонент насыщенности цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Возвращает или задаёт компонент яркости цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/запись float.

**Возвращаемое значение:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Возвращает или задаёт компонент яркости цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Возвращает коллекцию преобразований цвета, применённых к цвету. Только для чтения [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Возвращаемое значение:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Возвращает строку, представляющую текущий формат цвета.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | int | Тип строкового представления цвета. |

**Возвращаемое значение:**
java.lang.String - строка, представляющая текущий формат цвета.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Копировать формат цвета из "color".

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Цвет [IColorFormat](../../com.aspose.slides/icolorformat) |