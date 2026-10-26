---
title: MasterHandoutSlide class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide クラス

ハンドアウト用のマスタースライドを表します。

**継承:**[`MasterHandoutSlide`](/slides/python-net/ja/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)

MasterHandoutSlide タイプは以下のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/ja/aspose.slides/masterhandoutslide/shapes/) | スライドのシェイプを返します。<br/>            読み取り専用 [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)。 |
| [`controls`](/slides/python-net/ja/aspose.slides/masterhandoutslide/controls/) | スライド上の ActiveX コントロールのコレクションを返します。<br/>            読み取り専用 [`IControlCollection`](/slides/python-net/ja/aspose.slides/icontrolcollection)。 |
| [`name`](/slides/python-net/ja/aspose.slides/masterhandoutslide/name/) | スライドの名前を取得または設定します。<br/>            読み書き **str**。 |
| [`slide_id`](/slides/python-net/ja/aspose.slides/masterhandoutslide/slide_id/) | スライドの ID を返します。<br/>            読み取り専用 **int**。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/masterhandoutslide/custom_data/) | スライドのカスタム データを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`timeline`](/slides/python-net/ja/aspose.slides/masterhandoutslide/timeline/) | アニメーション タイムライン オブジェクトを返します。<br/>            読み取り専用 [`IAnimationTimeLine`](/slides/python-net/ja/aspose.slides/ianimationtimeline)。 |
| [`slide_show_transition`](/slides/python-net/ja/aspose.slides/masterhandoutslide/slide_show_transition/) | スライドショー中に指定スライドが進む方法に関する情報を含む Transition オブジェクトを返します。<br/>            読み取り専用 [`ISlideShowTransition`](/slides/python-net/ja/aspose.slides/islideshowtransition)。 |
| [`background`](/slides/python-net/ja/aspose.slides/masterhandoutslide/background/) | スライドの背景を返します。<br/>            読み取り専用 [`IBackground`](/slides/python-net/ja/aspose.slides/ibackground)。 |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/masterhandoutslide/hyperlink_queries/) | 含まれるハイパーリンクへの簡易アクセスを提供します。<br/>            読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries)。 |
| [`show_master_shapes`](/slides/python-net/ja/aspose.slides/masterhandoutslide/show_master_shapes/) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。<br/>            マスタースライド自体ではこのプロパティは常に `false` を返します。<br/>            読み書き **bool**。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/masterhandoutslide/presentation/) | IPresentation インターフェイスを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`header_footer_manager`](/slides/python-net/ja/aspose.slides/masterhandoutslide/header_footer_manager/) | マスターハンドアウト スライドの HeaderFooter マネージャーを返します。<br/>            読み取り専用 [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/imasterhandoutslideheaderfootermanager)。 |
| [`theme_manager`](/slides/python-net/ja/aspose.slides/masterhandoutslide/theme_manager/) | テーマ マネージャーを返します。<br/>            読み取り専用 [`IMasterThemeManager`](/slides/python-net/ja/aspose.slides.theme/imasterthememanager)。 |
| [`drawing_guides`](/slides/python-net/ja/aspose.slides/masterhandoutslide/drawing_guides/) | マスターハンドアウト スライドの描画ガイド コレクションを返します。<br/>            読み取り専用 [`IDrawingGuidesCollection`](/slides/python-net/ja/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ja/aspose.slides/masterhandoutslide/slide/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | すべての許容シェイプ内のすべての段落で、同じ書式のランを結合します。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ja/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | すべての許容シェイプ内のすべての段落で、同じ書式のランを結合します。 |
| [`equals(self, slide)`](/slides/python-net/ja/aspose.slides/masterhandoutslide/equals/#ibaseslide) | 2 つの IBaseSlide インスタンスが等しいかどうかを判定します。<br/>            返される値はスライドの構造と静的コンテンツに基づいて計算されます。<br/>            すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定等が等しい場合、スライドは等しいとみなされます。比較では SlideId のような一意識別子や、日付プレースホルダーの現在の日付値のような動的コンテンツは考慮されません。 |
| [`create_theme_effective(self)`](/slides/python-net/ja/aspose.slides/masterhandoutslide/create_theme_effective/#) | このスライドの有効なテーマを返します。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ja/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | 指定された代替テキストを持つシェイプの最初の出現を検索します。 |


### 参照
* クラス [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)
* クラス [`MasterHandoutSlide`](/slides/python-net/ja/aspose.slides/masterhandoutslide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)