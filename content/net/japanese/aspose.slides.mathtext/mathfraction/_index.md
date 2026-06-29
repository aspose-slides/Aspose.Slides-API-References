---
title: MathFraction
second_title: Aspose.Sildes for .NET API リファレンス
description: 分子と分母が分数線で区切られた分数オブジェクトを指定します。分数線は、分数プロパティに応じて水平または斜めにすることができます。分数オブジェクトは、分数線なしで 1 つの要素を別の要素の上に配置するスタック関数を表すためにも使用されます。
type: docs
weight: 8670
url: /ja/aspose.slides.mathtext/mathfraction/
---
## MathFraction クラス

分子と分母が分数線で区切られた分数オブジェクトを指定します。分数線は、分数プロパティに応じて水平または斜めにすることができます。分数オブジェクトは、分数線なしで 1 つの要素を別の要素の上に配置するスタック関数を表すためにも使用されます。

```csharp
public sealed class MathFraction : MathElementBase, IMathFraction
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MathFraction](mathfraction#constructor)(IMathElement, IMathElement) | 指定された分子と分母を使用して、タイプが 'Bar' の MathFraction を初期化します |
| [MathFraction](mathfraction#constructor_1)(IMathElement, IMathElement, MathFractionTypes) | 指定された分子、分母、およびタイプで MathFraction を初期化します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Denominator](../../aspose.slides.mathtext/mathfraction/denominator) { get; } | 分母 |
| [FractionType](../../aspose.slides.mathtext/mathfraction/fractiontype) { get; set; } | 分数タイプ デフォルト: Bar |
| [Numerator](../../aspose.slides.mathtext/mathfraction/numerator) { get; } | 分子 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | この要素の上にアクセント記号 (char) を設定します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | このインスタンスを引数として使用し、指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | このインスタンスを引数として使用し、指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | このインスタンスを引数として使用し、指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを引数として、指定された追加引数と共に、指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | このインスタンスを引数として、指定された追加引数と共に、指定された関数を取得します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 数式要素を丸括弧で囲みます |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 数式要素を指定された文字（例: 丸括弧やその他の文字）で囲みます |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | このインスタンスを関数名として使用し、引数の関数を取得します |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | このインスタンスを関数名として使用し、引数の関数を取得します |
| [GetChildren](../../aspose.slides.mathtext/mathfraction/getchildren)() | 子要素を取得します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | この要素を下部の波かっこでグループ化します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | この要素を下部の波かっこなどのグループ文字でグループ化します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 上限・下限なしで積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 積分を取得します |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 数式要素を結合し、数式ブロックを形成します |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 数式テキストを結合し、数式ブロックを形成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N 変数演算子を作成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N 変数演算子を作成します |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | この要素の上部にバーを設定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定された引数から、指定された次数の数学的ルートを設定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定された引数から、指定された次数の数学的ルートを設定します |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 下限を取得します |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 下限を取得します |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 下付き文字を作成します |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 下付き文字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 左側に下付き文字と上付き文字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 左側に下付き文字と上付き文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 右側に下付き文字と上付き文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 右側に下付き文字と上付き文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 上付き文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 上付き文字を作成します |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 上限を取得します |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 上限を取得します |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | この要素をボーダーボックスに配置します |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素をボーダーボックスに配置します |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | この要素を非表示ボックス（論理的グループ）に配置します。このボックスは、数式やその他の数式テキストの構成要素をグループ化するために使用されます。ボックス化されたオブジェクトは、例えば、配置点の有無にかかわらず演算子エミュレータとして、改行点として、または改行を許可しないようにグループ化することができます |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 縦配列に配置します |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | この要素の下部にバーを設定します |

### 例

例:

```csharp
[C#]
MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```

### 参照

* クラス [MathElementBase](../mathelementbase)
* インターフェース [IMathFraction](../imathfraction)
* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->