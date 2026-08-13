---
title: IDataLabel
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시리즈 레이블을 나타냅니다.
type: docs
weight: 937
url: /ko/aspose.slides.charts/idatalabel/
---
## IDataLabel 클래스

시리즈 레이블을 나타냅니다.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | TextFrameForOverriding을 매개변수 \"text\"의 텍스트로 초기화합니다. TextFrameForOverriding이 이미 초기화된 경우 단순히 텍스트를 변경합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동 소수점 비교를 흉내내어 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동 소수점 비교를 흉내내어 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | 차트 요소의 실제 높이를 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. 읽기 **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | 차트 요소의 실제 너비를 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. 읽기 **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | 차트 요소의 실제 x 위치(왼쪽)를 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. 읽기 **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | 차트 요소의 실제 상단을 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. 읽기 **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | 차트 요소의 상단을 차트 높이의 비율로 가져옵니다. 읽기 전용 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | 데이터 레이블 형식을 반환합니다. 읽기 전용 [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | 차트 요소의 높이를 차트 높이의 비율로 지정합니다. 읽기 **float**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | False는 데이터 레이블이 표시되지 않음을 의미하며 (따라서 모든 Show*-플래그(ShowValue 등)가 false) 입니다. 읽기 전용 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | 차트 요소의 오른쪽을 차트 너비의 비율로 가져옵니다. 읽기 전용 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 차트 텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | 풍부한 형식의 텍스트를 포함할 수 있습니다. 이 속성이 null이 아니면 이 형식화된 텍스트 값이 자동 생성 텍스트를 대체합니다. 자동 생성 텍스트는 데이터 레이블, 값 축의 표시 단위 레이블, 축 제목, 차트 제목, 트렌드라인 레이블의 암시적 속성입니다. 자동 생성 텍스트는 [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) 속성으로 서식이 지정됩니다. 읽기 전용 [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | 워크북 데이터 셀을 가져옵니다. IDataLabelFormat::get(set)_ShowLabelValueFromCell 속성이 true인 경우에 적용됩니다. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | 차트 요소의 너비를 차트 너비의 비율로 지정합니다. 읽기 **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | 차트 요소의 x 위치(왼쪽)를 차트 너비의 비율로 지정합니다. 읽기 **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | 차트 요소의 상단을 차트 높이의 비율로 지정합니다. 읽기 **float**. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | [DataLabelFormat](../datalabelformat/) 설정 또는 TextFrameForOverriding.Text 값에 따라 실제 레이블 텍스트를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 버전입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 버전입니다. |
| virtual void [Hide](./hide/)() | 모든 Show*-플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 숨깁니다. 이후 IsVisible는 false가 됩니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자의 유사 버전입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠급니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 버전입니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | 차트 요소의 높이를 차트 높이의 비율로 지정합니다. 쓰기 **float**. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | 워크북 데이터 셀을 설정합니다. IDataLabelFormat::get(set)_ShowLabelValueFromCell 속성이 true인 경우에 적용됩니다. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | 차트 요소의 너비를 차트 너비의 비율로 지정합니다. 쓰기 **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | 차트 요소의 x 위치(왼쪽)를 차트 너비의 비율로 지정합니다. 쓰기 **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | 차트 요소의 상단을 차트 높이의 비율로 지정합니다. 쓰기 **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 버전입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 구현하여 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [ILayoutable](../ilayoutable/)
* 클래스 [IOverridableText](../ioverridabletext/)
* 클래스 [IActualLayout](../iactuallayout/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)