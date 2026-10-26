---
title: PortionFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 클래스는 텍스트 부분 포맷 속성을 포함합니다. IPortionFormatEffectiveData와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.
type: docs
weight: 4811
url: /ko/aspose.slides/portionformat/
---
## PortionFormat 클래스


This class contains the text portion formatting properties. Unlike [IPortionFormatEffectiveData](../iportionformateffectivedata/), all properties of this class are writeable.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 지정된 객체와 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(또 NaN도) 같지 않지만, 두 NaN을 같은 것으로 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(또 NaN도) 같지 않지만, 두 NaN을 같은 것으로 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | 대체 언어의 Id를 반환합니다. 읽기 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | 북마크 식별자를 반환합니다. 읽기 [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | 복합 스크립트 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | 동아시아 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | 텍스트 [EffectFormat](../effectformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | 위첨자 또는 아래첨자 텍스트를 반환합니다. 값은 -100% (아래첨자)부터 100% (위첨자)까지입니다. **std::numeric_limits<float>::quiet_NaN()**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | 텍스트 [FillFormat](../fillformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | 글꼴이 굵게인지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | 부분의 글꼴 높이를 반환합니다. **std::numeric_limits<float>::quiet_NaN()**는 높이가 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | 글꼴이 이탤릭인지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | 텍스트 밑줄 종류를 반환합니다. 상속이 적용되지 않습니다. 읽기 [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | 텍스트를 강조하는 색상을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | 마우스 클릭을 위해 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | 하이퍼링크 관리자. 읽기 전용 [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | 마우스 오버를 위해 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | 밑줄 스타일이 자체 [FillFormat](../fillformat/) 속성을 가지고 있는지 또는 텍스트의 [FillFormat](../fillformat/) 속성에서 상속받는지 결정합니다. 읽기 [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | 밑줄 스타일이 자체 [LineFormat](../lineformat/) 속성을 가지고 있는지 또는 텍스트의 [LineFormat](../lineformat/) 속성에서 상속받는지 결정합니다. 읽기 [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | 커닝이 활성화되어야 하는 최소 글꼴 크기를 반환합니다. **std::numeric_limits<float>::quiet_NaN()**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | 숫자가 텍스트 동아시아 언어별 수직 레이아웃을 무시해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | 교정 언어의 Id를 반환합니다. 맞춤법 및 문법 검사에 사용됩니다. 읽기 [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | 라틴 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | [LineFormat](../lineformat/) 속성을 반환합니다 텍스트 윤곽을 위해. 상속이 적용되지 않습니다. 읽기 전용 [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | 텍스트 높이를 정규화해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate 객체를 반환합니다. 읽기 전용 [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 부모 [IPresentationComponent](../ipresentationcomponent/)를 반환합니다. 읽기 전용 [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | 텍스트가 교정되지 않아야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | 스마트 태그를 정리해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기 **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | 문자 간 간격 증가 값을 반환합니다. **std::numeric_limits<float>::quiet_NaN()**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | 텍스트 부분에 대한 맞춤법 검사 활성화 여부를 나타내는 값을 가져옵니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 **false**입니다. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | 텍스트의 취소선 종류를 반환합니다. 상속이 적용되지 않습니다. 읽기 [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | 기호 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | 텍스트 대문자화 유형을 반환합니다. 상속이 적용되지 않습니다. 읽기 [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | 밑줄 선 [FillFormat](../fillformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | [LineFormat](../lineformat/) 속성을 반환합니다, 밑줄 선을 윤곽하도록 사용됩니다. 상속이 적용되지 않습니다. 읽기 전용 [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | 상속이 적용된 효과적인 부분 포맷 데이터를 가져옵니다. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 해시 코드를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 타입의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 구현. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자를 사용합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
|  [PortionFormat](./portionformat/)() | [PortionFormat](./) 클래스의 새 인스턴스를 초기화합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | 대체 언어의 Id를 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | 북마크 식별자를 설정합니다. 쓰기 [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 복합 스크립트 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 동아시아 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | 위첨자 또는 아래첨자 텍스트를 설정합니다. 값은 -100% (아래첨자)부터 100% (위첨자)까지입니다. **std::numeric_limits<float>::quiet_NaN()**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | 글꼴이 굵게인지 여부를 결정합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | 부분의 글꼴 높이를 설정합니다. **std::numeric_limits<float>::quiet_NaN()**는 높이가 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | 글꼴이 이탤릭인지 여부를 결정합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | 텍스트 밑줄 유형을 설정합니다. 상속이 적용되지 않습니다. 쓰기 [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 마우스 클릭을 위해 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 마우스 오버를 위해 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | 밑줄 스타일이 자체 [FillFormat](../fillformat/) 속성을 가지고 있는지 또는 텍스트의 [FillFormat](../fillformat/) 속성에서 상속받는지 결정합니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | 밑줄 스타일이 자체 [LineFormat](../lineformat/) 속성을 가지고 있는지 또는 텍스트의 [LineFormat](../lineformat/) 속성에서 상속받는지 결정합니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | 커닝이 활성화되어야 하는 최소 글꼴 크기를 설정합니다. **std::numeric_limits<float>::quiet_NaN()**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | 숫자가 텍스트 동아시아 언어별 수직 레이아웃을 무시해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | 교정 언어의 Id를 설정합니다. 맞춤법 및 문법 검사에 사용됩니다. 쓰기 [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 라틴 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | 텍스트 높이를 정규화해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | 텍스트가 교정되지 않아야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | 스마트 태그를 정리해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 쓰기 **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | 문자 간 간격 증가 값을 설정합니다. **std::numeric_limits<float>::quiet_NaN()**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | 텍스트 부분에 대한 맞춤법 검사 활성화 여부를 나타내는 값을 설정합니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 **false**입니다. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | 텍스트의 취소선 종류를 설정합니다. 상속이 적용되지 않습니다. 쓰기 [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 기호 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | 텍스트 대문자화 유형을 설정합니다. 상속이 적용되지 않습니다. 쓰기 [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 번째 템플릿 인자를 강한 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자를 사용합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 비고


이 클래스는 특정 부분에 대해 정의된 텍스트 부분 포맷 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않으므로 대부분의 경우 "정의되지 않음" 의미의 값을 얻게 됩니다.

상속을 포함한 실제 포맷 매개변수 값을 얻으려면 [PortionFormat::GetEffective](./geteffective/) 메서드를 사용해야 하며, 이 메서드는 [IPortionFormatEffectiveData](../iportionformateffectivedata/) 인스턴스를 반환합니다.

다음 예제에서는 PowerPoint [Presentation](../presentation/)의 [Paragraph](../paragraph/) 부분에 라틴 글꼴을 할당하는 방법을 보여줍니다.
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides는 이러한 특수 식별자를 사용합니다 (PowerPoint에서 사용되는 것과 유사합니다):
// +mn-lt - 본문 글꼴 라틴 (소형 라틴 글꼴)
// +mj-lt - 제목 글꼴 라틴 (대형 라틴 글꼴)
// +mn-ea - 본문 글꼴 동아시아 (소형 동아시아 글꼴)
// +mj-ea - 본문 글꼴 동아시아 (소형 동아시아 글꼴)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## 참조

* 클래스 [BasePortionFormat](../baseportionformat/)
* 클래스 [IPortionFormat](../iportionformat/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)