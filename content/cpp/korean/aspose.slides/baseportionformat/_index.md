---
title: BasePortionFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: 공통 텍스트 부분 서식 속성.
type: docs
weight: 144
url: /ko/aspose.slides/baseportionformat/
---
## BasePortionFormat 클래스

Common text portion formatting properties.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 지정된 객체와 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(또 NaN도) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(또 NaN도) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | 대체 언어의 Id를 반환합니다. 읽기 [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | 복합 스크립트 폰트 정보를 반환합니다. Null은 폰트가 정의되지 않았으며 기본 템플릿(Master)에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | 동아시아 폰트 정보를 반환합니다. Null은 폰트가 정의되지 않았으며 기본 템플릿에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | 텍스트 [EffectFormat](../effectformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | 위첨자 혹은 아래첨자 텍스트를 반환합니다. 값은 -100% (아래첨자)에서 100% (위첨자) 사이입니다. **std::numeric_limits<float>::quiet_NaN()** 은 값이 정의되지 않았으며 기본 템플릿에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | 텍스트 [FillFormat](../fillformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | 폰트가 굵게 표시되는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | 부분의 폰트 높이를 반환합니다. **std::numeric_limits<float>::quiet_NaN()** 은 높이가 정의되지 않았으며 기본 템플릿에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | 폰트가 이탤릭인지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | 텍스트 밑줄 유형을 반환합니다. 상속이 적용되지 않습니다. 읽기 [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | 텍스트를 강조하는 데 사용되는 색상을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | 밑줄 스타일이 자체 [FillFormat](../fillformat/) 속성을 가지고 있는지 또는 텍스트의 [FillFormat](../fillformat/) 속성으로부터 상속받는지 여부를 결정합니다. 읽기 [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | 밑줄 스타일이 자체 [LineFormat](../lineformat/) 속성을 가지고 있는지 또는 텍스트의 [LineFormat](../lineformat/) 속성으로부터 상속받는지 여부를 결정합니다. 읽기 [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | 커닝을 활성화해야 하는 최소 폰트 크기를 반환합니다. **std::numeric_limits<float>::quiet_NaN()** 은 값이 정의되지 않았으며 기본 템플릿에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | 숫자가 텍스트 동양 언어 특정 수직 레이아웃을 무시해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | 교정 언어의 Id를 반환합니다. 맞춤법 및 문법 검사에 사용됩니다. 읽기 [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | 라틴 폰트 정보를 반환합니다. Null은 폰트가 정의되지 않았으며 기본 템플릿에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | [LineFormat](../lineformat/) 텍스트 윤곽 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | 텍스트 높이를 정규화해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate 객체를 반환합니다. 읽기 전용 [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 부모 [IPresentationComponent](../ipresentationcomponent/)를 반환합니다. 읽기 전용 [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | 텍스트가 교정되지 않아야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | 문자 간 간격 증가값을 반환합니다. **std::numeric_limits<float>::quiet_NaN()** 은 값이 정의되지 않았으며 기본 템플릿에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | 텍스트 부분에 대해 맞춤법 검사가 활성화되어 있는지 여부를 나타내는 값을 가져옵니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정되면 맞춤법 검사가 허용됩니다. 기본값은 **false**입니다. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | 텍스트의 취소선 유형을 반환합니다. 상속이 적용되지 않습니다. 읽기 [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | 기호 폰트 정보를 반환합니다. Null은 폰트가 정의되지 않았으며 기본 템플릿에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | 텍스트 대소문자 변환 유형을 반환합니다. 상속이 적용되지 않습니다. 읽기 [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | 밑줄 라인 [FillFormat](../fillformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | [LineFormat](../lineformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 해시 코드를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 구문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 형식 복제를 활성화합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | 대체 언어의 Id를 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 복합 스크립트 폰트 정보를 설정합니다. Null은 폰트가 정의되지 않았으며 기본 템플릿에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 동아시아 폰트 정보를 설정합니다. Null은 폰트가 정의되지 않았으며 기본 템플릿에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | 위첨자 혹은 아래첨자 텍스트를 설정합니다. 값은 -100% (아래첨자)에서 100% (위첨자) 사이입니다. **std::numeric_limits<float>::quiet_NaN()** 은 값이 정의되지 않았으며 기본 템플릿에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | 폰트가 굵게 표시되는지 여부를 결정합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | 부분의 폰트 높이를 설정합니다. **std::numeric_limits<float>::quiet_NaN()** 은 높이가 정의되지 않았으며 기본 템플릿에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | 폰트가 이탤릭인지 여부를 결정합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | 텍스트 밑줄 유형을 설정합니다. 상속이 적용되지 않습니다. 쓰기 [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | 밑줄 스타일이 자체 [FillFormat](../fillformat/) 속성을 가지고 있는지 또는 텍스트의 [FillFormat](../fillformat/) 속성으로부터 상속받는지 여부를 결정합니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | 밑줄 스타일이 자체 [LineFormat](../lineformat/) 속성을 가지고 있는지 또는 텍스트의 [LineFormat](../lineformat/) 속성으로부터 상속받는지 여부를 결정합니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | 커닝을 활성화해야 하는 최소 폰트 크기를 설정합니다. **std::numeric_limits<float>::quiet_NaN()** 은 값이 정의되지 않았으며 기본 템플릿에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | 숫자가 텍스트 동양 언어 특정 수직 레이아웃을 무시해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | 교정 언어의 Id를 설정합니다. 맞춤법 및 문법 검사에 사용됩니다. 쓰기 [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 라틴 폰트 정보를 설정합니다. Null은 폰트가 정의되지 않았으며 기본 템플릿에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | 텍스트 높이를 정규화해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | 텍스트가 교정되지 않아야 하는지 여부를 결정합니다. 상Inheritance이 적용되지 않습니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | 문자 간 간격 증가값을 설정합니다. **std::numeric_limits<float>::quiet_NaN()** 은 값이 정의되지 않았으며 기본 템플릿에서 상Inheritance되어야 함을 의미합니다. 쓰기 **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | 텍스트 부분에 대한 맞춤법 검사가 활성화되어 있는지 여부를 나타내는 값을 설정합니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정되면 맞춤법 검사가 허용됩니다. 기본값은 **false**입니다. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | 텍스트의 취소선 유형을 설정합니다. 상Inheritance이 적용되지 않습니다. 쓰기 [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 기호 폰트 정보를 설정합니다. Null은 폰트가 정의되지 않았으며 기본 템플릿에서 상Inheritance되어야 함을 의미합니다. 쓰기 [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | 텍스트 대소문자 변환 유형을 설정합니다. 상Inheritance이 적용되지 않습니다. 쓰기 [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 구문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고, 스마트 포인터나 ThisProtector를 사용하십시오. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [PVIObject](../pviobject/)
* 클래스 [IBasePortionFormat](../ibaseportionformat/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)