---
title: MathElementBase
second_title: Aspose.Sildes for .NET API リファレンス
description: IMathElement のベースクラスで、すべての派生クラスで共通するいくつかのメソッドの実装を提供します。内部使用のみです。派生クラスは IMathElement でなければなりません。
type: docs
weight: 8680
url: /ja/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase クラス

Base class for IMathElement with the implementation of some methods that are common to all inherited classes For internal use only. Inherited class must be IMathElement.

```csharp
public abstract class MathElementBase : IMathElement
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | この要素の上に文字（アクセントマーク）を設定します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | このインスタンスを引数として、指定された関数を適用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | このインスタンスを引数として、指定された関数を適用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | このインスタンスを引数として、指定された関数を適用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを引数として、指定された関数と追加の引数を取ります。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | このインスタンスを引数として、指定された関数と追加の引数を取ります。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | この分子と指定された分母で分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | この分子と指定された分母で分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | この分子と指定された分母で、指定されたタイプの分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | この分子と指定された分母で、指定されたタイプの分数を作成します。 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | 数学要素を丸括弧で囲みます。 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | 指定された文字（例：丸括弧や他の文字）で数学要素を囲みます。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | このインスタンスを関数名として、引数の関数を取得します。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | このインスタンスを関数名として、引数の関数を取得します。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | 下部の波括弧でこの要素をグループ化します。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | 下部の波括弧などのグルーピング文字を使用して、この要素をグループ化します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | 上下限なしの積分を取得します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | 積分を取得します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | 積分を取得します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 積分を取得します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | 積分を取得します。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | 数学要素を結合して、数式ブロックを形成します。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | 数学要素を結合して、数式ブロックを形成します。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N項演算子を作成します。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | N項演算子を作成します。 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | この要素の上部にバーを設定します。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | 指定された引数から、与えられた次数の数学的根号を指定します。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | 指定された引数から、与えられた次数の数学的根号を指定します。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | 下限を取得します。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | 下限を取得します。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | 下付き文字を作成します。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | 下付き文字を作成します。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | 左側に下付き文字と上付き文字を作成します。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | 左側に下付き文字と上付き文字を作成します。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | 右側に下付き文字と上付き文字を作成します。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | 右側に下付き文字と上付き文字を作成します。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | 上付き文字を作成します。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | 上付き文字を作成します。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | 上限を取得します。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | 上限を取得します。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | この要素を枠ボックスに配置します。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素を枠ボックスに配置します。 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | この要素を非表示のボックス（論理的グルーピング）に配置します。このボックスは、方程式やその他の数式テキストの構成要素をグループ化するために使用されます。たとえば、演算子エミュレータとして、整列ポイントの有無にかかわらず使用したり、改行ポイントとして使用したり、内部で改行を許可しないようにグループ化したりできます。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 縦方向の配列に配置します。 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | この要素の下部にバーを設定します。 |

### 参照

* インターフェイス [IMathElement](../imathelement)
* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->