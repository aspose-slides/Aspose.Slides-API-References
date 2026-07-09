---
title: MathBorderBox
second_title: Aspose.Sildes for .NET API 參考文件
description: 在 IMathElement 周圍繪製矩形或其他類型的框線。
type: docs
weight: 8610
url: /zh-hant/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox 類別

在 IMathElement 周圍繪製矩形或其他類型的框線。

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## 建構函式

| 名稱 | 說明 |
| --- | --- |
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | 建立帶有矩形框線的 MathBorderBox 元素 |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | 建立 MathBorderBox 元素 |

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | Base argument |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | Hide Bottom Edge (default is false) - 指定框線盒子底部邊緣的隱藏或顯示狀態。 |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | Hide Left Edge (default is false) - 指定框線盒子左側邊緣的隱藏或顯示狀態。 |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | Hide Right Edge (default is false) - 指定框線盒子右側邊緣的隱藏或顯示狀態。 |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | Hide Top Edge (default is false) - 指定框線盒子頂部邊緣的隱藏或顯示狀態。 |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | Strikethrough Bottom-Left to Top-Right (default is false) - 指定從左下角到右上角的對角刪除線的隱藏或顯示狀態。 |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | Strikethrough Horizontal (default is false) - 指定水平刪除線的隱藏或顯示狀態。 |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | Strikethrough Top-Left to Bottom-Right (default is false) - 指定從左上角到右下角的對角刪除線的隱藏或顯示狀態。 |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | Strikethrough Vertical (default is false) - 指定垂直刪除線的隱藏或顯示狀態。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 設定此元素上方的重音符號（字元）。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此實例作為參數，呼叫指定的函式。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此實例作為參數，呼叫指定的函式。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此實例作為參數，呼叫指定的函式。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此實例作為參數，並以指定的額外參數呼叫函式。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此實例作為參數，並以指定的額外參數呼叫函式。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 以此分子與指定的分母建立分數。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 以此分子與指定的分母建立分數。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 以此分子與指定的分母，建立指定類型的分數。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 以此分子與指定的分母，建立指定類型的分數。 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 用括號將數學元素括起來。 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 用指定的字元（例如括號或其他字元）將數學元素框住。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此實例作為函式名稱，將參數函式套用於指定的 IMathElement。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此實例作為函式名稱，將參數函式套用於指定的字串。 |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | 取得子元素。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 以底部大括號將此元素放入群組。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 以指定的分組字元（例如底部大括號或其他）將此元素放入群組。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 取得無上下限的積分符號。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取得帶有上下限的積分符號。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取得帶有上下限的積分符號。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得帶有上下限的積分符號。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取得帶有上下限的積分符號。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 將數學元素加入並形成數學區塊。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 將數學文字加入並形成數學區塊。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 元運算子。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 建立 N 元運算子。 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素上方加上橫線。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 從指定參數取得給定次方的數學根號。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 從指定參數取得給定次方的數學根號。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 取得下限。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 取得下限。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 建立下標。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 建立下標。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左側同時建立下標與上標。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左側同時建立下標與上標。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右側同時建立下標與上標。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右側同時建立下標與上標。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 建立上標。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 建立上標。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 取得上限。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 取得上限。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 將此元素放入框線盒中。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 將此元素放入框線盒中。 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 將此元素放入非視覺盒（邏輯分組），用於將方程式或其他數學文字的組件分組。盒狀物件可作為帶或不帶對齊點的運算子模擬器、換行點，或用於防止行內換行的分組。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直陣列。 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部加上橫線。 |

### 範例

範例：

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### 參見

* 類別 [MathElementBase](../mathelementbase)
* 介面 [IMathBorderBox](../imathborderbox)
* 命名空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->