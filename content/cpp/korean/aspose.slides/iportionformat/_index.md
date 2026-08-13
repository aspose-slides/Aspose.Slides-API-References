---
title: IPortionFormat
second_title: Aspose.Slides for C++ API 참조
description: 이 클래스는 텍스트 부분 서식 속성을 포함합니다. IPortionFormatEffectiveData와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.
type: docs
weight: 3329
url: /ko/aspose.slides/iportionformat/
---
## IPortionFormat 클래스


이 클래스는 텍스트 부분 서식 속성을 포함합니다. [IPortionFormatEffectiveData](../iportionformateffectivedata/)와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## Methods

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않음에도 불구하고, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않음에도 불구하고, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | 대체 언어의 Id를 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | 북마크 식별자를 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | 복합 스크립트 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | 동아시아 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | 텍스트 [EffectFormat](../effectformat/) 속성을 반환합니다. 상속이 적용되지 않음. 읽기 전용 [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | 위첨자 또는 아래첨자 텍스트를 반환합니다. 값은 -100% (아래첨자)부터 100% (위첨자)까지입니다. **std::numeric_limits<float>::quiet_NaN()**은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | 텍스트 [FillFormat](../fillformat/) 속성을 반환합니다. 상속이 적용되지 않음. 읽기 전용 [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | 글꼴이 굵게인지 여부를 결정합니다. 상속이 적용되지 않음. 읽기 [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | 부분의 글꼴 높이를 반환합니다. **std::numeric_limits<float>::quiet_NaN()**은 높이가 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | 글꼴이 이탤릭인지 여부를 결정합니다. 상속이 적용되지 않음. 읽기 [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | 텍스트 밑줄 유형을 반환합니다. 상속이 적용되지 않음. 읽기 [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | 텍스트를 강조하는 색상을 반환합니다. 상속이 적용되지 않음. 읽기 전용 [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | 마우스 클릭에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | 하이퍼링크 관리자를 읽기 전용 [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | 마우스 오버에 정의된 하이퍼링크를 반환합니다. 읽기 [IHyperlink](../ihyperlink/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | 밑줄 스타일이 자체 [FillFormat](../fillformat/) 속성을 가지고 있는지 또는 텍스트의 [FillFormat](../fillformat/) 속성에서 상속받는지 여부를 결정합니다. 읽기 [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | 밑줄 스타일이 자체 [LineFormat](../lineformat/) 속성을 가지고 있는지 또는 텍스트의 [LineFormat](../lineformat/) 속성에서 상속받는지 여부를 결정합니다. 읽기 [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | 커닝을 활성화해야 하는 최소 글꼴 크기를 반환합니다. **std::numeric_limits<float>::quiet_NaN()**은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | 숫자가 텍스트 동양 언어별 수직 레이아웃을 무시해야 하는지 여부를 결정합니다. 상속이 적용되지 않음. 읽기 [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | 맞춤법 검사 언어의 Id를 반환합니다. 맞춤법 및 문법 확인에 사용됩니다. 읽기 [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | 라틴 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | 텍스트 외곽선에 대한 [LineFormat](../lineformat/) 속성을 반환합니다. 상속이 적용되지 않음. 읽기 전용 [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | 텍스트 높이를 정규화해야 하는지 여부를 결정합니다. 상속이 적용되지 않음. 읽기 [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | 텍스트를 교정하지 않아야 하는지 여부를 결정합니다. 상속이 적용되지 않음. 읽기 [NullableBool](../nullablebool/). |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | 스마트 태그를 정리해야 하는지 여부를 결정합니다. 상속이 적용되지 않음. 읽기 **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | 문자 간 간격 증가값을 반환합니다. **std::numeric_limits<float>::quiet_NaN()**은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | 텍스트 부분에 대한 맞춤법 검사가 활성화되었는지를 나타내는 값을 가져옵니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 **false**입니다. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | 텍스트의 취소선 유형을 반환합니다. 상속이 적용되지 않음. 읽기 [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | 기호 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | 텍스트 대소문자 변환 유형을 반환합니다. 상속이 적용되지 않음. 읽기 [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | 밑줄 라인 [FillFormat](../fillformat/) 속성을 반환합니다. 상속이 적용되지 않음. 읽기 전용 [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | 밑줄 라인을 외곽선하는 데 사용되는 [LineFormat](../lineformat/) 속성을 반환합니다. 상속이 적용되지 않음. 읽기 전용 [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | 상속이 적용된 실제 부분 서식 데이터를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 C# 유사 구현. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 구현. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 오브젝트를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조를 통해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조를 통해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | 대체 언어의 Id를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | 북마크 식별자를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 복합 스크립트 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 동아시아 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../ifontdata/). |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | 위첨자 또는 아래첨자 텍스트를 설정합니다. 값은 -100% (아래첨자)부터 100% (위첨자)까지입니다. **std::numeric_limits<float>::quiet_NaN()**은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | 글꼴이 굵게인지 여부를 결정합니다. 상속이 적용되지 않음. 쓰기 [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | 부분의 글꼴 높이를 설정합니다. **std::numeric_limits<float>::quiet_NaN()**은 높이가 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | 글꼴이 이탤릭인지 여부를 결정합니다. 상속이 적용되지 않음. 쓰기 [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | 텍스트 밑줄 유형을 설정합니다. 상속이 적용되지 않음. 쓰기 [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 마우스 클릭에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 마우스 오버에 정의된 하이퍼링크를 설정합니다. 쓰기 [IHyperlink](../ihyperlink/). |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | 밑줄 스타일이 자체 [FillFormat](../fillformat/) 속성을 가지고 있는지 또는 텍스트의 [FillFormat](../fillformat/) 속성에서 상속받는지 여부를 결정합니다. 쓰기 [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | 밑줄 스타일이 자체 [LineFormat](../lineformat/) 속성을 가지고 있는지 또는 텍스트의 [LineFormat](../lineformat/) 속성에서 상속받는지 여부를 결정합니다. 쓰기 [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | 커닝을 활성화해야 하는 최소 글꼴 크기를 설정합니다. **std::numeric_limits<float>::quiet_NaN()**은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | 숫자가 텍스트 동양 언어별 수직 레이아웃을 무시해야 하는지 여부를 결정합니다. 상속이 적용되지 않음. 쓰기 [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | 맞춤법 검사 언어의 Id를 설정합니다. 맞춤법 및 문법 확인에 사용됩니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 라틴 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | 텍스트 높이를 정규화해야 하는지 여부를 결정합니다. 상속이 적용되지 않음. 쓰기 [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | 텍스트를 교정하지 않아야 하는지 여부를 결정합니다. 상류가 적용되지 않음. 쓰기 [NullableBool](../nullablebool/). |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | 스마트 태그를 정리해야 하는지 여부를 결정합니다. 상속이 적용되지 않음. 쓰기 **bool**. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | 문자 간 간격 증가값을 설정합니다. **std::numeric_limits<float>::quiet_NaN()**은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | 텍스트 부분에 대한 맞춤법 검사가 활성화되었는지를 나타내는 값을 설정합니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 **false**입니다. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | 텍스트의 취소선 유형을 설정합니다. 상속이 적용되지 않음. 쓰기 [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 기호 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | 텍스트 대소문자 변환 유형을 설정합니다. 상속이 적용되지 않음. 쓰기 [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터로 설정합니다(공유 대신). 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | [Object.ToString()](../../system/object/tostring/) 메서드의 C# 유사 구현. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문의 구현입니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 오브젝트를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## Remarks

이 클래스는 특정 부분에 대해 정의된 텍스트 부분 서식 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않으므로 대부분의 경우 "정의되지 않음" 값을 얻게 된다는 의미입니다.

상속된 값을 포함한 실제 서식 매개변수 값을 얻으려면 [IPortionFormat::GetEffective](./geteffective/) 메서드를 사용해야 하며, 이 메서드는 [IPortionFormatEffectiveData](../iportionformateffectivedata/) 인스턴스를 반환합니다.

## See Also

* 클래스 [IBasePortionFormat](../ibaseportionformat/)
* 클래스 [IHyperlinkContainer](../ihyperlinkcontainer/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)