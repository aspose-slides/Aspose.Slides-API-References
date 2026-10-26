---
title: ITrendline
second_title: Aspose.Slides for C++ API 레퍼런스
description: 클래스는 차트 시리즈의 추세선을 나타냅니다.
type: docs
weight: 1223
url: /ko/aspose.slides.charts/itrendline/
---
## ITrendline 클래스

Class represents trend line of chart series

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | 텍스트 매개변수 "text"를 사용하여 TextFrameForOverriding을 초기화합니다. TextFrameForOverriding이 이미 초기화된 경우 단순히 텍스트를 변경합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 동등하지 않지만, 두 NaN이 동등한 것으로 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 동등하지 않지만, 두 NaN이 동등한 것으로 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual **double** [get_Backward](./get_backward/)() | 트렌드 라인이 추세를 따르는 시리즈의 데이터 이전에 확장되는 카테고리(또는 산점도 차트의 단위) 수를 지정합니다. 산점도 및 비산점도 차트에서는 값이 0 이상인 모든 값을 허용합니다. 읽기 **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | 트렌드 라인의 방정식이 차트에 표시되도록 지정합니다(Rsquaredvalue와 동일한 레이블에 표시). 읽기 **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | 트렌드 라인의 R-제곱 값이 차트에 표시되도록 지정합니다(방정식과 동일한 레이블에 표시). 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 트렌드 라인의 형식을 나타냅니다. 읽기 [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | 트렌드 라인이 추세를 따르는 시리즈의 데이터 이후에 확장되는 카테고리(또는 산점도 차트의 단위) 수를 지정합니다. 산점도 및 비산점도 차트에서는 값이 0 이상인 모든 값을 허용합니다. 읽기 **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | 트렌드 라인이 y축과 교차하는 값을 지정합니다. 이 속성은 트렌드 라인 유형이 exp, linear 또는 poly인 경우에만 지원됩니다. 읽기 **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | 다항식 트렌드 라인의 차수를 지정합니다. 다른 트렌드 라인 유형에서는 무시됩니다. 값은 2에서 6 사이여야 합니다. 읽기 **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | 이동 평균 트렌드 라인의 기간을 지정합니다. 다른 트렌드 라인 변형에서는 무시됩니다. 값은 2에서 255 사이여야 합니다. 읽기 **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | 이 트렌드라인과 관련된 범례 항목을 나타냅니다. 읽기 전용 [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 차트 텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | 리치 형식 텍스트를 포함할 수 있습니다. 이 속성이 null이 아니면 해당 형식 텍스트 값이 자동 생성 텍스트를 덮어씁니다. 자동 생성 텍스트는 데이터 레이블, 값 축의 표시 단위 레이블, 축 제목, 차트 제목, 트렌드 라인 레이블의 암시적 속성입니다. 자동 생성 텍스트는 [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) 속성을 사용해 형식이 지정됩니다. 읽기 전용 [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | 트렌드라인의 이름을 가져옵니다. 읽기 [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | 트렌드 라인의 유형을 가져옵니다. 읽기 [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_Backward](./set_backward/)(**double**) | 트렌드 라인이 추세를 따르는 시리즈의 데이터 이전에 확장되는 카테고리(또는 산점도 차트의 단위) 수를 지정합니다. 산점도 및 비산점도 차트에서는 값이 0 이상인 모든 값을 허용합니다. 쓰기 **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | 트렌드 라인의 방정식이 차트에 표시되도록 지정합니다(Rsquaredvalue와 동일한 레이블에 표시). 쓰기 **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | 트렌드 라인의 R-제곱 값이 차트에 표시되도록 지정합니다(방정식과 동일한 레이블에 표시). 쓰기 **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | 트렌드 라인의 형식을 나타냅니다. 쓰기 [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | 트렌드 라인이 추세를 따르는 시리즈의 데이터 이후에 확장되는 카테고리(또는 산점도 차트의 단위) 수를 지정합니다. 산점도 및 비산점도 차트에서는 값이 0 이상인 모든 값을 허용합니다. 쓰기 **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | 트렌드 라인이 y축과 교차하는 값을 지정합니다. 이 속성은 트렌드 라인 유형이 exp, linear 또는 poly인 경우에만 지원됩니다. 쓰기 **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | 다항식 트렌드 라인의 차수를 지정합니다. 다른 트렌드 라인 유형에서는 무시됩니다. 값은 2에서 6 사이여야 합니다. 쓰기 **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | 이동 평균 트렌드 라인의 기간을 지정합니다. 다른 트렌드 라인 변형에서는 무시됩니다. 값은 2에서 255 사이여야 합니다. 쓰기 **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | 트렌드라인의 이름을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | 트렌드 라인의 유형을 설정합니다. 쓰기 [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [IOverridableText](../ioverridabletext/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)