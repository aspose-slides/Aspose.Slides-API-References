---
title: IChartSeriesGroup
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시리즈 그룹을 나타냅니다.
type: docs
weight: 846
url: /ko/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup 클래스

Represents group of series.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C#-style 부동 소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C#-style 부동 소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | 버블 차트에서 버블 크기 값을 표시하는 방식을 지정합니다. [BubbleSizeRepresentationType](../bubblesizerepresentationtype/)를 읽으세요. |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | 버블 차트의 스케일 계수를 지정합니다(기본 크기의 0~300%). **int32_t**를 읽으세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | 지정된 인덱스에 있는 그룹의 차트 시리즈를 반환합니다. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10~90%). **uint8_t**를 읽으세요. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | 첫 번째 파이 또는 도넛 차트 조각의 각도를 degree 단위로 가져옵니다(위에서 시계 방향, 0~360도). **uint16_t**를 읽으세요. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | 3D 차트에서 데이터 시리즈 간의 거리를 마커 너비의 백분율로 반환합니다. **uint16_t**를 읽으세요. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | 막대 또는 열 클러스터 간의 간격을 막대 또는 열 너비의 백분율로 지정합니다. **uint16_t**를 읽으세요. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | 차트에 시리즈 라인이 있으면 true입니다. 스택형 막대 및 OfPie 차트에 적용됩니다. **bool**를 읽으세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | HiLowLines 형식을 지정합니다. HiLowLines는 HiLowClose, OpenHiLowClose, VolumeHiLowClose 및 VolumeOpenHiLowClose 차트 유형에 적용됩니다. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | 시리즈의 각 데이터 마커에 다른 색상을 지정합니다. **bool**를 읽으세요. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | 2D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%~100%)로 지정합니다. |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | pie-of-pie 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대에 해당하는 데이터 포인트를 결정하는 방법을 지정합니다. [PieSplitType](../piesplittype/)를 읽으세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | 사용자 정의 분할이 있는 pie-of-pie 또는 bar-of-pie 차트의 커스텀 분할 정보를 제공합니다. 인덱스로 두 번째 파이 또는 막대에 그려질 데이터 포인트를 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | 사용자 정의 분할이 있는 pie-of-pie 또는 bar-of-pie 차트의 커스텀 분할 정보를 제공합니다. 두 번째 파이 또는 막대에 그려질 데이터 포인트를 포함합니다. 읽기 전용 [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | 두 번째 파이 또는 막대에 해당하는 데이터 포인트를 결정하는 데 사용되는 값을 지정합니다. PieSplitBy 속성과 함께 사용됩니다. **double**를 읽으세요. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | 이 그룹의 시리즈가 보조 축에 플롯되는지 여부를 나타냅니다. 읽기 전용 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | 첫 번째 파이의 크기를 기준으로 두 번째 파이 또는 막대의 크기를 백분율(5~200%)로 지정합니다. **uint16_t**를 읽으세요. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | 차트 시리즈의 읽기 전용 컬렉션을 반환합니다. 읽기 전용 [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | 이 시리즈 그룹의 타입을 반환합니다. 읽기 전용 [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | Line 또는 Stock 차트의 상/하 막대에 대한 접근을 제공합니다. 읽기 전용 [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조에 의해 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조에 의해 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | 버블 차트에서 버블 크기 값이 표시되는 방식을 지정합니다. [BubbleSizeRepresentationType](../bubblesizerepresentationtype/)에 기록합니다. |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | 버블 차트의 스케일 계수를 지정합니다(기본 크기의 0~300%). **int32_t**에 기록합니다. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10~90%). **uint8_t**에 기록합니다. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | 첫 번째 파이 또는 도넛 차트 조각의 각도를 degree 단위로 설정합니다(위에서 시계 방향, 0~360도). **uint16_t**에 기록합니다. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | 마커 너비의 백분율로 3D 차트의 데이터 시리즈 간 거리를 설정합니다. **uint16_t**에 기록합니다. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | 막대 또는 열 클러스터 간의 간격을 막대 또는 열 너비의 백분율로 지정합니다. **uint16_t**에 기록합니다. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | 차트에 시리즈 라인이 있으면 true입니다. 스택형 막대 및 OfPie 차트에 적용됩니다. **bool**에 기록합니다. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | 시리즈의 각 데이터 마커에 다른 색상을 지정합니다. **bool**에 기록합니다. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | 2D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%~100%)로 지정합니다. |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | pie-of-pie 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대에 해당하는 데이터 포인트를 결정하는 방법을 지정합니다. [PieSplitType](../piesplittype/)에 기록합니다. |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | 두 번째 파이 또는 막대에 해당하는 데이터 포인트를 결정하는 데 사용되는 값을 지정합니다. PieSplitBy 속성과 함께 사용됩니다. **double**에 기록합니다. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | 두 번째 파이 또는 막대의 크기를 첫 번째 파이의 크기를 기준으로 백분율(5~200%)로 지정합니다. **uint16_t**에 기록합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 shared 대신 weak 포인터로 설정합니다. 컨테이너의 포인터를 weak 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 비고

1) ChartSeriesGroupCollection 클래스 및 CombinableSeriesTypesGroup 열거형에 대한 요약 및 비고를 참조하십시오. 2) 시리즈 그룹은 그룹 내 각 시리즈에 공통된 일부 시리즈 속성을 포함합니다("시리즈 그룹 속성"). [ChartSeriesGroup](../chartseriesgroup/) 클래스의 "시리즈 그룹 속성"은 읽기/쓰기 가능합니다. 각 "시리즈 그룹 속성"은 [ChartSeries](../chartseries/) 클래스에서 읽기 전용 투영을 가질 수 있습니다.

## 참고

* 클래스 [IChartComponent](../ichartcomponent/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)