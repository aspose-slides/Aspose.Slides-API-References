---
title: IChartSeriesGroup
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет группу рядов.
type: docs
url: /ru/com.aspose.slides/ichartseriesgroup/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Представляет группу рядов.

--------------------

1) Смотрите сводку и замечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа рядов содержит некоторые свойства рядов, общие для каждого ряда в группе ("свойства группы рядов"). "Свойства группы рядов" в классе ChartSeriesGroup имеют режим чтения/записи. Каждое из "свойств группы рядов" может иметь только для чтения проекцию в классе ChartSeries.
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Возвращает тип этой группы рядов. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Указывает, построен ли ряд этой группы на вторичной оси. |
| [getSeries()](#getSeries--) | Возвращает только для чтения коллекцию рядов диаграммы. |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [getUpDownBars()](#getUpDownBars--) | Предоставляет доступ к полосам вверх/вниз линейной или сточной диаграммы. |
| [getGapWidth()](#getGapWidth--) | Задает пространство между кластерами столбцов или полос, в процентах от ширины столбца или полосы. |
| [setGapWidth(int value)](#setGapWidth-int-) | Задает пространство между кластерами столбцов или полос, в процентах от ширины столбца или полосы. |
| [getGapDepth()](#getGapDepth--) | Возвращает или задает расстояние, в процентах от ширины маркера, между рядами данных в 3D-диаграмме. |
| [setGapDepth(int value)](#setGapDepth-int-) | Возвращает или задает расстояние, в процентах от ширины маркера, между рядами данных в 3D-диаграмме. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от верха, от 0 до 360). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от верха, от 0 до 360). |
| [isColorVaried()](#isColorVaried--) | Указывает, что каждый маркер данных в ряду имеет различный цвет. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Указывает, что каждый маркер данных в ряду имеет различный цвет. |
| [hasSeriesLines()](#hasSeriesLines--) | Истина, если диаграмма имеет линии рядов. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Истина, если диаграмма имеет линии рядов. |
| [getOverlap()](#getOverlap--) | Указывает, насколько столбцы и полосы должны перекрываться на 2-D-диаграммах, в процентах (от -100 % до 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Указывает, насколько столбцы и полосы должны перекрываться на 2-D-диаграммах, в процентах (от -100 % до 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Задает размер второго сектора или полосы диаграммы «круг-в-круге» или «полоса-в-круге», в процентах от размера первого круга (может быть от 5 % до 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Задает размер второго сектора или полосы диаграммы «круг-в-круге» или «полоса-в-круге», в процентах от размера первого круга (может быть от 5 % до 200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Задает значение, которое используется для определения, какие точки данных находятся во втором секторе или полосе диаграммы «круг-в-круге» или «полоса-в-круге». |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Задает значение, которое используется для определения, какие точки данных находятся во втором секторе или полосе диаграммы «круг-в-круге» или «полоса-в-круге». |
| [getPieSplitBy()](#getPieSplitBy--) | Указывает, как определять, какие точки данных находятся во втором секторе или полосе диаграммы «круг-в-круге» или «полоса-в-круге». |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Указывает, как определять, какие точки данных находятся во втором секторе или полосе диаграммы «круг-в-круге» или «полоса-в-круге». |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Пользовательская информация о разбиении для диаграммы «круг-в-круге» или «полоса-в-круге» с пользовательским разбиением. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Указывает размер отверстия в кольцевой диаграмме (может быть от 10 % до 90 % от размера области построения). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Указывает размер отверстия в кольцевой диаграмме (может быть от 10 % до 90 % от размера области построения). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 % до 300 % от стандартного размера). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 % до 300 % от стандартного размера). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Задает формат HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Указывает, как представляются значения размеров пузырей на пузырьковой диаграмме. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Указывает, как представляются значения размеров пузырей на пузырьковой диаграмме. |

### getType() {#getType--}
```
public abstract int getType()
```

Возвращает тип этой группы рядов. Только для чтения [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Возвращаемое значение:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Указывает, построен ли ряд этой группы на вторичной оси. Только для чтения boolean.

**Возвращаемое значение:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Возвращает только для чтения коллекцию рядов диаграммы. Только для чтения [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Возвращаемое значение:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Возвращает элемент по указанному индексу.

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

Предоставляет доступ к полосам вверх/вниз линейной или сточной диаграммы. Только для чтения [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Возвращаемое значение:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Задает пространство между кластерами столбцов или полос, в процентах от ширины столбца или полосы. Чтение/запись int.

**Возвращаемое значение:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Задает пространство между кластерами столбцов или полос, в процентах от ширины столбца или полосы. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Возвращает или задает расстояние, в процентах от ширины маркера, между рядами данных в 3D-диаграмме. Чтение/запись int.

**Возвращаемое значение:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Возвращает или задает расстояние, в процентах от ширины маркера, между рядами данных в 3D-диаграмме. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от верха, от 0 до 360). Чтение/запись int.

**Возвращаемое значение:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от верха, от 0 до 360). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Указывает, что каждый маркер данных в ряду имеет различный цвет. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Указывает, что каждый маркер данных в ряду имеет различный цвет. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Истина, если диаграмма имеет линии рядов. Применяется к сложенным столбчатым и диаграммам OfPie. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Истина, если диаграмма имеет линии рядов. Применяется к сложенным столбчатым и диаграммам OfPie. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Указывает, насколько столбцы и полосы должны перекрываться на 2-D-диаграммах, в процентах (от -100 % до 100 %). - -100 %: Максимальное расстояние (столбцы полностью отделены). - 0 %: Столбцы размещаются бок о бок без перекрытия и без промежутка. - 100 %: Максимальное перекрытие (столбцы полностью накладываются друг на друга). Это свойство чтение/запись byte.

--------------------

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

Указывает, насколько столбцы и полосы должны перекрываться на 2-D-диаграммах, в процентах (от -100 % до 100 %). - -100 %: Максимальное расстояние (столбцы полностью отделены). - 0 %: Столбцы размещаются бок о бок без перекрытия и без промежутка. - 100 %: Максимальное перекрытие (столбцы полностью накладываются друг на друга). Это свойство чтение/запись byte.

--------------------

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

Задает размер второго сектора или полосы диаграммы «круг-в-круге» или «полоса-в-круге», в процентах от размера первого круга (может быть от 5 % до 200 %). Чтение/запись int.

**Возвращаемое значение:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Задает размер второго сектора или полосы диаграммы «круг-в-круге» или «полоса-в-круге», в процентах от размера первого круга (может быть от 5 % до 200 %). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Задает значение, которое используется для определения, какие точки данных находятся во втором секторе или полосе диаграммы «круг-в-круге» или «полоса-в-круге». Используется совместно со свойством PieSplitBy. Чтение/запись double.

**Возвращаемое значение:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Задает значение, которое используется для определения, какие точки данных находятся во втором секторе или полосе диаграммы «круг-в-круге» или «полоса-в-круге». Используется совместно со свойством PieSplitBy. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Указывает, как определять, какие точки данных находятся во втором секторе или полосе диаграммы «круг-в-круге» или «полоса-в-круге». Чтение/запись [PieSplitType](../../com.aspose.slides/piesplittype).

**Возвращаемое значение:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Указывает, как определять, какие точки данных находятся во втором секторе или полосе диаграммы «круг-в-круге» или «полоса-в-круге». Чтение/запись [PieSplitType](../../com.aspose.slides/piesplittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Пользовательская информация о разбиении для диаграммы «круг-в-круге» или «полоса-в-круге» с пользовательским разбиением. Содержит точки данных, которые должны быть отрисованы во втором секторе или полосе. Только для чтения [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Возвращаемое значение:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Задает размер отверстия в кольцевой диаграмме (может быть от 10 % до 90 % от размера области построения). Чтение/запись byte.

**Возвращаемое значение:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Задает размер отверстия в кольцевой диаграмме (может быть от 10 % до 90 % от размера области построения). Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Задает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 % до 300 % от стандартного размера). Чтение/запись int.

**Возвращаемое значение:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Задает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 % до 300 % от стандартного размера). Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Задает формат HiLowLines. HiLowLines применяется к типам диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose.

**Возвращаемое значение:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Указывает, как представляются значения размеров пузырей на пузырьковой диаграмме. Чтение/запись [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Возвращаемое значение:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Указывает, как представляются значения размеров пузырей на пузырьковой диаграмме. Чтение/запись [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |