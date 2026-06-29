---
title: MathPhantom
second_title: Aspose.Slides for .NET API リファレンス
description: ファントム数学オブジェクト lt mphantgt を表し、子要素のレイアウトに影響を与えますが、必ずしも表示されるわけではありません。ファントムは基本式を非表示にしつつ、幅・高さ・深さを保持して数式を揃えたりスペースを確保したりできます。表示・幾何形状の動作は Show、ZeroWid、ZeroAsc、ZeroDesc、Transp といったプロパティで制御されます。
type: docs
weight: 8900
url: /ja/aspose.slides.mathtext/mathphantom/
---
## MathPhantom クラス

Represents a phantom math object (&lt;m:phant&gt;) that affects the layout of its child element without necessarily displaying it. A phantom can hide its base expression while preserving its width, height, or depth to align formulas or reserve space. Visibility and geometry behavior are controlled by properties such as Show, ZeroWid, ZeroAsc, ZeroDesc, and Transp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | 指定された基本数学要素を使用して、[`MathPhantom`](../mathphantom) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | 基本引数 |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | 基本要素が表示されるかどうかを示す値を取得または設定します。 |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | クラスベースの間隔規則に対して、ファントムが透明であるかどうかを示す値を取得または設定します。 |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | 基本要素の上昇（ベースライン上の高さ）をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | 基本要素の下降（ベースライン下の深さ）をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | 基本要素の幅をゼロとして扱うかどうかを示す値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | この要素の上部にアクセント記号（文字）を設定します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | このインスタンスを引数として、指定された関数を適用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | このインスタンスを引数として、指定された関数を適用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | このインスタンスを引数として、指定された関数を適用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを第一引数、指定された追加引数を第二引数として、指定された関数を適用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | このインスタンスを第一引数、指定された文字列引数を第二引数として、指定された関数を適用します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | この分子と指定された分母で分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | この分子と指定された文字列分母で分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | この分子と指定された分母で、指定された型の分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | この分子と指定された文字列分母で、指定された型の分数を作成します。 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 数学要素を括弧で囲みます。 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 指定された文字（例えば括弧や他の文字）で数学要素をフレームとして囲みます。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | このインスタンスを関数名として、引数の関数を取得します。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | このインスタンスを関数名として、文字列引数の関数を取得します。 |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | 子要素を取得します。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 下側の波括弧を使用して、この要素をグループ化します。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 下側の波括弧やその他のグルーピング文字を使用して、この要素をグループ化します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 制限なしで積分を取ります。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 積分を取ります。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 積分を取ります。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 積分を取ります。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 積分を取ります。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 数学要素を結合し、数学ブロックを形成します。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 数学テキストを結合し、数学ブロックを形成します。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N項演算子を作成します。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N項演算子を作成します。 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | この要素の上部にバーを設定します。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定された引数の、指定された次数の数学的根を指定します。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定された文字列引数の、指定された次数の数学的根を指定します。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 下限を取得します。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 下限を取得します。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 下付き文字を作成します。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 下付き文字を作成します。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 左側に下付き文字と上付き文字を作成します。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 左側に下付き文字と上付き文字を作成します。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 右側に下付き文字と上付き文字を作成します。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 右側に下付き文字と上付き文字を作成します。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 上付き文字を作成します。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 上付き文字を作成します。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 上限を取得します。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 上限を取得します。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | この要素をボーダーボックスに配置します。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素をボーダーボックスに配置します（複数のオプション）。 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | この要素を非表示ボックス（論理的なグルーピング）に配置します。これは、方程式や他の数学テキストのコンポーネントをグループ化するために使用されます。ボックス化されたオブジェクトは、例えば演算子エミュレータとして、配置点の有無にかかわらず、改行点として、または改行を許可しないようにグループ化することができます。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 縦方向の配列に配置します。 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | この要素の下部にバーを設定します。 |

### 例

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // 内容を非表示にする
phantom.ZeroWidth = false;     // 幅を保持する
```

### 参照

* クラス [MathElementBase](../mathelementbase)
* インターフェイス [IMathPhantom](../imathphantom)
* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->