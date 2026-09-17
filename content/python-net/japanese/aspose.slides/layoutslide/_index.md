---
title: LayoutSlide class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/layoutslide/
---
## LayoutSlide クラス

レイアウトスライドを表します。

**Inheritance:**[`LayoutSlide`](/slides/python-net/ja/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)

LayoutSlide 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`shapes`](/slides/python-net/ja/aspose.slides/layoutslide/shapes/) | スライドのシェイプを返します。<br/>            読み取り専用 [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ja/aspose.slides/layoutslide/controls/) | スライド上の ActiveX コントロールのコレクションを返します。<br/>            読み取り専用 [`IControlCollection`](/slides/python-net/ja/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ja/aspose.slides/layoutslide/name/) | スライドの名前を取得または設定します。<br/>            読み書き **str**. |
| [`slide_id`](/slides/python-net/ja/aspose.slides/layoutslide/slide_id/) | スライドの ID を返します。<br/>            読み取り専用 **int**. |
| [`custom_data`](/slides/python-net/ja/aspose.slides/layoutslide/custom_data/) | スライドのカスタム データを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ja/aspose.slides/layoutslide/timeline/) | アニメーション タイムライン オブジェクトを返します。<br/>            読み取り専用 [`IAnimationTimeLine`](/slides/python-net/ja/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ja/aspose.slides/layoutslide/slide_show_transition/) | 指定されたスライドがスライドショー中にどのように進行するかに関する情報を含む Transition オブジェクトを返します。<br/>            読み取り専用 [`ISlideShowTransition`](/slides/python-net/ja/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ja/aspose.slides/layoutslide/background/) | スライドの背景を返します。<br/>            読み取り専用 [`IBackground`](/slides/python-net/ja/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/layoutslide/hyperlink_queries/) | 含まれるハイパーリンクへの簡単なアクセスを提供します。<br/>            読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ja/aspose.slides/layoutslide/show_master_shapes/) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。<br/>            読み書き **bool**. |
| [`presentation`](/slides/python-net/ja/aspose.slides/layoutslide/presentation/) | IPresentation インターフェイスを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ja/aspose.slides/layoutslide/header_footer_manager/) | レイアウトスライドの HeaderFooter マネージャーを返します。<br/>            読み取り専用 [`ILayoutSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/ja/aspose.slides/layoutslide/placeholder_manager/) | レイアウトスライドのプレースホルダー マネージャーを返します。<br/>            読み取り専用 [`ILayoutPlaceholderManager`](/slides/python-net/ja/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/ja/aspose.slides/layoutslide/master_slide/) | レイアウトのマスタースライドを取得または設定します。<br/>            読み書き [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/ja/aspose.slides/layoutslide/theme_manager/) | オーバーライドされたテーマ マネージャーを返します。<br/>            読み取り専用 [`IOverrideThemeManager`](/slides/python-net/ja/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/ja/aspose.slides/layoutslide/layout_type/) | このレイアウトスライドのレイアウト タイプを返します。<br/>            読み取り専用 [`SlideLayoutType`](/slides/python-net/ja/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/ja/aspose.slides/layoutslide/has_depending_slides/) | このレイアウトスライドに依存するスライドが少なくとも1枚存在する場合に true を返します。<br/>            読み取り専用 **bool**. |
| [`drawing_guides`](/slides/python-net/ja/aspose.slides/layoutslide/drawing_guides/) | レイアウトスライドの描画ガイドのコレクションを返します。<br/>            読み取り専用 [`IDrawingGuidesCollection`](/slides/python-net/ja/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ja/aspose.slides/layoutslide/slide/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | すべての許容可能なシェイプのすべての段落で、同じ書式のランを結合します。 |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ja/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | すべての許容可能なシェイプのすべての段落で、同じ書式のランを結合します。 |
| [`equals(self, slide)`](/slides/python-net/ja/aspose.slides/layoutslide/equals/#ibaseslide) | 2 つの IBaseSlide インスタンスが等しいかどうかを判断します。<br/>            返される値はスライドの構造と静的コンテンツに基づいて計算されます。<br/>            すべてのシェイプ、スタイル、テキスト、アニメーション、およびその他の設定などが等しい場合、2 スライドは等しいとみなされます。比較では、SlideId のような一意の識別子の値や、日付プレースホルダーの現在の日付値のような動的コンテンツは考慮されません。 |
| [`create_theme_effective(self)`](/slides/python-net/ja/aspose.slides/layoutslide/create_theme_effective/#) | このスライドに対する実効テーマを返します。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ja/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | 指定された代替テキストを持つシェイプの最初の出現を検索します。 |
| [`remove(self)`](/slides/python-net/ja/aspose.slides/layoutslide/remove/#) | プレゼンテーションからレイアウトを削除します。 |
| [`get_depending_slides(self)`](/slides/python-net/ja/aspose.slides/layoutslide/get_depending_slides/#) | このレイアウトスライドに依存するすべてのスライドを含む配列を返します。 |

### 参照
* クラス [`BaseSlide`](/slides/python-net/ja/aspose.slides/baseslide)
* クラス [`LayoutSlide`](/slides/python-net/ja/aspose.slides/layoutslide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)