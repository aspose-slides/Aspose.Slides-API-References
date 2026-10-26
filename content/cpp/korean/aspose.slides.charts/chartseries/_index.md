---
title: ChartSeries
second_title: Aspose.Slides for C++ API 레퍼런스
description: 차트 시리즈를 나타냅니다.
type: docs
weight: 274
url: /ko/aspose.slides.charts/chartseries/
---
## ChartSeries 클래스

차트 시리즈를 나타냅니다.

```cpp
class ChartSeries : public Aspose::Slides::Charts::IChartSeries,
                    public Aspose::Slides::IDOMObject
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [ChartShapeType](../chartshapetype/) [get_Bar3DShape](./get_bar3dshape/)() override | 3-D 막대 차트 시리즈의 모양을 지정합니다. 이 속성의 값을 변경하면 시리즈 유형이 자동으로 변경될 수 있습니다. 읽기 [ChartShapeType](../chartshapetype/). |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | 버블 차트에서 버블 크기 값을 표시하는 방식을 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 투영 속성입니다. 따라서 이 속성은 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeRepresentation() 읽기/쓰기 속성을 사용하십시오. |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | 버블 차트의 스케일 팩터를 지정합니다(기본 크기의 0%~300% 사이). 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 투영 속성이며 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeScale() 읽기/쓰기 속성을 사용하십시오. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 상위 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_DataPoint](./get_datapoint/)(**int32_t**) override | 지정된 인덱스에 있는 이 시리즈의 데이터 포인트를 반환합니다. |
| **int32_t** [get_DataPoint](./get_datapoint/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointCollection](../ichartdatapointcollection/)\> [get_DataPoints](./get_datapoints/)() override | 이 시리즈의 데이터 포인트 컬렉션을 반환합니다. 읽기 전용 [IChartDataPointCollection](../ichartdatapointcollection/). |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | 도넛 차트에서 구멍의 크기를 지정합니다(플롯 영역 크기의 10%~90% 사이). 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 투영 속성이며 읽기 전용입니다. 값을 변경하려면 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_DoughnutHoleSize() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsXFormat](./get_errorbarsxformat/)() override | X 방향 오류 막대를 나타냅니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsYFormat](./get_errorbarsyformat/)() override | Y 방향 오류 막대를 나타냅니다. |
| **int32_t** [get_Explosion](./get_explosion/)() override | 파이 차트의 중심에서 열린 파이 조각까지의 거리를 파이 지름의 백분율로 표현합니다. 읽기 **int32_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | 첫 번째 파이 또는 도넛 차트 조각의 각도를 도(degree) 단위로 지정합니다(위에서 시계 방향, 0~360도). 이 속성은 상위 시리즈 그룹에 투영되는 읽기 전용 속성입니다. 값을 변경하려면 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_FirstSliceAngle() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 시리즈의 형식을 반환합니다. 읽기 전용 [IFormat](../iformat/). |
| **int32_t** [get_GapDepth](./get_gapdepth/)() override | 3D 차트에서 데이터 시리즈 간의 거리를 마커 너비의 백분율로 반환합니다. 이 속성은 읽기 전용이며, 값을 변경하려면 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapDepth() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **int32_t**. |
| **int32_t** [get_GapWidth](./get_gapwidth/)() override | 막대 또는 열 클러스터 간의 간격을 막대 또는 열 너비의 백분율로 지정합니다. 이 속성은 읽기 전용이며, 값을 변경하려면 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapWidth() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **int32_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | 이 시리즈 및 관련 시리즈에 시리즈 라인이 있는지 판단합니다. 이 속성은 읽기 전용이며, 값을 변경하려면 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_HasSeriesLines() 읽기/쓰기 속성을 사용하십시오. 형식 지정은 ParentSeriesGroup.SeriesLinesFormat 속성을 사용하십시오. 읽기 전용 **bool**. |
| **bool** [get_HasUpDownBars](./get_hasupdownbars/)() override | 라인 차트 또는 주식 차트에 상승/하강 막대가 있는지 판단합니다. 이 속성은 읽기 전용이며, 값을 변경하려면 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars()->get(set)_HasUpDownBars() 읽기/쓰기 속성을 사용하십시오. 형식 지정은 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars() 속성을 사용하십시오. 읽기 전용 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_InvertedSolidFillColor](./get_invertedsolidfillcolor/)() override | 시리즈의 반전 실색을 지정합니다. 색상 설정을 적용하려면 시리즈 형식의 FillType을 [FillType::Solid](../../aspose.slides/filltype/) 로 설정하십시오. 읽기 [ColorFormat](../../aspose.slides/colorformat/). |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | 값이 음수일 경우 막대, 열 또는 버블 시리즈가 색상을 반전하도록 지정합니다. 읽기 **bool**. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | 시리즈의 각 데이터 마커가 서로 다른 색을 갖도록 지정합니다. 이 속성은 읽기 전용이며, 값을 변경하려면 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_IsColorVaried() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)(**int32_t**) override | 지정된 인덱스에 있는 이 시리즈의 데이터 포인트에 대한 데이터 레이블을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelCollection](../idatalabelcollection/)\> [get_Labels](./get_labels/)() override | 시리즈의 레이블을 반환합니다. 읽기 전용 [IDataLabelCollection](../idatalabelcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | [Marker](../marker/). 읽기 전용 [IMarker](../imarker/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringChartValue](../istringchartvalue/)\> [get_Name](./get_name/)() override | 시리즈 이름을 반환합니다. 읽기 전용 [IStringChartValue](../istringchartvalue/). |
| [System::String](../../system/string/) [get_NumberFormatOfBubbleSizes](./get_numberformatofbubblesizes/)() override | NumberFormatOfBubbleSizes. 읽기 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_NumberFormatOfValues](./get_numberformatofvalues/)() override | NumberFormatOfValues. 읽기 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_NumberFormatOfXValues](./get_numberformatofxvalues/)() override | NumberFormatOfXValues. 읽기 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_NumberFormatOfYValues](./get_numberformatofyvalues/)() override | NumberFormatOfYValues. 읽기 [System::String](../../system/string/). |
| **int32_t** [get_Order](./get_order/)() override | 시리즈의 순서를 반환합니다. 읽기 **int32_t**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | 2D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%~100%)로 지정합니다. 이 속성은 읽기 전용이며, 값을 변경하려면 [get_ParentSeriesGroup()->Overlap()](./get_parentseriesgroup/) 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **int8_t**. |
| [ParentLabelLayoutType](../parentlabellayouttype/) [get_ParentLabelLayout](./get_parentlabellayout/)() override | 상위 카테고리 레이블 레이아웃을 나타냅니다. Treemap 차트에만 적용됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ParentSeries](./get_parentseries/)(**int32_t**) override | 지정된 인덱스에 있는 상위 시리즈 그룹의 차트 시리즈를 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_ParentSeriesGroup](./get_parentseriesgroup/)() override | ParentSeriesGroup. 읽기 전용 [IChartSeriesGroup](../ichartseriesgroup/). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | pie-of-pie 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. 이 속성은 읽기 전용이며, 값을 변경하려면 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitBy() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | 맞춤 분할이 있는 pie-of-pie 또는 bar-of-pie 차트의 맞춤 분할 정보를 반환합니다. 지정된 인덱스에 그려질 데이터 포인트를 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | 맞춤 분할이 있는 pie-of-pie 또는 bar-of-pie 차트의 맞춤 분할 정보를 나타냅니다. 두 번째 파이 또는 막대에 그려질 데이터 포인트를 포함합니다. 읽기 전용 [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | pie-of-pie 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대에 포함될 데이터 포인트를 결정하는 데 사용되는 값을 지정합니다. 이 속성은 읽기 전용이며, 값을 변경하려면 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitPosition() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | 이 시리즈가 보조 축에 플롯되는지 여부를 나타냅니다. 읽기 **bool**. |
| [QuartileMethodType](../quartilemethodtype/) [get_QuartileMethod](./get_quartilemethod/)() override | 사분위 방법을 나타냅니다. BoxAndWhisker 차트에만 적용됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | 이 시리즈와 관련된 범례 항목을 나타냅니다. 읽기 전용 [ILegendEntryProperties](../ilegendentryproperties/). |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | pie-of-pie 차트 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대의 크기를 첫 번째 파이의 크기 대비 백분율(5%~200%)로 지정합니다. 이 속성은 읽기 전용이며, 값을 변경하려면 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_SecondPieSize() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **uint16_t**. |
| **bool** [get_ShowConnectorLines](./get_showconnectorlines/)() override | 연결선을 나타냅니다. Waterfall 차트에만 적용됩니다. |
| **bool** [get_ShowInnerPoints](./get_showinnerpoints/)() override | 내부 포인트를 나타냅니다. BoxAndWhisker 차트에 내부 포인트가 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기 **bool**. |
| **bool** [get_ShowMeanLine](./get_showmeanline/)() override | 평균선을 나타냅니다. BoxAndWhisker 차트에 평균선이 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기 **bool**. |
| **bool** [get_ShowMeanMarkers](./get_showmeanmarkers/)() override | 평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 마커가 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기 **bool**. |
| **bool** [get_ShowOutlierPoints](./get_showoutlierpoints/)() override | 이상치 포인트를 나타냅니다. BoxAndWhisker 차트에 이상치 포인트가 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기 **bool**. |
| **bool** [get_Smooth](./get_smooth/)() override | 곡선 스무딩을 나타냅니다. 라인 차트 또는 산점도 차트에서 곡선 스무딩이 켜져 있는 경우 true입니다. 라인 및 선으로 연결된 산점도 차트에만 적용됩니다. 읽기 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendline](../itrendline/)\> [get_TrendLine](./get_trendline/)(**int32_t**) override | 지정된 인덱스에 있는 추세선을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendlineCollection](../itrendlinecollection/)\> [get_TrendLines](./get_trendlines/)() override | 시리즈 추세선 컬렉션을 반환합니다. 읽기 전용 [ITrendlineCollection](../itrendlinecollection/). |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | 이 시리즈의 유형을 반환합니다. 읽기 [ChartType](../charttype/). |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticSeriesColor](./getautomaticseriescolor/)() override | 시리즈 인덱스와 차트 스타일에 따라 자동 색상을 반환합니다. FillType이 NotDefined인 경우 기본적으로 이 색상이 사용됩니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시를 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 경비 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며, 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며, 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_Bar3DShape](./set_bar3dshape/)([ChartShapeType](../chartshapetype/)) override | 시리즈의 모양을 지정합니다. 이 속성 값을 변경하면 시리즈 유형이 자동으로 변경될 수 있습니다. 쓰기 [ChartShapeType](../chartshapetype/). |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | 파이 차트의 중심에서 열린 파이 조각까지의 거리를 파이 지름의 백분율로 표현합니다. 쓰기 **int32_t**. |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | 값이 음수일 경우 막대, 열 또는 버블 시리즈가 색상을 반전하도록 지정합니다. 쓰기 **bool**. |
| void [set_NumberFormatOfBubbleSizes](./set_numberformatofbubblesizes/)([System::String](../../system/string/)) override | NumberFormatOfBubbleSizes. 쓰기 [System::String](../../system/string/). |
| void [set_NumberFormatOfValues](./set_numberformatofvalues/)([System::String](../../system/string/)) override | NumberFormatOfValues. 쓰기 [System::String](../../system/string/). |
| void [set_NumberFormatOfXValues](./set_numberformatofxvalues/)([System::String](../../system/string/)) override | NumberFormatOfXValues. 쓰기 [System::String](../../system/string/). |
| void [set_NumberFormatOfYValues](./set_numberformatofyvalues/)([System::String](../../system/string/)) override | NumberFormatOfYValues. 쓰기 [System::String](../../system/string/). |
| void [set_Order](./set_order/)(**int32_t**) override | 시리즈의 순서를 반환합니다. 쓰기 **int32_t**. |
| void [set_ParentLabelLayout](./set_parentlabellayout/)([ParentLabelLayoutType](../parentlabellayouttype/)) override | 상위 카테고리 레이블 레이아웃을 나타냅니다. Treemap 차트에만 적용됩니다. |
| void [set_PlotOnSecondAxis](./set_plotonsecondaxis/)(**bool**) override | 이 시리즈가 보조 축에 플롯되는지 여부를 나타냅니다. 쓰기 **bool**. |
| void [set_QuartileMethod](./set_quartilemethod/)([QuartileMethodType](../quartilemethodtype/)) override | 사분위 방법을 나타냅니다. BoxAndWhisker 차트에만 적용됩니다. |
| void [set_ShowConnectorLines](./set_showconnectorlines/)(**bool**) override | 연결선을 나타냅니다. Waterfall 차트에만 적용됩니다. |
| void [set_ShowInnerPoints](./set_showinnerpoints/)(**bool**) override | 내부 포인트를 나타냅니다. BoxAndWhisker 차트에 내부 포인트가 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 쓰기 **bool**. |
| void [set_ShowMeanLine](./set_showmeanline/)(**bool**) override | 평균선을 나타냅니다. BoxAndWhisker 차트에 평균선이 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 쓰기 **bool**. |
| void [set_ShowMeanMarkers](./set_showmeanmarkers/)(**bool**) override | 평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 마커가 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 쓰기 **bool**. |
| void [set_ShowOutlierPoints](./set_showoutlierpoints/)(**bool**) override | 이상치 포인트를 나타냅니다. BoxAndWhisker 차트에 이상치 포인트가 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 쓰기 **bool**. |
| void [set_Smooth](./set_smooth/)(**bool**) override | 곡선 스무딩을 나타냅니다. 라인 차트 또는 산점도 차트에서 곡선 스무딩이 켜져 있는 경우 true입니다. 라인 및 선으로 연결된 산점도 차트에만 적용됩니다. 쓰기 **bool**. |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | 이 시리즈의 유형을 반환합니다. 쓰기 [ChartType](../charttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문장의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 경비 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [IChartSeries](../ichartseries/)
* 클래스 [IDOMObject](../../aspose.slides/idomobject/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)