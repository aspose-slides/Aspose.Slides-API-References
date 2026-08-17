---
title: IColorFormat
second_title: Справочник API Aspose.Slides для Java
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

| Method | Description |
| --- | --- |
| [getColorType()](#getColorType--) | Возвращает или задает метод определения цвета. |
| [setColorType(int value)](#setColorType-int-) | Возвращает или задает метод определения цвета. |
| [getColor()](#getColor--) | Возвращает полученный цвет (с примененными всеми трансформациями цвета). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Возвращает полученный цвет (с примененными всеми трансформациями цвета). |
| [getPresetColor()](#getPresetColor--) | Возвращает или задает предустановленный цвет. |
| [setPresetColor(int value)](#setPresetColor-int-) | Возвращает или задает предустановленный цвет. |
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
| [getSaturation()](#getSaturation--) | Возвращает или задает компонент насыщенности цвета в представлении HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Возвращает или задает компонент насыщенности цвета в представлении HSL. |
| [getLuminance()](#getLuminance--) | Возвращает или задает компонент яркости цвета в представлении HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Возвращает или задает компонент яркости цвета в представлении HSL. |
| [getColorTransform()](#getColorTransform--) | Возвращает коллекцию трансформаций цвета, примененных к цвету. |
| [toString(int format)](#toString-int-) | Возвращает строку, представляющую текущий формат цвета. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Копировать формат цвета из "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Возвращает или задает метод определения цвета. Чтение/запись [ColorType](../../com.aspose.slides/colortype).

**Возвращает:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Возвращает или задает метод определения цвета. Чтение/запись [ColorType](../../com.aspose.slides/colortype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

Возвращает полученный цвет (с примененными всеми трансформациями цвета). Устанавливает RGB-цвета и очищает все трансформации цвета. Чтение/запись java.awt.Color.

**Возвращает:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Возвращает полученный цвет (с примененными всеми трансформациями цвета). Устанавливает RGB-цвета и очищает все трансформации цвета. Чтение/запись java.awt.Color.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.Color |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Возвращает или задает предустановленный цвет. Чтение/запись [PresetColor](../../com.aspose.slides/presetcolor).

**Возвращает:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Возвращает или задает предустановленный цвет. Чтение/запись [PresetColor](../../com.aspose.slides/presetcolor).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Возвращает или задает цвет, определяемый таблицей системных цветов. Чтение/запись [SystemColor](../../com.aspose.slides/systemcolor).

**Возвращает:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Возвращает или задает цвет, определяемый таблицей системных цветов. Чтение/запись [SystemColor](../../com.aspose.slides/systemcolor).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Возвращает или задает цвет, определяемый схемой цветов. Чтение/запись [SchemeColor](../../com.aspose.slides/schemecolor).

**Возвращает:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Возвращает или задает цвет, определяемый схемой цветов. Чтение/запись [SchemeColor](../../com.aspose.slides/schemecolor).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

Возвращает или задает красный компонент цвета. Все трансформации цвета игнорируются. Чтение/запись byte.

**Возвращает:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Возвращает или задает красный компонент цвета. Все трансформации цвета игнорируются. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

Возвращает или задает зеленый компонент цвета. Все трансформации цвета игнорируются. Чтение/запись byte.

**Возвращает:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Возвращает или задает зеленый компонент цвета. Все трансформации цвета игнорируются. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

Возвращает или задает синий компонент цвета. Все трансформации цвета игнорируются. Чтение/запись byte.

**Возвращает:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Возвращает или задает синий компонент цвета. Все трансформации цвета игнорируются. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Возвращает или задает красный компонент цвета. Все трансформации цвета игнорируются. Чтение/запись float.

**Возвращает:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Возвращает или задает красный компонент цвета. Все трансформации цвета игнорируются. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Возвращает или задает зеленый компонент цвета. Все трансформации цвета игнорируются. Чтение/запись float.

**Возвращает:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Возвращает или задает зеленый компонент цвета. Все трансформации цвета игнорируются. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Возвращает или задает синий компонент цвета. Все трансформации цвета игнорируются. Чтение/запись float.

**Возвращает:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Возвращает или задает синий компонент цвета. Все трансформации цвета игнорируются. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

Возвращает или задает компонент оттенка цвета в представлении HSL. Все трансформации цвета игнорируются. Чтение/запись float.

**Возвращает:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Возвращает или задает компонент оттенка цвета в представлении HSL. Все трансформации цвета игнорируются. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Возвращает или задает компонент насыщенности цвета в представлении HSL. Все трансформации цвета игнорируются. Чтение/запись float.

**Возвращает:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Возвращает или задает компонент насыщенности цвета в представлении HSL. Все трансформации цвета игнорируются. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Возвращает или задает компонент яркости цвета в представлении HSL. Все трансформации цвета игнорируются. Чтение/запись float.

**Возвращает:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Возвращает или задает компонент яркости цвета в представлении HSL. Все трансформации цвета игнорируются. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Возвращает коллекцию трансформаций цвета, примененных к цвету. Только чтение [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Возвращает:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Возвращает строку, представляющую текущий формат цвета.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | int | Тип формата строкового представления цвета. |

**Возвращает:**
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