---
title: ChartPortionFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 클래스는 차트에서 사용되는 차트 부분 서식 속성을 포함합니다. IPortionFormatEffectiveData와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.
type: docs
weight: 261
url: /ko/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat 클래스

이 클래스는 차트에서 사용되는 차트 부분 서식 속성을 포함합니다. [IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/)와 달리 이 클래스의 모든 속성은 쓰기 가능합니다.

```cpp
class ChartPortionFormat : public Aspose::Slides::BasePortionFormat,
                           public Aspose::Slides::Charts::IChartPortionFormat
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 지정된 객체와 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 같다고 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않음). |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 같다고 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않음). |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../../aspose.slides/baseportionformat/get_alternativelanguageid/)() override | 대체 언어의 Id를 반환합니다. 읽기 [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_ComplexScriptFont](../../aspose.slides/baseportionformat/get_complexscriptfont/)() override | 복합 스크립트 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../../aspose.slides/ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_EastAsianFont](../../aspose.slides/baseportionformat/get_eastasianfont/)() override | 동아시아 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../../aspose.slides/ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/baseportionformat/get_effectformat/)() override | 텍스트 [EffectFormat](../../aspose.slides/effectformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IEffectFormat](../../aspose.slides/ieffectformat/). |
| **float** [get_Escapement](../../aspose.slides/baseportionformat/get_escapement/)() override | 위첨자 또는 아래첨자 텍스트를 반환합니다. 값은 -100% (아래첨자) 에서 100% (위첨자) 사이입니다. **std::numeric_limits<float>::quiet_NaN()** 은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/baseportionformat/get_fillformat/)() override | 텍스트 [FillFormat](../../aspose.slides/fillformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IFillFormat](../../aspose.slides/ifillformat/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontBold](../../aspose.slides/baseportionformat/get_fontbold/)() override | 글꼴이 굵게인지 여부를 판단합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| **float** [get_FontHeight](../../aspose.slides/baseportionformat/get_fontheight/)() override | 부분의 글꼴 높이를 반환합니다. **std::numeric_limits<float>::quiet_NaN()** 은 높이가 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontItalic](../../aspose.slides/baseportionformat/get_fontitalic/)() override | 글꼴이 이탤릭인지 여부를 판단합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| [TextUnderlineType](../../aspose.slides/textunderlinetype/) [get_FontUnderline](../../aspose.slides/baseportionformat/get_fontunderline/)() override | 텍스트 밑줄 유형을 반환합니다. 상속이 적용되지 않습니다. 읽기 [TextUnderlineType](../../aspose.slides/textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_HighlightColor](../../aspose.slides/baseportionformat/get_highlightcolor/)() override | 텍스트를 강조하는 데 사용되는 색상을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IColorFormat](../../aspose.slides/icolorformat/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineFill](../../aspose.slides/baseportionformat/get_ishardunderlinefill/)() override | 밑줄 스타일이 자체 [FillFormat](../../aspose.slides/fillformat/) 속성을 갖는지 또는 텍스트의 [FillFormat](../../aspose.slides/fillformat/) 속성에서 상속받는지 판단합니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineLine](../../aspose.slides/baseportionformat/get_ishardunderlineline/)() override | 밑줄 스타일이 자체 [LineFormat](../../aspose.slides/lineformat/) 속성을 갖는지 또는 텍스트의 [LineFormat](../../aspose.slides/lineformat/) 속성에서 상속받는지 판단합니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| **float** [get_KerningMinimalSize](../../aspose.slides/baseportionformat/get_kerningminimalsize/)() override | 커닝을 켜야 하는 최소 글꼴 크기를 반환합니다. **std::numeric_limits<float>::quiet_NaN()** 은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Kumimoji](../../aspose.slides/baseportionformat/get_kumimoji/)() override | 숫자가 텍스트 동부 언어 전용 수직 레이아웃을 무시해야 하는지 판단합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../../aspose.slides/baseportionformat/get_languageid/)() override | 교정 언어의 Id를 반환합니다. 맞춤법 및 문법 검사에 사용됩니다. 읽기 [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_LatinFont](../../aspose.slides/baseportionformat/get_latinfont/)() override | 라틴 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../../aspose.slides/ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/baseportionformat/get_lineformat/)() override | 텍스트 외곽선에 대한 [LineFormat](../../aspose.slides/lineformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [ILineFormat](../../aspose.slides/ilineformat/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_NormaliseHeight](../../aspose.slides/baseportionformat/get_normaliseheight/)() override | 텍스트의 높이를 정규화해야 하는지 판단합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Parent_Immediate 객체를 반환합니다. 읽기 전용 [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 부모 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)를 반환합니다. 읽기 전용 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_ProofDisabled](../../aspose.slides/baseportionformat/get_proofdisabled/)() override | 텍스트를 교정하지 않아야 하는지 판단합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| **float** [get_Spacing](../../aspose.slides/baseportionformat/get_spacing/)() override | 문자 간격 증가 값을 반환합니다. **std::numeric_limits<float>::quiet_NaN()** 은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| **bool** [get_SpellCheck](../../aspose.slides/baseportionformat/get_spellcheck/)() override | 텍스트 부분에 대한 맞춤법 검사가 활성화되어 있는지 여부를 나타내는 값을 가져옵니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 **false**입니다. |
| [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) [get_StrikethroughType](../../aspose.slides/baseportionformat/get_strikethroughtype/)() override | 텍스트의 취소선 유형을 반환합니다. 상속이 적용되지 않습니다. 읽기 [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_SymbolFont](../../aspose.slides/baseportionformat/get_symbolfont/)() override | 기호 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../../aspose.slides/ifontdata/). |
| [Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/) [get_TextCapType](../../aspose.slides/baseportionformat/get_textcaptype/)() override | 텍스트 대소문자 유형을 반환합니다. 상속이 적용되지 않습니다. 읽기 [Slides::TextCapType](../../aspose.slides/textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_UnderlineFillFormat](../../aspose.slides/baseportionformat/get_underlinefillformat/)() override | 밑줄 선 [FillFormat](../../aspose.slides/fillformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_UnderlineLineFormat](../../aspose.slides/baseportionformat/get_underlinelineformat/)() override | 밑줄 선을 외곽선으로 만들 때 사용되는 [LineFormat](../../aspose.slides/lineformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [ILineFormat](../../aspose.slides/ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | 해시 코드를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출에 해당합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자에 해당합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 구문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드에 해당합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_AlternativeLanguageId](../../aspose.slides/baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | 대체 언어의 Id를 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../../aspose.slides/baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 복합 스크립트 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../../aspose.slides/ifontdata/). |
| void [set_EastAsianFont](../../aspose.slides/baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 동아시아 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../../aspose.slides/ifontdata/). |
| void [set_Escapement](../../aspose.slides/baseportionformat/set_escapement/)(**float**) override | 위첨자 또는 아래첨자 텍스트를 설정합니다. 값은 -100% (아래첨자) 에서 100% (위첨자) 사이입니다. **std::numeric_limits<float>::quiet_NaN()** 은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| void [set_FontBold](../../aspose.slides/baseportionformat/set_fontbold/)([NullableBool](../../aspose.slides/nullablebool/)) override | 글꼴이 굵게인지 여부를 판단합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_FontHeight](../../aspose.slides/baseportionformat/set_fontheight/)(**float**) override | 부분의 글꼴 높이를 설정합니다. **std::numeric_limits<float>::quiet_NaN()** 은 높이가 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| void [set_FontItalic](../../aspose.slides/baseportionformat/set_fontitalic/)([NullableBool](../../aspose.slides/nullablebool/)) override | 글꼴이 이탤릭인지 여부를 판단합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_FontUnderline](../../aspose.slides/baseportionformat/set_fontunderline/)([TextUnderlineType](../../aspose.slides/textunderlinetype/)) override | 텍스트 밑줄 유형을 설정합니다. 상속이 적용되지 않습니다. 쓰기 [TextUnderlineType](../../aspose.slides/textunderlinetype/). |
| void [set_IsHardUnderlineFill](../../aspose.slides/baseportionformat/set_ishardunderlinefill/)([NullableBool](../../aspose.slides/nullablebool/)) override | 밑줄 스타일이 자체 [FillFormat](../../aspose.slides/fillformat/) 속성을 갖는지 또는 텍스트의 [FillFormat](../../aspose.slides/fillformat/) 속성에서 상속받는지 판단합니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_IsHardUnderlineLine](../../aspose.slides/baseportionformat/set_ishardunderlineline/)([NullableBool](../../aspose.slides/nullablebool/)) override | 밑줄 스타일이 자체 [LineFormat](../../aspose.slides/lineformat/) 속성을 갖는지 또는 텍스트의 [LineFormat](../../aspose.slides/lineformat/) 속성에서 상속받는지 판단합니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_KerningMinimalSize](../../aspose.slides/baseportionformat/set_kerningminimalsize/)(**float**) override | 커닝을 켜야 하는 최소 글꼴 크기를 설정합니다. **std::numeric_limits<float>::quiet_NaN()** 은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| void [set_Kumimoji](../../aspose.slides/baseportionformat/set_kumimoji/)([NullableBool](../../aspose.slides/nullablebool/)) override | 숫자가 텍스트 동부 언어 전용 수직 레이아웃을 무시해야 하는지 판단합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_LanguageId](../../aspose.slides/baseportionformat/set_languageid/)([System::String](../../system/string/)) override | 교정 언어의 Id를 설정합니다. 맞춤법 및 문법 검사에 사용됩니다. 쓰기 [System::String](../../system/string/). |
| void [set_LatinFont](../../aspose.slides/baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 라틴 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../../aspose.slides/ifontdata/). |
| void [set_NormaliseHeight](../../aspose.slides/baseportionformat/set_normaliseheight/)([NullableBool](../../aspose.slides/nullablebool/)) override | 텍스트의 높이를 정규화해야 하는지 판단합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_ProofDisabled](../../aspose.slides/baseportionformat/set_proofdisabled/)([NullableBool](../../aspose.slides/nullablebool/)) override | 텍스트를 교정하지 않아야 하는지 판단합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Spacing](../../aspose.slides/baseportionformat/set_spacing/)(**float**) override | 문자 간격 증가 값을 설정합니다. **std::numeric_limits<float>::quiet_NaN()** 은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| void [set_SpellCheck](../../aspose.slides/baseportionformat/set_spellcheck/)(**bool**) override | 텍스트 부분에 대한 맞춤법 검사가 활성화되어 있는지 나타내는 값을 설정합니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 **false**입니다. |
| void [set_StrikethroughType](../../aspose.slides/baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)) override | 텍스트의 취소선 유형을 설정합니다. 상속이 적용되지 않습니다. 쓰기 [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/). |
| void [set_SymbolFont](../../aspose.slides/baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 기호 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../../aspose.slides/ifontdata/). |
| void [set_TextCapType](../../aspose.slides/baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/)) override | 텍스트 대소문자 유형을 설정합니다. 상속이 적용되지 않습니다. 쓰기 [Slides::TextCapType](../../aspose.slides/textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운트 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드에 해당합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 비고

이 클래스는 특정 부분에 정의된 텍스트 부분 서식 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않으므로 대부분의 경우 "undefined" 의미의 값을 얻게 됨을 의미합니다.

상속을 포함한 실제 서식 매개변수 값을 얻으려면 [PortionFormat::GetEffective](../../aspose.slides/portionformat/geteffective/) 메서드를 사용해야 하며, 이 메서드는 [IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/) 인스턴스를 반환합니다.

## 관련 항목

* 클래스 [BasePortionFormat](../../aspose.slides/baseportionformat/)
* 클래스 [IChartPortionFormat](../ichartportionformat/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)