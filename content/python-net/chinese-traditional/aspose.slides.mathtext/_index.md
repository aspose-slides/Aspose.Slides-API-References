---
title: aspose.slides.mathtext
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/
---
包含用於在 Microsoft PowerPoint 簡報中處理數學文字的類別。
## 類別

| 類別 | 說明 |
| :- | :- |
| [`BaseScript`](/slides/python-net/zh-hant/aspose.slides.mathtext/basescript/) | 數學腳本 |
| [`IMathAccent`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathaccent/) | 指定重音功能，由基底和結合變音符號組成<br/>            範例： 𝑎́ |
| [`IMathAccentFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathaccentfactory/) | 允許建立數學重音 |
| [`IMathArray`](/slides/python-net/zh-hant/aspose.slides.mathtext/imatharray/) | 指定方程式或任何數學物件的垂直陣列 |
| [`IMathArrayFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imatharrayfactory/) | 允許建立數學陣列 |
| [`IMathBar`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathbar/) | 指定橫線函數，由基礎參數與上橫線或下橫線組成 |
| [`IMathBarFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathbarfactory/) | 允許建立數學橫線 |
| [`IMathBlock`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathblock/) | 指定位於 MathParagraph 內且自行換行的數學文字實例。<br/>            所有數學區域，包括方程式、運算式、方程式或運算式陣列以及公式，都以 math block 表示。 |
| [`IMathBlockCollection`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathblockcollection/) | math block (IMathBlock) 的集合 |
| [`IMathBlockFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathblockfactory/) | 允許建立 math block |
| [`IMathBorderBox`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathborderbox/) | 在 IMathElement 周圍繪製矩形或其他邊框。 |
| [`IMathBorderBoxFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathborderboxfactory/) | 允許建立 math border box |
| [`IMathBox`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathbox/) | 指定數學元素的邏輯盒裝（封裝）。<br/>            例如，盒裝的物件可以作為具備或不具備對齊點的運算子模擬器，<br/>            作為換行點，或被分組以避免內部換行。<br/>            例如，"==" 運算子應盒裝以防止換行。 |
| [`IMathBoxFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathboxfactory/) | 允許建立 math box |
| [`IMathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathdelimiter/) | 指定分隔符物件，由開啟與關閉字元（例如括號、<br/>            大括號、方括號與直線）以及內部一個或多個以指定字元分隔的數學元素組成。<br/>            範例： (𝑥2); [𝑥2\|𝑦2] |
| [`IMathDelimiterFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathdelimiterfactory/) | 允許建立 math delimiter |
| [`IMathElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathelement/) | 任何數學元素的基礎介面：<br/>            分數、數學文字、函式、含多個元素的運算式等 |
| [`IMathElementCollection`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathelementcollection/) | 表示數學元素 (MathElement) 的集合 |
| [`IMathFraction`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathfraction/) | 指定分數物件，由分子與分母以分數線分隔。<br/>            分數線可為水平或對角線，視分數屬性而定。<br/>            此分數物件亦用於表示堆疊函式，將一個元素置於另一個之上，且不使用分數線。 |
| [`IMathFractionFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathfractionfactory/) | 允許建立 math fraction |
| [`IMathFunction`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathfunction/) | 指定參數的函式 |
| [`IMathFunctionFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathfunctionfactory/) | 允許建立 math function |
| [`IMathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacter/) | 指定位於表達式上方或下方的分組符號，通常用於突顯元素之間的關係 |
| [`IMathGroupingCharacterFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathgroupingcharacterfactory/) | 允許建立 math grouping character |
| [`IMathLeftSubSuperscriptElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathleftsubsuperscriptelement/) | 指定上下標物件，由基底 <br/>            以及放置於基底左側的下標與上標組成。 |
| [`IMathLimit`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathlimit/) | 指定極限物件，由基線上的文字以及其上方或下方的縮小文字組成。 |
| [`IMathLimitFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathlimitfactory/) | 允許建立 IMathLimit |
| [`IMathMatrix`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/) | 指定 Matrix 物件，由子元素以一或多列多欄的方式排列。<br/>            需要注意的是，矩陣本身不具備內建的分隔符。<br/>            若要將矩陣放入括號中，應使用分隔符物件 (IMathDelimiter)。<br/>            可使用 Null 參數在矩陣中建立空白。 |
| [`IMathMatrixFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrixfactory/) | 允許建立 math matrix |
| [`IMathNaryOperator`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathnaryoperator/) | 指定 N 元數學物件，例如求和與積分。<br/>            它由運算子、基底（或運算元）以及選擇性的上、下限組成。<br/>            N 元運算子的例子包括：Summation、Union、Intersection、Integral |
| [`IMathNaryOperatorFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathnaryoperatorfactory/) | 允許建立 IMathNaryOperator |
| [`IMathNaryOperatorProperties`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathnaryoperatorproperties/) | 指定 IMathNaryOperator 的屬性 |
| [`IMathParagraph`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathparagraph/) | 作為數學區塊 (IMathBlock) 容器的數學段落 |
| [`IMathParagraphFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathparagraphfactory/) | 允許建立 math paragraph |
| [`IMathPhantom`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/) | 表示幽靈數學物件 (<m:phant>)，影響其子元素的版面配置<br/>            而不一定顯示。幽靈可隱藏其基底表達式，同時保留寬度、高度或深度，以對齊公式或預留空間。<br/>            其可見性與幾何行為由屬性如 Show、ZeroWid、ZeroAsc、<br/>            ZeroDesc 與 Transp 控制。 |
| [`IMathPortion`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathportion/) | 表示內含數學上下文的區段 |
| [`IMathRadical`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathradical/) | 指定根號函式，由基底與可選的指數組成。<br/>            根號物件範例為 √𝑥。 |
| [`IMathRadicalFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathradicalfactory/) | 允許建立 math radical |
| [`IMathRightSubSuperscriptElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathrightsubsuperscriptelement/) | 指定上下標物件，由基底 <br/>            以及放置於基底右側的下標與上標組成。 |
| [`IMathRightSubSuperscriptElementFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathrightsubsuperscriptelementfactory/) | 允許建立 IMathRightSubSuperscriptElementFactory |
| [`IMathSubscriptElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathsubscriptelement/) | 指定下標物件，由基底 <br/>            以及放置於右下方的縮小下標組成。 |
| [`IMathSubscriptElementFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathsubscriptelementfactory/) | 允許建立 IMathSubscriptElement |
| [`IMathSuperscriptElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathsuperscriptelement/) | 指定上標物件，由基底 <br/>            以及放置於右上方的縮小上標組成 |
| [`IMathSuperscriptElementFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathsuperscriptelementfactory/) | 允許建立 IMathSuperscriptElement |
| [`IMathematicalText`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathematicaltext/) | 數學文字 |
| [`IMathematicalTextFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathematicaltextfactory/) | 允許建立 MathematicalText 元素 |
| [`MathAccent`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/) | 指定重音功能，由基底與結合變音符號組成<br/>            範例： 𝑎́ |
| [`MathAccentFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccentfactory/) | 允許建立 math accent |
| [`MathArray`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/) | 指定方程式或任何數學物件的垂直陣列 |
| [`MathArrayFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharrayfactory/) | 允許建立 math array |
| [`MathBar`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbar/) | 指定條形函式，由基礎參數與上橫線或下橫線組成 |
| [`MathBarFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbarfactory/) | 允許建立 math bar |
| [`MathBlock`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/) | 指定位於 MathParagraph 內且自行換行的數學文字實例。<br/>            所有數學區域，包括方程式、運算式、方程式或運算式陣列以及公式，都以 math block 表示。 |
| [`MathBlockFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblockfactory/) | 允許建立 math block |
| [`MathBorderBox`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/) | 在 IMathElement 周圍繪製矩形或其他邊框。 |
| [`MathBorderBoxFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderboxfactory/) | 允許建立 math border box |
| [`MathBox`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/) | 指定數學元素的邏輯盒裝（封裝）。<br/>            例如，盒裝的物件可作為具備或不具備對齊點的運算子模擬器，<br/>            作為換行點，或被分組以避免內部換行。<br/>            例如，\"==\" 運算子應盒裝以防止換行。 |
| [`MathBoxFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathboxfactory/) | 允許建立 math box |
| [`MathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/) | 指定分隔符物件，由開啟與關閉字元（例如括號、<br/>            大括號、方括號與直線）以及內部一個或多個以指定字元分隔的數學元素組成。<br/>            範例： (𝑥2); [𝑥2\|𝑦2] |
| [`MathDelimiterFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiterfactory/) | 允許建立 math delimiter |
| [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/) | IMathElement 的基底類別，實作所有子類別共用的部分方法<br/>            僅供內部使用。繼承類別必須為 IMathElement。 |
| [`MathFraction`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfraction/) | 指定分數物件，由分子與分母以分數線分隔。<br/>            分數線可為水平或對角線，視分數屬性而定。<br/>            此分數物件亦用於表示堆疊函式，將一個元素置於另一個之上，且不使用分數線。 |
| [`MathFractionFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfractionfactory/) | 允許建立 math fraction |
| [`MathFunction`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/) | 指定參數的函式 |
| [`MathFunctionFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunctionfactory/) | 允許建立 math function |
| [`MathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/) | 指定位於表達式上方或下方的分組符號，通常用於突顯元素之間的關係 |
| [`MathGroupingCharacterFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacterfactory/) | 允許建立 math grouping character |
| [`MathLeftSubSuperscriptElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathleftsubsuperscriptelement/) | 指定上下標物件，由基底 <br/>            以及放置於基底左側的下標與上標組成。 |
| [`MathLimit`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathlimit/) | 指定極限物件，由基線上的文字以及其上方或下方的縮小文字組成。 |
| [`MathLimitFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathlimitfactory/) | 允許建立 IMathLimit |
| [`MathMatrix`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/) | 指定 Matrix 物件，由子元素以一或多列多欄的方式排列。<br/>            需要注意的是，矩陣本身不具備內建的分隔符。<br/>            若要將矩陣放入括號中，應使用分隔符物件 (IMathDelimiter)。<br/>            可使用 Null 參數在矩陣中建立空白。 |
| [`MathMatrixFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrixfactory/) | 允許建立 math matrix |
| [`MathNaryOperator`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/) | 指定 N 元數學物件，例如求和與積分。<br/>            它由運算子、基底（或運算元）以及選擇性的上、下限組成。<br/>            N 元運算子的例子包括：Summation、Union、Intersection、Integral |
| [`MathNaryOperatorFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperatorfactory/) | 允許建立 IMathNaryOperator |
| [`MathParagraph`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathparagraph/) | 作為數學區塊 (IMathBlock) 容器的數學段落 |
| [`MathParagraphFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathparagraphfactory/) | 允許建立 math paragraph |
| [`MathPhantom`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/) | 表示幽靈數學物件 (<m:phant>)，影響其子元素的版面配置<br/>            而不一定顯示。幽靈可隱藏其基底表達式，同時保留寬度、高度或深度，以對齊公式或預留空間。<br/>            其可見性與幾何行為由屬性如 Show、ZeroWid、ZeroAsc、<br/>            ZeroDesc 與 Transp 控制。 |
| [`MathPortion`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathportion/) | 表示內含數學上下文的區段 |
| [`MathRadical`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathradical/) | 指定根號函式，由基底與可選的指數組成。<br/>            根號物件範例為 √𝑥。 |
| [`MathRadicalFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathradicalfactory/) | 允許建立 math radical |
| [`MathRightSubSuperscriptElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/) | 指定上下標物件，由基底 <br/>            以及放置於基底右側的下標與上標組成。 |
| [`MathRightSubSuperscriptElementFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/) | 允許建立 IMathRightSubSuperscriptElementFactory |
| [`MathSubscriptElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsubscriptelement/) | 指定下標物件，由基底 <br/>            以及放置於右下方的縮小下標組成。 |
| [`MathSubscriptElementFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsubscriptelementfactory/) | 允許建立 IMathSubscriptElement |
| [`MathSuperscriptElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/) | 指定上標物件，由基底 <br/>            以及放置於右上方的縮小上標組成。 |
| [`MathSuperscriptElementFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelementfactory/) | 允許建立 IMathSuperscriptElement |
| [`MathematicalText`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/) | 數學文字 |
| [`MathematicalTextFactory`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltextfactory/) | 允許建立 MathematicalText 元素 |

