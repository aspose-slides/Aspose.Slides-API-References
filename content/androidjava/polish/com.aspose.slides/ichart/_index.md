---
title: IChart
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje graficzny wykres na slajdzie.
type: docs
url: /pl/com.aspose.slides/ichart/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Reprezentuje graficzny wykres na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Określa, czy jedynie widoczne komórki są wykreślane. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Określa, czy jedynie widoczne komórki są wykreślane. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Zwraca lub ustawia sposób wykreślania pustych komórek na wykresie. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Zwraca lub ustawia sposób wykreślania pustych komórek na wykresie. |
| [getChartData()](#getChartData--) | Zwraca informacje o powiązanych lub osadzonych danych związanych z wykresem. |
| [hasTitle()](#hasTitle--) | Określa, czy wykres ma widoczny tytuł. |
| [setTitle(boolean value)](#setTitle-boolean-) | Określa, czy wykres ma widoczny tytuł. |
| [getChartTitle()](#getChartTitle--) | Zwraca lub ustawia tytuł wykresu Tylko do odczytu [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Określa, czy wykres ma tabelę danych. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Określa, czy wykres ma tabelę danych. |
| [hasLegend()](#hasLegend--) | Określa, czy wykres ma legendę. |
| [setLegend(boolean value)](#setLegend-boolean-) | Określa, czy wykres ma legendę. |
| [getLegend()](#getLegend--) | Zwraca lub ustawia legendę dla wykresu. |
| [getChartDataTable()](#getChartDataTable--) | Zwraca tabelę danych wykresu. |
| [getStyle()](#getStyle--) | Zwraca lub ustawia styl wykresu. |
| [setStyle(int value)](#setStyle-int-) | Zwraca lub ustawia styl wykresu. |
| [getType()](#getType--) | Zwraca lub ustawia typ wykresu. |
| [setType(int value)](#setType-int-) | Zwraca lub ustawia typ wykresu. |
| [getPlotArea()](#getPlotArea--) | Reprezentuje obszar plotowania wykresu. |
| [getRotation3D()](#getRotation3D--) | Zwraca obrót 3D wykresu. |
| [getBackWall()](#getBackWall--) | Zwraca obiekt umożliwiający zmianę formatu tylnej ściany wykresu 3D. |
| [getSideWall()](#getSideWall--) | Zwraca obiekt umożliwiający zmianę formatu bocznej ściany wykresu 3D. |
| [getFloor()](#getFloor--) | Zwraca obiekt umożliwiający zmianę formatu podłogi wykresu 3D. |
| [getUserShapes()](#getUserShapes--) | Określ kształty rysowane na wykresie. |
| [getAxes()](#getAxes--) | Zapewnia dostęp do osi wykresu. |
| [validateChartLayout()](#validateChartLayout--) | Oblicza rzeczywiste wartości elementów wykresu. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Określa, że etykiety danych powyżej maksimum wykresu mają być wyświetlane. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Określa, że etykiety danych powyżej maksimum wykresu mają być wyświetlane. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Określa, że obszar wykresu ma mieć zaokrąglone rogi. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Określa, że obszar wykresu ma mieć zaokrąglone rogi. |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```


Określa, czy jedynie widoczne komórki są wykreślane. False to plot both visible and hidden cells. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```


Określa, czy jedynie widoczne komórki są wykreślane. False to plot both visible and hidden cells. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```


Zwraca lub ustawia sposób wykreślania pustych komórek na wykresie. Odczyt/zapis [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Zwraca:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```


Zwraca lub ustawia sposób wykreślania pustych komórek na wykresie. Odczyt/zapis [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```


Zwraca informacje o powiązanych lub osadzonych danych związanych z wykresem. Tylko do odczytu [IChartData](../../com.aspose.slides/ichartdata).

**Zwraca:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```


Określa, czy wykres ma widoczny tytuł. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```


Określa, czy wykres ma widoczny tytuł. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```


Zwraca lub ustawia tytuł wykresu Tylko do odczytu [IChartTitle](../../com.aspose.slides/icharttitle).

**Zwraca:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```


Określa, czy wykres ma tabelę danych. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```


Określa, czy wykres ma tabelę danych. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```


Określa, czy wykres ma legendę. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```


Określa, czy wykres ma legendę. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```


Zwraca lub ustawia legendę dla wykresu. Tylko do odczytu [ILegend](../../com.aspose.slides/ilegend).

**Zwraca:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```


Zwraca tabelę danych wykresu. Tylko do odczytu [IDataTable](../../com.aspose.slides/idatatable).

**Zwraca:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```


Zwraca lub ustawia styl wykresu. Odczyt/zapis [StyleType](../../com.aspose.slides/styletype).

**Zwraca:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```


Zwraca lub ustawia styl wykresu. Odczyt/zapis [StyleType](../../com.aspose.slides/styletype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```


Zwraca lub ustawia typ wykresu. Odczyt/zapis [ChartType](../../com.aspose.slides/charttype).

**Zwraca:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Zwraca lub ustawia typ wykresu. Odczyt/zapis [ChartType](../../com.aspose.slides/charttype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```


Reprezentuje obszar plotowania wykresu. Tylko do odczytu [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Zwraca:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```


Zwraca obrót 3D wykresu. Tylko do odczytu [IRotation3D](../../com.aspose.slides/irotation3d).

**Zwraca:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```


Zwraca obiekt umożliwiający zmianę formatu tylnej ściany wykresu 3D. Tylko do odczytu [IChartWall](../../com.aspose.slides/ichartwall).

**Zwraca:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```


Zwraca obiekt umożliwiający zmianę formatu bocznej ściany wykresu 3D. Tylko do odczytu [IChartWall](../../com.aspose.slides/ichartwall).

**Zwraca:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```


Zwraca obiekt umożliwiający zmianę formatu podłogi wykresu 3D. Tylko do odczytu [IChartWall](../../com.aspose.slides/ichartwall).

**Zwraca:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```


Określ kształty rysowane na wykresie. Tylko do odczytu [IGroupShape](../../com.aspose.slides/igroupshape).

**Zwraca:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```


Zapewnia dostęp do osi wykresu. Tylko do odczytu [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Zwraca:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```


Oblicza rzeczywiste wartości elementów wykresu. Actual values inlude position of elements that implement IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```


Określa, że etykiety danych powyżej maksimum wykresu mają być wyświetlane. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```


Określa, że etykiety danych powyżej maksimum wykresu mają być wyświetlane. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```


Określa, że obszar wykresu ma mieć zaokrąglone rogi. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```


Określa, że obszar wykresu ma mieć zaokrąglone rogi. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |