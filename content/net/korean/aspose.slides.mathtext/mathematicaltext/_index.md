---
title: MathematicalText
second_title: Aspose.Sildes for .NET API 참조
description: 수학 텍스트
type: docs
weight: 9060
url: /ko/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText 클래스

수학 텍스트

```csharp
public sealed class MathematicalText : MathElementBase, IMathematicalText
```

## 생성자

| Name | Description |
| --- | --- |
| [MathematicalText](mathematicaltext#constructor)() | 기본 생성자 (String.Empty 값을 생성) |
| [MathematicalText](mathematicaltext#constructor_1)(char) | 단일 기호로 MathText 생성 |
| [MathematicalText](mathematicaltext#constructor_2)(string) | 텍스트에서 MathematicalText 생성 |
| [MathematicalText](mathematicaltext#constructor_3)(string, IPortionFormat) | 텍스트와 형식 설정에서 MathematicalText 생성 |

## 속성

| Name | Description |
| --- | --- |
| [Format](../../aspose.slides.mathtext/mathematicaltext/format) { get; } | 텍스트 서식 속성 |
| [Value](../../aspose.slides.mathtext/mathematicaltext/value) { get; set; } | 텍스트 값 |

## 메서드

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 강세 부호를 설정합니다 (이 요소 위에 있는 문자) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 적용합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 적용합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 이 인스턴스를 인수로 사용하여 지정된 함수를 적용합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 적용합니다 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 적용합니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 수학 요소를 괄호로 둘러쌉니다 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 괄호나 다른 문자와 같이 지정된 문자로 수학 요소를 둘러쌉니다 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 이 인스턴스를 함수 이름으로 사용하여 인수에 대한 함수를 적용합니다 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 이 인스턴스를 함수 이름으로 사용하여 인수에 대한 함수를 적용합니다 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 하단 중괄호와 같은 그룹화 문자 또는 기타 문자를 사용하여 이 요소를 그룹에 배치합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 제한 없이 적분을 적용합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 적분을 적용합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 적분을 적용합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 적분을 적용합니다 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 적분을 적용합니다 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 수학 요소를 결합하여 수학 블록을 구성합니다 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 수학 텍스트를 결합하여 수학 블록을 구성합니다 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary 연산자를 생성합니다 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary 연산자를 생성합니다 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 이 요소 위에 바를 설정합니다 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 지정된 인수의 주어진 차수에 대한 수학적 근을 지정합니다. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 지정된 인수의 주어진 차수에 대한 수학적 근을 지정합니다. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 하한을 적용합니다 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 하한을 적용합니다 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 아래 첨자를 생성합니다 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 아래 첨자를 생성합니다 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 위 첨자를 생성합니다 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 위 첨자를 생성합니다 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 상한을 적용합니다 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 상한을 적용합니다 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 이 요소를 경계 상자에 배치합니다 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 이 요소를 경계 상자에 배치합니다 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 이 요소를 비시각적 상자(논리적 그룹화) 안에 배치합니다. 이 상자는 방정식 또는 다른 수학 텍스트 인스턴스의 구성 요소를 그룹화하는 데 사용됩니다. 박스화된 객체는 (예를 들어) 정렬점을 갖거나 갖지 않는 연산자 에뮬레이터 역할을 하거나, 줄 바꿈 지점으로 사용되거나, 내부에서 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 수직 배열에 배치합니다 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 이 요소 하단에 바를 설정합니다 |

### 예제

예시:

```csharp
[C#]
MathematicalText mathText = new MathematicalText("x+y");
```

### 참고

* 클래스 [MathElementBase](../mathelementbase)
* 인터페이스 [IMathematicalText](../imathematicaltext)
* 네임스페이스 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->