---
title: IAxis
second_title: Aspose.Slides for C++ API 레퍼런스
description: 차트 축을 나타내는 객체를 캡슐화합니다.
type: docs
weight: 534
url: /ko/aspose.slides.charts/iaxis/
---
## IAxis 클래스

차트 축을 나타내는 객체를 캡슐화합니다.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동소수점 비교를 흉내내어 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동소수점 비교를 흉내내어 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | 축의 실제 주요 단위를 지정합니다. 실제 값을 얻기 위해 이전에 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | 축의 실제 주요 단위 배율을 지정합니다. 실제 값을 얻기 위해 이전에 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | 축의 실제 최대값을 지정합니다. 실제 값을 얻기 위해 이전에 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | 축의 실제 부 단위를 지정합니다. 실제 값을 얻기 위해 이전에 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | 축의 실제 부 단위 배율을 지정합니다. 실제 값을 얻기 위해 이전에 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | 축의 실제 최소값을 지정합니다. 실제 값을 얻기 위해 이전에 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | 범주 축(빈닝)의 집계 유형을 나타냅니다. 범주에 적용됩니다. Histogram 또는 HistogramPareto 시리즈에만 사용됩니다. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | 값 축이 범주 축을 범주 사이에서 교차하는지 여부를 나타냅니다. 이 속성은 범주 축에만 적용되며 3D 차트에는 적용되지 않습니다. 읽기 **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | 날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. 읽기 [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | AggregationType 속성 값이 [AxisAggregationType::ByBinWidth](../axisaggregationtype/)로 설정된 경우 빈 너비를 지정합니다. 범주 축에 적용됩니다. Histogram 또는 HistogramPareto 시리즈에만 사용됩니다. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | 범주 축의 유형을 지정합니다. 읽기 [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | 수직 축이 교차하는 축상의 지점을 나타냅니다. 읽기 **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | 다른 축이 교차하는 지정된 축의 CrossType을 나타냅니다. 읽기 [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | 값 축에 대한 표시 단위의 배율 값을 지정합니다. 읽기 [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | 축의 형식을 나타냅니다. 읽기 전용 [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | 축에 표시 제목이 있는지 여부를 결정합니다. 읽기 **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | 축의 주요 단위가 자동으로 할당되는지 여부를 나타냅니다. 읽기 **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | 최대값이 자동으로 할당되는지 여부를 나타냅니다. 읽기 **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | 축의 부 단위가 자동으로 할당되는지 여부를 나타냅니다. 읽기 **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | 최소값이 자동으로 할당되는지 여부를 나타냅니다. 읽기 **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | 자동 오버플로우 빈 값을 지정합니다. false인 경우: OverflowBin 속성을 사용하십시오. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | 자동 눈금 라벨 간격 값을 지정합니다. false인 경우: TickLabelSpacing 속성을 사용하십시오. 읽기 **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | 자동 눈금 표시 간격 값을 지정합니다. false인 경우: TickMarksSpacing 속성을 사용하십시오. 읽기 **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | 자동 언더플로우 빈 값을 지정합니다. false인 경우: UnderflowBin 속성을 사용하십시오. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | 값 축의 스케일 유형이 로그인지 여부를 나타냅니다. 읽기 **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | 형식이 연결된 원본 데이터인지 여부를 나타냅니다. 읽기 **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | 오버플로우 빈이 적용되는지 지정합니다. IsAutomaticOverflowBin 및 OverflowBin을 사용하여 오버플로우 빈 값을 조정하십시오. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | MS PowerPoint가 데이터를 마지막에서 처음으로 플롯하는지 여부를 나타냅니다. 읽기 **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | 언더플로우 빈이 적용되는지 지정합니다. IsAutomaticUnderflowBin 및 UnderflowBin을 사용하여 언더플로우 빈 값을 조정하십시오. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | 축이 표시되는지 여부를 나타냅니다. 읽기 **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | 라벨이 축으로부터 떨어지는 거리를 지정합니다. 범주 축 또는 날짜 축에 적용됩니다. 값은 0%와 1000% 사이여야 합니다. 읽기 **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | 로그 기반을 나타냅니다. 기본값은 10입니다. 읽기 **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | 차트 축의 주요 그리드라인 형식을 나타냅니다. 읽기 전용 [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | 지정된 축의 주요 눈금 표시 유형을 나타냅니다. 읽기 [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | 날짜 또는 값 축의 주요 단위를 나타냅니다. 읽기 **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | 날짜 축의 주요 단위 배율을 나타냅니다. 읽기 [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | 값 축의 최대값을 나타냅니다. 읽기 **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | 차트 축의 부 그리드라인 형식을 나타냅니다. 읽기 전용 [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | 지정된 축의 부 눈금 표시 유형을 나타냅니다. 읽기 [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | 날짜 또는 값 축의 부 단위를 나타냅니다. 읽기 **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | 날짜 축의 주요 단위 배율을 나타냅니다. 읽기 [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | 값 축의 최소값을 나타냅니다. 읽기 **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | [Axis](../axis/) 레이블의 형식 문자열을 나타냅니다. 읽기 [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | AggregationType 속성 값이 [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/)로 설정된 경우 빈의 수를 지정합니다. 범주 축에 적용됩니다. Histogram 또는 HistogramPareto 시리즈에만 사용됩니다. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | 오버플로우 빈 사용자 정의 값을 지정합니다. IsAutomaticOverflowBin 속성이 false이고 IsOverflowBin 속성이 true인 경우에 적용됩니다. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | 축의 위치를 나타냅니다. 읽기 [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | 주요 그리드라인이 표시되는지 여부를 나타냅니다. 읽기 전용 **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | 부 그리드라인이 표시되는지 여부를 나타냅니다. 읽기 전용 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 차트 텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | 지정된 축의 눈금 라벨 위치를 나타냅니다. 읽기 [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | 눈금 라벨의 회전 각도를 나타냅니다. 읽기 **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | 그려지는 라벨 사이에 건너뛸 눈금 라벨 수를 지정합니다. 읽기 **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | 다음 눈금을 그리기 전에 건너뛸 눈금 수를 지정합니다. 범주 축 또는 시리즈 축에 적용됩니다. 읽기 **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | 축의 제목을 가져옵니다. 읽기 전용 [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | 언더플로우 빈 사용자 정의 값을 지정합니다. IsAutomaticUnderflowBin 속성이 false이고 IsUnderflowBin 속성이 true인 경우에 적용됩니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 버전입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 버전입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자의 유사 버전입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금을 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 버전입니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자입니다. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | 범주 축(빈닝)의 집계 유형을 나타냅니다. 범주에 적용됩니다. Histogram 또는 HistogramPareto 시리즈에만 사용됩니다. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | 값 축이 범주 축을 범주 사이에서 교차하는지 여부를 나타냅니다. 이 속성은 범주 축에만 적용되며 3D 차트에는 적용되지 않습니다. **bool** 쓰기. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | 날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. [TimeUnitType](../timeunittype/) 쓰기. |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | AggregationType 속성 값이 [AxisAggregationType::ByBinWidth](../axisaggregationtype/)로 설정된 경우 빈 너비를 지정합니다. 범주 축에 적용됩니다. Histogram 또는 HistogramPareto 시리즈에만 사용됩니다. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | 범주 축의 유형을 지정합니다. [CategoryAxisType](../categoryaxistype/) 쓰기. |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | 수직 축이 교차하는 축상의 지점을 나타냅니다. **float** 쓰기. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | 다른 축이 교차하는 지정된 축의 CrossType을 나타냅니다. [CrossesType](../crossestype/) 쓰기. |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | 값 축에 대한 표시 단위의 배율 값을 지정합니다. [DisplayUnitType](../displayunittype/) 쓰기. |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | 축에 표시 제목이 있는지 여부를 결정합니다. **bool** 쓰기. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | 축의 주요 단위가 자동으로 할당되는지 여부를 나타냅니다. **bool** 쓰기. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | 최대값이 자동으로 할당되는지 여부를 나타냅니다. **bool** 쓰기. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | 축의 부 단위가 자동으로 할당되는지 여부를 나타냅니다. **bool** 쓰기. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | 최소값이 자동으로 할당되는지 여부를 나타냅니다. **bool** 쓰기. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | 자동 오버플로우 빈 값을 지정합니다. false인 경우: OverflowBin 속성을 사용하십시오. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | 자동 눈금 라벨 간격 값을 지정합니다. false인 경우: TickLabelSpacing 속성을 사용하십시오. **bool** 쓰기. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | 자동 눈금 표시 간격 값을 지정합니다. false인 경우: TickMarksSpacing 속성을 사용하십시오. **bool** 쓰기. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | 자동 언더플로우 빈 값을 지정합니다. false인 경우: UnderflowBin 속성을 사용하십시오. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | 값 축의 스케일 유형이 로그인지 여부를 나타냅니다. **bool** 쓰기. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | 형식이 연결된 원본 데이터인지 여부를 나타냅니다. **bool** 쓰기. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | 오버플로우 빈이 적용되는지 지정합니다. IsAutomaticOverflowBin 및 OverflowBin을 사용하여 오버플로우 빈 값을 조정하십시오. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | MS PowerPoint가 데이터를 마지막에서 처음으로 플롯하는지 여부를 나타냅니다. **bool** 쓰기. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | 언더플로우 빈이 적용되는지 지정합니다. IsAutomaticUnderflowBin 및 UnderflowBin을 사용하여 언더플로우 빈 값을 조정하십시오. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | 축이 표시되는지 여부를 나타냅니다. **bool** 쓰기. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | 라벨이 축으로부터 떨어지는 거리를 지정합니다. 범주 축 또는 날짜 축에 적용됩니다. 값은 0%와 1000% 사이여야 합니다. **uint16_t** 쓰기. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | 로그 기반을 나타냅니다. 기본값은 10입니다. **double** 쓰기. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | 지정된 축의 주요 눈금 표시 유형을 나타냅니다. [TickMarkType](../tickmarktype/) 쓰기. |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | 날짜 또는 값 축의 주요 단위를 나타냅니다. **double** 쓰기. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | 날짜 축의 주요 단위 배율을 나타냅니다. [TimeUnitType](../timeunittype/) 쓰기. |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | 값 축의 최대값을 나타냅니다. **double** 쓰기. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | 지정된 축의 부 눈금 표시 유형을 나타냅니다. [TickMarkType](../tickmarktype/) 쓰기. |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | 날짜 또는 값 축의 부 단위를 나타냅니다. **double** 쓰기. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | 날짜 축의 주요 단위 배율을 나타냅니다. [TimeUnitType](../timeunittype/) 쓰기. |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | 값 축의 최소값을 나타냅니다. **double** 쓰기. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | [Axis](../axis/) 레이블의 형식 문자열을 나타냅니다. [System::String](../../system/string/) 쓰기. |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | AggregationType 속성 값이 [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/)로 설정된 경우 빈의 수를 지정합니다. 범주 축에 적용됩니다. Histogram 또는 HistogramPareto 시리즈에만 사용됩니다. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | 오버플로우 빈 사용자 정의 값을 지정합니다. IsAutomaticOverflowBin 속성이 false이고 IsOverflowBin 속성이 true인 경우에 적용됩니다. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | 축의 위치를 나타냅니다. [AxisPositionType](../axispositiontype/) 쓰기. |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | 지정된 축의 눈금 라벨 위치를 나타냅니다. [TickLabelPositionType](../ticklabelpositiontype/) 쓰기. |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | 눈금 라벨의 회전 각도를 나타냅니다. **float** 쓰기. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | 그려지는 라벨 사이에 건너뛸 눈금 라벨 수를 지정합니다. **uint32_t** 쓰기. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | 다음 눈금을 그리기 전에 건너뛸 눈금 수를 지정합니다. 범주 축 또는 시리즈 축에 적용됩니다. **uint16_t** 쓰기. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | 언더플로우 빈 사용자 정의 값을 지정합니다. IsAutomaticUnderflowBin 속성이 false이고 IsUnderflowBin 속성이 true인 경우에 적용됩니다. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | 축 데이터에 따라 자동으로 결정된 값으로 IAxis::get(set)_CategoryAxisType 속성을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 버전입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 구현하여 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참조

* 클래스 [IFormattedTextContainer](../iformattedtextcontainer/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)