---
title: MathLeftSubSuperscriptElement
second_title: Aspose.Sildes の .NET API リファレンス
description: ベースの左側に配置される、基底と下付きおよび上付きからなるサブ・スーパースクリプト オブジェクトを指定します。
type: docs
weight: 8790
url: /ja/aspose.slides.mathtext/mathleftsubsuperscriptelement/
---
## MathLeftSubSuperscriptElement クラス

ベースの左側に配置される、基底と下付き・上付きから構成されるサブ・スーパースクリプト オブジェクトを指定します。

```csharp
public sealed class MathLeftSubSuperscriptElement : BaseScript, IMathLeftSubSuperscriptElement
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MathLeftSubSuperscriptElement](mathleftsubsuperscriptelement)(IMathElement, IMathElement, IMathElement) | MathLeftSubSuperscriptElement クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | 基底引数 |
| [Subscript](../../aspose.slides.mathtext/mathleftsubsuperscriptelement/subscript) { get; } | 下付き |
| [Superscript](../../aspose.slides.mathtext/mathleftsubsuperscriptelement/superscript) { get; } | 上付き |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | アクセント記号（この要素の上部に表示される文字）を設定します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | このインスタンスを引数として指定された関数を使用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | このインスタンスを引数として指定された関数を使用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | このインスタンスを引数として指定された関数を使用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを第一引数として、指定された追加引数とともに指定された関数を使用します。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | このインスタンスを第一引数として、指定された追加引数とともに指定された関数を使用します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | この分子と指定された分母で分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | この分子と指定された分母（文字列）で分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | この分子と指定された分母で、指定されたタイプの分数を作成します。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | この分子と指定された分母（文字列）で、指定されたタイプの分数を作成します。 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 数式要素を丸括弧で囲みます。 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 指定された文字（例：丸括弧など）で数式要素を囲みます。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | このインスタンスを関数名として、引数の関数を使用します。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | このインスタンスを関数名として、文字列引数の関数を使用します。 |
| [GetChildren](../../aspose.slides.mathtext/mathleftsubsuperscriptelement/getchildren)() | 子要素を取得します。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 下側の波かっこを使用して、この要素をグループに配置します。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 下側の波かっこなどのグループ化文字を使用して、この要素をグループに配置します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 上限・下限なしで積分を取得します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 指定された上限と下限で積分を取得します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 指定された文字列による上限・下限で積分を取得します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 指定された上限・下限と位置情報で積分を取得します。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 指定された文字列による上限・下限と位置情報で積分を取得します。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 数式要素を結合して、数式ブロックを形成します。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 数式テキストを結合して、数式ブロックを形成します。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N元演算子を作成します。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N元演算子を作成します。 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | この要素の上部にバーを設定します。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定された引数から、指定された次数の数学的根を指定します。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定された引数から、指定された次数の数学的根を指定します。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 下限を取得します。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 下限を取得します。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 下付き文字を作成します。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 下付き文字を作成します。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 左側に下付きと上付きを作成します。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 左側に下付きと上付きを作成します。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 右側に下付きと上付きを作成します。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 右側に下付きと上付きを作成します。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 上付き文字を作成します。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 上付き文字を作成します。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 上限を取得します。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 上限を取得します。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | この要素をボーダーボックスに配置します。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素をボーダーボックスに配置します。 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | この要素を非表示ボックス（論理的グループ化）に配置します。このボックスは、数式の部品やその他のテキスト要素をグループ化するために使用されます。たとえば、演算子エミュレータとして、配置点の有無にかかわらず、改行点として、または行内改行を許可しないようにグループ化できます。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 縦配列に配置します。 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | この要素の下部にバーを設定します。 |

### 例

例：

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
```

### 参照

* クラス [BaseScript](../basescript)
* インターフェイス [IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement)
* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->