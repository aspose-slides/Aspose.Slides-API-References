---
title: MathBox
second_title: Aspose.Sildes .NET API 參考
description: 指定數學元素的邏輯盒裝（封裝）。例如，盒裝物件可以作為具有或不具有對齊點的運算子模擬器、作為換行點，或被分組以防止其內部換行。例如，應將運算子盒裝以防止換行。
type: docs
weight: 8650
url: /zh-hant/aspose.slides.mathtext/mathbox/
---
## MathBox 類別

指定數學元素的邏輯盒裝（封裝）。例如，盒裝物件可以作為具有或不具有對齊點的運算子模擬器、作為換行點，或被分組以防止其內部換行。例如，應將「==」運算子盒裝以防止換行。

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## 建構函式

| 名稱 | 說明 |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | 使用指定元素作為參數初始化 MathBox |

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | 為 true 時，此運算子模擬器作為對齊點；即其他方程式中指定的對齊點可與之對齊。預設值：false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | 基礎參數 |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differential 為 true 時，盒子充當微分（例如積分式中的 𝑑𝑥），且會獲得適當的數學微分水平間距。預設值：false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicit break 指定 Box 物件起始處是否有換行，即行在 Box 物件起始處換行。指定前一行數學文字中運算子的編號，該運算子將作為本行數學文字的對齊點。可能的數值：1..255。預設值：0（無明確換行） |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break 此屬性指定物件盒子的「不可斷行」屬性。為 true 時，盒子內部不會發生換行。這對由多個二元運算子組成的運算子模擬器尤為重要。若未指定此元素，則盒子內可換行。預設值：true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator 為 true 時，盒子及其內容表現為單一運算子，並繼承運算子的屬性。這意味著，例如，該字符可作為換行點，且可與其他運算子對齊。Operator Emulator 常在一個或多個字形組合成一個運算子時使用，例如 '=='。預設值：false |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 設定重音符號（此元素上方的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 以此實例作為參數取得指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 以此實例作為參數取得指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 以此實例作為參數取得指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 以此實例作為參數並傳入指定的額外參數，取得指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 以此實例作為參數並傳入指定的額外參數，取得指定的函式 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 以此分子與指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 以此分子與指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 以此分子與指定的分母，按指定類型建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 以此分子與指定的分母，按指定類型建立分數 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 將數學元素括於括號中 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 將數學元素以指定字元（如括號或其他字元）作為框架括起來 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 以此實例作為函式名稱，取得參數的函式 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 以此實例作為函式名稱，取得參數的函式 |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | 取得子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括號將此元素置於群組中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分組字元（如底部大括號或其他）將此元素置於群組中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 取得無上下限的積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取得積分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 將數學元素結合並形成數學區塊 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 將數學文字結合並形成數學區塊 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 元運算子 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 建立 N 元運算子 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素上方設定橫線 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定給定次數的數學根號，來源於指定參數 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定給定次數的數學根號，來源於指定參數 |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 將此元素放入非可視盒（邏輯分組），用於將方程式或其他數學文字的組件分組。盒裝物件可以（例如）作為具有或不具有對齊點的運算子模擬器、作為換行點，或被分組以防止其內部換行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直陣列 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素下方設定橫線 |

### 範例

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### 另請參閱

* 類別 [MathElementBase](../mathelementbase)
* 介面 [IMathBox](../imathbox)
* 命名空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->