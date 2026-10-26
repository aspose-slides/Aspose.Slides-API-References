---
title: Aspose.Slides.MathText
second_title: Aspose.Sildes for .NET API リファレンス
description: Microsoft PowerPoint プレゼンテーションで数式テキストを操作するためのクラスを含みます。
type: docs
weight: 140
url: /ja/aspose.slides.mathtext/
---
Microsoft PowerPoint プレゼンテーションで数式テキストを操作するためのクラスを含みます。

## Classes

| Class | Description |
| --- | --- |
| [BaseScript](./basescript) | Math script |
| [MathAccent](./mathaccent) | ベースと結合アクセント記号からなるアクセント関数を指定します。例: 𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | 数式アクセントを作成できます。 |
| [MathArray](./matharray) | 方程式または任意の数式オブジェクトの垂直配列を指定します。 |
| [MathArrayFactory](./matharrayfactory) | 数式配列を作成できます。 |
| [MathBar](./mathbar) | ベース引数と上バーまたは下バーからなるバー関数を指定します。 |
| [MathBarFactory](./mathbarfactory) | 数式バーを作成できます。 |
| [MathBlock](./mathblock) | MathParagraph 内に含まれ、独自の行で開始する数式テキストのインスタンスを指定します。方程式、式、方程式や式の配列、数式全体など、すべての数式領域は math block で表されます。 |
| [MathBlockFactory](./mathblockfactory) | 数式ブロックを作成できます。 |
| [MathBorderBox](./mathborderbox) | IMathElement の周囲に矩形またはその他の枠線を描画します。 |
| [MathBorderBoxFactory](./mathborderboxfactory) | 数式ボーダーボックスを作成できます。 |
| [MathBox](./mathbox) | 数式要素の論理的なボックス化（パッケージ化）を指定します。例えば、ボックス化されたオブジェクトは整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして使用したり、行内改行を許可しないようにグループ化したりできます。例として、"==" 演算子は行改行を防ぐためにボックス化すべきです。 |
| [MathBoxFactory](./mathboxfactory) | 数式ボックスを作成できます。 |
| [MathDelimiter](./mathdelimiter) | 開きおよび閉じ文字（例えば丸括弧、波括弧、角括弧、縦棒など）からなり、内部に1つ以上の数式要素を指定文字で区切って含む区切りオブジェクトを指定します。例: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | 数式区切り記号を作成できます。 |
| [MathElementBase](./mathelementbase) | IMathElement 用の基底クラスで、すべての派生クラスに共通するいくつかのメソッドの実装を提供します。内部使用のみです。派生クラスは IMathElement でなければなりません。 |
| [MathematicalText](./mathematicaltext) | 数式テキスト |
| [MathematicalTextFactory](./mathematicaltextfactory) | MathematicalText 要素を作成できます。 |
| [MathFraction](./mathfraction) | 分子と分母が分数線で区切られた分数オブジェクトを指定します。分数線は水平または斜めにすることができ、分数のプロパティに依存します。また、分数オブジェクトは分割関数（スタック関数）を表すためにも使用され、これは要素を上に重ねるもので、分数線はありません。 |
| [MathFractionFactory](./mathfractionfactory) | 数式分数を作成できます。 |
| [MathFunction](./mathfunction) | 引数の関数を指定します。 |
| [MathFunctionFactory](./mathfunctionfactory) | 数式関数を作成できます。 |
| [MathGroupingCharacter](./mathgroupingcharacter) | 式の上下に配置され、要素間の関係を強調するためのグルーピング記号を指定します。 |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | 数式グルーピング文字を作成できます。 |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | ベースと、ベースの左側に配置される下付き文字と上付き文字からなる Sub-Superscript オブジェクトを指定します。 |
| [MathLimit](./mathlimit) | ベースライン上のテキストと、その直上または直下に配置された縮小サイズのテキストからなる Limit オブジェクトを指定します。 |
| [MathLimitFactory](./mathlimitfactory) | IMathLimit を作成できます。 |
| [MathMatrix](./mathmatrix) | 子要素が1つ以上の行と列に配置された Matrix オブジェクトを指定します。マトリックスには組み込みの区切り記号がないことに注意してください。マトリックスを括弧で囲むには区切りオブジェクト (IMathDelimiter) を使用する必要があります。null 引数を使用してマトリックス内に空白を作ることができます。 |
| [MathMatrixFactory](./mathmatrixfactory) | 数式マトリックスを作成できます。 |
| [MathNaryOperator](./mathnaryoperator) | 和や積分などの N 変数数式オブジェクトを指定します。演算子、ベース（またはオペランド）、およびオプションの上限と下限から構成されます。N 変数演算子の例: 和、和集合、積集合、積分 |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | IMathNaryOperator を作成できます。 |
| [MathParagraph](./mathparagraph) | 数式ブロック (IMathBlock) のコンテナである数式段落です。 |
| [MathParagraphFactory](./mathparagraphfactory) | 数式段落を作成できます。 |
| [MathPhantom](./mathphantom) | 子要素のレイアウトに影響を与えるが必ずしも表示しない幻影数式オブジェクト (&lt;m:phant&gt;) を表します。幻影は幅や高さ、深さを保持したままベース式を非表示にでき、式の整列やスペース確保に利用できます。表示とジオメトリの動作は Show、ZeroWid、ZeroAsc、ZeroDesc、Transp などのプロパティで制御されます。 |
| [MathPortion](./mathportion) | 内部に数式コンテキストを含む部分を表します。 |
| [MathRadical](./mathradical) | 底とオプションの指数からなる根号関数を指定します。根号オブジェクトの例は √𝑥 です。 |
| [MathRadicalFactory](./mathradicalfactory) | 数式ルートを作成できます。 |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | ベースと、ベースの右側に配置される下付き文字と上付き文字からなる Sub-Superscript オブジェクトを指定します。 |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | IMathRightSubSuperscriptElementFactory を作成できます。 |
| [MathSubscriptElement](./mathsubscriptelement) | ベースと、ベースの右下に配置され、縮小サイズの下付き文字からなる下付きオブジェクトを指定します。 |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | IMathSubscriptElement を作成できます。 |
| [MathSuperscriptElement](./mathsuperscriptelement) | ベースと、ベースの右上に配置され、縮小サイズの上付き文字からなる上付きオブジェクトを指定します。 |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | IMathSuperscriptElement を作成できます。 |

