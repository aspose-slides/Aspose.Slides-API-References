---
title: PdfOptions
second_title: Aspose.Sildes for .NET API リファレンス
description: プレゼンテーションを Pdf 形式で保存する方法を制御するオプションを提供します。
type: docs
weight: 4330
url: /ja/aspose.slides.export/pdfoptions/
---
## PdfOptions クラス

プレゼンテーションをPdf形式で保存する方法を制御するオプションを提供します。

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfOptions](pdfoptions)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | ドキュメントがユーザーアクセスで開かれたときに付与されるアクセス許可を指定するフラグのセットが含まれています。参照してください [`PdfAccessPermissions`](../pdfaccesspermissions)。 |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Aspose.Slides が共通とみなすフォントファミリのユーザー定義名の配列を取得または設定します。読み書き可能な String[]。 |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | `true` の場合、指定された透過色を画像に適用します。 |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | 各画像に対して最も効果的な圧縮（デフォルトではなく）を自動的に選択すべきかを示します。Boolean.true に設定すると、プレゼンテーション内のすべての画像について最適な圧縮アルゴリズムが選択され、結果の PDF 文書のサイズが小さくなります。最適な画像圧縮率の選択は計算コストが高く、追加の RAM が必要であり、このオプションはデフォルトで Boolean.false です。 |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | 生成された PDF 文書の目的となる準拠レベル。読み書き可能な [`PdfCompliance`](../pdfcompliance)。 |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。読み書き可能な String。 |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | 各スライドの周囲に黒いフレームを描画する場合は true。読み書き可能な Boolean。 |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | フォントのすべての文字を埋め込むか、使用されたサブセットのみを埋め込むかを決定します。読み書き可能な Boolean。 |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Aspose.Slides が ASCII (33..127 のコード範囲) のテキスト用に共通フォントを埋め込むかどうかを決定します。127 を超える文字コードのフォントは常に埋め込まれます。共通フォントリストには PDF の基本 14 フォントと追加のユーザー指定フォントが含まれます。読み書き可能な Boolean。 |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | グラデーションのビジュアルスタイルを取得または設定します。読み書き可能な [`GradientStyle`](../../aspose.slides/gradientstyle)。 |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | 画像の透過色を取得または設定します。 |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | プレゼンテーションからすべての OLE データを結果の PDF に埋め込みファイルに変換する場合は true。読み書き可能な Boolean。 |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。読み取り専用の [`IInkOptions`](../iinkoptions)。 |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | PDF 文書内の JPEG 画像の品質を決定する値を取得または設定します。読み書き可能な Byte。 |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | PDF 文書を保護するためのユーザーパスワードを設定します。読み書き可能な String。 |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | 保存の進捗状況をパーセンテージで更新するコールバックオブジェクトを表します。[`IProgressCallback`](../../aspose.slides/iprogresscallback) を参照してください。 |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | フォントが太字スタイルをサポートしていない場合に、テキストをビットマップとしてラスタライズし PDF に保存するかどうかを示します。この方法は特定のフォントに対して結果の PDF のテキスト品質を向上させることがあります。読み書き可能な Boolean。 |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true。読み書き可能な Boolean。 |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは `false` です。 |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。読み書き可能な Boolean。デフォルト値は **false** です。 |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します。[`ISlidesLayoutOptions`](../islideslayoutoptions)。 |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | PDF 文書内の画像の解像度を決定する値を取得または設定します。 |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | ドキュメント内のすべてのテキストコンテンツに使用される圧縮タイプを指定します。読み書き可能な [`PdfTextCompression`](../pdftextcompression)。 |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | 警告を受け取り、ロード処理を継続するか中止するかを決定するオブジェクトを取得または設定します。読み書き可能な [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)。 |

### 例

次の例は、カスタムオプションを使用して PowerPoint を PDF に変換する方法を示します。

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions クラスのインスタンスを作成します
	PdfOptions pdfOptions = new PdfOptions();
	// Jpeg の品質を設定します
	pdfOptions.JpegQuality = 90;
	// メタファイルの動作を設定します
	pdfOptions.SaveMetafilesAsPng = true;
	// テキスト圧縮レベルを設定します
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// PDF 標準を定義します
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// プレゼンテーションを PDF として保存します
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

次の例は、非表示スライドを含めて PowerPoint を PDF に変換する方法を示します。

```csharp
[C#]
// PowerPoint ファイルを表す Presentation クラスのインスタンスを作成します
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions クラスのインスタンスを作成します
	PdfOptions pdfOptions = new PdfOptions();
	// 非表示スライドを追加します
	pdfOptions.ShowHiddenSlides = true;
	// プレゼンテーションを PDF として保存します
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

次の例は、パスワードで保護された PDF に PowerPoint を変換する方法を示します。

```csharp
[C#]
// PowerPoint ファイルを表す Presentation オブジェクトのインスタンスを作成します
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// PdfOptions クラスのインスタンスを作成します
	PdfOptions pdfOptions = new PdfOptions();
	// PDF のパスワードとアクセス許可を設定します
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// プレゼンテーションを PDF として保存します
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

次の例は、ノート付きで PowerPoint を PDF に変換する方法を示します。

```csharp
[C#]
// プレゼンテーション ファイルを表す Presentation オブジェクトを作成します
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// スライドのタイプとサイズを設定します
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### 参照

* クラス [SaveOptions](../saveoptions)
* インターフェイス [IPdfOptions](../ipdfoptions)
* 名前空間 [Aspose.Slides.Export](../../aspose.slides.export)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->