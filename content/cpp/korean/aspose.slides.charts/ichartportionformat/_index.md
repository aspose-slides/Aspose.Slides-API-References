---
title: IChartPortionFormat
second_title: Aspose.Slides for C++ API 참조
description: 차트에서 사용되는 차트 부분 서식 속성을 나타냅니다.
type: docs
weight: 807
url: /ko/aspose.slides.charts/ichartportionformat/
---
## IChartPortionFormat 클래스


차트에서 사용되는 차트 부분 서식 속성을 나타냅니다.

```cpp
class IChartPortionFormat : public virtual Aspose::Slides::IBasePortionFormat
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 모방합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 모방합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../../aspose.slides/ibaseportionformat/get_alternativelanguageid/)() | 대체 언어의 Id를 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_ComplexScriptFont](../../aspose.slides/ibaseportionformat/get_complexscriptfont/)() | 복합 스크립트 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../../aspose.slides/ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_EastAsianFont](../../aspose.slides/ibaseportionformat/get_eastasianfont/)() | 동아시아 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../../aspose.slides/ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ibaseportionformat/get_effectformat/)() | 텍스트 [EffectFormat](../../aspose.slides/effectformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual **float** [get_Escapement](../../aspose.slides/ibaseportionformat/get_escapement/)() | 위첨자 또는 아래첨자 텍스트를 반환합니다. 값은 -100% (아래첨자)부터 100% (위첨자)까지입니다. **std::numeric_limits<float>::quiet_NaN()**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ibaseportionformat/get_fillformat/)() | 텍스트 [FillFormat](../../aspose.slides/fillformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_FontBold](../../aspose.slides/ibaseportionformat/get_fontbold/)() | 글꼴이 굵게인지 여부를 판단합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_FontHeight](../../aspose.slides/ibaseportionformat/get_fontheight/)() | 부분의 글꼴 높이를 반환합니다. **std::numeric_limits<float>::quiet_NaN()**는 높이가 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_FontItalic](../../aspose.slides/ibaseportionformat/get_fontitalic/)() | 글꼴이 이탤릭인지 여부를 판단합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [TextUnderlineType](../../aspose.slides/textunderlinetype/) [get_FontUnderline](../../aspose.slides/ibaseportionformat/get_fontunderline/)() | 텍스트 밑줄 유형을 반환합니다. 상속이 적용되지 않습니다. 읽기 [TextUnderlineType](../../aspose.slides/textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_HighlightColor](../../aspose.slides/ibaseportionformat/get_highlightcolor/)() | 텍스트를 강조 표시하는 색상을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/get_ishardunderlinefill/)() | 밑줄 스타일이 자체 [FillFormat](../../aspose.slides/fillformat/) 속성을 가지고 있는지 또는 텍스트의 [FillFormat](../../aspose.slides/fillformat/) 속성으로부터 상속받는지 판단합니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/get_ishardunderlineline/)() | 밑줄 스타일이 자체 [LineFormat](../../aspose.slides/lineformat/) 속성을 가지고 있는지 또는 텍스트의 [LineFormat](../../aspose.slides/lineformat/) 속성으로부터 상속받는지 판단합니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../../aspose.slides/ibaseportionformat/get_kerningminimalsize/)() | 커닝을 활성화해야 하는 최소 글꼴 크기를 반환합니다. **std::numeric_limits<float>::quiet_NaN()**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Kumimoji](../../aspose.slides/ibaseportionformat/get_kumimoji/)() | 숫자가 동아시아 언어 전용 세로 텍스트 레이아웃을 무시해야 하는지 판단합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../../aspose.slides/ibaseportionformat/get_languageid/)() | 교정 언어의 Id를 반환합니다. 맞춤법 및 문법 검사에 사용됩니다. 읽기 [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_LatinFont](../../aspose.slides/ibaseportionformat/get_latinfont/)() | 라틴 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../../aspose.slides/ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ibaseportionformat/get_lineformat/)() | 텍스트 외곽선에 대한 [LineFormat](../../aspose.slides/lineformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_NormaliseHeight](../../aspose.slides/ibaseportionformat/get_normaliseheight/)() | 텍스트 높이를 정규화해야 하는지 판단합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_ProofDisabled](../../aspose.slides/ibaseportionformat/get_proofdisabled/)() | 텍스트를 교정하지 않아야 하는지 판단합니다. 상속이 적용되지 않습니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_Spacing](../../aspose.slides/ibaseportionformat/get_spacing/)() | 문자 간 간격 증가 값을 반환합니다. **std::numeric_limits<float>::quiet_NaN()**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 **float**. |
| virtual **bool** [get_SpellCheck](../../aspose.slides/ibaseportionformat/get_spellcheck/)() | 텍스트 부분에 대해 맞춤법 검사가 활성화되어 있는지를 나타내는 값을 가져옵니다. 이 속성이 **false**로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. **true**로 설정되면 맞춤법 검사가 허용됩니다. 기본값은 **false**입니다. |
| virtual [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) [get_StrikethroughType](../../aspose.slides/ibaseportionformat/get_strikethroughtype/)() | 텍스트의 취소선 유형을 반환합니다. 상속이 적용되지 않습니다. 읽기 [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_SymbolFont](../../aspose.slides/ibaseportionformat/get_symbolfont/)() | 기호 글꼴 정보를 반환합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기 [IFontData](../../aspose.slides/ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/) [get_TextCapType](../../aspose.slides/ibaseportionformat/get_textcaptype/)() | 텍스트 대문자화 유형을 반환합니다. 상속이 적용되지 않습니다. 읽기 [Slides::TextCapType](../../aspose.slides/textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_UnderlineFillFormat](../../aspose.slides/ibaseportionformat/get_underlinefillformat/)() | 밑줄 선 [FillFormat](../../aspose.slides/fillformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_UnderlineLineFormat](../../aspose.slides/ibaseportionformat/get_underlinelineformat/)() | 밑줄 선 외곽선에 사용되는 [LineFormat](../../aspose.slides/lineformat/) 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [ILineFormat](../../aspose.slides/ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사를 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사를 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_AlternativeLanguageId](../../aspose.slides/ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | 대체 언어의 Id를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../../aspose.slides/ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 복합 스크립트 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../../aspose.slides/ifontdata/). |
| virtual void [set_EastAsianFont](../../aspose.slides/ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 동아시아 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../../aspose.slides/ifontdata/). |
| virtual void [set_Escapement](../../aspose.slides/ibaseportionformat/set_escapement/)(**float**) | 위첨자 또는 아래첨자 텍스트를 설정합니다. 값은 -100% (아래첨자)부터 100% (위첨자)까지입니다. **std::numeric_limits<float>::quiet_NaN()**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| virtual void [set_FontBold](../../aspose.slides/ibaseportionformat/set_fontbold/)([NullableBool](../../aspose.slides/nullablebool/)) | 글꼴이 굵게인지 여부를 판단합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_FontHeight](../../aspose.slides/ibaseportionformat/set_fontheight/)(**float**) | 부분의 글꼴 높이를 설정합니다. **std::numeric_limits<float>::quiet_NaN()**는 높이가 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| virtual void [set_FontItalic](../../aspose.slides/ibaseportionformat/set_fontitalic/)([NullableBool](../../aspose.slides/nullablebool/)) | 글꼴이 이탤릭인지 여부를 판단합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_FontUnderline](../../aspose.slides/ibaseportionformat/set_fontunderline/)([TextUnderlineType](../../aspose.slides/textunderlinetype/)) | 텍스트 밑줄 유형을 설정합니다. 상속이 적용되지 않습니다. 쓰기 [TextUnderlineType](../../aspose.slides/textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../../aspose.slides/nullablebool/)) | 밑줄 스타일이 자체 [FillFormat](../../aspose.slides/fillformat/) 속성을 가지고 있는지 또는 텍스트의 [FillFormat](../../aspose.slides/fillformat/) 속성으로부터 상속받는지 판단합니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/set_ishardunderlineline/)([NullableBool](../../aspose.slides/nullablebool/)) | 밑줄 스타일이 자체 [LineFormat](../../aspose.slides/lineformat/) 속성을 가지고 있는지 또는 텍스트의 [LineFormat](../../aspose.slides/lineformat/) 속성으로부터 상속받는지 판단합니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_KerningMinimalSize](../../aspose.slides/ibaseportionformat/set_kerningminimalsize/)(**float**) | 커닝을 활성화해야 하는 최소 글꼴 크기를 설정합니다. **std::numeric_limits<float>::quiet_NaN()**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| virtual void [set_Kumimoji](../../aspose.slides/ibaseportionformat/set_kumimoji/)([NullableBool](../../aspose.slides/nullablebool/)) | 숫자가 동아시아 언어 전용 세로 텍스트 레이아웃을 무시해야 하는지 판단합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_LanguageId](../../aspose.slides/ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | 교정 언어의 Id를 설정합니다. 맞춤법 및 문법 검사에 사용됩니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_LatinFont](../../aspose.slides/ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 라틴 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../../aspose.slides/ifontdata/). |
| virtual void [set_NormaliseHeight](../../aspose.slides/ibaseportionformat/set_normaliseheight/)([NullableBool](../../aspose.slides/nullablebool/)) | 텍스트 높이를 정규화해야 하는지 판단합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_ProofDisabled](../../aspose.slides/ibaseportionformat/set_proofdisabled/)([NullableBool](../../aspose.slides/nullablebool/)) | 텍스트를 교정하지 않아야 하는지 판단합니다. 상속이 적용되지 않습니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_Spacing](../../aspose.slides/ibaseportionformat/set_spacing/)(**float**) | 문자 간 간격 증가 값을 설정합니다. **std::numeric_limits<float>::quiet_NaN()**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 **float**. |
| virtual void [set_SpellCheck](../../aspose.slides/ibaseportionformat/set_spellcheck/)(**bool**) | 텍스트 부분에 대해 맞춤법 검사가 활성화되어 있는지를 나타내는 값을 설정합니다. 이 속성이 **false**로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. **true**로 설정되면 맞춤법 검사가 허용됩니다. 기본값은 **false**입니다. |
| virtual void [set_StrikethroughType](../../aspose.slides/ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)) | 텍스트의 취소선 유형을 설정합니다. 상속이 적용되지 않습니다. 쓰기 [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/). |
| virtual void [set_SymbolFont](../../aspose.slides/ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 기호 글꼴 정보를 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 쓰기 [IFontData](../../aspose.slides/ifontdata/). |
| virtual void [set_TextCapType](../../aspose.slides/ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/)) | 텍스트 대문자화 유형을 설정합니다. 상속이 적용되지 않습니다. 쓰기 [Slides::TextCapType](../../aspose.slides/textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 템플릿 인자 n을 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [IBasePortionFormat](../../aspose.slides/ibaseportionformat/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)