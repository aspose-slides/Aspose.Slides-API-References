---
title: MathAccent
second_title: Aspose.Sildes for .NET API 參考
description: 指定音調功能，由基礎與組合變音符號組成 範例 ́
type: docs
weight: 8550
url: /zh-hant/aspose.slides.mathtext/mathaccent/
---
## MathAccent 類別

Specifies the accent function, consisting of a base and a combining diacritical mark Example: 𝑎́

```csharp
public sealed class MathAccent : MathElementBase, IMathAccent
```

## 建構函式

| 名稱 | 描述 |
| --- | --- |
| [MathAccent](mathaccent#constructor)(IMathElement) | 建立一個套用於指定數學元素且使用預設音調字元值的數學音調 |
| [MathAccent](mathaccent#constructor_1)(IMathElement, char) | 建立一個套用於指定數學元素的數學音調 |

## 屬性

| 名稱 | 描述 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathaccent/base) { get; } | 套用音調的參數 |
| [Character](../../aspose.slides.mathtext/mathaccent/character) { get; set; } | 音調字元 值應位於 (U+0300–U+036F) 或 (U+20D0–U+20EF) 範圍內 預設值：組合抑揚符號 (U+0302) |

## 方法

| 名稱 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 設定一個音調標記（此元素上方的字元） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此實例作為參數調用指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此實例作為參數調用指定的單參數函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此實例作為參數調用指定函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此實例作為參數，並使用指定的額外參數，調用指定的雙參數函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此實例作為參數，並使用指定的額外參數，調用指定的雙參數函式 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 以此作為分子，並以指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 以此作為分子，並以指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 以此作為分子，並以指定的分母建立指定類型的分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 以此作為分子，並以指定的分母建立指定類型的分數 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 將數學元素置於括號中 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 將數學元素置於指定字元（例如括號或其他字元）之中作為框架 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 以此實例作為函式名稱，取得參數的函式 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 以此實例作為函式名稱，取得參數的函式 |
| [GetChildren](../../aspose.slides.mathtext/mathaccent/getchildren)() | 取得子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部的大括號將此元素放入群組 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分組字元（例如底部大括號或其他）將此元素置於群組中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 取得無上下限的積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取得積分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 合併數學元素並形成數學區塊 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 合併數學文字並形成數學區塊 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 元運算子 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 建立 N 元運算子 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素上方設定橫線 |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 將此元素放入非可視盒（邏輯分組），用於將等式或其他數學文字的組件分組。此盒狀物件可（例如）作為具或不具對齊點的運算子模擬器、作為換行點，或被分組以防止內部換行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直陣列中 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部設定橫線 |

### 範例

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("x");
MathAccent accent = new MathAccent(baseElement, '~');
```

### 另請參閱

* 類別 [MathElementBase](../mathelementbase)
* 介面 [IMathAccent](../imathaccent)
* 命名空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->