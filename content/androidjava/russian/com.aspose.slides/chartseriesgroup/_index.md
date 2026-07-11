---
title: ChartSeriesGroup
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет группу рядов.
type: docs
url: /ru/com.aspose.slides/chartseriesgroup/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Представляет группу рядов.

--------------------

1) См. сводку и замечания к классу ChartSeriesGroupCollection и перечислению CombinableSeriesTypesGroup. 2) Группа рядов содержит некоторые свойства рядов, общие для каждого ряда в группе («свойства группы рядов»). «Свойства группы рядов» в классе ChartSeriesGroup доступны для чтения/записи. Каждый из «свойств группы рядов» может иметь только для чтения проекцию в классе ChartSeries.

## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Возвращает тип этой группы рядов. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Указывает, построены ли ряды этой группы на вторичной оси. |
| [getSeries()](#getSeries--) | Возвращает коллекцию рядов. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [getUpDownBars()](#getUpDownBars--) | Предоставляет доступ к верхним/нижним полосам линейной или биржевой диаграммы. |
| [getGapWidth()](#getGapWidth--) | Указывает пространство между кластерами столбцов или колонок в процентах от их ширины. |
| [setGapWidth(int value)](#setGapWidth-int-) | Указывает пространство между кластерами столбцов или колонок в процентах от их ширины. |
| [getGapDepth()](#getGapDepth--) | Возвращает или задает расстояние, в процентах от ширины маркера, между рядами данных в 3D-диаграмме. |
| [setGapDepth(int value)](#setGapDepth-int-) | Возвращает или задает расстояние, в процентах от ширины маркера, между рядами данных в 3D-диаграмме. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от верхней позиции, от 0 до 360 градусов). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от верхней позиции, от 0 до 360 градусов). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Указывает размер отверстия в кольцевой диаграмме (может быть от 0 до 90 процентов от размера области построения). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Указывает размер отверстия в кольцевой диаграмме (может быть от 0 до 90 процентов от размера области построения). |
| [getOverlap()](#getOverlap--) | Указывает степень перекрытия столбцов и колонок на 2-D диаграммах в процентах (от -100% до 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Указывает степень перекрытия столбцов и колонок на 2-D диаграммах в процентах (от -100% до 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Указывает размер второго круга или столбца в диаграмме pie-of-pie или bar-of-pie в процентах от размера первого круга (может быть от 5 до 200 процентов). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Указывает размер второго круга или столбца в диаграмме pie-of-pie или bar-of-pie в процентах от размера первого круга (может быть от 5 до 200 процентов). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Указывает, как значения размеров пузырей представлены на пузырьковой диаграмме. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Указывает, как значения размеров пузырей представлены на пузырьковой диаграмме. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором круге или столбце диаграммы pie-of-pie или bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором круге или столбце диаграммы pie-of-pie или bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Указывает, как определять, какие точки данных находятся во втором круге или столбце диаграммы pie-of-pie или bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Указывает, как определять, какие точки данных находятся во втором круге или столбце диаграммы pie-of-pie или bar-of-pie. |
| [isColorVaried()](#isColorVaried--) | Указывает, что каждый маркер данных в ряду имеет разный цвет. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Указывает, что каждый маркер данных в ряду имеет разный цвет. |
| [hasSeriesLines()](#hasSeriesLines--) | True, если диаграмма имеет линии серии. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True, если диаграмма имеет линии серии. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Указывает формат HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Информация о пользовательском разбиении для диаграммы pie-of-pie или bar-of-pie с пользовательским разбиением. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Возвращает родительскую диаграмму. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд объекта FillFormat. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию объекта FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Возвращает тип этой группы рядов. Только для чтения [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Возвращает:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Указывает, построены ли ряды этой группы на вторичной оси. Только для чтения boolean.

**Возвращает:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Возвращает коллекцию рядов. Только для чтения [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Возвращает:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
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
public final IUpDownBarsManager getUpDownBars()
```

Предоставляет доступ к верхним/нижним полосам линейной или биржевой диаграммы. Только для чтения [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Возвращает:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Указывает пространство между кластерами столбцов или колонок в процентах от их ширины. Чтение/запись int.

**Возвращает:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Указывает пространство между кластерами столбцов или колонок в процентах от их ширины. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Возвращает или задает расстояние, в процентах от ширины маркера, между рядами данных в 3D-диаграмме. Чтение/запись int.

**Возвращает:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Возвращает или задает расстояние, в процентах от ширины маркера, между рядами данных в 3D-диаграмме. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от верхней позиции, от 0 до 360 градусов). Чтение/запись int.

**Возвращает:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от верхней позиции, от 0 до 360 градусов). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Указывает размер отверстия в кольцевой диаграмме (может быть от 0 до 90 процентов от размера области построения). Чтение/запись byte.

**Возвращает:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Указывает размер отверстия в кольцевой диаграмме (может быть от 0 до 90 процентов от размера области построения). Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Указывает степень перекрытия столбцов и колонок на 2-D диаграммах в процентах (от -100% до 100%). -100%: максимальное разстояние (столбцы полностью разъединены). 0%: столбцы размещаются рядом без перекрытия и без промежутков. 100%: максимальное перекрытие (столбцы полностью накладываются друг на друга). Это свойство Чтение/запись byte.

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


**Возвращает:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Указывает степень перекрытия столбцов и колонок на 2-D диаграммах в процентах (от -100% до 100%). -100%: максимальное разстояние (столбцы полностью разъединены). 0%: столбцы размещаются рядом без перекрытия и без промежутков. 100%: максимальное перекрытие (столбцы полностью накладываются друг на друга). Это свойство Чтение/запись byte.

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
public final int getSecondPieSize()
```

Указывает размер второго круга или столбца в диаграмме pie-of-pie или bar-of-pie в процентах от размера первого круга (может быть от 5 до 200 процентов). Чтение/запись int.

**Возвращает:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Указывает размер второго круга или столбца в диаграмме pie-of-pie или bar-of-pie в процентах от размера первого круга (может быть от 5 до 200 процентов). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Указывает, как значения размеров пузырей представлены на пузырьковой диаграмме. Чтение/запись [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Возвращает:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Указывает, как значения размеров пузырей представлены на пузырьковой диаграмме. Чтение/запись [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором круге или столбце диаграммы pie-of-pie или bar-of-pie. Используется совместно с свойством PieSplitBy. Чтение/запись double.

**Возвращает:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором круге или столбце диаграммы pie-of-pie или bar-of-pie. Используется совместно с свойством PieSplitBy. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Указывает, как определять, какие точки данных находятся во втором круге или столбце диаграммы pie-of-pie или bar-of-pie. Чтение/запись [PieSplitType](../../com.aspose.slides/piesplittype).

**Возвращает:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Указывает, как определять, какие точки данных находятся во втором круге или столбце диаграммы pie-of-pie или bar-of-pie. Чтение/запись [PieSplitType](../../com.aspose.slides/piesplittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Указывает, что каждый маркер данных в ряду имеет разный цвет. Чтение/запись boolean.

**Возвращает:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Указывает, что каждый маркер данных в ряду имеет разный цвет. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

True, если диаграмма имеет линии серии. Применяется к stacked bar и OfPie диаграммам. Чтение/запись boolean.

**Возвращает:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

True, если диаграмма имеет линии серии. Применяется к stacked bar и OfPie диаграммам. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Указывает формат HiLowLines. HiLowLines применяется с типами диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose.

**Возвращает:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). Чтение/запись int.

**Возвращает:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Информация о пользовательском разбиении для диаграммы pie-of-pie или bar-of-pie с пользовательским разбиением. Содержит точки данных, которые должны быть отрисованы во втором круге или столбце. Только для чтения [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Возвращает:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Возвращает родительскую диаграмму. Только для чтения [IChart](../../com.aspose.slides/ichart).

**Возвращает:**
[IChart](../../com.aspose.slides/ichart)

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