---
title: Aspose.Slides.MathText
second_title: Aspose.Sildes for .NET API 參考文件
description: 包含用於在 Microsoft PowerPoint 簡報中處理數學文字的類別。
type: docs
weight: 140
url: /zh-hant/aspose.slides.mathtext/
---
包含用於在 Microsoft PowerPoint 簡報中處理數學文字的類別。

## 類別

| 類別 | 說明 |
| --- | --- |
| [BaseScript](./basescript) | 數學腳本 |
| [MathAccent](./mathaccent) | 指定重音功能，由基底和組合變音符號組成 範例：𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | 允許建立數學重音 |
| [MathArray](./matharray) | 指定方程式或任何數學物件的垂直陣列 |
| [MathArrayFactory](./matharrayfactory) | 允許建立數學陣列 |
| [MathBar](./mathbar) | 指定條形函數，由基底參數和上線或下線組成 |
| [MathBarFactory](./mathbarfactory) | 允許建立數學條形 |
| [MathBlock](./mathblock) | 指定包含在 MathParagraph 中且自行開始於新行的數學文字實例。所有數學區域，包括方程式、表達式、方程式或表達式的陣列以及公式，都以數學區塊表示。 |
| [MathBlockFactory](./mathblockfactory) | 允許建立數學區塊 |
| [MathBorderBox](./mathborderbox) | 在 IMathElement 周圍繪製矩形或其他邊框。 |
| [MathBorderBoxFactory](./mathborderboxfactory) | 允許建立數學邊框盒 |
| [MathBox](./mathbox) | 指定數學元素的邏輯封裝（打包）。例如，封裝的物件可以作為帶或不帶對齊點的運算子模擬器、作為換行點，或被分組以不允許在其內部換行。例如，應將 “==” 運算子封裝以防止換行。 |
| [MathBoxFactory](./mathboxfactory) | 允許建立數學盒 |
| [MathDelimiter](./mathdelimiter) | 指定分界符物件，由開啟和關閉字元（如括號、大括號、方括號和直條）組成，內含一個或多個數學元素，並以指定字元分隔。範例：(𝑥2)；[𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | 允許建立數學分界符 |
| [MathElementBase](./mathelementbase) | IMathElement 的基底類別，實作所有繼承類別共通的某些方法。僅供內部使用。繼承類別必須是 IMathElement。 |
| [MathematicalText](./mathematicaltext) | 數學文字 |
| [MathematicalTextFactory](./mathematicaltextfactory) | 允許建立 MathematicalText 元素 |
| [MathFraction](./mathfraction) | 指定分數物件，由分子與分母組成，兩者以分數線分隔。分數線可根據分數屬性為水平或對角線。分數物件亦用於表示堆疊函數，即將一個元素放在另一個元素之上，且不使用分數線。 |
| [MathFractionFactory](./mathfractionfactory) | 允許建立數學分數 |
| [MathFunction](./mathfunction) | 指定參數的函數。 |
| [MathFunctionFactory](./mathfunctionfactory) | 允許建立數學函數 |
| [MathGroupingCharacter](./mathgroupingcharacter) | 指定表達式上下的分組符號，通常用於突顯元素之間的關係 |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | 允許建立數學分組字元 |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | 指定上下標物件，由基底以及置於基底左側的下標與上標組成。 |
| [MathLimit](./mathlimit) | 指定極限物件，由基線上的文字以及緊接其上方或下方的縮小文字組成。 |
| [MathLimitFactory](./mathlimitfactory) | 允許建立 IMathLimit |
| [MathMatrix](./mathmatrix) | 指定矩陣物件，由子元素以一或多列多行排列。需注意矩陣本身沒有內建的分界符。若需將矩陣放入括號，應使用分界符物件 (IMathDelimiter)。可使用 null 參數在矩陣中創建空位。 |
| [MathMatrixFactory](./mathmatrixfactory) | 允許建立數學矩陣 |
| [MathNaryOperator](./mathnaryoperator) | 指定 N 元數學物件，例如求和與積分。它由運算子、基底（或操作元）以及可選的上、下限組成。N 元運算子的例子包括：Summation、Union、Intersection、Integral。 |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | 允許建立 IMathNaryOperator |
| [MathParagraph](./mathparagraph) | 數學段落，作為數學區塊 (IMathBlock) 的容器 |
| [MathParagraphFactory](./mathparagraphfactory) | 允許建立數學段落 |
| [MathPhantom](./mathphantom) | 表示一個 phantom 數學物件 (&lt;m:phant&gt;)，會影響其子元素的版面配置，但不一定顯示。phantom 可以隱藏其基礎表達式，同時保留寬度、高度或深度，以對齊公式或保留空間。可見性與幾何行為由屬性如 Show、ZeroWid、ZeroAsc、ZeroDesc 與 Transp 控制。 |
| [MathPortion](./mathportion) | 表示內含數學上下文的部分。 |
| [MathRadical](./mathradical) | 指定根號函數，由基底和可選的指數組成。根號物件範例為 √𝑥。 |
| [MathRadicalFactory](./mathradicalfactory) | 允許建立根號 |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | 指定上下標物件，由基底以及置於基底右側的下標與上標組成。 |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | 允許建立 IMathRightSubSuperscriptElementFactory |
| [MathSubscriptElement](./mathsubscriptelement) | 指定下標物件，由基底以及置於右下方的縮小下標組成。 |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | 允許建立 IMathSubscriptElement |
| [MathSuperscriptElement](./mathsuperscriptelement) | 指定上標物件，由基底以及置於右上方的縮小上標組成。 |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | 允許建立 IMathSuperscriptElement |

## 介面

| 介面 | 說明 |
| --- | --- |
| [IMathAccent](./imathaccent) | 指定重音功能，由基底和組合變音符號組成 範例：𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | 允許建立數學重音 |
| [IMathArray](./imatharray) | 指定方程式或任何數學物件的垂直陣列 |
| [IMathArrayFactory](./imatharrayfactory) | 允許建立數學陣列 |
| [IMathBar](./imathbar) | 指定條形函數，由基底參數和上線或下線組成 |
| [IMathBarFactory](./imathbarfactory) | 允許建立數學條形 |
| [IMathBlock](./imathblock) | 指定包含在 MathParagraph 中且自行開始於新行的數學文字實例。所有數學區域，包括方程式、表達式、方程式或表達式的陣列以及公式，都以數學區塊表示。 |
| [IMathBlockCollection](./imathblockcollection) | 數學區塊 (IMathBlock) 的集合 |
| [IMathBlockFactory](./imathblockfactory) | 允許建立數學區塊 |
| [IMathBorderBox](./imathborderbox) | 在 IMathElement 周圍繪製矩形或其他邊框。 |
| [IMathBorderBoxFactory](./imathborderboxfactory) | 允許建立數學邊框盒 |
| [IMathBox](./imathbox) | 指定數學元素的邏輯封裝（打包）。例如，封裝的物件可以作為帶或不帶對齊點的運算子模擬器、作為換行點，或被分組以不允許在其內部換行。例如，應將 “==” 運算子封裝以防止換行。 |
| [IMathBoxFactory](./imathboxfactory) | 允許建立數學盒 |
| [IMathDelimiter](./imathdelimiter) | 指定分界符物件，由開啟和關閉字元（如括號、大括號、方括號和直條）組成，內含一個或多個數學元素，並以指定字元分隔。範例：(𝑥2)；[𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | 允許建立數學分界符 |
| [IMathElement](./imathelement) | 任何數學元素（如分數、數學文字、函數、含多個元素的表達式等）的基礎介面 |
| [IMathElementCollection](./imathelementcollection) | 表示一個數學元素集合 (MathElement)。 |
| [IMathematicalText](./imathematicaltext) | 數學文字 |
| [IMathematicalTextFactory](./imathematicaltextfactory) | 允許建立 MathematicalText 元素 |
| [IMathFraction](./imathfraction) | 指定分數物件，由分子與分母組成，兩者以分數線分隔。分數線可根據分數屬性為水平或對角線。分數物件亦用於表示堆疊函數，即將一個元素放在另一個元素之上，且不使用分數線。 |
| [IMathFractionFactory](./imathfractionfactory) | 允許建立數學分數 |
| [IMathFunction](./imathfunction) | 指定參數的函數。 |
| [IMathFunctionFactory](./imathfunctionfactory) | 允許建立數學函數 |
| [IMathGroupingCharacter](./imathgroupingcharacter) | 指定表達式上下的分組符號，通常用於突顯元素之間的關係 |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | 允許建立數學分組字元 |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | 指定上下標物件，由基底以及置於基底左側的下標與上標組成。 |
| [IMathLimit](./imathlimit) | 指定極限物件，由基線上的文字以及緊接其上方或下方的縮小文字組成。 |
| [IMathLimitFactory](./imathlimitfactory) | 允許建立 IMathLimit |
| [IMathMatrix](./imathmatrix) | 指定矩陣物件，由子元素以一或多列多行排列。需注意矩陣本身沒有內建的分界符。若需將矩陣放入括號，應使用分界符物件 (IMathDelimiter)。可使用 null 參數在矩陣中創建空位。 |
| [IMathMatrixFactory](./imathmatrixfactory) | 允許建立數學矩陣 |
| [IMathNaryOperator](./imathnaryoperator) | 指定 N 元數學物件，例如求和與積分。它由運算子、基底（或操作元）以及可選的上、下限組成。N 元運算子的例子包括：Summation、Union、Intersection、Integral。 |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | 允許建立 IMathNaryOperator |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | 指定 IMathNaryOperator 的屬性 |
| [IMathParagraph](./imathparagraph) | 數學段落，作為數學區塊 (IMathBlock) 的容器 |
| [IMathParagraphFactory](./imathparagraphfactory) | 允許建立數學段落 |
| [IMathPhantom](./imathphantom) | 表示一個 phantom 數學物件 (&lt;m:phant&gt;)，會影響其子元素的版面配置，但不一定顯示。phantom 可以隱藏其基礎表達式，同時保留寬度、高度或深度，以對齊公式或保留空間。可見性與幾何行為由屬性如 Show、ZeroWid、ZeroAsc、ZeroDesc 與 Transp 控制。 |
| [IMathPortion](./imathportion) | 表示內含數學上下文的部分。 |
| [IMathRadical](./imathradical) | 指定根號函數，由基底和可選的指數組成。根號物件範例為 √𝑥。 |
| [IMathRadicalFactory](./imathradicalfactory) | 允許建立根號 |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | 指定上下標物件，由基底以及置於基底右側的下標與上標組成。 |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | 允許建立 IMathRightSubSuperscriptElementFactory |
| [IMathSubscriptElement](./imathsubscriptelement) | 指定下標物件，由基底以及置於右下方的縮小下標組成。 |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | 允許建立 IMathSubscriptElement |
| [IMathSuperscriptElement](./imathsuperscriptelement) | 指定上標物件，由基底以及置於右上方的縮小上標組成。 |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | 允許建立 IMathSuperscriptElement |

## 列舉

| 列舉 | 說明 |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | 分界符相對於運算元內容的位置與大小 |
| [MathFractionTypes](./mathfractiontypes) | 分數類型 |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | 常見單參數數學函數 |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | 常見雙參數數學函數 |
| [MathHorizontalAlignment](./mathhorizontalalignment) | 水平對齊 |
| [MathIntegralTypes](./mathintegraltypes) | 數學積分類型 |
| [MathJustification](./mathjustification) | 指定數學段落的對齊方式（同一段落中相鄰的多個數學文字實例） |
| [MathLimitLocations](./mathlimitlocations) | N 元運算子中上下限（下標/上標）的位置 |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | Nary 運算子 IMathNaryOperator 類型（不含積分），積分請見 [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | 矩陣或陣列中列與列之間垂直間距的類型 |
| [MathSpacingRules](./mathspacingrules) | 矩陣中列與列之間水平間距的類型 |
| [MathTopBotPositions](./mathtopbotpositions) | 上下位置列舉 |
| [MathVerticalAlignment](./mathverticalalignment) | 垂直對齊 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->