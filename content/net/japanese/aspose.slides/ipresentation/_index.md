---
title: IPresentation
second_title: Aspose.Sildes for .NET API リファレンス
description: プレゼンテーション ドキュメント
type: docs
weight: 6730
url: /ja/aspose.slides/ipresentation/
---
## IPresentation インターフェース

プレゼンテーション ドキュメント

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | プレゼンテーション内のすべてのカスタム データ パーツを返します。読み取り専用 [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | IDisposable インターフェースを返します。読み取り専用 IDisposable。 |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | ベースの IPresentationComponent インターフェースを取得できます。読み取り専用 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | プレゼンテーションに埋め込まれたすべてのオーディオ ファイルのコレクションを返します。読み取り専用 [`IAudioCollection`](../iaudiocollection)。 |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | コメントの作成者のコレクションを返します。読み取り専用 [`ICommentAuthorCollection`](../icommentauthorcollection)。 |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | datetime フィールドの内容を置き換える日付と時刻を取得または設定します。デフォルトではこの Presentation オブジェクトの作成時刻です。読み書き可能 DateTime。 |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | プレゼンテーションのカスタム データを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | シェイプのデフォルト テキスト スタイルを返します。読み取り専用 [`ITextStyle`](../itextstyle)。 |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | プレゼンテーションに署名するために使用された署名のコレクションを返します。読み取り専用 [`IDigitalSignatureCollection`](../idigitalsignaturecollection)。 |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | 標準およびカスタム ドキュメント プロパティを含む DocumentProperties オブジェクトを返します。読み取り専用 [`IDocumentProperties`](../idocumentproperties)。 |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | プレゼンテーション内の最初のスライド番号を表します。読み書き可能 Int32。 |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | フォント マネージャーを返します。読み取り専用 [`IFontsManager`](../ifontsmanager)。 |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | プレゼンテーションのヘッダー/フッターマネージャーを返します。読み取り専用 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager)。 |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | すべてのプレゼンテーション スライドに含まれるハイパーリンクへの簡単なアクセスを提供します（マスタ、レイアウト、ノート スライドは除く）。読み取り専用 [`IHyperlinkQueries`](../ihyperlinkqueries)。 |
| [Images](../../aspose.slides/ipresentation/images) { get; } | プレゼンテーション内のすべての画像のコレクションを返します。読み取り専用 [`IImageCollection`](../iimagecollection)。 |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | プレゼンテーションで定義されているすべてのレイアウト スライドのリストを返します。読み取り専用 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection)。 |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | ハンドアウト マスターマネージャーを返します。読み取り専用 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager)。 |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | ノート マスターマネージャーを返します。読み取り専用 [`IMasterNotesSlideManager`](../imasternotesslidemanager)。 |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | プレゼンテーションで定義されているすべてのマスタースライドのリストを返します。読み取り専用 [`IMasterSlideCollection`](../imasterslidecollection)。 |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | プレゼンテーションのマスターテーマを返します。読み取り専用 [`IMasterTheme`](../../aspose.slides.theme/imastertheme)。 |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | ノート スライドサイズオブジェクトを返します。読み取り専用 [`INotesSize`](../inotessize)。 |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | このプレゼンテーションの権限マネージャーを取得します。読み取り専用 [`IProtectionManager`](../iprotectionmanager)。 |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | プレゼンテーションで定義されているすべてのスライド セクションのリストを返します。読み取り専用 [`ISectionCollection`](../isectioncollection)。 |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | プレゼンテーション ドキュメントに適用された感度ラベルのコレクションを返します。読み取り専用 [`ISensitivityLabelCollection`](../isensitivitylabelcollection)。 |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | プレゼンテーションで定義されているすべてのスライドのリストを返します。読み取り専用 [`ISlideCollection`](../islidecollection)。 |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | スライド サイズオブジェクトを返します。読み取り専用 [`ISlideSize`](../islidesize)。 |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | プレゼンテーションが読み込まれた形式に関する情報を返します。読み取り専用 [`SourceFormat`](./sourceformat)。 |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | プレゼンテーション マクロを含む VBA プロジェクトを取得します。読み書き可能 [`IVbaProject`](../../aspose.slides.vba/ivbaproject)。 |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | プレゼンテーションに埋め込まれたすべてのビデオ ファイルのコレクションを返します。読み取り専用 [`IVideoCollection`](../ivideocollection)。 |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | プレゼンテーション全体のビュー プロパティを取得します。読み取り専用 [`IViewProperties`](../iviewproperties)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | プレゼンテーションのすべてのスライドに対するサムネイル画像オブジェクトを返します。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | プレゼンテーションの指定されたスライドに対するサムネイル ビットマップオブジェクトを返します。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | 指定されたサイズでプレゼンテーションのすべてのスライドに対するサムネイル画像オブジェクトを返します。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | カスタム縮尺でプレゼンテーションのすべてのスライドに対するサムネイル画像オブジェクトを返します。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 指定されたサイズでプレゼンテーションの指定されたスライドに対するサムネイル画像オブジェクトを返します。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | カスタム縮尺でプレゼンテーションの指定されたスライドに対するサムネイル画像オブジェクトを返します。 |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | ID によって Slide、MasterSlide、または LayoutSlide を返します。 |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | 正規表現のすべての一致箇所を指定された色で強調表示します。 |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | サンプルテキストのすべての一致箇所を指定された色で強調表示します。 |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | サンプルテキストのすべての一致箇所を指定された色で強調表示します。 |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | すべてのスライドのすべての対象シェイプ内のすべての段落において、同じ書式のランを結合します。 |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | 正規表現のすべての一致箇所を指定された文字列に置換します。 |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 指定されたテキストのすべての出現箇所を別の指定テキストに置換します。 |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | プレゼンテーションのすべてのスライドを XAML マークアップを表す一連のファイルに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | 指定された形式でプレゼンテーションのすべてのスライドをストリームに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | 指定された形式でプレゼンテーションのすべてのスライドをファイルに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | 指定された形式でプレゼンテーションの指定されたスライドをストリームに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | 指定された形式と追加オプションでプレゼンテーションのすべてのスライドをストリームに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | 指定された形式でプレゼンテーションの指定されたスライドをファイルに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | 指定された形式と追加オプションでプレゼンテーションのすべてのスライドをファイルに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | 指定された形式でプレゼンテーションの指定されたスライドをストリームに保存します。 |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | 指定された形式でプレゼンテーションの指定されたスライドをファイルに保存します。 |

### 参照

* インターフェース [IPresentationComponent](../ipresentationcomponent)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->