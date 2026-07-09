---
title: MathFraction
second_title: Aspose.Sildes for .NET API 參考
description: 指定分數物件，由分子與分母組成，兩者以分數線分隔。分數線可為水平或對角線，取決於分數屬性。分數物件亦用於表示堆疊函式，將一個元素放在另一個元素上方，且無分數線。
type: docs
weight: 8690
url: /zh-hant/aspose.slides.mathtext/mathfraction/
---
## MathFraction 類別

指定分數物件，由分子與分母組成，兩者以分數線分隔。分數線可為水平或對角線，取決於分數屬性。分數物件亦用於表示堆疊函式，將一個元素放在另一個元素上方，且無分數線。

```csharp
public sealed class MathFraction : MathElementBase, IMathFraction
```

## 建構式

| 名稱 | 說明 |
| --- | --- |
| [MathFraction](mathfraction#constructor)(IMathElement, IMathElement) | 初始化型別為「Bar」的 MathFraction，指定分子與分母 |
| [MathFraction](mathfraction#constructor_1)(IMathElement, IMathElement, MathFractionTypes) | 初始化 MathFraction，指定分子、分母與類型 |

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Denominator](../../aspose.slides.mathtext/mathfraction/denominator) { get; } | 分母 |
| [FractionType](../../aspose.slides.mathtext/mathfraction/fractiontype) { get; set; } | 分數類型，預設：Bar |
| [Numerator](../../aspose.slides.mathtext/mathfraction/numerator) { get; } | 分子 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 設定此元素上方的重音符號（字元） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此實例作為參數，取得指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此實例作為參數，取得指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此實例作為參數，取得指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此實例作為參數，並加上指定的額外參數，取得指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此實例作為參數，並加上指定的額外參數，取得指定函式 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 以此分子和指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 以此分子和指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 以此分子、指定分母與指定類型建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 以此分子、指定分母與指定類型建立分數 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 用括號將數學元素包起來 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 用指定字元（如括號或其他字元）將數學元素框住 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 以此實例作為函式名稱，取得單一參數的函式 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 以此實例作為函式名稱，取得單一參數的函式 |
| [GetChildren](../../aspose.slides.mathtext/mathfraction/getchildren)() | 取得子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括號將此元素放入群組 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分組字元（如底部大括號或其他）將此元素放入群組 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 取得無上下限的積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取得積分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 合併數學元素並形成數學區塊 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 合併數學文字並形成數學區塊 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 元運算子 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 建立 N 元運算子 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素上方加上一條線 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 從指定參數取得指定階次的數學根號 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 從指定參數取得指定階次的數學根號 |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 將此元素置於邊框盒中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 將此元素置於邊框盒中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 將此元素置於非可視盒（邏輯分組），用於將方程式或其他數學文字的組件分組。盒狀物件可（例如）作為具或不具對齊點的運算子模擬器、作為換行點，或分組以防止換行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直陣列 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部加上一條線 |

### 範例

範例：

```csharp
[C#]
MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```

### 另請參閱

* 類別 [MathElementBase](../mathelementbase)
* 介面 [IMathFraction](../imathfraction)
* 命名空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->