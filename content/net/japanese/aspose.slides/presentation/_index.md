---
title: Presentation
second_title: Aspose.Sildes for .NET API リファレンス
description: Microsoft PowerPoint プレゼンテーションを表します。
type: docs
weight: 9610
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
| [Presentation](presentation#constructor)() | このコンストラクタは、新しいプレゼンテーションを最初から作成します。作成されたプレゼンテーションには空のスライドが1枚含まれます。 |
| [Presentation](presentation#constructor_1)(LoadOptions) | このコンストラクタは、新しいプレゼンテーションを最初から作成します。作成されたプレゼンテーションには空のスライドが1枚含まれます。 |
| [Presentation](presentation#constructor_2)(Stream) | このコンストラクタは、既存の Presentation を読み取る主な手段です。 |
| [Presentation](presentation#constructor_4)(string) | このコンストラクタは、Presentation の内容が読み取られるソースファイルパスを取得します。 |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | このコンストラクタは、既存の Presentation を読み取る主な手段です。 |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | このコンストラクタは、Presentation の内容が読み取られるソースファイルパスを取得します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | プレゼンテーション内のすべてのカスタム データ パートを返します。読み取り専用 [`ICustomXmlPart`](../icustomxmlpart)[]。 |
| [Audios](../../aspose.slides/presentation/audios) { get; } | プレゼンテーションに埋め込まれたすべてのオーディオ ファイルのコレクションを返します。読み取り専用 [`IAudioCollection`](../iaudiocollection)。 |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | コメント作成者のコレクションを返します。読み取り専用 [`ICommentAuthorCollection`](../icommentauthorcollection)。 |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | datetime フィールドの内容に置き換える日付と時刻を取得または設定します。デフォルトはこの Presentation オブジェクトの作成時刻です。読み書き可能 DateTime。 |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | プレゼンテーションのカスタム データを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | シェイプの既定テキスト スタイルを返します。読み取り専用 [`ITextStyle`](../itextstyle)。 |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | プレゼンテーションに署名するために使用される署名のコレクションを返します。読み取り専用 [`IDigitalSignatureCollection`](../idigitalsignaturecollection)。 |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | 標準およびカスタム ドキュメント プロパティを含む DocumentProperties オブジェクトを返します。読み取り専用 [`IDocumentProperties`](../idocumentproperties)。 |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | プレゼンテーション内の最初のスライド番号を表します |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | フォント マネージャーを返します。読み取り専用 [`IFontsManager`](../ifontsmanager)。 |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | 実際のヘッダー/フッター マネージャーを返します。読み取り専用 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager)。 |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | すべてのプレゼンテーション スライド（マスター、レイアウト、ノート スライドは除く）に含まれるすべてのハイパーリンクへ簡単にアクセスできるようにします。読み取り専用 [`IHyperlinkQueries`](../ihyperlinkqueries)。 |
| [Images](../../aspose.slides/presentation/images) { get; } | プレゼンテーション内のすべての画像のコレクションを返します。読み取り専用 [`IImageCollection`](../iimagecollection)。 |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | プレゼンテーションで定義されているすべてのレイアウト スライドのリストを返します。読み取り専用 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection)。 |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | 配布資料マスター マネージャーを返します。読み取り専用 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager)。 |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | ノート マスター マネージャーを返します。読み取り専用 [`IMasterNotesSlideManager`](../imasternotesslidemanager)。 |
| [Masters](../../aspose.slides/presentation/masters) { get; } | プレゼンテーションで定義されているすべてのマスター スライドのリストを返します。読み取り専用 [`IMasterSlideCollection`](../imasterslidecollection)。 |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | マスター テーマを返します。読み取り専用 [`IMasterTheme`](../../aspose.slides.theme/imastertheme)。 |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | ノート スライド サイズ オブジェクトを返します。読み取り専用 [`INotesSize`](../inotessize)。 |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | このプレゼンテーションの権限マネージャーを取得します。読み取り専用 [`IProtectionManager`](../iprotectionmanager)。 |
| [Sections](../../aspose.slides/presentation/sections) { get; } | プレゼンテーションで定義されているすべてのスライド セクションのリストを返します。読み取り専用 [`ISectionCollection`](../isectioncollection)。 |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | プレゼンテーション ドキュメントに適用された感度ラベルのコレクションを返します。読み取り専用 [`ISensitivityLabelCollection`](../isensitivitylabelcollection)。 |
| [Slides](../../aspose.slides/presentation/slides) { get; } | プレゼンテーションで定義されているすべてのスライドのリストを返します。読み取り専用 [`ISlideCollection`](../islidecollection)。 |
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
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | 指定したスライドのサムネイル Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | 指定サイズでプレゼンテーションのすべてのスライドのサムネイル Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | カスタム スケーリングでプレゼンテーションのすべてのスライドのサムネイル Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 指定サイズで指定したスライドのサムネイル Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | カスタム スケーリングで指定したスライドのサムネイル Image オブジェクトを返します。 |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Id により Slide、MasterSlide、または LayoutSlide を返します。 |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | 正規表現のすべての一致部分を指定された色でハイライトします。 |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | サンプルテキストのすべての一致部分を指定された色でハイライトします。 |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | サンプルテキストのすべての一致部分を指定された色でハイライトします。 |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | すべてのスライドのすべての許容可能なシェイプ内のすべての段落で、同一書式のランを結合します。 |
| [RefreshChartsData](../../aspose.slides/presentation/refreshchartsdata)(bool) | プレゼンテーション内のすべてのチャートのデータを、ソース ワークブックから再読み込みします。 |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | 正規表現のすべての一致を指定された文字列に置換します。 |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 指定されたテキストのすべての出現箇所を別の指定テキストに置換します。 |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | プレゼンテーションのすべてのスライドを XAML マークアップを表すファイル群に保存します。 |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | プレゼンテーションのすべてのスライドを指定された形式でストリームに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | プレゼンテーションのすべてのスライドを指定形式のファイルに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | 指定したスライドをページ番号を保持したまま、指定形式でストリームに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | プレゼンテーションのすべてのスライドを指定形式および追加オプションでストリームに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | 指定したスライドをページ番号を保持したまま、指定形式のファイルに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | 指定したスライドをページ番号を保持したまま、指定形式とオプションでストリームに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | 指定したスライドをページ番号を保持したまま、指定形式とオプションでファイルに保存します。 |

### 例

以下の例は、PowerPoint Presentation の作成方法を示します。

```csharp
[C#]
// プレゼンテーション ファイルを表す Presentation オブジェクトを作成します
using (Presentation presentation = new Presentation())
{
    // 最初のスライドを取得します
    ISlide slide = presentation.Slides[0];
    // ラインタイプのオートシェイプを追加します
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// プレゼンテーション ファイルを保存します。
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

以下の例は、Presentation の開閉と保存方法を示します。

```csharp
[C#]
// Presentation でサポートされている任意のファイルを読み込みます（例: ppt、pptx、odp など）。
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