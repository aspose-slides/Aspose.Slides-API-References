---
title: MathBlock
second_title: Aspose.Sildes for .NET API リファレンス
description: MathParagraph に含まれ、独自の行から開始する数式テキストのインスタンスを指定します。すべての数式領域（方程式、式、方程式や式の配列、数式）は MathBlock で表されます。
type: docs
weight: 8590
url: /ja/aspose.slides.mathtext/mathblock/
---
## MathBlock クラス

MathParagraph に含まれ、独自の行から開始する数式テキストのインスタンスを指定します。数式ゾーン全体（方程式、式、方程式や式の配列、数式）はすべて MathBlock で表されます。

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MathBlock](mathblock#constructor)() | MathBlock クラスの新しいインスタンスを初期化します。 |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | 新しい数式ブロックを作成し、指定した要素をその中に配置します |
| [MathBlock](mathblock#constructor_1)(IMathElement) | 新しい数式ブロックを作成し、指定した要素をその中に配置します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | コレクションに実際に含まれる子 math 要素の数を取得します。読み取り専用 Int32。 |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | 子要素コレクションは変更可能なため、false を返します。 |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | 指定されたインデックスの IMathElement を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | アクセント記号（この要素の上に置かれる文字）を設定します。 |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | コレクションの末尾に math 要素を追加します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | このインスタンスを引数として、指定された関数を使用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | このインスタンスを引数として、指定された関数を使用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | このインスタンスを引数として、指定された関数を使用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを第1引数、指定された追加引数を第2引数として、指定された関数を使用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | このインスタンスを第1引数、指定された追加引数を第2引数として、指定された関数を使用します。 |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | コレクションからすべての要素を削除します。 |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | コレクションが特定の値を含むかどうかを判定します。 |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | 指定された配列にコピーします。 |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | 子要素を区切り文字で区切ります（角括弧は使用しません）。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | この分子と指定された分母を用いて分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | この分子と指定された分母を用いて分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | この分子と指定された分母を用いて、指定されたタイプの分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | この分子と指定された分母を用いて、指定されたタイプの分数を作成します。 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 数式要素を丸括弧で囲みます。 |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | このブロックの子要素を、丸括弧など指定された文字で枠付けして囲みます。 |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | このブロックの子要素を、指定された文字で枠付けし、区切り文字で区切ります。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | このインスタンスを関数名として、引数の関数を使用します。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | このインスタンスを関数名として、引数の関数を使用します。 |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | 子要素を取得します。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 下側の波括弧を使用してこの要素をグループ化します。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 下側の波括弧などのグルーピング文字を使用してこの要素をグループ化します。 |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | コレクション内の特定の数式要素のインデックスを取得します。 |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | 指定されたインデックスに MathElement を挿入します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 上限下限なしで積分を取ります。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 積分を取ります。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 積分を取ります。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 積分を取ります。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 積分を取ります。 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | この数式ブロックに数式要素を結合します。 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | この数式ブロックに数式テキストを結合します。 |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | 別の数式ブロックをこのブロックに結合します。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N元演算子を作成します。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N元演算子を作成します。 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | この要素の上にバーを設定します。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定された引数から、指定された次数の数学的ルートを指定します。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定された引数から、指定された次数の数学的ルートを指定します。 |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | コレクションの指定インデックスの要素を削除します。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 下限を取ります。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 下限を取ります。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 下付き文字を作成します。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 下付き文字を作成します。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 左側に下付き文字と上付き文字を作成します。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 左側に下付き文字と上付き文字を作成します。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 右側に下付き文字と上付き文字を作成します。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 右側に下付き文字と上付き文字を作成します。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 上付き文字を作成します。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 上付き文字を作成します。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 上限を取ります。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 上限を取ります。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | この要素を枠ボックスに配置します。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素を枠ボックスに配置します。 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | この要素を非表示ボックス（論理的グループ）に配置します。これは、方程式や他の数式テキストの構成要素をグループ化するために使用されます。ボックス化されたオブジェクトは、例えば、整列点の有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして使用したり、内部で改行を許可しないようにグループ化したりできます。 |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | 子要素を縦方向の配列に配置します。 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | この要素の下にバーを設定します。 |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | この [`MathBlock`](../mathblock) の内容を MathML として保存します。 |

### 例

Example:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### 参照

* クラス [MathElementBase](../mathelementbase)
* インターフェイス [IMathBlock](../imathblock)
* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->