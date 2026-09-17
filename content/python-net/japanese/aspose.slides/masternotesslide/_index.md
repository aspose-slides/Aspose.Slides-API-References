---
title: MasterNotesSlide class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masternotesslide/
---
## MasterNotesSlide クラス

ノート用のマスタースライドを表します。

**継承:**[`MasterNotesSlide`](/slides/python-net/ja/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)

MasterNotesSlide 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`shapes`](/slides/python-net/ja/aspose.slides/masternotesslide/shapes/) | スライドのシェイプを返します。<br/>            読み取り専用 [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/ja/aspose.slides/masternotesslide/controls/) | スライド上の ActiveX コントロールのコレクションを返します。<br/>            読み取り専用 [`IControlCollection`](/slides/python-net/ja/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/ja/aspose.slides/masternotesslide/name/) | スライドの名前を取得または設定します。<br/>            読み書き **str**。 |
| [`slide_id`](/slides/python-net/ja/aspose.slides/masternotesslide/slide_id/) | スライドの ID を返します。<br/>            読み取り専用 **int**。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/masternotesslide/custom_data/) | スライドのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/ja/aspose.slides/masternotesslide/timeline/) | アニメーションタイムラインオブジェクトを返します。<br/>            読み取り専用 [`IAnimationTimeLine`](/slides/python-net/ja/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/ja/aspose.slides/masternotesslide/slide_show_transition/) | 指定されたスライドがスライドショー中にどのように進行するかに関する情報を含む Transition オブジェクトを返します。<br/>            読み取り専用 [`ISlideShowTransition`](/slides/python-net/ja/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/ja/aspose.slides/masternotesslide/background/) | スライドの背景を返します。<br/>            読み取り専用 [`IBackground`](/slides/python-net/ja/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/masternotesslide/hyperlink_queries/) | 含まれるハイパーリンクへの簡単なアクセスを提供します。<br/>            読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/ja/aspose.slides/masternotesslide/show_master_shapes/) | マスタースライド上のシェイプがスライドに表示されるかどうかを指定します。<br/>            マスタースライド自体ではこのプロパティは常に `false` を返します。<br/>            読み書き **bool**。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/masternotesslide/presentation/) | IPresentation インターフェイスを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`header_footer_manager`](/slides/python-net/ja/aspose.slides/masternotesslide/header_footer_manager/) | マスターノートスライドの HeaderFooter マネージャーを返します。<br/>            読み取り専用 [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/imasterhandoutslideheaderfootermanager)。 |
| [`theme_manager`](/slides/python-net/ja/aspose.slides/masternotesslide/theme_manager/) | テーママネージャーを返します。<br/>            読み取り専用 [`IMasterThemeManager`](/slides/python-net/ja/aspose.slides.theme/imasterthememanager)。 |
| [`notes_style`](/slides/python-net/ja/aspose.slides/masternotesslide/notes_style/) | ノートテキストのスタイルを返します。<br/>            読み取り専用 [`ITextStyle`](/slides/python-net/ja/aspose.slides/itextstyle)。 |
| [`drawing_guides`](/slides/python-net/ja/aspose.slides/masternotesslide/drawing_guides/) | マスターノートスライドの描画ガイドのコレクションを返します。<br/>            読み取り専用 [`IDrawingGuidesCollection`](/slides/python-net/ja/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ja/aspose.slides/masternotesslide/slide/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | すべての許容可能なシェイプのすべての段落で、同じ書式のランを結合します。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ja/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | すべての許容可能なシェイプのすべての段落で、同じ書式のランを結合します。 |
| [`equals(self, slide)`](/slides/python-net/ja/aspose.slides/masternotesslide/equals/#ibaseslide) | 二つの IBaseSlide インスタンスが等しいかどうかを判定します。<br/>            戻り値はスライドの構造と静的コンテンツに基づいて計算されます。<br/>            すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定が等しい場合、スライドは等しいとみなされます。比較ではユニークな識別子の値（例：SlideId）や動的コンテンツ（例：日付プレースホルダーの現在の日付値）は考慮されません。 |
| [`create_theme_effective(self)`](/slides/python-net/ja/aspose.slides/masternotesslide/create_theme_effective/#) | このスライドの有効なテーマを返します。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ja/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | 指定された代替テキストを持つシェイプの最初の出現を検索します。 |

### 参照
* クラス [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)
* クラス [`MasterNotesSlide`](/slides/python-net/ja/aspose.slides/masternotesslide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)