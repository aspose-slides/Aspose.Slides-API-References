---
title: ChartSeriesGroup
second_title: Aspose.Slides для Java справочник API
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

1) См. сводку и примечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе ("свойства группы серий"). "Свойства группы серий" в классе ChartSeriesGroup являются чтение/запись. Каждый из "свойств группы серий" может иметь только для чтения проекцию в классе ChartSeries.
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Возвращает тип этой группы серий. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Указывает, построена ли серия этой группы по вторичной оси. |
| [getSeries()](#getSeries--) | Возвращает коллекцию серий. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [getUpDownBars()](#getUpDownBars--) | Обеспечивает доступ к полосам вверх/вниз диаграммы Line или Stock. |
| [getGapWidth()](#getGapWidth--) | Получает или задает расстояние между кластерами столбцов или колонок в процентах от ширины столбца или колонки. |
| [setGapWidth(int value)](#setGapWidth-int-) | Получает или задает расстояние между кластерами столбцов или колонок в процентах от ширины столбца или колонки. |
| [getGapDepth()](#getGapDepth--) | Получает или задает расстояние между данными сериями в 3D-диаграмме в процентах от ширины маркера. |
| [setGapDepth(int value)](#setGapDepth-int-) | Получает или задает расстояние между данными сериями в 3D-диаграмме в процентах от ширины маркера. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Указывает размер отверстия в кольцевой диаграмме (может быть от 0 до 90 процентов от размера области построения). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Указывает размер отверстия в кольцевой диаграмме (может быть от 0 до 90 процентов от размера области построения). |
| [getOverlap()](#getOverlap--) | Указывает, насколько столбцы и колонки должны перекрываться на 2-D диаграммах, в процентах (от -100% до 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Указывает, насколько столбцы и колонки должны перекрываться на 2-D диаграммах, в процентах (от -100% до 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Указывает размер второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie в процентах от размера первой части (может быть от 5 до 200 процентов). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Указывает размер второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie в процентах от размера первой части (может быть от 5 до 200 процентов). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Указывает, как значения размеров пузырьков отображаются на пузырьковой диаграмме. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Указывает, как значения размеров пузырьков отображаются на пузырьковой диаграмме. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Указывает значение, используемое для определения, какие точки данных находятся во второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Указывает значение, используемое для определения, какие точки данных находятся во второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Указывает, как определить, какие точки данных находятся во второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Указывает, как определить, какие точки данных находятся во второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie. |
| [isColorVaried()](#isColorVaried--) | Указывает, что каждый маркер данных в серии имеет разный цвет. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Указывает, что каждый маркер данных в серии имеет разный цвет. |
| [hasSeriesLines()](#hasSeriesLines--) | True, если диаграмма имеет линии серии. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True, если диаграмма имеет линии серии. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Указывает формат HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Информация о пользовательском разделении для диаграммы типа pie-of-pie или bar-of-pie с пользовательским разделением. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Возвращает родительскую диаграмму. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд объекта FillFormat. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию объекта FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Возвращает тип этой группы серий. Только для чтения [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Возвращает:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Указывает, построена ли серия этой группы по вторичной оси. Только для чтения boolean.

**Возвращает:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Возвращает коллекцию серий. Только для чтения [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Возвращает:**
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

**Возвращает:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Обеспечивает доступ к полосам вверх/вниз диаграммы Line или Stock. Только для чтения [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Возвращает:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Получает или задает расстояние между кластерами столбцов или колонок в процентах от ширины столбца или колонки. Значение должно быть от 0 до 500. Чтение/запись int.

--------------------

Это свойство применяется к сериям следующих типов: подтипы Bar (см. также метод [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), подтипы Column (см. также метод [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Возвращает:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Получает или задает расстояние между кластерами столбцов или колонок в процентах от ширины столбца или колонки. Значение должно быть от 0 до 500. Чтение/запись int.

--------------------

Это свойство применяется к сериям следующих типов: подтипы Bar (см. также метод [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), подтипы Column (см. также метод [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Получает или задает расстояние между данными сериями в 3D-диаграмме в процентах от ширины маркера. Значение должно быть от 0 до 500. Чтение/запись int.

--------------------

Это свойство применяется к сериям следующих типов: 3D-подтипы Bar и Column (см. также метод [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Возвращает:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Получает или задает расстояние между данными сериями в 3D-диаграмме в процентах от ширины маркера. Значение должно быть от 0 до 500. Чтение/запись int.

--------------------

Это свойство применяется к сериям следующих типов: 3D-подтипы Bar и Column (см. также метод [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). Чтение/запись int.

**Возвращает:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). Чтение/запись int.

**Параметры:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Указывает, насколько столбцы и колонки должны перекрываться на 2-D диаграммах, в процентах (от -100% до 100%). - -100%: максимальное разнесение (столбцы полностью разъединены). - 0%: столбцы расположены рядом без перекрытия и разрыва. - 100%: максимальное перекрытие (столбцы полностью накладываются друг на друга). Это свойство является чтение/запись byte.

--------------------

> ```
> Следующий пример демонстрирует, как установить перекрытие для группы серий диаграммы 
>   и отобразить получившуюся диаграмму в форме:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Установить перекрытие в 55%
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

Указывает, насколько столбцы и колонки должны перекрываться на 2-D диаграммах, в процентах (от -100% до 100%). - -100%: максимальное разнесение (столбцы полностью разъединены). - 0%: столбцы расположены рядом без перекрытия и разрыва. - 100%: максимальное перекрытие (столбцы полностью накладываются друг на друга). Это свойство является чтение/запись byte.

--------------------

> ```
> Следующий пример демонстрирует, как установить перекрытие для группы серий диаграммы 
>   и отобразить получившуюся диаграмму в форме:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Установить перекрытие в 55%
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

Указывает размер второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie в процентах от размера первой части (может быть от 5 до 200 процентов). Чтение/запись int.

**Возвращает:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Указывает размер второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie в процентах от размера первой части (может быть от 5 до 200 процентов). Чтение/запись int.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Указывает, как значения размеров пузырьков отображаются на пузырьковой диаграмме. Чтение/запись [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Возвращает:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Указывает, как значения размеров пузырьков отображаются на пузырьковой диаграмме. Чтение/запись [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Указывает значение, используемое для определения, какие точки данных находятся во второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie. Используется совместно со свойством PieSplitBy. Чтение/запись double.

**Возвращает:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Указывает значение, используемое для определения, какие точки данных находятся во второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie. Используется совместно со свойством PieSplitBy. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Указывает, как определить, какие точки данных находятся во второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie. Чтение/запись [PieSplitType](../../com.aspose.slides/piesplittype).

**Возвращает:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Указывает, как определить, какие точки данных находятся во второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie. Чтение/запись [PieSplitType](../../com.aspose.slides/piesplittype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Указывает, что каждый маркер данных в серии имеет разный цвет. Чтение/запись boolean.

**Возвращает:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Указывает, что каждый маркер данных в серии имеет разный цвет. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Указывает формат HiLowLines. HiLowLines применяется к типам диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Информация о пользовательском разделении для диаграммы типа pie-of-pie или bar-of-pie с пользовательским разделением. Содержит точки данных, которые должны быть нарисованы во второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie. Только для чтения [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

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