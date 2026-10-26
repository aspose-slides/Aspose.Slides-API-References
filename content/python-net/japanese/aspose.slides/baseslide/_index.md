---
title: BaseSlide class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/baseslide/
---
## BaseSlide クラス

すべてのスライドタイプに共通するデータを表します。

BaseSlide 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`shapes`](/slides/python-net/ja/aspose.slides/baseslide/shapes/) | スライドのシェイプを返します。<br/>            読み取り専用 [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/ja/aspose.slides/baseslide/controls/) | スライド上の ActiveX コントロールのコレクションを返します。<br/>            読み取り専用 [`IControlCollection`](/slides/python-net/ja/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/ja/aspose.slides/baseslide/name/) | スライドの名前を取得または設定します。<br/>            読み書き可能 **str**。 |
| [`slide_id`](/slides/python-net/ja/aspose.slides/baseslide/slide_id/) | スライドの ID を返します。<br/>            読み取り専用 **int**。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/baseslide/custom_data/) | スライドのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/ja/aspose.slides/baseslide/timeline/) | アニメーションのタイムラインオブジェクトを返します。<br/>            読み取り専用 [`IAnimationTimeLine`](/slides/python-net/ja/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/ja/aspose.slides/baseslide/slide_show_transition/) | Transition オブジェクトを返します。<br/>            これは、指定されたスライドがスライドショー中にどのように進行するかに関する情報を含みます。<br/>            読み取り専用 [`ISlideShowTransition`](/slides/python-net/ja/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/ja/aspose.slides/baseslide/background/) | スライドの背景を返します。<br/>            読み取り専用 [`IBackground`](/slides/python-net/ja/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/baseslide/hyperlink_queries/) | 含まれるハイパーリンクへの簡単なアクセスを提供します。<br/>            読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/ja/aspose.slides/baseslide/show_master_shapes/) | マスタースライド上のシェイプをスライド上に表示するかどうかを指定します。<br/>            マスタースライド自体ではこのプロパティは常に `false` を返します。<br/>            読み書き可能 **bool**。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/baseslide/presentation/) | IPresentation インターフェイスを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/baseslide/slide/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/baseslide/join_portions_with_same_formatting/#) | すべての許容可能なシェイプのすべての段落で、同じ書式のランを結合します。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ja/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | すべての許容可能なシェイプのすべての段落で、同じ書式のランを結合します。 |
| [`equals(self, slide)`](/slides/python-net/ja/aspose.slides/baseslide/equals/#ibaseslide) | 2 つの IBaseSlide インスタンスが等しいかどうかを判定します。<br/>            返される値はスライドの構造と静的コンテンツに基づいて計算されます。<br/>            すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定等が等しい場合、スライドは等しいとみなされます。比較では、一意の識別子値（例: SlideId）や動的コンテンツ（例: 日付プレースホルダーの現在の日付値）は考慮されません。 |
| [`create_theme_effective(self)`](/slides/python-net/ja/aspose.slides/baseslide/create_theme_effective/#) | このスライドの有効なテーマを返します。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ja/aspose.slides/baseslide/find_shape_by_alt_text/#str) | 指定された代替テキストを持つシェイプの最初の出現を検索します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)