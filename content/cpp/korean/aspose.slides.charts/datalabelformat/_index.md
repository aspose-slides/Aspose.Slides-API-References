---
title: DataLabelFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: DataLabel에 대한 서식 옵션을 나타냅니다.
type: docs
weight: 391
url: /ko/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat 클래스

[DataLabel](../datalabel/)에 대한 형식 옵션을 나타냅니다.

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## 메서드

| Method | Description |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 지정된 객체와 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 포함 NaN과도 같지 않지만, 두 NaN을 동일하게 취급하는 C# 스타일의 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 포함 NaN과도 같지 않지만, 두 NaN을 동일하게 취급하는 C# 스타일의 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 데이터 레이블의 형식을 나타냅니다. 읽기 전용 [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | 읽기 **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | DataLabels 객체의 형식 문자열을 나타냅니다. 읽기 [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Parent_Immediate 객체를 반환합니다. 읽기 전용 [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 부모 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)를 반환합니다. 읽기 전용 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | 데이터 레이블의 위치를 나타냅니다. 읽기 [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | 차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. 읽기 [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | 지정된 차트의 데이터 레이블 버블 크기 값 표시 동작을 나타냅니다. True이면 버블 크기 값을 표시하고, False이면 숨깁니다. 읽기 **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | 지정된 차트의 데이터 레이블 카테고리 이름 표시 동작을 나타냅니다. True이면 차트의 데이터 레이블에 카테고리 이름을 표시하고, False이면 숨깁니다. 읽기 **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | 지정된 차트의 데이터 레이블이 데이터 호출(callout)로 표시될지 데이터 레이블로 표시될지 결정합니다. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | 지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. True이면 셀 값을 표시하고, False이면 숨깁니다. 읽기 **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | 지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. True이면 리더 라인을 표시하고, False이면 숨깁니다. 읽기 **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | 지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. True이면 범례 키가 보입니다. 읽기 **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. True이면 백분율 값을 표시하고, False이면 숨깁니다. 읽기 **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | 차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean을 반환합니다. True이면 시리즈 이름을 표시하고, False이면 숨깁니다. 읽기 **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. True이면 백분율 값을 표시하고, False이면 숨깁니다. 읽기 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 차트 텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | 해시 코드를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 형식의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 형식 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | 쓰기 **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | DataLabels 객체의 형식 문자열을 나타냅니다. 쓰기 [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | 데이터 레이블의 위치를 나타냅니다. 쓰기 [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | 차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. 쓰기 [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | 지정된 차트의 데이터 레이블 버블 크기 값 표시 동작을 나타냅니다. True이면 버블 크기 값을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | 지정된 차트의 데이터 레이블 카테고리 이름 표시 동작을 나타냅니다. True이면 차트의 데이터 레이블에 카테고리 이름을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | 지정된 차트의 데이터 레이블이 데이터 호출(callout)로 표시될지 데이터 레이블로 표시될지 결정합니다. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | 지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. True이면 셀 값을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | 지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. True이면 리더 라인을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | 지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. True이면 범례 키가 보입니다. 쓰기 **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. True이면 백분율 값을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | 차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean을 설정합니다. True이면 시리즈 이름을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. True이면 백분율 값을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [PVIObject](../../aspose.slides/pviobject/)
* 클래스 [IDataLabelFormat](../idatalabelformat/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)