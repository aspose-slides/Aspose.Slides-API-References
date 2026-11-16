---
title: MathBlock
second_title: Aspose.Sildes for .NET API 參考
description: 指定一個包含於 MathParagraph 且獨占一行的數學文字實例。所有數學區域，包括等式、表達式、等式或表達式的陣列以及公式，都由 math block 表示。
type: docs
weight: 8610
url: /zh-hant/aspose.slides.mathtext/mathblock/
---
## MathBlock 類別

指定數學文字的實例，該實例包含於 MathParagraph 中，並在自己的行上開始。所有數學區域，包括等式、表達式、等式或表達式的陣列以及公式，都由 math block 表示。

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## 建構函式

| 名稱 | 說明 |
| --- | --- |
| [MathBlock](mathblock#constructor)() | 初始化 MathBlock 類別的一個新實例。 |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | 建立一個新的數學區塊，並將指定的元件放入其中 |
| [MathBlock](mathblock#constructor_1)(IMathElement) | 建立一個新的數學區塊，並將指定的元件放入其中 |

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | 取得集合中實際包含的子數學元素的數量。 唯讀 Int32。 |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | 返回 false，因為子元素集合可以被修改。 |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | 取得或設定指定索引處的 IMathElement。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 設定此元素上方的重音標記（此元素頂部的字元） |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | 在集合的末端加入一個數學元素。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 將指定的函式以此實例作為參數使用。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 將指定的函式以此實例作為參數使用。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 將指定的函式以此實例作為參數使用。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 將指定的函式以此實例作為參數，並使用指定的額外參數。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 將指定的函式以此實例作為參數，並使用指定的額外參數。 |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | 從集合中移除所有元素。 |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | 判斷集合是否包含特定值。 |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | 複製到指定的陣列。 |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | 以分隔字元（不含括號）界定子元素。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子和指定的分母建立分數。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子和指定的分母建立分數。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定的分母，依指定類型建立分數。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定的分母，依指定類型建立分數。 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 將數學元素括於括號內。 |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | 將此區塊的子元素以指定字元（如括號或其他字元）作為框架包住。 |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | 將此區塊的子元素以指定字元（如括號或其他）作為框架包住，並以分隔字元界定。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 以此實例作為函式名稱，將單一參數的函式套用於此。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 以此實例作為函式名稱，將單一參數的函式套用於此。 |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | 取得子元素。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括號將此元素放入群組。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分組字元（如底部大括號或其他）將此元素放入群組。 |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | 判斷特定數學元素在集合中的索引。 |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | 在指定索引處將 MathElement 插入集合。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 取得無上下限的積分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取得積分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取得積分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得積分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取得積分。 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | 將數學元素與此數學區塊合併。 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | 將數學文字與此數學區塊合併。 |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | 將另一個數學區塊與此區塊合併。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 元運算子。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 建立 N 元運算子。 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素的上方設定一條橫線。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定給定次方的數學根，使用指定的參數。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定給定次方的數學根，使用指定的參數。 |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | 從集合中移除第一個出現的特定物件。 |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | 從集合中移除指定索引處的元素。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 取得下限。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 取得下限。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 建立下標。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 建立下標。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左側建立下標與上標。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左側建立下標與上標。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右側建立下標與上標。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右側建立下標與上標。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 建立上標。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 建立上標。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 取得上限。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 取得上限。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放入邊框盒中。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放入邊框盒中。 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 將此元素放入非視覺盒（邏輯分組），用於將方程式或其他數學文字的組件分組。盒狀物件可以（例如）作為具或不具對齊點的運算子模擬器，作為換行點，或被分組以防止其中換行。 |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | 將子元素排列成垂直陣列。 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部設定一條橫線。 |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | 將此 [`MathBlock`](../mathblock) 的內容儲存為 MathML。 |

### 範例

範例：

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### 另請參閱

* 類別 [MathElementBase](../mathelementbase)
* 介面 [IMathBlock](../imathblock)
* 命名空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->