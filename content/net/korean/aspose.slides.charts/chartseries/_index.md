---
title: ChartSeries
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 차트 시리즈를 나타냅니다.
type: docs
weight: 1440
url: /ko/aspose.slides.charts/chartseries/
---
## ChartSeries 클래스

차트 시리즈를 나타냅니다.

```csharp
public class ChartSeries : IChartSeries
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | 3-D 막대 차트 시리즈의 모양을 지정합니다. 이 속성의 값을 변경하면 시리즈 유형이 자동으로 변경될 수 있습니다. 읽기/쓰기 [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | 버블 차트에서 버블 크기 값을 표시하는 방식을 지정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영입니다. 따라서 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.BubbleSizeRepresentation 읽기/쓰기 속성을 사용하십시오. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | 버블 차트의 배율 계수를 지정합니다(기본 크기의 0~300 %). 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영이며, 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.BubbleSizeScale 읽기/쓰기 속성을 사용하십시오. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | 상위 차트를 반환합니다. 읽기 전용 [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | 이 시리즈의 데이터 포인트 컬렉션을 반환합니다. 읽기 전용 [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10~90 %). 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영이며, 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.DoughnutHoleSize 읽기/쓰기 속성을 사용하십시오. 읽기 전용 Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | X 축 방향 ErrorBars를 나타냅니다. X 방향 ErrorBars는 area, bar, scatter, bubble 유형에만 사용할 수 있습니다. 다른 차트 유형(3-D 차트 포함)에서는 null을 반환합니다. 사용자 지정 값의 경우 DataPoints 컬렉션과 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 속성을 사용하여 값을 지정하십시오. 읽기 전용 [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Y 축 방향 ErrorBars를 나타냅니다. Y 방향 ErrorBars는 area, bar, line, scatter, bubble 유형에만 사용할 수 있습니다. 다른 차트 유형(3-D 차트 포함)에서는 null을 반환합니다. 사용자 지정 값의 경우 DataPoints 컬렉션과 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 속성을 사용하여 값을 지정하십시오. 읽기 전용 [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | 파이 차트 슬라이스를 중심에서 떨어뜨린 거리를 파이 직경의 백분율로 지정합니다. 읽기/쓰기 Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | 첫 번째 파이 또는 도넛 차트 슬라이스의 각도를 도(degree) 단위로 지정합니다(시계 방향, 0~360도). 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영이며, 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.FirstSliceAngle 읽기/쓰기 속성을 사용하십시오. 읽기 전용 UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | 시리즈의 서식을 반환합니다. 읽기 전용 [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 3-D 차트에서 데이터 시리즈 간의 거리(마커 너비에 대한 백분율)를 반환하거나 설정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영이며, 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.GapDepth 읽기/쓰기 속성을 사용하십시오. 읽기 전용 Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | 막대 또는 열 클러스터 사이의 간격을 막대·열 너비의 백분율로 지정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영이며, 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.GapWidth 읽기/쓰기 속성을 사용하십시오. 읽기 전용 Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | 이 시리즈와 연관된 시리즈 라인이 있는지와 그 종류를 결정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영이며, 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.HasSeriesLines 읽기/쓰기 속성을 사용하십시오. 시리즈 라인 서식은 ParentSeriesGroup.SeriesLinesFormat 속성을 사용하십시오. 읽기 전용 Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | 라인 또는 주식 차트가 상승/하강 막대를 갖는지 결정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영이며, 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.UpDownBars.HasUpDownBars 읽기/쓰기 속성을 사용하십시오. 상승/하강 막선 서식은 ParentSeriesGroup.UpDownBars 속성을 사용하십시오. 읽기 전용 Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | 시리즈의 반전 실선 색을 지정합니다. 색 설정을 적용하려면 시리즈 서식의 FillType을 FillType.Solid로 설정하십시오. 읽기/쓰기 [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | 값이 음수인 경우 막대·열·버블 시리즈가 색을 반전하도록 지정합니다. 읽기/쓰기 Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | 시리즈의 각 데이터 마커가 서로 다른 색을 갖도록 지정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영이며, 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.IsColorVaried 읽기/쓰기 속성을 사용하십시오. 읽기 전용 Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | 시리즈의 레이블을 반환합니다. 읽기 전용 [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | 마커. 읽기 전용 [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | 시리즈 이름을 반환합니다. 읽기 전용 [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. 읽기/쓰기 String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. 읽기/쓰기 String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. 읽기/쓰기 String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. 읽기/쓰기 String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | 시리즈의 순서를 반환합니다. 읽기/쓰기 Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 2-D 차트에서 막대와 열이 겹치는 정도를 백분율(-100 %~100 %)로 지정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영이며, 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.Overlap 읽기/쓰기 속성을 사용하십시오. 읽기 전용 SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | 상위 카테고리 레이블의 레이아웃을 나타냅니다. Treemap 차트에만 적용됩니다. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. 읽기 전용 [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영이며, 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.PieSplitBy 읽기/쓰기 속성을 사용하십시오. 읽기 전용 [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | 사용자 지정 분할 정보는 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 그릴 데이터 포인트를 포함합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영이며, 읽기 전용 [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 값이며, PieSplitBy 속성과 함께 사용됩니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영이며, 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.PieSplitPosition 읽기/쓰기 속성을 사용하십시오. 읽기 전용 Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | 이 시리즈가 보조 축에 표시되는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | 사분위수 방법을 나타냅니다. BoxAndWhisker 차트에만 적용됩니다. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | 이 시리즈와 관련된 범례 항목을 나타냅니다. 읽기 전용 [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율(5~200 %)로 지정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 그룹 속성의 투영이며, 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.SecondPieSize 읽기/쓰기 속성을 사용하십시오. 읽기 전용 UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | 연결선(Connector Lines)을 나타냅니다. Waterfall 차트에만 적용됩니다. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | 내부 포인트를 나타냅니다. BoxAndWhisker 차트에 내부 포인트가 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | 평균선(Mean Line)을 나타냅니다. BoxAndWhisker 차트에 평균선이 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | 평균 마커(Mean Markers)를 나타냅니다. BoxAndWhisker 차트에 평균 마커가 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | 이상값 포인트(Outlier Points)를 나타냅니다. BoxAndWhisker 차트에 이상값 포인트가 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | 곡선 스무딩(Curve Smoothing)을 나타냅니다. 라인 차트나 스캐터 차트(라인 연결)에서 곡선 스무딩이 켜져 있는 경우 true입니다. 라인 및 스캐터(라인 연결) 차트에만 적용됩니다. 읽기/쓰기 Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | 시리즈 추세선 컬렉션. 읽기 전용 [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | 이 시리즈의 유형을 반환합니다. 읽기/쓰기 [`ChartType`](../charttype). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | 시리즈 인덱스와 차트 스타일을 기준으로 자동 색을 반환합니다. FillType이 NotDefined인 경우 기본 색으로 사용됩니다. |

### 참고

* 인터페이스 [IChartSeries](../ichartseries)
* 네임스페이스 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->