---
title: IDataLabelCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет метки серии.
type: docs
url: /ru/com.aspose.slides/idatalabelcollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Представляет метки серии.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает метку данных для точки данных с указанным индексом. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Возвращает формат по умолчанию для всех меток данных в коллекции. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Представляет формат линий-выделителей меток данных. |
| [isVisible()](#isVisible--) | False означает, что метка данных не видна по умолчанию (и поэтому все флаги Show* (ShowValue, …) свойства DefaultDataLabelFormat имеют значение false). |
| [hide()](#hide--) | Сделать метку данных скрытой по умолчанию, установив все флаги Show* (ShowValue, …) свойства DefaultDataLabelFormat в состояние false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Получает количество видимых меток данных в коллекции. |
| [getCount()](#getCount--) | Получает количество всех меток данных в коллекции. |
| [getParentSeries()](#getParentSeries--) | Возвращает родительскую серию диаграммы. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Возвращает индекс указанного DataLabel в коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Получает метку данных для точки данных с указанным индексом.

--------------------

Альтернативный способ доступа к метке данных: - getSeries().getDataPoints().get_Item(i).getLabel() - управлять свойствами метки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Возвращает формат по умолчанию для всех меток данных в коллекции. Только для чтения [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Возвращаемое значение:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Представляет формат линий-выделителей меток данных. Только для чтения [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False означает, что метка данных не видна по умолчанию (и поэтому все флаги Show* (ShowValue, …) свойства DefaultDataLabelFormat имеют значение false). Только для чтения boolean .

--------------------

Если метка данных видна по умолчанию, её можно скрыть вызовом метода Hide(). Но если метка данных не видна по умолчанию (IsVisible — false), её можно сделать «видимой по умолчанию», установив все флаги Show* (ShowValue, …) свойства DefaultDataLabelFormat в состояние true.

**Возвращаемое значение:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Сделать метку данных скрытой по умолчанию, установив все флаги Show* (ShowValue, …) свойства DefaultDataLabelFormat в состояние false. После этого IsVisible будет false.

--------------------

Если метка данных не видна по умолчанию (IsVisible — false), её можно сделать «видимой по умолчанию», установив все флаги Show* (ShowValue, …) свойства DefaultDataLabelFormat в состояние true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Получает количество видимых меток данных в коллекции. Только для чтения int .

**Возвращаемое значение:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Получает количество всех меток данных в коллекции. Только для чтения int .

**Возвращаемое значение:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Возвращает родительскую серию диаграммы. Только для чтения [IChartSeries](../../com.aspose.slides/ichartseries).

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Возвращает индекс указанного DataLabel в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel для поиска. |

**Возвращаемое значение:**
int - Индекс DataLabel или -1, если DataLabel не принадлежит этой коллекции.