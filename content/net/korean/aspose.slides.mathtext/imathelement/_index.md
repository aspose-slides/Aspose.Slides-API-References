---
title: IMathElement
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 분수, 수학 텍스트, 함수, 여러 요소가 포함된 식 등 모든 수학 요소의 기본 인터페이스
type: docs
weight: 8230
url: /ko/aspose.slides.mathtext/imathelement/
---
## IMathElement 인터페이스

수학 요소(분수, 수학 텍스트, 함수, 여러 요소가 있는 식 등)의 기본 인터페이스

```csharp
public interface IMathElement
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | 이 요소 위에 억양 기호(문자)를 설정합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | 이 인스턴스를 인수와 지정된 추가 인수로 사용하여 지정된 함수를 호출합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | 이 인스턴스를 인수와 지정된 추가 인수로 사용하여 지정된 함수를 호출합니다 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | 이 분자를 사용하고 지정된 분모로 분수를 생성합니다 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | 이 분자를 사용하고 지정된 분모로 분수를 생성합니다 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | 수학 요소를 괄호로 감쌉니다 |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | 괄호와 같은 지정된 문자 또는 다른 문자로 이 요소를 프레임합니다 |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | 이 인스턴스를 함수 이름으로 사용하여 인수 함수를 호출합니다 |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | 이 인스턴스를 함수 이름으로 사용하여 인수 함수를 호출합니다 |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | 자식 요소를 가져옵니다 |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | 하단 중괄호 등과 같은 그룹 문자로 이 요소를 그룹에 배치합니다 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | 한계 없이 적분을 표시합니다 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | 적분을 표시합니다 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | 적분을 표시합니다 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 적분을 표시합니다 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | 적분을 표시합니다 |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | 수학 요소를 결합하여 수학 블록을 형성합니다 |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | 수학 텍스트를 결합하여 수학 블록을 형성합니다 |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary 연산자를 생성합니다 |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | N-ary 연산자를 생성합니다 |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | 이 요소 위에 바를 설정합니다 |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | 지정된 인수에서 지정된 차수의 수학적 루트를 지정합니다 |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | 지정된 인수에서 지정된 차수의 수학적 루트를 지정합니다 |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | 하한을 가져옵니다 |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | 하한을 가져옵니다 |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | 아래첨자를 생성합니다 |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | 아래첨자를 생성합니다 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | 위첨자를 생성합니다 |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | 위첨자를 생성합니다 |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | 상한을 가져옵니다 |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | 상한을 가져옵니다 |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | 이 요소를 테두리 상자에 배치합니다 |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | 이 요소를 테두리 상자에 배치합니다 |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | 이 요소를 논리적 그룹화인 비시각 박스에 배치합니다. 박스 객체는 예를 들어 정렬 지점이 있거나 없으며 연산자 에뮬레이터, 줄 바꿈 지점 또는 줄 바꿈을 방지하도록 그룹화될 수 있습니다 |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | 수직 배열에 넣습니다 |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | 이 요소 아래에 바를 설정합니다 |

### 예제

예시:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### 참고

* 네임스페이스 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->