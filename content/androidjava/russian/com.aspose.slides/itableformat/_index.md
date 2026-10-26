---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет формат таблицы.
type: docs
url: /ru/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Представляет формат таблицы.
## Методы

| Метод | Описание |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Возвращает объект свойств заливки таблицы. |
| [getTransparency()](#getTransparency--) | Получает или задает прозрачность цвета заливки. |
| [setTransparency(float value)](#setTransparency-float-) | Получает или задает прозрачность цвета заливки. |
| [getEffective()](#getEffective--) | Получает эффективные свойства форматирования таблицы с учётом наследования и применённых стилей таблицы. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Возвращает объект свойств заливки таблицы. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращаемое значение:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Получает или задает прозрачность цвета заливки. Чтение/запись  float .

**Возвращаемое значение:**
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

Получает эффективные свойства форматирования таблицы с учётом наследования и применённых стилей таблицы.

**Возвращаемое значение:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - объект [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).