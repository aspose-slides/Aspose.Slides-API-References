---
title: IDataLabelCollection
second_title: Справочник API Aspose.Slides для Java
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
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Возвращает формат по умолчанию всех меток данных в коллекции. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Представляет формат линий-указателей меток данных. |
| [isVisible()](#isVisible--) | False означает, что метка данных по умолчанию не видима (и поэтому все Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat имеют значение false). |
| [hide()](#hide--) | Сделать метку данных скрытой по умолчанию, установив все Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat в состояние false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Получает количество видимых меток данных в коллекции. |
| [getCount()](#getCount--) | Получает количество всех меток данных в коллекции. |
| [getParentSeries()](#getParentSeries--) | Возвращает родительскую серию диаграммы. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Возвращает индекс указанного DataLabel в коллекции. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Получает или задает тип формы по умолчанию для меток данных. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Получает или задает тип формы по умолчанию для меток данных. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Получает метку данных для точки данных с указанным индексом.

--------------------

Альтернативный способ доступа к метке данных: - getSeries().getDataPoints().get_Item(i).getLabel() - управляйте свойствами метки.

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


Возвращает формат по умолчанию всех меток данных в коллекции. Точно для чтения [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Возвращаемое значение:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


Представляет формат линий-указателей меток данных. Точно для чтения [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

**Возвращаемое значение:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False означает, что метка данных по умолчанию не видима (и поэтому все Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat имеют значение false). Точно для чтения  boolean .

--------------------

Если метка данных видима по умолчанию, вы можете сделать её скрытой по умолчанию с помощью метода Hide(). Но если метка данных не видима по умолчанию (IsVisible равно false), вы можете сделать её "видимой по умолчанию", установив флаги Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat в состояние true.

**Возвращаемое значение:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Сделать метку данных скрытой по умолчанию, установив все Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat в состояние false. После этого IsVisible будет false.

--------------------

Если метка данных не видима по умолчанию (IsVisible равно false), вы можете сделать её "видимой по умолчанию", установив флаги Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat в состояние true.
### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Получает количество видимых меток данных в коллекции. Точно для чтения  int .

**Возвращаемое значение:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Получает количество всех меток данных в коллекции. Точно для чтения  int .

**Возвращаемое значение:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Возвращает родительскую серию диаграммы. Точно для чтения [IChartSeries](../../com.aspose.slides/ichartseries).

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
int — индекс DataLabel или -1, если DataLabel не принадлежит этой коллекции.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```


Получает или задает тип формы по умолчанию для меток данных. Возвращает [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined), если форма не задана.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Установить тип формы всех меток данных в первой серии в Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Установка этого свойства также задает свойство IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) для всех меток данных в коллекции в то же значение.

**Возвращаемое значение:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```


Получает или задает тип формы по умолчанию для меток данных. Возвращает [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined), если форма не задана.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Установить тип формы всех меток данных в первой серии в Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Установка этого свойства также задает свойство IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) для всех меток данных в коллекции в то же значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |