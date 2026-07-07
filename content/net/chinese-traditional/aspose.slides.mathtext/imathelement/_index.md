---
title: IMathElement
second_title: Aspose.Slides for .NET API 參考
description: 任何數學元素（如分數、數學文字、函式、多元素表達式等）的基礎介面
type: docs
weight: 8230
url: /zh-hant/aspose.slides.mathtext/imathelement/
---
## IMathElement 介面

任何數學元素的基礎介面：分數、數學文字、函式、多元素表達式等

```csharp
public interface IMathElement
```

## 方法

| 名稱 | 說明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | 設定此元素上方的重音標記（位於此元素頂部的字元） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | 以此實例作為參數，套用指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | 以此實例作為參數，套用指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | 以此實例作為參數，套用指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | 以此實例作為參數，套用指定的函式，並加入指定的額外參數 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | 以此實例作為參數，套用指定的函式，並加入指定的額外參數 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | 使用此分子與指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | 使用此分子與指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | 依指定類型，使用此分子與指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | 依指定類型，使用此分子與指定的分母建立分數 |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | 將數學元素包在括號內 |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | 以指定字元（例如括號或其他字元）將此元素框起來 |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | 以此實例作為函式名稱，套用單一參數的函式 |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | 以此實例作為函式名稱，套用單一參數的函式 |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | 取得子元素 |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | 使用底部大括號將此元素放入群組 |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | 使用分組字元（如底部大括號或其他）將此元素放入群組 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | 取得無上下限的積分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | 取得積分 |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | 將數學元素合併成數學區塊 |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | 將數學文字合併成數學區塊 |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 進制運算子 |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | 建立 N 進制運算子 |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | 在此元素上方設定橫線 |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | 指定給定次方的數學根號，使用指定參數 |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | 指定給定次方的數學根號，使用指定參數 |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | 取得下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | 取得下限 |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | 建立下標 |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | 建立下標 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左側建立下標與上標 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | 在左側建立下標與上標 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右側建立下標與上標 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | 在右側建立下標與上標 |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | 建立上標 |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | 建立上標 |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | 取得上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | 取得上限 |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | 將此元素放入邊框盒 |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | 將此元素放入邊框盒 |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | 將此元素放入非可視方框（邏輯分組），用於將方程式或其他數學文字的組件分組。此方框物件可（例如）作為具有或不具有對齊點的運算子模擬器、作為換行點，或以分組方式避免在內部換行。 |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | 放入垂直陣列 |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | 在此元素底部設定橫線 |

### 範例

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### 參見

* 命名空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->