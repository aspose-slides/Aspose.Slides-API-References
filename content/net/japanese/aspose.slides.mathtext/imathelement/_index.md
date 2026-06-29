---
title: IMathElement
second_title: Aspose.Sildes for .NET API リファレンス
description: 任意の数学要素（分数、数学テキスト、関数、複数要素の式など）の基本インターフェイス
type: docs
weight: 8210
url: /ja/aspose.slides.mathtext/imathelement/
---
## IMathElement インターフェイス

任意の数学要素（分数、数学テキスト、関数、複数要素の式など）の基本インターフェイスです

```csharp
public interface IMathElement
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | この要素の上にアクセント記号（文字）を設定します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | このインスタンスを引数として指定された関数を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | このインスタンスを引数として指定された関数を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | このインスタンスを引数として指定された関数を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを第一引数、指定された追加引数を第二引数として、指定された関数を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | このインスタンスを第一引数、指定された文字列を第二引数として、指定された関数を呼び出します |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | この分子と指定された分母で、指定された種類の分数を作成します |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | この分子と指定された分母で、指定された種類の分数を作成します |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | 数学要素を括弧で囲みます |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | この要素を指定された文字（括弧など）で囲みます |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | このインスタンスを関数名として、引数の関数を呼び出します |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | このインスタンスを関数名として、引数の関数を呼び出します |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | 子要素を取得します |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | この要素を下部の波括弧でグループに配置します |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | この要素を下部の波括弧などのグルーピング文字でグループに配置します |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | 上限と下限のない積分を取得します |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | 積分を取得します |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | 数学要素を結合し、数学ブロックを形成します |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | 数学テキストを結合し、数学ブロックを形成します |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N元演算子を作成します |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | N元演算子を作成します |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | この要素の上にバーを設定します |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | 指定された引数に対して、指定された次数のルートを設定します |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | 指定された引数に対して、指定された次数のルートを設定します |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | 下限を取得します |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | 下限を取得します |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | 下付き文字を作成します |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | 下付き文字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | 左側に下付き文字と上付き文字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | 左側に下付き文字と上付き文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | 右側に下付き文字と上付き文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | 右側に下付き文字と上付き文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | 上付き文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | 上付き文字を作成します |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | 上限を取得します |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | 上限を取得します |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | この要素を枠ボックスに配置します |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素を枠ボックスに配置します |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | この要素を非表示のボックス（論理的なグループ）に配置します。このボックスは方程式やその他の数式テキストの構成要素をグループ化するために使用されます。例えば、ボックス化されたオブジェクトは配置点の有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして使用したり、内部で改行が許可されないようにグループ化したりできます。 |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | 縦方向の配列に配置します |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | この要素の下にバーを設定します |

### 例

例:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### 関連項目

* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->