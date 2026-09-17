---
title: IMasterSlide class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/imasterslide/
---
## IMasterSlide クラス

プレゼンテーション内のマスタースライドを表します。

IMasterSlide タイプは次のメンバーを公開します：

## プロパティ

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/ja/aspose.slides/imasterslide/header_footer_manager/) | マスタースライドの HeaderFooter マネージャーを返します。<br/>            読み取り専用 [`IMasterSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/imasterslideheaderfootermanager)。 |
| [`title_style`](/slides/python-net/ja/aspose.slides/imasterslide/title_style/) | タイトルテキストのスタイルを返します。<br/>            読み取り専用 [`ITextStyle`](/slides/python-net/ja/aspose.slides/itextstyle)。 |
| [`body_style`](/slides/python-net/ja/aspose.slides/imasterslide/body_style/) | 本文テキストのスタイルを返します。<br/>            読み取り専用 [`ITextStyle`](/slides/python-net/ja/aspose.slides/itextstyle)。 |
| [`other_style`](/slides/python-net/ja/aspose.slides/imasterslide/other_style/) | その他のテキストのスタイルを返します。<br/>            読み取り専用 [`ITextStyle`](/slides/python-net/ja/aspose.slides/itextstyle)。 |
| [`layout_slides`](/slides/python-net/ja/aspose.slides/imasterslide/layout_slides/) | このマスタースライドに対する子レイアウトスライドのコレクションを返します。<br/>            読み取り専用 [`IMasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection)。 |
| [`preserve`](/slides/python-net/ja/aspose.slides/imasterslide/preserve/) | 対応するマスターが、マスターに続くすべてのスライドが削除されたときに削除されるかどうかを決定します。<br/>            注意: Aspose.Slides は未使用のマスターを自動的に削除することはありません、<br/>            未使用のマスターを実際に削除するには **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste** を呼び出します。<br/>            読み取り/書き込み **bool**。 |
| [`has_depending_slides`](/slides/python-net/ja/aspose.slides/imasterslide/has_depending_slides/) | このマスタースライドに依存しているスライドが少なくとも1つ存在する場合に true を返します。<br/>            読み取り専用 **bool**。 |
| [`drawing_guides`](/slides/python-net/ja/aspose.slides/imasterslide/drawing_guides/) | マスタースライド用の描画ガイドのコレクションを返します。<br/>            読み取り専用 [`IDrawingGuidesCollection`](/slides/python-net/ja/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/ja/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/ja/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/ja/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/ja/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/ja/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/ja/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/ja/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/ja/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/ja/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/ja/aspose.slides/imasterslide/theme_manager/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/ja/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | 現在のマスタースライドを基に新しいマスタースライドを作成し、外部テーマを適用して <br/>            すべての依存スライドに作成されたマスタースライドを適用します。 |
| [`get_depending_slides(self)`](/slides/python-net/ja/aspose.slides/imasterslide/get_depending_slides/#) | このマスタースライドに依存しているすべてのスライドの配列を返します。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ja/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/ja/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/ja/aspose.slides/imasterslide/create_theme_effective/#) |  |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)