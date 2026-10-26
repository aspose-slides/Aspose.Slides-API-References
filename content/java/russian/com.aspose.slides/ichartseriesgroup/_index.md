---
title: IChartSeriesGroup
second_title: Справочник API Aspose.Slides для Java
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

1) См. сводку и примечания к классу ChartSeriesGroupCollection и перечислению CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе («свойства группы серий»). «Свойства группы серий» в классе ChartSeriesGroup являются чтение/запись. Каждое из «свойств группы серий» может иметь проекцию только для чтения в классе ChartSeries.

## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Возвращает тип этой группы серий. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Указывает, построены ли серии этой группы на вторичной оси. |
| [getSeries()](#getSeries--) | Возвращает только для чтения коллекцию серий диаграммы. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [getUpDownBars()](#getUpDownBars--) | Обеспечивает доступ к верхним/нижним полосам линейной или сточной диаграммы. |
| [getGapWidth()](#getGapWidth--) | Указывает пространство между кластерами столбцов или колонн в процентах от их ширины. |
| [setGapWidth(int value)](#setGapWidth-int-) | Указывает пространство между кластерами столбцов или колонн в процентах от их ширины. |
| [getGapDepth()](#getGapDepth--) | Возвращает или задает расстояние, в процентах от ширины маркера, между данными серий в 3D-диаграмме. |
| [setGapDepth(int value)](#setGapDepth-int-) | Возвращает или задает расстояние, в процентах от ширины маркера, между данными серий в 3D-диаграмме. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). |
| [isColorVaried()](#isColorVaried--) | Указывает, что каждый маркер данных в серии имеет разный цвет. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Указывает, что каждый маркер данных в серии имеет разный цвет. |
| [hasSeriesLines()](#hasSeriesLines--) | Истина, если диаграмма имеет линии серий. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Истина, если диаграмма имеет линии серий. |
| [getOverlap()](#getOverlap--) | Указывает, насколько столбцы и колонки перекрываются в 2-D диаграммах, в процентах (от -100 % до 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Указывает, насколько столбцы и колонки перекрываются в 2-D диаграммах, в процентах (от -100 % до 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Указывает размер второго круга или столбца в диаграмме «пирог-в-пироге» или «бар-в-пироге», в процентах от размера первого круга (может быть от 5 % до 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Указывает размер второго круга или столбца в диаграмме «пирог-в-пироге» или «бар-в-пироге», в процентах от размера первого круга (может быть от 5 % до 200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Указывает значение, которое используется для определения, какие точки данных находятся во втором круге или столбце в диаграмме «пирог-в-пироге» или «бар-в-пироге». |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Указывает значение, которое используется для определения, какие точки данных находятся во втором круге или столбце в диаграмме «пирог-в-пироге» или «бар-в-пироге». |
| [getPieSplitBy()](#getPieSplitBy--) | Указывает, как определить, какие точки данных находятся во втором круге или столбце в диаграмме «пирог-в-пироге» или «бар-в-пироге». |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Указывает, как определить, какие точки данных находятся во втором круге или столбце в диаграмме «пирог-в-пироге» или «бар-в-пироге». |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Пользовательская информация о разбиении для диаграммы «пирог-в-пироге» или «бар-в-пироге» с пользовательским разбиением. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Указывает размер отверстия в кольцевой диаграмме (может быть от 10 % до 90 % от размера области построения). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Указывает размер отверстия в кольцевой диаграмме (может быть от 10 % до 90 % от размера области построения). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 % до 300 % от стандартного размера). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 % до 300 % от стандартного размера). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Указывает формат HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Указывает, как значения размеров пузырей отображаются на пузырьковой диаграмме. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Указывает, как значения размеров пузырей отображаются на пузырьковой диаграмме. |

### getType() {#getType--}
```
public abstract int getType()
```

Возвращает тип этой группы серий. Только для чтения [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Возвращает:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Указывает, построены ли серии этой группы на вторичной оси. Только для чтения boolean.

**Возвращает:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Возвращает только для чтения коллекцию серий диаграммы. Только для чтения [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Возвращает:**
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

**Возвращает:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Обеспечивает доступ к верхним/нижним полосам линейной или сточной диаграммы. Только для чтения [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Возвращает:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Указывает пространство между кластерами столбцов или колонн в процентах от их ширины. Чтение/запись int.

**Возвращает:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Указывает пространство между кластерами столбцов или колонн в процентах от их ширины. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Возвращает или задает расстояние, в процентах от ширины маркера, между данными серий в 3D-диаграмме. Чтение/запись int.

**Возвращает:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Возвращает или задает расстояние, в процентах от ширины маркера, между данными серий в 3D-диаграмме. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). Чтение/запись int.

**Возвращает:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Указывает, что каждый маркер данных в серии имеет разный цвет. Чтение/запись boolean.

**Возвращает:**
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

**Возвращает:**
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

Указывает, насколько столбцы и колонки перекрываются в 2-D диаграммах, в процентах (от -100 % до 100 %). - -100 %: Максимальное расстояние (столбцы полностью разделены). - 0 %: Столбцы размещаются рядом без перекрытия или интервала. - 100 %: Максимальное перекрытие (столбцы полностью перекрывают друг друга). Это свойство является чтение/запись byte.

**Возвращает:**
byte

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Установить перекрытие 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Указывает, насколько столбцы и колонки перекрываются в 2-D диаграммах, в процентах (от -100 % до 100 %). - -100 %: Максимальное расстояние (столбцы полностью разделены). - 0 %: Столбцы размещаются рядом без перекрытия или интервала. - 100 %: Максимальное перекрытие (столбцы полностью перекрывают друг друга). Это свойство является чтение/запись byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Установить перекрытие 55%
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

Указывает размер второго круга или столбца в диаграмме «пирог-в-пироге» или «бар-в-пироге», в процентах от размера первого круга (может быть от 5 % до 200 %). Чтение/запись int.

**Возвращает:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Указывает размер второго круга или столбца в диаграмме «пирог-в-пироге» или «бар-в-пироге», в процентах от размера первого круга (может быть от 5 % до 200 %). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Указывает значение, которое используется для определения, какие точки данных находятся во втором круге или столбце в диаграмме «пирог-в-пироге» или «бар-в-пироге». Используется совместно со свойством PieSplitBy. Чтение/запись double.

**Возвращает:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Указывает значение, которое используется для определения, какие точки данных находятся во втором круге или столбце в диаграмме «пирог-в-пироге» или «бар-в-пироге». Используется совместно со свойством PieSplitBy. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Указывает, как определить, какие точки данных находятся во втором круге или столбце в диаграмме «пирог-в-пироге» или «бар-в-пироге». Чтение/запись [PieSplitType](../../com.aspose.slides/piesplittype).

**Возвращает:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Указывает, как определить, какие точки данных находятся во втором круге или столбце в диаграмме «пирог-в-пироге» или «бар-в-пироге». Чтение/запись [PieSplitType](../../com.aspose.slides/piesplittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Пользовательская информация о разбиении для диаграммы «пирог-в-пироге» или «бар-в-пироге» с пользовательским разбиением. Содержит точки данных, которые должны быть отрисованы во втором круге или столбце в диаграмме «пирог-в-пироге» или «бар-в-пироге». Только для чтения [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Возвращает:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Указывает размер отверстия в кольцевой диаграмме (может быть от 10 % до 90 % от размера области построения). Чтение/запись byte.

**Возвращает:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Указывает размер отверстия в кольцевой диаграмме (может быть от 10 % до 90 % от размера области построения). Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 % до 300 % от стандартного размера). Чтение/запись int.

**Возвращает:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 % до 300 % от стандартного размера). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Указывает формат HiLowLines. HiLowLines применяется в типах диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose.

**Возвращает:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Указывает, как значения размеров пузырей отображаются на пузырьковой диаграмме. Чтение/запись [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Возвращает:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Указывает, как значения размеров пузырей отображаются на пузырьковой диаграмме. Чтение/запись [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |