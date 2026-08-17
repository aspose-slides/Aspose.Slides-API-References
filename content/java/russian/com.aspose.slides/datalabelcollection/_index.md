---
title: DataLabelCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет метки серии.
type: docs
url: /ru/com.aspose.slides/datalabelcollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Представляет метки серии.
## Методы

| Метод | Описание |
| --- | --- |
| [getChart()](#getChart--) | Возвращает родительскую chart. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [isVisible()](#isVisible--) | False означает, что подпись данных не видна по умолчанию (и поэтому все флаги Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat имеют значение false). |
| [hide()](#hide--) | Сделать подпись данных скрытой по умолчанию, установив все флаги Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat в состояние false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Получает количество видимых подписей данных в коллекции. |
| [getCount()](#getCount--) | Получает количество всех подписей данных в коллекции. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Получает формат подписи данных по умолчанию. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Представляет формат линий-подключений подписей данных. |
| [getParentSeries()](#getParentSeries--) | Получает родительскую серию. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Возвращает индекс указанного DataLabel в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает подпись данных для точки данных с указанным индексом. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд FillFormat. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Возвращает родительскую chart. Только для чтения [IChart](../../com.aspose.slides/ichart).

**Возвращает:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False означает, что подпись данных не видна по умолчанию (и поэтому все флаги Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat имеют значение false). Только для чтения boolean.

--------------------

Если подпись данных видна по умолчанию, её можно скрыть по умолчанию с помощью метода Hide(). Но если подпись данных не видна по умолчанию (IsVisible равно false), её можно сделать «видимой по умолчанию», установив флаги Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat в состояние true.

**Возвращает:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Сделать подпись данных скрытой по умолчанию, установив все флаги Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat в состояние false. После этого IsVisible будет false.

--------------------

Если подпись данных не видна по умолчанию (IsVisible равно false), её можно сделать «видимой по умолчанию», установив флаги Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat в состояние true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Получает количество видимых подписей данных в коллекции. Только для чтения int.

**Возвращает:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

Получает количество всех подписей данных в коллекции. Только для чтения int.

**Возвращает:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Получает формат подписи данных по умолчанию. Только для чтения [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Возвращает:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Представляет формат линий-подключений подписей данных. Только для чтения [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Получает родительскую серию. Только для чтения [IChartSeries](../../com.aspose.slides/ichartseries).

**Возвращает:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Возвращает индекс указанного DataLabel в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel для поиска. |

**Возвращает:**
int - Индекс DataLabel или -1, если DataLabel не принадлежит этой коллекции.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Получает подпись данных для точки данных с указанным индексом.

--------------------

Альтернативный способ доступа к подписи данных: - series.getDataPoints().get_Item(i).getLabel() - управление свойствами подписи.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд FillFormat. Только для чтения [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращает:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию FillFormat. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращает:**
[IPresentation](../../com.aspose.slides/ipresentation)