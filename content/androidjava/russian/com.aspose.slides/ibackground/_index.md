---
title: IBackground
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет фон слайда.
type: docs
url: /ru/com.aspose.slides/ibackground/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Представляет фон слайда.
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Возвращает тип заполнения фона. |
| [setType(byte value)](#setType-byte-) | Возвращает тип заполнения фона. |
| [getFillFormat()](#getFillFormat--) | Возвращает FillFormat для заполнения BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Возвращает EffectFormat для заполнения BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Возвращает ColorFormat для заполнения BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Возвращает индекс заполнения BackgroundType.Themed в коллекции тем фона. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Возвращает индекс заполнения BackgroundType.Themed в коллекции тем фона. |
| [getEffective()](#getEffective--) | Получает эффективные данные фона с применённым наследованием. |
### getType() {#getType--}
```
public abstract byte getType()
```

Возвращает тип заполнения фона. Чтение/запись [BackgroundType](../../com.aspose.slides/backgroundtype).

**Возвращаемое:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Возвращает тип заполнения фона. Чтение/запись [BackgroundType](../../com.aspose.slides/backgroundtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Возвращает FillFormat для заполнения BackgroundType.OwnBackground. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращаемое:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Возвращает EffectFormat для заполнения BackgroundType.OwnBackground. Только для чтения [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Возвращаемое:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

Возвращает ColorFormat для заполнения BackgroundType.Themed. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

Возвращает индекс заполнения BackgroundType.Themed в коллекции тем фона. 0 означает отсутствие заполнения. 1..999 — индекс. Чтение/запись int.

**Возвращаемое:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

Возвращает индекс заполнения BackgroundType.Themed в коллекции тем фона. 0 означает отсутствие заполнения. 1..999 — индекс. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

Получает эффективные данные фона с применённым наследованием.

**Возвращаемое:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - Объект [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).