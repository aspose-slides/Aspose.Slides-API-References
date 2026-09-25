---
title: Presentation class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/presentation/
---
## Presentation クラス

Microsoft PowerPoint プレゼンテーションを表します。

Presentation 型は次のメンバーを公開します:

## コンストラクタ

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides/presentation/__init__/#) | このコンストラクタは新しいプレゼンテーションをゼロから作成します。<br/>            作成されたプレゼンテーションには空のスライドが1枚含まれます。 |
| [`__init__(self, load_options)`](/slides/python-net/ja/aspose.slides/presentation/__init__/#loadoptions) | このコンストラクタは新しいプレゼンテーションをゼロから作成します。<br/>            作成されたプレゼンテーションには空のスライドが1枚含まれます。 |
| [`__init__(self, stream)`](/slides/python-net/ja/aspose.slides/presentation/__init__/#iorawiobase) | このコンストラクタは既存の Presentation を読み込むための主要な手段です。 |
| [`__init__(self, stream, load_options)`](/slides/python-net/ja/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | このコンストラクタは既存の Presentation を読み込むための主要な手段です。 |
| [`__init__(self, file)`](/slides/python-net/ja/aspose.slides/presentation/__init__/#str) | このコンストラクタは、Presentation の内容が読み込まれるソースファイル パスを取得します。<br/>             |
| [`__init__(self, file, load_options)`](/slides/python-net/ja/aspose.slides/presentation/__init__/#str-loadoptions) | このコンストラクタは、Presentation の内容が読み込まれるソースファイル パスを取得します。<br/>            |

## プロパティ

| Property | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/ja/aspose.slides/presentation/current_date_time/) | 日時フィールドの内容を置き換える日付と時刻を取得または設定します。<br/>            デフォルトではこの Presentation オブジェクトの作成時刻です。<br/>            読み取り/書き込み **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/ja/aspose.slides/presentation/header_footer_manager/) | 実際の HeaderFooter マネージャを取得します。<br/>            読み取り専用 [`IPresentationHeaderFooterManager`](/slides/python-net/ja/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/ja/aspose.slides/presentation/protection_manager/) | このプレゼンテーションの権限マネージャを取得します。<br/>            読み取り専用 [`IProtectionManager`](/slides/python-net/ja/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/ja/aspose.slides/presentation/slides/) | プレゼンテーションで定義されているすべてのスライドの一覧を取得します。<br/ja/>            読み取り専用 [`ISlideCollection`](/slides/python-net/ja/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/ja/aspose.slides/presentation/sections/) | プレゼンテーションで定義されているすべてのスライド セクションの一覧を取得します。<br/>            読み取り専用 [`ISectionCollection`](/slides/python-net/ja/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/ja/aspose.slides/presentation/slide_size/) | スライド サイズ オブジェクトを取得します。<br/>            読み取り専用 [`ISlideSize`](/slides/python-net/ja/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/ja/aspose.slides/presentation/notes_size/) | ノート スライド サイズ オブジェクトを取得します。<br/>            読み取り専用 [`INotesSize`](/slides/python-net/ja/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/ja/aspose.slides/presentation/layout_slides/) | プレゼンテーションで定義されているすべてのレイアウト スライドの一覧を取得します。<br/>            読み取り専用 [`IGlobalLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/ja/aspose.slides/presentation/masters/) | プレゼンテーションで定義されているすべてのマスタースライドの一覧を取得します。<br/>            読み取り専用 [`IMasterSlideCollection`](/slides/python-net/ja/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/ja/aspose.slides/presentation/master_notes_slide_manager/) | ノート マスター マネージャを取得します。<br/>            読み取り専用 [`IMasterNotesSlideManager`](/slides/python-net/ja/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/ja/aspose.slides/presentation/master_handout_slide_manager/) | 配布資料 マスター マネージャを取得します。<br/>            読み取り専用 [`IMasterHandoutSlideManager`](/slides/python-net/ja/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/ja/aspose.slides/presentation/fonts_manager/) | フォント マネージャを取得します。<br/>            読み取り専用 [`IFontsManager`](/slides/python-net/ja/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/ja/aspose.slides/presentation/default_text_style/) | シェイプのデフォルト テキスト スタイルを取得します。<br/>            読み取り専用 [`ITextStyle`](/slides/python-net/ja/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/ja/aspose.slides/presentation/comment_authors/) | コメント作者のコレクションを取得します。<br/>            読み取り専用 [`ICommentAuthorCollection`](/slides/python-net/ja/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/ja/aspose.slides/presentation/document_properties/) | 標準およびカスタム文書プロパティを含む DocumentProperties オブジェクトを取得します。<br/>            読み取り専用 [`IDocumentProperties`](/slides/python-net/ja/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/ja/aspose.slides/presentation/images/) | プレゼンテーション内のすべての画像のコレクションを取得します。<br/>            読み取り専用 [`IImageCollection`](/slides/python-net/ja/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/ja/aspose.slides/presentation/audios/) | プレゼンテーション内のすべての埋め込みオーディオ ファイルのコレクションを取得します。<br/>            読み取り専用 [`IAudioCollection`](/slides/python-net/ja/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/ja/aspose.slides/presentation/videos/) | プレゼンテーション内のすべての埋め込みビデオ ファイルのコレクションを取得します。<br/>            読み取り専用 [`IVideoCollection`](/slides/python-net/ja/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/ja/aspose.slides/presentation/slide_show_settings/) | プレゼンテーションのスライドショー設定を取得します。 |
| [`digital_signatures`](/slides/python-net/ja/aspose.slides/presentation/digital_signatures/) | プレゼンテーションに署名するために使用される署名のコレクションを取得します。<br/>            読み取り専用 [`IDigitalSignatureCollection`](/slides/python-net/ja/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/ja/aspose.slides/presentation/custom_data/) | プレゼンテーションのカスタム データを取得します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/ja/aspose.slides/presentation/all_custom_xml_parts/) | プレゼンテーション内のすべてのカスタム データ パートを取得します。<br/>            読み取り専用 [`ICustomXmlPart`](/slides/python-net/ja/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/ja/aspose.slides/presentation/vba_project/) | プレゼンテーション マクロを含む VBA プロジェクトを取得または設定します。<br/>            読み取り/書き込み [`IVbaProject`](/slides/python-net/ja/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/ja/aspose.slides/presentation/hyperlink_queries/) | すべてのプレゼンテーション スライドに含まれるすべてのハイパーリンク（マスター、レイアウト、ノート スライドを除く）への簡単なアクセスを提供します。<br/>            読み取り専用 [`IHyperlinkQueries`](/slides/python-net/ja/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/ja/aspose.slides/presentation/view_properties/) | プレゼンテーション全体のビュー プロパティを取得します。<br/>            読み取り専用 [`IViewProperties`](/slides/python-net/ja/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/ja/aspose.slides/presentation/first_slide_number/) | プレゼンテーション内の最初のスライド番号を表します |
| [`sensitivity_labels`](/slides/python-net/ja/aspose.slides/presentation/sensitivity_labels/) | プレゼンテーション文書に適用された感度ラベルのコレクションを取得します。<br/>            読み取り専用 [`ISensitivityLabelCollection`](/slides/python-net/ja/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/ja/aspose.slides/presentation/source_format/) | プレゼンテーションが読み込まれた形式に関する情報を取得します。<br/>            読み取り専用 [`SourceFormat`](/slides/python-net/ja/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/ja/aspose.slides/presentation/master_theme/) | マスターテーマを取得します。<br/>            読み取り専用 [`IMasterTheme`](/slides/python-net/ja/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/ja/aspose.slides/presentation/presentation/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/ja/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | プレゼンテーションのすべてのスライドを指定された形式のファイルに保存します。 |
| [`save(self, stream, format)`](/slides/python-net/ja/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | プレゼンテーションのすべてのスライドを指定された形式のストリームに保存します。 |
| [`save(self, fname, format, options)`](/slides/python-net/ja/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/ja/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | プレゼンテーションのすべてのスライドを指定された形式のストリームに、追加オプションとともに保存します。 |
| [`save(self, options)`](/slides/python-net/ja/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | プレゼンテーションのすべてのスライドを XAML マークアップを表すファイルのセットに保存します。 |
| [`save(self, fname, slides, format)`](/slides/python-net/ja/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | 指定されたスライドをページ番号を保持したまま、指定された形式のファイルに保存します。 |
| [`save(self, fname, slides, format, options)`](/slides/python-net/ja/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 指定されたスライドをページ番号を保持したまま、指定された形式のファイルに保存します。 |
| [`save(self, stream, slides, format)`](/slides/python-net/ja/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | 指定されたスライドをページ番号を保持したまま、指定された形式のストリームに保存します。 |
| [`save(self, stream, slides, format, options)`](/slides/python-net/ja/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 指定されたスライドをページ番号を保持したまま、指定された形式のストリームに保存します。 |
| [`get_images(self, options)`](/slides/python-net/ja/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | プレゼンテーションのすべてのスライドの Image オブジェクトを取得します。 |
| [`get_images(self, options, slides)`](/slides/python-net/ja/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | 指定されたスライドのサムネイル Image オブジェクトを取得します。 |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | カスタムスケーリングを使用して、プレゼンテーションのすべてのスライドのサムネイル Image オブジェクトを取得します。 |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | カスタムスケーリングを使用して、指定されたスライドのサムネイル Image オブジェクトを取得します。 |
| [`get_images(self, options, image_size)`](/slides/python-net/ja/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | 指定されたサイズで、プレゼンテーションのすべてのスライドのサムネイル Image オブジェクトを取得します。 |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/ja/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | 指定されたサイズで、指定されたスライドのサムネイル Image オブジェクトを取得します。 |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ja/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | サンプルテキストのすべての一致箇所を指定された色でハイライトします。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ja/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | サンプルテキストのすべての一致箇所を指定された色でハイライトします。 |
| [`get_slide_by_id(self, id)`](/slides/python-net/ja/aspose.slides/presentation/get_slide_by_id/#int) | Id によって Slide、MasterSlide、または LayoutSlide を取得します。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/presentation/join_portions_with_same_formatting/#) | すべてのスライドのすべての許容可能なシェイプ内のすべての段落で、同じ書式設定のランを結合します。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ja/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | 正規表現のすべての一致箇所を指定された色でハイライトします。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ja/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 指定されたテキストのすべての出現箇所を別の指定テキストに置換します。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ja/aspose.slides/presentation/replace_regex/#str-str) | 正規表現のすべての一致箇所を指定された文字列に置換します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)