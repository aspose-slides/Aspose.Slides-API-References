---
title: PortionFormat
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 이 클래스는 텍스트 부분 서식 속성을 포함합니다. IPortionFormatEffectiveData./iportionformateffectivedata와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.
type: docs
weight: 9490
url: /ko/aspose.slides/portionformat/
---
## PortionFormat 클래스

이 클래스는 텍스트 부분 서식 속성을 포함합니다. [`IPortionFormatEffectiveData`](../iportionformateffectivedata)와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PortionFormat](portionformat)() | 새로운 [`PortionFormat`](../portionformat) 클래스의 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | 대체 언어의 Id를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 기본 IPresentationComponent 인터페이스를 가져올 수 있습니다. 읽기 전용 [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | 북마크 식별자를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | 복합 스크립트 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 Master에서 상속되어야 함을 의미합니다. 읽기/쓰기 [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | 동아시아 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 Master에서 상속되어야 함을 의미합니다. 읽기/쓰기 [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | 텍스트 EffectFormat 속성을 반환합니다. 상속이 적용되지 않음. 읽기 전용 [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | 위첨자 또는 아래첨자 텍스트를 반환하거나 설정합니다. 값은 -100% (아래첨자)부터 100% (위첨자)까지입니다. **float.NaN**은 값이 정의되지 않았으며 Master에서 상속되어야 함을 의미합니다. 읽기/쓰기 Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | 텍스트 FillFormat 속성을 반환합니다. 상속이 적용되지 않음. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | 글꼴이 굵게 표시되는지 여부를 결정합니다. 상속이 적용되지 않음. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | 부분의 글꼴 높이를 반환하거나 설정합니다. **float.NaN**은 높이가 정의되지 않았으며 Master에서 상속되어야 함을 의미합니다. 읽기/쓰기 Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | 글꼴이 기울임꼴인지 여부를 결정합니다. 상속이 적용되지 않음. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | 텍스트 밑줄 유형을 반환하거나 설정합니다. 상속이 적용되지 않음. 읽기/쓰기 [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | 텍스트를 강조 표시하는 데 사용되는 색상을 반환합니다. 상속이 적용되지 않음. 읽기 전용 [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | 하이퍼링크 관리자. 읽기 전용 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | 밑줄 스타일이 자체 FillFormat 속성을 가지는지 아니면 텍스트의 FillFormat 속성에서 상속받는지 여부를 결정합니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | 밑줄 스타일이 자체 LineFormat 속성을 가지는지 아니면 텍스트의 LineFormat 속성에서 상속받는지 여부를 결정합니다. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | 커닝을 켜야 하는 최소 글꼴 크기를 반환하거나 설정합니다. **float.NaN**은 값이 정의되지 않았으며 Master에서 상속되어야 함을 의미합니다. 읽기/쓰기 Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | 숫자가 텍스트 동양 언어별 수직 레이아웃을 무시해야 하는지 여부를 결정합니다. 상속이 적용되지 않음. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | 교정 언어의 Id를 반환하거나 설정합니다. 맞춤법 및 문법 검사를 위해 사용됩니다. 읽기/쓰기 String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | 라틴 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 Master에서 상속되어야 함을 의미합니다. 읽기/쓰기 [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | 텍스트 외곽선에 대한 LineFormat 속성을 반환합니다. 상속이 적용되지 않음. 읽기 전용 [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | 텍스트 높이를 정규화해야 하는지 여부를 결정합니다. 상속이 적용되지 않음. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | 텍스트가 교정되지 않아야 하는지 여부를 결정합니다. 상속이 적용되지 않음. 읽기/쓰기 [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | 스마트 태그를 정리해야 하는지 여부를 결정합니다. 상속이 적용되지 않음. 읽기/쓰기 Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | 문자 간 간격 증가량을 반환하거나 설정합니다. **float.NaN**은 값이 정의되지 않았으며 Master에서 상속되어야 함을 의미합니다. 읽기/쓰기 Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | 텍스트 부분에 대해 맞춤법 검사가 활성화되는지 여부를 나타내는 값을 가져오거나 설정합니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | 텍스트의 취소선 유형을 반환하거나 설정합니다. 상속이 적용되지 않음. 읽기/쓰기 [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | 기호 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 Master에서 상속되어야 함을 의미합니다. 읽기/쓰기 [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | 텍스트 대소문자 변환 유형을 반환하거나 설정합니다. 상속이 적용되지 않음. 읽기/쓰기 [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | 밑줄 라인의 FillFormat 속성을 반환합니다. 상속이 적용되지 않음. 읽기 전용 [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | 밑줄 라인을 외곽선 처리하는 데 사용되는 LineFormat 속성을 반환합니다. 상속이 적용되지 않음. 읽기 전용 [`ILineFormat`](../ilineformat). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 지정된 객체와 비교합니다. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | 상속이 적용된 효과적인 부분 서식 데이터를 가져옵니다. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 해시 코드를 반환합니다. |

## 비고

이 클래스는 특정 부분에 대해 정의된 텍스트 부분 서식 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않기 때문에 대부분의 경우 값이 "undefined"(정의되지 않음)이라는 의미를 갖게 됩니다.

상속을 포함한 효과적인 서식 매개변수 값을 얻으려면 [`GetEffective`](./geteffective) 메서드를 사용해야 하며, 이 메서드는 [`IPortionFormatEffectiveData`](../iportionformateffectivedata) 인스턴스를 반환합니다.

## 예제

다음 예제는 PowerPoint 프레젠테이션의 Paragraph 부분에 라틴 글꼴을 할당하는 방법을 보여줍니다.

```csharp
[C#]
//프레젠테이션 파일을 나타내는 프레젠테이션 객체를 인스턴스화합니다
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides는 이러한 특수 식별자를 사용합니다 (PowerPoint에서 사용되는 것과 유사합니다):
// +mn-lt - 본문 글꼴 라틴어 (소형 라틴 글꼴)
// +mj-lt - 제목 글꼴 라틴어 (대형 라틴 글꼴)
// +mn-ea - 본문 글꼴 동아시아 (소형 동아시아 글꼴)
// +mj-ea - 본문 글꼴 동아시아 (소형 동아시아 글꼴)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

## 참조

* 클래스 [BasePortionFormat](../baseportionformat)
* 인터페이스 [IPortionFormat](../iportionformat)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->