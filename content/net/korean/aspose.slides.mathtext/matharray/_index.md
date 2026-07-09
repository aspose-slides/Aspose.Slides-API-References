---
title: MathArray
second_title: Aspose.Sildes for .NET API 참조
description: 수식 또는 기타 수학 객체의 수직 배열을 지정합니다
type: docs
weight: 8550
url: /ko/aspose.slides.mathtext/matharray/
---
## MathArray 클래스

수식이나 기타 수학 객체의 수직 배열을 지정합니다

```csharp
public sealed class MathArray : MathElementBase, IMathArray
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MathArray](matharray#constructor_1)(IEnumerable&lt;IMathElement&gt;) | 수학 배열을 만들고 지정된 요소를 그 안에 배치합니다 |
| [MathArray](matharray#constructor)(IMathElement) | 수학 배열을 만들고 지정된 요소를 그 안에 배치합니다 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/matharray/arguments) { get; } | 배열의 항목 집합 |
| [BaseJustification](../../aspose.slides.mathtext/matharray/basejustification) { get; set; } | 배열을 주변 텍스트에 상대적으로 정렬 방식을 지정합니다. 배열 외부 텍스트는 배열 객체의 아래쪽, 위쪽 또는 중앙에 정렬될 수 있습니다. 기본값: Center |
| [MaximumDistribution](../../aspose.slides.mathtext/matharray/maximumdistribution) { get; set; } | Maximum Distribution true인 경우, 배열은 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 배치됩니다. |
| [ObjectDistribution](../../aspose.slides.mathtext/matharray/objectdistribution) { get; set; } | Object Distribution true인 경우, 배열의 내용이 배열 객체의 최대 너비에 맞게 배치됩니다. |
| [RowSpacing](../../aspose.slides.mathtext/matharray/rowspacing) { get; set; } | 배열 행 사이의 간격입니다. RowSpacingRule이 3(Exactly)으로 설정된 경우에만 사용되며, 이 경우 측정 단위는 포인트이며 Multiple인 경우 절반 줄이 측정 단위입니다. 기본값: 0 |
| [RowSpacingRule](../../aspose.slides.mathtext/matharray/rowspacingrule) { get; set; } | 배열 요소 사이의 수직 간격 유형입니다. 기본값: SingleLineGap |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 강세 기호를 설정합니다(이 요소 위에 표시되는 문자). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 지정된 함수를 이 인스턴스를 인수로 사용합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 지정된 함수를 이 인스턴스를 인수로 사용합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 지정된 함수를 이 인스턴스를 인수로 사용합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 지정된 함수를 이 인스턴스를 인수로 사용하고 추가 인수를 지정합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 지정된 함수를 이 인스턴스를 인수로 사용하고 추가 인수를 지정합니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 이 분자와 지정된 분모로 분수를 만듭니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 이 분자와 지정된 분모로 분수를 만듭니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 만듭니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 만듭니다. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 수학 요소를 괄호로 둘러쌉니다. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 감쌉니다. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다. |
| [GetChildren](../../aspose.slides.mathtext/matharray/getchildren)() | 자식 요소를 가져옵니다. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 하단 중괄호와 같은 그룹화 문자 또는 다른 문자를 사용하여 이 요소를 그룹에 배치합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 제한 없이 적분을 취합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 적분을 취합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 적분을 취합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 적분을 취합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 적분을 취합니다. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 수학 요소를 결합하여 수학 블록을 형성합니다. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 수학 텍스트를 결합하여 수학 블록을 형성합니다. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary 연산자를 생성합니다. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary 연산자를 생성합니다. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 이 요소의 위에 바를 설정합니다. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 하한을 취합니다. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 하한을 취합니다. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 아래첨자를 생성합니다. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 아래첨자를 생성합니다. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 위첨자를 생성합니다. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 위첨자를 생성합니다. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 상한을 취합니다. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 상한을 취합니다. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 이 요소를 경계 상자에 배치합니다. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 이 요소를 경계 상자에 배치합니다. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 이 요소를 비시각 박스(논리적 그룹) 안에 배치합니다. 이 박스는 방정식이나 다른 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다. 박스 객체는 예를 들어 정렬점이 있거나 없거나 연산자 에뮬레이터 역할을 하거나 줄 바꿈 지점으로 사용되거나 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 수직 배열에 넣습니다. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 이 요소의 아래에 바를 설정합니다. |

### 예제

예제:

```csharp
[C#]
MathArray mathArray = new MathArray(new MathematicalText("item1"));
```

### 참고

* 클래스 [MathElementBase](../mathelementbase)
* 인터페이스 [IMathArray](../imatharray)
* 네임스페이스 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->