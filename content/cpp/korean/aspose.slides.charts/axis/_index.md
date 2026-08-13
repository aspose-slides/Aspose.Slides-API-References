---
title: Axis
second_title: Aspose.Slides for C++ API 참조
description: 차트 축을 나타내는 객체를 캡슐화합니다.
type: docs
weight: 14
url: /ko/aspose.slides.charts/axis/
---
## Axis 클래스

차트 축을 나타내는 객체를 캡슐화합니다.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | 축의 실제 주요 단위를 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | 축의 실제 주요 단위 스케일을 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | 축의 실제 최대 값을 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | 축의 실제 보조 단위를 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | 축의 실제 보조 단위 스케일을 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | 축의 실제 최소 값을 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | 범주 축의 집계 유형(빈닝)을 나타냅니다. 범주에 적용됩니다. 히스토그램 또는 HistogramPareto 시리즈에만 사용됩니다. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | 값 축이 범주 사이에서 범주 축을 교차하는지 여부를 나타냅니다. 이 속성은 범주 축에만 적용되며 3D 차트에는 적용되지 않습니다. **bool**를 읽습니다. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | 날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. [TimeUnitType](../timeunittype/)을(를) 읽습니다. |
| **double** [get_BinWidth](./get_binwidth/)() override | AggregationType 속성 값이 [AxisAggregationType::ByBinWidth](../axisaggregationtype/)로 설정된 경우 빈 너비를 지정합니다. 범주 축에 적용됩니다. 히스토그램 또는 HistogramPareto 시리즈에만 사용됩니다. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | 범주 축의 유형을 지정합니다. [Charts::CategoryAxisType](../categoryaxistype/)을(를) 읽습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 부모 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | 축이 직각으로 교차하는 지점을 나타냅니다. **float**를 읽습니다. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | 다른 축이 교차하는 지정된 축의 CrossType을 나타냅니다. [CrossesType](../crossestype/)을(를) 읽습니다. |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | 값 축에 대한 표시 단위의 스케일 값을 지정합니다. [DisplayUnitType](../displayunittype/)을(를) 읽습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | 축의 형식을 나타냅니다. 읽기 전용 [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | 축에 표시 가능한 제목이 있는지 여부를 결정합니다. **bool**를 읽습니다. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | 축의 주요 단위가 자동으로 지정되는지 여부를 나타냅니다. **bool**를 읽습니다. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | 최대 값이 자동으로 지정되는지 여부를 나타냅니다. **bool**를 읽습니다. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | 축의 보조 단위가 자동으로 지정되는지 여부를 나타냅니다. **bool**를 읽습니다. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | 최소 값이 자동으로 지정되는지 여부를 나타냅니다. **bool**를 읽습니다. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | 자동 오버플로 빈 값을 지정합니다. false인 경우: OverflowBin 속성을 사용하십시오. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | 자동 눈금 라벨 간격 값을 지정합니다. false인 경우: TickLabelSpacing 속성을 사용하십시오. **bool**를 읽습니다. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | 자동 눈금 표시 간격 값을 지정합니다. false인 경우: TickMarksSpacing 속성을 사용하십시오. **bool**를 읽습니다. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | 자동 언더플로 빈 값을 지정합니다. false인 경우: UnderflowBin 속성을 사용하십시오. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | 값 축 스케일 유형이 로그인지 여부를 나타냅니다. **bool**를 읽습니다. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | 형식이 연결된 원본 데이터인지 여부를 나타냅니다. **bool**를 읽습니다. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | 오버플로 빈이 적용되는지 지정합니다. 오버플로 빈 값을 조정하려면 IsAutomaticOverflowBin 및 OverflowBin을 사용하십시오. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | MS PowerPoint가 데이터 포인트를 마지막에서 첫 번째로 플롯하는지 여부를 나타냅니다. **bool**를 읽습니다. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | 언더플로 빈이 적용되는지 지정합니다. 언더플로 빈 값을 조정하려면 IsAutomaticUnderflowBin 및 UnderflowBin을 사용하십시오. |
| **bool** [get_IsVisible](./get_isvisible/)() override | 축이 표시되는지 여부를 나타냅니다. **bool**를 읽습니다. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | 축에서 레이블까지의 거리를 지정합니다. 범주 축 또는 날짜 축에 적용됩니다. 값은 0%와 1000% 사이여야 합니다. **uint16_t**를 읽습니다. |
| **double** [get_LogBase](./get_logbase/)() override | 로그 기반을 나타냅니다. 기본값은 10입니다. **double**를 읽습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | 차트 축에 대한 주요 격자선 형식을 나타냅니다. 읽기 전용 [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | 지정된 축에 대한 주요 눈금 표시 유형을 나타냅니다. [TickMarkType](../tickmarktype/)을(를) 읽습니다. |
| **double** [get_MajorUnit](./get_majorunit/)() override | 날짜 또는 값 축에 대한 주요 단위를 나타냅니다. **double**를 읽습니다. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. [TimeUnitType](../timeunittype/)을(를) 읽습니다. |
| **double** [get_MaxValue](./get_maxvalue/)() override | 값 축에 대한 최대 값을 나타냅니다. **double**를 읽습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | 차트 축에 대한 보조 격자선 형식을 나타냅니다. 읽기 전용 [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | 지정된 축에 대한 보조 눈금 표시 유형을 나타냅니다. [TickMarkType](../tickmarktype/)을(를) 읽습니다. |
| **double** [get_MinorUnit](./get_minorunit/)() override | 날짜 또는 값 축에 대한 보조 단위를 나타냅니다. **double**를 읽습니다. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. [TimeUnitType](../timeunittype/)을(를) 읽습니다. |
| **double** [get_MinValue](./get_minvalue/)() override | 값 축에 대한 최소 값을 나타냅니다. **double**를 읽습니다. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | [Axis](./) 레이블에 대한 형식 문자열을 나타냅니다. [System::String](../../system/string/)을(를) 읽습니다. |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | AggregationType 속성 값이 [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/)로 설정된 경우 빈 수를 지정합니다. 범주 축에 적용됩니다. 히스토그램 또는 HistogramPareto 시리즈에만 사용됩니다. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | 오버플로 빈 사용자 정의 값을 지정합니다. IsAutomaticOverflowBin 속성이 false로 설정되고 IsOverflowBin 속성이 true인 경우 적용됩니다. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | 축의 위치를 나타냅니다. [AxisPositionType](../axispositiontype/)을(를) 읽습니다. |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | 주요 격자선을 숨기려면 [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType()을 [FillType::NoFill](../../aspose.slides/filltype/)로 설정하십시오. 읽기 전용 **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | 보조 격자선을 숨기려면 [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType()을 [FillType::NoFill](../../aspose.slides/filltype/)로 설정하십시오. 읽기 전용 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 텍스트 형식을 나타냅니다. 읽기 전용 [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | 지정된 축에 대한 눈금 라벨 위치를 나타냅니다. [TickLabelPositionType](../ticklabelpositiontype/)을(를) 읽습니다. |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | 눈금 라벨의 회전 각도를 나타냅니다. **float**를 읽습니다. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | 그려지는 레이블 사이에 건너뛸 눈금 라벨 수를 지정합니다. 범주 또는 시리즈 축에 적용됩니다. **uint32_t**를 읽습니다. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | 다음 눈금이 그려지기 전에 건너뛸 눈금 수를 지정합니다. 범주 또는 시리즈 축에 적용됩니다. **uint16_t**를 읽습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | 축의 제목을 가져옵니다. 읽기 전용 [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | 언더플로 빈 사용자 정의 값을 지정합니다. IsAutomaticUnderflowBin 속성이 false로 설정되고 IsUnderflowBin 속성이 true인 경우 적용됩니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | 범주 축의 집계 유형(빈닝)을 나타냅니다. 범주에 적용됩니다. 히스토그램 또는 HistogramPareto 시리즈에만 사용됩니다. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | 값 축이 범주 사이에서 범주 축을 교차하는지 여부를 나타냅니다. 이 속성은 범주 축에만 적용되며 3D 차트에는 적용되지 않습니다. **bool**를 씁니다. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | 날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. [TimeUnitType](../timeunittype/)을(를) 씁니다. |
| void [set_BinWidth](./set_binwidth/)(**double**) override | AggregationType 속성 값이 [AxisAggregationType::ByBinWidth](../axisaggregationtype/)로 설정된 경우 빈 너비를 지정합니다. 범주 축에 적용됩니다. 히스토그램 또는 HistogramPareto 시리즈에만 사용됩니다. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | 범주 축의 유형을 지정합니다. [Charts::CategoryAxisType](../categoryaxistype/)을(를) 씁니다. |
| void [set_CrossAt](./set_crossat/)(**float**) override | 축이 직각으로 교차하는 지점을 나타냅니다. **float**를 씁니다. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | 다른 축이 교차하는 지정된 축의 CrossType을 나타냅니다. [CrossesType](../crossestype/)을(를) 씁니다. |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | 값 축에 대한 표시 단위의 스케일 값을 지정합니다. [DisplayUnitType](../displayunittype/)을(를) 씁니다. |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | 축에 표시 가능한 제목이 있는지 여부를 결정합니다. **bool**를 씁니다. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | 축의 주요 단위가 자동으로 지정되는지 여부를 나타냅니다. **bool**를 씁니다. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | 최대 값이 자동으로 지정되는지 여부를 나타냅니다. **bool**를 씁니다. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | 축의 보조 단위가 자동으로 지정되는지 여부를 나타냅니다. **bool**를 씁니다. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | 최소 값이 자동으로 지정되는지 여부를 나타냅니다. **bool**를 씁니다. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | 자동 오버플로 빈 값을 지정합니다. false인 경우: OverflowBin 속성을 사용하십시오. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | 자동 눈금 라벨 간격 값을 지정합니다. false인 경우: TickLabelSpacing 속성을 사용하십시오. **bool**를 씁니다. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | 자동 눈금 표시 간격 값을 지정합니다. false인 경우: TickMarksSpacing 속성을 사용하십시오. **bool**를 씁니다. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | 자동 언더플로 빈 값을 지정합니다. false인 경우: UnderflowBin 속성을 사용하십시오. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | 값 축 스케일 유형이 로그인지 여부를 나타냅니다. **bool**를 씁니다. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | 형식이 연결된 원본 데이터인지 여부를 나타냅니다. **bool**를 씁니다. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | 오버플로 빈이 적용되는지 지정합니다. 오버플로 빈 값을 조정하려면 IsAutomaticOverflowBin 및 OverflowBin을 사용하십시오. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | MS PowerPoint가 데이터 포인트를 마지막에서 첫 번째로 플롯하는지 여부를 나타냅니다. **bool**를 씁니다. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | 언더플로 빈이 적용되는지 지정합니다. 언더플로 빈 값을 조정하려면 IsAutomaticUnderflowBin 및 UnderflowBin을 사용하십시오. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | 축이 표시되는지 여부를 나타냅니다. **bool**를 씁니다. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | 축에서 레이블까지의 거리를 지정합니다. 범주 또는 날짜 축에 적용됩니다. 값은 0%와 1000% 사이여야 합니다. **uint16_t**를 씁니다. |
| void [set_LogBase](./set_logbase/)(**double**) override | 로그 기반을 나타냅니다. 기본값은 10입니다. **double**를 씁니다. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | 지정된 축에 대한 주요 눈금 표시 유형을 나타냅니다. [TickMarkType](../tickmarktype/)을(를) 씁니다. |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | 날짜 또는 값 축에 대한 주요 단위를 나타냅니다. **double**를 씁니다. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. [TimeUnitType](../timeunittype/)을(를) 씁니다. |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | 값 축에 대한 최대 값을 나타냅니다. **double**를 씁니다. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | 지정된 축에 대한 보조 눈금 표시 유형을 나타냅니다. [TickMarkType](../tickmarktype/)을(를) 씁니다. |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | 날짜 또는 값 축에 대한 보조 단위를 나타냅니다. **double**를 씁니다. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. [TimeUnitType](../timeunittype/)을(를) 씁니다. |
| void [set_MinValue](./set_minvalue/)(**double**) override | 값 축에 대한 최소 값을 나타냅니다. **double**를 씁니다. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | [Axis](./) 레이블에 대한 형식 문자열을 나타냅니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | AggregationType 속성 값이 [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/)로 설정된 경우 빈 수를 지정합니다. 범주 축에 적용됩니다. 히스토그램 또는 HistogramPareto 시리즈에만 사용됩니다. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | 오버플로 빈 사용자 정의 값을 지정합니다. IsAutomaticOverflowBin 속성이 false로 설정되고 IsOverflowBin 속성이 true인 경우 적용됩니다. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | 축의 위치를 나타냅니다. [AxisPositionType](../axispositiontype/)을(를) 씁니다. |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | 지정된 축에 대한 눈금 라벨 위치를 나타냅니다. [TickLabelPositionType](../ticklabelpositiontype/)을(를) 씁니다. |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | 눈금 라벨의 회전 각도를 나타냅니다. **float**를 씁니다. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | 그려지는 레이블 사이에 건너뛸 눈금 라벨 수를 지정합니다. 범주 또는 시리즈 축에 적용됩니다. **uint32_t**를 씁니다. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | 다음 눈금이 그려지기 전에 건너뛸 눈금 수를 지정합니다. 범주 또는 시리즈 축에 적용됩니다. **uint16_t**를 씁니다. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | 언더플로 빈 사용자 정의 값을 지정합니다. IsAutomaticUnderflowBin 속성이 false로 설정되고 IsUnderflowBin 속성이 true인 경우 적용됩니다. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | IAxis::get(set)_CategoryAxisType 속성을 축 데이터에 기반해 자동으로 결정되는 값으로 설정합니다. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n번째 템플릿 인수를 약한 포인터로 설정합니다(공유 포인터가 아니라). 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소하고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## See Also

* 클래스 [DomObject](../../aspose.slides/domobject/)
* 클래스 [IAxis](../iaxis/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)