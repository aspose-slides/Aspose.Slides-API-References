---
title: IBackground
second_title: Aspose.Slides для Java справочник API
description: Представляет фон слайда.
type: docs
url: /ru/com.aspose.slides/ibackground/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Represents background of a slide.
## Методы

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Возвращает тип заполнения фона. |
| [setType(byte value)](#setType-byte-) | Возвращает тип заполнения фона. |
| [getFillFormat()](#getFillFormat--) | Возвращает объект FillFormat для заполнения BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Возвращает объект EffectFormat для заполнения BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Возвращает объект ColorFormat для заполнения BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Возвращает индекс заполнения BackgroundType.Themed в коллекции тем фона. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Возвращает индекс заполнения BackgroundType.Themed в коллекции тем фона. |
| [getEffective()](#getEffective--) | Получает эффективные данные фона с учётом наследования. |
### getType() {#getType--}
```
public abstract byte getType()
```

Возвращает тип заполнения фона. Чтение/запись [BackgroundType](../../com.aspose.slides/backgroundtype).

**Возвращаемое значение:**
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

Возвращает объект FillFormat для заполнения BackgroundType.OwnBackground. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращаемое значение:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Возвращает объект EffectFormat для заполнения BackgroundType.OwnBackground. Только для чтения [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Возвращаемое значение:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

Возвращает объект ColorFormat для заполнения BackgroundType.Themed. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

Возвращает индекс заполнения BackgroundType.Themed в коллекции тем фона. 0 означает отсутствие заполнения. 1..999 — индекс. Чтение/запись int.

**Возвращаемое значение:**
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

Получает эффективные данные фона с учётом наследования.

**Возвращаемое значение:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) — [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).