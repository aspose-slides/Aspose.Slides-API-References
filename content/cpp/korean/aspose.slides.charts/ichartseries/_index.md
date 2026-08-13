---
title: IChartSeries
second_title: Aspose.Slides for C++ API 참조
description: 차트 시리즈를 나타냅니다.
type: docs
weight: 820
url: /ko/aspose.slides.charts/ichartseries/
---
## IChartSeries 클래스


차트 시리즈를 나타냅니다.

```cpp
class IChartSeries : public Aspose::Slides::Charts::IChartComponent
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN을 서로 같은 것으로 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 여기서는 동일하게 취급됩니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN을 서로 같은 것으로 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 여기서는 동일하게 취급됩니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [ChartShapeType](../chartshapetype/) [get_Bar3DShape](./get_bar3dshape/)() | 3D 막대 차트 시리즈의 형태를 지정합니다. 이 속성의 값을 변경하면 시리즈 유형이 자동으로 변경될 수 있습니다. 읽기 [ChartShapeType](../chartshapetype/). |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | 버블 차트에서 버블 크기 값을 표시하는 방식을 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. ParentSeriesGroup 속성을 사용하여 상위 시리즈 그룹에 접근하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeRepresentation() 읽기/쓰기 속성을 사용하십시오. |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | 버블 차트의 배율을 지정합니다(기본 크기의 0%~300% 사이). 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. ParentSeriesGroup 속성을 사용하여 상위 시리즈 그룹에 접근하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeScale() 읽기/쓰기 속성을 사용하십시오. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_DataPoint](./get_datapoint/)(**int32_t**) | 지정된 인덱스에 있는 이 시리즈의 데이터 포인트를 반환합니다. |
| virtual **int32_t** [get_DataPoint](./get_datapoint/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointCollection](../ichartdatapointcollection/)\> [get_DataPoints](./get_datapoints/)() | 이 시리즈의 데이터 포인트 컬렉션을 반환합니다. 읽기 전용 [IChartDataPointCollection](../ichartdatapointcollection/). |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | 도넛 차트에서 구멍의 크기를 지정합니다(플롯 영역 크기의 10%~90% 사이). 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. ParentSeriesGroup 속성을 사용하여 상위 시리즈 그룹에 접근하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_DoughnutHoleSize() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsXFormat](./get_errorbarsxformat/)() | X 방향을 가진 시리즈의 ErrorBars를 나타냅니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsYFormat](./get_errorbarsyformat/)() | Y 방향을 가진 시리즈의 ErrorBars를 나타냅니다. |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | 열린 파이 조각이 파이 차트 중심으로부터 떨어진 거리를 파이 직경의 백분율로 나타냅니다. 읽기 **int32_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | 첫 번째 파이 또는 도넛 차트 조각의 각도를 도(degree) 단위로 지정합니다(위에서 시계 방향, 0~360도). 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. ParentSeriesGroup 속성을 사용하여 상위 시리즈 그룹에 접근하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_FirstSliceAngle() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 시리즈의 형식을 반환합니다. 읽기 전용 [IFormat](../iformat/). |
| virtual **int32_t** [get_GapDepth](./get_gapdepth/)() | 3D 차트에서 마커 너비의 백분율로 데이터 시리즈 간 거리를 반환합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. ParentSeriesGroup 속성을 사용하여 상위 시리즈 그룹에 접근하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapDepth() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **int32_t**. |
| virtual **int32_t** [get_GapWidth](./get_gapwidth/)() | 막대 또는 열 클러스터 간 간격을 막대 또는 열 너비의 백분율로 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. ParentSeriesGroup 속성을 사용하여 상위 시리즈 그룹에 접근하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapWidth() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **int32_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | 이 시리즈 및 관련 시리즈에 시리즈 라인이 있는지 여부를 결정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. ParentSeriesGroup 속성을 사용하여 상위 시리즈 그룹에 접근하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_HasSeriesLines() 읽기/쓰기 속성을 사용하십시오. 시리즈 라인 형식은 ParentSeriesGroup.SeriesLinesFormat 속성을 사용하십시오. 읽기 전용 **bool**. |
| virtual **bool** [get_HasUpDownBars](./get_hasupdownbars/)() | 라인 또는 주식 차트에 상승/하강 막대가 있는지 여부를 결정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. ParentSeriesGroup 속성을 사용하여 상위 시리즈 그룹에 접근하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars()->get(set)_HasUpDownBars() 읽기/쓰기 속성을 사용하십시오. 상승/하강 막대 형식은 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars() 속성을 사용하십시오. 읽기 전용 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_InvertedSolidFillColor](./get_invertedsolidfillcolor/)() | 시리즈에 대한 역색 고정 색상을 지정합니다. 색상 설정을 적용하려면 시리즈 형식의 FillType을 [FillType::Solid](../../aspose.slides/filltype/)로 설정하십시오. 읽기 [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | 값이 음수인 경우 막대, 열 또는 버블 시리즈가 색상을 반전하도록 지정합니다. 읽기 **bool**. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | 시리즈의 각 데이터 마커에 서로 다른 색상이 지정되는지 여부를 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. ParentSeriesGroup 속성을 사용하여 상위 시리즈 그룹에 접근하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_IsColorVaried() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)(**int32_t**) | 지정된 인덱스에 있는 이 시리즈의 데이터 포인트에 대한 데이터 레이블을 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelCollection](../idatalabelcollection/)\> [get_Labels](./get_labels/)() | 시리즈의 레이블을 반환합니다. 읽기 전용 [IDataLabelCollection](../idatalabelcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | 시리즈 마커를 반환합니다. 읽기 전용 [IMarker](../imarker/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringChartValue](../istringchartvalue/)\> [get_Name](./get_name/)() | 시리즈 이름을 반환합니다. 읽기 전용 [IStringChartValue](../istringchartvalue/). |
| virtual [System::String](../../system/string/) [get_NumberFormatOfBubbleSizes](./get_numberformatofbubblesizes/)() | 시리즈 버블 크기에 대한 숫자 형식을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_NumberFormatOfValues](./get_numberformatofvalues/)() | 시리즈 값에 대한 숫자 형식을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_NumberFormatOfXValues](./get_numberformatofxvalues/)() | 시리즈 x 값에 대한 숫자 형식을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_NumberFormatOfYValues](./get_numberformatofyvalues/)() | 시리즈 y 값에 대한 숫자 형식을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual **int32_t** [get_Order](./get_order/)() | 시리즈의 순서를 반환합니다. 읽기 **int32_t**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | 2D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%~100%)로 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성이며, 상위 그룹 속성의 투영이므로 읽기 전용입니다. 값을 변경하려면 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_Overlap() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **int8_t**. |
| virtual [ParentLabelLayoutType](../parentlabellayouttype/) [get_ParentLabelLayout](./get_parentlabellayout/)() | 상위 카테고리 레이블의 레이아웃을 나타냅니다. Treemap 차트에만 적용됩니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](./)\> [get_ParentSeries](./get_parentseries/)(**int32_t**) | 지정된 인덱스에 있는 상위 시리즈 그룹의 차트 시리즈를 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_ParentSeriesGroup](./get_parentseriesgroup/)() | 상위 시리즈 그룹을 반환합니다. 읽기 전용 [IChartSeriesGroup](../ichartseriesgroup/). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. ParentSeriesGroup 속성을 사용하여 상위 시리즈 그룹에 접근하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitBy() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | 사용자 지정 분할이 있는 파이-오브-파이 또는 바-오브-파이 차트에 대한 사용자 지정 분할 정보를 반환합니다. 지정된 인덱스에 있는 두 번째 파이 또는 바에 그려질 데이터 포인트를 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | 사용자 지정 분할이 있는 파이-오브-파이 또는 바-오브-파이 차트에 대한 사용자 지정 분할 정보를 반환합니다. 두 번째 파이 또는 바에 그려질 데이터 포인트를 포함합니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 읽기 전용 [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용되는 값을 지정합니다. PieSplitBy 속성과 함께 사용됩니다. 이 속성은 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. ParentSeriesGroup 속성을 사용하여 상위 시리즈 그룹에 접근하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitPosition() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | 이 시리즈가 두 번째 값 축에 표시되는지 여부를 나타냅니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [QuartileMethodType](../quartilemethodtype/) [get_QuartileMethod](./get_quartilemethod/)() | 사분위수 방법을 나타냅니다. BoxAndWhisker 차트에만 적용됩니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | 이 시리즈와 관련된 범례 항목을 나타냅니다. 읽기 전용 [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | 두 번째 파이 또는 바(파이-파이 차트 또는 바-파이 차트)의 크기를 첫 번째 파이 크기의 백분율로 지정합니다(5%에서 200% 사이 가능). 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. ParentSeriesGroup 속성을 사용하여 상위 시리즈 그룹에 접근하십시오. 값 변경을 위해 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_SecondPieSize() 읽기/쓰기 속성을 사용하십시오. 읽기 전용 **uint16_t**. |
| virtual **bool** [get_ShowConnectorLines](./get_showconnectorlines/)() | 연결 선을 나타냅니다. Waterfall 차트에만 적용됩니다. |
| virtual **bool** [get_ShowInnerPoints](./get_showinnerpoints/)() | 내부 포인트를 나타냅니다. BoxAndWhisker 차트에 내부 포인트가 표시될 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기 **bool**. |
| virtual **bool** [get_ShowMeanLine](./get_showmeanline/)() | 평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 선이 표시될 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기 **bool**. |
| virtual **bool** [get_ShowMeanMarkers](./get_showmeanmarkers/)() | 평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 마커가 표시될 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기 **bool**. |
| virtual **bool** [get_ShowOutlierPoints](./get_showoutlierpoints/)() | 이상값 포인트를 나타냅니다. BoxAndWhisker 차트에 이상값 포인트가 표시될 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual **bool** [get_Smooth](./get_smooth/)() | 곡선 스무딩을 나타냅니다. 선 차트 또는 산점도 차트에서 곡선 스무딩이 켜져 있는 경우 true입니다. 선 차트 및 선으로 연결된 산점도 차트에만 적용됩니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITrendline](../itrendline/)\> [get_TrendLine](./get_trendline/)(**int32_t**) | 지정된 인덱스의 추세선을 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITrendlineCollection](../itrendlinecollection/)\> [get_TrendLines](./get_trendlines/)() | 시리즈 추세선 컬렉션 읽기 전용 [ITrendlineCollection](../itrendlinecollection/). |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | 이 시리즈의 유형을 반환합니다. 읽기 [ChartType](../charttype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticSeriesColor](./getautomaticseriescolor/)() | 시리즈 인덱스와 차트 스타일을 기반으로 시리즈의 자동 색상을 반환합니다. FillType이 NotDefined인 경우 기본적으로 이 색상이 사용됩니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해시 생성을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문구의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 형식 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_Bar3DShape](./set_bar3dshape/)([ChartShapeType](../chartshapetype/)) | 3-D 막대 차트 시리즈의 모양을 지정합니다. 이 속성 값을 변경하면 시리즈의 Type이 자동으로 변경될 수 있습니다. 쓰기 [ChartShapeType](../chartshapetype/). |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | 열린 파이 조각이 파이 차트 중심으로부터의 거리를 파이 지름의 백분율로 나타냅니다. 쓰기 **int32_t**. |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | 값이 음수인 경우 바, 열 또는 버블 시리즈가 색상을 반전하도록 지정합니다. 쓰기 **bool**. |
| virtual void [set_NumberFormatOfBubbleSizes](./set_numberformatofbubblesizes/)([System::String](../../system/string/)) | 시리즈 버블 크기의 숫자 형식을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_NumberFormatOfValues](./set_numberformatofvalues/)([System::String](../../system/string/)) | 시리즈 값의 숫자 형식을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_NumberFormatOfXValues](./set_numberformatofxvalues/)([System::String](../../system/string/)) | 시리즈 x 값의 숫자 형식을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_NumberFormatOfYValues](./set_numberformatofyvalues/)([System::String](../../system/string/)) | 시리즈 y 값의 숫자 형식을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_Order](./set_order/)(**int32_t**) | 시리즈의 순서를 반환합니다. 쓰기 **int32_t**. |
| virtual void [set_ParentLabelLayout](./set_parentlabellayout/)([ParentLabelLayoutType](../parentlabellayouttype/)) | 상위 카테고리 레이블의 레이아웃을 나타냅니다. Treemap 차트에만 적용됩니다. |
| virtual void [set_PlotOnSecondAxis](./set_plotonsecondaxis/)(**bool**) | 이 시리즈가 두 번째 값 축에 플롯되는지 여부를 나타냅니다. 쓰기 **bool**. |
| virtual void [set_QuartileMethod](./set_quartilemethod/)([QuartileMethodType](../quartilemethodtype/)) | 사분위수 방법을 나타냅니다. BoxAndWhisker 차트에만 적용됩니다. |
| virtual void [set_ShowConnectorLines](./set_showconnectorlines/)(**bool**) | 연결 선을 나타냅니다. Waterfall 차트에만 적용됩니다. |
| virtual void [set_ShowInnerPoints](./set_showinnerpoints/)(**bool**) | 내부 포인트를 나타냅니다. BoxAndWhisker 차트에 내부 포인트가 표시될 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 쓰기 **bool**. |
| virtual void [set_ShowMeanLine](./set_showmeanline/)(**bool**) | 평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 선이 표시될 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 쓰기 **bool**. |
| virtual void [set_ShowMeanMarkers](./set_showmeanmarkers/)(**bool**) | 평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 마커가 표시될 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 쓰기 **bool**. |
| virtual void [set_ShowOutlierPoints](./set_showoutlierpoints/)(**bool**) | 이상값 포인트를 나타냅니다. BoxAndWhisker 차트에 이상값 포인트가 표시될 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다. 쓰기 **bool**. |
| virtual void [set_Smooth](./set_smooth/)(**bool**) | 곡선 스무딩을 나타냅니다. 선 차트 또는 산점도 차트에서 곡선 스무딩이 켜져 있는 경우 true입니다. 선 차트 및 선으로 연결된 산점도 차트에만 적용됩니다. 쓰기 **bool**. |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | 이 시리즈의 유형을 반환합니다. 쓰기 [ChartType](../charttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유 대신)로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참조

* 클래스 [IChartComponent](../ichartcomponent/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)