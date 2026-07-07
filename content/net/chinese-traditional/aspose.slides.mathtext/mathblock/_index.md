---
title: MathBlock
second_title: Aspose.Sildes for .NET API 參考文件
description: 指定一個包含於 MathParagraph 且起始於獨立行的數學文字實例。所有數學區域，包括方程式、運算式、方程式或運算式的陣列以及公式，都以數學區塊表示。
type: docs
weight: 8590
url: /zh-hant/aspose.slides.mathtext/mathblock/
---
## MathBlock 類別

指定一個包含於 MathParagraph 且起始於獨立行的數學文字實例。所有數學區段，包括方程式、運算式、方程式或運算式陣列以及公式，都以數學區塊表示。

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## 建構式

| 名稱 | 說明 |
| --- | --- |
| [MathBlock](mathblock#constructor)() | 初始化 MathBlock 類別的新執行個體。 |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | 建立一個新的數學區塊並將指定的元素放入其中 |
| [MathBlock](mathblock#constructor_1)(IMathElement) | 建立一個新的數學區塊並將指定的元素放入其中 |

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | 取得集合中實際包含的子數學元素數量。唯讀 Int32。 |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | 傳回 false，因為子元素集合可以被修改。 |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | 取得或設定指定索引處的 IMathElement。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 設定重音符號（此元素上方的字元） |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | 在集合的末端新增一個數學元素。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此實例作為參數呼叫指定函式。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此實例作為參數呼叫指定函式。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此實例作為參數呼叫指定函式。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此實例作為參數，並加入指定的額外參數，呼叫兩參數函式。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此實例作為參數，並加入指定的額外參數，呼叫兩參數函式。 |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | 移除集合中的所有元素。 |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | 判斷集合是否包含特定值。 |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | 複製至指定的陣列。 |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | 以分隔字元（不含括號）區隔子元素。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子與指定的分母建立分數。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子與指定的分母建立分數。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 以此分子與指定的分母，依指定的類型建立分數。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 以此分子與指定的分母，依指定的類型建立分數。 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 將數學元素以括號括起。 |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | 使用指定的字元（如括號或其他字元）將此區塊的子元素框住。 |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | 使用指定的字元（如括號或其他）將此區塊的子元素框住，並以分隔字元區隔。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 以此實例作為函式名稱，對參數使用指定的函式。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 以此實例作為函式名稱，對參數使用指定的函式。 |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | 取得子元素。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括號將此元素放入群組。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分組字元（如底部大括號或其他）將此元素放入群組。 |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | 判斷特定數學元素在集合中的索引。 |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | 在指定索引處插入 MathElement 於集合中。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 取得無上下限的積分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取得積分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取得積分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得積分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取得積分。 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | 將數學元素與此數學區塊結合。 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | 將數學文字與此數學區塊結合。 |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | 將另一個數學區塊與此區塊結合。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 元運算子。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 建立 N 元運算子。 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素的上方加上橫線。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定給定次方的數學根，使用指定的參數。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定給定次方的數學根，使用指定的參數。 |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | 從集合中移除特定物件的第一次出現。 |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | 移除集合中指定索引處的元素。 |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 將此元素放入框線盒中。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 將此元素放入框線盒中。 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 將此元素放入非可視盒（邏輯分組），此盒用於將方程式或其他數學文字的組件分組。盒狀物件可（例如）作為帶或不帶對齊點的運算子模擬器、作為換行點，或被分組以防止內部換行。 |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | 將子元素以垂直陣列排列。 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部加上橫線。 |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | 將此 [`MathBlock`](../mathblock) 的內容儲存為 MathML |

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
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->