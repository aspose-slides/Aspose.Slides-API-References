---
title: Chart
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Javy
description: Reprezentuje wykres graficzny na slajdzie.
type: docs
url: /pl/com.aspose.slides/chart/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Reprezentuje wykres graficzny na slajdzie.
## Metody

| Method | Opis |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Oblicza rzeczywiste wartości elementów wykresu. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Określa, czy wykreślane są tylko widoczne komórki. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Określa, czy wykreślane są tylko widoczne komórki. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Zwraca lub ustawia sposób rysowania pustych komórek na wykresie. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Zwraca lub ustawia sposób rysowania pustych komórek na wykresie. |
| [getChartData()](#getChartData--) | Zwraca informacje o powiązanych lub osadzonych danych skojarzonych z wykresem. |
| [hasTitle()](#hasTitle--) | Określa, czy wykres posiada widoczny tytuł. |
| [setTitle(boolean value)](#setTitle-boolean-) | Określa, czy wykres posiada widoczny tytuł. |
| [getChartTitle()](#getChartTitle--) | Zwraca lub ustawia tytuł wykresu. |
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
| [getPlotArea()](#getPlotArea--) | Reprezentuje obszar wykresu. |
| [getRotation3D()](#getRotation3D--) | Zwraca rotację 3D wykresu. |
| [getBackWall()](#getBackWall--) | Zwraca obiekt umożliwiający zmianę formatu tylnej ściany wykresu 3D. |
| [getSideWall()](#getSideWall--) | Zwraca obiekt umożliwiający zmianę formatu bocznej ściany wykresu 3D. |
| [getFloor()](#getFloor--) | Zwraca obiekt umożliwiający zmianę formatu podłogi wykresu 3D. |
| [getTextFormat()](#getTextFormat--) | Zwraca format tekstu wykresu. |
| [createThemeEffective()](#createThemeEffective--) | Zwraca efektywny motyw dla tego wykresu. |
| [getThemeManager()](#getThemeManager--) | Zwraca menedżera motywów. |
| [getUserShapes()](#getUserShapes--) | Określa kształty rysowane na wykresie. |
| [getAxes()](#getAxes--) | Umożliwia dostęp do osi wykresu. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Określa, że etykiety danych powyżej maksimum wykresu mają być wyświetlane. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Określa, że etykiety danych powyżej maksimum wykresu mają być wyświetlane. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Określa, że obszar wykresu ma mieć zaokrąglone rogi. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Określa, że obszar wykresu ma mieć zaokrąglone rogi. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Oblicza rzeczywiste wartości elementów wykresu. Rzeczywiste wartości obejmują pozycję elementów implementujących interfejs IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) oraz rzeczywiste wartości osi (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Określa, czy wykreślane są tylko widoczne komórki. false oznacza wykreślanie zarówno widocznych, jak i ukrytych komórek. **Odczyt/zapis** boolean.

**Zwraca:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Określa, czy wykreślane są tylko widoczne komórki. false oznacza wykreślanie zarówno widocznych, jak i ukrytych komórek. **Odczyt/zapis** boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Zwraca lub ustawia sposób rysowania pustych komórek na wykresie. **Odczyt/zapis** [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Zwraca:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Zwraca lub ustawia sposób rysowania pustych komórek na wykresie. **Odczyt/zapis** [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Zwraca informacje o powiązanych lub osadzonych danych skojarzonych z wykresem. **Tylko do odczytu** [IChartData](../../com.aspose.slides/ichartdata).

**Zwraca:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Określa, czy wykres posiada widoczny tytuł. **Odczyt/zapis** boolean.

**Zwraca:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Określa, czy wykres posiada widoczny tytuł. **Odczyt/zapis** boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Zwraca lub ustawia tytuł wykresu. **Tylko do odczytu** [IChartTitle](../../com.aspose.slides/icharttitle).

**Zwraca:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Określa, czy wykres ma tabelę danych. **Odczyt/zapis** boolean.

**Zwraca:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Określa, czy wykres ma tabelę danych. **Odczyt/zapis** boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Określa, czy wykres ma legendę. **Odczyt/zapis** boolean.

**Zwraca:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Określa, czy wykres ma legendę. **Odczyt/zapis** boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Zwraca lub ustawia legendę dla wykresu. **Tylko do odczytu** [ILegend](../../com.aspose.slides/ilegend).

**Zwraca:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Zwraca tabelę danych wykresu. **Tylko do odczytu** [IDataTable](../../com.aspose.slides/idatatable).

**Zwraca:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public final int getStyle()
```

Zwraca lub ustawia styl wykresu. **Odczyt/zapis** [StyleType](../../com.aspose.slides/styletype).

**Zwraca:**
int

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Zwraca lub ustawia styl wykresu. **Odczyt/zapis** [StyleType](../../com.aspose.slides/styletype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Zwraca lub ustawia typ wykresu. **Odczyt/zapis** [ChartType](../../com.aspose.slides/charttype).

**Zwraca:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Zwraca lub ustawia typ wykresu. **Odczyt/zapis** [ChartType](../../com.aspose.slides/charttype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Reprezentuje obszar wykresu. **Tylko do odczytu** [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Zwraca:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Zwraca rotację 3D wykresu. **Tylko do odczytu** [IRotation3D](../../com.aspose.slides/irotation3d).

**Zwraca:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Zwraca obiekt umożliwiający zmianę formatu tylnej ściany wykresu 3D. **Tylko do odczytu** [IChartWall](../../com.aspose.slides/ichartwall).

**Zwraca:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Zwraca obiekt umożliwiający zmianę formatu bocznej ściany wykresu 3D. **Tylko do odczytu** [IChartWall](../../com.aspose.slides/ichartwall).

**Zwraca:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Zwraca obiekt umożliwiający zmianę formatu podłogi wykresu 3D. **Tylko do odczytu** [IChartWall](../../com.aspose.slides/ichartwall).

**Zwraca:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Zwraca format tekstu wykresu. Właściwość nie ma zastosowania dla następujących typów: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). **Tylko do odczytu** [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Zwraca:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Zwraca efektywny motyw dla tego wykresu.

**Zwraca:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Zwraca menedżera motywów. **Tylko do odczytu** [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Zwraca:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Określa kształty rysowane na wykresie. **Tylko do odczytu** [IGroupShape](../../com.aspose.slides/igroupshape).

**Zwraca:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Umożliwia dostęp do osi wykresu. **Tylko do odczytu** [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Zwraca:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Określa, że etykiety danych powyżej maksimum wykresu mają być wyświetlane. **Odczyt/zapis** boolean.

**Zwraca:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Określa, że etykiety danych powyżej maksimum wykresu mają być wyświetlane. **Odczyt/zapis** boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Określa, że obszar wykresu ma mieć zaokrąglone rogi. **Odczyt/zapis** boolean.

**Zwraca:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Określa, że obszar wykresu ma mieć zaokrąglone rogi. **Odczyt/zapis** boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Zwraca wykres. **Tylko do odczytu** [IChart](../../com.aspose.slides/ichart).

**Zwraca:**
[IChart](../../com.aspose.slides/ichart)