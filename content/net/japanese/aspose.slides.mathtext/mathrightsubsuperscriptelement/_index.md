---
title: MathRightSubSuperscriptElement
second_title: Aspose.Sildes for .NET API リファレンス
description: ベースと、ベースの右側に配置される下付文字および上付文字からなるサブスクリプトオブジェクトを指定します。
type: docs
weight: 8940
url: /ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement クラス

ベースの右側に配置される下付文字と上付文字からなるサブスクリプトオブジェクトを指定します。

```csharp
public sealed class MathRightSubSuperscriptElement : BaseScript, IMathRightSubSuperscriptElement
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MathRightSubSuperscriptElement](mathrightsubsuperscriptelement)(IMathElement, IMathElement, IMathElement) | MathRightSubSuperscriptElement クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlignScripts](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/alignscripts) { get; set; } | 下付文字/上付文字の配置を指定します。true の場合、下付文字と上付文字は水平方向に揃えられます。false の場合、ベースの形状に合わせてカーニングされます。既定値は false です。 |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | ベース引数 |
| [Subscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript) { get; } | 下付文字引数 |
| [Superscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript) { get; } | 上付文字引数 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | アクセント記号（この要素の上にある文字）を設定します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | このインスタンスを引数として指定された関数を実行します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | このインスタンスを引数として、指定された MathFunctionsOfOneArgument 関数を実行します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | このインスタンスを引数として、指定された関数を実行します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを引数として、指定された関数と追加の IMathElement 引数を使用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | このインスタンスを引数として、指定された関数と追加の文字列引数を使用します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | この分子と指定された分母を使用して分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | この分子と指定された分母（文字列）を使用して分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | この分子と指定された分母を使用し、指定された MathFractionTypes のタイプの分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | この分子と指定された分母（文字列）を使用し、指定された MathFractionTypes のタイプの分数を作成します。 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 数学要素を括弧で囲みます。 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 括弧などの指定された文字や他の文字で数学要素を囲みます。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | このインスタンスを関数名として、引数の関数を適用します。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | このインスタンスを関数名として、文字列引数の関数を適用します。 |
| [GetChildren](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/getchildren)() | 子要素を取得します。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 下部の波括弧を使用してこの要素をグループ化します。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 下部波括弧などのグループ化文字を使用してこの要素をグループ化します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 限界なしの積分を取得します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 積分を取得します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 積分を取得します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 積分を取得します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 積分を取得します。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 数学要素を結合して数式ブロックを形成します。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 数式テキストを結合して数式ブロックを形成します。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N 変数演算子を作成します。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N 変数演算子を作成します。 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | この要素の上部にバーを設定します。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定された引数から指定された次数の数学的ルートを設定します。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定された引数から指定された次数の数学的ルートを設定します。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 下限を取得します。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 下限を取得します。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 下付文字を作成します。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 下付文字を作成します。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 左側に下付文字と上付文字を作成します。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 左側に下付文字と上付文字を作成します。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 右側に下付文字と上付文字を作成します。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 右側に下付文字と上付文字を作成します。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 上付文字を作成します。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 上付文字を作成します。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 上限を取得します。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 上限を取得します。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | この要素をボーダーボックスに配置します。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素をボーダーボックスに配置します。 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | この要素を非表示ボックス（論理的グルーピング）に配置します。これは方程式や他の数式テキストの構成要素をグループ化するために使用されます。ボックス化されたオブジェクトは、例えば整列ポイントの有無にかかわらず演算子エミュレータとして、改行ポイントとして、または改行を許可しないようにグループ化することができます。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 縦方向の配列に配置します。 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | この要素の下部にバーを設定します。 |

### 例

例:

```csharp
[C#]
MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```

### 参照

* クラス [BaseScript](../basescript)
* インターフェイス [IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement)
* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->