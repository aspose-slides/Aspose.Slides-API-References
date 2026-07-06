---
title: BasePortionFormat
second_title: Aspose.Sildes for .NET API 참조
description: 공통 텍스트 부분 서식 속성.
type: docs
weight: 970
url: /ko/aspose.slides/baseportionformat/
---
## BasePortionFormat 클래스

공통 텍스트 부분 서식 속성.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 대체 언어의 Id를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 기본 IPresentationComponent 인터페이스를 가져올 수 있습니다. 읽기 전용 [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 복합 스크립트 글꼴 정보를 반환하거나 설정합니다. Null이면 글꼴이 정의되지 않았으며 마스터에서 상속되어야 합니다. 읽기/쓰기 [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 동아시아 글꼴 정보를 반환하거나 설정합니다. Null이면 글꼴이 정의되지 않았으며 마스터에서 상속되어야 합니다. 읽기/쓰기 [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | 텍스트 EffectFormat 속성을 반환합니다. 상속되지 않습니다. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 위첨자 또는 아래첨자 텍스트를 반환하거나 설정합니다. 값은 -100% (아래첨자)에서 100% (위첨자)까지입니다. **float.NaN**은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | 텍스트 FillFormat 속성을 반환합니다. 상속되지 않습니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | 글꼴이 굵게 표시되는지 여부를 결정합니다. 상속되지 않습니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 부분의 글꼴 높이를 반환하거나 설정합니다. **float.NaN**은 높이가 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | 글꼴이 이탤릭인지 여부를 결정합니다. 상속되지 않습니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | 텍스트 밑줄 유형을 반환하거나 설정합니다. 상속되지 않습니다. 읽기/쓰기 [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | 텍스트를 강조 표시하는 데 사용되는 색상을 반환합니다. 상속되지 않습니다. 읽기 전용 [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 밑줄 스타일이 자체 FillFormat 속성을 갖는지 또는 텍스트의 FillFormat 속성에서 상속받는지 여부를 결정합니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 밑줄 스타일이 자체 LineFormat 속성을 갖는지 또는 텍스트의 LineFormat 속성에서 상속받는지 여부를 결정합니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | 커닝을 켜야 하는 최소 글꼴 크기를 반환하거나 설정합니다. **float.NaN**은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 숫자가 텍스트 동아시아 언어별 세로 레이아웃을 무시하도록 해야 하는지 여부를 결정합니다. 상속되지 않습니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 교정 언어의 Id를 반환하거나 설정합니다. 맞춤법 및 문법 검사에 사용됩니다. 읽기/쓰기 String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | 라틴어 글꼴 정보를 반환하거나 설정합니다. Null이면 글꼴이 정의되지 않았으며 마스터에서 상속되어야 합니다. 읽기/쓰기 [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | 텍스트 외곽선용 LineFormat 속성을 반환합니다. 상속되지 않습니다. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | 텍스트 높이를 정규화할지 여부를 결정합니다. 상속되지 않습니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | 텍스트가 교정되지 않아야 하는지 여부를 결정합니다. 상속되지 않습니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 문자 사이 간격 증가 값을 반환하거나 설정합니다. **float.NaN**은 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | 텍스트 부분에 대해 맞춤법 검사 사용 여부를 가져오거나 설정합니다. 이 속성을 false 로 설정하면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true 로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 `false` 입니다. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | 텍스트의 취소선 유형을 반환하거나 설정합니다. 상속되지 않습니다. 읽기/쓰기 [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 기호 글꼴 정보를 반환하거나 설정합니다. Null이면 글꼴이 정의되지 않았으며 마스터에서 상속되어야 합니다. 읽기/쓰기 [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | 텍스트 대소문자 변환 유형을 반환하거나 설정합니다. 상속되지 않습니다. 읽기/쓰기 [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 밑줄 선 FillFormat 속성을 반환합니다. 상속되지 않습니다. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 밑줄 선을 외곽선하는 데 사용되는 LineFormat 속성을 반환합니다. 상속되지 않습니다. 읽기 전용 [`ILineFormat`](../ilineformat). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 지정된 객체와 비교합니다. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 해시 코드를 반환합니다. |

### 참조

* 클래스 [PVIObject](../pviobject)
* 인터페이스 [IBasePortionFormat](../ibaseportionformat)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->