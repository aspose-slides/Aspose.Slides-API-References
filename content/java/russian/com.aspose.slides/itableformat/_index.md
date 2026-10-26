---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: Представляет формат таблицы.
type: docs
url: /ru/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Представляет формат таблицы.
## Методы

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Возвращает объект свойств заливки таблицы. |
| [getTransparency()](#getTransparency--) | Получает или задает прозрачность цвета заливки. |
| [setTransparency(float value)](#setTransparency-float-) | Получает или задает прозрачность цвета заливки. |
| [getEffective()](#getEffective--) | Получает эффективные свойства форматирования таблицы с применённым наследованием и стилями таблицы. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Возвращает объект свойств заливки таблицы. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращает:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Получает или задает прозрачность цвета заливки. Чтение/запись  float .

**Возвращает:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Получает или задает прозрачность цвета заливки. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```

Получает эффективные свойства форматирования таблицы с применённым наследованием и стилями таблицы.

**Возвращает:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).