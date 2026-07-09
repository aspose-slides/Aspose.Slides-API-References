---
title: MathBox
second_title: Aspose.Sildes for .NET API 參考
description: 指定數學元素的邏輯盒裝與封裝。舉例來說，盒裝物件可以作為具有或不具有對齊點的運算子模擬器、作為換行點，或被分組以防止在其中換行。例如，應將運算子盒裝以防止換行。
type: docs
weight: 8630
url: /zh-hant/aspose.slides.mathtext/mathbox/
---
## MathBox 類別

指定數學元素的邏輯盒裝（封裝）。例如，盒裝物件可以作為具有或不具有對齊點的運算子模擬器、作為換行點，或被分組以防止在其中換行。例如，應將「==」運算子盒裝，以防止換行。

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## 建構函式

| 名稱 | 描述 |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | 使用指定的元素作為參數來初始化 MathBox |

## 屬性

| 名稱 | 描述 |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | 為 true 時，此運算子模擬器充當對齊點；即其他等式中指定的對齊點可以與之對齊。預設值：false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | 基礎參數 |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | 微分 為 true 時，盒子作為微分（例如積分式中的 𝑑𝑥），並獲得適當的水平間距。預設值：false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | 明確換行 指定盒子物件起始處是否有換行，使行在盒子開始處換行。指定前一行數學文字中哪個運算子作為本行對齊點，可能值：1..255 預設值：0（無明確換行） |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | 不換行 此屬性指定物件盒的「不可斷行」屬性。為 true 時，盒子內部不能換行。對於由多個二元運算子組成的運算子模擬器尤其重要。未指定時，盒子內可換行。預設值：true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | 運算子模擬器 為 true 時，盒子及其內容視為單一運算子，繼承運算子的屬性。例如，該字元可以作為換行點，並可與其他運算子對齊。常用於多個字形合成的運算子（如 '=='）。預設值：false |

## 方法

| 名稱 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 設定此元素上方的重音符號（字元） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此實例作為參數來呼叫指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此實例作為參數來呼叫指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此實例作為參數來呼叫指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此實例作為參數並加入指定的額外參數來呼叫指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此實例作為參數並加入指定的額外參數來呼叫指定函式 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 以此分子和指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 以此分子和指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 以此分子、指定分母和指定類型建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 以此分子、指定分母和指定類型建立分數 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 用括號將數學元素括起來 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 用指定字元（如括號或其他字元）將數學元素框起來 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此實例作為函式名稱，將參數函式套用於此參數 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此實例作為函式名稱，將參數函式套用於此參數 |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | 取得子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括號將此元素放入群組 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用群組字元（如底部大括號或其他）將此元素放入群組 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 取得無上下限的積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取得積分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 連接數學元素並形成數學區塊 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 連接數學文字並形成數學區塊 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 進制運算子 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 建立 N 進制運算子 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素上方加上橫線 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定給定次方的數學根號，來源於指定參數 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定給定次方的數學根號，來源於指定參數 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 取得下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 取得下限 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 建立下標 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 建立下標 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左側同時建立下標與上標 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左側同時建立下標與上標 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右側同時建立下標與上標 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右側同時建立下標與上標 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 建立上標 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 建立上標 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 取得上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 取得上限 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 將此元素放入邊框盒 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 將此元素放入邊框盒 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 將此元素放入非可視盒（邏輯分組），用於將方程式或其他數學文字的組件分組。盒裝物件可（例如）作為具有或不具有對齊點的運算子模擬器、作為換行點，或被分組以防止在其中換行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直陣列 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素下方加上橫線 |

### 示例

示例：

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### 另請參閱

* 類別 [MathElementBase](../mathelementbase)
* 介面 [IMathBox](../imathbox)
* 命名空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->