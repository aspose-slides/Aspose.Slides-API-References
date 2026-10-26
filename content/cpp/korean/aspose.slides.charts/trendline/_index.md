---
title: Trendline
second_title: Aspose.Slides for C++ API 레퍼런스
description: 클래스는 차트 시리즈의 추세선을 나타냅니다
type: docs
weight: 1366
url: /ko/aspose.slides.charts/trendline/
---
## Trendline 클래스

Class represents trend line of chart series

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## 메서드

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | 텍스트 매개변수 "text"를 사용하여 TextFrameForOverriding을 초기화합니다. TextFrameForOverriding이 이미 초기화된 경우 텍스트만 변경합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **double** [get_Backward](./get_backward/)() override | 트렌드 라인이 추세를 분석하는 시리즈 데이터 이전에 확장되는 카테고리(또는 산점도 차트의 단위) 수를 지정합니다. 산점도 및 비산점도 차트에서는 값이 0 이상이면 됩니다. **double**을 읽습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 부모 차트를 반환합니다. 읽기 전용 [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | 트렌드라인 방정식이 차트에 표시되도록 지정합니다 (Rsquaredvalue와 같은 레이블에). **bool**을 읽습니다. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | 트렌드라인의 R-제곱값이 차트에 표시되도록 지정합니다 (방정식과 같은 레이블에). **bool**을 읽습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 트렌드 라인의 형식을 나타냅니다. [IFormat](../iformat/)을 읽습니다. |
| **double** [get_Forward](./get_forward/)() override | 트렌드 라인이 추세를 분석하는 시리즈 데이터 이후에 확장되는 카테고리(또는 산점도 차트의 단위) 수를 지정합니다. 산점도 및 비산점도 차트에서는 값이 0 이상이어야 합니다. **double**을 읽습니다. |
| **double** [get_Intercept](./get_intercept/)() override | 트렌드 라인이 y축을 교차하는 값을 지정합니다. 이 속성은 트렌드라인 유형이 exp, linear 또는 poly인 경우에만 지원됩니다. **double**을 읽습니다. |
| **uint8_t** [get_Order](./get_order/)() override | 다항식 트렌드 라인의 차수를 지정합니다. 다른 트렌드 라인 유형에서는 무시됩니다. 값은 2에서 6 사이여야 합니다. **uint8_t**을 읽습니다. |
| **uint8_t** [get_Period](./get_period/)() override | 이동 평균 트렌드 라인의 기간을 지정합니다. 다른 트렌드 라인 변형에서는 무시됩니다. 값은 2에서 255 사이여야 합니다. **uint8_t**을 읽습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | 이 트렌드라인과 관련된 범례 항목을 나타냅니다. 읽기 전용 [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | 리치 포맷 텍스트를 포함할 수 있습니다. 이 속성이 null이 아니면 해당 포맷 텍스트 값이 데이터 레이블의 자동 생성 텍스트를 대체합니다. 자동 생성 데이터 레이블 텍스트는 ShowSeriesName, ShowValue 등 속성으로 관리되고 TextFormatManager.TextFormat 속성으로 포맷된 텍스트를 의미합니다. 읽기 전용 [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | 트렌드라인의 이름을 가져옵니다. [System::String](../../system/string/)를 읽습니다. |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | 트렌드 라인의 유형을 가져옵니다. [Charts::TrendlineType](../trendlinetype/)를 읽습니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시화를 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 클론을 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무것도 복사하지 않으며 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로는 아무것도 복사하지 않으며 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/)의 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_Backward](./set_backward/)(**double**) override | 트렌드 라인이 시리즈 데이터 이전에 확장되는 카테고리(또는 산점도 차트의 단위) 수를 지정합니다. 산점도 및 비산점도 차트에서는 값이 0 이상이어야 합니다. **double**을 씁니다. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | 트렌드라인 방정식이 차트에 표시되도록 지정합니다 (Rsquaredvalue와 같은 레이블에). **bool**을 씁니다. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | 트렌드라인의 R-제곱값이 차트에 표시되도록 지정합니다 (방정식과 같은 레이블에). **bool**을 씁니다. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | 트렌드 라인의 형식을 나타냅니다. [IFormat](../iformat/)을 씁니다. |
| void [set_Forward](./set_forward/)(**double**) override | 트렌드 라인이 시리즈 데이터 이후에 확장되는 카테고리(또는 산점도 차트의 단위) 수를 지정합니다. 산점도 및 비산점도 차트에서는 값이 0 이상이어야 합니다. **double**을 씁니다. |
| void [set_Intercept](./set_intercept/)(**double**) override | 트렌드 라인이 y축을 교차하는 값을 지정합니다. 이 속성은 트렌드라인 유형이 exp, linear 또는 poly인 경우에만 지원됩니다. **double**을 씁니다. |
| void [set_Order](./set_order/)(**uint8_t**) override | 다항식 트렌드 라인의 차수를 지정합니다. 다른 트렌드 라인 유형에서는 무시됩니다. 값은 2에서 6 사이여야 합니다. **uint8_t**을 씁니다. |
| void [set_Period](./set_period/)(**uint8_t**) override | 이동 평균 트렌드 라인의 기간을 지정합니다. 다른 트렌드 라인 변형에서는 무시됩니다. 값은 2에서 255 사이여야 합니다. **uint8_t**을 씁니다. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | 트렌드라인의 이름을 설정합니다. [System::String](../../system/string/)을 씁니다. |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | 트렌드 라인의 유형을 설정합니다. [Charts::TrendlineType](../trendlinetype/)을 씁니다. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 템플릿의 n번째 인수를 공유 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [DomObject](../../aspose.slides/domobject/)
* 클래스 [ITrendline](../itrendline/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)