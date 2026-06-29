---
title: MathMatrix
second_title: Aspose.Sildes for .NET API リファレンス
description: 子要素が1つ以上の行と列に配置された Matrix オブジェクトを指定します。マトリックスには組み込みのデリミタがないことに注意してください。マトリックスを括弧で囲むには、デリミタ オブジェクト IMathDelimiter を使用する必要があります。null 引数を使用してマトリックス内に空白を作成できます。
type: docs
weight: 8830
url: /ja/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix クラス

行や列が1つ以上配置された子要素で構成される Matrix オブジェクトを指定します。マトリックスには組み込みのデリミタがないことに注意してください。マトリックスを括弧で囲むには、デリミタ オブジェクト (IMathDelimiter) を使用する必要があります。null 引数を使用してマトリックス内に空白を作成できます。

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | MathMatrix クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | 周囲のテキストに対する垂直方向の配置を指定します。可能な値は top、bottom、center です。デフォルト: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | マトリックスの列数 |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | 列間の水平間隔の値です。ColumnGapRule が 3 (\"Exactly\") に設定されている場合、単位は twips (1/20 ポイント) と解釈されます。ColumnGapRule が 4 (\"Multiple\") に設定されている場合、単位は 0.5 em の増分数として解釈されます。その他の場合は無視されます。デフォルト: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | 列間の水平間隔のタイプです。水平間隔の単位は em またはポイント (twips として保存) です。デフォルト: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | 空のマトリックス要素のプレースホルダーを非表示にします。デフォルト: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | マトリックスの要素 |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | twips (1/20 ポイント) 単位の最小列幅。ギャップ間隔（「Column Gap」または「Gap Width」とも呼ばれる）は MinColumnWidth に加算され、合計の Matrix Column Spacing（異なる列の同じエッジ間の距離）を決定します。デフォルト: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | マトリックスの行数 |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | 行間の垂直間隔の値です。RowGapRule が 3 (\"Exactly\") に設定されている場合、単位は twips (1/20 ポイント) と解釈されます。RowGapRule が 4 (\"Multiple\") に設定されている場合、単位は半行として解釈されます。デフォルト: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | 行間の垂直間隔のタイプです。垂直間隔の単位は lines またはポイント (twips として保存) です。デフォルト: SingleSpacingGap (0) |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | この要素の上にアクセント記号（文字）を設定します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | このインスタンスを引数として指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | このインスタンスを引数として指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | このインスタンスを引数として指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | このインスタンスを最初の引数、指定された追加引数を第二引数として、指定された関数を取得します |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | このインスタンスを最初の引数、指定された追加引数を第二引数として、指定された関数を取得します |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | 指定された列を削除します |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | 指定された行を削除します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | この分子と指定された分母で分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 数式要素を丸括弧で囲みます |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 丸括弧や他の文字など、指定された文字で数式要素を囲みます |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | このインスタンスを関数名として、引数の関数を取得します |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | このインスタンスを関数名として、引数の関数を取得します |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | 子要素を取得します |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | 指定された列の水平配置を取得します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 下側の波かっこを使用してこの要素をグループ化します |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 下側の波かっこなどのグループ文字を使用してこの要素をグループ化します |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | 指定された列の後に新しい列を挿入します。新しい列のすべての要素は初期的に null です。 |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | 指定された列の前に新しい列を挿入します。新しい列のすべての要素は初期的に null です。 |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | 指定された行の後に新しい行を挿入します。新しい行のすべての要素は初期的に null です。 |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | 指定された行の前に新しい行を挿入します。新しい行のすべての要素は初期的に null です。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 上下限なしで積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 積分を取得します |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 積分を取得します |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 数学要素を結合し、数学ブロックを形成します |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 数学テキストを結合し、数学ブロックを形成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N 変量演算子を作成します |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N 変量演算子を作成します |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | この要素の上部にバーを設定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定された引数から、指定された次数の数学的根を指定します |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定された引数から、指定された次数の数学的根を指定します |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | 指定された列の水平配置を設定します |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | 指定された列の水平配置を設定します |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 下限を取得します |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 下限を取得します |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 添字を作成します |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 添字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMMathElement) | 左側に添字と上付き文字を作成します |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 左側に添字と上付き文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 右側に添字と上付き文字を作成します |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 右側に添字と上付き文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 上付き文字を作成します |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 上付き文字を作成します |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 上限を取得します |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 上限を取得します |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | この要素をボーダーボックスに配置します |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | この要素をボーダーボックスに配置します |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | この要素を非表示ボックス（論理的グルーピング）に配置します。これは、等式やその他の数式テキストのコンポーネントをグループ化するために使用されます。ボックス化されたオブジェクトは、例えば、配置点の有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして機能したり、改行を許可しないようにグループ化したりできます。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 縦方向の配列に配置します |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | この要素の下部にバーを設定します |

### 例

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### 参照

* クラス [MathElementBase](../mathelementbase)
* インターフェイス [IMathMatrix](../imathmatrix)
* 名前空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->