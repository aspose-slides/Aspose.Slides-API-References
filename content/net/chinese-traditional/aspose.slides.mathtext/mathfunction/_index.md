---
title: MathFunction
second_title: Aspose.Sildes for .NET API 參考文件
description: 指定一個參數的函式。
type: docs
weight: 8740
url: /zh-hant/aspose.slides.mathtext/mathfunction/
---
## MathFunction 類別

指定一個參數的函式。

```csharp
public sealed class MathFunction : MathElementBase, IMathFunction
```

## 建構式

| 名稱 | 說明 |
| --- | --- |
| [MathFunction](mathfunction#constructor)(IMathElement, IMathElement) | 初始化 MathFunction 類別的新執行個體。 |
| [MathFunction](mathfunction#constructor_1)(string, IMathElement) | 初始化 MathFunction 類別的新執行個體。 |

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathfunction/base) { get; } | 函式參數 |
| [Name](../../aspose.slides.mathtext/mathfunction/name) { get; } | 函式名稱 例如，函式名稱為 sin 和 cos |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 設定重音符號（此元素上方的字元） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 取得使用此實例作為參數的指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 取得使用此實例作為參數的指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 取得使用此實例作為參數的指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 取得使用此實例作為參數且具指定額外參數的指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 取得使用此實例作為參數且具指定額外參數的指定函式 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 以此分子和指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 以此分子和指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 以此分子和指定的分母，依指定類型建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 以此分子和指定的分母，依指定類型建立分數 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 將數學元素括於括號中 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 以指定字元（例如括號或其他字元）將數學元素框起來 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此實例作為函式名稱，取得一個參數的函式 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此實例作為函式名稱，取得一個參數的函式 |
| [GetChildren](../../aspose.slides.mathtext/mathfunction/getchildren)() | 取得子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括號將此元素置於群組中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用群組字元（例如底部大括號或其他）將此元素置於群組中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 取得無上/下限的積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取得積分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 將數學元素合併並形成數學區塊 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 將數學文字合併並形成數學區塊 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 元運算子 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 建立 N 元運算子 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素上方設定一條橫線 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定給定次方的數學根，來源於指定的參數。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定給定次方的數學根，來源於指定的參數。 |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 將此元素放入非可視方框（邏輯分組），用於將方程式或其他數學文字的組件分組。此方框物件可作為運算子模擬器（有或無對齊點）、換行點，或以不允許斷行的方式分組。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直陣列中 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素下方設定一條橫線 |

### 範例

範例：

```csharp
[C#]
MathFunction func = new MathFunction("sin", new MathematicalText("x"));
```

### 另請參閱

* 類別 [MathElementBase](../mathelementbase)
* 介面 [IMathFunction](../imathfunction)
* 命名空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->