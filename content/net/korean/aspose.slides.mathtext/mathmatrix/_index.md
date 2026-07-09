---
title: MathMatrix
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 하나 이상의 행과 열에 배치된 자식 요소들로 구성된 Matrix 객체를 지정합니다. 행렬에는 내장 구분 기호가 없다는 점에 유의해야 합니다. 행렬을 괄호 안에 넣으려면 구분 기호 객체 IMathDelimiter를 사용해야 합니다. Null 인수를 사용하여 행렬에 빈 공간을 만들 수 있습니다.
type: docs
weight: 8850
url: /ko/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix 클래스

행과 열이 하나 이상으로 배치된 자식 요소들로 구성된 Matrix 객체를 지정합니다. 행렬에는 내장 구분 기호가 없다는 점에 유의해야 합니다. 행렬을 괄호 안에 넣으려면 구분 기호 객체(IMathDelimiter)를 사용해야 합니다. Null 인수를 사용하여 행렬에 빈 공간을 만들 수 있습니다.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | MathMatrix 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | 주위 텍스트에 대한 수직 정렬을 지정합니다. 가능한 값은 top, bottom, center 입니다. 기본값: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | 행렬의 열 수 |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | 행렬의 열 사이 수평 간격 값; ColumnGapRule가 3("Exactly")으로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. ColumnGapRule가 4("Multiple")으로 설정된 경우 단위는 0.5 em 증가 단위의 개수로 해석됩니다. 다른 경우는 무시됩니다. 기본값: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | 행렬의 열 사이 수평 간격 유형; 수평 간격 단위는 ems 또는 포인트(twips로 저장)일 수 있습니다. 기본값: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | 빈 행렬 요소에 대한 자리 표시자를 숨깁니다. 기본값: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | 행렬 요소 |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | twips(포인트의 1/20) 단위의 최소 열 너비. 간격(gap spacing, “Column Gap” 또는 “Gap Width”이라고도 함)은 MinColumnWidth에 추가되어 전체 행렬 열 간격(다른 열의 동일한 가장자리 사이 거리)을 결정합니다. 기본값: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | 행렬의 행 수 |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | 행렬의 행 사이 수직 간격 값; RowGapRule가 3("Exactly")으로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. RowGapRule가 4("Multiple")으로 설정된 경우 단위는 반줄(half-lines)로 해석됩니다. 기본값: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | 행렬의 행 사이 수직 간격 유형; 수직 간격 단위는 줄(lines) 또는 포인트(twips로 저장)일 수 있습니다. 기본값: SingleSpacingGap (0) |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 이 요소 위에 억양 기호(문자)를 설정합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 호출합니다. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 호출합니다. |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | 지정된 열을 삭제합니다. |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | 지정된 행을 삭제합니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 이 분자와 지정된 분모로 분수를 생성합니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 이 분자와 지정된 분모로 분수를 생성합니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 수학 요소를 괄호로 둘러쌉니다. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 감쌉니다. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 호출합니다. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 호출합니다. |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | 자식 요소를 가져옵니다. |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | 지정된 열의 수평 정렬을 가져옵니다. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 이 요소를 하단 중괄호를 사용하여 그룹에 배치합니다. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 이 요소를 하단 중괄호 등과 같은 그룹화 문자로 그룹에 배치합니다. |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | 지정된 열 뒤에 새 열을 삽입합니다. 새 열의 모든 요소는 초기에는 null입니다. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | 지정된 열 앞에 새 열을 삽입합니다. 새 열의 모든 요소는 초기에는 null입니다. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | 지정된 행 뒤에 새 행을 삽입합니다. 새 행의 모든 요소는 초기에는 null입니다. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | 지정된 행 앞에 새 행을 삽입합니다. 새 행의 모든 요소는 초기에는 null입니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 제한 없이 적분을 수행합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 적분을 수행합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 적분을 수행합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 적분을 수행합니다. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 적분을 수행합니다. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 수학 요소를 결합하여 수학 블록을 형성합니다. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 수학 텍스트를 결합하여 수학 블록을 형성합니다. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary 연산자를 생성합니다. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary 연산자를 생성합니다. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 이 요소 위에 바를 설정합니다. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 주어진 차수에 대한 수학적 루트를 지정된 인수에서 지정합니다. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 주어진 차수에 대한 수학적 루트를 지정된 인수에서 지정합니다. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | 지정된 열의 수평 정렬을 설정합니다. |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | 지정된 열들의 수평 정렬을 설정합니다. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 하한을 지정합니다. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 하한을 지정합니다. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 아래첨자를 생성합니다. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 아래첨자를 생성합니다. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 위첨자를 생성합니다. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 위첨자를 생성합니다. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 상한을 지정합니다. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 상한을 지정합니다. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 이 요소를 테두리 상자에 배치합니다. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 이 요소를 테두리 상자에 배치합니다. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 이 요소를 비시각 박스(논리적 그룹화) 안에 배치합니다. 이는 방정식이나 기타 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다. 박스화된 객체는 예를 들어 정렬점이 있거나 없는 연산자 에뮬레이터, 줄 바꿈 지점으로 작동하거나, 내부에 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 수직 배열에 넣습니다. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 이 요소 아래에 바를 설정합니다. |

### 예제

예시:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### 참고

* 클래스 [MathElementBase](../mathelementbase)
* 인터페이스 [IMathMatrix](../imathmatrix)
* 네임스페이스 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->