---
title: Axis
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 차트 축을 나타내는 객체를 캡슐화합니다.
type: docs
weight: 1180
url: /ko/aspose.slides.charts/axis/
---
## Axis 클래스

차트의 축을 나타내는 객체를 캡슐화합니다.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## 속성

| Name | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | 축의 실제 주요 단위를 지정합니다. 실제 값을 얻기 위해 이전에 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | 축의 실제 주요 단위 스케일을 지정합니다. 실제 값을 얻기 위해 이전에 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | 축의 실제 최대 값을 지정합니다. 실제 값을 얻기 위해 이전에 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | 축의 실제 보조 단위를 지정합니다. 실제 값을 얻기 위해 이전에 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | 축의 실제 보조 단위 스케일을 지정합니다. 실제 값을 얻기 위해 이전에 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | 축의 실제 최소 값을 지정합니다. 실제 값을 얻기 위해 이전에 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | 카테고리 축(빈닝)의 집계 유형을 나타냅니다. 카테고리에 적용됩니다. Histogram 또는 HistogramPareto 시리즈와 함께 사용할 수 있습니다. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | 값 축이 카테고리 축 사이를 교차하는지를 나타냅니다. 이 속성은 카테고리 축에만 적용되며 3D 차트에는 적용되지 않습니다. 읽기/쓰기 Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | 날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. 읽기/쓰기 [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | AggregationType 속성 값이 AxisAggregationType.ByBinWidth 로 설정된 경우 빈 너비를 지정합니다. 카테고리 축에 적용됩니다. Histogram 또는 HistogramPareto 시리즈와 함께 사용할 수 있습니다. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | 카테고리 축의 유형을 지정합니다. 읽기/쓰기 [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | 상위 차트를 반환합니다. 읽기 전용 [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | 수직 축이 교차하는 축상의 지점을 나타냅니다. 읽기/쓰기 Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | 다른 축이 교차하는 지정된 축상의 CrossType을 나타냅니다. 읽기/쓰기 [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | 값 축에 대한 표시 단위의 스케일 값을 지정합니다. 읽기/쓰기 [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | 축의 형식을 나타냅니다. 읽기 전용 [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | 축에 표시 가능한 제목이 있는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | 축의 주요 단위가 자동으로 지정되는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | 최대 값이 자동으로 지정되는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | 축의 보조 단위가 자동으로 지정되는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | 최소 값이 자동으로 지정되는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | 자동 overflow bin 값을 지정합니다. false인 경우: OverflowBin 속성을 사용하십시오. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | 자동 눈금 레이블 간격 값을 지정합니다. false인 경우: TickLabelSpacing 속성을 사용하십시오. 읽기/쓰기 Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | 자동 눈금 표시 간격 값을 지정합니다. false인 경우: TickMarksSpacing 속성을 사용하십시오. 읽기/쓰기 Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | 자동 underflow bin 값을 지정합니다. false인 경우: UnderflowBin 속성을 사용하십시오. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | 값 축 스케일 유형이 로그인지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | 형식이 원본 데이터에 연결되어 있는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | overflow bin이 적용되는지 지정합니다. IsAutomaticOverflowBin 및 OverflowBin을 사용하여 overflow bin 값을 조정하십시오. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | MS PowerPoint가 데이터 포인트를 마지막에서 첫 번째로 플롯하는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | underflow bin이 적용되는지 지정합니다. IsAutomaticUnderflowBin 및 UnderflowBin을 사용하여 underflow bin 값을 조정하십시오. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | 축이 표시되는지 여부를 나타냅니다. 읽기/쓰기 Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | 레이블이 축으로부터 떨어지는 거리를 지정합니다. 카테고리 또는 날짜 축에 적용됩니다. 값은 0%와 1000% 사이여야 합니다. 읽기/쓰기 UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | 로그 기반을 나타냅니다. 기본값은 10입니다. 읽기/쓰기 Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | 차트 축에 대한 주요 눈금선 형식을 나타냅니다. 읽기 전용 [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | 지정된 축에 대한 주요 눈금 표시 유형을 나타냅니다. 읽기/쓰기 [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | 날짜 또는 값 축에 대한 주요 단위를 나타냅니다. 읽기/쓰기 Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. 읽기/쓰기 [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | 값 축의 최대 값을 나타냅니다. 읽기/쓰기 Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | 차트 축에 대한 보조 눈금선 형식을 나타냅니다. 읽기 전용 [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | 지정된 축에 대한 보조 눈금 표시 유형을 나타냅니다. 읽기/쓰기 [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | 날짜 또는 값 축에 대한 보조 단위를 나타냅니다. 읽기/쓰기 Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. 읽기/쓰기 [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | 값 축의 최소 값을 나타냅니다. 읽기/쓰기 Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Axis 레이블에 대한 형식 문자열을 나타냅니다. 읽기/쓰기 String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | AggregationType 속성 값이 AxisAggregationType.ByNumberOfBins 로 설정된 경우 빈 개수를 지정합니다. 카테고리 축에 적용됩니다. Histogram 또는 HistogramPareto 시리즈와 함께 사용할 수 있습니다. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | overflow bin 사용자 정의 값을 지정합니다. IsAutomaticOverflowBin 속성이 false이고 IsOverflowBin 속성이 true인 경우 적용됩니다. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | 축의 위치를 나타냅니다. 읽기/쓰기 [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | 주 눈금선을 숨기려면 MajorGridLinesFormat.Line.FillFormat.FillType을 FillType.NoFill 로 설정하십시오. 읽기 전용 Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | 보조 눈금선을 숨기려면 MinorGridLinesFormat.Line.FillFormat.FillType을 FillType.NoFill 로 설정하십시오. 읽기 전용 Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | 텍스트 형식을 나타냅니다. 읽기 전용 [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | 지정된 축에 대한 눈금 레이블 위치를 나타냅니다. 읽기/쓰기 [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | 눈금 레이블의 회전 각도를 나타냅니다. 읽기/쓰기 Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | 그려지는 레이블 사이에 건너뛸 눈금 레이블 수를 지정합니다. 카테고리 또는 시리즈 축에 적용됩니다. 읽기/쓰기 UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | 다음 눈금이 그려지기 전에 건너뛸 눈금 수를 지정합니다. 카테고리 또는 시리즈 축에 적용됩니다. 읽기/쓰기 UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | 축의 제목을 가져옵니다. 읽기 전용 [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | underflow bin 사용자 정의 값을 지정합니다. IsAutomaticUnderflowBin 속성이 false이고 IsUnderflowBin 속성이 true인 경우 적용됩니다. |

## 메서드

| Name | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | 축 데이터에 따라 자동으로 결정되는 값을 사용하여 IAxis.CategoryAxisType 속성을 설정합니다. |

### 참고

* 클래스 [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* 클래스 [AxesManager](../axesmanager)
* 인터페이스 [IAxis](../iaxis)
* 네임스페이스 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->