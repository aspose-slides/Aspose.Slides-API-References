---
title: PdfOptions
second_title: Aspose.Sildes for .NET API 參考
description: 提供控制簡報以 Pdf 格式儲存方式的選項。
type: docs
weight: 4330
url: /zh-hant/aspose.slides.export/pdfoptions/
---
## PdfOptions 類別

提供用於控制將簡報以 Pdf 格式儲存時之選項。

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## 建構函式

| 名稱 | 說明 |
| --- | --- |
| [PdfOptions](pdfoptions)() | 預設建構函式。 |

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | 包含一組旗標，指定在使用者存取文件時應授予哪些存取權限。請參閱 [`PdfAccessPermissions`](../pdfaccesspermissions)。 |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | 取得或設定使用者自訂的字型系列名稱陣列，Aspose.Slides 將視為共用字型。讀寫 String[]。 |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | 如果為 `true`，則將指定的透明顏色套用至影像。 |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | 指示是否應自動為每個影像選擇最有效的壓縮（而非預設壓縮）。若設定為 Boolean.true，則會為簡報中的每張影像選擇最適當的壓縮演算法，從而減小產生的 PDF 文件大小。最佳影像壓縮比例的選擇計算成本高且會佔用額外的記憶體，預設為 Boolean.false。 |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | 產生的 PDF 文件所需的符合等級。讀寫 [`PdfCompliance`](../pdfcompliance)。 |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | 取得或設定當找不到來源字型時所使用的字型。讀寫 String。 |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | 若為 true，則在每張投影片周圍繪製黑色框線。讀寫 Boolean。 |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | 決定是否應嵌入字型的全部字元或僅嵌入使用的子集合。讀寫 Boolean。 |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | 決定 Aspose.Slides 是否為 ASCII（33..127 代碼範圍）的文字嵌入常用字型。代碼大於 127 的字元字型始終會嵌入。常用字型清單包括 PDF 的基礎 14 種字型及使用者指定的其他字型。讀寫 Boolean。 |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | 取得或設定漸層的視覺樣式。讀寫 [`GradientStyle`](../../aspose.slides/gradientstyle)。 |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | 取得或設定影像的透明顏色。 |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | 若為 true，則將簡報中的所有 OLE 資料轉換為產生的 PDF 中的內嵌檔案。讀寫 Boolean。 |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | 提供控制匯出文件中墨跡物件外觀的選項。唯讀 [`IInkOptions`](../iinkoptions)。 |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | 取得或設定決定 PDF 文件內 JPEG 影像品質的值。讀寫 Byte。 |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | 設定使用者密碼以保護 PDF 文件。讀寫 String。 |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | 代表以百分比形式提供儲存進度更新的回呼物件。請參閱 [`IProgressCallback`](../../aspose.slides/iprogresscallback)。 |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | 指示當字型不支援粗體樣式時，是否將文字光柵化為點陣圖並儲存至 PDF。此方式可提升某些字型在產生的 PDF 中的文字品質。讀寫 Boolean。 |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | 若為 true，則將簡報中使用的所有中繼檔轉換為 PNG 影像。讀寫 Boolean。 |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | 指定產生的文件是否應包含隱藏投影片。預設為 `false`。 |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | 指定在儲存簡報時是否跳過包含 JavaScript 呼叫的超連結。讀寫 Boolean。預設值為 **false**。 |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | 取得或設定匯出簡報時投影片在頁面上的排列模式 [`ISlidesLayoutOptions`](../islideslayoutoptions)。 |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | 取得或設定決定 PDF 文件內影像解析度的值。 |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | 指定文件中所有文字內容使用的壓縮類型。讀寫 [`PdfTextCompression`](../pdftextcompression)。 |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | 取得或設定接收警告並決定載入過程是否繼續或中止的物件。讀寫 [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)。 |

### 範例

以下範例說明如何使用自訂選項將 PowerPoint 轉換為 PDF。

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// 初始化 PdfOptions 類別
	PdfOptions pdfOptions = new PdfOptions();
	// 設定 JPEG 品質
	pdfOptions.JpegQuality = 90;
	// 設定中繼檔的行為
	pdfOptions.SaveMetafilesAsPng = true;
	// 設定文字壓縮等級
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// 定義 PDF 標準
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// 將簡報儲存為 PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

以下範例說明如何在包含隱藏投影片的情況下將 PowerPoint 轉換為 PDF。

```csharp
[C#]
// 實例化一個代表 PowerPoint 檔案的 Presentation 類別
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// 實例化 PdfOptions 類別
	PdfOptions pdfOptions = new PdfOptions();
	// 加入隱藏投影片
	pdfOptions.ShowHiddenSlides = true;
	// 將簡報儲存為 PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

以下範例說明如何將 PowerPoint 轉換為受密碼保護的 PDF。

```csharp
[C#]
// Instantiates a Presentation object that represents a PowerPoint file
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Instantiates the PdfOptions class
	PdfOptions pdfOptions = new PdfOptions();
	// Sets PDF password and access permissions
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Saves the presentation as a PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

以下範例說明如何將 PowerPoint 轉換為包含筆記的 PDF。

```csharp
[C#]
// 實例化一個代表簡報檔案的 Presentation 物件
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// 設定投影片類型與大小
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### 另請參閱

* 類別 [SaveOptions](../saveoptions)
* 介面 [IPdfOptions](../ipdfoptions)
* 命名空間 [Aspose.Slides.Export](../../aspose.slides.export)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->