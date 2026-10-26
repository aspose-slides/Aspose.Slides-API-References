---
title: aspose.slides.mathtext
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/
---
Microsoft PowerPoint プレゼンテーションで数式テキストを扱うためのクラスが含まれます。

## クラス

| クラス | 説明 |
| :- | :- |
| [`BaseScript`](/slides/python-net/ja/aspose.slides.mathtext/basescript/) | 数式スクリプト |
| [`IMathAccent`](/slides/python-net/ja/aspose.slides.mathtext/imathaccent/) | アクセント関数を指定します。基底と結合アクセント記号で構成されます<br/>            例: 𝑎́ |
| [`IMathAccentFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathaccentfactory/) | 数式アクセントを作成できます |
| [`IMathArray`](/slides/python-net/ja/aspose.slides.mathtext/imatharray/) | 方程式や任意の数式オブジェクトの垂直配列を指定します |
| [`IMathArrayFactory`](/slides/python-net/ja/aspose.slides.mathtext/imatharrayfactory/) | 数式配列を作成できます |
| [`IMathBar`](/slides/python-net/ja/aspose.slides.mathtext/imathbar/) | バー関数を指定します。基底引数と上バーまたは下バーで構成されます |
| [`IMathBarFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathbarfactory/) | 数式バーを作成できます |
| [`IMathBlock`](/slides/python-net/ja/aspose.slides.mathtext/imathblock/) | MathParagraph 内に含まれ、独自の行で開始する数式テキストのインスタンスを指定します。<br/>            方程式、式、方程式や式の配列、数式全体など、すべての数式領域は math block で表されます。 |
| [`IMathBlockCollection`](/slides/python-net/ja/aspose.slides.mathtext/imathblockcollection/) | math block (IMathBlock) のコレクション |
| [`IMathBlockFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathblockfactory/) | math block を作成できます |
| [`IMathBorderBox`](/slides/python-net/ja/aspose.slides.mathtext/imathborderbox/) | IMathElement の周囲に長方形またはその他の枠線を描画します。 |
| [`IMathBorderBoxFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathborderboxfactory/) | math border box を作成できます |
| [`IMathBox`](/slides/python-net/ja/aspose.slides.mathtext/imathbox/) | 数式要素の論理的なボックス化（パッケージ化）を指定します。<br/>            たとえば、ボックス化されたオブジェクトは配置点の有無にかかわらず演算子エミュレータとして機能したり、改行点として使用されたり、内部で改行を許可しないようにグループ化されたりします。<br/>            例として、"==" 演算子は改行を防ぐためにボックス化すべきです。 |
| [`IMathBoxFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathboxfactory/) | math box を作成できます |
| [`IMathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/imathdelimiter/) | 区切り文字オブジェクトを指定します。開き文字と閉じ文字（括弧、波括弧、角括弧、縦棒など）で構成され、内部に1つ以上の数式要素が指定文字で区切られます。<br/>            例: (𝑥2); [𝑥2\|𝑦2] |
| [`IMathDelimiterFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathdelimiterfactory/) | math delimiter を作成できます |
| [`IMathElement`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/) | 任意の数式要素の基本インターフェース:<br/>            分数、数式テキスト、関数、複数要素を持つ式など |
| [`IMathElementCollection`](/slides/python-net/ja/aspose.slides.mathtext/imathelementcollection/) | MathElement のコレクションを表します。 |
| [`IMathFraction`](/slides/python-net/ja/aspose.slides.mathtext/imathfraction/) | 分数オブジェクトを指定します。分子と分母が分数バーで区切られます。分数バーは水平または斜めにでき、分数のプロパティに依存します。分数オブジェクトは、バーなしで要素を上下に配置するスタック関数の表現にも使用されます。 |
| [`IMathFractionFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathfractionfactory/) | math fraction を作成できます |
| [`IMathFunction`](/slides/python-net/ja/aspose.slides.mathtext/imathfunction/) | 引数の関数を指定します。 |
| [`IMathFunctionFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathfunctionfactory/) | math function を作成できます |
| [`IMathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/) | 式の上下に配置されるグルーピング記号を指定します。通常、要素間の関係を強調するために使用されます。 |
| [`IMathGroupingCharacterFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacterfactory/) | math grouping character を作成できます |
| [`IMathLeftSubSuperscriptElement`](/slides/python-net/ja/aspose.slides.mathtext/imathleftsubsuperscriptelement/) | 基底と、基底の左側に配置される下付きと上付きからなる Sub-Superscript オブジェクトを指定します。 |
| [`IMathLimit`](/slides/python-net/ja/aspose.slides.mathtext/imathlimit/) | ベースライン上のテキストと、その直上または直下に配置される縮小テキストからなる Limit オブジェクトを指定します。 |
| [`IMathLimitFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathlimitfactory/) | IMathLimit を作成できます |
| [`IMathMatrix`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/) | 子要素が1つ以上の行と列に配置された Matrix オブジェクトを指定します。<br/>            行列には組み込みの区切り文字がないことに注意してください。<br/>            行列を括弧で囲むには delimiter オブジェクト (IMathDelimiter) を使用します。<br/>            Null 引数を使用して行列内にギャップを作成できます。 |
| [`IMathMatrixFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrixfactory/) | math matrix を作成できます |
| [`IMathNaryOperator`](/slides/python-net/ja/aspose.slides.mathtext/imathnaryoperator/) | 総和や積分などの N 項演算子オブジェクトを指定します。<br/>            演算子、基底（またはオペランド）、およびオプションの上限と下限で構成されます。<br/>            N 項演算子の例: 総和、和集合、交差、積分 |
| [`IMathNaryOperatorFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathnaryoperatorfactory/) | IMathNaryOperator を作成できます |
| [`IMathNaryOperatorProperties`](/slides/python-net/ja/aspose.slides.mathtext/imathnaryoperatorproperties/) | IMathNaryOperator のプロパティを指定します。 |
| [`IMathParagraph`](/slides/python-net/ja/aspose.slides.mathtext/imathparagraph/) | 数学ブロック (IMathBlock) を格納するコンテナである数式段落 |
| [`IMathParagraphFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathparagraphfactory/) | math paragraph を作成できます |
| [`IMathPhantom`](/slides/python-net/ja/aspose.slides.mathtext/imathphantom/) | 子要素のレイアウトに影響を与える phantom 数式オブジェクト (<m:phant>) を表しますが、必ずしも表示されません。phantom は基底式を非表示にしつつ、幅・高さ・深さを保持して数式の整列やスペース確保に利用できます。<br/>            表示や幾何特性は Show、ZeroWid、ZeroAsc、ZeroDesc、Transp などのプロパティで制御されます。 |
| [`IMathPortion`](/slides/python-net/ja/aspose.slides.mathtext/imathportion/) | 内部に数式コンテキストを持つ部分を表します。 |
| [`IMathRadical`](/slides/python-net/ja/aspose.slides.mathtext/imathradical/) | 基底とオプションの指数からなる根号関数を指定します。<br/>            例: √𝑥 |
| [`IMathRadicalFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathradicalfactory/) | math radical を作成できます |
| [`IMathRightSubSuperscriptElement`](/slides/python-net/ja/aspose.slides.mathtext/imathrightsubsuperscriptelement/) | 基底と、基底の右側に配置される下付きと上付きからなる Sub-Superscript オブジェクトを指定します。 |
| [`IMathRightSubSuperscriptElementFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathrightsubsuperscriptelementfactory/) | IMathRightSubSuperscriptElementFactory を作成できます |
| [`IMathSubscriptElement`](/slides/python-net/ja/aspose.slides.mathtext/imathsubscriptelement/) | 基底と、右下に配置される縮小サイズの下付きからなる subscript オブジェクトを指定します。 |
| [`IMathSubscriptElementFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathsubscriptelementfactory/) | IMathSubscriptElement を作成できます |
| [`IMathSuperscriptElement`](/slides/python-net/ja/aspose.slides.mathtext/imathsuperscriptelement/) | 基底と、右上に配置される縮小サイズの上付きからなる superscript オブジェクトを指定します。 |
| [`IMathSuperscriptElementFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathsuperscriptelementfactory/) | IMathSuperscriptElement を作成できます |
| [`IMathematicalText`](/slides/python-net/ja/aspose.slides.mathtext/imathematicaltext/) | 数式テキスト |
| [`IMathematicalTextFactory`](/slides/python-net/ja/aspose.slides.mathtext/imathematicaltextfactory/) | MathematicalText 要素を作成できます |
| [`MathAccent`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/) | アクセント関数を指定します。基底と結合アクセント記号で構成されます<br/>            例: 𝑎́ |
| [`MathAccentFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathaccentfactory/) | 数式アクセントを作成できます |
| [`MathArray`](/slides/python-net/ja/aspose.slides.mathtext/matharray/) | 方程式や任意の数式オブジェクトの垂直配列を指定します |
| [`MathArrayFactory`](/slides/python-net/ja/aspose.slides.mathtext/matharrayfactory/) | 数式配列を作成できます |
| [`MathBar`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/) | バー関数を指定します。基底引数と上バーまたは下バーで構成されます |
| [`MathBarFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathbarfactory/) | 数式バーを作成できます |
| [`MathBlock`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/) | MathParagraph 内に含まれ、独自の行で開始する数式テキストのインスタンスを指定します。<br/>            方程式、式、方程式や式の配列、数式全体など、すべての数式領域は math block で表されます。 |
| [`MathBlockFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathblockfactory/) | math block を作成できます |
| [`MathBorderBox`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/) | IMathElement の周囲に長方形またはその他の枠線を描画します。 |
| [`MathBorderBoxFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathborderboxfactory/) | math border box を作成できます |
| [`MathBox`](/slides/python-net/ja/aspose.slides.mathtext/mathbox/) | 数式要素の論理的なボックス化（パッケージ化）を指定します。<br/>            たとえば、ボックス化されたオブジェクトは配置点の有無にかかわらず演算子エミュレータとして機能したり、改行点として使用されたり、内部で改行を許可しないようにグループ化されたりします。<br/>            例として、"==" 演算子は改行を防ぐためにボックス化すべきです。 |
| [`MathBoxFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathboxfactory/) | math box を作成できます |
| [`MathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/) | 区切り文字オブジェクトを指定します。開き文字と閉じ文字（括弧、波括弧、角括弧、縦棒など）で構成され、内部に1つ以上の数式要素が指定文字で区切られます。<br/>            例: (𝑥2); [𝑥2\|𝑦2] |
| [`MathDelimiterFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiterfactory/) | math delimiter を作成できます |
| [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase/) | IMathElement の基本クラスで、すべての派生クラスで共通のメソッド実装を提供します。<br/>            内部使用のみ。派生クラスは IMathElement 必須です。 |
| [`MathFraction`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/) | 分数オブジェクトを指定します。分子と分母が分数バーで区切られます。分数バーは水平または斜めにでき、分数のプロパティに依存します。分数オブジェクトは、バーなしで要素を上下に配置するスタック関数の表現にも使用されます。 |
| [`MathFractionFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathfractionfactory/) | math fraction を作成できます |
| [`MathFunction`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/) | 引数の関数を指定します。 |
| [`MathFunctionFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathfunctionfactory/) | math function を作成できます |
| [`MathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/) | 式の上下に配置されるグルーピング記号を指定します。通常、要素間の関係を強調するために使用されます。 |
| [`MathGroupingCharacterFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacterfactory/) | math grouping character を作成できます |
| [`MathLeftSubSuperscriptElement`](/slides/python-net/ja/aspose.slides.mathtext/mathleftsubsuperscriptelement/) | 基底と、基底の左側に配置される下付きと上付きからなる Sub-Superscript オブジェクトを指定します。 |
| [`MathLimit`](/slides/python-net/ja/aspose.slides.mathtext/mathlimit/) | ベースライン上のテキストと、その直上または直下に配置される縮小テキストからなる Limit オブジェクトを指定します。 |
| [`MathLimitFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathlimitfactory/) | IMathLimit を作成できます |
| [`MathMatrix`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/) | 子要素が1つ以上の行と列に配置された Matrix オブジェクトを指定します。<br/>            行列には組み込みの区切り文字がないことに注意してください。<br/>            行列を括弧で囲むには delimiter オブジェクト (IMathDelimiter) を使用します。<br/>            Null 引数を使用して行列内にギャップを作成できます。 |
| [`MathMatrixFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrixfactory/) | math matrix を作成できます |
| [`MathNaryOperator`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/) | 総和や積分などの N 項演算子オブジェクトを指定します。<br/>            演算子、基底（またはオペランド）、およびオプションの上限と下限で構成されます。<br/>            N 項演算子の例: 総和、和集合、交差、積分 |
| [`MathNaryOperatorFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperatorfactory/) | IMathNaryOperator を作成できます |
| [`MathParagraph`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/) | 数学ブロック (IMathBlock) を格納するコンテナである数式段落 |
| [`MathParagraphFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraphfactory/) | math paragraph を作成できます |
| [`MathPhantom`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/) | 子要素のレイアウトに影響を与える phantom 数式オブジェクト (<m:phant>) を表しますが、必ずしも表示されません。phantom は基底式を非表示にしつつ、幅・高さ・深さを保持して数式の整列やスペース確保に利用できます。<br/>            表示や幾何特性は Show、ZeroWid、ZeroAsc、ZeroDesc、Transp などのプロパティで制御されます。 |
| [`MathPortion`](/slides/python-net/ja/aspose.slides.mathtext/mathportion/) | 内部に数式コンテキストを持つ部分を表します。 |
| [`MathRadical`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/) | 基底とオプションの指数からなる根号関数を指定します。<br/>            例: √𝑥 |
| [`MathRadicalFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathradicalfactory/) | math radical を作成できます |
| [`MathRightSubSuperscriptElement`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/) | 基底と、基底の右側に配置される下付きと上付きからなる Sub-Superscript オブジェクトを指定します。 |
| [`MathRightSubSuperscriptElementFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/) | IMathRightSubSuperscriptElementFactory を作成できます |
| [`MathSubscriptElement`](/slides/python-net/ja/aspose.slides.mathtext/mathsubscriptelement/) | 基底と、右下に配置される縮小サイズの下付きからなる subscript オブジェクトを指定します。 |
| [`MathSubscriptElementFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathsubscriptelementfactory/) | IMathSubscriptElement を作成できます |
| [`MathSuperscriptElement`](/slides/python-net/ja/aspose.slides.mathtext/mathsuperscriptelement/) | 基底と、右上に配置される縮小サイズの上付きからなる superscript オブジェクトを指定します。 |
| [`MathSuperscriptElementFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathsuperscriptelementfactory/) | IMathSuperscriptElement を作成できます |
| [`MathematicalText`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/) | 数式テキスト |
| [`MathematicalTextFactory`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltextfactory/) | MathematicalText 要素を作成できます |

