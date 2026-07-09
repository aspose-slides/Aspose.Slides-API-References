---
title: MathRightSubSuperscriptElement
second_title: Aspose.Sildes for .NET API 參考
description: 指定由基底以及放置在基底右側的下標與上標組成的下上標物件。
type: docs
weight: 8960
url: /zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement 類別

指定右側的下標/上標物件，該物件由基底以及放置在基底右側的下標與上標組成。

```csharp
public sealed class MathRightSubSuperscriptElement : BaseScript, IMathRightSubSuperscriptElement
```

## 建構函式

| 名稱 | 說明 |
| --- | --- |
| [MathRightSubSuperscriptElement](mathrightsubsuperscriptelement)(IMathElement, IMathElement, IMathElement) | 初始化 MathRightSubSuperscriptElement 類別的新執行個體。 |

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlignScripts](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/alignscripts) { get; set; } | 指定下標/上標的對齊方式。當為 true 時，下標與上標在水平方向上對齊。當為 false 時，它們會依據基底的形狀進行調整。預設值為 false。 |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | 基底參數 |
| [Subscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript) { get; } | 下標參數 |
| [Superscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript) { get; } | 上標參數 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 設定重音符號（此元素上方的字元） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 以此實例作為參數，取得指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 以此實例作為參數，取得指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 以此實例作為參數，取得指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 以此實例作為參數，並使用指定的額外參數，取得指定的二參數函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 以此實例作為參數，並使用指定的額外參數（字串），取得指定的二參數函式 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 以此作為分子，並使用指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 以此作為分子，並使用指定的分母（字串）建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 以此作為分子，並使用指定的分母，建立指定類型的分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 以此作為分子，並使用指定的分母（字串），建立指定類型的分數 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 將數學元素以括號括起 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 使用指定的字元（如括號或其他字元）將數學元素框起 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 以此實例作為函式名稱，取得以參數為函式的函式 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 以此實例作為函式名稱，取得以參數為函式的函式 |
| [GetChildren](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/getchildren)() | 取得子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括號將此元素放入群組 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分組字元（如底部大括號或其他）將此元素放入群組 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 取得無上下限的積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得帶有指定上下限位置的積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取得帶有指定上下限位置的積分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 將數學元素結合並形成數學區塊 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 將數學文字結合並形成數學區塊 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 元運算子 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 建立 N 元運算子 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素上方設定橫線 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定給定次方的數學根號，來源於指定的參數 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定給定次方的數學根號，來源於指定的參數 |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 將此元素放入非可視盒（邏輯分組），用於將方程式或其他數學文字的組件分組。此盒狀物件可作為具有或不具有對齊點的運算子模擬器、作為換行點，或被分組以防止內部換行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直陣列 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部設定橫線 |

### 範例

範例：

```csharp
[C#]
MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```

### 另請參閱

* 類別 [BaseScript](../basescript)
* 介面 [IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement)
* 命名空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->