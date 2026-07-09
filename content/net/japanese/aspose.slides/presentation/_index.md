---
title: Presentation
second_title: Aspose.Sildes for .NET API リファレンス
description: Microsoft PowerPoint プレゼンテーションを表します。
type: docs
weight: 9590
url: /ja/aspose.slides/presentation/
---
## Presentation クラス

Microsoft PowerPoint プレゼンテーションを表します。

```csharp
public sealed class Presentation : IPresentation
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Presentation](presentation#constructor)() | このコンストラクタは新しいプレゼンテーションを最初から作成します。作成されたプレゼンテーションには空のスライドが1枚含まれます。 |
| [Presentation](presentation#constructor_1)(LoadOptions) | このコンストラクタは新しいプレゼンテーションを最初から作成します。作成されたプレゼンテーションには空のスライドが1枚含まれます。 |
| [Presentation](presentation#constructor_2)(Stream) | このコンストラクタは既存の Presentation を読み込むための主要な手段です。 |
| [Presentation](presentation#constructor_4)(string) | このコンストラクタは、Presentation の内容を読み取るソースファイルパスを取得します。 |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | このコンストラクタは既存の Presentation を読み込むための主要な手段です。 |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | このコンストラクタは、Presentation の内容を読み取るソースファイルパスを取得します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | プレゼンテーション内のすべてのカスタム データ パーツを返します。読み取り専用 [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | プレゼンテーションに埋め込まれたすべてのオーディオ ファイルのコレクションを返します。読み取り専用 [`IAudioCollection`](../iaudiocollection)。 |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | コメント作成者のコレクションを返します。読み取り専用 [`ICommentAuthorCollection`](../icommentauthorcollection)。 |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | 日時フィールドの内容を置き換える日付と時刻を取得または設定します。デフォルトはこの Presentation オブジェクトの作成時刻です。読み書き可能な DateTime。 |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | プレゼンテーションのカスタム データを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | シェイプのデフォルト テキスト スタイルを返します。読み取り専用 [`ITextStyle`](../itextstyle)。 |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | プレゼンテーションに署名するために使用される署名のコレクションを返します。読み取り専用 [`IDigitalSignatureCollection`](../idigitalsignaturecollection)。 |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | 標準およびカスタム ドキュメント プロパティを含む DocumentProperties オブジェクトを返します。読み取り専用 [`IDocumentProperties`](../idocumentproperties)。 |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | プレゼンテーション内の最初のスライド番号を表します。 |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | フォント マネージャを返します。読み取り専用 [`IFontsManager`](../ifontsmanager)。 |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | 現在のヘッダー/フッターマネージャを返します。読み取り専用 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager)。 |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | すべてのプレゼンテーション スライド（マスター、レイアウト、ノート スライドを除く）に含まれるすべてのハイパーリンクへの簡易アクセスを提供します。読み取り専用 [`IHyperlinkQueries`](../ihyperlinkqueries)。 |
| [Images](../../aspose.slides/presentation/images) { get; } | プレゼンテーション内のすべての画像のコレクションを返します。読み取り専用 [`IImageCollection`](../iimagecollection)。 |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | プレゼンテーションで定義されているすべてのレイアウト スライドの一覧を返します。読み取り専用 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection)。 |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | 配付資料マスターマネージャを返します。読み取り専用 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager)。 |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | ノートマスターマネージャを返します。読み取り専用 [`IMasterNotesSlideManager`](../imasternotesslidemanager)。 |
| [Masters](../../aspose.slides/presentation/masters) { get; } | プレゼンテーションで定義されているすべてのマスタースライドの一覧を返します。読み取り専用 [`IMasterSlideCollection`](../imasterslidecollection)。 |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | マスターテーマを返します。読み取り専用 [`IMasterTheme`](../../aspose.slides.theme/imastertheme)。 |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | ノートスライドサイズオブジェクトを返します。読み取り専用 [`INotesSize`](../inotessize)。 |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | このプレゼンテーションの権限マネージャを取得します。読み取り専用 [`IProtectionManager`](../iprotectionmanager)。 |
| [Sections](../../aspose.slides/presentation/sections) { get; } | プレゼンテーションで定義されているすべてのスライド セクションの一覧を返します。読み取り専用 [`ISectionCollection`](../isectioncollection)。 |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | プレゼンテーション ドキュメントに適用された感度ラベルのコレクションを返します。読み取り専用 [`ISensitivityLabelCollection`](../isensitivitylabelcollection)。 |
| [Slides](../../aspose.slides/presentation/slides) { get; } | プレゼンテーションで定義されているすべてのスライドの一覧を返します。読み取り専用 [`ISlideCollection`](../islidecollection)。 |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | プレゼンテーションのスライドショー設定を返します。 |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | スライド サイズ オブジェクトを返します。読み取り専用 [`ISlideSize`](../islidesize)。 |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | プレゼンテーションが読み込まれた形式に関する情報を返します。読み取り専用 [`SourceFormat`](../sourceformat)。 |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | プレゼンテーション マクロを含む VBA プロジェクトを取得または設定します。読み書き可能 [`IVbaProject`](../../aspose.slides.vba/ivbaproject)。 |
| [Videos](../../aspose.slides/presentation/videos) { get; } | プレゼンテーションに埋め込まれたすべてのビデオ ファイルのコレクションを返します。読み取り専用 [`IVideoCollection`](../ivideocollection)。 |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | プレゼンテーション全体のビュー プロパティを取得します。読み取り専用 [`IViewProperties`](../iviewproperties)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | この Presentation オブジェクトが使用しているすべてのリソースを解放します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | プレゼンテーションのすべてのスライドの Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | 指定されたスライドのサムネイル Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | 指定されたサイズで、プレゼンテーションのすべてのスライドのサムネイル Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | カスタムスケーリングで、プレゼンテーションのすべてのスライドのサムネイル Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 指定されたサイズで、指定されたスライドのサムネイル Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | カスタムスケーリングで、指定されたスライドのサムネイル Image オブジェクトを返します。 |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | ID により Slide、MasterSlide、または LayoutSlide を返します。 |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | 正規表現のすべての一致箇所を指定された色でハイライトします。 |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | サンプル テキストのすべての一致箇所を指定された色でハイライトします。 |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | サンプル テキストのすべての一致箇所を指定された色でハイライトします。 |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | すべてのスライドのすべての対象シェイプ内のすべての段落で、同じ書式のランを結合します。 |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | 正規表現のすべての一致箇所を指定された文字列に置換します。 |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 指定されたテキストのすべての出現箇所を別の指定テキストに置換します。 |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | プレゼンテーションのすべてのスライドを XAML マークアップを表すファイル群に保存します。 |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | プレゼンテーションのすべてのスライドを指定された形式でストリームに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | プレゼンテーションのすべてのスライドを指定された形式でファイルに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | ページ番号を保持したまま、指定された形式でプレゼンテーションの指定スライドをストリームに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | 指定された形式と追加オプションで、プレゼンテーションのすべてのスライドをストリームに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | ページ番号を保持したまま、指定された形式でプレゼンテーションの指定スライドをファイルに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | ページ番号を保持したまま、指定された形式でプレゼンテーションの指定スライドをストリームに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | ページ番号を保持したまま、指定された形式でプレゼンテーションの指定スライドをファイルに保存します。 |

### 例

次の例は PowerPoint Presentation の作成方法を示しています。

```csharp
[C#]
// プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
using (Presentation presentation = new Presentation())
{
    // 最初のスライドを取得します
    ISlide slide = presentation.Slides[0];
    // ライン型のオートシェイプを追加します
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// プレゼンテーション ファイルを保存します。
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

次の例は Presentation を開いて保存する方法を示しています。

```csharp
[C#]
// Presentation でサポートされている任意のファイル（例：ppt、pptx、odp など）をロードします。
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// プレゼンテーション ファイルを保存します。
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### 参照

* インターフェイス [IPresentation](../ipresentation)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->