---
title: DataLabel
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시리즈 레이블을 나타냅니다.
type: docs
weight: 365
url: /ko/aspose.slides.charts/datalabel/
---
## DataLabel 클래스

시리즈 레이블을 나타냅니다.

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## 메서드

| Method | 설명 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | 텍스트 매개변수 "text"를 사용하여 TextFrameForOverriding을 초기화합니다. TextFrameForOverriding이 이미 초기화된 경우 텍스트만 변경합니다. |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | [DataLabel](./) 클래스의 새 인스턴스를 생성합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN이 동일하다고 간주되는 C#-style 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN이 동일하다고 간주되는 C#-style 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **float** [get_ActualHeight](./get_actualheight/)() override | 차트 요소의 실제 높이를 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. 읽기 **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | 차트 요소의 실제 너비를 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. 읽기 **float**. |
| **float** [get_ActualX](./get_actualx/)() override | 차트 요소의 실제 x 위치(왼쪽)를 차트 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. 읽기 **float**. |
| **float** [get_ActualY](./get_actualy/)() override | 차트 요소의 실제 상단을 차트 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 먼저 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 메서드를 호출하십시오. 읽기 **float**. |
| **float** [get_Bottom](./get_bottom/)() override | 하단. 읽기 전용 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 부모 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | 데이터 레이블 형식을 반환합니다. 읽기 전용 [IDataLabelFormat](../idatalabelformat/). |
| **float** [get_Height](./get_height/)() override | 차트 높이의 비율로 제목의 높이를 반환합니다. 읽기 **float**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | False는 데이터 레이블이 표시되지 않음을 의미합니다(따라서 모든 Show* 플래그(ShowValue 등)가 false가 됩니다). 읽기 전용 **bool**. |
| **float** [get_Right](./get_right/)() override | 오른쪽. 읽기 전용 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | 리치 형식 텍스트를 포함할 수 있습니다. 이 속성이 null이 아니면 이 형식 텍스트 값이 데이터 레이블의 자동 생성 텍스트를 대체합니다. 데이터 레이블의 자동 생성 텍스트는 ShowSeriesName, ShowValue 등 속성에 의해 관리되고 TextFormatManager.TextFormat 속성으로 서식이 지정된 텍스트를 의미합니다. 읽기 전용 [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | 워크북 데이터 셀을 가져옵니다. IDataLabelFormat::get(set)_ShowLabelValueFromCell 속성이 true인 경우 적용됩니다. |
| **float** [get_Width](./get_width/)() override | 차트 너비의 비율로 제목의 너비를 반환합니다. 읽기 **float**. |
| **float** [get_X](./get_x/)() override | 차트 너비의 비율로 제목의 x 좌표를 반환합니다. 읽기 **float**. |
| **float** [get_Y](./get_y/)() override | 차트 높이의 비율로 제목의 y 좌표를 반환합니다. 읽기 **float**. |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | [DataLabelFormat](../datalabelformat/) 설정 또는 [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text() 값을 기반으로 실제 레이블 텍스트를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| void [Hide](./hide/)() override | 모든 Show* 플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 숨깁니다. 이 후 IsVisible는 false가 됩니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_Height](./set_height/)(**float**) override | 차트 높이의 비율로 제목의 높이를 설정합니다. 쓰기 **float**. |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | 워크북 데이터 셀을 설정합니다. IDataLabelFormat::get(set)_ShowLabelValueFromCell 속성이 true인 경우 적용됩니다. |
| void [set_Width](./set_width/)(**float**) override | 차트 너비의 비율로 제목의 너비를 설정합니다. 쓰기 **float**. |
| void [set_X](./set_x/)(**float**) override | 차트 너비의 비율로 제목의 x 좌표를 설정합니다. 쓰기 **float**. |
| void [set_Y](./set_y/)(**float**) override | 차트 높이의 비율로 제목의 y 좌표를 설정합니다. 쓰기 **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구성을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IDataLabel](../idatalabel/)
* 클래스 [IDOMObject](../../aspose.slides/idomobject/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)