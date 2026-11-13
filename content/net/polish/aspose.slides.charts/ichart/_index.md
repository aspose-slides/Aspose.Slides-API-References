---
title: IChart
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje wykres graficzny na slajdzie.
type: docs
weight: 1760
url: /pl/aspose.slides.charts/ichart/
---
## IChart interfejs

Reprezentuje wykres graficzny na slajdzie.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Umożliwia pobranie podstawowego interfejsu IFormattedTextContainer. Tylko do odczytu [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Umożliwia pobranie podstawowego interfejsu IGraphicalObject. Tylko do odczytu [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Zwraca interfejs IOverrideThemeable. Tylko do odczytu [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Umożliwia dostęp do osi wykresu. Tylko do odczytu [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Zwraca obiekt, który umożliwia zmianę formatu tylnej ściany wykresu 3D. Tylko do odczytu [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Zwraca informacje o powiązanych lub osadzonych danych powiązanych z wykresem. Tylko do odczytu [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Zwraca tabelę danych wykresu. Tylko do odczytu [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Zwraca lub ustawia tytuł wykresu. Tylko do odczytu [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Zwraca lub ustawia sposób rysowania pustych komórek na wykresie. Do odczytu i zapisu [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Zwraca obiekt, który umożliwia zmianę formatu podłogi wykresu 3D. Tylko do odczytu [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Określa, czy wykres ma tabelę danych. Do odczytu i zapisu Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Określa, czy wykres ma legendę. Do odczytu i zapisu Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Określa, czy obszar wykresu ma zaokrąglone rogi. Do odczytu i zapisu Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Określa, czy wykres ma widoczny tytuł. Do odczytu i zapisu Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Zwraca lub ustawia legendę wykresu. Tylko do odczytu [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Reprezentuje obszar rysowania wykresu. Tylko do odczytu [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Określa, czy rysowane są tylko widoczne komórki. Fałsz oznacza rysowanie zarówno widocznych, jak i ukrytych komórek. Do odczytu i zapisu Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Zwraca obrót 3D wykresu. Tylko do odczytu [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Określa, czy etykiety danych powyżej maksimum wykresu mają być wyświetlane. Do odczytu i zapisu Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Zwraca obiekt, który umożliwia zmianę formatu bocznej ściany wykresu 3D. Tylko do odczytu [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Zwraca lub ustawia styl wykresu. Do odczytu i zapisu [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Zwraca lub ustawia typ wykresu. Do odczytu i zapisu [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Określa kształty rysowane na wierzchu wykresu. Tylko do odczytu [`IGroupShape`](../../aspose.slides/igroupshape). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Oblicza rzeczywiste wartości elementów wykresu. Rzeczywiste wartości obejmują pozycję elementów implementujących interfejs IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) oraz rzeczywiste wartości osi (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Zobacz także

* interfejs [IFormattedTextContainer](../iformattedtextcontainer)
* interfejs [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interfejs [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->