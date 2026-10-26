---
title: ColorFormat
second_title: Справочник API Aspose.Slides для Java
description: Представляет цвет, используемый в презентации.
type: docs
url: /ru/com.aspose.slides/colorformat/
---
**Наследование:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**  
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)  
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

Представляет цвет, используемый в презентации.
## Методы

| Method | Description |
| --- | --- |
| [getColorType()](#getColorType--) | Возвращает или задает метод определения цвета. |
| [setColorType(int value)](#setColorType-int-) | Возвращает или задает метод определения цвета. |
| [getColor()](#getColor--) | Возвращает полученный цвет (с примененными всеми преобразованиями цвета). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Возвращает полученный цвет (с примененными всеми преобразованиями цвета). |
| [getPresetColor()](#getPresetColor--) | Возвращает или задает предустановку цвета. |
| [setPresetColor(int value)](#setPresetColor-int-) | Возвращает или задает предустановку цвета. |
| [getSystemColor()](#getSystemColor--) | Возвращает или задает цвет, определяемый таблицей системных цветов. |
| [setSystemColor(int value)](#setSystemColor-int-) | Возвращает или задает цвет, определяемый таблицей системных цветов. |
| [getSchemeColor()](#getSchemeColor--) | Возвращает или задает цвет, определяемый схемой цветов. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Возвращает или задает цвет, определяемый схемой цветов. |
| [getR()](#getR--) | Возвращает или задает красный компонент цвета. |
| [setR(byte value)](#setR-byte-) | Возвращает или задает красный компонент цвета. |
| [getG()](#getG--) | Возвращает или задает зеленый компонент цвета. |
| [setG(byte value)](#setG-byte-) | Возвращает или задает зеленый компонент цвета. |
| [getB()](#getB--) | Возвращает или задает синий компонент цвета. |
| [setB(byte value)](#setB-byte-) | Возвращает или задает синий компонент цвета. |
| [getFloatR()](#getFloatR--) | Возвращает или задает красный компонент цвета. |
| [setFloatR(float value)](#setFloatR-float-) | Возвращает или задает красный компонент цвета. |
| [getFloatG()](#getFloatG--) | Возвращает или задает зеленый компонент цвета. |
| [setFloatG(float value)](#setFloatG-float-) | Возвращает или задает зеленый компонент цвета. |
| [getFloatB()](#getFloatB--) | Возвращает или задает синий компонент цвета. |
| [setFloatB(float value)](#setFloatB-float-) | Возвращает или задает синий компонент цвета. |
| [getHue()](#getHue--) | Возвращает или задает компонент оттенка цвета в представлении HSL. |
| [setHue(float value)](#setHue-float-) | Возвращает или задает компонент оттенка цвета в представлении HSL. |
| [getSaturation()](#getSaturation--) | Возвращает или задает компонент насыщения цвета в представлении HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Возвращает или задает компонент насыщения цвета в представлении HSL. |
| [getLuminance()](#getLuminance--) | Возвращает или задает компонент яркости цвета в представлении HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Возвращает или задает компонент яркости цвета в представлении HSL. |
| [getColorTransform()](#getColorTransform--) | Возвращает коллекцию преобразований цвета, примененных к цвету. |
| [toString(int format)](#toString-int-) | Возвращает строку, представляющую текущий формат цвета. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Копировать формат цвета из "color". |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет равенство с указанным объектом. |
| [hashCode()](#hashCode--) | Возвращает хэш-код. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getColorType() {#getColorType--}
```
public final int getColorType()
```

Возвращает или задает метод определения цвета. Чтение/запись [ColorType](../../com.aspose.slides/colortype).

**Возвращаемое значение:**
int

### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

Возвращает или задает метод определения цвета. Чтение/запись [ColorType](../../com.aspose.slides/colortype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Color getColor()
```

Возвращает полученный цвет (с примененными всеми преобразованиями цвета). Устанавливает RGB-цвета и очищает все преобразования цвета. Чтение/запись java.awt.Color.

**Возвращаемое значение:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

Возвращает полученный цвет (с примененными всеми преобразованиями цвета). Устанавливает RGB-цвета и очищает все преобразования цвета. Чтение/запись java.awt.Color.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

Возвращает или задает предустановку цвета. Чтение/запись [PresetColor](../../com.aspose.slides/presetcolor).

**Возвращаемое значение:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

Возвращает или задает предустановку цвета. Чтение/запись [PresetColor](../../com.aspose.slides/presetcolor).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

Возвращает или задает цвет, определяемый таблицей системных цветов. Чтение/запись [SystemColor](../../com.aspose.slides/systemcolor).

**Возвращаемое значение:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

Возвращает или задает цвет, определяемый таблицей системных цветов. Чтение/запись [SystemColor](../../com.aspose.slides/systemcolor).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

Возвращает или задает цвет, определяемый схемой цветов. Чтение/запись [SchemeColor](../../com.aspose.slides/schemecolor).

**Возвращаемое значение:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

Возвращает или задает цвет, определяемый схемой цветов. Чтение/запись [SchemeColor](../../com.aspose.slides/schemecolor).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

Возвращает или задает красный компонент цвета. Все преобразования цвета игнорируются. Чтение/запись  byte .

**Возвращаемое значение:**
byte

### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

Возвращает или задает красный компонент цвета. Все преобразования цвета игнорируются. Чтение/запись  byte .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

Возвращает или задает зеленый компонент цвета. Все преобразования цвета игнорируются.

**Возвращаемое значение:**
byte

### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

Возвращает или задает зеленый компонент цвета. Все преобразования цвета игнорируются.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

Возвращает или задает синий компонент цвета. Все преобразования цвета игнорируются. Чтение/запись  byte .

**Возвращаемое значение:**
byte

### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

Возвращает или задает синий компонент цвета. Все преобразования цвета игнорируются. Чтение/запись  byte .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

Возвращает или задает красный компонент цвета. Все преобразования цвета игнорируются. Чтение/запись  float .

**Возвращаемое значение:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

Возвращает или задает красный компонент цвета. Все преобразования цвета игнорируются. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

Возвращает или задает зеленый компонент цвета. Все преобразования цвета игнорируются. Чтение/запись  float .

**Возвращаемое значение:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

Возвращает или задает зеленый компонент цвета. Все преобразования цвета игнорируются. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

Возвращает или задает синий компонент цвета. Все преобразования цвета игнорируются. Чтение/запись  float .

**Возвращаемое значение:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

Возвращает или задает синий компонент цвета. Все преобразования цвета игнорируются. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

Возвращает или задает компонент оттенка цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/запись  float .

**Возвращаемое значение:**
float

### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

Возвращает или задает компонент оттенка цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

Возвращает или задает компонент насыщения цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/запись  float .

**Возвращаемое значение:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

Возвращает или задает компонент насыщения цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

Возвращает или задает компонент яркости цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/запись  float .

**Возвращаемое значение:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

Возвращает или задает компонент яркости цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

Возвращает коллекцию преобразований цвета, примененных к цвету. Только чтение [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Возвращаемое значение:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

Возвращает строку, представляющую текущий формат цвета.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | int | Тип формата строкового представления цвета. |

**Возвращаемое значение:**
java.lang.String — Строка, представляющая текущий формат цвета.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

Копировать формат цвета из "color".

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Проверяет равенство с указанным объектом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект. |

**Возвращаемое значение:**
boolean — Истина, если объекты равны, иначе ложь.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Возвращает хэш-код.

**Возвращаемое значение:**
int — Хэш-код.

### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только чтение long.

**Возвращаемое значение:**
long

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```

**Возвращаемое значение:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Возвращает родительский IPresentationComponent. Только чтение [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Возвращаемое значение:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)