---
title: IPresentation class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ipresentation/
---
## IPresentation クラス

プレゼンテーション ドキュメント

IPresentation 型は次のメンバーを公開します:

## プロパティ

| Property | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/ja/aspose.slides/ipresentation/current_date_time/) | datetime フィールドの内容を置き換える日付と時刻を取得または設定します。<br/>            デフォルトではこの Presentation オブジェクトの作成時刻です。<br/>            読み取り/書き込み **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/ja/aspose.slides/ipresentation/header_footer_manager/) | プレゼンテーションの HeaderFooter マネージャーを取得します。<br/>            読み取り専用 [`IPresentationHeaderFooterManager`](/slides/python-net/ja/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/ja/aspose.slides/ipresentation/protection_manager/) | このプレゼンテーションの権限マネージャーを取得します。 <br/>            読み取り専用 [`IProtectionManager`](/slides/python-net/ja/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/ja/aspose.slides/ipresentation/slides/) | プレゼンテーションで定義されているすべてのスライドの一覧を取得します。<br/ja/>            読み取り専用 [`ISlideCollection`](/slides/python-net/ja/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/ja/aspose.slides/ipresentation/sections/) | プレゼンテーションで定義されているすべてのスライド セクションの一覧を取得します。<br/>            読み取り専用 [`ISectionCollection`](/slides/python-net/ja/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/ja/aspose.slides/ipresentation/slide_size/) | スライド サイズ オブジェクトを取得します。<br/>            読み取り専用 [`ISlideSize`](/slides/python-net/ja/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/ja/aspose.slides/ipresentation/notes_size/) | ノート スライド サイズ オブジェクトを取得します。<br/>            読み取り専用 [`INotesSize`](/slides/python-net/ja/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/ja/aspose.slides/ipresentation/layout_slides/) | プレゼンテーションで定義されているすべてのレイアウト スライドの一覧を取得します。<br/>            読み取り専用 [`IGlobalLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/ja/aspose.slides/ipresentation/masters/) | プレゼンテーションで定義されているすべてのマスタースライドの一覧を取得します。<br/>            読み取り専用 [`IMasterSlideCollection`](/slides/python-net/ja/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/ja/aspose.slides/ipresentation/master_notes_slide_manager/) | ノート マスターマネージャーを取得します。<br/>            読み取り専用 [`IMasterNotesSlideManager`](/slides/python-net/ja/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/ja/aspose.slides/ipresentation/master_handout_slide_manager/) | 配布資料 マスターマネージャーを取得します。<br/>            読み取り専用 [`IMasterHandoutSlideManager`](/slides/python-net/ja/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/ja/aspose.slides/ipresentation/fonts_manager/) | フォント マネージャーを取得します。<br/>            読み取り専用 [`IFontsManager`](/slides/python-net/ja/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/ja/aspose.slides/ipresentation/default_text_style/) | シェイプのデフォルト テキスト スタイルを取得します。<br/>            読み取り専用 [`ITextStyle`](/slides/python-net/ja/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/ja/aspose.slides/ipresentation/comment_authors/) | コメント作者のコレクションを取得します。<br/>            読み取り専用 [`ICommentAuthorCollection`](/slides/python-net/ja/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/ja/aspose.slides/ipresentation/document_properties/) | 標準およびカスタム ドキュメント プロパティを含む DocumentProperties オブジェクトを取得します。<br/>            読み取り専用 [`IDocumentProperties`](/slides/python-net/ja/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/ja/aspose.slides/ipresentation/images/) | プレゼンテーション内のすべての画像のコレクションを取得します。<br/>            読み取り専用 [`IImageCollection`](/slides/python-net/ja/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/ja/aspose.slides/ipresentation/audios/) | プレゼンテーション内に埋め込まれたすべてのオーディオ ファイルのコレクションを取得します。<br/>            読み取り専用 [`IAudioCollection`](/slides/python-net/ja/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/ja/aspose.slides/ipresentation/videos/) | プレゼンテーション内に埋め込まれたすべてのビデオ ファイルのコレクションを取得します。<br/>            読み取り専用 [`IVideoCollection`](/slides/python-net/ja/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/ja/aspose.slides/ipresentation/custom_data/) | プレゼンテーションのカスタム データを取得します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/ja/aspose.slides/ipresentation/vba_project/) | プレゼンテーション マクロを含む VBA プロジェクトを取得します。<br/>            読み取り/書き込み [`IVbaProject`](/slides/python-net/ja/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/ja/aspose.slides/ipresentation/source_format/) | プレゼンテーションが読み込まれたフォーマットに関する情報を取得します。<br/>            読み取り専用 [`IPresentation.source_format`](/slides/python-net/ja/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/ja/aspose.slides/ipresentation/master_theme/) | プレゼンテーションのマスターテーマを取得します。<br/>            読み取り専用 [`IMasterTheme`](/slides/python-net/ja/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/ipresentation/hyperlink_queries/) | すべてのプレゼンテーション スライド（マスター、レイアウト、ノート スライドを除く）に含まれるすべてのハイパーリンクへの簡単なアクセスを提供します。<br/>            読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/ja/aspose.slides/ipresentation/view_properties/) | プレゼンテーション全体のビュー プロパティを取得します。<br/>            読み取り専用 [`IViewProperties`](/slides/python-net/ja/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/ja/aspose.slides/ipresentation/first_slide_number/) | プレゼンテーション内の最初のスライド番号を表します。<br/>            読み取り/書き込み **int**. |
| [`all_custom_xml_parts`](/slides/python-net/ja/aspose.slides/ipresentation/all_custom_xml_parts/) | プレゼンテーション内のすべてのカスタム データ パートを取得します。<br/>            読み取り専用 [`ICustomXmlPart`](/slides/python-net/ja/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/ja/aspose.slides/ipresentation/digital_signatures/) | プレゼンテーションに署名するために使用される署名のコレクションを取得します。<br/>            読み取り専用 [`IDigitalSignatureCollection`](/slides/python-net/ja/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/ja/aspose.slides/ipresentation/sensitivity_labels/) | プレゼンテーション ドキュメントに適用された機密ラベルのコレクションを取得します。<br/>            読み取り専用 [`ISensitivityLabelCollection`](/slides/python-net/ja/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/ja/aspose.slides/ipresentation/presentation/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | プレゼンテーションのすべてのスライドを、指定された形式のファイルに保存します。 |
| [`save(self, stream, format)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | プレゼンテーションのすべてのスライドを、指定された形式のストリームに保存します。 |
| [`save(self, fname, format, options)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | プレゼンテーションのすべてのスライドを、指定された形式および追加オプションでファイルに保存します。 |
| [`save(self, stream, format, options)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | プレゼンテーションのすべてのスライドを、指定された形式と追加オプションでストリームに保存します。 |
| [`save(self, fname, slides, format)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | プレゼンテーションの指定されたスライドを、指定された形式のファイルに保存します。 |
| [`save(self, fname, slides, format, options)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | プレゼンテーションの指定されたスライドを、指定された形式のファイルに保存します。 |
| [`save(self, stream, slides, format)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | プレゼンテーションの指定されたスライドを、指定された形式のストリームに保存します。 |
| [`save(self, stream, slides, format, options)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | プレゼンテーションの指定されたスライドを、指定された形式のストリームに保存します。 |
| [`save(self, options)`](/slides/python-net/ja/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | プレゼンテーションのすべてのスライドを、XAML マークアップを表すファイルのセットに保存します。 |
| [`get_images(self, options)`](/slides/python-net/ja/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | プレゼンテーションのすべてのスライドのサムネイル画像オブジェクトを取得します。 |
| [`get_images(self, options, slides)`](/slides/python-net/ja/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | プレゼンテーションの指定されたスライドのサムネイル ビットマップ オブジェクトを取得します。 |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | カスタムスケーリングでプレゼンテーションのすべてのスライドのサムネイル画像オブジェクトを取得します。 |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | カスタムスケーリングでプレゼンテーションの指定されたスライドのサムネイル画像オブジェクトを取得します。 |
| [`get_images(self, options, image_size)`](/slides/python-net/ja/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | 指定されたサイズでプレゼンテーションのすべてのスライドのサムネイル画像オブジェクトを取得します。 |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/ja/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | 指定されたサイズでプレゼンテーションの指定されたスライドのサムネイル画像オブジェクトを取得します。 |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ja/aspose.slides/ipresentation/highlight_text/#str-asposepydrawingcolor) | サンプルテキストのすべての一致箇所を、指定された色でハイライトします。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ja/aspose.slides/ipresentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | サンプルテキストのすべての一致箇所を、指定された色でハイライトします。 |
| [`get_slide_by_id(self, id)`](/slides/python-net/ja/aspose.slides/ipresentation/get_slide_by_id/#int) | Id により Slide、MasterSlide、または LayoutSlide を取得します。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | すべてのスライドのすべての許容可能なシェイプ内のすべての段落で、同じ書式設定を持つランを結合します。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ja/aspose.slides/ipresentation/highlight_regex/#str-asposepydrawingcolor) | 正規表現のすべての一致箇所を、指定された色でハイライトします。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ja/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 指定されたテキストのすべての出現箇所を、別の指定テキストに置換します。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ja/aspose.slides/ipresentation/replace_regex/#str-str) | 正規表現のすべての一致箇所を、指定された文字列に置換します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)