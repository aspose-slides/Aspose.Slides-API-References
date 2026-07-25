---
title: MathBox
second_title: Aspose.Slides for C++ API リファレンス
description: 数学要素の論理的なボックス化（パッケージ化）を指定します。たとえば、ボックス化されたオブジェクトは、整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして機能したり、内部で改行が許可されないようにグループ化されたりします。例として、\"==\" 演算子は改行を防ぐためにボックス化すべきです。
type: docs
weight: 742
url: /ja/aspose.slides.mathtext/mathbox/
---
## MathBox クラス

数学要素の論理的なボックス化（パッケージ化）を指定します。たとえば、ボックス化されたオブジェクトは、整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして機能したり、行内で改行が許可されないようにグループ化されたりします。例として、\"==\" 演算子は改行を防ぐためにボックス化すべきです。

```cpp
class MathBox : public Aspose::Slides::MathText::MathElementBase,
                public Aspose::Slides::MathText::IMathBox,
                public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## メソッド

| Method | 説明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | この要素の上部にある文字（アクセントマーク）を設定します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | このインスタンスを引数として指定された関数を取得します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | このインスタンスを引数として指定された関数を取得します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | このインスタンスを引数として指定された関数を取得します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | この分子と指定された分母で分数を作成します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | この分子と指定された分母で分数を作成します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | 指定された型の分数を、この分子と指定された分母で作成します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | 指定された型の分数を、この分子と指定された分母で作成します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | 数学要素を括弧で囲みます |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | 数学要素を指定された文字（括弧やその他の文字）で囲みます |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | このインスタンスを関数名として、引数の関数を取得します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | このインスタンスを関数名として、引数の関数を取得します |
| **bool** [get_AlignmentPoint](./get_alignmentpoint/)() override | true の場合、この演算子エミュレータは整列ポイントとして機能します。つまり、他の式で指定された整列ポイントと合わせることができます。デフォルト: false |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() override | 基底引数 |
| **bool** [get_Differential](./get_differential/)() override | 微分: true の場合、ボックスは微分として機能し（例: \\uD835\\uDC51\\uD835\\uDC65 が積分対象にある場合）、数学的微分に適した横幅を取得します。デフォルト: false |
| **uint8_t** [get_ExplicitBreak](./get_explicitbreak/)() override | 明示的な改行は、Box オブジェクトの開始時に改行があるかどうかを指定します。これにより、行は Box オブジェクトの開始位置で折り返されます。また、前の行の数式テキストにある演算子の番号を、現在の行の数式テキストの整列ポイントとして使用するかを指定します。可能な値: 1..255 デフォルト: 0（明示的な改行なし） |
| **bool** [get_NoBreak](./get_nobreak/)() override | 改行なし: このプロパティはオブジェクトボックスの「改行不可」属性を指定します。true の場合、ボックス内部で改行は発生しません。これは、複数の二項演算子からなる演算子エミュレータに重要です。指定されない場合、ボックス内部で改行が可能です。デフォルト: true |
| **bool** [get_OperatorEmulator](./get_operatoremulator/)() override | 演算子エミュレータ: true の場合、ボックスとその内容は単一の演算子として振る舞い、演算子のプロパティを継承します。つまり、例えば文字が改行ポイントとして機能し、他の演算子と整列できるということです。'==' のように複数の字形が結合して演算子になる場合に演算子エミュレータが使用されます。デフォルト値: false |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | 子要素を取得します |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | この要素を下側の波かっこでグループに配置します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | 下側の波かっこなどのグルーピング文字を使用してこの要素をグループに配置します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | 積分を取得します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 積分を取得します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | 上限・下限なしで積分を取得します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | 積分を取得します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | 積分を取得します |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 数学要素を結合し、数学ブロックを形成します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | 数学テキストを結合し、数学ブロックを形成します |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリオブジェクトを使用してください。 |
|  [MathBox](./mathbox/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | [MathBox](./) を指定された要素を引数として初期化します |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | N 項演算子を作成します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | N 項演算子を作成します |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | この要素の上部にバーを設定します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 指定された引数から、指定された次数の数学的根を指定します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | 指定された引数から、指定された次数の数学的根を指定します |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます |
| void [set_AlignmentPoint](./set_alignmentpoint/)(**bool**) override | true の場合、この演算子エミュレータは整列ポイントとして機能します。つまり、他の式で指定された整列ポイントと合わせることができます。デフォルト: false |
| void [set_Differential](./set_differential/)(**bool**) override | 微分: true の場合、ボックスは微分として機能し（例: \\uD835\\uDC51\\uD835\\uDC65 が積分対象にある場合）、数学的微分に適した横幅を取得します。デフォルト: false |
| void [set_ExplicitBreak](./set_explicitbreak/)(**uint8_t**) override | 明示的な改行は、Box オブジェクトの開始時に改行があるかどうかを指定します。これにより、行は Box オブジェクトの開始位置で折り返されます。また、前の行の数式テキストにある演算子の番号を、現在の行の数式テキストの整列ポイントとして使用するかを指定します。可能な値: 1..255 デフォルト: 0（明示的な改行なし） |
| void [set_NoBreak](./set_nobreak/)(**bool**) override | 改行なし: このプロパティはオブジェクトボックスの「改行不可」属性を指定します。true の場合、ボックス内部で改行は発生しません。これは、複数の二項演算子からなる演算子エミュレータに重要です。指定されない場合、ボックス内部で改行が可能です。デフォルト: true |
| void [set_OperatorEmulator](./set_operatoremulator/)(**bool**) override | 演算子エミュレータ: true の場合、ボックスとその内容は単一の演算子として振る舞い、演算子のプロパティを継承します。つまり、例えば文字が改行ポイントとして機能し、他の演算子と整列できるということです。'==' のように複数の字形が結合して演算子になる場合に演算子エミュレータが使用されます。デフォルト値: false |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 下限を取得します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | 下限を取得します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 下付き文字を作成します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | 下付き文字を作成します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 左側に下付き文字と上付き文字を作成します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | 左側に下付き文字と上付き文字を作成します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 右側に下付き文字と上付き文字を作成します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | 右側に下付き文字と上付き文字を作成します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 上付き文字を作成します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | 上付き文字を作成します |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | 上限を取得します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | 上限を取得します |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、戻します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | この要素をボーダーボックスに配置します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | この要素をボーダーボックスに配置します |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | この要素を非表示のボックス（論理的なグルーピング）に配置します。これは、式や他の数式テキストの構成要素をグループ化するために使用されます。ボックス化されたオブジェクトは、例えば整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして機能したり、内部で改行が許可されないようにグループ化されたりします。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | 縦配列に配置します |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換することを可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | この要素の下部にバーを設定します |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考

例: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## 参照

* クラス [MathElementBase](../mathelementbase/)
* クラス [IMathBox](../imathbox/)
* クラス [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* 名前空間 [Aspose::Slides::MathText](../)
* ライブラリ [Aspose.Slides](../../)