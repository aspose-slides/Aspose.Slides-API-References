---
title: MathDelimiter
second_title: Aspose.Sildes 用於 .NET 的 API 參考
description: 指定分隔符物件，由開啟與關閉字元組成，如圓括號、花括號、方括號和直線，且內部包含一個或多個以指定字元分隔的數學元素。範例 2 2x7C2
type: docs
weight: 8650
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter 類別

指定分隔符物件，由開啟與關閉字元組成（例如圓括號、花括號、方括號與直線），以及內部一個或多個以指定字元分隔的數學元素。範例：(𝑥2)；[𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## 建構函式

| 名稱 | 說明 |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | 以指定的元素作為單一基礎參數來初始化 MathDelimiter |

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | 一個或多個以分隔字元分隔的數學元素 |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Delimiter Beginning Character 指定起始（開啟）分隔字元。數學分隔符是圍繞字元，例如圓括號、方括號與花括號。預設值：'('。 |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | 指定分隔符物件中分隔符的形狀。當為 MathDelimiterShape.Centered 時，分隔符會在數學文字的數學軸上居中，且仍會調整以符合其內容的整個高度。當為 MathDelimiterShape.Match 時，其高度與形狀會被改變以完全匹配其內容。 |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimiter Ending Character 指定結束（關閉）分隔字元。數學分隔符是圍繞字元，例如圓括號、方括號與花括號。預設值：')'。 |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的成長方式。當為 true 時，分隔符會垂直增長以匹配其運算元的高度。預設值為 true。 |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimiter Separator Character 指定分隔物件中分隔參數的字元。預設值：'&#x7C;'。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 設定一個重音記號（此元素上方的字元） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 以此實例作為參數，使用指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 以此實例作為參數，使用指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 以此實例作為參數，使用指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 以此實例作為參數，並使用指定的額外參數，呼叫指定的函式 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 以此實例作為參數，並使用指定的額外參數，呼叫指定的函式 |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | 使用指定的分隔字元來分隔參數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子與指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子與指定的分母建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 以此分子與指定的分母，依指定類型建立分數 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 以此分子與指定的分母，依指定類型建立分數 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 將數學元素包於圓括號中 |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | 將數學元素以指定字元（如圓括號或其他字元）包圍 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 以此實例作為函式名稱，對參數使用函式 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 以此實例作為函式名稱，對參數使用函式 |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | 取得子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括號將此元素置於一個群組中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分組字元（例如底部大括號或其他）將此元素置於群組中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 取得無上下限的積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取得積分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取得積分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 將數學元素合併並形成數學區塊 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 將數學文字合併並形成數學區塊 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 建立 N 元運算子 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 建立 N 元運算子 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素上方設定一條橫線 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定給定次方根的數學根來源於指定的參數。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定給定次方根的數學根來源於指定的參數。 |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 放入邊框盒中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 將此元素放入非可視盒（邏輯分組）中，用於將方程式或其他數學文字的組件分組。盒狀物件可以（例如）作為具有或不具有對齊點的運算子模擬器、作為換行點，或被分組以防止在內部換行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直陣列中 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部設定一條橫線 |

### 範例

Example:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### 參見

* 類別 [MathElementBase](../mathelementbase)
* 介面 [IMathDelimiter](../imathdelimiter)
* 命名空間 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->