---
title: IChartSeries
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 차트 시리즈를 나타냅니다.
type: docs
weight: 1930
url: /ko/aspose.slides.charts/ichartseries/
---
## IChartSeries 인터페이스

차트 시리즈를 나타냅니다.

```csharp
public interface IChartSeries : IChartComponent
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | 기본 IChartComponent 인터페이스를 가져올 수 있습니다. 읽기 전용 [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 3D 막대 차트 시리즈의 모양을 지정합니다. 이 속성 값을 변경하면 시리즈 유형이 자동으로 변경될 수 있습니다. 읽기/쓰기 [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | 버블 차트에서 버블 크기 값이 표시되는 방식을 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.BubbleSizeRepresentation 읽기/쓰기 속성을 사용하십시오. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | 버블 차트의 배율 계수를 지정합니다(기본 크기의 0~300%). 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.BubbleSizeScale 읽기/쓰기 속성을 사용하십시오. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | 이 시리즈의 데이터 포인트 컬렉션을 반환합니다. 읽기 전용 [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10~90%). 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.DoughnutHoleSize 읽기/쓰기 속성을 사용하십시오. 읽기 전용 Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | X 방향 오류 막대를 나타냅니다. X 방향 오류 막대는 area, bar, scatter, bubble 시리즈에 사용할 수 있습니다. 다른 차트 유형(3D 차트 포함)에서는 null을 반환합니다. 사용자 정의 값의 경우 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 속성을 사용하여 DataPoints 컬렉션에 값을 지정하십시오. 읽기 전용 [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Y 방향 오류 막대를 나타냅니다. Y 방향 오류 막대는 area, bar, line, scatter, bubble 시리즈에 사용할 수 있습니다. 다른 차트 유형(3D 차트 포함)에서는 null을 반환합니다. 사용자 정의 값의 경우 [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) 속성을 사용하여 DataPoints 컬렉션에 값을 지정하십시오. 읽기 전용 [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | 파이 슬라이스가 차트 중심에서 떨어진 거리를 파이 지름의 백분율로 지정합니다. 읽기/쓰기 Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | 첫 번째 파이 또는 도넛 슬라이스의 각도를 도(시계 방향, 0~360)로 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 읽기 전용이며, 값을 변경하려면 ParentSeriesGroup.FirstSliceAngle 읽기/쓰기 속성을 사용하십시오. 읽기 전용 UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | 시리즈의 형식을 반환합니다. 읽기 전용 [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 3D 차트에서 마커 너비의 백분율로 데이터 시리즈 간 거리(갭 깊이)를 반환하거나 설정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 읽기 전용이며, 값을 변경하려면 ParentSeriesGroup.GapDepth 읽기/쓰기 속성을 사용하십시오. 읽기 전용 Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | 막대 또는 열 클러스터 간의 간격을 막대·열 너비의 백분율로 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 읽기 전용이며, 값을 변경하려면 ParentSeriesGroup.GapWidth 읽기/쓰기 속성을 사용하십시오. 읽기 전용 Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | 이 시리즈와 관련 시리즈에 대한 시리즈 라인의 존재 여부를 결정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 읽기 전용이며, 값을 변경하려면 ParentSeriesGroup.HasSeriesLines 읽기/쓰기 속성을 사용하십시오. 시리즈 라인의 형식은 ParentSeriesGroup.SeriesLinesFormat 속성을 사용하십시오. 읽기 전용 Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | 라인·주식 차트에 상승/하강 바가 있는지 여부를 결정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 읽기 전용이며, 값을 변경하려면 ParentSeriesGroup.UpDownBars.HasUpDownBars 읽기/쓰기 속성을 사용하십시오. 상승/하강 바의 형식은 ParentSeriesGroup.UpDownBars 속성을 사용하십시오. 읽기 전용 Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | 시리즈에 대한 반전 솔리드 색상을 지정합니다. 색상 적용을 위해 시리즈 형식 FillType을 FillType.Solid으로 설정하십시오. 읽기/쓰기 [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | 값이 음수인 경우 막대·열·버블 시리즈가 색상을 반전하도록 지정합니다. 읽기/쓰기 Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | 시리즈의 각 데이터 마커에 서로 다른 색상이 적용되는지를 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 읽기 전용이며, 값을 변경하려면 ParentSeriesGroup.IsColorVaried 읽기/쓰기 속성을 사용하십시오. 읽기 전용 Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | 시리즈의 레이블을 반환합니다. 읽기 전용 [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | 시리즈 마커를 반환합니다. 읽기 전용 [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | 시리즈 이름을 반환합니다. 읽기 전용 [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | 시리즈 버블 크기의 숫자 형식을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | 시리즈 값의 숫자 형식을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | 시리즈 X 값의 숫자 형식을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | 시리즈 Y 값의 숫자 형식을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | 시리즈의 순서를 반환하거나 설정합니다. 읽기/쓰기 Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 2D 차트에서 막대·열이 겹치는 비율을 -100%~100% 범위의 백분율로 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영이며 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.Overlap 읽기/쓰기 속성을 사용하십시오. 읽기 전용 SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | 상위 카테고리 레이블 레이아웃을 나타냅니다. Treemap 차트에만 적용됩니다. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | 상위 시리즈 그룹을 반환합니다. 읽기 전용 [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | 파이·파이 또는 바·바 차트에서 두 번째 파이·바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 읽기 전용이며, 값을 변경하려면 ParentSeriesGroup.PieSplitBy 읽기/쓰기 속성을 사용하십시오. 읽기 전용 [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | 사용자 정의 분할이 있는 파이·파이 또는 바·바 차트에 대한 사용자 정의 분할 정보를 제공합니다. 두 번째 파이·바에 그려질 데이터 포인트를 포함합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 읽기 전용 [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | 파이·파이 또는 바·바 차트에서 두 번째 파이·바에 포함될 데이터 포인트를 결정하는 값을 지정합니다. PieSplitBy 속성과 함께 사용됩니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 읽기 전용이며, 값을 변경하려면 ParentSeriesGroup.PieSplitPosition 읽기/쓰기 속성을 사용하십시오. 읽기 전용 Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | 이 시리즈가 두 번째 값 축에 플롯되는지를 나타냅니다. 읽기/쓰기 Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | 사분위수 방법을 나타냅니다. BoxAndWhisker 차트에만 적용됩니다. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | 이 시리즈와 연관된 범례 항목을 반환합니다. 읽기 전용 [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | 파이·파이 또는 바·바 차트에서 두 번째 파이·바의 크기를 첫 번째 파이 크기의 백분율(5~200%)로 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 읽기 전용이며, 값을 변경하려면 ParentSeriesGroup.SecondPieSize 읽기/쓰기 속성을 사용하십시오. 읽기 전용 UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | 연결선(Connector Lines)을 나타냅니다. Waterfall 차트에만 적용됩니다. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | 내부 포인트를 나타냅니다. BoxAndWhisker 차트에 내부 포인트가 표시될 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | 평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 선이 표시될 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | 평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 마커가 표시될 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | 이상치 포인트를 나타냅니다. BoxAndWhisker 차트에 이상치 포인트가 표시될 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | 곡선 매끄러움을 나타냅니다. 라인 차트나 스케터 차트에서 곡선 매끄러움이 켜져 있는 경우 true입니다. 라인·스케터 연결 차트에만 적용됩니다. 읽기/쓰기 Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | 시리즈 트렌드 라인 컬렉션을 반환합니다. 읽기 전용 [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | 이 시리즈의 유형을 반환하거나 설정합니다. 읽기/쓰기 [`ChartType`](../charttype). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | 시리즈 인덱스와 차트 스타일에 따라 시리즈의 자동 색상을 반환합니다. FillType이 NotDefined인 경우 기본적으로 이 색상이 사용됩니다. |

### 참고

* 인터페이스 [IChartComponent](../ichartcomponent)
* 네임스페이스 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->