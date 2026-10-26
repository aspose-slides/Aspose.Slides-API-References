---
title: MathBox
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 수학 요소의 논리적 박싱(패키징)을 지정합니다. 예를 들어, 박스가 적용된 객체는 정렬 지점이 있거나 없을 때 연산자 에뮬레이터로 사용되거나, 줄 바꿈 지점으로 사용되거나, 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. 예를 들어, 연산자를 박스 처리하면 줄 바꿈을 방지할 수 있습니다.
type: docs
weight: 8630
url: /ko/aspose.slides.mathtext/mathbox/
---
## MathBox 클래스

수학 요소의 논리적 박싱(패키징)을 지정합니다. 예를 들어, 박스가 적용된 객체는 정렬 지점이 있거나 없을 때 연산자 에뮬레이터로 사용될 수 있으며, 줄 바꿈 지점으로 사용되거나 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. 예를 들어, "==" 연산자는 줄 바꿈을 방지하기 위해 박스 처리되어야 합니다.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | 지정된 요소를 인수로 하여 MathBox를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | true인 경우, 이 연산자 에뮬레이터가 정렬 지점으로 작동합니다; 즉, 다른 방정식에서 지정된 정렬 지점과 정렬될 수 있습니다. 기본값: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | 기본 인수 |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | 미분 true인 경우, 박스는 미분 기호로 동작하며(예: 적분식의 𝑑𝑥), 수학적 미분에 적합한 가로 간격을 받습니다. 기본값: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | 명시적 구분은 Box 객체 시작에 줄 바꿈이 있는지 여부를 지정합니다. 또한 현재 수학 텍스트 라인의 정렬 지점으로 사용할 이전 라인 수학 텍스트의 연산자 번호를 지정합니다. 가능한 값: 1..255 기본값: 0 (명시적 줄 바꿈 없음) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break 이 속성은 객체 박스에 대한 "깨지지 않음" 특성을 지정합니다. true인 경우, 박스 내부에서 줄 바꿈이 발생하지 않습니다. 이는 둘 이상의 이진 연산자로 구성된 연산자 에뮬레이터에 중요할 수 있습니다. 이 요소가 지정되지 않으면, 박스 내부에서 줄 바꿈이 발생할 수 있습니다. 기본값: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator. true인 경우, 박스와 그 내용물이 단일 연산자로 동작하며 연산자의 특성을 상속합니다. 예를 들어, 문자 자체가 줄 바꿈 지점으로 작동하고 다른 연산자와 정렬될 수 있습니다. Operator Emulator는 하나 이상의 글리프가 결합하여 연산자를 형성할 때 종종 사용됩니다(예: '=='). 기본값: false |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 이 요소 상단에 악센트 표시(문자)를 설정합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 취합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 취합니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 이 분자를 사용하여 지정된 분모와 함께 분수를 만듭니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 이 분자를 사용하여 지정된 분모와 함께 분수를 만듭니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 이 분자를 사용하여 지정된 유형의 분수와 지정된 분모를 만듭니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 이 분자를 사용하여 지정된 유형의 분수와 지정된 분모를 만듭니다. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 수학 요소를 괄호로 묶습니다. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 지정된 문자(예: 괄호 또는 다른 문자)로 수학 요소를 프레임처럼 묶습니다. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다. |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | 자식 요소를 가져옵니다. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 하단 중괄호 또는 다른 그룹화 문자와 같은 문자로 이 요소를 그룹에 배치합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 제한 없이 적분을 취합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 적분을 취합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 적분을 취합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 적분을 취합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 적분을 취합니다. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 수학 요소를 결합하여 수학 블록을 형성합니다. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 수학 텍스트를 결합하여 수학 블록을 형성합니다. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary 연산자를 만듭니다. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary 연산자를 만듭니다. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 이 요소 상단에 수평선을 설정합니다. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 하한을 취합니다. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 하한을 취합니다. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 아래 첨자를 만듭니다. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 아래 첨자를 만듭니다. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 왼쪽에 아래 첨자와 위 첨자를 만듭니다. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 왼쪽에 아래 첨자와 위 첨자를 만듭니다. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 오른쪽에 아래 첨자와 위 첨자를 만듭니다. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 오른쪽에 아래 첨자와 위 첨자를 만듭니다. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 위 첨자를 만듭니다. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 위 첨자를 만듭니다. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 상한을 취합니다. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 상한을 취합니다. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 이 요소를 경계 박스에 배치합니다. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 이 요소를 경계 박스에 배치합니다. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 이 요소를 비시각적 박스(논리적 그룹화) 안에 배치하여 방정식이나 기타 수학 텍스트의 구성 요소를 그룹화합니다. 박스가 적용된 객체는 예를 들어 정렬 지점이 있거나 없을 때 연산자 에뮬레이터로 사용되거나 줄 바꿈 지점으로 사용되거나 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 수직 배열에 배치합니다. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 이 요소 하단에 수평선을 설정합니다. |

### 예제

예시:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### 관련 항목

* 클래스 [MathElementBase](../mathelementbase)
* 인터페이스 [IMathBox](../imathbox)
* 네임스페이스 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->