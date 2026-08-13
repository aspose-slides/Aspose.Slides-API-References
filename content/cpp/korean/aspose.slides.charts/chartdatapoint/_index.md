---
title: ChartDataPoint
second_title: Aspose.Slides for C++ API 참조
description: 시리즈 데이터 포인트를 나타냅니다.
type: docs
weight: 144
url: /ko/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint 클래스

시리즈 데이터 포인트를 나타냅니다.

```cpp
class ChartDataPoint : public Aspose::Slides::Charts::IChartDataPoint,
                       public Aspose::Slides::IDOMObject
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| **float** [get_ActualHeight](./get_actualheight/)() override | 차트 요소의 실제 높이를 지정합니다. 실제 값을 얻으려면 먼저 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. 읽기 **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | 차트 요소의 실제 너비를 지정합니다. 실제 값을 얻으려면 먼저 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. 읽기 **float**. |
| **float** [get_ActualX](./get_actualx/)() override | 차트 요소의 실제 x 위치(왼쪽)를 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 먼저 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. 읽기 **float**. |
| **float** [get_ActualY](./get_actualy/)() override | 차트 요소의 실제 상단을 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 먼저 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. 읽기 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() override | BubbleSize. 읽기 전용 [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() override | 차트 데이터 포인트의 색상 값을 반환합니다. 지도 차트에서 사용됩니다. 읽기 전용 [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) override | 지정된 인덱스에 있는 데이터 포인트 수준을 반환합니다. Treeamp 및 Sunburst 시리즈에 적용됩니다. 데이터 포인트 수준 인덱스는 0부터 시작합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() override | 데이터 포인트 수준의 컨테이너를 반환합니다. Treeamp 및 Sunburst 시리즈에 적용됩니다. 데이터 포인트 수준 인덱스는 0부터 시작합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() override | Custom 값 유형의 경우 시리즈 오류 막대 값을 나타냅니다. 읽기 전용 [IErrorBarsCustomValues](../ierrorbarscustomvalues/). |
| **int32_t** [get_Explosion](./get_explosion/)() override | 파이의 중심으로부터 데이터 포인트가 이동해야 하는 양을 지정합니다. 읽기 **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 서식 속성을 나타냅니다. 읽기 [IFormat](../iformat/). |
| **uint32_t** [get_Index](./get_index/)() override | 부모의 자식 컬렉션 중 어느 항목에 이 데이터 포인트가 적용되는지 결정합니다. 읽기 **uint32_t**. |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | 값이 음수인 경우 데이터 포인트가 색상을 반전하도록 지정합니다. 읽기 **bool**. |
| **bool** [get_IsBubble3D](./get_isbubble3d/)() override | 버블에 3D 효과가 적용되도록 지정합니다. 읽기 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() override | 라벨. 읽기 전용 [IDataLabel](../idatalabel/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | 데이터 마커를 지정합니다. 읽기 전용 [IMarker](../imarker/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | 다음 목록에 있는 차트 유형인 경우 해당 범례 항목의 속성: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). 읽기 전용 [ILegendEntryProperties](../ilegendentryproperties/). |
| **bool** [get_SetAsTotal](./get_setastotal/)() override | 데이터 포인트를 총합으로 설정합니다. Waterfall 시리즈 유형에만 적용됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() override | 차트 데이터 포인트의 크기 값을 반환합니다. Treemap 및 Sunburst 차트에서 사용됩니다. 읽기 전용 [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() override | 값. 읽기 전용 [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() override | X값. 읽기 전용 [IStringOrDoubleChartValue](../istringordoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() override | Y값. 읽기 전용 [IDoubleChartValue](../idoublechartvalue/). |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() override | 시리즈 인덱스, 데이터 포인트 인덱스, ParentSeriesGroup.IsColorVaried 속성 및 차트 스타일을 기반으로 데이터 포인트의 자동 색상을 반환합니다. FillType이 NotDefined인 경우 기본적으로 이 색상이 사용됩니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사품입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사품입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자의 유사품입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠급니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사품입니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| void [Remove](./remove/)() override | 차트 시리즈에서 DataPoint를 제거합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | 파이의 중심으로부터 데이터 포인트가 이동해야 하는 양을 지정합니다. 쓰기 **int32_t**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | 서식 속성을 나타냅니다. 쓰기 [IFormat](../iformat/). |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | 값이 음수인 경우 데이터 포인트가 색상을 반전하도록 지정합니다. 쓰기 **bool**. |
| void [set_IsBubble3D](./set_isbubble3d/)(**bool**) override | 버블에 3D 효과가 적용되도록 지정합니다. 쓰기 **bool**. |
| void [set_SetAsTotal](./set_setastotal/)(**bool**) override | 데이터 포인트를 총합으로 설정합니다. Waterfall 시리즈 유형에만 적용됩니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사품입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [IChartDataPoint](../ichartdatapoint/)
* 클래스 [IDOMObject](../../aspose.slides/idomobject/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)