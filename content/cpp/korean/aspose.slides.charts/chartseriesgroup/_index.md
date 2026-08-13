---
title: ChartSeriesGroup
second_title: Aspose.Slides for C++ API 참조
description: 시리즈 그룹을 나타냅니다.
type: docs
weight: 300
url: /ko/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup 클래스


Series 그룹을 나타냅니다.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | 버블 차트에서 버블 크기 값을 표시하는 방식을 지정합니다. 읽기 [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | 버블 차트의 배율 인자를 지정합니다(기본 크기의 0%에서 300% 사이 가능). 읽기 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 상위 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | 지정된 인덱스의 그룹 내 차트 시리즈를 반환합니다. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 0%에서 90% 사이 가능). 읽기 **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | 첫 번째 파이 또는 도넛 차트 조각의 각도를 도(degree) 단위로 가져옵니다(위에서 시계 방향, 0도에서 360도). 읽기 **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | 3D 차트에서 데이터 시리즈 간 거리(마커 너비 대비 백분율)를 반환합니다. 읽기 **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | 막대 또는 컬럼 클러스터 사이의 간격을 막대 또는 컬럼 너비 대비 백분율로 지정합니다. 읽기 **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | 차트에 시리즈 라인이 있는 경우 true. 스택형 막대 및 OfPie 차트에 적용됩니다. 읽기 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | HiLowLines 형식을 지정합니다. HiLowLines는 HiLowClose, OpenHiLowClose, VolumeHiLowClose 및 VolumeOpenHiLowClose 차트 유형에 적용됩니다. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | 시리즈의 각 데이터 마커가 서로 다른 색을 갖도록 지정합니다. 읽기 **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | 2D 차트에서 막대와 컬럼이 겹치는 비율을 백분율(-100%~100%)로 지정합니다. |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | pie-of-pie 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대에 포함되는 데이터 포인트를 결정하는 방법을 지정합니다. 읽기 [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | 사용자 정의 분할이 있는 pie-of-pie 또는 bar-of-pie 차트에 대한 사용자 정의 분할 정보를 제공합니다. 인덱스로 지정된 두 번째 파이 또는 막대에 그릴 데이터 포인트를 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | 사용자 정의 분할이 있는 pie-of-pie 또는 bar-of-pie 차트에 대한 사용자 정의 분할 정보를 제공합니다. 두 번째 파이 또는 막대에 그릴 데이터 포인트를 포함합니다. 읽기 전용 [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | pie-of-pie 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대에 포함되는 데이터 포인트를 결정하는 데 사용할 값을 지정합니다. PieSplitBy 속성과 함께 사용됩니다. 읽기 **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | 이 그룹의 시리즈가 보조 축에 플롯되는지 여부를 나타냅니다. 읽기 전용 **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | pie-of-pie 차트 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대의 크기를 첫 번째 파이 크기의 백분율(5%~200%)로 지정합니다. 읽기 **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | 시리즈 컬렉션을 반환합니다. 읽기 전용 [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | 이 시리즈 그룹의 유형을 반환합니다. 읽기 전용 [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Line 또는 Stock 차트의 상승/하락 막대에 대한 접근을 제공합니다. 읽기 전용 [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | 지정된 인덱스의 요소를 가져옵니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금 기능입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|   [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | 버블 차트에서 버블 크기 값을 표시하는 방식을 지정합니다. 쓰기 [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | 버블 차트의 배율 인자를 지정합니다(기본 크기의 0%~300% 사이). 쓰기 **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 0%~90% 사이). 쓰기 **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | 첫 번째 파이 또는 도넛 차트 조각의 각도를 도(degree) 단위로 설정합니다(위에서 시계 방향, 0도~360도). 쓰기 **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | 3D 차트에서 데이터 시리즈 간 거리(마커 너비 대비 백분율)를 설정합니다. 쓰기 **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | 막대 또는 컬럼 클러스터 사이의 간격을 막대 또는 컬럼 너비 대비 백분율로 지정합니다. 쓰기 **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | 차트에 시리즈 라인이 있는 경우 true. 스택형 막대 및 OfPie 차트에 적용됩니다. 쓰기 **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | 시리즈의 각 데이터 마커가 서로 다른 색을 갖도록 지정합니다. 쓰기 **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | 2D 차트에서 막대와 컬럼이 겹치는 비율을 백분율(-100%~100%)로 지정합니다. |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | pie-of-pie 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대에 포함되는 데이터 포인트를 결정하는 방법을 지정합니다. 쓰기 [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | pie-of-pie 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대에 포함되는 데이터 포인트를 결정하는 데 사용할 값을 지정합니다. PieSplitBy 속성과 함께 사용됩니다. 쓰기 **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | pie-of-pie 차트 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대의 크기를 첫 번째 파이 크기의 백분율(5%~200%)로 지정합니다. 쓰기 **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제하는 기능을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 비고

1) ChartSeriesGroupCollection 클래스와 CombinableSeriesTypesGroup 열거형에 대한 요약 및 비고를 참조하십시오. 2) Series 그룹은 그룹의 각 Series에 공통인 일부 Series 속성("Series 그룹 속성")을 포함합니다. [ChartSeriesGroup](./) 클래스의 "Series 그룹 속성"은 읽기/쓰기 가능합니다. 각 "Series 그룹 속성"은 [ChartSeries](../chartseries/) 클래스에서 읽기 전용 투영을 가질 수 있습니다. 

## 참고

* 클래스 [IChartSeriesGroup](../ichartseriesgroup/)
* 클래스 [IDOMObject](../../aspose.slides/idomobject/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)