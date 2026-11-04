---
title: MathElementBase
second_title: Aspose.Sildes for .NET API 참조
description: 모든 파생 클래스에서 공통으로 사용되는 일부 메서드 구현을 포함하는 IMathElement의 기본 클래스입니다. 내부 전용입니다. 파생 클래스는 IMathElement여야 합니다.
type: docs
weight: 8700
url: /ko/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase 클래스

Base class for IMathElement with the implementation of some methods that are common to all inherited classes For internal use only. Inherited class must be IMathElement.

```csharp
public abstract class MathElementBase : IMathElement
```

## 메서드

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 이 요소 위에 억양 부호(문자)를 설정합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 호출합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 호출합니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | 이 분자와 지정된 분모를 사용하여 분수를 만듭니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | 이 분자와 지정된 분모를 사용하여 분수를 만듭니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 만듭니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 만듭니다 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | 수식 요소를 괄호로 둘러쌉니다 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | 수식 요소를 괄호나 기타 문자와 같은 지정된 문자로 둘러쌉니다 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | 이 인스턴스를 함수 이름으로 사용하여 인수 함수를 호출합니다 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | 이 인스턴스를 함수 이름으로 사용하여 인수 함수를 호출합니다 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | 하단 중괄호와 같은 그룹화 문자 또는 다른 문자를 사용하여 이 요소를 그룹에 배치합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | 제한 없이 적분을 가져옵니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | 적분을 가져옵니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | 적분을 가져옵니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 적분을 가져옵니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | 적분을 가져옵니다 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | 수학 요소를 결합하여 수학 블록을 형성합니다 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | 수학 텍스트를 결합하여 수학 블록을 형성합니다 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary 연산자를 생성합니다 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | N-ary 연산자를 생성합니다 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 이 요소 위에 수평선을 설정합니다 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMMathElement) | 하한을 가져옵니다 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | 하한을 가져옵니다 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMMathElement) | 아래 첨자를 생성합니다 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | 아래 첨자를 생성합니다 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMMathElement, IMMathElement) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMMathElement, IMMathElement) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMMathElement) | 위 첨자를 생성합니다 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | 위 첨자를 생성합니다 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMMathElement) | 상한을 가져옵니다 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | 상한을 가져옵니다 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | 이 요소를 경계 상자에 배치합니다 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | 이 요소를 경계 상자에 배치합니다 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 이 요소를 눈에 보이지 않는 상자(논리적 그룹) 안에 배치합니다. 이 상자는 수식이나 기타 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다. 예를 들어, 상자 객체는 정렬점이 있거나 없는 연산자 에뮬레이터 역할을 하거나, 줄 바꿈 지점으로 사용되거나, 내부에서 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 수직 배열에 배치합니다 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 이 요소 아래에 수평선을 설정합니다 |

### 참조

* 인터페이스 [IMathElement](../imathelement)
* 네임스페이스 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->