---
title: Slide class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/slide/
---
## Slide クラス

プレゼンテーション内のスライドを表します。

**継承:**[`Slide`](/slides/python-net/ja/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)

The Slide type exposes the following members:

## プロパティ

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/ja/aspose.slides/slide/shapes/) | スライドのシェイプを返します。<br/>            読み取り専用 [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/ja/aspose.slides/slide/controls/) | スライド上のActiveXコントロールのコレクションを返します。<br/>            読み取り専用 [`IControlCollection`](/slides/python-net/ja/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/ja/aspose.slides/slide/name/) | スライドの名前を取得または設定します。<br/>            読み書き **str**。 |
| [`slide_id`](/slides/python-net/ja/aspose.slides/slide/slide_id/) | スライドのIDを返します。<br/>            読み取り専用 **int**。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/slide/custom_data/) | スライドのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/ja/aspose.slides/slide/timeline/) | アニメーションタイムラインオブジェクトを返します。<br/>            読み取り専用 [`IAnimationTimeLine`](/slides/python-net/ja/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/ja/aspose.slides/slide/slide_show_transition/) | Transitionオブジェクトを返します。このオブジェクトは、指定されたスライドがスライドショー中にどのように進行するかに関する情報を含みます。<br/>            読み取り専用 [`ISlideShowTransition`](/slides/python-net/ja/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/ja/aspose.slides/slide/background/) | スライドの背景を返します。<br/>            読み取り専用 [`IBackground`](/slides/python-net/ja/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/slide/hyperlink_queries/) | 含まれるハイパーリンクへの簡単なアクセスを提供します。<br/>            読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/ja/aspose.slides/slide/show_master_shapes/) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。<br/>            読み書き **bool**。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/slide/presentation/) | IPresentationインターフェイスを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`header_footer_manager`](/slides/python-net/ja/aspose.slides/slide/header_footer_manager/) | スライドのHeaderFooterマネージャーを返します。<br/>            読み取り専用 [`ISlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/islideheaderfootermanager)。 |
| [`theme_manager`](/slides/python-net/ja/aspose.slides/slide/theme_manager/) | 上書きテーママネージャーを返します。<br/>            読み取り専用 [`IOverrideThemeManager`](/slides/python-net/ja/aspose.slides.theme/ioverridethememanager)。 |
| [`slide_number`](/slides/python-net/ja/aspose.slides/slide/slide_number/) | スライド番号を返します。<br/>            [`Presentation.slides`](/slides/python-net/ja/aspose.slides/presentation/slides) コレクション内のスライドのインデックスは常に SlideNumber - Presentation.FirstSlideNumber と等しくなります。<br/>            読み書き **int**。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/slide/hidden/) | 指定されたスライドがスライドショー中に非表示かどうかを決定します。<br/>            読み書き **bool**。 |
| [`layout_slide`](/slides/python-net/ja/aspose.slides/slide/layout_slide/) | 現在のスライドのレイアウトスライドを取得または設定します。<br/>            読み書き [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)。 |
| [`notes_slide_manager`](/slides/python-net/ja/aspose.slides/slide/notes_slide_manager/) | ノートスライドへのアクセス、追加、削除を可能にします。<br/>            読み取り専用 [`INotesSlideManager`](/slides/python-net/ja/aspose.slides/inotesslidemanager)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/slide/slide/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/slide/join_portions_with_same_formatting/#) | すべての許容シェイプ内のすべての段落において、同じ書式設定のランを結合します。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ja/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | すべての許容シェイプ内のすべての段落において、同じ書式設定のランを結合します。 |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/slide/get_image/#float-float) | カスタムスケーリングを使用したサムネイル画像オブジェクトを返します。 |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/slide/get_image/#) | 実際のサイズの20%のサムネイル画像オブジェクトを返します。 |
| [`get_image(self, image_size)`](/slides/python-net/ja/aspose.slides/slide/get_image/#asposepydrawingsize) | 指定サイズのサムネイル画像オブジェクトを返します。 |
| [`get_image(self, options)`](/slides/python-net/ja/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | 指定されたパラメータでサムネイルTIFF画像オブジェクトを返します。 |
| [`get_image(self, options)`](/slides/python-net/ja/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | サムネイル画像オブジェクトを返します。 |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | カスタムスケーリングを使用したサムネイル画像オブジェクトを返します。 |
| [`get_image(self, options, image_size)`](/slides/python-net/ja/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | 指定サイズのサムネイル画像オブジェクトを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/slide/write_as_svg/#iorawiobase) | スライドのコンテンツをSVGファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | スライドのコンテンツをSVGファイルとして保存します。 |
| [`equals(self, slide)`](/slides/python-net/ja/aspose.slides/slide/equals/#ibaseslide) | 2つのIBaseSlideインスタンスが等しいかどうかを判定します。<br/>            返される値はスライドの構造と静的コンテンツに基づいて計算されます。<br/>            すべてのシェイプ、スタイル、テキスト、アニメーション、およびその他の設定等が等しい場合、2つのスライドは等しいとみなされます。比較では、SlideIdのような一意の識別子や、日付プレースホルダーの現在の日付値などの動的コンテンツは考慮されません。 |
| [`create_theme_effective(self)`](/slides/python-net/ja/aspose.slides/slide/create_theme_effective/#) | このスライドの有効なテーマを返します。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ja/aspose.slides/slide/find_shape_by_alt_text/#str) | 指定された代替テキストを持つシェイプの最初の出現を検索します。 |
| [`write_as_emf(self, stream)`](/slides/python-net/ja/aspose.slides/slide/write_as_emf/#iorawiobase) | スライドのコンテンツをEMFファイルとして保存します。 |
| [`remove(self)`](/slides/python-net/ja/aspose.slides/slide/remove/#) | プレゼンテーションからスライドを削除します。 |
| [`reset(self)`](/slides/python-net/ja/aspose.slides/slide/reset/#) | LayoutSlide上にプロトタイプを持つすべてのシェイプの位置、サイズ、書式設定をリセットします。 |
| [`get_slide_comments(self, author)`](/slides/python-net/ja/aspose.slides/slide/get_slide_comments/#icommentauthor) | 特定の作者によって追加されたすべてのスライドコメントを返します。 |

### 参照
* クラス [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)
* クラス [`Slide`](/slides/python-net/ja/aspose.slides/slide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)