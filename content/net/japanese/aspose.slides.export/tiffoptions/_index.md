---
title: TiffOptions
second_title: Aspose.Sildes for .NET API リファレンス
description: プレゼンテーションがTIFF形式で保存される方法を制御するオプションを提供します。
type: docs
weight: 4570
url: /ja/aspose.slides.export/tiffoptions/
---
## TiffOptions クラス

Provides options that control how a presentation is saved in TIFF format.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TiffOptions](tiffoptions)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは [`CompressionType`](./compressiontype) が CCITT4 または CCITT3 に設定されている場合にのみ適用されます。読み取り/書き込み [`BlackWhiteConversionMode`](../blackwhiteconversionmode)。デフォルトは Default です。 |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | 圧縮タイプを指定します。読み取り/書き込み [`TiffCompressionTypes`](../tiffcompressiontypes)。 |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。読み取り/書き込み String。 |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | 水平方向の解像度（ドット/インチ）を指定します。読み取り/書き込み UInt32。 |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | 垂直方向の解像度（ドット/インチ）を指定します。読み取り/書き込み UInt32。 |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | グラデーションの視覚スタイルを取得または設定します。読み取り/書き込み [`GradientStyle`](../../aspose.slides/gradientstyle)。 |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | 生成される TIFF 画像のサイズを指定します。デフォルト値は 0x0 で、これは生成画像のサイズがプレゼンテーションのスライドサイズに基づいて計算されることを意味します。読み取り/書き込み Size。 |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | エクスポートされたドキュメント内のインクオブジェクトの外観を制御するオプションを提供します。読み取り専用 [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | 生成された画像のピクセル形式を指定します。読み取り/書き込み [`ImagePixelFormat`](../imagepixelformat)。 |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | 保存進捗をパーセンテージで更新するコールバックオブジェクトを表します。[`IProgressCallback`](../../aspose.slides/iprogresscallback) を参照してください。 |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは `false` です。 |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | プレゼンテーションを保存する際に JavaScript 呼び出しを持つハイパーリンクをスキップするかどうかを指定します。読み取り/書き込み Boolean。デフォルト値は **false** です。 |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [`ISlidesLayoutOptions`](../islideslayoutoptions)。 |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | 警告を受け取り、ロードプロセスを続行するか中止するかを決定するオブジェクトを取得または設定します。読み取り/書き込み [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)。 |

### 例

以下の例は、デフォルトサイズで PowerPoint を TIFF に変換する方法を示します。

```csharp
[C#]
// プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化する
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // プレゼンテーションを TIFF ドキュメントとして保存する
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

以下の例は、カスタムサイズで PowerPoint を TIFF に変換する方法を示します。

```csharp
[C#]
// Presentation ファイルを表す Presentation オブジェクトをインスタンス化します
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // TiffOptions クラスをインスタンス化する
    TiffOptions opts = new TiffOptions();
    // 圧縮タイプを設定する
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // 圧縮タイプ
    // Default - デフォルトの圧縮方式 (LZW) を指定します。
    // None - 圧縮しないことを指定します。
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Depth は圧縮タイプに依存し、手動で設定できません。
    // 解像度単位は常に “2”(ドット/インチ) に等しいです。
    // 画像 DPI を設定する
    opts.DpiX = 200;
    opts.DpiY = 100;
    // 画像サイズを設定する
    opts.ImageSize = new Size(1728, 1078);
    // 指定した画像サイズでプレゼンテーションを TIFF に保存する
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

以下の例は、カスタム画像ピクセル形式で PowerPoint を TIFF に変換する方法を示します。

```csharp
[C#]
// Presentation ファイルを表す Presentation オブジェクトをインスタンス化する
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat には次の値が含まれます (ドキュメントから確認できるように):
    Format1bppIndexed; // 1 ビット/ピクセル、インデックス付き。
    Format4bppIndexed; // 4 ビット/ピクセル、インデックス付き。
    Format8bppIndexed; // 8 ビット/ピクセル、インデックス付き。
    Format24bppRgb; // 24 ビット/ピクセル、RGB。
    Format32bppArgb; // 32 ビット/ピクセル、ARGB。
    */
    // 指定した画像サイズでプレゼンテーションを TIFF に保存する
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### 関連項目

* クラス [SaveOptions](../saveoptions)
* インターフェイス [ITiffOptions](../itiffoptions)
* 名前空間 [Aspose.Slides.Export](../../aspose.slides.export)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->