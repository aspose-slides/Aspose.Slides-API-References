---
title: DataLabelCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет подписи серии.
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

Представляет подписи серии.
## Методы

| Метод | Описание |
| --- | --- |
| [getChart()](#getChart--) | Возвращает родительскую диаграмму. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [isVisible()](#isVisible--) | False означает, что подпись данных по умолчанию не видна (и поэтому все флаги Show*- (ShowValue, ...) свойства DefaultDataLabelFormat имеют значение false). |
| [hide()](#hide--) | Сделать подпись данных скрытой по умолчанию, установив все флаги Show*- (ShowValue, ...) свойства DefaultDataLabelFormat в состояние false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Получает количество видимых подписей данных в коллекции. |
| [getCount()](#getCount--) | Получает количество всех подписей данных в коллекции. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Получает формат подписи данных по умолчанию. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Представляет формат линий-выноски подписей данных. |
| [getParentSeries()](#getParentSeries--) | Получает родительскую серию. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Возвращает индекс указанной DataLabel в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает подпись данных для точки данных с указанным индексом. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд объекта FillFormat. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию объекта FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Возвращает родительскую диаграмму. Только для чтения [IChart](../../com.aspose.slides/ichart).

**Возвращает:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Перечислитель IGenericEnumerator, который можно использовать для прохода по коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - java.util.Iterator для всей коллекции.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False означает, что подпись данных по умолчанию не видна (и поэтому все флаги Show*- (ShowValue, ...) свойства DefaultDataLabelFormat имеют значение false). Только для чтения boolean.

--------------------

Если подпись данных видна по умолчанию, вы можете сделать её скрытой по умолчанию с помощью метода Hide(). Но если подпись данных по умолчанию не видна (IsVisible равно false), вы можете сделать подпись данных «видимой по умолчанию», установив флаги Show*- (ShowValue, ...) свойства DefaultDataLabelFormat в состояние true.

**Возвращает:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Сделать подпись данных скрытой по умолчанию, установив все флаги Show*- (ShowValue, ...) свойства DefaultDataLabelFormat в состояние false. После этого IsVisible будет false.

--------------------

Если подпись данных по умолчанию не видна (IsVisible равно false), вы можете сделать подпись данных «видимой по умолчанию», установив флаги Show*- (ShowValue, ...) свойства DefaultDataLabelFormat в состояние true.

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

Представляет формат линий-выноски подписей данных. Только для чтения [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

Возвращает индекс указанной DataLabel в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel для поиска. |

**Возвращает:**
int - Индекс DataLabel или -1, если DataLabel не из этой коллекции.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Получает подпись данных для точки данных с указанным индексом.

--------------------

Альтернативный способ доступа к подписи данных: - series.getDataPoints().get_Item(i).getLabel() - управлять свойствами подписи.

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

Возвращает родительский слайд объекта FillFormat. Только для чтения [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращает:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию объекта FillFormat. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращает:**
[IPresentation](../../com.aspose.slides/ipresentation)