## 列舉

| 列舉 | 說明 |
| :- | :- |
| [`MathDelimiterShape`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimitershape/) | 分隔符相對於運算元內容的位置與大小 |
| [`MathFractionTypes`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfractiontypes/) | 分數類型 |
| [`MathFunctionsOfOneArgument`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunctionsofoneargument/) | 單參數常用數學函式 |
| [`MathFunctionsOfTwoArguments`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunctionsoftwoarguments/) | 雙參數常用數學函式 |
| [`MathHorizontalAlignment`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathhorizontalalignment/) | 水平對齊 |
| [`MathIntegralTypes`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathintegraltypes/) | 積分類型 |
| [`MathJustification`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathjustification/) | 指定 math paragraph 的對齊方式（同一段落內相鄰的數學文字實例系列） |
| [`MathLimitLocations`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathlimitlocations/) | n 元運算子中上下標（下標/上標）的位置 |
| [`MathNaryOperatorTypes`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperatortypes/) | Nary 運算子 IMathNaryOperator 類型（不含積分）<br/>            對於積分 [`MathIntegralTypes`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathintegraltypes) |
| [`MathRowSpacingRule`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrowspacingrule/) | 矩陣或陣列中欄之間垂直間距的類型 |
| [`MathSpacingRules`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathspacingrules/) | 矩陣欄之間間隙（水平間距）的類型 |
| [`MathTopBotPositions`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathtopbotpositions/) | 上下位置列舉 |
| [`MathVerticalAlignment`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathverticalalignment/) | 垂直對齊 |