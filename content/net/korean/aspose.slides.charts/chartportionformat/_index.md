---
title: ChartPortionFormat
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 이 클래스는 차트에서 사용되는 차트 부분 서식 속성을 포함합니다. IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata와 달리 이 클래스의 모든 속성은 쓸 수 있습니다.
type: docs
weight: 1430
url: /ko/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat 클래스

이 클래스는 차트에서 사용되는 차트 부분 서식 속성을 포함합니다. [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)와 달리, 이 클래스의 모든 속성은 쓸 수 있습니다.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 대체 언어의 Id를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 기본 IPresentationComponent 인터페이스를 가져올 수 있습니다. 읽기 전용 [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 복합 스크립트 폰트 정보를 반환하거나 설정합니다. Null은 폰트가 정의되지 않았으며 마스터에서 상속받아야 함을 의미합니다. 읽기/쓰기 [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 동아시아 폰트 정보를 반환하거나 설정합니다. Null은 폰트가 정의되지 않았으며 마스터에서 상속받아야 함을 의미합니다. 읽기/쓰기 [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | 텍스트 EffectFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 위첨자 또는 아래첨자 텍스트를 반환하거나 설정합니다. -100% (아래첨자)에서 100% (위첨자)까지의 값입니다. **float.NaN**은 값이 정의되지 않았으며 마스터에서 상속받아야 함을 의미합니다. 읽기/쓰기 Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | 텍스트 FillFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | 폰트가 굵게인지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 부분의 폰트 높이를 반환하거나 설정합니다. **float.NaN**은 높이가 정의되지 않았으며 마스터에서 상속받아야 함을 의미합니다. 읽기/쓰기 Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | 폰트가 이탤릭인지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | 텍스트 밑줄 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | 텍스트를 강조 표시하는 색상을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 밑줄 스타일이 자체 FillFormat 속성을 가지는지 또는 텍스트의 FillFormat 속성으로부터 상속받는지 결정합니다. 읽기/쓰기 [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 밑줄 스타일이 자체 LineFormat 속성을 가지는지 또는 텍스트의 LineFormat 속성으로부터 상속받는지 결정합니다. 읽기/쓰기 [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | 커닝을 켜야 하는 최소 폰트 크기를 반환하거나 설정합니다. **float.NaN**은 값이 정의되지 않았으며 마스터에서 상속받아야 함을 의미합니다. 읽기/쓰기 Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 숫자가 텍스트 동아시아 언어 별 수직 레이아웃을 무시하도록 할지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 교정 언어의 Id를 반환하거나 설정합니다. 맞춤법 및 문법 검사에 사용됩니다. 읽기/쓰기 String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | 라틴 폰트 정보를 반환하거나 설정합니다. Null은 폰트가 정의되지 않았으며 마스터에서 상속받아야 함을 의미합니다. 읽기/쓰기 [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | 텍스트 테두리용 LineFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | 텍스트 높이를 정규화할지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | 텍스트를 교정하지 않을지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 문자 간격 증가값을 반환하거나 설정합니다. **float.NaN**은 값이 정의되지 않았으며 마스터에서 상속받아야 함을 의미합니다. 읽기/쓰기 Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | 텍스트 부분에 대한 맞춤법 검사가 활성화되어 있는지 여부를 가져오거나 설정합니다. 이 속성을 false 로 설정하면 텍스트 요소의 맞춤법 검사가 억제됩니다. true 로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 `false`입니다. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | 텍스트에 대한 취소선 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 기호 폰트 정보를 반환하거나 설정합니다. Null은 폰트가 정의되지 않았으며 마스터에서 상속받아야 함을 의미합니다. 읽기/쓰기 [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | 텍스트 대문자화 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 밑줄 선의 FillFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 밑줄 선을 테두리하는 데 사용되는 LineFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [`ILineFormat`](../../aspose.slides/ilineformat). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 지정된 객체와 비교합니다. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 해시 코드를 반환합니다. |

### 비고

이 클래스는 특정 부분에 정의된 텍스트 부분 서식 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않으므로 대부분의 경우 "정의되지 않음"을 의미하는 값을 얻게 됩니다.

상속된 값을 포함한 실제 서식 매개변수 값을 가져오려면 [`GetEffective`](../../aspose.slides/portionformat/geteffective) 메서드를 사용해야 하며, 이 메서드는 [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) 인스턴스를 반환합니다.

### 참고

* 클래스 [BasePortionFormat](../../aspose.slides/baseportionformat)
* 인터페이스 [IChartPortionFormat](../ichartportionformat)
* 네임스페이스 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->