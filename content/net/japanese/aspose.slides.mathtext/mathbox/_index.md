---
title: MathBox
second_title: Aspose.Sildes for .NET API リファレンス
description: 数学要素の論理的なボックス化（パッケージ化）を指定します。たとえば、ボックス化されたオブジェクトは、整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして使用したり、内部で改行が許可されないようにグループ化したりできます。例として、演算子は改行を防ぐためにボックス化すべきです。
type: docs
weight: 8610
url: /ja/aspose.slides.mathtext/mathbox/
---
## MathBox クラス

数学要素の論理的なボックス化（パッケージ化）を指定します。たとえば、ボックス化されたオブジェクトは、整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして使用したり、内部で改行が許可されないようにグループ化したりできます。例として、"==" 演算子は改行を防ぐためにボックス化すべきです。

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | 指定された要素を引数として MathBox を初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | true の場合、この演算子エミュレータは整列ポイントとして機能します。つまり、他の式で指定された整列ポイントとそれを揃えることができます。既定値: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | 基本引数 |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | true の場合、ボックスは微分記号として機能します（例: 積分項の 𝑑𝑥）。数学的微分に適した水平間隔が適用されます。既定値: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicit break は、Box オブジェクトの開始位置に改行があるかどうかを指定します。すなわち、行はボックスオブジェクトの開始位置で折り返されます。また、現在の行の整列ポイントとして使用する、前の行の演算子の番号を指定します。可能な値: 1..255 既定値: 0（明示的な改行なし） |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break は、このオブジェクトボックスの「改行不可」属性を指定します。true の場合、ボックス内部で改行は発生しません。これは、複数の二項演算子で構成される演算子エミュレータに重要です。指定しない場合、ボックス内部で改行が可能です。既定値: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator。true の場合、ボックスとその内容は単一の演算子として振る舞い、演算子のプロパティを継承します。たとえば、この文字は改行ポイントとして機能し、他の演算子と整列できます。'==' のように複数の字形が結合して演算子になる場合に、Operator Emulator がよく使用されます。既定値: false |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | アクセント記号（この要素の上部に付く文字）を設定します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | このインスタンスを引数として指定された関数を呼び出します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | このインスタンスを引数として指定された関数を呼び出します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | このインスタンスを引数として指定された関数を呼び出します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを第1引数、指定された追加引数を第2引数として、指定された関数を呼び出します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | このインスタンスを第1引数、指定された文字列を第2引数として、指定された関数を呼び出します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | この要素を分子、指定された要素を分母として分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | この要素を分子、指定された文字列を分母として分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | この要素を分子、指定された要素を分母とし、指定された型の分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | この要素を分子、指定された文字列を分母とし、指定された型の分数を作成します。 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 数式要素を丸括弧で囲みます。 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 指定された文字（例えば丸括弧など）で数式要素を囲みます。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | このインスタンスを関数名として、引数の関数を呼び出します。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | このインスタンスを関数名として、引数の関数を呼び出します。 |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | 子要素を取得します。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 下部波かっこを使用してこの要素をグループ化します。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 下部波かっこなどのグループ文字を使用してこの要素をグループ化します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 上限下限なしで積分を取ります。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 指定された上限と下限を持つ積分を取ります。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 指定された上限と下限（文字列）を持つ積分を取ります。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 指定された上限、下限、および限界位置で積分を取ります。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 指定された上限、下限（文字列）および限界位置で積分を取ります。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 数式要素を結合し、数式ブロックを形成します。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 数式テキストを結合し、数式ブロックを形成します。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N 変数演算子を作成します。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N 変数演算子を作成します。 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | この要素の上部にバーを設定します。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定された引数から与えられた次数の数学的ルートを指定します。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定された引数から与えられた次数の数学的ルートを指定します。 |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | この要素をボーダーボックスに配置します。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素をボーダーボックスに配置します。 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | この要素を非表示のボックス（論理的なグループ化）に配置します。このボックスは、方程式やその他の数式テキストの構成要素をグループ化するために使用されます。たとえば、ボックス化されたオブジェクトは、整列ポイントの有無にかかわらず演算子エミュレータとして、改行ポイントとして、または内部で改行を許可しないようにグループ化するために使用できます。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 縦方向の配列に配置します。 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | この要素の下部にバーを設定します。 |

### 例

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### 参照

* クラス [MathElementBase](../mathelementbase)
* インターフェイス [IMathBox](../imathbox)
* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->