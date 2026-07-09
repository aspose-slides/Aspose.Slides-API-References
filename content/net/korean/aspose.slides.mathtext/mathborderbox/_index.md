---
title: MathBorderBox
second_title: Aspose.Sildes for .NET API 참조
description: IMathElement 주위에 직사각형 또는 기타 테두리를 그립니다.
type: docs
weight: 8610
url: /ko/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox 클래스

Draws a rectangular or some other border around the IMathElement.

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## 생성자

| Name | Description |
| --- | --- |
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | 직사각형 테두리를 가진 MathBorderBox 요소를 생성합니다 |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | MathBorderBox 요소를 생성합니다 |

## 속성

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | 기본 인수 |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | 아래 가장자리 숨기기 (기본값은 false) - 테두리 상자의 아래 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | 왼쪽 가장자리 숨기기 (기본값은 false) - 테두리 상자의 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | 오른쪽 가장자리 숨기기 (기본값은 false) - 테두리 상자의 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | 위쪽 가장자리 숨기기 (기본값은 false) - 테두리 상자의 위쪽 가장자리의 숨김 또는 표시 상태를 지정합니다. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | 좌하단에서 우상단까지 취소선 (기본값은 false). 테두리 상자의 좌하단 모서리에서 우상단 모서리까지 대각선 취소선의 숨김 또는 표시 상태를 지정합니다. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | 가로 취소선 (기본값은 false) - 가로 취소선의 숨김 또는 표시 상태를 지정합니다. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | 좌상단에서 우하단까지 취소선 (기본값은 false). 테두리 상자의 좌상단 모서리에서 우하단 모서리까지 대각선 취소선의 숨김 또는 표시 상태를 지정합니다. |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | 세로 취소선 (기본값은 false) - 세로 취소선의 숨김 또는 표시 상태를 지정합니다. |

## 메서드

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 이 요소 위에 억음 부호(문자)를 설정합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 호출합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 호출합니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 이 분자를 사용하고 지정된 분모로 분수를 생성합니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 이 분자를 사용하고 지정된 분모로 분수를 생성합니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 이 분자를 사용하고 지정된 분모로 지정된 유형의 분수를 생성합니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 이 분자를 사용하고 지정된 분모로 지정된 유형의 분수를 생성합니다 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 수학 요소를 괄호로 둘러쌉니다 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 괄호와 같은 지정된 문자 또는 다른 문자로 수학 요소를 감쌉니다 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 호출합니다 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 호출합니다 |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | 자식 요소를 가져옵니다 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 하단 중괄호와 같은 그룹 문자 또는 다른 문자를 사용하여 이 요소를 그룹에 배치합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 제한 없이 적분을 수행합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 적분을 수행합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 적분을 수행합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 적분을 수행합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 적분을 수행합니다 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 수학 요소를 결합하여 수학 블록을 형성합니다 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 수학 텍스트를 결합하여 수학 블록을 형성합니다 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-항 연산자를 생성합니다 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-항 연산자를 생성합니다 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 이 요소의 상단에 바를 설정합니다 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 하한을 지정합니다 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 하한을 지정합니다 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 아래 첨자를 생성합니다 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 아래 첨자를 생성합니다 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 위 첨자를 생성합니다 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 위 첨자를 생성합니다 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 상한을 지정합니다 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 상한을 지정합니다 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 이 요소를 테두리 상자에 배치합니다 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 이 요소를 테두리 상자에 배치합니다 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 이 요소를 비시각적인 상자(논리적 그룹) 안에 배치합니다. 이 상자는 방정식이나 다른 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다. 예를 들어, 상자 안의 객체는 정렬 지점이 있거나 없거나 연산자 에뮬레이터 역할을 하거나, 줄 바꿈 지점으로 활용되거나, 내부 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 수직 배열에 넣습니다 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 이 요소의 하단에 바를 설정합니다 |

### 예제

예시:

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### 관련 항목

* 클래스 [MathElementBase](../mathelementbase)
* 인터페이스 [IMathBorderBox](../imathborderbox)
* 네임스페이스 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->