---
title: "Aspose::Slides::MathText"
second_title: "Aspose.Slides for C++ API リファレンス"
description: 
type: docs
weight: 157
url: /ja/aspose.slides.mathtext/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [BaseScript](./basescript/) | 数式スクリプト |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) と [Control](../aspose.slides/control/) 文字プロパティ |
| [IMathAccent](./imathaccent/) | アクセント関数を指定します。ベースと結合ダイアクリティカルマークで構成されます。例: \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | 数式アクセントを作成できます |
| [IMathArray](./imatharray/) | 方程式または任意の数学オブジェクトの垂直配列を指定します |
| [IMathArrayFactory](./imatharrayfactory/) | 数式配列を作成できます |
| [IMathBar](./imathbar/) | バー関数を指定します。ベース引数と上バーまたは下バーで構成されます |
| [IMathBarFactory](./imathbarfactory/) | 数式バーを作成できます |
| [IMathBlock](./imathblock/) | [MathParagraph](./mathparagraph/) 内に含まれ、独立した行で開始する数学テキストのインスタンスを指定します。方程式、式、方程式や式の配列、数式など、すべての数学領域は math block で表されます |
| [IMathBlockCollection](./imathblockcollection/) | math block のコレクション ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | math block を作成できます |
| [IMathBorderBox](./imathborderbox/) | [IMathElement](./imathelement/) の周囲に矩形またはその他の枠線を描画します |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | math border box を作成できます |
| [IMathBox](./imathbox/) | 数学要素の論理的ボックス化（パッケージ化）を指定します。たとえば、ボックス化されたオブジェクトは、配置ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして使用されたり、内部で改行を許可しないようにグループ化したりできます。例として、"==“ 演算子は改行を防ぐためにボックス化すべきです |
| [IMathBoxFactory](./imathboxfactory/) | 数式ボックスを作成できます |
| [IMathDelimiter](./imathdelimiter/) | 区切りオブジェクトを指定します。開始文字と終了文字（括弧、波かっこ、角括弧、縦棒など）で構成され、内部に1つ以上の数学要素が指定文字で区切られます。例: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | 数式デリミタを作成できます |
| [IMathElement](./imathelement/) | 分数、数学テキスト、関数、複数要素の式など、任意の数学要素の基本インターフェイス |
| [IMathElementCollection](./imathelementcollection/) | 数学要素 (MathElement) のコレクションを表します |
| [IMathematicalText](./imathematicaltext/) | 数学テキスト |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | [MathematicalText](./mathematicaltext/) 要素を作成できます |
| [IMathFraction](./imathfraction/) | 分子と分母が分数バーで区切られた分数オブジェクトを指定します。分数バーは水平または斜めにでき、分数プロパティによって決まります。このオブジェクトは、バーなしで要素を上下に配置するスタック関数を表すためにも使用されます |
| [IMathFractionFactory](./imathfractionfactory/) | 数式分数を作成できます |
| [IMathFunction](./imathfunction/) | 引数の関数を指定します |
| [IMathFunctionFactory](./imathfunctionfactory/) | 数式関数を作成できます |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | 式の上または下に配置されるグルーピング記号を指定します。通常、要素間の関係を強調するために使用されます |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | 数式グルーピング文字を作成できます |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | 基底の左側に配置された下付文字と上付文字からなるサブスクリプト・上付文字オブジェクトを指定します |
| [IMathLimit](./imathlimit/) | ベースライン上のテキストと、その直上または直下に配置された縮小サイズのテキストで構成されるリミットオブジェクトを指定します |
| [IMathLimitFactory](./imathlimitfactory/) | [IMathLimit](./imathlimit/) を作成できます |
| [IMathMatrix](./imathmatrix/) | 子要素が1つ以上の行と列に配置されたマトリックスオブジェクトを指定します。マトリックスには組み込みの区切り文字がないことに注意してください。マトリックスを括弧で囲むには、区切りオブジェクト ([IMathDelimiter](./imathdelimiter/)) を使用する必要があります。null 引数を使用してマトリックス内に空白を作成できます |
| [IMathMatrixFactory](./imathmatrixfactory/) | 数式マトリックスを作成できます |
| [IMathNaryOperator](./imathnaryoperator/) | N項演算子（例: 総和や積分）の数学オブジェクトを指定します。演算子、基底（またはオペランド）、および任意の上限と下限で構成されます。N項演算子の例: 総和、和集合、交差、積分 |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | [IMathNaryOperator](./imathnaryoperator/) を作成できます |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | [IMathNaryOperator](./imathnaryoperator/) のプロパティを指定します |
| [IMathParagraph](./imathparagraph/) | 数学ブロック ([IMathBlock](./imathblock/)) のコンテナである数学段落 |
| [IMathParagraphFactory](./imathparagraphfactory/) | 数学段落を作成できます |
| [IMathPhantom](./imathphantom/) | <m:phant> のファントム数学オブジェクトを表します。子要素のレイアウトに影響を与えますが、必ずしも表示されません。ファントムは基底式を非表示にしつつ、幅・高さ・深さを保持して式の位置合わせやスペース確保に使用できます。表示や幾何属性は Show、ZeroWid、ZeroAsc、ZeroDesc、Transp などのプロパティで制御されます |
| [IMathPortion](./imathportion/) | 内部に数学的コンテキストを持つ領域を表します |
| [IMathRadical](./imathradical/) | 根号関数を指定します。基底とオプションの指数で構成されます。根号オブジェクトの例は \\u221A\\uD835\\uDC65 です |
| [IMathRadicalFactory](./imathradicalfactory/) | 数式ルートを作成できます |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | 基底の右側に配置された下付文字と上付文字からなるサブスクリプト・上付文字オブジェクトを指定します |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) を作成できます |
| [IMathSubscriptElement](./imathsubscriptelement/) | 基底と右下に配置された縮小サイズの下付文字からなる下付文字オブジェクトを指定します |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | [IMathSubscriptElement](./imathsubscriptelement/) を作成できます |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | 基底と右上に配置された縮小サイズの上付文字からなる上付文字オブジェクトを指定します |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | [IMathSuperscriptElement](./imathsuperscriptelement/) を作成できます |
| [MathAccent](./mathaccent/) | アクセント関数を指定します。ベースと結合ダイアクリティカルマークで構成されます。例: \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | 数式アクセントを作成できます |
| [MathArray](./matharray/) | 方程式または任意の数学オブジェクトの垂直配列を指定します |
| [MathArrayFactory](./matharrayfactory/) | 数式配列を作成できます |
| [MathBar](./mathbar/) | バー関数を指定します。ベース引数と上バーまたは下バーで構成されます |
| [MathBarFactory](./mathbarfactory/) | 数式バーを作成できます |
| [MathBlock](./mathblock/) | [MathParagraph](./mathparagraph/) 内に含まれ、独立した行で開始する数学テキストのインスタンスを指定します。方程式、式、方程式や式の配列、数式など、すべての数学領域は math block で表されます |
| [MathBlockFactory](./mathblockfactory/) | math block を作成できます |
| [MathBorderBox](./mathborderbox/) | [IMathElement](./imathelement/) の周囲に矩形またはその他の枠線を描画します |
| [MathBorderBoxFactory](./mathborderboxfactory/) | math border box を作成できます |
| [MathBox](./mathbox/) | 数学要素の論理的ボックス化（パッケージ化）を指定します。たとえば、ボックス化されたオブジェクトは、配置ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして使用されたり、内部で改行を許可しないようにグループ化したりできます。例として、"==“ 演算子は改行を防ぐためにボックス化すべきです |
| [MathBoxFactory](./mathboxfactory/) | 数式ボックスを作成できます |
| [MathDelimiter](./mathdelimiter/) | 区切りオブジェクトを指定します。開始文字と終了文字（括弧、波かっこ、角括弧、縦棒など）で構成され、内部に1つ以上の数学要素が指定文字で区切られます。例: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | 数式デリミタを作成できます |
| [MathElementBase](./mathelementbase/) | [IMathElement](./imathelement/) の基本クラスで、すべての派生クラスに共通するいくつかのメソッドの実装を提供します。内部使用のみです。派生クラスは [IMathElement](./imathelement/) である必要があります |
| [MathematicalText](./mathematicaltext/) | 数学テキスト |
| [MathematicalTextFactory](./mathematicaltextfactory/) | [MathematicalText](./mathematicaltext/) 要素を作成できます |
| [MathFraction](./mathfraction/) | 分子と分母が分数バーで区切られた分数オブジェクトを指定します。分数バーは水平または斜めにでき、分数プロパティによって決まります。このオブジェクトは、バーなしで要素を上下に配置するスタック関数を表すためにも使用されます |
| [MathFractionFactory](./mathfractionfactory/) | 数式分数を作成できます |
| [MathFunction](./mathfunction/) | 引数の関数を指定します |
| [MathFunctionFactory](./mathfunctionfactory/) | 数式関数を作成できます |
| [MathGroupingCharacter](./mathgroupingcharacter/) | 式の上または下に配置されるグルーピング記号を指定します。通常、要素間の関係を強調するために使用されます |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | 数式グルーピング文字を作成できます |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | 基底の左側に配置された下付文字と上付文字からなるサブスクリプト・上付文字オブジェクトを指定します |
| [MathLimit](./mathlimit/) | ベースライン上のテキストと、その直上または直下に配置された縮小サイズのテキストで構成されるリミットオブジェクトを指定します |
| [MathLimitFactory](./mathlimitfactory/) | [IMathLimit](./imathlimit/) を作成できます |
| [MathMatrix](./mathmatrix/) | 子要素が1つ以上の行と列に配置されたマトリックスオブジェクトを指定します。マトリックスには組み込みの区切り文字がないことに注意してください。マトリックスを括弧で囲むには、区切りオブジェクト ([IMathDelimiter](./imathdelimiter/)) を使用する必要があります。null 引数を使用してマトリックス内に空白を作成できます |
| [MathMatrixFactory](./mathmatrixfactory/) | 数式マトリックスを作成できます |
| [MathNaryOperator](./mathnaryoperator/) | N項演算子（例: 総和や積分）の数学オブジェクトを指定します。演算子、基底（またはオペランド）、および任意の上限と下限で構成されます。N項演算子の例: 総和、和集合、交差、積分 |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | [IMathNaryOperator](./imathnaryoperator/) を作成できます |
| [MathParagraph](./mathparagraph/) | 数学ブロック ([IMathBlock](./imathblock/)) のコンテナである数学段落 |
| [MathParagraphFactory](./mathparagraphfactory/) | 数学段落を作成できます |
| [MathPhantom](./mathphantom/) | <m:phant> のファントム数学オブジェクトを表します。子要素のレイアウトに影響を与えますが、必ずしも表示されません。ファントムは基底式を非表示にしつつ、幅・高さ・深さを保持して式の位置合わせやスペース確保に使用できます。表示や幾何属性は Show、ZeroWid、ZeroAsc、ZeroDesc、Transp などのプロパティで制御されます |
| [MathPortion](./mathportion/) | 内部に数学的コンテキストを持つ領域を表します |
| [MathRadical](./mathradical/) | 根号関数を指定します。基底とオプションの指数で構成されます。根号オブジェクトの例は \\u221A\\uD835\\uDC65 です |
| [MathRadicalFactory](./mathradicalfactory/) | 数式ルートを作成できます |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | 基底の右側に配置された下付文字と上付文字からなるサブスクリプト・上付文字オブジェクトを指定します |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) を作成できます |
| [MathSubscriptElement](./mathsubscriptelement/) | 基底と右下に配置された縮小サイズの下付文字からなる下付文字オブジェクトを指定します |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | [IMathSubscriptElement](./imathsubscriptelement/) を作成できます |
| [MathSuperscriptElement](./mathsuperscriptelement/) | 基底と右上に配置された縮小サイズの上付文字からなる上付文字オブジェクトを指定します |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | [IMathSuperscriptElement](./imathsuperscriptelement/) を作成できます |

## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | 区切り文字の位置とサイズ（被演算子の内容に対して） |
| [MathFractionTypes](./mathfractiontypes/) | 分数の種類 |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | 1引数の共通数学関数 |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | 2引数の共通数学関数 |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | 水平配置 |
| [MathIntegralTypes](./mathintegraltypes/) | 数学積分の種類 |
| [MathJustification](./mathjustification/) | math paragraph の整列方法を指定します（同一段落内の隣接した数学テキストの系列） |
| [MathLimitLocations](./mathlimitlocations/) | n項演算子におけるリミット（下付文字/上付文字）の位置 |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | n項演算子 [IMathNaryOperator](./imathnaryoperator/) の種類（積分を除く）。積分の場合は [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | マトリックスまたは配列の列間の垂直間隔の種類 |
| [MathSpacingRules](./mathspacingrules/) | マトリックスの列間のギャップ（水平間隔）の種類 |
| [MathTopBotPositions](./mathtopbotpositions/) | 上/下位置の列挙型 |
| [MathVerticalAlignment](./mathverticalalignment/) | 垂直配置 |