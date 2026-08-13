---
title: MathMatrix
second_title: Aspose.Slides for C++ API 레퍼런스
description: 행과 열이 하나 이상 배치된 자식 요소들로 구성된 Matrix 객체를 지정합니다. 행렬에는 기본 구분 기호가 없다는 점을 유의해야 합니다. 행렬을 대괄호 안에 넣으려면 구분 기호 객체(IMathDelimiter)를 사용해야 합니다. Null 인수를 사용하여 행렬에 빈 공간을 만들 수 있습니다.
type: docs
weight: 950
url: /ko/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix 클래스

Matrix 객체를 지정합니다. 이 객체는 하나 이상의 행과 열에 배치된 자식 요소들로 구성됩니다. 행렬에는 기본 구분 기호가 없다는 점에 유의해야 합니다. 행렬을 대괄호 안에 배치하려면 구분 기호 객체([IMathDelimiter](../imathdelimiter/))를 사용해야 합니다. null 인수를 사용하여 행렬에 빈 공간을 만들 수 있습니다.

```cpp
class MathMatrix : public Aspose::Slides::MathText::MathElementBase,
                   public Aspose::Slides::MathText::IMathMatrix,
                   public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## 메서드

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | 이 요소 위에 억양 기호(문자)를 설정합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 호출합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 호출합니다. |
| void [DeleteColumn](./deletecolumn/)(**int32_t**) override | 지정된 열을 삭제합니다. |
| void [DeleteRow](./deleterow/)(**int32_t**) override | 지정된 행을 삭제합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | 수학 요소를 괄호로 감쌉니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | 괄호 등 지정된 문자로 수학 요소를 프레임처럼 감쌉니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 포함 NaN과도 동등하지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 포함 NaN과도 동등하지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 이 인스턴스를 함수 이름으로 사용하여 인수에 대한 함수를 호출합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | 이 인스턴스를 함수 이름으로 사용하여 인수에 대한 함수를 호출합니다. |
| [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() override | 주변 텍스트에 대한 수직 정렬을 지정합니다. 가능한 값은 top, bottom, center이며 기본값은 Center입니다. |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | 행렬의 열 수 |
| **uint32_t** [get_ColumnGap](./get_columngap/)() override | 행렬 열 사이의 가로 간격 값입니다. ColumnGapRule이 3("Exactly")이면 단위는 twips(1/20포인트)이며, 4("Multiple")이면 0.5 em 증분 수로 해석됩니다. 다른 경우는 무시됩니다. 기본값: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() override | 행렬 열 사이의 가로 간격 유형입니다. 가로 간격 단위는 em 또는 포인트(twips로 저장)이며 기본값은 SingleSpacingGap(0)입니다. |
| **bool** [get_HidePlaceholders](./get_hideplaceholders/)() override | 빈 행렬 요소에 대한 자리표시자를 숨깁니다. 기본값: false |
| **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() override | 최소 열 너비(twips, 1/20포인트)입니다. Gap spacing(\u201CColumn Gap\u201D 또는 \u201CGap Width\u201D이라고도 함)은 MinColumnWidth에 추가되어 전체 Matrix [Column](../../aspose.slides/column/) 간격(다른 열의 동일한 가장자리 사이 거리)을 결정합니다. 기본값: 0. |
| **int32_t** [get_RowCount](./get_rowcount/)() override | 행렬의 행 수 |
| **uint32_t** [get_RowGap](./get_rowgap/)() override | 행렬 행 사이의 세로 간격 값입니다. RowGapRule이 3("Exactly")이면 단위는 twips(1/20포인트)이며, 4("Multiple")이면 반 라인 단위로 해석됩니다. 기본값: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() override | 행렬 행 사이의 세로 간격 유형입니다. 세로 간격 단위는 라인 또는 포인트(twips로 저장)이며 기본값은 SingleSpacingGap(0)입니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | 자식 요소를 가져옵니다. |
| [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) override | 지정된 열의 가로 정렬을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | 이 요소를 하단 중괄호를 사용하여 그룹에 배치합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | 하단 중괄호 등 그룹화 문자를 사용하여 이 요소를 그룹에 배치합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | 행렬의 요소입니다. |
| void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 행렬의 요소입니다. |
| void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) override | 지정된 열 뒤에 새 열을 삽입합니다. 새 열의 모든 요소는 처음에 null입니다. |
| void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) override | 지정된 열 앞에 새 열을 삽입합니다. 새 열의 모든 요소는 처음에 null입니다. |
| void [InsertRowAfter](./insertrowafter/)(**int32_t**) override | 지정된 행 뒤에 새 행을 삽입합니다. 새 행의 모든 요소는 처음에 null입니다. |
| void [InsertRowBefore](./insertrowbefore/)(**int32_t**) override | 지정된 행 앞에 새 행을 삽입합니다. 새 행의 모든 요소는 처음에 null입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | 적분을 수행합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 적분을 수행합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | 한계 없이 적분을 수행합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | 적분을 수행합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | 적분을 수행합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 수학 요소를 결합하여 수학 블록을 형성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | 수학 텍스트를 결합하여 수학 블록을 형성합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠급니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| [MathMatrix](./mathmatrix/)(**int32_t**, **int32_t**) | [MathMatrix](./) 클래스의 새 인스턴스를 초기화합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 형식 복제를 가능하게 합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | N-ary 연산자를 생성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | N-ary 연산자를 생성합니다. |
| [Object](../../system/object/object/)() | 객체를 생성하고 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | 이 요소의 상단에 바를 설정합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 지정된 인수에서 주어진 차수의 수학적 근을 지정합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | 지정된 인수에서 주어진 차수의 수학적 근을 지정합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 참조 기준으로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) override | 주변 텍스트에 대한 수직 정렬을 지정합니다. 가능한 값은 top, bottom, center이며 기본값은 Center입니다. |
| void [set_ColumnGap](./set_columngap/)(**uint32_t**) override | 행렬 열 사이의 가로 간격 값입니다. ColumnGapRule이 3("Exactly")이면 단위는 twips(1/20포인트)이며, 4("Multiple")이면 0.5 em 증분 수로 해석됩니다. 다른 경우는 무시됩니다. 기본값: 0 |
| void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) override | 행렬 열 사이의 가로 간격 유형입니다. 가로 간격 단위는 em 또는 포인트(twips로 저장)이며 기본값은 SingleSpacingGap(0)입니다. |
| void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) override | 빈 행렬 요소에 대한 자리표시자를 숨깁니다. 기본값: false |
| void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) override | 최소 열 너비(twips, 1/20포인트)입니다. Gap spacing(\u201CColumn Gap\u201D 또는 \u201CGap Width\u201D이라고도 함)은 MinColumnWidth에 추가되어 전체 Matrix [Column](../../aspose.slides/column/) 간격(다른 열의 동일한 가장자리 사이 거리)을 결정합니다. 기본값: 0. |
| void [set_RowGap](./set_rowgap/)(**uint32_t**) override | 행렬 행 사이의 세로 간격 값입니다. RowGapRule이 3("Exactly")이면 단위는 twips(1/20포인트)이며, 4("Multiple")이면 반 라인 단위로 해석됩니다. 기본값: 0 |
| void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) override | 행렬 행 사이의 세로 간격 유형입니다. 세로 간격 단위는 라인 또는 포인트(twips로 저장)이며 기본값은 SingleSpacingGap(0)입니다. |
| void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | 지정된 열의 가로 정렬을 설정합니다. |
| void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | 지정된 열들의 가로 정렬을 설정합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 하한을 지정합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | 하한을 지정합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 아래첨자를 생성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | 아래첨자를 생성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 위첨자를 생성합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | 위첨자를 생성합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 상한을 지정합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | 상한을 지정합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하세요. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | 이 요소를 경계 상자에 배치합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | 이 요소를 경계 상자에 배치합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | 이 요소를 비시각적 박스(논리적 그룹) 안에 배치합니다. 이는 방정식이나 기타 수학 텍스트 구성 요소를 그룹화하는 데 사용됩니다. 예를 들어, 이 박스 객체는 정렬 포인트가 있거나 없거나 연산자 에뮬레이터 역할을 하거나 줄 바꿈 지점으로 사용할 수 있으며, 내부에서 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | 수직 배열에 배치합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | 이 요소의 하단에 바를 설정합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 구현하여 잠금 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴하고 모든 내부 데이터 구조를 해제합니다. |

## 비고

예시:
```cpp
System::SharedPtr<IMathMatrix> matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## 참고

* 클래스 [MathElementBase](../mathelementbase/)
* 클래스 [IMathMatrix](../imathmatrix/)
* 클래스 [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* 네임스페이스 [Aspose::Slides::MathText](../)
* Library [Aspose.Slides](../../)