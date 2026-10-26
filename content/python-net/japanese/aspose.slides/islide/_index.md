---
title: ISlide class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/islide/
---
## ISlide クラス

プレゼンテーション内のスライドを表します。

ISlide 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/ja/aspose.slides/islide/header_footer_manager/) | Returns HeaderFooter manager of the slide.<br/>            読み取り専用 [`ISlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/ja/aspose.slides/islide/slide_number/) | Returns a number of slide.<br/>            [`IPresentation.slides`](/slides/python-net/ja/aspose.slides/ipresentation/slides) コレクション内のスライドのインデックスは常に SlideNumber - 1 に等しいです。<br/>            読み書き可能 **int**. |
| [`hidden`](/slides/python-net/ja/aspose.slides/islide/hidden/) | Determines whether the specified slide is hidden during a slide show.<br/>            読み書き可能 **bool**. |
| [`layout_slide`](/slides/python-net/ja/aspose.slides/islide/layout_slide/) | Returns or sets the layout slide for the current slide.<br/>            読み書き可能 [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/ja/aspose.slides/islide/notes_slide_manager/) | Allow to access notes slide, add and remove it.<br/>            読み取り専用 [`INotesSlideManager`](/slides/python-net/ja/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/ja/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/ja/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/ja/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/ja/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/ja/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/ja/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/ja/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/ja/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/ja/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/ja/aspose.slides/islide/theme_manager/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/islide/get_image/#float-float) | カスタムスケーリングを使用した画像オブジェクトを返します。 |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/islide/get_image/#) | サムネイル画像オブジェクトを返します（実サイズの 20%）。 |
| [`get_image(self, image_size)`](/slides/python-net/ja/aspose.slides/islide/get_image/#asposeslidessize) | 指定サイズの画像オブジェクトを返します。 |
| [`get_image(self, options)`](/slides/python-net/ja/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | 指定されたパラメータでサムネイル TIFF ビットマップオブジェクトを返します。 |
| [`get_image(self, options)`](/slides/python-net/ja/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | サムネイルビットマップオブジェクトを返します。 |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | カスタムスケーリングを使用したサムネイルビットマップオブジェクトを返します。 |
| [`get_image(self, options, image_size)`](/slides/python-net/ja/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | 指定サイズのサムネイルビットマップオブジェクトを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/islide/write_as_svg/#iorawiobase) | スライド内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | スライド内容を SVG ファイルとして保存します。 |
| [`get_slide_comments(self, author)`](/slides/python-net/ja/aspose.slides/islide/get_slide_comments/#icommentauthor) | 特定の作者が追加したすべてのスライドコメントを返します。 |
| [`write_as_emf(self, stream)`](/slides/python-net/ja/aspose.slides/islide/write_as_emf/#iorawiobase) | スライド内容を EMF ファイルとして保存します。 |
| [`remove(self)`](/slides/python-net/ja/aspose.slides/islide/remove/#) | プレゼンテーションからスライドを削除します。 |
| [`reset(self)`](/slides/python-net/ja/aspose.slides/islide/reset/#) | LayoutSlide 上にプロトタイプを持つすべてのシェイプの位置、サイズ、書式設定をリセットします。 |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ja/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/ja/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/ja/aspose.slides/islide/create_theme_effective/#) |  |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)