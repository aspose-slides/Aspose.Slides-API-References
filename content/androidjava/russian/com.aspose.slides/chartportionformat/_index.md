---
title: ChartPortionFormat
second_title: Aspose.Slides для Android через справочник Java API
description: Этот класс содержит свойства форматирования частей диаграммы, используемые в диаграммах.
type: docs
url: /ru/com.aspose.slides/chartportionformat/
---

**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
```
public final class ChartPortionFormat extends BasePortionFormat implements IChartPortionFormat
```

Этот класс содержит свойства форматирования частей диаграммы, используемые в диаграммах. В отличие от [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), все свойства этого класса доступны для записи.

--------------------

Этот класс используется для получения и изменения свойств форматирования текстовой части, определённых для конкретной части. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective), который возвращает экземпляр [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращаемое значение:**
long