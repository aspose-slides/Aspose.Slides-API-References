---
title: MasterSlide class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masterslide/
---
## MasterSlide クラス

プレゼンテーション内のマスタースライドを表します。

**継承:**[`MasterSlide`](/slides/python-net/ja/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)

MasterSlide 型は次のメンバーを公開します:

## プロパティ

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/ja/aspose.slides/masterslide/shapes/) | スライドのシェイプを返します。<br/>            読み取り専用 [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ja/aspose.slides/masterslide/controls/) | スライド上の ActiveX コントロールのコレクションを返します。<br/>            読み取り専用 [`IControlCollection`](/slides/python-net/ja/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ja/aspose.slides/masterslide/name/) | マスタースライドの名前を取得または設定します。<br/>            読み書き可能 **str**. |
| [`slide_id`](/slides/python-net/ja/aspose.slides/masterslide/slide_id/) | スライドの ID を返します。<br/>            読み取り専用 **int**. |
| [`custom_data`](/slides/python-net/ja/aspose.slides/masterslide/custom_data/) | スライドのカスタム データを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ja/aspose.slides/masterslide/timeline/) | アニメーション タイムライン オブジェクトを返します。<br/>            読み取り専用 [`IAnimationTimeLine`](/slides/python-net/ja/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ja/aspose.slides/masterslide/slide_show_transition/) | Transition オブジェクトを返します。<br/>            指定されたスライドがスライドショー中にどのように進むかに関する情報を含みます。<br/>            読み取り専用 [`ISlideShowTransition`](/slides/python-net/ja/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ja/aspose.slides/masterslide/background/) | スライドの背景を返します。<br/>            読み取り専用 [`IBackground`](/slides/python-net/ja/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/masterslide/hyperlink_queries/) | 含まれるハイパーリンクへの簡単なアクセスを提供します。<br/>            読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ja/aspose.slides/masterslide/show_master_shapes/) | マスタースライド上のシェイプがスライドに表示されるかどうかを指定します。<br/>            マスタースライド自体に対してこのプロパティは常に `false` を返します。<br/>            読み書き可能 **bool**. |
| [`presentation`](/slides/python-net/ja/aspose.slides/masterslide/presentation/) | IPresentation インターフェイスを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ja/aspose.slides/masterslide/header_footer_manager/) | マスタースライドの HeaderFooter マネージャーを返します。<br/>            読み取り専用 [`IMasterSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/ja/aspose.slides/masterslide/title_style/) | タイトル テキストのスタイルを返します。<br/>            読み取り専用 [`ITextStyle`](/slides/python-net/ja/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/ja/aspose.slides/masterslide/body_style/) | 本文テキストのスタイルを返します。<br/>            読み取り専用 [`ITextStyle`](/slides/python-net/ja/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/ja/aspose.slides/masterslide/other_style/) | その他のテキストのスタイルを返します。<br/>            読み取り専用 [`ITextStyle`](/slides/python-net/ja/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/ja/aspose.slides/masterslide/layout_slides/) | このマスタースライドの子レイアウトスライドのコレクションを返します。<br/>            読み取り専用 [`IMasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/ja/aspose.slides/masterslide/preserve/) | 対応するマスターが、そのマスターに続くすべてのスライドが削除されたときに削除されるかどうかを判断します。<br/>            注: Aspose.Slides は未使用のマスターを自動的に削除しません。未使用のマスターを実際に削除するには **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste** を呼び出します。<br/>            読み書き可能 **bool**. |
| [`has_depending_slides`](/slides/python-net/ja/aspose.slides/masterslide/has_depending_slides/) | このマスタースライドに依存するスライドが少なくとも1つ存在する場合に true を返します。<br/>            読み取り専用 **bool**. |
| [`theme_manager`](/slides/python-net/ja/aspose.slides/masterslide/theme_manager/) | テーマ マネージャーを返します。<br/>            読み取り専用 [`IMasterThemeManager`](/slides/python-net/ja/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/ja/aspose.slides/masterslide/drawing_guides/) | マスタースライド用の描画ガイドのコレクションを返します。<br/>            読み取り専用 [`IDrawingGuidesCollection`](/slides/python-net/ja/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ja/aspose.slides/masterslide/slide/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/masterslide/join_portions_with_same_formatting/#) | すべての許容可能なシェイプ内のすべての段落で、同じ書式のランを結合します。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ja/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | すべての許容可能なシェイプ内のすべての段落で、同じ書式のランを結合します。 |
| [`equals(self, slide)`](/slides/python-net/ja/aspose.slides/masterslide/equals/#ibaseslide) | 2つの IBaseSlide インスタンスが等しいかどうかを判断します。<br/>            戻り値はスライドの構造と静的コンテンツに基づいて計算されます。<br/>            すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定等が等しい場合、スライドは等しいとみなされます。比較では、SlideId のような固有識別子の値や、日付プレースホルダーの現在の日付値のような動的コンテンツは考慮されません。 |
| [`create_theme_effective(self)`](/slides/python-net/ja/aspose.slides/masterslide/create_theme_effective/#) | このスライドの有効なテーマを返します。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ja/aspose.slides/masterslide/find_shape_by_alt_text/#str) | 指定された代替テキストを持つシェイプの最初の出現を検索します。 |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/ja/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | 現在のマスタースライドを基に新しいマスタースライドを作成し、外部テーマを適用します。<br/>            作成されたマスタースライドをすべての依存スライドに適用します。 |
| [`get_depending_slides(self)`](/slides/python-net/ja/aspose.slides/masterslide/get_depending_slides/#) | このマスタースライドに依存するすべてのスライドの配列を返します。 |

### 参照
* クラス [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)
* クラス [`MasterSlide`](/slides/python-net/ja/aspose.slides/masterslide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)