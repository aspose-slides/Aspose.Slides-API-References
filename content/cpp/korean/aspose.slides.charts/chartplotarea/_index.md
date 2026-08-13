---
title: ChartPlotArea
second_title: C++용 Aspose.Slides API 참조
description: 차트가 플롯되어야 하는 사각형을 나타냅니다.
type: docs
weight: 248
url: /ko/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea 클래스

차트가 플롯되어야 하는 사각형을 나타냅니다.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| **float** [get_ActualHeight](./get_actualheight/)() override | 차트 요소의 실제 높이를 지정합니다. 실제 값을 얻으려면 먼저 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. **float**을 읽습니다. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | 차트 요소의 실제 너비를 지정합니다. 실제 값을 얻으려면 먼저 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. **float**을 읽습니다. |
| **float** [get_ActualX](./get_actualx/)() override | 차트 요소의 x 위치(왼쪽)를 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 먼저 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. **float**을 읽습니다. |
| **float** [get_ActualY](./get_actualy/)() override | 차트 요소의 실제 상단을 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 먼저 메서드 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)를 호출하십시오. **float**을 읽습니다. |
| **float** [get_Bottom](./get_bottom/)() override | 하단. 읽기 전용 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). 읽기 전용 [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 플롯 영역의 형식을 반환합니다. 읽기 전용 [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | 플롯 영역 경계 상자의 높이를 차트 높이의 비율(0~1)로 반환합니다. **float**을 읽습니다. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | 위치 계산 방법을 정의합니다: true – 자동으로 계산; X, Y, Width, Height 속성으로 정의됩니다. 읽기 전용 **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | 플롯 영역 레이아웃이 수동으로 정의된 경우, 이 속성은 플롯 영역을 내부(축 및 축 레이블 제외) 또는 외부(축 및 축 레이블 포함) 중 어디에 배치할지 지정합니다. [LayoutTargetType](../layouttargettype/)을(를) 읽습니다. |
| **float** [get_Right](./get_right/)() override | 오른쪽. 읽기 전용 **float**. |
| **float** [get_Width](./get_width/)() override | 플롯 영역 경계 상자의 너비를 차트 너비의 비율(0~1)로 반환합니다. **float**을 읽습니다. |
| **float** [get_X](./get_x/)() override | 플롯 영역 경계 상자의 왼쪽 상단 모서리의 x 좌표를 차트 너비의 비율(0~1)로 반환합니다. **float**을 읽습니다. |
| **float** [get_Y](./get_y/)() override | 플롯 영역 경계 상자의 왼쪽 상단 모서리의 y 좌표를 차트 높이의 비율(0~1)로 반환합니다. **float**을 읽습니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/)의 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_Height](./set_height/)(**float**) override | 플롯 영역 경계 상자의 높이를 차트 높이의 비율(0~1)로 설정합니다. **float**을 씁니다. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | 플롯 영역 레이아웃이 수동으로 정의된 경우, 이 속성은 플롯 영역을 내부(축 및 축 레이블 제외) 또는 외부(축 및 축 레이블 포함) 중 어디에 배치할지 지정합니다. [LayoutTargetType](../layouttargettype/)을 씁니다. |
| void [set_Width](./set_width/)(**float**) override | 플롯 영역 경계 상자의 너비를 차트 너비의 비율(0~1)로 설정합니다. **float**을 씁니다. |
| void [set_X](./set_x/)(**float**) override | 플롯 영역 경계 상자의 왼쪽 상단 모서리의 x 좌표를 차트 너비의 비율(0~1)로 설정합니다. **float**을 씁니다. |
| void [set_Y](./set_y/)(**float**) override | 플롯 영역 경계 상자의 왼쪽 상단 모서리의 y 좌표를 차트 높이의 비율(0~1)로 설정합니다. **float**을 씁니다. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n번째 템플릿 인자를 공유 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운트 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [DomObject](../../aspose.slides/domobject/)
* 클래스 [IChartPlotArea](../ichartplotarea/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)