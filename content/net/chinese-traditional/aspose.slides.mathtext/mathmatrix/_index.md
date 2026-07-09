---
title: MathMatrix
second_title: Aspose.Sildes .NET API 參考
description: 指定 Matrix 物件，由排布在一或多列與欄的子元素組成。重要的是，矩陣本身不具內建分隔符號。若要將矩陣置於括號中，應使用分隔符物件 IMathDelimiter。可使用 null 參數在矩陣中建立空格。
type: docs
weight: 8850
url: /zh-hant/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix 類別

指定 Matrix 物件，由排布在一或多列與欄的子元素組成。重要的是，矩陣本身不具內建分隔符號。若要將矩陣置於括號中，應使用分隔符物件 (IMathDelimiter)。可使用 null 參數在矩陣中建立空格。

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## 建構函式

| 名稱 | 描述 |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | 初始化 MathMatrix 類別的新執行個體。 |

## 屬性

| 名稱 | 描述 |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | 指定相對於周圍文字的垂直對齊方式。可能的值有 top、bottom 和 center。預設：Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | 矩陣的欄數 |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | 矩陣欄之間水平間距的數值；如果 ColumnGapRule 設為 3（\"Exactly\"），則單位視為 twips（點的 1/20）。如果 ColumnGapRule 設為 4（\"Multiple\"），則單位視為 0.5 em 的增量數。在其他情況下會被忽略。預設：0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | 矩陣欄之間水平間距的類型；水平間距單位可以是 ems 或 points（以 twips 儲存）。預設：SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | 隱藏空矩陣元素的佔位符。預設：false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | 矩陣的元素 |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | 最小欄寬，以 twips（點的 1/20）為單位。間隙間距（亦稱「Column Gap」或「Gap Width」）會加到 MinColumnWidth，以決定整體矩陣欄間距（不同欄相同邊緣之間的距離）。預設：0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | 矩陣的列數 |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | 矩陣列之間垂直間距的數值；如果 RowGapRule 設為 3（\"Exactly\"），則單位視為 twips（點的 1/20）。如果 RowGapRule 設為 4（\"Multiple\"），則單位視為半行。預設：0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | 矩陣列之間垂直間距的類型；垂直間距單位可以是 lines 或 points（以 twips 儲存）。預設：SingleSpacingGap (0) |

## 方法

| 名稱 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 設定一個重音符號（此元素上方的字元） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此實例作為參數，執行指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此實例作為參數，執行指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此實例作為參數，執行指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此實例作為參數，並使用指定的額外參數，執行指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此實例作為參數，並使用指定的額外參數，執行指定的函式 |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | 刪除指定的欄 |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | 刪除指定的列 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 以此分子與指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 以此分子與指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 以指定類型、此分子與指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 以指定類型、此分子與指定的分母建立分數 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 將數學元素包以括號 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 將數學元素以指定字元（如括號或其他字元）框起 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此實例作為函式名稱，對參數執行函式 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此實例作為函式名稱，對參數執行函式 |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | 取得子元素 |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | 取得指定欄的水平對齊方式 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括號將此元素放入群組 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分組字元（例如底部大括號或其他）將此元素放入群組 |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | 在指定欄之後插入新欄，初始時新欄的所有元素皆為 null。 |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | 在指定欄之前插入新欄，初始時新欄的所有元素皆為 null。 |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | 在指定列之後插入新列，初始時新列的所有元素皆為 null。 |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | 在指定列之前插入新列，初始時新列的所有元素皆為 null。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 取得無上下限的積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取得積分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 將數學元素加入並形成數學區塊 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 將數學文字加入並形成數學區塊 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 元運算子 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 建立 N 元運算子 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素上方設定一條橫線 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定給定次方的數學根號，來源於指定的參數。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定給定次方的數學根號，來源於指定的參數。 |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | 設定指定欄的水平對齊方式 |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | 設定指定欄的水平對齊方式 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 取得下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 取得下限 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 建立下標 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 建立下標 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左側建立下標與上標 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左側建立下標與上標 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右側建立下標與上標 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右側建立下標與上標 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 建立上標 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 建立上標 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 取得上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 取得上限 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 將此元素放入邊框盒中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 將此元素放入邊框盒中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 將此元素放入非可視盒（邏輯分組），用於將方程式或其他數學文字的組件分組。盒狀物件可（例如）作為具有或不具有對齊點的運算子模擬器，作為換行點，或被分組以防止其中換行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直陣列 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部設定一條橫線 |

### 範例

示例：

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### 另請參閱

* 類別 [MathElementBase](../mathelementbase)
* 介面 [IMathMatrix](../imathmatrix)
* 命名空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->