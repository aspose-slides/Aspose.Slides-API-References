---
title: "Aspose::Slides::MathText"
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 157
url: /zh-hant/aspose.slides.mathtext/
---
## 類別

| 類別 | 描述 |
| --- | --- |
| [BaseScript](./basescript/) | 數學腳本 |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) 與 [Control](../aspose.slides/control/) 字元屬性 |
| [IMathAccent](./imathaccent/) | 指定重音功能，由基底和組合附加變音記號組成 示例： \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | 允許建立數學重音 |
| [IMathArray](./imatharray/) | 指定方程式或任何數學物件的垂直陣列 |
| [IMathArrayFactory](./imatharrayfactory/) | 允許建立數學陣列 |
| [IMathBar](./imathbar/) | 指定橫線函式，由基礎參數與上橫線或下橫線組成 |
| [IMathBarFactory](./imathbarfactory/) | 允許建立數學橫線 |
| [IMathBlock](./imathblock/) | 指定包含於 [MathParagraph](./mathparagraph/) 中且另起新行的數學文字實例。所有數學區域，包括方程式、表達式、方程式或表達式的陣列以及公式，都以數學區塊表示。 |
| [IMathBlockCollection](./imathblockcollection/) | 數學區塊的集合 ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | 允許建立數學區塊 |
| [IMathBorderBox](./imathborderbox/) | 在 [IMathElement](./imathelement/) 周圍繪製矩形或其他邊框。 |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | 允許建立數學邊框盒 |
| [IMathBox](./imathbox/) | 指定數學元素的邏輯框選（封裝）。例如，框選物件可作為帶或不帶對齊點的運算子模擬器、作為換行點，或被分組以防止內部換行。例如，\"==\" 運算子應被框選以防止換行。 |
| [IMathBoxFactory](./imathboxfactory/) | 允許建立數學框盒 |
| [IMathDelimiter](./imathdelimiter/) | 指定分隔符物件，由開閉字符（例如括號、花括號、方括號與垂直線）組成，內含一個或多個數學元素，並以指定字符分隔。範例：(\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | 允許建立數學分隔符 |
| [IMathElement](./imathelement/) | 任何數學元素（分數、數學文字、函式、多元素表達式等）的基礎介面 |
| [IMathElementCollection](./imathelementcollection/) | 代表數學元素（MathElement）的集合。 |
| [IMathematicalText](./imathematicaltext/) | 數學文字 |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | 允許建立 [MathematicalText](./mathematicaltext/) 元素 |
| [IMathFraction](./imathfraction/) | 指定分數物件，由分子與分母以分數線分隔。分數線可水平或斜向，取決於分數屬性。該分數物件亦用於表示堆疊函式，將一個元素置於另一個之上，且無分數線。 |
| [IMathFractionFactory](./imathfractionfactory/) | 允許建立數學分數 |
| [IMathFunction](./imathfunction/) | 指定帶參數的函式 |
| [IMathFunctionFactory](./imathfunctionfactory/) | 允許建立數學函式 |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | 指定位於表達式上方或下方的分組符號，通常用於突顯元素之間的關係 |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | 允許建立數學分組字符 |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | 指定上下標物件，由基底及置於左側的下標與上標組成 |
| [IMathLimit](./imathlimit/) | 指定極限物件，由基線文字與其上方或下方的縮小文字組成 |
| [IMathLimitFactory](./imathlimitfactory/) | 允許建立 [IMathLimit](./imathlimit/) |
| [IMathMatrix](./imathmatrix/) | 指定矩陣物件，由子元素以一或多列與欄位排列。需要注意的是矩陣本身不具備內建分隔符。若要將矩陣放入括號中，應使用分隔符物件 ([IMathDelimiter](./imathdelimiter/))。可使用空參數在矩陣中建立空隙。 |
| [IMathMatrixFactory](./imathmatrixfactory/) | 允許建立數學矩陣 |
| [IMathNaryOperator](./imathnaryoperator/) | 指定 N 元數學物件，例如 Summation 與 Integral。它由運算子、基底（或運算元）以及可選的上、下限組成。N 元運算子的範例有：Summation、Union、Intersection、Integral |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | 允許建立 [IMathNaryOperator](./imathnaryoperator/) |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | 指定 [IMathNaryOperator](./imathnaryoperator/) 的屬性 |
| [IMathParagraph](./imathparagraph/) | 數學段落，用於容納數學區塊（[IMathBlock](./imathblock/)） |
| [IMathParagraphFactory](./imathparagraphfactory/) | 允許建立數學段落 |
| [IMathPhantom](./imathphantom/) | 代表幽靈數學物件 (<m:phant>)，會影響其子元素的版面配置而不一定顯示。幽靈可隱藏基礎表達式，同時保留其寬度、高度或深度，以對齊公式或保留空間。可透過 Show、ZeroWid、ZeroAsc、ZeroDesc、Transp 等屬性控制可視性與幾何行為。 |
| [IMathPortion](./imathportion/) | 代表內含數學上下文的部分。 |
| [IMathRadical](./imathradical/) | 指定根號函式，由基底與可選的指數組成。根號物件範例為 \\u221A\\uD835\\uDC65。 |
| [IMathRadicalFactory](./imathradicalfactory/) | 允許建立數學根號 |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | 指定上下標物件，由基底及置於右側的下標與上標組成 |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | 允許建立 [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [IMathSubscriptElement](./imathsubscriptelement/) | 指定下標物件，由基底及置於右下方的縮小下標組成 |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | 允許建立 [IMathSubscriptElement](./imathsubscriptelement/) |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | 指定上標物件，由基底及置於右上方的縮小上標組成 |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | 允許建立 [IMathSuperscriptElement](./imathsuperscriptelement/) |
| [MathAccent](./mathaccent/) | 指定重音功能，由基底和組合附加變音記號組成 示例： \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | 允許建立數學重音 |
| [MathArray](./matharray/) | 指定方程式或任何數學物件的垂直陣列 |
| [MathArrayFactory](./matharrayfactory/) | 允許建立數學陣列 |
| [MathBar](./mathbar/) | 指定橫線函式，由基礎參數與上橫線或下橫線組成 |
| [MathBarFactory](./mathbarfactory/) | 允許建立數學橫線 |
| [MathBlock](./mathblock/) | 指定包含於 [MathParagraph](./mathparagraph/) 中且另起新行的數學文字實例。所有數學區域，包括方程式、表達式、方程式或表達式的陣列以及公式，都以數學區塊表示。 |
| [MathBlockFactory](./mathblockfactory/) | 允許建立數學區塊 |
| [MathBorderBox](./mathborderbox/) | 在 [IMathElement](./imathelement/) 周圍繪製矩形或其他邊框。 |
| [MathBorderBoxFactory](./mathborderboxfactory/) | 允許建立數學邊框盒 |
| [MathBox](./mathbox/) | 指定數學元素的邏輯框選（封裝）。例如，框選物件可作為帶或不帶對齊點的運算子模擬器、作為換行點，或被分組以防止內部換行。例如，\"==\" 運算子應被框選以防止換行。 |
| [MathBoxFactory](./mathboxfactory/) | 允許建立數學框盒 |
| [MathDelimiter](./mathdelimiter/) | 指定分隔符物件，由開閉字符（例如括號、花括號、方括號與垂直線）組成，內含一個或多個數學元素，並以指定字符分隔。範例：(\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | 允許建立數學分隔符 |
| [MathElementBase](./mathelementbase/) | [IMathElement](./imathelement/) 的基礎類別，實作部分所有繼承類別共用的方法 僅供內部使用。繼承類別必須為 [IMathElement](./imathelement/)。 |
| [MathematicalText](./mathematicaltext/) | 數學文字 |
| [MathematicalTextFactory](./mathematicaltextfactory/) | 允許建立 [MathematicalText](./mathematicaltext/) 元素 |
| [MathFraction](./mathfraction/) | 指定分數物件，由分子與分母以分數線分隔。分數線可水平或斜向，取決於分數屬性。該分數物件亦用於表示堆疊函式，將一個元素置於另一個之上，且無分數線。 |
| [MathFractionFactory](./mathfractionfactory/) | 允許建立數學分數 |
| [MathFunction](./mathfunction/) | 指定帶參數的函式 |
| [MathFunctionFactory](./mathfunctionfactory/) | 允許建立數學函式 |
| [MathGroupingCharacter](./mathgroupingcharacter/) | 指定位於表達式上方或下方的分組符號，通常用於突顯元素之間的關係 |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | 允許建立數學分組字符 |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | 指定上下標物件，由基底及置於左側的下標與上標組成 |
| [MathLimit](./mathlimit/) | 指定極限物件，由基線文字與其上方或下方的縮小文字組成 |
| [MathLimitFactory](./mathlimitfactory/) | 允許建立 [IMathLimit](./imathlimit/) |
| [MathMatrix](./mathmatrix/) | 指定矩陣物件，由子元素以一或多列與欄位排列。需要注意的是矩陣本身不具備內建分隔符。若要將矩陣放入括號中，應使用分隔符物件 ([IMathDelimiter](./imathdelimiter/))。可使用空參數在矩陣中建立空隙。 |
| [MathMatrixFactory](./mathmatrixfactory/) | 允許建立數學矩陣 |
| [MathNaryOperator](./mathnaryoperator/) | 指定 N 元數學物件，例如 Summation 與 Integral。它由運算子、基底（或運算元）以及可選的上、下限組成。N 元運算子的範例有：Summation、Union、Intersection、Integral |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | 允許建立 [IMathNaryOperator](./imathnaryoperator/) |
| [MathParagraph](./mathparagraph/) | 數學段落，用於容納數學區塊（[IMathBlock](./imathblock/)） |
| [MathParagraphFactory](./mathparagraphfactory/) | 允許建立數學段落 |
| [MathPhantom](./mathphantom/) | 代表幽靈數學物件 (<m:phant>)，會影響其子元素的版面配置而不一定顯示。幽靈可隱藏基礎表達式，同時保留其寬度、高度或深度，以對齊公式或保留空間。可透過 Show、ZeroWid、ZeroAsc、ZeroDesc、Transp 等屬性控制可視性與幾何行為。 |
| [MathPortion](./mathportion/) | 代表內含數學上下文的部分。 |
| [MathRadical](./mathradical/) | 指定根號函式，由基底與可選的指數組成。根號物件範例為 \\u221A\\uD835\\uDC65。 |
| [MathRadicalFactory](./mathradicalfactory/) | 允許建立數學根號 |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | 指定上下標物件，由基底及置於右側的下標與上標組成 |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | 允許建立 [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [MathSubscriptElement](./mathsubscriptelement/) | 指定下標物件，由基底及置於右下方的縮小下標組成 |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | 允許建立 [IMathSubscriptElement](./imathsubscriptelement/) |
| [MathSuperscriptElement](./mathsuperscriptelement/) | 指定上標物件，由基底及置於右上方的縮小上標組成 |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | 允許建立 [IMathSuperscriptElement](./imathsuperscriptelement/) |
## 列舉

| 列舉 | 描述 |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | 分隔符相對於運算元內容的位置與大小 |
| [MathFractionTypes](./mathfractiontypes/) | 分數類型 |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | 單參數常見數學函式 |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | 雙參數常見數學函式 |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | 水平對齊 |
| [MathIntegralTypes](./mathintegraltypes/) | 積分類型 |
| [MathJustification](./mathjustification/) | 指定數學段落的對齊方式（同一段落中相鄰的數學文字實例的系列）。 |
| [MathLimitLocations](./mathlimitlocations/) | n 元運算子中上下限（下標/上標）的位置。 |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | N 元運算子 [IMathNaryOperator](./imathnaryoperator/) 類型（不包括積分），對於積分則為 [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | 矩陣或陣列中欄位之間垂直間距的類型 |
| [MathSpacingRules](./mathspacingrules/) | 矩陣欄位之間間隙（水平間距）的類型 |
| [MathTopBotPositions](./mathtopbotpositions/) | 上/下位置列舉 |
| [MathVerticalAlignment](./mathverticalalignment/) | 垂直對齊 |