---
title: Aspose.Slides.MathText
second_title: Aspose.Sildes for .NET API 참조
description: Microsoft PowerPoint 프레젠테이션에서 수학 텍스트 작업을 위한 클래스를 포함합니다.
type: docs
weight: 140
url: /ko/aspose.slides.mathtext/
---
Microsoft PowerPoint 프레젠테이션에서 수학 텍스트 작업을 위한 클래스를 포함합니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [BaseScript](./basescript) | Math script |
| [MathAccent](./mathaccent) | 베이스와 결합 부호를 포함하는 악센트 함수를 지정합니다. 예: 𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | 수학 악센트를 생성할 수 있습니다. |
| [MathArray](./matharray) | 방정식 또는 기타 수학 객체의 수직 배열을 지정합니다. |
| [MathArrayFactory](./matharrayfactory) | 수학 배열을 생성할 수 있습니다. |
| [MathBar](./mathbar) | 베이스 인수와 위바 또는 아래바로 구성된 바 함수를 지정합니다. |
| [MathBarFactory](./mathbarfactory) | 수학 바를 생성할 수 있습니다. |
| [MathBlock](./mathblock) | MathParagraph에 포함되고 자체 라인에서 시작되는 수학 텍스트 인스턴스를 지정합니다. 방정식, 표현식, 방정식 또는 표현식 배열 및 수식 등 모든 수학 영역은 MathBlock으로 표현됩니다. |
| [MathBlockFactory](./mathblockfactory) | MathBlock을 생성할 수 있습니다. |
| [MathBorderBox](./mathborderbox) | IMathElement 주위에 사각형 또는 기타 테두리를 그립니다. |
| [MathBorderBoxFactory](./mathborderboxfactory) | 수학 테두리 상자를 생성할 수 있습니다. |
| [MathBox](./mathbox) | 수학 요소의 논리적 박싱(패키징)을 지정합니다. 예를 들어, 박싱된 객체는 정렬점 유무에 관계없이 연산자 에뮬레이터, 줄 바꿈 지점 역할을 하거나 줄 바꿈이 허용되지 않도록 그룹화할 수 있습니다. 예: "==" 연산자는 줄 바꿈을 방지하기 위해 박싱되어야 합니다. |
| [MathBoxFactory](./mathboxfactory) | 수학 상자를 생성할 수 있습니다. |
| [MathDelimiter](./mathdelimiter) | 시작 및 종료 문자(예: 괄호, 중괄호, 대괄호, 수직 바)와 하나 이상의 수학 요소가 포함된 구분자 객체를 지정합니다. 지정된 문자로 구분됩니다. 예: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | 수학 구분자를 생성할 수 있습니다. |
| [MathElementBase](./mathelementbase) | IMathElement의 기본 클래스이며 모든 파생 클래스에 공통적인 일부 메서드 구현을 포함합니다. 내부 전용이며 파생 클래스는 IMathElement이어야 합니다. |
| [MathematicalText](./mathematicaltext) | Mathematical text |
| [MathematicalTextFactory](./mathematicaltextfactory) | MathematicalText 요소를 생성할 수 있습니다. |
| [MathFraction](./mathfraction) | 분자와 분모가 분수선으로 구분된 분수 객체를 지정합니다. 분수선은 속성에 따라 수평 또는 대각선일 수 있습니다. 또한 분수선이 없는 스택 함수도 이 객체로 표현됩니다. |
| [MathFractionFactory](./mathfractionfactory) | 수학 분수를 생성할 수 있습니다. |
| [MathFunction](./mathfunction) | 인수의 함수를 지정합니다. |
| [MathFunctionFactory](./mathfunctionfactory) | 수학 함수를 생성할 수 있습니다. |
| [MathGroupingCharacter](./mathgroupingcharacter) | 식 위나 아래에 그룹화 기호를 지정하여 요소 간 관계를 강조합니다. |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | 수학 그룹화 문자를 생성할 수 있습니다. |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | Sub-Superscript 객체를 지정합니다. 이는 베이스와 베이스 왼쪽에 배치된 아래첨자와 위첨자로 구성됩니다. |
| [MathLimit](./mathlimit) | Limit 객체를 지정합니다. 기준선 위에 텍스트와 바로 위하거나 아래에 배치되는 축소된 텍스트로 구성됩니다. |
| [MathLimitFactory](./mathlimitfactory) | IMathLimit을 생성할 수 있습니다. |
| [MathMatrix](./mathmatrix) | 자식 요소가 하나 이상의 행과 열에 배치된 Matrix 객체를 지정합니다. 매트릭스에는 기본 구분자가 없으며, 괄호 안에 배치하려면 IMathDelimiter 구분자 객체를 사용해야 합니다. Null 인수를 사용해 매트릭스에 빈칸을 만들 수 있습니다. |
| [MathMatrixFactory](./mathmatrixfactory) | 수학 매트릭스를 생성할 수 있습니다. |
| [MathNaryOperator](./mathnaryoperator) | Summation, Integral 등과 같은 N-ary 수학 객체를 지정합니다. 연산자, 베이스(또는 피연산자), 선택적 상한 및 하한으로 구성됩니다. 예: Summation, Union, Intersection, Integral |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | IMathNaryOperator를 생성할 수 있습니다. |
| [MathParagraph](./mathparagraph) | 수학 블록(IMathBlock)을 포함하는 수학 단락을 지정합니다. |
| [MathParagraphFactory](./mathparagraphfactory) | 수학 단락을 생성할 수 있습니다. |
| [MathPhantom](./mathphantom) | <m:phant> 태그를 사용하는 팬텀 수학 객체를 나타내며, 자식 요소의 레이아웃에 영향을 주지만 반드시 표시되지 않을 수 있습니다. 팬텀은 기본 표현식을 숨기면서 너비, 높이, 깊이를 유지해 수식을 정렬하거나 공간을 예약합니다. 표시 여부와 기하학적 동작은 Show, ZeroWid, ZeroAsc, ZeroDesc, Transp 속성으로 제어됩니다. |
| [MathPortion](./mathportion) | 수학적 컨텍스트가 포함된 부분을 나타냅니다. |
| [MathRadical](./mathradical) | 베이스와 선택적인 차수를 포함하는 radical 함수를 지정합니다. 예: √𝑥 |
| [MathRadicalFactory](./mathradicalfactory) | 수학 루트를 생성할 수 있습니다. |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | Sub-Superscript 객체를 지정합니다. 이는 베이스와 베이스 오른쪽에 배치된 아래첨자와 위첨자로 구성됩니다. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | IMathRightSubSuperscriptElementFactory를 생성할 수 있습니다. |
| [MathSubscriptElement](./mathsubscriptelement) | 아래첨자 객체를 지정합니다. 이는 베이스와 베이스 오른쪽 아래에 배치된 축소된 아래첨자로 구성됩니다. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | IMathSubscriptElement를 생성할 수 있습니다. |
| [MathSuperscriptElement](./mathsuperscriptelement) | 위첨자 객체를 지정합니다. 이는 베이스와 베이스 오른쪽 위에 배치된 축소된 위첨자로 구성됩니다. |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | IMathSuperscriptElement를 생성할 수 있습니다. |

## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [IMathAccent](./imathaccent) | 베이스와 결합 부호를 포함하는 악센트 함수를 지정합니다. 예: 𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | 수학 악센트를 생성할 수 있습니다. |
| [IMathArray](./imatharray) | 방정식 또는 기타 수학 객체의 수직 배열을 지정합니다. |
| [IMathArrayFactory](./imatharrayfactory) | 수학 배열을 생성할 수 있습니다. |
| [IMathBar](./imathbar) | 베이스 인수와 위바 또는 아래바로 구성된 바 함수를 지정합니다. |
| [IMathBarFactory](./imathbarfactory) | 수학 바를 생성할 수 있습니다. |
| [IMathBlock](./imathblock) | MathParagraph에 포함되고 자체 라인에서 시작되는 수학 텍스트 인스턴스를 지정합니다. 모든 수학 영역은 MathBlock으로 표현됩니다. |
| [IMathBlockCollection](./imathblockcollection) | MathBlock 컬렉션 |
| [IMathBlockFactory](./imathblockfactory) | MathBlock을 생성할 수 있습니다. |
| [IMathBorderBox](./imathborderbox) | IMathElement 주위에 사각형 또는 기타 테두리를 그립니다. |
| [IMathBorderBoxFactory](./imathborderboxfactory) | 수학 테두리 상자를 생성할 수 있습니다. |
| [IMathBox](./imathbox) | 수학 요소의 논리적 박싱(패키징)을 지정합니다. 예를 들어, 박싱된 객체는 정렬점 유무에 관계없이 연산자 에뮬레이터, 줄 바꿈 지점 역할을 하거나 줄 바꿈이 허용되지 않도록 그룹화할 수 있습니다. 예: "==" 연산자는 줄 바꿈을 방지하기 위해 박싱되어야 합니다. |
| [IMathBoxFactory](./imathboxfactory) | 수학 상자를 생성할 수 있습니다. |
| [IMathDelimiter](./imathdelimiter) | 시작 및 종료 문자(예: 괄호, 중괄호, 대괄호, 수직 바)와 하나 이상의 수학 요소가 포함된 구분자 객체를 지정합니다. 지정된 문자로 구분됩니다. 예: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | 수학 구분자를 생성할 수 있습니다. |
| [IMathElement](./imathelement) | 모든 수학 요소(분수, 수학 텍스트, 함수, 다중 요소 표현식 등)의 기본 인터페이스 |
| [IMathElementCollection](./imathelementcollection) | 수학 요소(MathElement) 컬렉션을 나타냅니다. |
| [IMathematicalText](./imathematicaltext) | Mathematical text |
| [IMathematicalTextFactory](./imathematicaltextfactory) | MathematicalText 요소를 생성할 수 있습니다. |
| [IMathFraction](./imathfraction) | 분자와 분모가 분수선으로 구분된 분수 객체를 지정합니다. 분수선은 속성에 따라 수평 또는 대각선일 수 있습니다. 또한 분수선이 없는 스택 함수도 이 객체로 표현됩니다. |
| [IMathFractionFactory](./imathfractionfactory) | 수학 분수를 생성할 수 있습니다. |
| [IMathFunction](./imathfunction) | 인수의 함수를 지정합니다. |
| [IMathFunctionFactory](./imathfunctionfactory) | 수학 함수를 생성할 수 있습니다. |
| [IMathGroupingCharacter](./imathgroupingcharacter) | 식 위나 아래에 그룹화 기호를 지정하여 요소 간 관계를 강조합니다. |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | 수학 그룹화 문자를 생성할 수 있습니다. |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | Sub-Superscript 객체를 지정합니다. 이는 베이스와 베이스 왼쪽에 배치된 아래첨자와 위첨자로 구성됩니다. |
| [IMathLimit](./imathlimit) | Limit 객체를 지정합니다. 기준선 위에 텍스트와 바로 위하거나 아래에 배치되는 축소된 텍스트로 구성됩니다. |
| [IMathLimitFactory](./imathlimitfactory) | IMathLimit을 생성할 수 있습니다. |
| [IMathMatrix](./imathmatrix) | 자식 요소가 하나 이상의 행과 열에 배치된 Matrix 객체를 지정합니다. 매트릭스에는 기본 구분자가 없으며, 괄호 안에 배치하려면 IMathDelimiter 구분자 객체를 사용해야 합니다. Null 인수를 사용해 매트릭스에 빈칸을 만들 수 있습니다. |
| [IMathMatrixFactory](./imathmatrixfactory) | 매트릭스를 생성할 수 있습니다. |
| [IMathNaryOperator](./imathnaryoperator) | Summation, Integral 등과 같은 N-ary 수학 객체를 지정합니다. 연산자, 베이스(또는 피연산자), 선택적 상한 및 하한으로 구성됩니다. 예: Summation, Union, Intersection, Integral |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | IMathNaryOperator를 생성할 수 있습니다. |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | IMathNaryOperator의 속성을 지정합니다. |
| [IMathParagraph](./imathparagraph) | 수학 블록(IMathBlock)을 포함하는 수학 단락을 지정합니다. |
| [IMathParagraphFactory](./imathparagraphfactory) | 수학 단락을 생성할 수 있습니다. |
| [IMathPhantom](./imathphantom) | <m:phant> 태그를 사용하는 팬텀 수학 객체를 나타내며, 자식 요소의 레이아웃에 영향을 주지만 반드시 표시되지 않을 수 있습니다. 팬텀은 기본 표현식을 숨기면서 너비, 높이, 깊이를 유지해 수식을 정렬하거나 공간을 예약합니다. 표시 여부와 기하학적 동작은 Show, ZeroWid, ZeroAsc, ZeroDesc, Transp 속성으로 제어됩니다. |
| [IMathPortion](./imathportion) | 수학적 컨텍스트가 포함된 부분을 나타냅니다. |
| [IMathRadical](./imathradical) | 베이스와 선택적인 차수를 포함하는 radical 함수를 지정합니다. 예: √𝑥 |
| [IMathRadicalFactory](./imathradicalfactory) | 수학 루트를 생성할 수 있습니다. |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | Sub-Superscript 객체를 지정합니다. 이는 베이스와 베이스 오른쪽에 배치된 아래첨자와 위첨자로 구성됩니다. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | IMathRightSubSuperscriptElementFactory를 생성할 수 있습니다. |
| [IMathSubscriptElement](./imathsubscriptelement) | 아래첨자 객체를 지정합니다. 이는 베이스와 베이스 오른쪽 아래에 배치된 축소된 아래첨자로 구성됩니다. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | IMathSubscriptElement를 생성할 수 있습니다. |
| [IMathSuperscriptElement](./imathsuperscriptelement) | 위첨자 객체를 지정합니다. 이는 베이스와 베이스 오른쪽 위에 배치된 축소된 위첨자로 구성됩니다. |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | IMathSuperscriptElement를 생성할 수 있습니다. |

