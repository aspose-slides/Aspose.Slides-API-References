---
title: IMathElement
second_title: Aspose.Sildes for .NET APIリファレンス
description: 任意の数学要素（分数、数式テキスト、関数、複数要素を含む式など）の基本インターフェイス
type: docs
weight: 8230
url: /ja/aspose.slides.mathtext/imathelement/
---
## IMathElement インターフェイス

任意の数学要素（分数、数式テキスト、関数、複数要素を含む式など）の基本インターフェイス

```csharp
public interface IMathElement
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | この要素の上に付くアクセント記号（文字）を設定します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | このインスタンスを引数として、指定された関数を取ります |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | このインスタンスを引数として、指定された関数を取ります |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | このインスタンスを引数として、指定された関数を取ります |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを引数として、指定された関数と追加の引数を取ります |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | このインスタンスを引数として、指定された関数と追加の引数を取ります |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | この数学要素を丸括弧で囲みます |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | 指定された文字（例えば括弧など）でこの要素を囲みます |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | このインスタンスを関数名として、引数の関数を取ります |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | このインスタンスを関数名として、引数の関数を取ります |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | 子要素を取得します |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | 下部の波括弧を使用してこの要素をグループ化します |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | 下部の波括弧などのグループ文字を使用してこの要素をグループ化します |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | 上下限なしの積分を取ります |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | 積分を取ります |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | 積分を取ります |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 積分を取ります |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | 積分を取ります |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | 数学要素を結合し、数式ブロックを形成します |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | 数学テキストを結合し、数式ブロックを形成します |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N 進演算子を作成します |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | N 進演算子を作成します |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | この要素の上にバーを設定します |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | 指定された引数から指定次数の数学的根を設定します |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | 指定された引数から指定次数の数学的根を設定します |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | 下限を取ります |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | 下限を取ります |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | 下付き文字を作成します |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | 下付き文字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | 左側に下付き文字と上付き文字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | 左側に下付き文字と上付き文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | 右側に下付き文字と上付き文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | 右側に下付き文字と上付き文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | 上付き文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | 上付き文字を作成します |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | 上限を取ります |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | 上限を取ります |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | この要素を枠ボックスに配置します |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素を枠ボックスに配置します |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | 視覚的ではないボックス（論理的グループ）に配置します。このボックスは、数式や他の数学テキストの部品をグループ化するために使用され、演算子エミュレータや改行ポイントとして、または改行を許可しないようにグループ化することができます。 |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | 縦方向配列に配置します |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | この要素の下にバーを設定します |

### 例

例:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### 参照

* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->