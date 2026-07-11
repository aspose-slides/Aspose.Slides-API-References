---
title: Chart
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет графическую диаграмму на слайде.
type: docs
url: /ru/com.aspose.slides/chart/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Представляет графическую диаграмму на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Вычисляет фактические значения элементов диаграммы. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Определяет, отображаются ли только видимые ячейки. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Определяет, отображаются ли только видимые ячейки. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Возвращает или задает способ отображения пустых ячеек на диаграмме. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Возвращает или задает способ отображения пустых ячеек на диаграмме. |
| [getChartData()](#getChartData--) | Возвращает информацию о связанном или встроенном наборе данных, связанном с диаграммой. |
| [hasTitle()](#hasTitle--) | Определяет, имеет ли диаграмма видимый заголовок. |
| [setTitle(boolean value)](#setTitle-boolean-) | Определяет, имеет ли диаграмма видимый заголовок. |
| [getChartTitle()](#getChartTitle--) | Возвращает или задает заголовок диаграммы. |
| [hasDataTable()](#hasDataTable--) | Определяет, имеет ли диаграмма таблицу данных. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Определяет, имеет ли диаграмма таблицу данных. |
| [hasLegend()](#hasLegend--) | Определяет, имеет ли диаграмма легенду. |
| [setLegend(boolean value)](#setLegend-boolean-) | Определяет, имеет ли диаграмма легенду. |
| [getLegend()](#getLegend--) | Возвращает или задает легенду для диаграммы. |
| [getChartDataTable()](#getChartDataTable--) | Возвращает таблицу данных диаграммы. |
| [getStyle()](#getStyle--) | Возвращает или задает стиль диаграммы. |
| [setStyle(int value)](#setStyle-int-) | Возвращает или задает стиль диаграммы. |
| [getType()](#getType--) | Возвращает или задает тип диаграммы. |
| [setType(int value)](#setType-int-) | Возвращает или задает тип диаграммы. |
| [getPlotArea()](#getPlotArea--) | Представляет область построения диаграммы. |
| [getRotation3D()](#getRotation3D--) | Возвращает 3D-поворот диаграммы. |
| [getBackWall()](#getBackWall--) | Возвращает объект, позволяющий изменять формат задней стенки 3D-диаграммы. |
| [getSideWall()](#getSideWall--) | Возвращает объект, позволяющий изменять формат боковой стенки 3D-диаграммы. |
| [getFloor()](#getFloor--) | Возвращает объект, позволяющий изменять формат пола 3D-диаграммы. |
| [getTextFormat()](#getTextFormat--) | Возвращает формат текста диаграммы. |
| [createThemeEffective()](#createThemeEffective--) | Возвращает эффективную тему для этой диаграммы. |
| [getThemeManager()](#getThemeManager--) | Возвращает менеджер тем. |
| [getUserShapes()](#getUserShapes--) | Указывайте фигуры, рисуемые поверх диаграммы. |
| [getAxes()](#getAxes--) | Обеспечивает доступ к осям диаграммы. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Указывает, что подписи данных выше максимума диаграммы должны отображаться. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Указывает, что подписи данных выше максимума диаграммы должны отображаться. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Указывает, что область диаграммы должна иметь скруглённые углы. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Указывает, что область диаграммы должна иметь скруглённые углы. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Вычисляет фактические значения элементов диаграммы. Фактические значения включают положение элементов, реализующих интерфейс IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight), и фактические значения осей (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Определяет, отображаются ли только видимые ячейки. False, чтобы отображать как видимые, так и скрытые ячейки. **Чтение/запись** boolean.

**Возвращает:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Определяет, отображаются ли только видимые ячейки. False, чтобы отображать как видимые, так и скрытые ячейки. **Чтение/запись** boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Возвращает или задает способ отображения пустых ячеек на диаграмме. **Чтение/запись** [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Возвращает:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Возвращает или задает способ отображения пустых ячеек на диаграмме. **Чтение/запись** [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Возвращает информацию о связанном или встроенном наборе данных, связанном с диаграммой. **Только для чтения** [IChartData](../../com.aspose.slides/ichartdata).

**Возвращает:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Определяет, имеет ли диаграмма видимый заголовок. **Чтение/запись** boolean.

**Возвращает:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Определяет, имеет ли диаграмма видимый заголовок. **Чтение/запись** boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Возвращает или задает заголовок диаграммы. **Только для чтения** [IChartTitle](../../com.aspose.slides/icharttitle).

**Возвращает:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Определяет, имеет ли диаграмма таблицу данных. **Чтение/запись** boolean.

**Возвращает:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Определяет, имеет ли диаграмма таблицу данных. **Чтение/запись** boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Определяет, имеет ли диаграмма легенду. **Чтение/запись** boolean.

**Возвращает:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Определяет, имеет ли диаграмма легенду. **Чтение/запись** boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Возвращает или задает легенду для диаграммы. **Только для чтения** [ILegend](../../com.aspose.slides/ilegend).

**Возвращает:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Возвращает таблицу данных диаграммы. **Только для чтения** [IDataTable](../../com.aspose.slides/idatatable).

**Возвращает:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public final int getStyle()
```

Возвращает или задает стиль диаграммы. **Чтение/запись** [StyleType](../../com.aspose.slides/styletype).

**Возвращает:**
int

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Возвращает или задает стиль диаграммы. **Чтение/запись** [StyleType](../../com.aspose.slides/styletype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Возвращает или задает тип диаграммы. **Чтение/запись** [ChartType](../../com.aspose.slides/charttype).

**Возвращает:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Возвращает или задает тип диаграммы. **Чтение/запись** [ChartType](../../com.aspose.slides/charttype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Представляет область построения диаграммы. **Только для чтения** [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Возвращает:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Возвращает 3D-поворот диаграммы. **Только для чтения** [IRotation3D](../../com.aspose.slides/irotation3d).

**Возвращает:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Возвращает объект, позволяющий изменять формат задней стенки 3D-диаграммы. **Только для чтения** [IChartWall](../../com.aspose.slides/ichartwall).

**Возвращает:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Возвращает объект, позволяющий изменять формат боковой стенки 3D-диаграммы. **Только для чтения** [IChartWall](../../com.aspose.slides/ichartwall).

**Возвращает:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Возвращает объект, позволяющий изменять формат пола 3D-диаграммы. **Только для чтения** [IChartWall](../../com.aspose.slides/ichartwall).

**Возвращает:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Возвращает формат текста диаграммы. Свойство не применимо к следующим типам: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). **Только для чтения** [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Возвращает:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Возвращает эффективную тему для этой диаграммы.

**Возвращает:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Возвращает менеджер тем. **Только для чтения** [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Возвращает:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Указывайте фигуры, рисуемые поверх диаграммы. **Только для чтения** [IGroupShape](../../com.aspose.slides/igroupshape).

**Возвращает:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Обеспечивает доступ к осям диаграммы. **Только для чтения** [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Возвращает:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Указывает, что подписи данных выше максимума диаграммы должны отображаться. **Чтение/запись** boolean.

**Возвращает:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Указывает, что подписи данных выше максимума диаграммы должны отображаться. **Чтение/запись** boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Указывает, что область диаграммы должна иметь скруглённые углы. **Чтение/запись** boolean.

**Возвращает:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Указывает, что область диаграммы должна иметь скруглённые углы. **Чтение/запись** boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Возвращает диаграмму. **Только для чтения** [IChart](../../com.aspose.slides/ichart).

**Возвращает:**
[IChart](../../com.aspose.slides/ichart)