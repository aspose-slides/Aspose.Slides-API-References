---
title: IPresentation
second_title: Aspose.Sildes for .NET API リファレンス
description: プレゼンテーション ドキュメント
type: docs
weight: 6770
url: /ja/aspose.slides/ipresentation/
---
## IPresentation インターフェイス

プレゼンテーション ドキュメント

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | プレゼンテーション内のすべてのカスタム データ パーツを返します。読み取り専用 [`ICustomXmlPart`](../icustomxmlpart)[]。 |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | IDisposable インターフェイスを返します。読み取り専用 IDisposable。 |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | ベースの IPresentationComponent インターフェイスを取得できます。読み取り専用 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | プレゼンテーション内のすべての埋め込みオーディオ ファイルのコレクションを返します。読み取り専用 [`IAudioCollection`](../iaudiocollection)。 |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | コメント作成者のコレクションを返します。読み取り専用 [`ICommentAuthorCollection`](../icommentauthorcollection)。 |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | 日時フィールドの内容を置き換える日付と時刻を取得または設定します。デフォルトはこの Presentation オブジェクトの作成時刻です。読み取り/書き込み DateTime。 |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | プレゼンテーションのカスタム データを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | シェイプのデフォルト テキスト スタイルを返します。読み取り専用 [`ITextStyle`](../itextstyle)。 |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | プレゼンテーションに署名するために使用される署名のコレクションを返します。読み取り専用 [`IDigitalSignatureCollection`](../idigitalsignaturecollection)。 |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | 標準およびカスタム ドキュメント プロパティを含む DocumentProperties オブジェクトを返します。読み取り専用 [`IDocumentProperties`](../idocumentproperties)。 |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | プレゼンテーション内の最初のスライド番号を表します。読み取り/書き込み Int32。 |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | フォント マネージャーを返します。読み取り専用 [`IFontsManager`](../ifontsmanager)。 |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | プレゼンテーションの HeaderFooter マネージャーを返します。読み取り専用 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager)。 |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | すべてのプレゼンテーション スライド（マスタ、レイアウト、ノート スライドを除く）に含まれるすべてのハイパーリンクへの簡単なアクセスを提供します。読み取り専用 [`IHyperlinkQueries`](../ihyperlinkqueries)。 |
| [Images](../../aspose.slides/ipresentation/images) { get; } | プレゼンテーション内のすべての画像のコレクションを返します。読み取り専用 [`IImageCollection`](../iimagecollection)。 |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | プレゼンテーションで定義されているすべてのレイアウト スライドの一覧を返します。読み取り専用 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection)。 |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | ハンドアウト マスター マネージャーを返します。読み取り専用 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager)。 |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | ノート マスター マネージャーを返します。読み取り専用 [`IMasterNotesSlideManager`](../imasternotesslidemanager)。 |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | プレゼンテーションで定義されているすべてのマスター スライドの一覧を返します。読み取り専用 [`IMasterSlideCollection`](../imasterslidecollection)。 |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | プレゼンテーションのマスター テーマを返します。読み取り専用 [`IMasterTheme`](../../aspose.slides.theme/imastertheme)。 |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | ノート スライド サイズオブジェクトを返します。読み取り専用 [`INotesSize`](../inotessize)。 |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | このプレゼンテーションの権限マネージャーを取得します。読み取り専用 [`IProtectionManager`](../iprotectionmanager)。 |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | プレゼンテーションで定義されているすべてのスライド セクションの一覧を返します。読み取り専用 [`ISectionCollection`](../isectioncollection)。 |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | プレゼンテーション ドキュメントに適用された感度ラベルのコレクションを返します。読み取り専用 [`ISensitivityLabelCollection`](../isensitivitylabelcollection)。 |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | プレゼンテーションで定義されているすべてのスライドの一覧を返します。読み取り専用 [`ISlideCollection`](../islidecollection)。 |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | スライド サイズオブジェクトを返します。読み取り専用 [`ISlideSize`](../islidesize)。 |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | プレゼンテーションが読み込まれた形式に関する情報を返します。読み取り専用 [`SourceFormat`](./sourceformat)。 |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | プレゼンテーション マクロを含む VBA プロジェクトを取得します。読み取り/書き込み [`IVbaProject`](../../aspose.slides.vba/ivbaproject)。 |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | プレゼンテーション内のすべての埋め込みビデオ ファイルのコレクションを返します。読み取り専用 [`IVideoCollection`](../ivideocollection)。 |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | プレゼンテーション全体のビュー プロパティを取得します。読み取り専用 [`IViewProperties`](../iviewproperties)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | プレゼンテーションのすべてのスライドのサムネイル画像オブジェクトを返します。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | 指定されたスライドのサムネイル ビットマップ オブジェクトを返します。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | 指定サイズでプレゼンテーションのすべてのスライドのサムネイル画像オブジェクトを返します。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | カスタム スケーリングでプレゼンテーションのすべてのスライドのサムネイル画像オブジェクトを返します。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 指定されたスライドを指定サイズでサムネイル画像オブジェクトを返します。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | 指定されたスライドをカスタム スケーリングでサムネイル画像オブジェクトを返します。 |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Id により Slide、MasterSlide、または LayoutSlide を返します。 |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | 正規表現のすべての一致箇所を指定された色でハイライトします。 |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | サンプルテキストのすべての一致箇所を指定された色でハイライトします。 |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | サンプルテキストのすべての一致箇所を指定された色でハイライトします。 |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | すべてのスライドのすべての対象シェイプ内のすべての段落で、同じ書式のランを結合します。 |
| [RefreshChartsData](../../aspose.slides/ipresentation/refreshchartsdata)(bool) | プレゼンテーション内のすべてのチャートのデータを、元のブックから再読み込みします。 |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | 正規表現のすべての一致箇所を指定された文字列に置換します。 |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 指定されたテキストのすべての出現箇所を別の指定テキストに置換します。 |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | プレゼンテーションのすべてのスライドを XAML マークアップを表すファイル群に保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | プレゼンテーションのすべてのスライドを、指定された形式でストリームに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | プレゼンテーションのすべてのスライドを、指定された形式のファイルに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | 指定されたスライドを、指定形式でストリームに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | プレゼンテーションのすべてのスライドを、指定形式および追加オプションでストリームに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | 指定されたスライドを、指定形式のファイルに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | プレゼンテーションのすべてのスライドを、指定形式および追加オプションでファイルに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | 指定されたスライドを、指定形式でストリームに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | 指定されたスライドを、指定形式のファイルに保存します。 |

### 参照

* インターフェイス [IPresentationComponent](../ipresentationcomponent)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->