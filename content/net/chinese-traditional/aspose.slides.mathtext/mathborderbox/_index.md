---
title: MathBorderBox
second_title: Aspose.Sildes for .NET API 參考
description: 在 IMathElement 周圍繪製矩形或其他邊框。
type: docs
weight: 8630
url: /zh-hant/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox 類別

Draws a rectangular or some other border around the IMathElement.

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## 建構函式

| Name | Description |
| --- | --- |
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | 建立具有矩形邊框的 MathBorderBox 元素 |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | 建立 MathBorderBox 元素 |

## 屬性

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | 基礎參數 |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | Hide Bottom Edge (default is false) - 指定邊框盒底部邊緣的隱藏或顯示狀態。 |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | Hide Left Edge (default is false) - 指定邊框盒左側邊緣的隱藏或顯示狀態。 |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | Hide Right Edge (default is false) - 指定邊框盒右側邊緣的隱藏或顯示狀態。 |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | Hide Top Edge (default is false) - 指定邊框盒頂部邊緣的隱藏或顯示狀態。 |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | Strikethrough Bottom-Left to Top-Right (default is false). 指定邊框盒左下角到右上角的斜刪除線的隱藏或顯示狀態。 |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | Strikethrough Horizontal (default is false) - 指定水平刪除線的隱藏或顯示狀態。 |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | Strikethrough Top-Left to Bottom-Right (default is false). 指定邊框盒左上角到右下角的斜刪除線的隱藏或顯示狀態。 |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | Strikethrough Vertical (default is false) - 指定垂直刪除線的隱藏或顯示狀態。 |

## 方法

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 設定附加符號（此元素上方的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此實例作為參數，套用指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此實例作為參數，套用指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此實例作為參數，套用指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此實例作為參數，並使用指定的額外參數，套用指定的兩參數函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此實例作為參數，並使用指定的額外參數，套用指定的兩參數函式 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 以此作為分子，建立分母為指定值的分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 以此作為分子，建立分母為指定值的分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 以此作為分子，建立指定類型且分母為指定值的分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 以此作為分子，建立指定類型且分母為指定值的分數 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 將數學元素包在括號內 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 將數學元素包在指定的字符內，如括號或其他框定字符 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此實例作為函式名稱，取用參數的函式 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此實例作為函式名稱，取用參數的函式 |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | 取得子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括號將此元素放入群組 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分組字符（例如底部大括號或其他）將此元素放入群組 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 取得無上下限的積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取得積分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 結合數學元素並形成數學區塊 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 結合數學文字並形成數學區塊 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 元運算子 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 建立 N 元運算子 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素上方設定橫線 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定指定參數的給定次方根 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定指定參數的給定次方根 |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 將此元素放入非可視方框（邏輯分組），用於將方程式或其他數學文字的組件分組。此方框物件可用作帶或不帶對齊點的運算子模擬器、作為換行點，或以不允許內部換行的方式分組。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直陣列 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部設定橫線 |

### 範例

範例：

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### 另請參閱

* 類別 [MathElementBase](../mathelementbase)
* 介面 [IMathBorderBox](../imathborderbox)
* 命名空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->