## 列挙型

| 列挙型 | 説明 |
| :- | :- |
| [`MathDelimiterShape`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimitershape/) | オペランドの内容に対する区切り文字の位置とサイズ |
| [`MathFractionTypes`](/slides/python-net/ja/aspose.slides.mathtext/mathfractiontypes/) | 分数の種類 |
| [`MathFunctionsOfOneArgument`](/slides/python-net/ja/aspose.slides.mathtext/mathfunctionsofoneargument/) | 1 引数の共通数学関数 |
| [`MathFunctionsOfTwoArguments`](/slides/python-net/ja/aspose.slides.mathtext/mathfunctionsoftwoarguments/) | 2 引数の共通数学関数 |
| [`MathHorizontalAlignment`](/slides/python-net/ja/aspose.slides.mathtext/mathhorizontalalignment/) | 水平方向の配置 |
| [`MathIntegralTypes`](/slides/python-net/ja/aspose.slides.mathtext/mathintegraltypes/) | 積分の種類 |
| [`MathJustification`](/slides/python-net/ja/aspose.slides.mathtext/mathjustification/) | 数式段落（同一段落内の隣接する数式テキストの系列）の配置を指定します。 |
| [`MathLimitLocations`](/slides/python-net/ja/aspose.slides.mathtext/mathlimitlocations/) | n 項演算子における極限（下付き/上付き）の位置。 |
| [`MathNaryOperatorTypes`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperatortypes/) | N 項演算子 IMathNaryOperator のタイプ（積分を除く）<br/>            積分については [`MathIntegralTypes`](/slides/python-net/ja/aspose.slides.mathtext/mathintegraltypes) |
| [`MathRowSpacingRule`](/slides/python-net/ja/aspose.slides.mathtext/mathrowspacingrule/) | 行列または配列の列間の垂直間隔のタイプ |
| [`MathSpacingRules`](/slides/python-net/ja/aspose.slides.mathtext/mathspacingrules/) | 行列の列間の隙間（水平間隔）のタイプ |
| [`MathTopBotPositions`](/slides/python-net/ja/aspose.slides.mathtext/mathtopbotpositions/) | 上/下位置の列挙 |
| [`MathVerticalAlignment`](/slides/python-net/ja/aspose.slides.mathtext/mathverticalalignment/) | 垂直方向の配置 |