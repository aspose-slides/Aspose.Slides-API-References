---
title: IMathElement
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 수학 요소(분수, 수학 텍스트, 함수, 다중 요소를 포함한 식 등)의 기본 인터페이스
type: docs
weight: 8250
url: /ko/aspose.slides.mathtext/imathelement/
---
## IMathElement 인터페이스

Base 인터페이스 of any mathematical element: fraction, mathmatical text, function, expression with multiple elements etc

```csharp
public interface IMathElement
```

## 메서드

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | 이 요소 위에 억양 부호(문자)를 설정합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 적용합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 적용합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | 이 인스턴스를 인수로 사용하여 지정된 함수를 적용합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 적용합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 적용합니다 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | 이 분자를 사용하여 지정된 분모와 함께 분수를 생성합니다 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | 이 분자를 사용하여 지정된 분모와 함께 분수를 생성합니다 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | 이 분자를 사용하여 지정된 유형과 지정된 분모와 함께 분수를 생성합니다 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | 이 분자를 사용하여 지정된 유형과 지정된 분모와 함께 분수를 생성합니다 |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | 수학 요소를 괄호로 감쌉니다 |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | 이 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러쌉니다 |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 적용합니다 |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 적용합니다 |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | 자식 요소를 가져옵니다 |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | 이 요소를 아래쪽 중괄호를 사용하여 그룹에 배치합니다 |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | 이 요소를 아래쪽 중괄호와 같은 그룹 문자 또는 다른 문자로 그룹에 배치합니다 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | 제한 없이 적분을 적용합니다 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | 적분을 적용합니다 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | 적분을 적용합니다 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 적분을 적용합니다 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | 적분을 적용합니다 |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | 수학 요소를 결합하여 수학 블록을 형성합니다 |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | 수학 텍스트를 결합하여 수학 블록을 형성합니다 |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-항 연산자를 생성합니다 |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | N-항 연산자를 생성합니다 |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | 이 요소 위에 막대를 설정합니다 |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | 지정된 인수를 사용하여 주어진 차수의 수학적 루트를 지정합니다 |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | 지정된 인수를 사용하여 주어진 차수의 수학적 루트를 지정합니다 |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | 하한을 설정합니다 |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | 하한을 설정합니다 |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | 아래첨자를 생성합니다 |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | 아래첨자를 생성합니다 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | 위첨자를 생성합니다 |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | 위첨자를 생성합니다 |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | 상한을 설정합니다 |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | 상한을 설정합니다 |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | 이 요소를 테두리 상자에 배치합니다 |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | 이 요소를 테두리 상자에 배치합니다 |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | 이 요소를 비시각적 박스(논리적 그룹)에 배치하여 방정식 구성 요소나 기타 수학 텍스트를 그룹화합니다. 박스 객체는 예를 들어 정렬점이 있거나 없거나 연산자 에뮬레이터, 줄 바꿈 지점 역할을 하거나 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다 |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | 수직 배열에 배치합니다 |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | 이 요소 아래에 막대를 설정합니다 |

### 예제

Example:
```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### 참조

* 네임스페이스 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->