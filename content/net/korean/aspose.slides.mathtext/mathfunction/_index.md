---
title: MathFunction
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 인수의 함수를 지정합니다.
type: docs
weight: 8720
url: /ko/aspose.slides.mathtext/mathfunction/
---
## MathFunction 클래스

인수의 함수를 지정합니다.

```csharp
public sealed class MathFunction : MathElementBase, IMathFunction
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MathFunction](mathfunction#constructor)(IMathElement, IMathElement) | MathFunction 클래스의 새 인스턴스를 초기화합니다. |
| [MathFunction](mathfunction#constructor_1)(string, IMathElement) | MathFunction 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathfunction/base) { get; } | 함수 인수 |
| [Name](../../aspose.slides.mathtext/mathfunction/name) { get; } | 함수 이름 예를 들어 함수 이름은 sin 및 cos입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 이 요소 위에 억양 표기(문자)를 설정합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 사용합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 사용합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 이 인스턴스를 인수로 사용하여 지정된 함수를 사용합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 사용합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 사용합니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 이 분자를 사용하여 지정된 분모와 함께 분수를 생성합니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 이 분자를 사용하여 지정된 분모와 함께 분수를 생성합니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 수학 요소를 괄호로 감쌉니다. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 괄호와 같은 지정된 문자 또는 다른 문자로 수학 요소를 프레임 형태로 감쌉니다. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다. |
| [GetChildren](../../aspose.slides.mathtext/mathfunction/getchildren)() | 자식 요소를 가져옵니다. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 하단 중괄호와 같은 그룹화 문자를 사용하거나 다른 문자를 사용하여 이 요소를 그룹에 배치합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 제한 없이 적분을 취합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 적분을 취합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 적분을 취합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 적분을 취합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 적분을 취합니다. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 수학 요소를 결합하여 수학 블록을 형성합니다. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 수학 텍스트를 결합하여 수학 블록을 형성합니다. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary 연산자를 생성합니다. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary 연산자를 생성합니다. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 이 요소 상단에 바를 설정합니다. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 하한을 취합니다. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 하한을 취합니다. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 아래 첨자를 생성합니다. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 아래 첨자를 생성합니다. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 위 첨자를 생성합니다. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 위 첨자를 생성합니다. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 상한을 취합니다. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 상한을 취합니다. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 이 요소를 테두리 상자에 배치합니다. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 이 요소를 테두리 상자에 배치합니다. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 이 요소를 시각적이지 않은 상자(논리적 그룹) 안에 배치합니다. 이 상자는 방정식이나 기타 수학 텍스트 구성 요소를 그룹화하는 데 사용됩니다. 예를 들어 정렬점이 있거나 없거나 연산자 에뮬레이터로, 줄 바꿈 지점으로, 혹은 줄 바꿈을 허용하지 않는 방식으로 그룹화될 수 있습니다. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 수직 배열에 넣습니다. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 이 요소 하단에 바를 설정합니다. |

### 예시

예:

```csharp
[C#]
MathFunction func = new MathFunction("sin", new MathematicalText("x"));
```

### 참고

* 클래스 [MathElementBase](../mathelementbase)
* 인터페이스 [IMathFunction](../imathfunction)
* 네임스페이스 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->