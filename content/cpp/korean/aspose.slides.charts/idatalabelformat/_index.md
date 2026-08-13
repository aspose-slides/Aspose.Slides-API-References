---
title: IDataLabelFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: DataLabel에 대한 서식 옵션을 나타냅니다.
type: docs
weight: 963
url: /ko/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat 클래스


[DataLabel](../datalabel/)에 대한 서식 옵션을 나타냅니다.

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 데이터 레이블의 형식을 나타냅니다. 읽기 전용 [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | 읽기 **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | DataLabels 객체의 형식 문자열을 나타냅니다. 읽기 [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | 데이터 레이블의 위치를 나타냅니다. 읽기 [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | 차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | 지정된 차트의 데이터 레이블 말풍선 크기 값 표시 동작을 나타냅니다. True이면 말풍선 크기 값을 표시합니다. False이면 숨깁니다. 읽기 **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | 지정된 차트의 데이터 레이블 카테고리 이름 표시 동작을 나타냅니다. True이면 차트의 데이터 레이블에 카테고리 이름을 표시합니다. False이면 숨깁니다. 읽기 **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | 지정된 차트의 데이터 레이블이 데이터 호출(Callout)로 표시될지 데이터 레이블로 표시될지를 결정합니다. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | 지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. True이면 셀 값을 표시합니다. False이면 숨깁니다. 읽기 **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | 지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. True이면 리더 라인을 표시합니다. False이면 숨깁니다. 읽기 **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | 지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. True이면 데이터 레이블 범례 키가 표시됩니다. 읽기 **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. True이면 백분율 값을 표시합니다. False이면 숨깁니다. 읽기 **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | 차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 부울 값을 반환합니다. True이면 시리즈 이름을 표시하고, False이면 숨깁니다. 읽기 **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. True이면 백분율 값을 표시합니다. False이면 숨깁니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 차트 텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 형식을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금을 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조에 의해 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조에 의해 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | 쓰기 **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | DataLabels 객체의 형식 문자열을 나타냅니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | 데이터 레이블의 위치를 나타냅니다. 쓰기 [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | 차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | 지정된 차트의 데이터 레이블 말풍선 크기 값 표시 동작을 나타냅니다. True이면 말풍선 크기 값을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | 지정된 차트의 데이터 레이블 카테고리 이름 표시 동작을 나타냅니다. True이면 차트의 데이터 레이블에 카테고리 이름을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | 지정된 차트의 데이터 레이블이 데이터 호출(Callout)로 표시될지 데이터 레이블로 표시될지를 결정합니다. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | 지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. True이면 셀 값을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | 지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. True이면 리더 라인을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | 지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. True이면 데이터 레이블 범례 키가 표시됩니다. 쓰기 **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. True이면 백분율 값을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | 차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 부울 값을 설정합니다. True이면 시리즈 이름을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. True이면 백분율 값을 표시하고, False이면 숨깁니다. 쓰기 **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 구현한 잠금 해제를 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IFormattedTextContainer](../iformattedtextcontainer/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)