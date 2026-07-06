---
title: MathBlock
second_title: Aspose.Sildes for .NET API 레퍼런스
description: MathParagraph에 포함되고 자체 라인에서 시작되는 수학 텍스트 인스턴스를 지정합니다. 방정식, 식, 방정식 또는 식 배열 및 공식 등을 포함한 모든 수학 영역은 수학 블록으로 표현됩니다.
type: docs
weight: 8590
url: /ko/aspose.slides.mathtext/mathblock/
---
## MathBlock 클래스

MathParagraph에 포함되고 자체 라인에서 시작되는 수학 텍스트 인스턴스를 지정합니다. 방정식, 수식, 방정식 또는 수식 배열, 그리고 공식 등을 포함한 모든 수학 영역은 수학 블록으로 표현됩니다.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MathBlock](mathblock#constructor)() | MathBlock 클래스의 새 인스턴스를 초기화합니다. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | 새 수학 블록을 만들고 지정된 요소들을 그 안에 넣습니다. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | 새 수학 블록을 만들고 지정된 요소를 그 안에 넣습니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | 컬렉션에 실제로 포함된 자식 수학 요소의 수를 가져옵니다. 읽기 전용 Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | 자식 요소 컬렉션을 수정할 수 있기 때문에 false를 반환합니다. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | 지정된 인덱스의 IMathElement를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 이 요소 위에 억양 부호(문자)를 설정합니다. |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | 수학 요소를 컬렉션 끝에 추가합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 이 인스턴스를 인수로 사용하고 추가 인수로 지정된 요소를 사용하여 함수를 호출합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 이 인스턴스를 인수로 사용하고 추가 인수로 지정된 문자열을 사용하여 함수를 호출합니다. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | 컬렉션의 모든 요소를 제거합니다. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | 컬렉션에 특정 값이 포함되어 있는지 확인합니다. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | 지정된 배열에 복사합니다. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | 대괄호 없이 구분 문자로 자식 요소를 구분합니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 이 분자와 지정된 분모를 사용하여 분수를 만듭니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 이 분자와 지정된 분모를 사용하여 분수를 만듭니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 만듭니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 만듭니다. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 수학 요소를 괄호로 둘러쌉니다. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | 이 블록의 자식 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸서 프레임을 만듭니다. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | 이 블록의 자식 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸고 구분 문자로 구분합니다. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 호출합니다. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 호출합니다. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | 자식 요소를 가져옵니다. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 하단 중괄호 등 그룹화 문자를 사용하여 이 요소를 그룹에 배치합니다. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | 컬렉션에서 특정 수학 요소의 인덱스를 결정합니다. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | 지정된 인덱스에 MathElement를 컬렉션에 삽입합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 제한 없이 적분을 수행합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 적분을 수행합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 적분을 수행합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 적분을 수행합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 적분을 수행합니다. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | 수학 요소를 이 수학 블록과 결합합니다. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | 수학 텍스트를 이 수학 블록과 결합합니다. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | 다른 수학 블록을 이 블록과 결합합니다. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary 연산자를 생성합니다. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary 연산자를 생성합니다. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 이 요소의 위에 막대를 설정합니다. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 주어진 차수에 대한 수학적 루트를 지정된 인수로 설정합니다. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 주어진 차수에 대한 수학적 루트를 지정된 인수로 설정합니다. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | 컬렉션에서 지정된 인덱스의 요소를 제거합니다. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 하한을 설정합니다. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 하한을 설정합니다. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 아래 첨자를 만듭니다. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 아래 첨자를 만듭니다. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 위 첨자를 생성합니다. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 위 첨자를 생성합니다. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 상한을 설정합니다. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 상한을 설정합니다. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 이 요소를 테두리 상자에 배치합니다. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 이 요소를 테두리 상자에 배치합니다. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 이 요소를 비시각적 상자(논리적 그룹화)에 배치합니다. 이 상자는 방정식이나 다른 수학 텍스트 인스턴스의 구성 요소를 그룹화하는 데 사용됩니다. 예를 들어 연산자 에뮬레이터 역할을 하거나 (정렬점 유무와 관계없이) 줄 바꿈 지점이 되거나 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | 자식 요소를 수직 배열에 배치합니다. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 이 요소의 아래에 막대를 설정합니다. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | [`MathBlock`](../mathblock)의 내용을 MathML로 저장합니다. |

### 예제

예시:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### 참고

* 클래스 [MathElementBase](../mathelementbase)
* 인터페이스 [IMathBlock](../imathblock)
* 네임스페이스 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->