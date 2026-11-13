---
title: IChartSeriesGroup
second_title: Справочная документация API Aspose.Slides для Java
description: Представляет группу серий.
type: docs
url: /ru/com.aspose.slides/ichartseriesgroup/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Представляет группу серий.

--------------------

1) Смотрите резюме и замечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе («свойства группы серий»). «Свойства группы серий» в классе ChartSeriesGroup имеют режим чтения/записи. Каждое из «свойств группы серий» может иметь проекцию только для чтения в классе ChartSeries.

## Методы

| Method | Описание |
| --- | --- |
| [getType()](#getType--) | Возвращает тип этой группы серий. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Указывает, построена ли серия этой группы на вторичной оси. |
| [getSeries()](#getSeries--) | Возвращает только для чтения коллекцию серий диаграммы. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [getUpDownBars()](#getUpDownBars--) | Обеспечивает доступ к барам вверх/вниз линейной или сточной диаграммы. |
| [getGapWidth()](#getGapWidth--) | Получает или задает пространство между кластерами столбцов или колонок, в процентах от ширины столбца или колонки. |
| [setGapWidth(int value)](#setGapWidth-int-) | Получает или задает пространство между кластерами столбцов или колонок, в процентах от ширины столбца или колонки. |
| [getGapDepth()](#getGapDepth--) | Получает или задает расстояние между данными сериями в 3D-диаграмме, в процентах от ширины маркера. |
| [setGapDepth(int value)](#setGapDepth-int-) | Получает или задает расстояние между данными сериями в 3D-диаграмме, в процентах от ширины маркера. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Получает или задает угол первого сектора круговой или пончиковой диаграммы, в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Получает или задает угол первого сектора круговой или пончиковой диаграммы, в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). |
| [isColorVaried()](#isColorVaried--) | Указывает, что каждый маркер данных в серии имеет разный цвет. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Указывает, что каждый маркер данных в серии имеет разный цвет. |
| [hasSeriesLines()](#hasSeriesLines--) | Истина, если диаграмма имеет линии серий. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Истина, если диаграмма имеет линии серий. |
| [getOverlap()](#getOverlap--) | Указывает, насколько столбцы и колонки перекрываются на 2-D диаграммах, в процентах (от -100% до 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Указывает, насколько столбцы и колонки перекрываются на 2-D диаграммах, в процентах (от -100% до 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Указывает размер второго пирога или столбца диаграммы «пирог-из-пирога» или «бар-из-пирога», в процентах от размера первого пирога (может быть от 5 до 200 процентов). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Указывает размер второго пирога или столбца диаграммы «пирог-из-пирога» или «бар-из-пирога», в процентах от размера первого пирога (может быть от 5 до 200 процентов). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-из-пирога» или «бар-из-пирога». |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-из-пирога» или «бар-из-пирога». |
| [getPieSplitBy()](#getPieSplitBy--) | Указывает, как определить, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-из-пирога» или «бар-из-пирога». |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Указывает, как определить, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-из-пирога» или «бар-из-пирога». |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Пользовательская информация о разграничении для диаграммы «пирог-из-пирога» или «бар-из-пирога» с пользовательским разделением. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Указывает размер отверстия в пончиковой диаграмме (может быть от 10 до 90 процентов от размера области построения). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Указывает размер отверстия в пончиковой диаграмме (может быть от 10 до 90 процентов от размера области построения). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от значения по умолчанию). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от значения по умолчанию). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Указывает формат HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Указывает, как значения размеров пузырей представлены на пузырьковой диаграмме. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Указывает, как значения размеров пузырей представлены на пузырьковой диаграмме. |

### getType() {#getType--}
```
public abstract int getType()
```

Возвращает тип этой группы серий. Только для чтения [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Возвращаемое значение:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Указывает, построена ли серия этой группы на вторичной оси. Только для чтения boolean.

**Возвращаемое значение:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Возвращает только для чтения коллекцию серий диаграммы. Только для чтения [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Возвращаемое значение:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Получает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Обеспечивает доступ к барам вверх/вниз линейной или сточной диаграммы. Только для чтения [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Возвращаемое значение:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Получает или задает пространство между кластерами столбцов или колонок, в процентах от ширины столбца или колонки. Значение должно быть от 0 до 500. Чтение/запись int.

**Возвращаемое значение:**
int

--------------------

Это свойство применяется к сериям следующих типов: Все подтипы столбцов и колонок, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Возвращаемое значение:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Устанавливает пространство между кластерами столбцов или колонок, в процентах от ширины столбца или колонки. Значение должно быть от 0 до 500. Чтение/запись int.

--------------------

Это свойство применяется к сериям следующих типов: Все подтипы столбцов и колонок, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Получает или задает расстояние между данными сериями в 3D-диаграмме, в процентах от ширины маркера. Значение должно быть от 0 до 500. Чтение/запись int.

**Возвращаемое значение:**
int

--------------------

Это свойство применяется к сериям следующих типов: 3D-подтипы столбцов и колонок, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Возвращаемое значение:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Устанавливает расстояние между данными сериями в 3D-диаграмме, в процентах от ширины маркера. Значение должно быть от 0 до 500. Чтение/запись int.

--------------------

Это свойство применяется к сериям следующих типов: 3D-подтипы столбцов и колонок, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Получает или задает угол первого сектора круговой или пончиковой диаграммы, в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). Чтение/запись int.

**Возвращаемое значение:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Устанавливает угол первого сектора круговой или пончиковой диаграммы, в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Указывает, что каждый маркер данных в серии имеет разный цвет. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Указывает, что каждый маркер данных в серии имеет разный цвет. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Истина, если диаграмма имеет линии серий. Применяется к сложенным столбцам и диаграммам OfPie. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Истина, если диаграмма имеет линии серий. Применяется к сложенным столбцам и диаграммам OfPie. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Указывает, насколько столбцы и колонки перекрываются на 2-D диаграммах, в процентах (от -100% до 100%). -100%: Максимальное расстояние (столбцы полностью разделены). 0%: Столбцы размещаются рядом без перекрытия и без расстояния. 100%: Максимальное перекрытие (столбцы полностью перекрывают друг друга). Это свойство имеет тип byte и поддерживает чтение/запись.

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Установить перекрытие на 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Указывает, насколько столбцы и колонки перекрываются на 2-D диаграммах, в процентах (от -100% до 100%). -100%: Максимальное расстояние (столбцы полностью разделены). 0%: Столбцы размещаются рядом без перекрытия и без расстояния. 100%: Максимальное перекрытие (столбцы полностью перекрывают друг друга). Это свойство имеет тип byte и поддерживает чтение/запись.

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Установить перекрытие на 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Указывает размер второго пирога или столбца диаграммы «пирог-из-пирога» или «бар-из-пирога», в процентах от размера первого пирога (может быть от 5 до 200 процентов). Чтение/запись int.

**Возвращаемое значение:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Устанавливает размер второго пирога или столбца диаграммы «пирог-из-пирога» или «бар-из-пирога», в процентах от размера первого пирога (может быть от 5 до 200 процентов). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-из-пирога» или «бар-из-пирога». Используется совместно со свойством PieSplitBy. Чтение/запись double.

**Возвращаемое значение:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Устанавливает значение, которое будет использоваться для определения, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-из-пирога» или «бар-из-пирога». Используется совместно со свойством PieSplitBy. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Указывает, как определить, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-из-пирога» или «бар-из-пирога». Чтение/запись [PieSplitType](../../com.aspose.slides/piesplittype).

**Возвращаемое значение:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Устанавливает, как определить, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-из-пирога» или «бар-из-пирога». Чтение/запись [PieSplitType](../../com.aspose.slides/piesplittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Пользовательская информация о разграничении для диаграммы «пирог-из-пирога» или «бар-из-пирога» с пользовательским разделением. Содержит точки данных, которые должны быть нарисованы во втором пироге или столбце. Только для чтения [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Возвращаемое значение:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Указывает размер отверстия в пончиковой диаграмме (может быть от 10 до 90 процентов от размера области построения). Чтение/запись byte.

**Возвращаемое значение:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Устанавливает размер отверстия в пончиковой диаграмме (может быть от 10 до 90 процентов от размера области построения). Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от значения по умолчанию). Чтение/запись int.

**Возвращаемое значение:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Устанавливает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от значения по умолчанию). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Указывает формат HiLowLines. HiLowLines применяются к типам диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose.

**Возвращаемое значение:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Указывает, как значения размеров пузырей представлены на пузырьковой диаграмме. Чтение/запись [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Возвращаемое значение:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Устанавливает, как значения размеров пузырей представлены на пузырьковой диаграмме. Чтение/запись [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |