---
title: MathArray
second_title: Aspose.Sildes の .NET API リファレンス
description: 方程式または任意の数式オブジェクトの垂直配列を指定します
type: docs
weight: 8530
url: /ja/aspose.slides.mathtext/matharray/
---
## MathArray クラス

方程式または任意の数式オブジェクトの垂直配列を指定します

```csharp
public sealed class MathArray : MathElementBase, IMathArray
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MathArray](matharray#constructor_1)(IEnumerable&lt;IMathElement&gt;) | 数学配列を作成し、指定された要素をその中に配置します |
| [MathArray](matharray#constructor)(IMathElement) | 数学配列を作成し、指定された要素をその中に配置します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/matharray/arguments) { get; } | 配列の項目の集合 |
| [BaseJustification](../../aspose.slides.mathtext/matharray/basejustification) { get; set; } | 配列の周囲のテキストに対する配置を指定します。配列外のテキストは、配列オブジェクトの底部、上部、または中央に揃えることができます。デフォルト値: Center |
| [MaximumDistribution](../../aspose.slides.mathtext/matharray/maximumdistribution) { get; set; } | Maximum Distribution が true の場合、配列は包含要素（ページ、列、セルなど）の最大幅に合わせて配置されます |
| [ObjectDistribution](../../aspose.slides.mathtext/matharray/objectdistribution) { get; set; } | Object Distribution が true の場合、配列の内容は配列オブジェクトの最大幅に合わせて配置されます |
| [RowSpacing](../../aspose.slides.mathtext/matharray/rowspacing) { get; set; } | 配列の行間の間隔です。RowSpacingRule が 3 の Exactly に設定されている場合にのみ使用され、単位はポイントになります。Multiple に設定されている場合は単位が半行になります。デフォルト: 0 |
| [RowSpacingRule](../../aspose.slides.mathtext/matharray/rowspacingrule) { get; set; } | 配列要素間の垂直間隔のタイプです。デフォルト: SingleLineGap |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | アクセントマークを設定します（この要素の上部に表示される文字） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | このインスタンスを引数として指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | このインスタンスを引数として指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | このインスタンスを引数として指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを引数として指定された関数を取得し、指定された追加引数を使用します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | このインスタンスを引数として指定された関数を取得し、指定された追加引数を使用します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | この分子と指定された分母を使用して分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | この分子と指定された分母を使用して分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | この分子と指定された分母を使用して、指定されたタイプの分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | この分子と指定された分母を使用して、指定されたタイプの分数を作成します |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 数式要素を括弧で囲みます |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 括弧やその他の文字など、指定された文字で数式要素を囲みます |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | このインスタンスを関数名として、引数の関数を取得します |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | このインスタンスを関数名として、引数の関数を取得します |
| [GetChildren](../../aspose.slides.mathtext/matharray/getchildren)() | 子要素を取得します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 下部の波かっこを使用して、この要素をグループに配置します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 下部の波かっこやその他の文字など、グループ化文字を使用してこの要素をグループに配置します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 制限なしで積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 積分を取得します |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 数式要素を結合して数式ブロックを形成します |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 数式テキストを結合して数式ブロックを形成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N元演算子を作成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N元演算子を作成します |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | この要素の上部にバーを設定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定された引数から指定された次数の数学的ルートを指定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定された引数から指定された次数の数学的ルートを指定します |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 下限を取得します |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 下限を取得します |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 下標を作成します |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 下標を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 左側に下標と上標を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 左側に下標と上標を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 右側に下標と上標を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 右側に下標と上標を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 上標を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 上標を作成します |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 上限を取得します |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 上限を取得します |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | この要素を枠箱に配置します |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素を枠箱に配置します |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | この要素を非表示のボックス（論理的なグループ）に配置します。このボックスは、方程式やその他の数式テキストの構成要素をグループ化するために使用されます。ボックス化されたオブジェクトは、たとえば配置ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして使用されたり、内部で改行を許可しないようにグループ化されたりします。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 垂直配列に配置します |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | この要素の下部にバーを設定します |

### 例

例:

```csharp
[C#]
MathArray mathArray = new MathArray(new MathematicalText("item1"));
```

### 参照

* クラス [MathElementBase](../mathelementbase)
* インターフェース [IMathArray](../imatharray)
* ネームスペース [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->