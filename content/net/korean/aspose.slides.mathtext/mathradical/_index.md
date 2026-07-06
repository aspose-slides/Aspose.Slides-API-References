---
title: MathRadical
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 기본과 선택적 차수로 구성된 근 함수를 지정합니다. 근 객체의 예는 .
type: docs
weight: 8940
url: /ko/aspose.slides.mathtext/mathradical/
---
## MathRadical 클래스

Specifies the radical function, consisting of a base, and an optional degree. Example of radical object is √𝑥.

```csharp
public sealed class MathRadical : MathElementBase, IMathRadical
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MathRadical](mathradical)(IMathElement, IMathElement) | MathRadical 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathradical/base) { get; } | Base 인수 |
| [Degree](../../aspose.slides.mathtext/mathradical/degree) { get; } | Degree 인수 |
| [HideDegree](../../aspose.slides.mathtext/mathradical/hidedegree) { get; set; } | Hide degree가 true이면 차수가 표시되지 않으며, 예: √𝑥 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 악센트 표시를 설정합니다 (이 요소 위에 표시되는 문자) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 취합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 취합니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 수학 요소를 괄호로 둘러쌉니다 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 괄호 등 지정된 문자로 수학 요소를 둘러싸서 프레이밍합니다 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [GetChildren](../../aspose.slides.mathtext/mathradical/getchildren)() | 자식 요소를 가져옵니다 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 하단 중괄호 등 그룹 문자로 이 요소를 그룹에 배치합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 제한 없이 적분을 취합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 적분을 취합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 적분을 취합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 적분을 취합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 적분을 취합니다 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 수학 요소를 결합하여 수학 블록을 형성합니다 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 수학 텍스트를 결합하여 수학 블록을 형성합니다 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary 연산자를 생성합니다 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary 연산자를 생성합니다 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 이 요소 위에 바를 설정합니다 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 지정된 인수로부터 주어진 차수의 수학적 루트를 지정합니다 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 지정된 인수로부터 주어진 차수의 수학적 루트를 지정합니다 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 하한을 취합니다 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 하한을 취합니다 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 아래 첨자를 생성합니다 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 아래 첨자를 생성합니다 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 왼쪽에 아래 첨자와 위첨자를 생성합니다 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 왼쪽에 아래 첨자와 위첨자를 생성합니다 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 오른쪽에 아래 첨자와 위첨자를 생성합니다 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 오른쪽에 아래 첨자와 위첨자를 생성합니다 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 위첨자를 생성합니다 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 위첨자를 생성합니다 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 상한을 취합니다 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 상한을 취합니다 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 이 요소를 테두리 박스에 배치합니다 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 이 요소를 테두리 박스에 배치합니다 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 이 요소를 논리적 그룹화용 비시각 박스에 배치합니다. 박스 객체는 예를 들어 정렬점 유무에 따른 연산자 에뮬레이터, 줄바꿈 지점, 또는 내부에서 줄바꿈을 허용하지 않는 그룹으로 사용할 수 있습니다 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 수직 배열에 배치합니다 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 이 요소 아래에 바를 설정합니다 |

### 예제

Example:

```csharp
[C#]
MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```

### 참고

* 클래스 [MathElementBase](../mathelementbase)
* 인터페이스 [IMathRadical](../imathradical)
* 네임스페이스 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->