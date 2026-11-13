---
title: IMathElement
second_title: Aspose.Sildes for .NET API 參考
description: 任何數學元素（如分數、數學文字、函式、含多個元素的表達式等）的基礎介面
type: docs
weight: 8250
url: /zh-hant/aspose.slides.mathtext/imathelement/
---
## IMathElement 介面

任何數學元素的基礎介面：分數、數學文字、函式、包含多個元素的表達式等

```csharp
public interface IMathElement
```

## 方法

| 名稱 | 說明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | 設定一個重音符號（此元素上方的字元） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | 以此實例作為參數，套用指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | 以此實例作為參數，套用指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | 以此實例作為參數，套用指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | 以此實例作為參數，並以指定的額外參數套用指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | 以此實例作為參數，並以指定的額外參數套用指定的函式 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | 使用此分子和指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | 使用此分子和指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | 使用此分子和指定的分母，依指定類型建立分數 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | 使用此分子和指定的分母，依指定類型建立分數 |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | 將數學元素括於括號中 |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | 使用指定的字元（如括號或其他字元）將此元素框住 |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | 以此實例作為函式名稱，取得一個帶參數的函式 |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | 以此實例作為函式名稱，取得一個帶參數的函式 |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | 取得子元素 |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | 使用底部大括號將此元素放入群組 |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | 使用分組字元（例如底部大括號或其他）將此元素放入群組 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | 取得無上下限的積分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | 取得積分 |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | 將數學元素連接起來，形成數學區塊 |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | 將數學文字連接起來，形成數學區塊 |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 元運算子 |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | 建立 N 元運算子 |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | 在此元素上方加上橫線 |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | 指定給定次方的根號，使用指定的參數 |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | 指定給定次方的根號，使用指定的參數 |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | 取得下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | 取得下限 |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | 建立下標 |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | 建立下標 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左側建立下標及上標 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | 在左側建立下標及上標 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右側建立下標及上標 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | 在右側建立下標及上標 |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | 建立上標 |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | 建立上標 |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | 取得上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | 取得上限 |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | 將此元素放入邊框盒中 |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | 將此元素放入邊框盒中 |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | 將此元素放入非可視盒（邏輯分組），用於將方程式或其他數學文字的元件分組。盒子物件可（例如）作為帶或不帶對齊點的運算子模擬器，作為換行點，或以不允許換行的方式分組。 |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | 放入垂直陣列 |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | 在此元素底部設定橫線 |

### 範例

Example:
```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### 相關參考

* 命名空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->