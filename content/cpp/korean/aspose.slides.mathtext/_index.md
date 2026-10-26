---
title: "Aspose::Slides::MathText"
second_title: Aspose.Slides C++ API 레퍼런스
description: 
type: docs
weight: 157
url: /ko/aspose.slides.mathtext/
---
## 클래스

| 클래스 | 설명 |
| --- | --- |
| [BaseScript](./basescript/) | 수학 스크립트 |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/)와 [Control](../aspose.slides/control/) 문자 속성 |
| [IMathAccent](./imathaccent/) | 기본과 결합 부호를 포함하는 악센트 함수를 지정합니다. 예시: \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | 수학 악센트를 만들 수 있습니다 |
| [IMathArray](./imatharray/) | 방정식 또는 기타 수학 객체의 수직 배열을 지정합니다 |
| [IMathArrayFactory](./imatharrayfactory/) | 수학 배열을 만들 수 있습니다 |
| [IMathBar](./imathbar/) | 기본 인수와 위바 또는 아래바를 포함하는 바 함수를 지정합니다 |
| [IMathBarFactory](./imathbarfactory/) | 수학 바를 만들 수 있습니다 |
| [IMathBlock](./imathblock/) | [MathParagraph](./mathparagraph/) 내부에 포함되고 자체 라인에서 시작하는 수학 텍스트 인스턴스를 지정합니다. 방정식, 식, 방정식 또는 식 배열, 수식 등을 포함한 모든 수학 영역은 수학 블록으로 표현됩니다. |
| [IMathBlockCollection](./imathblockcollection/) | 수학 블록([IMathBlock](./imathblock/))의 컬렉션 |
| [IMathBlockFactory](./imathblockfactory/) | 수학 블록을 만들 수 있습니다 |
| [IMathBorderBox](./imathborderbox/) | [IMathElement](./imathelement/) 주위에 직사각형 또는 기타 테두리를 그립니다. |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | 수학 테두리 상자를 만들 수 있습니다 |
| [IMathBox](./imathbox/) | 수학 요소의 논리적 박싱(패키징)을 지정합니다. 예를 들어, 박스화된 객체는 정렬 포인트 유무에 따라 연산자 에뮬레이터, 줄 바꿈 포인트 역할을 하거나 내부에서 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다. 예를 들어, \"==\" 연산자는 줄 바꿈을 방지하기 위해 박스화되어야 합니다. |
| [IMathBoxFactory](./imathboxfactory/) | 수학 박스를 만들 수 있습니다 |
| [IMathDelimiter](./imathdelimiter/) | 열고 닫는 문자(예: 괄호, 중괄호, 대괄호, 수직 막대)와 하나 이상의 수학 요소를 포함하고 지정된 문자로 구분되는 구분자 객체를 지정합니다. 예시: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | 수학 구분자를 만들 수 있습니다 |
| [IMathElement](./imathelement/) | 분수, 수학 텍스트, 함수, 여러 요소를 가진 식 등 모든 수학 요소의 기본 인터페이스 |
| [IMathElementCollection](./imathelementcollection/) | 수학 요소(MathElement)의 컬렉션을 나타냅니다 |
| [IMathematicalText](./imathematicaltext/) | 수학 텍스트 |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | [MathematicalText](./mathematicaltext/) 요소를 만들 수 있습니다 |
| [IMathFraction](./imathfraction/) | 분자와 분모가 분수선으로 구분되는 분수 객체를 지정합니다. 분수선은 속성에 따라 수평 또는 대각선일 수 있습니다. 또한 분수 객체는 분수선 없이 한 요소를 다른 요소 위에 배치하는 스택 함수를 나타내는 데 사용됩니다. |
| [IMathFractionFactory](./imathfractionfactory/) | 수학 분수를 만들 수 있습니다 |
| [IMathFunction](./imathfunction/) | 인수를 받는 함수를 지정합니다 |
| [IMathFunctionFactory](./imathfunctionfactory/) | 수학 함수를 만들 수 있습니다 |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | 보통 요소 간 관계를 강조하기 위해 식 위나 아래에 배치되는 그룹화 기호를 지정합니다 |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | 수학 그룹화 문자를 만들 수 있습니다 |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | 기본 왼쪽에 아래첨자와 위첨자를 배치한 Sub-Superscript 객체를 지정합니다 |
| [IMathLimit](./imathlimit/) | 기준선에 텍스트와 그 바로 위 또는 아래에 축소된 텍스트를 포함하는 Limit 객체를 지정합니다 |
| [IMathLimitFactory](./imathlimitfactory/) | [IMathLimit](./imathlimit/)을 만들 수 있습니다 |
| [IMathMatrix](./imathmatrix/) | 행 및 열에 배치된 자식 요소들로 구성된 Matrix 객체를 지정합니다. 매트릭스는 기본 구분자를 가지고 있지 않다는 점에 유의하십시오. 매트릭스를 괄호 안에 넣으려면 구분자 객체([IMathDelimiter](./imathdelimiter/))를 사용해야 합니다. Null 인자를 사용해 매트릭스에 빈 공간을 만들 수 있습니다. |
| [IMathMatrixFactory](./imathmatrixfactory/) | 수학 매트릭스를 만들 수 있습니다 |
| [IMathNaryOperator](./imathnaryoperator/) | 합계와 적분과 같은 N-ary 수학 객체를 지정합니다. 연산자, 기반(또는 피연산자) 및 선택적인 상한/하한으로 구성됩니다. N-ary 연산자 예: 합계, 합집합, 교집합, 적분 |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | [IMathNaryOperator](./imathnaryoperator/)을 만들 수 있습니다 |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | [IMathNaryOperator](./imathnaryoperator/)의 속성을 지정합니다 |
| [IMathParagraph](./imathparagraph/) | 수학 블록([IMathBlock](./imathblock/))의 컨테이너인 수학 단락 |
| [IMathParagraphFactory](./imathparagraphfactory/) | 수학 단락을 만들 수 있습니다 |
| [IMathPhantom](./imathphantom/) | 표시되지 않을 수도 있지만 자식 요소의 레이아웃에 영향을 주는 팬텀 수학 객체(<m:phant>)를 나타냅니다. 팬텀은 기본 표현식을 숨기면서 너비, 높이, 깊이를 유지해 수식을 정렬하거나 공간을 예약할 수 있습니다. 표시와 기하학 동작은 Show, ZeroWid, ZeroAsc, ZeroDesc, Transp와 같은 속성으로 제어됩니다. |
| [IMathPortion](./imathportion/) | 내부에 수학적 컨텍스트가 포함된 부분을 나타냅니다 |
| [IMathRadical](./imathradical/) | 기본과 선택적 차수를 포함하는 루트 함수를 지정합니다. 루트 객체 예: \\u221A\\uD835\\uDC65. |
| [IMathRadicalFactory](./imathradicalfactory/) | 수학 루트를 만들 수 있습니다 |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | 기본 오른쪽에 아래첨자와 위첨자를 배치한 Sub-Superscript 객체를 지정합니다 |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/)을 만들 수 있습니다 |
| [IMathSubscriptElement](./imathsubscriptelement/) | 기본 오른쪽 아래에 축소된 사이즈의 아래첨자를 배치한 subscript 객체를 지정합니다 |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | [IMathSubscriptElement](./imathsubscriptelement/)을 만들 수 있습니다 |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | 기본 오른쪽 위에 축소된 사이즈의 위첨자를 배치한 superscript 객체를 지정합니다 |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | [IMathSuperscriptElement](./imathsuperscriptelement/)을 만들 수 있습니다 |
| [MathAccent](./mathaccent/) | 기본과 결합 부호를 포함하는 악센트 함수를 지정합니다. 예시: \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | 수학 악센트를 만들 수 있습니다 |
| [MathArray](./matharray/) | 방정식 또는 기타 수학 객체의 수직 배열을 지정합니다 |
| [MathArrayFactory](./matharrayfactory/) | 수학 배열을 만들 수 있습니다 |
| [MathBar](./mathbar/) | 기본 인수와 위바 또는 아래바를 포함하는 바 함수를 지정합니다 |
| [MathBarFactory](./mathbarfactory/) | 수학 바를 만들 수 있습니다 |
| [MathBlock](./mathblock/) | [MathParagraph](./mathparagraph/) 내부에 포함되고 자체 라인에서 시작하는 수학 텍스트 인스턴스를 지정합니다. 방정식, 식, 방정식 또는 식 배열, 수식 등을 포함한 모든 수학 영역은 수학 블록으로 표현됩니다. |
| [MathBlockFactory](./mathblockfactory/) | 수학 블록을 만들 수 있습니다 |
| [MathBorderBox](./mathborderbox/) | [IMathElement](./imathelement/) 주위에 직사각형 또는 기타 테두리를 그립니다. |
| [MathBorderBoxFactory](./mathborderboxfactory/) | 수학 테두리 상자를 만들 수 있습니다 |
| [MathBox](./mathbox/) | 수학 요소의 논리적 박싱(패키징)을 지정합니다. 예를 들어, 박스화된 객체는 정렬 포인트 유무에 따라 연산자 에뮬레이터, 줄 바꿈 포인트 역할을 하거나 내부에서 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다. 예를 들어, \"==\" 연산자는 줄 바꿈을 방지하기 위해 박스화되어야 합니다. |
| [MathBoxFactory](./mathboxfactory/) | 수학 박스를 만들 수 있습니다 |
| [MathDelimiter](./mathdelimiter/) | 열고 닫는 문자(예: 괄호, 중괄호, 대괄호, 수직 막대)와 하나 이상의 수학 요소를 포함하고 지정된 문자로 구분되는 구분자 객체를 지정합니다. 예시: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | 수학 구분자를 만들 수 있습니다 |
| [MathElementBase](./mathelementbase/) | [IMathElement](./imathelement/)에 대한 기본 클래스로, 모든 파생 클래스에 공통적인 일부 메서드 구현을 포함합니다. 내부용으로만 사용됩니다. 파생 클래스는 [IMathElement](./imathelement/)이어야 합니다. |
| [MathematicalText](./mathematicaltext/) | 수학 텍스트 |
| [MathematicalTextFactory](./mathematicaltextfactory/) | [MathematicalText](./mathematicaltext/) 요소를 만들 수 있습니다 |
| [MathFraction](./mathfraction/) | 분자와 분모가 분수선으로 구분되는 분수 객체를 지정합니다. 분수선은 속성에 따라 수평 또는 대각선일 수 있습니다. 또한 분수 객체는 분수선 없이 한 요소를 다른 요소 위에 배치하는 스택 함수를 나타내는 데 사용됩니다. |
| [MathFractionFactory](./mathfractionfactory/) | 수학 분수를 만들 수 있습니다 |
| [MathFunction](./mathfunction/) | 인수를 받는 함수를 지정합니다 |
| [MathFunctionFactory](./mathfunctionfactory/) | 수학 함수를 만들 수 있습니다 |
| [MathGroupingCharacter](./mathgroupingcharacter/) | 보통 요소 간 관계를 강조하기 위해 식 위나 아래에 배치되는 그룹화 기호를 지정합니다 |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | 수학 그룹화 문자를 만들 수 있습니다 |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | 기본 왼쪽에 아래첨자와 위첨자를 배치한 Sub-Superscript 객체를 지정합니다 |
| [MathLimit](./mathlimit/) | 기준선에 텍스트와 그 바로 위 또는 아래에 축소된 텍스트를 포함하는 Limit 객체를 지정합니다 |
| [MathLimitFactory](./mathlimitfactory/) | [IMathLimit](./imathlimit/)을 만들 수 있습니다 |
| [MathMatrix](./mathmatrix/) | 행 및 열에 배치된 자식 요소들로 구성된 Matrix 객체를 지정합니다. 매트릭스는 기본 구분자를 가지고 있지 않다는 점에 유의하십시오. 매트릭스를 괄호 안에 넣으려면 구분자 객체([IMathDelimiter](./imathdelimiter/))를 사용해야 합니다. Null 인자를 사용해 매트릭스에 빈 공간을 만들 수 있습니다. |
| [MathMatrixFactory](./mathmatrixfactory/) | 수학 매트릭스를 만들 수 있습니다 |
| [MathNaryOperator](./mathnaryoperator/) | 합계와 적분과 같은 N-ary 수학 객체를 지정합니다. 연산자, 기반(또는 피연산자) 및 선택적인 상한/하한으로 구성됩니다. N-ary 연산자 예: 합계, 합집합, 교집합, 적분 |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | [IMathNaryOperator](./imathnaryoperator/)을 만들 수 있습니다 |
| [MathParagraph](./mathparagraph/) | [IMathBlock](./imathblock/) 블록의 컨테이너인 수학 단락 |
| [MathParagraphFactory](./mathparagraphfactory/) | 수학 단락을 만들 수 있습니다 |
| [MathPhantom](./mathphantom/) | 표시되지 않을 수도 있지만 자식 요소의 레이아웃에 영향을 주는 팬텀 수학 객체(<m:phant>)를 나타냅니다. 팬텀은 기본 표현식을 숨기면서 너비, 높이, 깊이를 유지해 수식을 정렬하거나 공간을 예약할 수 있습니다. 표시와 기하학 동작은 Show, ZeroWid, ZeroAsc, ZeroDesc, Transp와 같은 속성으로 제어됩니다. |
| [MathPortion](./mathportion/) | 내부에 수학적 컨텍스트가 포함된 부분을 나타냅니다 |
| [MathRadical](./mathradical/) | 기본과 선택적 차수를 포함하는 루트 함수를 지정합니다. 루트 객체 예: \\u221A\\uD835\\uDC65. |
| [MathRadicalFactory](./mathradicalfactory/) | 수학 루트를 만들 수 있습니다 |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | 기본 오른쪽에 아래첨자와 위첨자를 배치한 Sub-Superscript 객체를 지정합니다 |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/)을 만들 수 있습니다 |
| [MathSubscriptElement](./mathsubscriptelement/) | 기본 오른쪽 아래에 축소된 사이즈의 아래첨자를 배치한 subscript 객체를 지정합니다 |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | [IMathSubscriptElement](./imathsubscriptelement/)을 만들 수 있습니다 |
| [MathSuperscriptElement](./mathsuperscriptelement/) | 기본 오른쪽 위에 축소된 사이즈의 위첨자를 배치한 superscript 객체를 지정합니다 |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | [IMathSuperscriptElement](./imathsuperscriptelement/)을 만들 수 있습니다 |

## 열거형

| 열거형 | 설명 |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | 피연산자 내용에 대한 구분자의 위치와 크기 |
| [MathFractionTypes](./mathfractiontypes/) | 분수 유형 |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | 인자 하나를 받는 일반 수학 함수 |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | 인자 두 개를 받는 일반 수학 함수 |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | 수평 정렬 |
| [MathIntegralTypes](./mathintegraltypes/) | 수학 적분 유형 |
| [MathJustification](./mathjustification/) | 동일 단락 내에서 인접한 수학 텍스트 인스턴스들의 연속인 수학 단락의 정렬을 지정합니다 |
| [MathLimitLocations](./mathlimitlocations/) | n-ary 연산자에서 제한(아래첨자/위첨자)의 위치 |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | 적분을 제외한 Nary 연산자 [IMathNaryOperator](./imathnaryoperator/) 유형. 적분의 경우 [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | 매트릭스 또는 배열에서 열 사이의 수직 간격 유형 |
| [MathSpacingRules](./mathspacingrules/) | 매트릭스 열 사이의 간격(수평 간격) 유형 |
| [MathTopBotPositions](./mathtopbotpositions/) | 위/아래 위치 열거 |
| [MathVerticalAlignment](./mathverticalalignment/) | 수직 정렬 |