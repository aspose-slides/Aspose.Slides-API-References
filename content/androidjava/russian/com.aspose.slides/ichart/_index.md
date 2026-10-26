---
title: IChart
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет графическую диаграмму на слайде.
type: docs
url: /ru/com.aspose.slides/ichart/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Представляет графическую диаграмму на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Определяет, отображаются ли только видимые ячейки. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Определяет, отображаются ли только видимые ячейки. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Возвращает или задает способ отображения пустых ячеек на диаграмме. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Возвращает или задает способ отображения пустых ячеек на диаграмме. |
| [getChartData()](#getChartData--) | Возвращает информацию о связанных или встроенных данных, связанных с диаграммой. |
| [hasTitle()](#hasTitle--) | Определяет, имеет ли диаграмма видимый заголовок. |
| [setTitle(boolean value)](#setTitle-boolean-) | Определяет, имеет ли диаграмма видимый заголовок. |
| [getChartTitle()](#getChartTitle--) | Возвращает или задает заголовок диаграммы. Только для чтения [IChartTitle](../../com.aspose.slides/icharttitle). |
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
| [getRotation3D()](#getRotation3D--) | Возвращает 3D-вращение диаграммы. |
| [getBackWall()](#getBackWall--) | Возвращает объект, позволяющий изменять формат задней стенки 3D-диаграммы. |
| [getSideWall()](#getSideWall--) | Возвращает объект, позволяющий изменять формат боковой стенки 3D-диаграммы. |
| [getFloor()](#getFloor--) | Возвращает объект, позволяющий изменять формат пола 3D-диаграммы. |
| [getUserShapes()](#getUserShapes--) | Указывает формы, нарисованные поверх диаграммы. |
| [getAxes()](#getAxes--) | Обеспечивает доступ к осям диаграммы. |
| [validateChartLayout()](#validateChartLayout--) | Вычисляет фактические значения элементов диаграммы. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Указывает, что подписи данных выше максимума диаграммы должны отображаться. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Указывает, что подписи данных выше максимума диаграммы должны отображаться. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Указывает, что область диаграммы должна иметь скругленные углы. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Указывает, что область диаграммы должна иметь скругленные углы. |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Определяет, отображаются ли только видимые ячейки. False — отображать как видимые, так и скрытые ячейки. Чтение/запись boolean.

**Возвращает:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Определяет, отображаются ли только видимые ячейки. False — отображать как видимые, так и скрытые ячейки. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Возвращает или задает способ отображения пустых ячеек на диаграмме. Чтение/запись [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Возвращает:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Возвращает или задает способ отображения пустых ячеек на диаграмме. Чтение/запись [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Возвращает информацию о связанных или встроенных данных, связанных с диаграммой. Только для чтения [IChartData](../../com.aspose.slides/ichartdata).

**Возвращает:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Определяет, имеет ли диаграмма видимый заголовок. Чтение/запись boolean.

**Возвращает:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Определяет, имеет ли диаграмма видимый заголовок. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Возвращает или задает заголовок диаграммы. Только для чтения [IChartTitle](../../com.aspose.slides/icharttitle).

**Возвращает:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Определяет, имеет ли диаграмма таблицу данных. Чтение/запись boolean.

**Возвращает:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Определяет, имеет ли диаграмма таблицу данных. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Определяет, имеет ли диаграмма легенду. Чтение/запись boolean.

**Возвращает:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Определяет, имеет ли диаграмма легенду. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Возвращает или задает легенду для диаграммы. Только для чтения [ILegend](../../com.aspose.slides/ilegend).

**Возвращает:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Возвращает таблицу данных диаграммы. Только для чтения [IDataTable](../../com.aspose.slides/idatatable).

**Возвращает:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Возвращает или задает стиль диаграммы. Чтение/запись [StyleType](../../com.aspose.slides/styletype).

**Возвращает:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Возвращает или задает стиль диаграммы. Чтение/запись [StyleType](../../com.aspose.slides/styletype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

Возвращает или задает тип диаграммы. Чтение/запись [ChartType](../../com.aspose.slides/charttype).

**Возвращает:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Возвращает или задает тип диаграммы. Чтение/запись [ChartType](../../com.aspose.slides/charttype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Представляет область построения диаграммы. Только для чтения [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Возвращает:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Возвращает 3D-вращение диаграммы. Только для чтения [IRotation3D](../../com.aspose.slides/irotation3d).

**Возвращает:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Возвращает объект, позволяющий изменять формат задней стенки 3D-диаграммы. Только для чтения [IChartWall](../../com.aspose.slides/ichartwall).

**Возвращает:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Возвращает объект, позволяющий изменять формат боковой стенки 3D-диаграммы. Только для чтения [IChartWall](../../com.aspose.slides/ichartwall).

**Возвращает:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Возвращает объект, позволяющий изменять формат пола 3D-диаграммы. Только для чтения [IChartWall](../../com.aspose.slides/ichartwall).

**Возвращает:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Указывает формы, нарисованные поверх диаграммы. Только для чтения [IGroupShape](../../com.aspose.slides/igroupshape).

**Возвращает:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Обеспечивает доступ к осям диаграммы. Только для чтения [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Возвращает:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Вычисляет фактические значения элементов диаграммы. Фактические значения включают позицию элементов, реализующих интерфейс IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) и фактические значения осей (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Указывает, что подписи данных выше максимума диаграммы должны отображаться. Чтение/запись boolean.

**Возвращает:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Указывает, что подписи данных выше максимума диаграммы должны отображаться. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Указывает, что область диаграммы должна иметь скругленные углы. Чтение/запись boolean.

**Возвращает:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Указывает, что область диаграммы должна иметь скругленные углы. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |