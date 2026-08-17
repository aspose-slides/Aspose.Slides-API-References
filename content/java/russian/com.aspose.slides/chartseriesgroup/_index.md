---
title: ChartSeriesGroup
second_title: Справочная документация API Aspose.Slides для Java
description: Представляет группу серий.
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

Представляет группу серий.

--------------------

1) См. резюме и замечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе ("свойства группы серий"). "Свойства группы серий" в классе ChartSeriesGroup доступны для чтения/записи. У каждого из "свойств группы серий" может быть только читаемая проекция в классе ChartSeries.
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Возвращает тип этой группы серий. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Указывает, построена ли серия этой группы по вторичной оси. |
| [getSeries()](#getSeries--) | Возвращает коллекцию серий. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [getUpDownBars()](#getUpDownBars--) | Обеспечивает доступ к верхним/нижним столбцам графика Line или Stock. |
| [getGapWidth()](#getGapWidth--) | Задает расстояние между кластерами столбцов или колонок в процентах от ширины столбца или колонки. |
| [setGapWidth(int value)](#setGapWidth-int-) | Задает расстояние между кластерами столбцов или колонок в процентах от ширины столбца или колонки. |
| [getGapDepth()](#getGapDepth--) | Возвращает или задает расстояние в процентах от ширины маркера между сериями данных в 3D-диаграмме. |
| [setGapDepth(int value)](#setGapDepth-int-) | Возвращает или задает расстояние в процентах от ширины маркера между сериями данных в 3D-диаграмме. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Получает или задает угол первого сегмента пироговой или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Получает или задает угол первого сегмента пироговой или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Задает размер отверстия в кольцевой диаграмме (может быть от 0 % до 90 % от размера области построения). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Задает размер отверстия в кольцевой диаграмме (может быть от 0 % до 90 % от размера области построения). |
| [getOverlap()](#getOverlap--) | Задает, насколько столбцы и колонки перекрываются в 2-D диаграммах, в процентах (от -100 % до 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Задает, насколько столбцы и колонки перекрываются в 2-D диаграммах, в процентах (от -100 % до 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Задает размер второго пирога или столбца диаграммы «пирог-в-пироге»/«столбец-в-пироге» в процентах от размера первого пирога (от 5 % до 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Задает размер второго пирога или столбца диаграммы «пирог-в-пироге»/«столбец-в-пироге» в процентах от размера первого пирога (от 5 % до 200 %). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Задает, как значения размера пузырьков представляются в пузырьковой диаграмме. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Задает, как значения размера пузырьков представляются в пузырьковой диаграмме. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Задает значение, используемое для определения, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-в-пироге»/«столбец-в-пироге». |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Задает значение, используемое для определения, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-в-пироге»/«столбец-в-пироге». |
| [getPieSplitBy()](#getPieSplitBy--) | Задает способ определения, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-в-пироге»/«столбец-в-пироге». |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Задает способ определения, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-в-пироге»/«столбец-в-пироге». |
| [isColorVaried()](#isColorVaried--) | Задает, чтобы каждый маркер данных в серии имел разный цвет. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Задает, чтобы каждый маркер данных в серии имел разный цвет. |
| [hasSeriesLines()](#hasSeriesLines--) | Истина, если у диаграммы есть линии серии. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Истина, если у диаграммы есть линии серии. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Задает формат HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Задает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 % до 300 % от размера по умолчанию). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Задает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 % до 300 % от размера по умолчанию). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Пользовательская информация о разбиении для диаграммы «пирог-в-пироге»/«столбец-в-пироге» с пользовательским разбиением. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Возвращает родительскую диаграмму. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд объекта FillFormat. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию объекта FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Возвращает тип этой группы серий. Только для чтения [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Возвращаемое значение:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Указывает, построена ли серия этой группы по вторичной оси. Только для чтения boolean.

**Возвращаемое значение:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Возвращает коллекцию серий. Только для чтения [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Возвращаемое значение:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Получает элемент по указанному индексу.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Обеспечивает доступ к верхним/нижним столбцам графика Line или Stock. Только для чтения [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Возвращаемое значение:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Задает расстояние между кластерами столбцов или колонок в процентах от ширины столбца или колонки. Чтение/запись int.

**Возвращаемое значение:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Задает расстояние между кластерами столбцов или колонок в процентах от ширины столбца или колонки. Чтение/запись int.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Возвращает или задает расстояние в процентах от ширины маркера между сериями данных в 3D-диаграмме. Чтение/запись int.

**Возвращаемое значение:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Возвращает или задает расстояние в процентах от ширины маркера между сериями данных в 3D-диаграмме. Чтение/запись int.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Получает или задает угол первого сегмента пироговой или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). Чтение/запись int.

**Возвращаемое значение:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Получает или задает угол первого сегмента пироговой или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). Чтение/запись int.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Задает размер отверстия в кольцевой диаграмме (может быть от 0 % до 90 % от размера области построения). Чтение/запись byte.

**Возвращаемое значение:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Задает размер отверстия в кольцевой диаграмме (может быть от 0 % до 90 % от размера области построения). Чтение/запись byte.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Задает, насколько столбцы и колонки перекрываются в 2-D диаграммах, в процентах (от -100 % до 100 %). - -100 %: максимальное расстояние (столбцы полностью разделены). - 0 %: столбцы размещены рядом без перекрытия и без промежутков. - 100 %: максимальное перекрытие (столбцы полностью накладываются друг на друга). Это свойство — чтение/запись byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Установить перекрытие до 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Задает, насколько столбцы и колонки перекрываются в 2-D диаграммах, в процентах (от -100 % до 100 %). - -100 %: максимальное расстояние (столбцы полностью разделены). - 0 %: столбцы размещены рядом без перекрытия и без промежутков. - 100 %: максимальное перекрытие (столбцы полностью накладываются друг на друга). Это свойство — чтение/запись byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Установить перекрытие до 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Задает размер второго пирога или столбца диаграммы «пирог-в-пироге»/«столбец-в-пироге» в процентах от размера первого пирога (от 5 % до 200 %). Чтение/запись int.

**Возвращаемое значение:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Задает размер второго пирога или столбца диаграммы «пирог-в-пироге»/«столбец-в-пироге» в процентах от размера первого пирога (от 5 % до 200 %). Чтение/запись int.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Задает, как значения размера пузырьков представляются в пузырьковой диаграмме. Чтение/запись [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Возвращаемое значение:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Задает, как значения размера пузырьков представляются в пузырьковой диаграмме. Чтение/запись [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Задает значение, используемое для определения, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-в-пироге»/«столбец-в-пироге». Используется вместе с свойством PieSplitBy. Чтение/запись double.

**Возвращаемое значение:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Задает значение, используемое для определения, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-в-пироге»/«столбец-в-пироге». Используется вместе с свойством PieSplitBy. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Задает способ определения, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-в-пироге»/«столбец-в-пироге». Чтение/запись [PieSplitType](../../com.aspose.slides/piesplittype).

**Возвращаемое значение:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Задает способ определения, какие точки данных находятся во втором пироге или столбце диаграммы «пирог-в-пироге»/«столбец-в-пироге». Чтение/запись [PieSplitType](../../com.aspose.slides/piesplittype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Задает, чтобы каждый маркер данных в серии имел разный цвет. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Задает, чтобы каждый маркер данных в серии имел разный цвет. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Истина, если у диаграммы есть линии серии. Применяется к сложенным столбчатым и диаграммам OfPie. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Истина, если у диаграммы есть линии серии. Применяется к сложенным столбчатым и диаграммам OfPie. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Задает формат HiLowLines. HiLowLines применяется к типам диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose.

**Возвращаемое значение:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Задает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 % до 300 % от размера по умолчанию). Чтение/запись int.

**Возвращаемое значение:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Задает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 % до 300 % от размера по умолчанию). Чтение/запись int.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Пользовательская информация о разбиении для диаграммы «пирог-в-пироге»/«столбец-в-пироге» с пользовательским разбиением. Содержит точки данных, которые должны быть нарисованы во втором пироге или столбце. Только для чтения [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Возвращаемое значение:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Возвращает родительскую диаграмму. Только для чтения [IChart](../../com.aspose.slides/ichart).

**Возвращаемое значение:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд объекта FillFormat. Только для чтения [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращаемое значение:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию объекта FillFormat. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)