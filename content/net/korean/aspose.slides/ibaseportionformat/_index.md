---
title: IBasePortionFormat
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 이 클래스는 텍스트 부분 서식 속성을 포함합니다. IPortionFormatEffectiveData./iportionformateffectivedata와 달리 이 클래스의 모든 속성은 쓰기 가능합니다.
type: docs
weight: 5310
url: /ko/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat 인터페이스

이 클래스는 텍스트 부분 서식 속성을 포함합니다. [`IPortionFormatEffectiveData`](../iportionformateffectivedata)와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.

```csharp
public interface IBasePortionFormat
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | 대체 언어의 Id를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | 복합 스크립트 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | 동아시아 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | 텍스트 EffectFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | 위첨자 또는 아래첨자 텍스트를 반환하거나 설정합니다. 값은 -100% (아래첨자)부터 100% (위첨자)까지입니다. **float.NaN**은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | 텍스트 FillFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | 글꼴이 굵게인지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | 부분의 글꼴 높이를 반환하거나 설정합니다. **float.NaN**은 높이가 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | 글꼴이 기울임인지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | 텍스트 밑줄 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | 텍스트 강조에 사용되는 색상을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | 밑줄 스타일이 자체 FillFormat 속성을 가지는지 또는 텍스트의 FillFormat 속성으로부터 상속받는지 여부를 결정합니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | 밑줄 스타일이 자체 LineFormat 속성을 가지는지 또는 텍스트의 LineFormat 속성으로부터 상속받는지 여부를 결정합니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | 커닝을 적용해야 하는 최소 글꼴 크기를 반환하거나 설정합니다. **float.NaN**은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | 숫자가 텍스트 동아시아 언어별 수직 레이아웃을 무시할지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | 교정 언어의 Id를 반환하거나 설정합니다. 맞춤법 및 문법 검사에 사용됩니다. 읽기/쓰기 String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | 라틴 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | 텍스트 외곽선에 대한 LineFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | 텍스트 높이가 정규화되어야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | 텍스트에 교정이 적용되지 않아야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | 문자 간 간격 증분을 반환하거나 설정합니다. **float.NaN**은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | 텍스트 부분에 대해 맞춤법 검사 사용 여부를 나타내는 값을 반환하거나 설정합니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 `false`입니다. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | 텍스트의 취소선 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | 기호 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | 텍스트 대소문자 변환 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | 밑줄 라인 FillFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | 밑줄 라인을 외곽선으로 만들 때 사용되는 LineFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [`ILineFormat`](../ilineformat). |

### 비고

이 클래스는 특정 부분에 대해 정의된 텍스트 부분 서식 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않으며, 대부분의 경우 "undefined" 의미의 값을 얻게 됨을 의미합니다.

상속을 포함한 실제 서식 매개변수 값을 얻으려면 [`GetEffective`](../iportionformat/geteffective) 메서드를 사용해야 하며, 이 메서드는 [`IPortionFormatEffectiveData`](../iportionformateffectivedata) 인스턴스를 반환합니다.

### 관련 항목

* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->