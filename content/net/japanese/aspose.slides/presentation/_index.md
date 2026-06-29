---
title: Presentation
second_title: Aspose.Sildes の .NET API リファレンス
description: Microsoft PowerPoint プレゼンテーションを表します。
type: docs
weight: 9570
url: /ja/aspose.slides/presentation/
---
## Presentation クラス

Microsoft PowerPoint プレゼンテーションを表します。

```csharp
public sealed class Presentation : IPresentation
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Presentation](presentation#constructor)() | このコンストラクターは新しいプレゼンテーションを最初から作成します。作成されたプレゼンテーションには空のスライドが 1 枚含まれます。 |
| [Presentation](presentation#constructor_1)(LoadOptions) | このコンストラクターは新しいプレゼンテーションを最初から作成します。作成されたプレゼンテーションには空のスライドが 1 枚含まれます。 |
| [Presentation](presentation#constructor_2)(Stream) | このコンストラクターは既存の Presentation を読み取る主な手段です。 |
| [Presentation](presentation#constructor_4)(string) | このコンストラクターはプレゼンテーションの内容を読み取る元ファイルのパスを取得します。 |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | このコンストラクターは既存の Presentation を読み取る主な手段です。 |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | このコンストラクターはプレゼンテーションの内容を読み取る元ファイルのパスを取得します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | プレゼンテーション内のすべてのカスタム データ パーツを返します。読み取り専用 [`ICustomXmlPart`](../icustomxmlpart)[]。 |
| [Audios](../../aspose.slides/presentation/audios) { get; } | プレゼンテーションに埋め込まれたすべてのオーディオ ファイルのコレクションを返します。読み取り専用 [`IAudioCollection`](../iaudiocollection)。 |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | コメント作成者のコレクションを返します。読み取り専用 [`ICommentAuthorCollection`](../icommentauthorcollection)。 |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | 日付と時刻を取得または設定します。デフォルトはこの Presentation オブジェクトの作成時刻です。読み書き可能 DateTime。 |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | プレゼンテーションのカスタム データを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | 図形の既定テキスト スタイルを返します。読み取り専用 [`ITextStyle`](../itextstyle)。 |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | プレゼンテーションに署名するために使用される署名のコレクションを返します。読み取り専用 [`IDigitalSignatureCollection`](../idigitalsignaturecollection)。 |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | 標準およびカスタム ドキュメント プロパティを含む DocumentProperties オブジェクトを返します。読み取り専用 [`IDocumentProperties`](../idocumentproperties)。 |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | プレゼンテーション内の最初のスライド番号を表します。 |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | フォント マネージャーを返します。読み取り専用 [`IFontsManager`](../ifontsmanager)。 |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | 現在の HeaderFooter マネージャーを返します。読み取り専用 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager)。 |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | すべてのプレゼンテーション スライド（マスタ、レイアウト、ノート スライドを除く）に含まれるすべてのハイパーリンクへの簡単なアクセスを提供します。読み取り専用 [`IHyperlinkQueries`](../ihyperlinkqueries)。 |
| [Images](../../aspose.slides/presentation/images) { get; } | プレゼンテーション内のすべての画像のコレクションを返します。読み取り専用 [`IImageCollection`](../iimagecollection)。 |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | プレゼンテーションで定義されているすべてのレイアウト スライドの一覧を返します。読み取り専用 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection)。 |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | ハンドアウト マスターマネージャーを返します。読み取り専用 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager)。 |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | ノート マスターマネージャーを返します。読み取り専用 [`IMasterNotesSlideManager`](../imasternotesslidemanager)。 |
| [Masters](../../aspose.slides/presentation/masters) { get; } | プレゼンテーションで定義されているすべてのマスタ スライドの一覧を返します。読み取り専用 [`IMasterSlideCollection`](../imasterslidecollection)。 |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | マスタ テーマを返します。読み取り専用 [`IMasterTheme`](../../aspose.slides.theme/imastertheme)。 |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | ノート スライド サイズ オブジェクトを返します。読み取り専用 [`INotesSize`](../inotessize)。 |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | このプレゼンテーションの権限マネージャーを取得します。読み取り専用 [`IProtectionManager`](../iprotectionmanager)。 |
| [Sections](../../aspose.slides/presentation/sections) { get; } | プレゼンテーションで定義されているすべてのスライド セクションの一覧を返します。読み取り専用 [`ISectionCollection`](../isectioncollection)。 |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | プレゼンテーション ドキュメントに適用されている感度ラベルのコレクションを返します。読み取り専用 [`ISensitivityLabelCollection`](../isensitivitylabelcollection)。 |
| [Slides](../../aspose.slides/presentation/slides) { get; } | プレゼンテーションで定義されているすべてのスライドの一覧を返します。読み取り専用 [`ISlideCollection`](../islidecollection)。 |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | プレゼンテーションのスライド ショー設定を返します。 |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | スライド サイズ オブジェクトを返します。読み取り専用 [`ISlideSize`](../islidesize)。 |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | プレゼンテーションがロードされた元の形式に関する情報を返します。読み取り専用 [`SourceFormat`](../sourceformat)。 |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | プレゼンテーションのマクロを含む VBA プロジェクトを取得または設定します。読み書き可能 [`IVbaProject`](../../aspose.slides.vba/ivbaproject)。 |
| [Videos](../../aspose.slides/presentation/videos) { get; } | プレゼンテーションに埋め込まれたすべてのビデオ ファイルのコレクションを返します。読み取り専用 [`IVideoCollection`](../ivideocollection)。 |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | プレゼンテーション全体のビュー プロパティを取得します。読み取り専用 [`IViewProperties`](../iviewproperties)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | この Presentation オブジェクトが使用しているすべてのリソースを解放します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | プレゼンテーションのすべてのスライドに対する Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | 指定されたスライドに対するサムネイル Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | 指定されたサイズでプレゼンテーションのすべてのスライドに対するサムネイル Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | カスタム スケーリングでプレゼンテーションのすべてのスライドに対するサムネイル Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 指定されたサイズで指定スライドに対するサムネイル Image オブジェクトを返します。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | カスタム スケーリングで指定スライドに対するサムネイル Image オブジェクトを返します。 |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Id により Slide、MasterSlide、または LayoutSlide を返します。 |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | 正規表現に一致したすべての箇所を指定された色でハイライトします。 |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | サンプル テキストに一致したすべての箇所を指定された色でハイライトします。 |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | サンプル テキストに一致したすべての箇所を指定された色でハイライトします。 |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | すべてのスライド内のすべての許容形状に対し、同一書式のランを結合します。 |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | 正規表現に一致したすべての箇所を指定された文字列に置換します。 |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 指定されたテキストのすべての出現箇所を別の指定テキストに置換します。 |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | プレゼンテーションのすべてのスライドを XAML マークアップを表すファイルのセットに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | 指定された形式でプレゼンテーションのすべてのスライドをストリームに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | 指定された形式でプレゼンテーションのすべてのスライドをファイルに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | ページ番号を保持したまま、指定されたスライドを指定形式でストリームに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | 指定された形式と追加オプションでプレゼンテーションのすべてのスライドをストリームに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | ページ番号を保持したまま、指定されたスライドを指定形式でファイルに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | ページ番号を保持したまま、指定されたスライドを指定形式でストリームに保存します。 |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | ページ番号を保持したまま、指定されたスライドを指定形式でファイルに保存します。 |

### 例

次の例は PowerPoint プレゼンテーションの作成方法を示します。

```csharp
[C#]
// プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化
using (Presentation presentation = new Presentation())
{
    // 最初のスライドを取得
    ISlide slide = presentation.Slides[0];
    // 種類が line のオートシェイプを追加
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// プレゼンテーション ファイルを保存
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

次の例は Presentation を開いて保存する方法を示します。

```csharp
[C#]
// Presentation でサポートされている任意のファイルを読み込みます（例：ppt、pptx、odp など）。
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