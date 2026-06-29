---
title: TiffOptions
second_title: Aspose.Sildes for .NET API リファレンス
description: プレゼンテーションを TIFF 形式で保存する方法を制御するオプションを提供します。
type: docs
weight: 4550
url: /ja/aspose.slides.export/tiffoptions/
---
## TiffOptions クラス

プレゼンテーションを TIFF 形式で保存する方法を制御するオプションを提供します。

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TiffOptions](tiffoptions)() | デフォルトコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは [`CompressionType`](./compressiontype) が CCITT4 または CCITT3 に設定されている場合にのみ適用されます。読み書き [`BlackWhiteConversionMode`](../blackwhiteconversionmode)。デフォルトは Default です。 |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | 圧縮タイプを指定します。読み書き [`TiffCompressionTypes`](../tiffcompressiontypes)。 |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。読み書き String。 |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | 水平解像度（dpi）を指定します。読み書き UInt32。 |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | 垂直解像度（dpi）を指定します。読み書き UInt32。 |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | グラデーションの視覚スタイルを取得または設定します。読み書き [`GradientStyle`](../../aspose.slides/gradientstyle)。 |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | 生成された TIFF 画像のサイズを指定します。デフォルト値は 0x0 で、これは生成画像のサイズがプレゼンテーションのスライドサイズに基づいて計算されることを意味します。読み書き Size。 |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。読み取り専用 [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | 生成された画像のピクセル形式を指定します。読み書き [`ImagePixelFormat`](../imagepixelformat)。 |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | 進捗更新（パーセンテージ）を保存するためのコールバックオブジェクトを表します。[`IProgressCallback`](../../aspose.slides/iprogresscallback) を参照してください。 |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは `false` です。 |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | プレゼンテーションの保存時に JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。読み書き Boolean。デフォルト値は **false** です。 |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [`ISlidesLayoutOptions`](../islideslayoutoptions)。 |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | 警告を受け取り、読み込みプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。読み書き [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)。 |

### 例

次の例は、デフォルトサイズで PowerPoint を TIFF に変換する方法を示します。

```csharp
[C#]
// プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // プレゼンテーションを TIFF ドキュメントとして保存します
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

次の例は、カスタムサイズで PowerPoint を TIFF に変換する方法を示します。

```csharp
[C#]
// プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // TiffOptions クラスをインスタンス化します
    TiffOptions opts = new TiffOptions();
    // 圧縮タイプを設定します
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // 圧縮タイプ
    // Default - デフォルトの圧縮方式 (LZW) を指定します。
    // None - 圧縮なしを指定します。
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // 深度は圧縮タイプに依存し、手動で設定できません。
    // 解像度単位は常に “2”(dots per inch) です。
    // 画像 DPI を設定します
    opts.DpiX = 200;
    opts.DpiY = 100;
    // 画像サイズを設定します
    opts.ImageSize = new Size(1728, 1078);
    // 指定された画像サイズでプレゼンテーションを TIFF として保存します
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

次の例は、カスタム画像ピクセル形式で PowerPoint を TIFF に変換する方法を示します。

```csharp
[C#]
// プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat には次の値が含まれます（ドキュメントから確認できます）:
    Format1bppIndexed; // 1 ビット/ピクセル、インデックス形式です。
    Format4bppIndexed; // 4 ビット/ピクセル、インデックス形式です。
    Format8bppIndexed; // 8 ビット/ピクセル、インデックス形式です。
    Format24bppRgb; // 24 ビット/ピクセル、RGB 形式です。
    Format32bppArgb; // 32 ビット/ピクセル、ARGB 形式です。
    */
    // 指定された画像サイズでプレゼンテーションを TIFF として保存します
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### 参照

* クラス [SaveOptions](../saveoptions)
* インターフェイス [ITiffOptions](../itiffoptions)
* 名前空間 [Aspose.Slides.Export](../../aspose.slides.export)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->