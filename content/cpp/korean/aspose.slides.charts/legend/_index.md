---
title: Legend
second_title: Aspose.Slides for C++ API 레퍼런스
description: 차트 범례 속성을 나타냅니다.
type: docs
weight: 1262
url: /ko/aspose.slides.charts/legend/
---
## Legend 클래스

Represents chart's legend properties.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떠한 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동등하게 간주하는 C# 스타일의 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떠한 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동등하게 간주하는 C# 스타일의 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **float** [get_ActualHeight](./get_actualheight/)() override | 차트 요소의 실제 높이를 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. **float**를 읽습니다. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | 차트 요소의 실제 너비를 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. **float**를 읽습니다. |
| **float** [get_ActualX](./get_actualx/)() override | 차트 요소의 실제 x 위치(왼쪽)를 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. **float**를 읽습니다. |
| **float** [get_ActualY](./get_actualy/)() override | 차트 요소의 실제 상단을 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. **float**를 읽습니다. |
| **float** [get_Bottom](./get_bottom/)() override | 하단. 읽기 전용 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | 범례 항목을 가져옵니다. 읽기 전용 [ILegendEntryCollection](../ilegendentrycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | 지정된 인덱스의 차트 데이터 포인트에 해당하는 범례 항목 속성을 가져옵니다. 차트 유형이 bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie인 경우 데이터 포인트는 첫 번째 시리즈에서 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 범례의 형식을 반환합니다. 읽기 전용 [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | 범례의 높이를 차트 높이에 대한 비율로 반환합니다. **float**를 읽습니다. |
| **bool** [get_Overlay](./get_overlay/)() override | 다른 차트 요소가 범례와 겹치도록 허용할지 여부를 결정합니다. **bool**를 읽습니다. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | 차트에서 범례의 위치를 지정합니다. X, Y, Width, Heigt 속성의 NaN이 아닌 값은 이 속성의 효과를 대체합니다. [LegendPositionType](../legendpositiontype/)를 읽습니다. |
| **float** [get_Right](./get_right/)() override | 오른쪽. 읽기 전용 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 텍스트 형식. 읽기 전용 [IChartTextFormat](../icharttextformat/). |
| **float** [get_Width](./get_width/)() override | 범례의 너비를 차트 너비에 대한 비율로 반환합니다. **float**를 읽습니다. |
| **float** [get_X](./get_x/)() override | 범례의 x 좌표를 차트 너비에 대한 비율로 반환합니다. **float**를 읽습니다. |
| **float** [get_Y](./get_y/)() override | 범례의 y 좌표를 차트 높이에 대한 비율로 반환합니다. **float**를 읽습니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 버전입니다. 사용자 정의 객체의 해시를 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_Height](./set_height/)(**float**) override | 범례의 높이를 차트 높이에 대한 비율로 설정합니다. **float**를 씁니다. |
| void [set_Overlay](./set_overlay/)(**bool**) override | 다른 차트 요소가 범례와 겹치도록 허용할지 여부를 결정합니다. **bool**를 씁니다. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | 차트에서 범례의 위치를 지정합니다. X, Y, Width, Heigt 속성의 NaN이 아닌 값은 이 속성의 효과를 대체합니다. [LegendPositionType](../legendpositiontype/)를 씁니다. |
| void [set_Width](./set_width/)(**float**) override | 범례의 너비를 차트 너비에 대한 비율로 설정합니다. **float**를 씁니다. |
| void [set_X](./set_x/)(**float**) override | 범례의 x 좌표를 차트 너비에 대한 비율로 설정합니다. **float**를 씁니다. |
| void [set_Y](./set_y/)(**float**) override | 범례의 y 좌표를 차트 높이에 대한 비율로 설정합니다. **float**를 씁니다. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 템플릿 인수 n번째를 공유 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [DomObject](../../aspose.slides/domobject/)
* 클래스 [ILegend](../ilegend/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)