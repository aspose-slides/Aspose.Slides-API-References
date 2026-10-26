---
title: IBaseSlide class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ibaseslide/
---
## IBaseSlide class

すべてのスライドタイプの共通データを表します。

IBaseSlide 型は次のメンバーを公開します：

## プロパティ

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/ja/aspose.slides/ibaseslide/shapes/) | スライドのシェイプを返します。<br/>            読み取り専用 [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/ja/aspose.slides/ibaseslide/controls/) | スライド上の ActiveX コントロールのコレクションを返します。<br/>            読み取り専用 [`IControlCollection`](/slides/python-net/ja/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/ja/aspose.slides/ibaseslide/name/) | スライドの名前を取得または設定します。<br/>            読み書き **str**。 |
| [`slide_id`](/slides/python-net/ja/aspose.slides/ibaseslide/slide_id/) | スライドの ID を返します。<br/>            読み取り専用 **int**。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/ibaseslide/custom_data/) | スライドのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/ja/aspose.slides/ibaseslide/timeline/) | アニメーションタイムラインオブジェクトを返します。<br/>            読み取り専用 [`IAnimationTimeLine`](/slides/python-net/ja/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/ja/aspose.slides/ibaseslide/slide_show_transition/) | TransitionEx オブジェクトを返します。このオブジェクトは、<br/>            スライドショー中に指定されたスライドがどのように進行するかに関する情報を含みます。<br/>            読み取り専用 [`ISlideShowTransition`](/slides/python-net/ja/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/ja/aspose.slides/ibaseslide/background/) | スライドの背景を返します。<br/>            読み取り専用 [`IBackground`](/slides/python-net/ja/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/ibaseslide/hyperlink_queries/) | 含まれるハイパーリンクへの簡単なアクセスを提供します。<br/>            読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/ja/aspose.slides/ibaseslide/show_master_shapes/) | マスタースライド上のシェイプをスライド上に表示するかどうかを指定します。<br/>            マスタースライド自体ではこのプロパティは常に `false` を返します。<br/>            読み書き **bool**。 |
| [`slide`](/slides/python-net/ja/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/ibaseslide/presentation/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ja/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | 指定された代替テキストを持つシェイプの最初の出現を検索します。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | すべての許容可能なシェイプ内のすべての段落で、同じ書式のランを結合します。 |
| [`equals(self, slide)`](/slides/python-net/ja/aspose.slides/ibaseslide/equals/#ibaseslide) | 2 つの IBaseSlide インスタンスが等しいかどうかを判定します。<br/>            返される値はスライドの構造と静的コンテンツに基づいて計算されます。<br/>            すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定などが等しい場合、スライドは等しいとみなされます。比較は一意の識別子の値（例: SlideId）や動的コンテンツ（例: 日付プレースホルダーの現在の日付値）を考慮しません。 |
| [`create_theme_effective(self)`](/slides/python-net/ja/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)