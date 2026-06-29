---
title: PdfOptions
second_title: Aspose.Sildes の .NET API リファレンス
description: プレゼンテーションが PDF 形式で保存される方法を制御するオプションを提供します。
type: docs
weight: 4310
url: /ja/aspose.slides.export/pdfoptions/
---
## PdfOptions クラス

プレゼンテーションが Pdf 形式で保存される方法を制御するオプションを提供します。

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfOptions](pdfoptions)() | デフォルト コンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | アクセス許可がユーザーアクセスでドキュメントを開く際に付与されるべきフラグのセットを含みます。[`PdfAccessPermissions`](../pdfaccesspermissions) を参照してください。 |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Aspose.Slides が共通と見なすべきフォント ファミリのユーザー定義名の配列を取得または設定します。読み取り/書き込み String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | `true` の場合、指定された透過色を画像に適用します。 |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | 各画像に対してデフォルトではなく最も効果的な圧縮（最高の圧縮）を自動的に選択すべきかを示します。Boolean.true に設定すると、プレゼンテーション内のすべての画像に対して最適な圧縮アルゴリズムが選択され、結果として PDF ドキュメントのサイズが小さくなります。最適な画像圧縮率の選択は計算コストが高く、追加の RAM が必要であり、既定では Boolean.false です。 |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | 生成された PDF ドキュメントの目的とするコンプライアンス レベルです。読み取り/書き込み [`PdfCompliance`](../pdfcompliance)。 |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | 元のフォントが見つからない場合に使用されるフォントを取得または設定します。読み取り/書き込み String。 |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True を設定すると、各スライドの周囲に黒いフレームが描画されます。読み取り/書き込み Boolean。 |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | フォントのすべての文字を埋め込むか、使用されたサブセットのみを埋め込むかを決定します。読み取り/書き込み Boolean。 |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Aspose.Slides が ASCII（コード範囲 33..127）のテキスト用に共通フォントを埋め込むかどうかを決定します。コード 127 より大きい文字コードのフォントは常に埋め込まれます。共通フォントのリストには PDF のベース 14 フォントと、ユーザーが指定した追加フォントが含まれます。読み取り/書き込み Boolean。 |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | グラデーションの視覚スタイルを取得または設定します。読み取り/書き込み [`GradientStyle`](../../aspose.slides/gradientstyle)。 |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | 画像の透過色を取得または設定します。 |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True を設定すると、プレゼンテーション内のすべての OLE データが結果の PDF に埋め込みファイルとして変換されます。読み取り/書き込み Boolean。 |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | エクスポートされたドキュメント内のインク オブジェクトの外観を制御するオプションを提供します。読み取り専用 [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。読み取り/書き込み Byte。 |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | PDF ドキュメントを保護するためのユーザーパスワードを設定します。読み取り/書き込み String。 |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | 保存進捗のパーセンテージ更新のためのコールバック オブジェクトを表します。[`IProgressCallback`](../../aspose.slides/iprogresscallback) を参照してください。 |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | フォントが太字スタイルをサポートしない場合、テキストをビットマップとしてラスタライズし PDF に保存すべきかどうかを示します。このアプローチは特定のフォントで結果の PDF のテキスト品質を向上させることができます。読み取り/書き込み Boolean。 |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True を設定すると、プレゼンテーションで使用されるすべてのメタファイルが PNG 画像に変換されます。読み取り/書き込み Boolean。 |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。既定は `false` です。 |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。読み取り/書き込み Boolean。デフォルト値は **false** です。 |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します。[`ISlidesLayoutOptions`](../islideslayoutoptions)。 |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | PDF ドキュメント内の画像解像度を決定する値を取得または設定します。 |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | ドキュメント内のすべてのテキスト コンテンツに使用される圧縮タイプを指定します。読み取り/書き込み [`PdfTextCompression`](../pdftextcompression)。 |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | 警告を受け取り、ロード プロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。読み取り/書き込み [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)。 |

### 例

次の例では、カスタム オプションを使用して PowerPoint を PDF に変換する方法を示します。

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

次の例では、非表示スライドを含めて PowerPoint を PDF に変換する方法を示します。

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

次の例では、パスワードで保護された PDF に PowerPoint を変換する方法を示します。

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

次の例では、ノート付きで PowerPoint を PDF に変換する方法を示します。

```csharp
[C#]
// プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
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