---
title: MathGroupingCharacter
second_title: Aspose.Sildes for .NET API リファレンス
description: 式の上または下に配置されるグループ化記号を指定し、通常は要素間の関係を強調します
type: docs
weight: 8740
url: /ja/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter クラス

式の上または下に配置されるグループ化記号を指定し、通常は要素間の関係を強調します

```csharp
public sealed class MathGroupingCharacter : MathElementBase, IMathGroupingCharacter
```

## コンストラクタ

| Name | Description |
| --- | --- |
| [MathGroupingCharacter](mathgroupingcharacter#constructor)(IMathElement) | MathGroupingCharacter クラスの新しいインスタンスを、デフォルトのグループ化文字 U+23DF (BOTTOM CURLY BRACKET) で初期化します |
| [MathGroupingCharacter](mathgroupingcharacter#constructor_1)(IMathElement, char, MathTopBotPositions, MathTopBotPositions) | MathGroupingCharacter クラスの新しいインスタンスを初期化します |

## プロパティ

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathgroupingcharacter/base) { get; } | 基本引数 |
| [Character](../../aspose.slides.mathtext/mathgroupingcharacter/character) { get; set; } | グループ化文字 デフォルト値: U+23DF (BOTTOM CURLY BRACKET) |
| [Position](../../aspose.slides.mathtext/mathgroupingcharacter/position) { get; set; } | グループ化文字の位置。デフォルト: Bottom |
| [VerticalJustification](../../aspose.slides.mathtext/mathgroupingcharacter/verticaljustification) { get; set; } | グループ文字の垂直位置揃え。オブジェクトのベースラインに対する配置を指定します。たとえば、グループ文字がオブジェクトの上にある場合、VerticalJustification が Top のときはオブジェクトの上部がベースラインに合わせられます。VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースラインに合わせられます。デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top |

## メソッド

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | アクセント記号を設定します（この要素の上に表示される文字） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | このインスタンスを引数として指定された関数を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | このインスタンスを引数として指定された関数を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | このインスタンスを引数として指定された関数を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを引数として、追加の引数とともに指定された関数を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | このインスタンスを引数として、追加の引数とともに指定された関数を呼び出します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 数式要素を丸括弧で囲みます |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 数式要素を指定された文字（丸括弧や他の文字）で囲みます |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | このインスタンスを関数名として、引数の関数を呼び出します |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | このインスタンスを関数名として、引数の関数を呼び出します |
| [GetChildren](../../aspose.slides.mathtext/mathgroupingcharacter/getchildren)() | 子要素を取得します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | この要素を下側の波括弧でグループ化します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | この要素を下側の波括弧やその他のグループ化文字でグループ化します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 範囲なしで積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 積分を取得します |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 数学要素を結合し、数学ブロックを形成します |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 数学テキストを結合し、数学ブロックを形成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N項演算子を作成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N項演算子を作成します |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | この要素の上にバーを設定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定された引数から、指定された次数の数学的根を指定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定された引数から、指定された次数の数学的根を指定します |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 下限を取得します |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 下限を取得します |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 下付文字を作成します |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 下付文字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 左側に下付文字と上付文字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 左側に下付文字と上付文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 右側に下付文字と上付文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 右側に下付文字と上付文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 上付文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 上付文字を作成します |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 上限を取得します |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 上限を取得します |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | この要素をボーダーボックスに配置します |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素をボーダーボックスに配置します |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | この要素を非可視ボックス（論理グループ）に配置します。これは、数式の構成要素やテキストの他のインスタンスをグループ化するために使用されます。ボックス化されたオブジェクトは、例えば、配置点の有無にかかわらず演算子エミュレータとして機能したり、改行点として機能したり、改行を許可しないようにグループ化したりできます。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 縦方向の配列に配置します |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | この要素の下にバーを設定します |

### 例

例:

```csharp
[C#]
MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

### 参照

* クラス [MathElementBase](../mathelementbase)
* インターフェイス [IMathGroupingCharacter](../imathgroupingcharacter)
* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->