---
title: MathDelimiter
second_title: Aspose.Sildes for .NET API リファレンス
description: 開始括弧や閉じ括弧（丸括弧、波括弧、角括弧、縦棒など）で構成され、指定された文字で区切られた 1 つ以上の数学要素を内部に持つ区切り文字オブジェクトを指定します。例: 2 2x7C2
type: docs
weight: 8630
url: /ja/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter クラス

区切り文字オブジェクトを指定します。開始文字と終了文字（括弧、波括弧、角括弧、縦棒など）で構成され、指定された文字で区切られた 1 つ以上の数学要素を内部に持ちます。例: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | 指定された要素を単一の基本引数として使用して MathDelimiter を初期化します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | 区切り文字で区切られた 1 つ以上の数学要素 |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Delimiter Beginning Character は開始（開く）区切り文字を指定します。数学的区切り文字は括弧、角括弧、波括弧などの囲む文字です。デフォルトは '(' です。 |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | 区切りオブジェクト内の区切り文字の形状を指定します。MathDelimiterShape.Centered の場合、区切り文字は数式テキストの数軸の周りに中央揃えになり、内容全体の高さに合わせて調整されます。MathDelimiterShape.Match の場合、高さと形状が内容に正確に合わせて変更されます。 |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimiter Ending Character は終了（閉じる）区切り文字を指定します。数学的区切り文字は括弧、角括弧、波括弧などの囲む文字です。デフォルトは ')' です。 |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。true の場合、区切り文字はオペランドの高さに合わせて垂直に伸びます。デフォルト値は true です。 |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimiter Separator Character は区切りオブジェクト内で引数を区切る文字を指定します。デフォルトは '&#x7C;' です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | この要素の上部にアクセント記号（文字）を設定します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | このインスタンスを引数として指定された関数を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | このインスタンスを引数として、指定された MathFunctionsOfOneArgument 関数を実行します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | このインスタンスを引数として、指定された関数（文字列）を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを第1引数、指定された追加引数を第2引数として、指定された MathFunctionsOfTwoArguments 関数を呼び出します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | このインスタンスを第1引数、指定された文字列引数を第2引数として、指定された MathFunctionsOfTwoArguments 関数を呼び出します |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | 指定された区切り文字を使用して引数を区切ります |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | この分子と指定された分母を使用して、指定された MathFractionTypes の分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | この分子と指定された分母を使用して、指定された MathFractionTypes の分数を作成します |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 数学要素を丸括弧で囲みます |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | 丸括弧や他の文字など、指定された文字で数学要素を囲みます |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | このインスタンスを関数名として、IMathElement を引数とする関数を呼び出します |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | このインスタンスを関数名として、文字列を引数とする関数を呼び出します |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | 子要素を取得します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 下側の波括弧を使用してこの要素をグループに配置します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 下側の波括弧などのグルーピング文字を使用してこの要素をグループに配置します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 上限・下限なしで積分を取ります |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | MathIntegralTypes と IMathElement、IMathElement を使用して積分を取ります |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | MathIntegralTypes と文字列、文字列 を使用して積分を取ります |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | MathIntegralTypes と IMathElement、IMathElement、MathLimitLocations を使用して積分を取ります |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | MathIntegralTypes と文字列、文字列、MathLimitLocations を使用して積分を取ります |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 数学要素を結合して数学ブロックを形成します |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 数学テキストを結合して数学ブロックを形成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N 変数演算子を作成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N 変数演算子を作成します |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | この要素の上部にバーを設定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定された引数から指定された次数の数学的ルートを設定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定された引数から指定された次数の数学的ルートを設定します |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 下限を取ります |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 下限を取ります |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 下付き文字を作成します |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 下付き文字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 左側に下付き文字と上付き文字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 左側に下付き文字と上付き文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 右側に下付き文字と上付き文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 右側に下付き文字と上付き文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 上付き文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 上付き文字を作成します |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 上限を取ります |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 上限を取ります |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | この要素をボーダーボックスに配置します |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素をボーダーボックスに配置します |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | この要素を非表示ボックス（論理グループ）に配置します。このボックスは数式やその他のテキストの構成要素をグループ化するために使用され、演算子エミュレータとして整列点の有無や改行点として、または改行を許可しないようにグループ化することができます。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 縦方向の配列に配置します |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | この要素の下部にバーを設定します |

### 例

例:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### 参照

* クラス [MathElementBase](../mathelementbase)
* インターフェイス [IMathDelimiter](../imathdelimiter)
* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->