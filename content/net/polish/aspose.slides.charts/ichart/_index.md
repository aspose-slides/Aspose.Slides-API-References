---
title: IChart
second_title: Aspose.Sildes dla .NET – Referencja API
description: Reprezentuje wykres graficzny na slajdzie.
type: docs
weight: 1720
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
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Udostępnia dostęp do osi wykresu. Tylko do odczytu [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Zwraca obiekt umożliwiający zmianę formatu tylnej ściany wykresu 3D. Tylko do odczytu [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Zwraca informacje o połączonych lub osadzonych danych powiązanych z wykresem. Tylko do odczytu [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Zwraca tabelę danych wykresu. Tylko do odczytu [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Zwraca lub ustawia tytuł wykresu. Tylko do odczytu [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Zwraca lub ustawia sposób rysowania pustych komórek na wykresie. Odczyt/zapis [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Zwraca obiekt umożliwiający zmianę formatu podłogi wykresu 3D. Tylko do odczytu [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Określa, czy wykres posiada tabelę danych. Odczyt/zapis Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Określa, czy wykres posiada legendę. Odczyt/zapis Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Określa, że obszar wykresu ma mieć zaokrąglone rogi. Odczyt/zapis Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Określa, czy wykres ma widoczny tytuł. Odczyt/zapis Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Zwraca lub ustawia legendę wykresu. Tylko do odczytu [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Reprezentuje obszar rysowania wykresu. Tylko do odczytu [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Określa, czy rysowane są tylko widoczne komórki. False, aby rysować zarówno widoczne, jak i ukryte komórki. Odczyt/zapis Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Zwraca obrót 3D wykresu. Tylko do odczytu [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Określa, że etykiety danych powyżej maksymalnej wartości wykresu mają być wyświetlane. Odczyt/zapis Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Zwraca obiekt umożliwiający zmianę formatu bocznej ściany wykresu 3D. Tylko do odczytu [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Zwraca lub ustawia styl wykresu. Odczyt/zapis [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Zwraca lub ustawia typ wykresu. Odczyt/zapis [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Określa kształty rysowane na wykresie. Tylko do odczytu [`IGroupShape`](../../aspose.slides/igroupshape). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Oblicza rzeczywiste wartości elementów wykresu. Rzeczywiste wartości obejmują pozycję elementów implementujących interfejs IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) oraz rzeczywiste wartości osi (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Zobacz także

* interfejs [IFormattedTextContainer](../iformattedtextcontainer)
* interfejs [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interfejs [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* biblioteka [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->