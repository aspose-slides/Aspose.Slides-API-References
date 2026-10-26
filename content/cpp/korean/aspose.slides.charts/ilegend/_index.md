---
title: ILegend
second_title: Aspose.Slides for C++ API 레퍼런스
description: 차트의 범례 속성을 나타냅니다.
type: docs
weight: 1080
url: /ko/aspose.slides.charts/ilegend/
---
## ILegend 클래스


차트의 범례 속성을 나타냅니다.

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# 스타일 부동 소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 같다고 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# 스타일 부동 소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 같다고 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | 차트 요소의 실제 높이를 지정합니다. 실제 값을 얻으려면 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 먼저 호출하십시오. 읽기 전용 **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | 차트 요소의 실제 너비를 지정합니다. 실제 값을 얻으려면 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 먼저 호출하십시오. 읽기 전용 **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | 차트 요소의 실제 x 위치(왼쪽)를 차트 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 먼저 호출하십시오. 읽기 전용 **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | 차트 요소의 실제 상단을 차트 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 먼저 호출하십시오. 읽기 전용 **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | 차트 높이의 비율로 차트 요소의 상단을 가져옵니다. 읽기 전용 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | 범례 항목을 가져옵니다. 읽기 전용 [ILegendEntryCollection](../ilegendentrycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | 지정된 인덱스의 차트 데이터 포인트에 해당하는 범례 항목의 속성을 가져옵니다. 차트 유형이 막대-파이, 분리 파이, 3D 분리 파이, 파이, 3D 파이, 파이-파이인 경우, 데이터 포인트는 첫 번째 시리즈에서 가져옵니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 범례의 형식을 반환합니다. 읽기 전용 [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | 차트 높이의 비율로 차트 요소의 높이를 지정합니다. 읽기 **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | 다른 차트 요소가 범례와 겹치도록 허용될지 여부를 결정합니다. 읽기 **bool**. |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | 차트에서 범례의 위치를 지정합니다. X, Y, Width, Heigt 속성의 NaN이 아닌 값은 이 속성의 효과를 무시합니다. 읽기 [LegendPositionType](../legendpositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | 차트 너비의 비율로 차트 요소의 오른쪽을 가져옵니다. 읽기 전용 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 차트 텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../icharttextformat/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | 차트 너비의 비율로 차트 요소의 너비를 지정합니다. 읽기 **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | 차트 너비의 비율로 차트 요소의 x 위치(왼쪽)를 지정합니다. 읽기 **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | 차트 높이의 비율로 차트 요소의 상단을 지정합니다. 읽기 **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시를 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 대상 유형으로 설명된 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | 차트 높이의 비율로 차트 요소의 높이를 지정합니다. 쓰기 **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | 다른 차트 요소가 범례와 겹치도록 허용될지 여부를 결정합니다. 쓰기 **bool**. |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | 차트에서 범례의 위치를 지정합니다. X, Y, Width, Height 속성의 NaN이 아닌 값은 이 속성의 효과를 무시합니다. 쓰기 [LegendPositionType](../legendpositiontype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | 차트 너비의 비율로 차트 요소의 너비를 지정합니다. 쓰기 **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | 차트 너비의 비율로 차트 요소의 x 위치(왼쪽)를 지정합니다. 쓰기 **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | 차트 높이의 비율로 차트 요소의 상단을 지정합니다. 쓰기 **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참조

* 클래스 [ILayoutable](../ilayoutable/)
* 클래스 [IFormattedTextContainer](../iformattedtextcontainer/)
* 클래스 [IActualLayout](../iactuallayout/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)