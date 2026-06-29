---
title: MathNaryOperator
second_title: Aspose.Sildes for .NET API リファレンス
description: 総和や積分などの N 変数数学オブジェクトを指定します。演算子、基底（またはオペランド）およびオプションの上限と下限で構成されます。N 変数演算子の例として、総和、和集合、積集合、積分があります。
type: docs
weight: 8850
url: /ja/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator クラス

N 変数の数学オブジェクト（例: 総和や積分）を指定します。演算子、基底（またはオペランド）およびオプションの上限と下限から構成されます。N 変数演算子の例: 総和、和集合、積集合、積分

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | MathNaryOperator クラスの新しいインスタンスを初期化します。 |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | MathNaryOperator クラスの新しいインスタンスを初期化します。 |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | MathNaryOperator クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | 基本引数 |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | 演算子文字はオペランドの高さに合わせて垂直方向に伸びます |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | 下付き文字を非表示にする |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | 上付き文字を非表示にする |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | 下限と上限の位置（下付き文字と上付き文字） |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | Nary 演算子文字 例: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | 下付き文字の引数を指定します。例えば積分の場合、下限を設定します |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | 上付き文字の引数を指定します。例えば積分の場合、上限を設定します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | アクセント記号（この要素の上に表示される文字）を設定します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | このインスタンスを引数として指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | このインスタンスを引数として指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | このインスタンスを引数として指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを引数として指定された関数を取得し、追加の引数を指定します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | このインスタンスを引数として指定された関数を取得し、追加の引数を指定します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 数式要素を括弧で囲みます |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 括弧や他の文字など、指定された文字で数式要素を囲みます |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | このインスタンスを関数名として、引数の関数を取得します |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | このインスタンスを関数名として、引数の関数を取得します |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | 子要素を取得します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 下カーブブレースを使用してこの要素をグループ化します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 下カーブブレースや他の文字など、グルーピング文字を使用してこの要素をグループ化します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 制限なしの積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 積分を取得します |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 数式要素を結合して数式ブロックを形成します |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 数式テキストを結合して数式ブロックを形成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary 演算子を作成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary 演算子を作成します |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | この要素の上にバーを設定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定された引数から、与えられた次数の数学的ルートを指定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定された引数から、与えられた次数の数学的ルートを指定します |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | この要素を枠ボックスに配置します |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素を枠ボックスに配置します |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | この要素を非表示ボックス（論理的なグループ化）に配置します。これは数式や他のテキストのコンポーネントをグループ化するために使用されます。ボックス化されたオブジェクトは、例えば演算子エミュレータとして、整列ポイントの有無にかかわらず、改行ポイントとして、または改行を許可しないようにグループ化することができます。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 縦方向の配列に配置します |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | この要素の下にバーを設定します |

### 例

例:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### 参照

* クラス [MathElementBase](../mathelementbase)
* インターフェイス [IMathNaryOperator](../imathnaryoperator)
* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->