---
title: PdfOptions
second_title: Aspose.Sildes の .NET API リファレンス
description: プレゼンテーションが PDF 形式で保存される方法を制御するオプションを提供します。
type: docs
weight: 4350
url: /ja/aspose.slides.export/pdfoptions/
---
## PdfOptions クラス

Provides options that control how a presentation is saved in Pdf format.

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
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | ドキュメントがユーザーアクセスで開かれたときに付与すべきアクセス許可を指定するフラグの集合を含みます。[`PdfAccessPermissions`](../pdfaccesspermissions) を参照してください。 |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Aspose.Slides が共通とみなすフォント ファミリのユーザー定義名の配列を取得または設定します。読み書き String[]。 |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | `true` の場合、指定された透過色を画像に適用します。 |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | 各画像に対してデフォルトの代わりに最も効果的な圧縮を自動的に選択すべきかどうかを示します。Boolean.true に設定すると、プレゼンテーション内のすべての画像に対して最適な圧縮アルゴリズムが選択され、結果として生成される PDF ドキュメントのサイズが小さくなります。最適な画像圧縮率の選択は計算コストが高く、追加の RAM を必要とし、このオプションはデフォルトで Boolean.false です。 |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | 生成された PDF ドキュメントの目的とする適合レベルです。読み書き [`PdfCompliance`](../pdfcompliance)。 |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | 元のフォントが見つからない場合に使用するフォントを取得または設定します。読み書き String。 |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | 各スライドの周囲に黒いフレームを描画する場合は true に設定します。読み書き Boolean。 |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | フォントのすべての文字を埋め込むか、使用されたサブセットのみを埋め込むかを決定します。読み書き Boolean。 |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | ASCII（33..127 のコード範囲）テキストに対して Aspose.Slides が共通フォントを埋め込むかどうかを決定します。コード 127 を超える文字のフォントは常に埋め込まれます。共通フォントリストには PDF の基本 14 フォントとユーザーが指定した追加フォントが含まれます。読み書き Boolean。 |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | グラデーションの視覚スタイルを取得または設定します。読み書き [`GradientStyle`](../../aspose.slides/gradientstyle)。 |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | 画像の透過色を取得または設定します。 |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | プレゼンテーションのすべての OLE データを結果の PDF に埋め込みファイルに変換する場合は true に設定します。読み書き Boolean。 |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | エクスポートされたドキュメント内のインク オブジェクトの外観を制御するオプションを提供します。読み取り専用 [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。読み書き Byte。 |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | PDF ドキュメントを保護するためのユーザーパスワードを設定します。読み書き String。 |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | 保存の進捗更新（パーセンテージ）を受け取るコールバック オブジェクトを表します。[`IProgressCallback`](../../aspose.slides/iprogresscallback) を参照してください。 |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | フォントが太字スタイルをサポートしていない場合に、テキストをビットマップとしてラスタライズし PDF に保存するかどうかを示します。この方法は特定のフォントで結果の PDF のテキスト品質を向上させることがあります。読み書き Boolean。 |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true に設定します。読み書き Boolean。 |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは `false` です。 |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | プレゼンテーションを保存する際に JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。読み書き Boolean。デフォルト値は **false** です。 |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [`ISlidesLayoutOptions`](../islideslayoutoptions)。 |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | PDF ドキュメント内の画像解像度を決定する値を取得または設定します。 |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | ドキュメント内のすべてのテキストコンテンツに使用する圧縮タイプを指定します。読み書き [`PdfTextCompression`](../pdftextcompression)。 |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | 警告を受け取り、ロードプロセスを継続するか中止するかを判断するオブジェクトを取得または設定します。読み書き [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)。 |

### 例

以下の例は、カスタム オプションを使用して PowerPoint を PDF に変換する方法を示しています。

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions クラスのインスタンス化
	PdfOptions pdfOptions = new PdfOptions();
	// Jpeg の品質を設定
	pdfOptions.JpegQuality = 90;
	// メタファイルの動作を設定
	pdfOptions.SaveMetafilesAsPng = true;
	// テキスト圧縮レベルを設定
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// PDF 標準を定義
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// プレゼンテーションを PDF として保存
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

以下の例は、非表示スライドを含めて PowerPoint を PDF に変換する方法を示しています。

```csharp
[C#]
// PowerPoint ファイルを表す Presentation クラスのインスタンス化
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions クラスのインスタンス化
	PdfOptions pdfOptions = new PdfOptions();
	// 非表示スライドを追加
	pdfOptions.ShowHiddenSlides = true;
	// プレゼンテーションを PDF として保存
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

以下の例は、パスワードで保護された PDF に PowerPoint を変換する方法を示しています。

```csharp
[C#]
// PowerPoint ファイルを表す Presentation オブジェクトのインスタンス化
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// PdfOptions クラスのインスタンス化
	PdfOptions pdfOptions = new PdfOptions();
	// PDF のパスワードとアクセス許可を設定
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// プレゼンテーションを PDF として保存
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

以下の例は、ノート付きで PowerPoint を PDF に変換する方法を示しています。

```csharp
[C#]
// プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// スライドタイプとサイズを設定
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