## Interfaces

| Interface | Description |
| --- | --- |
| [IMathAccent](./imathaccent) | ベースと結合アクセント記号からなるアクセント関数を指定します。例: 𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | 数式アクセントを作成できます。 |
| [IMathArray](./imatharray) | 方程式または任意の数式オブジェクトの垂直配列を指定します。 |
| [IMathArrayFactory](./imatharrayfactory) | 数式配列を作成できます。 |
| [IMathBar](./imathbar) | ベース引数と上バーまたは下バーからなるバー関数を指定します。 |
| [IMathBarFactory](./imathbarfactory) | 数式バーを作成できます。 |
| [IMathBlock](./imathblock) | MathParagraph 内に含まれ、独自の行で開始する数式テキストのインスタンスを指定します。方程式、式、方程式や式の配列、数式全体など、すべての数式領域は math block で表されます。 |
| [IMathBlockCollection](./imathblockcollection) | math ブロック (IMathBlock) のコレクション |
| [IMathBlockFactory](./imathblockfactory) | 数式ブロックを作成できます。 |
| [IMathBorderBox](./imathborderbox) | IMathElement の周囲に矩形またはその他の枠線を描画します。 |
| [IMathBorderBoxFactory](./imathborderboxfactory) | 数式ボーダーボックスを作成できます。 |
| [IMathBox](./imathbox) | 数式要素の論理的なボックス化（パッケージ化）を指定します。例えば、ボックス化されたオブジェクトは整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして使用したり、行内改行を許可しないようにグループ化したりできます。例として、"==" 演算子は行改行を防ぐためにボックス化すべきです。 |
| [IMathBoxFactory](./imathboxfactory) | 数式ボックスを作成できます。 |
| [IMathDelimiter](./imathdelimiter) | 開きおよび閉じ文字（例えば丸括弧、波括弧、角括弧、縦棒など）からなり、内部に1つ以上の数式要素を指定文字で区切って含む区切りオブジェクトを指定します。例: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | 数式区切り記号を作成できます。 |
| [IMathElement](./imathelement) | 分数、数式テキスト、関数、複数要素の式など、任意の数式要素の基底インターフェイスです。 |
| [IMathElementCollection](./imathelementcollection) | 数式要素 (MathElement) のコレクションを表します。 |
| [IMathematicalText](./imathematicaltext) | 数式テキスト |
| [IMathematicalTextFactory](./imathematicaltextfactory) | MathematicalText 要素を作成できます。 |
| [IMathFraction](./imathfraction) | 分子と分母が分数線で区切られた分数オブジェクトを指定します。分数線は水平または斜めにすることができ、分数のプロパティに依存します。また、分数オブジェクトは分割関数（スタック関数）を表すためにも使用され、これは要素を上に重ねるもので、分数線はありません。 |
| [IMathFractionFactory](./imathfractionfactory) | 数式分数を作成できます。 |
| [IMathFunction](./imathfunction) | 引数の関数を指定します。 |
| [IMathFunctionFactory](./imathfunctionfactory) | 数式関数を作成できます。 |
| [IMathGroupingCharacter](./imathgroupingcharacter) | 式の上下に配置され、要素間の関係を強調するためのグルーピング記号を指定します。 |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | 数式グルーピング文字を作成できます。 |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | ベースと、ベースの左側に配置される下付き文字と上付き文字からなる Sub-Superscript オブジェクトを指定します。 |
| [IMathLimit](./imathlimit) | ベースライン上のテキストと、その直上または直下に配置された縮小サイズのテキストからなる Limit オブジェクトを指定します。 |
| [IMathLimitFactory](./imathlimitfactory) | IMathLimit を作成できます。 |
| [IMathMatrix](./imathmatrix) | 子要素が1つ以上の行と列に配置された Matrix オブジェクトを指定します。マトリックスには組み込みの区切り記号がないことに注意してください。マトリックスを括弧で囲むには区切りオブジェクト (IMathDelimiter) を使用する必要があります。null 引数を使用してマトリックス内に空白を作ることができます。 |
| [IMathMatrixFactory](./imathmatrixfactory) | 数式マトリックスを作成できます。 |
| [IMathNaryOperator](./imathnaryoperator) | 和や積分などの N 変数数式オブジェクトを指定します。演算子、ベース（またはオペランド）、およびオプションの上限と下限から構成されます。N 変数演算子の例: 和、和集合、積集合、積分 |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | IMathNaryOperator を作成できます。 |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | IMathNaryOperator のプロパティを指定します。 |
| [IMathParagraph](./imathparagraph) | 数式ブロック (IMathBlock) のコンテナである数式段落です。 |
| [IMathParagraphFactory](./imathparagraphfactory) | 数式段落を作成できます。 |
| [IMathPhantom](./imathphantom) | 子要素のレイアウトに影響を与えるが必ずしも表示しない幻影数式オブジェクト (&lt;m:phant&gt;) を表します。幻影は幅や高さ、深さを保持したままベース式を非表示にでき、式の整列やスペース確保に利用できます。表示とジオメトリの動作は Show、ZeroWid、ZeroAsc、ZeroDesc、Transp などのプロパティで制御されます。 |
| [IMathPortion](./imathportion) | 内部に数式コンテキストを含む部分を表します。 |
| [IMathRadical](./imathradical) | 底とオプションの指数からなる根号関数を指定します。根号オブジェクトの例は √𝑥 です。 |
| [IMathRadicalFactory](./imathradicalfactory) | 数式ルートを作成できます。 |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | ベースと、ベースの右側に配置される下付き文字と上付き文字からなる Sub-Superscript オブジェクトを指定します。 |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | IMathRightSubSuperscriptElementFactory を作成できます。 |
| [IMathSubscriptElement](./imathsubscriptelement) | ベースと、ベースの右下に配置され、縮小サイズの下付き文字からなる下付きオブジェクトを指定します。 |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | IMathSubscriptElement を作成できます。 |
| [IMathSuperscriptElement](./imathsuperscriptelement) | ベースと、ベースの右上に配置され、縮小サイズの上付き文字からなる上付きオブジェクトを指定します。 |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | IMathSuperscriptElement を作成できます。 |

## Enumeration

| Enumeration | Description |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | オペランドの内容に対する区切り記号の位置とサイズ |
| [MathFractionTypes](./mathfractiontypes) | 分数タイプ |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | 1 引数の一般的な数学関数 |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | 2 引数の一般的な数学関数 |
| [MathHorizontalAlignment](./mathhorizontalalignment) | 水平配置 |
| [MathIntegralTypes](./mathintegraltypes) | 数学積分タイプ |
| [MathJustification](./mathjustification) | 同一段落内の隣接する数式テキストインスタンスの系列である math paragraph の配置を指定します。 |
| [MathLimitLocations](./mathlimitlocations) | N 変数演算子におけるリミット（下付/上付）の位置 |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | 積分を除く Nary 演算子 IMathNaryOperator のタイプ。積分については [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | 行列または配列の列間の垂直間隔のタイプ |
| [MathSpacingRules](./mathspacingrules) | 行列の列間のギャップ（水平間隔）のタイプ |
| [MathTopBotPositions](./mathtopbotpositions) | 上/下位置の列挙体 |
| [MathVerticalAlignment](./mathverticalalignment) | 垂直配置 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->