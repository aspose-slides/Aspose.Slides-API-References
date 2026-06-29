---
title: MathBorderBox
second_title: Aspose.Sildes for .NET APIリファレンス
description: IMathElement の周囲に長方形またはその他の枠線を描画します。
type: docs
weight: 8590
url: /ja/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox クラス

IMathElement の周囲に長方形またはその他の枠線を描画します。

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## コンストラクター

| Name | Description |
| --- | --- |
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | 長方形の枠線を持つ MathBorderBox 要素を作成します |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | MathBorderBox 要素を作成します |

## プロパティ

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | 基本引数 |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | 下端を非表示にする (デフォルトは false) - ボーダーボックスの下端の非表示または表示状態を指定します |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | 左端を非表示にする (デフォルトは false) - ボーダーボックスの左端の非表示または表示状態を指定します |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | 右端を非表示にする (デフォルトは false) - ボーダーボックスの右端の非表示または表示状態を指定します |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | 上端を非表示にする (デフォルトは false) - ボーダーボックスの上端の非表示または表示状態を指定します |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | 左下から右上への取り消し線 (デフォルトは false) - ボーダーボックスの左下隅から右上隅への斜め取り消し線の非表示または表示状態を指定します |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | 水平取り消し線 (デフォルトは false) - 水平取り消し線の非表示または表示状態を指定します |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | 左上から右下への取り消し線 (デフォルトは false) - ボーダーボックスの左上隅から右下隅への斜め取り消し線の非表示または表示状態を指定します |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | 垂直取り消し線 (デフォルトは false) - 垂直取り消し線の非表示または表示状態を指定します |

## メソッド

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | アクセント記号を設定します (この要素の上部に表示される文字) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | このインスタンスを引数として指定された関数を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | このインスタンスを引数として指定された関数を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | このインスタンスを引数として指定された関数を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを引数として指定された関数を呼び出し、追加の引数も指定します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | このインスタンスを引数として指定された関数を呼び出し、追加の引数も指定します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 数式要素を丸括弧で囲みます |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 丸括弧など、指定された文字で数式要素を枠取ります |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | このインスタンスを関数名として、引数の関数を呼び出します |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | このインスタンスを関数名として、引数の関数を呼び出します |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | 子要素を取得します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 下部の波かっこを使用してこの要素をグループ化します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 下部の波かっこなどのグループ文字を使用してこの要素をグループ化します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 上下限なしで積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 積分を取得します |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 数式要素を結合し、数式ブロックを構成します |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 数式テキストを結合し、数式ブロックを構成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N 項演算子を作成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N 項演算子を作成します |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | この要素の上にバーを設定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定された引数から指定された次数の数学的根を指定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定された引数から指定された次数の数学的根を指定します |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 下限を取得します |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 下限を取得します |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 下付き文字を作成します |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 下付き文字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 左側に下付きと上付き文字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 左側に下付きと上付き文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 右側に下付きと上付き文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 右側に下付きと上付き文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 上付き文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 上付き文字を作成します |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 上限を取得します |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 上限を取得します |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | この要素をボーダーボックスに配置します |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素をボーダーボックスに配置します |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | この要素を非表示ボックス (論理的なグルーピング) に配置します。これは数式やその他のテキストの構成要素をグループ化するために使用されます。ボックス化されたオブジェクトは、例えば整列ポイントの有無にかかわらず演算子エミュレータとして、改行ポイントとして、または改行を許可しないようにグループ化することができます |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 垂直配列に配置します |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | この要素の下にバーを設定します |

### 例

例:

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### 参照

* クラス [MathElementBase](../mathelementbase)
* インターフェイス [IMathBorderBox](../imathborderbox)
* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->