## 열거형

| 열거형 | 설명 |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | 피연산자 내용에 대한 구분자의 위치 및 크기 |
| [MathFractionTypes](./mathfractiontypes) | Fraction Types |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | 단일 인수에 대한 일반 수학 함수 |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | 두 인수에 대한 일반 수학 함수 |
| [MathHorizontalAlignment](./mathhorizontalalignment) | Horizontal Alignment |
| [MathIntegralTypes](./mathintegraltypes) | 수학 적분 유형 |
| [MathJustification](./mathjustification) | 수학 단락의 정렬 방식을 지정합니다(같은 단락 내에 인접한 수학 텍스트 인스턴스들의 시리즈). |
| [MathLimitLocations](./mathlimitlocations) | N-ary 연산자에서 한계(아래첨자/위첨자)의 위치. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | N-ary 연산자(IMathNaryOperator) 유형(적분 제외). 적분은 [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) 참고 |
| [MathRowSpacingRule](./mathrowspacingrule) | 매트릭스 또는 배열의 열 사이에 적용되는 수직 간격 유형 |
| [MathSpacingRules](./mathspacingrules) | 매트릭스 열 사이의 간격(수평 간격) 유형 |
| [MathTopBotPositions](./mathtopbotpositions) | 상/하 위치 열거형 |
| [MathVerticalAlignment](./mathverticalalignment) | Vertical Alignment |