---
title: IPresentation class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ipresentation/
---
## IPresentation クラス

プレゼンテーション ドキュメント

IPresentation タイプは以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`current_date_time`](/slides/python-net/ja/aspose.slides/ipresentation/current_date_time/) | 日付と時刻を取得または設定します。この値は datetime フィールドの内容を置き換えます。<br/>            デフォルトではこの Presentation オブジェクトの作成時刻です。<br/>            読み書き **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/ja/aspose.slides/ipresentation/header_footer_manager/) | プレゼンテーションの HeaderFooter マネージャーを返します。<br/>            読み取り専用 [`IPresentationHeaderFooterManager`](/slides/python-net/ja/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/ja/aspose.slides/ipresentation/protection_manager/) | このプレゼンテーションの権限マネージャーを取得します。<br/>            読み取り専用 [`IProtectionManager`](/slides/python-net/ja/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/ja/aspose.slides/ipresentation/slides/) | プレゼンテーションで定義されているすべてのスライドの一覧を返します。<br/ja/>            読み取り専用 [`ISlideCollection`](/slides/python-net/ja/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/ja/aspose.slides/ipresentation/sections/) | プレゼンテーションで定義されているすべてのスライド セクションの一覧を返します。<br/>            読み取り専用 [`ISectionCollection`](/slides/python-net/ja/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/ja/aspose.slides/ipresentation/slide_size/) | スライド サイズオブジェクトを返します。<br/>            読み取り専用 [`ISlideSize`](/slides/python-net/ja/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/ja/aspose.slides/ipresentation/notes_size/) | ノート スライド サイズオブジェクトを返します。<br/>            読み取り専用 [`INotesSize`](/slides/python-net/ja/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/ja/aspose.slides/ipresentation/layout_slides/) | プレゼンテーションで定義されているすべてのレイアウト スライドの一覧を返します。<br/>            読み取り専用 [`IGlobalLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/ja/aspose.slides/ipresentation/masters/) | プレゼンテーションで定義されているすべてのマスター スライドの一覧を返します。<br/>            読み取り専用 [`IMasterSlideCollection`](/slides/python-net/ja/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/ja/aspose.slides/ipresentation/master_notes_slide_manager/) | ノート マスター マネージャーを返します。<br/>            読み取り専用 [`IMasterNotesSlideManager`](/slides/python-net/ja/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/ja/aspose.slides/ipresentation/master_handout_slide_manager/) | 配布資料 マスター マネージャーを返します。<br/>            読み取り専用 [`IMasterHandoutSlideManager`](/slides/python-net/ja/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/ja/aspose.slides/ipresentation/fonts_manager/) | フォント マネージャーを返します。<br/>            読み取り専用 [`IFontsManager`](/slides/python-net/ja/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/ja/aspose.slides/ipresentation/default_text_style/) | シェイプのデフォルト テキスト スタイルを返します。<br/>            読み取り専用 [`ITextStyle`](/slides/python-net/ja/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/ja/aspose.slides/ipresentation/comment_authors/) | コメント作成者のコレクションを返します。<br/>            読み取り専用 [`ICommentAuthorCollection`](/slides/python-net/ja/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/ja/aspose.slides/ipresentation/document_properties/) | 標準およびカスタム ドキュメント プロパティを含む DocumentProperties オブジェクトを返します。<br/>            読み取り専用 [`IDocumentProperties`](/slides/python-net/ja/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/ja/aspose.slides/ipresentation/images/) | プレゼンテーション内のすべての画像のコレクションを返します。<br/>            読み取り専用 [`IImageCollection`](/slides/python-net/ja/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/ja/aspose.slides/ipresentation/audios/) | プレゼンテーション内のすべての埋め込みオーディオ ファイルのコレクションを返します。<br/>            読み取り専用 [`IAudioCollection`](/slides/python-net/ja/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/ja/aspose.slides/ipresentation/videos/) | プレゼンテーション内のすべての埋め込みビデオ ファイルのコレクションを返します。<br/>            読み取り専用 [`IVideoCollection`](/slides/python-net/ja/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/ja/aspose.slides/ipresentation/custom_data/) | プレゼンテーションのカスタム データを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/ja/aspose.slides/ipresentation/vba_project/) | プレゼンテーションのマクロを含む VBA プロジェクトを取得します。<br/>            読み書き [`IVbaProject`](/slides/python-net/ja/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/ja/aspose.slides/ipresentation/source_format/) | プレゼンテーションがロードされた形式に関する情報を返します。<br/>            読み取り専用 [`IPresentation.source_format`](/slides/python-net/ja/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/ja/aspose.slides/ipresentation/master_theme/) | プレゼンテーションのマスター テーマを返します。<br/>            読み取り専用 [`IMasterTheme`](/slides/python-net/ja/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/ipresentation/hyperlink_queries/) | すべてのプレゼンテーション スライドに含まれるハイパーリンク（マスター、レイアウト、ノート スライドを除く）への簡単なアクセスを提供します。<br/>            読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/ja/aspose.slides/ipresentation/view_properties/) | プレゼンテーション全体の表示プロパティを取得します。<br/>            読み取り専用 [`IViewProperties`](/slides/python-net/ja/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/ja/aspose.slides/ipresentation/first_slide_number/) | プレゼンテーションの最初のスライド番号を表します。<br/>            読み書き **int**. |
| [`all_custom_xml_parts`](/slides/python-net/ja/aspose.slides/ipresentation/all_custom_xml_parts/) | プレゼンテーション内のすべてのカスタム データ パーツを返します。<br/>            読み取り専用 [`ICustomXmlPart`](/slides/python-net/ja/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/ja/aspose.slides/ipresentation/digital_signatures/) | プレゼンテーションに署名するために使用される署名のコレクションを返します。<br/>            読み取り専用 [`IDigitalSignatureCollection`](/slides/python-net/ja/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/ja/aspose.slides/ipresentation/sensitivity_labels/) | プレゼンテーション ドキュメントに適用された感度ラベルのコレクションを返します。<br/>            読み取り専用 [`ISensitivityLabelCollection`](/slides/python-net/ja/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/ja/aspose.slides/ipresentation/presentation/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | 指定された形式でプレゼンテーションのすべてのスライドをファイルに保存します。 |
| [`save(self, stream, format)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | 指定された形式でプレゼンテーションのすべてのスライドをストリームに保存します。 |
| [`save(self, fname, format, options)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 指定された形式および追加オプションでプレゼンテーションのすべてのスライドをファイルに保存します。 |
| [`save(self, stream, format, options)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 指定された形式および追加オプションでプレゼンテーションのすべてのスライドをストリームに保存します。 |
| [`save(self, fname, slides, format)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | 指定された形式でプレゼンテーションの指定スライドをファイルに保存します。 |
| [`save(self, fname, slides, format, options)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 指定された形式でプレゼンテーションの指定スライドをファイルに保存します。 |
| [`save(self, stream, slides, format)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | 指定された形式でプレゼンテーションの指定スライドをストリームに保存します。 |
| [`save(self, stream, slides, format, options)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 指定された形式でプレゼンテーションの指定スライドをストリームに保存します。 |
| [`save(self, options)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | プレゼンテーションのすべてのスライドを XAML マークアップを表すファイルのセットに保存します。 |
| [`get_images(self, options)`](/slides/python-net/ja/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | プレゼンテーションのすべてのスライドに対するサムネイル画像オブジェクトを返します。 |
| [`get_images(self, options, slides)`](/slides/python-net/ja/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | プレゼンテーションの指定スライドに対するサムネイル ビットマップ オブジェクトを返します。 |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | カスタム スケーリングでプレゼンテーションのすべてのスライドに対するサムネイル画像オブジェクトを返します。 |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | カスタム スケーリングでプレゼンテーションの指定スライドに対するサムネイル画像オブジェクトを返します。 |
| [`get_images(self, options, image_size)`](/slides/python-net/ja/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | 指定サイズでプレゼンテーションのすべてのスライドに対するサムネイル画像オブジェクトを返します。 |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/ja/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | 指定サイズでプレゼンテーションの指定スライドに対するサムネイル画像オブジェクトを返します。 |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ja/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor) | サンプルテキストのすべての一致箇所を指定された色でハイライトします。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ja/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | サンプルテキストのすべての一致箇所を指定された色でハイライトします。 |
| [`get_slide_by_id(self, id)`](/slides/python-net/ja/aspose.slides/ipresentation/get_slide_by_id/#int) | Id に基づいて Slide、MasterSlide、または LayoutSlide を返します。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | すべてのスライドのすべての対象シェイプ内のすべての段落で、同じ書式設定のランを結合します。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ja/aspose.slides/ipresentation/highlight_regex/#str-asposeslidescolor) | 正規表現のすべての一致箇所を指定された色でハイライトします。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ja/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 指定されたテキストのすべての出現箇所を別の指定テキストに置換します。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ja/aspose.slides/ipresentation/replace_regex/#str-str) | 正規表現のすべての一致箇所を指定された文字列に置換します。 |
| [`refresh_charts_data(self, skip_failed_charts)`](/slides/python-net/ja/aspose.slides/ipresentation/refresh_charts_data/#bool) | プレゼンテーション内のすべてのチャートのデータを、元のブックから再読み込みします。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)