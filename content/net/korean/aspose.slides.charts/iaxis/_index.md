---
title: IAxis
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 차트 축을 나타내는 객체를 캡슐화합니다.
type: docs
weight: 1710
url: /ko/aspose.slides.charts/iaxis/
---
## IAxis 인터페이스

Encapsulates the object that represents a chart's axis.

```csharp
public interface IAxis : IFormattedTextContainer
```

## 속성

| Name | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | 축의 실제 주요 단위를 지정합니다. 실제 값을 얻기 위해 이전에 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | 축의 실제 주요 단위 배율을 지정합니다. 실제 값을 얻기 위해 이전에 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | 축의 실제 최대값을 지정합니다. 실제 값을 얻기 위해 이전에 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | 축의 실제 부단위를 지정합니다. 실제 값을 얻기 위해 이전에 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | 축의 실제 부단위 배율을 지정합니다. 실제 값을 얻기 위해 이전에 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | 축의 실제 최소값을 지정합니다. 실제 값을 얻기 위해 이전에 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | 범주 축(빈ning)의 집계 유형을 나타냅니다. 범주에 적용됩니다. Histogram 또는 HistogramPareto 시리즈와 함께 사용할 수 있습니다. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | 기본 IFormattedTextContainer 인터페이스를 가져올 수 있습니다. 읽기 전용 [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | 값 축이 범주 축을 범주 사이에서 교차하는지 여부를 나타냅니다. 이 속성은 범주 축에만 적용되며 3D 차트에는 적용되지 않습니다. 읽기/쓰기 Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | 날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. 읽기/쓰기 [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | AggregationType 속성 값이 AxisAggregationType.ByBinWidth 로 설정된 경우 bin 너비를 지정합니다. 범주 축에 적용됩니다. Histogram 또는 HistogramPareto 시리즈와 함께 사용할 수 있습니다. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | 범주 축의 유형을 지정합니다. 읽기/쓰기 [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | 축에서 수직 축이 교차하는 지점을 나타냅니다. 읽기/쓰기 Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | 다른 축이 교차하는 지정된 축의 CrossType을 나타냅니다. 읽기/쓰기 [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | 값 축에 대한 표시 단위의 스케일 값을 지정합니다. 읽기/쓰기 [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | 축의 형식을 나타냅니다. 읽기 전용 [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | 축에 보이는 제목이 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | 축의 주요 단위가 자동으로 지정되는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | 최대값이 자동으로 지정되는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | 축의 부단위가 자동으로 지정되는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | 최소값이 자동으로 지정되는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | 자동 오버플로우 bin 값을 지정합니다. false인 경우: OverflowBin 속성을 사용합니다. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | 자동 눈금 레이블 간격 값을 지정합니다. false인 경우: TickLabelSpacing 속성을 사용합니다. 읽기/쓰기 Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | 자동 눈금 표시 간격 값을 지정합니다. false인 경우: TickMarksSpacing 속성을 사용합니다. 읽기/쓰기 Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | 자동 언더플로우 bin 값을 지정합니다. false인 경우: UnderflowBin 속성을 사용합니다. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | 값 축 스케일 유형이 로그인지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | 형식이 연결된 원본 데이터인지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | 오버플로우 bin이 적용되는지 여부를 지정합니다. IsAutomaticOverflowBin 및 OverflowBin을 사용하여 오버플로우 bin 값을 조정합니다. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | MS PowerPoint가 데이터 포인트를 마지막에서 처음으로 플롯하는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | 언더플로우 bin이 적용되는지 여부를 지정합니다. IsAutomaticUnderflowBin 및 UnderflowBin을 사용하여 언더플로우 bin 값을 조정합니다. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | 축이 표시되는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | 축에서 레이블까지의 거리를 지정합니다. 범주 축 또는 날짜 축에 적용됩니다. 값은 0%와 1000% 사이여야 합니다. 읽기/쓰기 UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | 로그 기준값을 나타냅니다. 기본값은 10입니다. 읽기/쓰기 Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | 차트 축의 주요 격자선 형식을 나타냅니다. 읽기 전용 [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | 지정된 축에 대한 주요 눈금 표시 유형을 나타냅니다. 읽기/쓰기 [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | 날짜 또는 값 축에 대한 주요 단위를 나타냅니다. 읽기/쓰기 Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | 날짜 축에 대한 주요 단위 배율을 나타냅니다. 읽기/쓰기 [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | 값 축의 최대값을 나타냅니다. 읽기/쓰기 Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | 차트 축의 부격자선 형식을 나타냅니다. 읽기 전용 [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | 지정된 축에 대한 부 눈금 표시 유형을 나타냅니다. 읽기/쓰기 [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | 날짜 또는 값 축에 대한 부 단위를 나타냅니다. 읽기/쓰기 Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | 날짜 축에 대한 주요 단위 배율을 나타냅니다. 읽기/쓰기 [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | 값 축의 최소값을 나타냅니다. 읽기/쓰기 Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | 축 레이블에 대한 형식 문자열을 나타냅니다. 읽기/쓰기 String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | AggregationType 속성 값이 AxisAggregationType.ByNumberOfBins 로 설정된 경우 bin 수를 지정합니다. 범주 축에 적용됩니다. Histogram 또는 HistogramPareto 시리즈와 함께 사용할 수 있습니다. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | 오버플로우 bin 사용자 지정 값을 지정합니다. IsAutomaticOverflowBin 속성이 false이고 IsOverflowBin 속성이 true인 경우 적용됩니다. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | 축의 위치를 나타냅니다. 읽기/쓰기 [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | 주요 격자선이 표시되는지 여부를 나타냅니다. 읽기 전용 Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | 부격자선이 표시되는지 여부를 나타냅니다. 읽기 전용 Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | 지정된 축에 대한 눈금 레이블 위치를 나타냅니다. 읽기/쓰기 [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | 눈금 레이블의 회전 각도를 나타냅니다. 읽기/쓰기 Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | 그려지는 레이블 사이에 건너뛸 눈금 레이블 수를 지정합니다. 읽기/쓰기 UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | 다음 눈금이 그려지기 전 건너뛸 눈금 수를 지정합니다. 범주 축 또는 시리즈 축에 적용됩니다. 읽기/쓰기 UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | 축의 제목을 가져옵니다. 읽기 전용 [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | 언더플로우 bin 사용자 지정 값을 지정합니다. IsAutomaticUnderflowBin 속성이 false이고 IsUnderflowBin 속성이 true인 경우 적용됩니다. |

## 메서드

| Name | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | 축 데이터에 따라 자동으로 결정되는 값으로 IAxis.CategoryAxisType 속성을 설정합니다. |

### 관련 항목

* 인터페이스 [IFormattedTextContainer](../iformattedtextcontainer)
* 네임스페이스 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->