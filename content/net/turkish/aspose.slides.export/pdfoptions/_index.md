---
title: PdfOptions
second_title: Aspose.Sildes for .NET API Referansı
description: Bir sunumun PDF formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.
type: docs
weight: 4330
url: /tr/aspose.slides.export/pdfoptions/
---
## PdfOptions sınıfı

Bir sunumun PDF formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PdfOptions](pdfoptions)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Belge, kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bayraklar kümesini içerir. [`PdfAccessPermissions`](../pdfaccesspermissions) bakınız. |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Aspose.Slides'in ortak olarak kabul etmesi gereken, kullanıcı tarafından tanımlanmış yazı tipi ailesi adlarının bir dizisini döndürür veya ayarlar. Read/write String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | `true` ise belirtilen saydam rengi bir görüntüye uygular. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Her görüntü için varsayılanın yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmeyeceğini belirler. Boolean.true olarak ayarlanırsa sunumdaki her görüntü için en uygun sıkıştırma algoritması seçilir ve bu, ortaya çıkan PDF belgesinin daha küçük olmasını sağlar. En iyi görüntü sıkıştırma oranı seçimi işlem açısından maliyetlidir ve ek RAM gerektirir; bu seçenek varsayılan olarak Boolean.false’tur. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Oluşturulan PDF belgesi için istenen uyumluluk seviyesi. Read/write [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Kaynak yazı tipi bulunamadığında kullanılacak yazı tipini döndürür veya ayarlar. Read-write String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | `true` ise her slaytın etrafına siyah çerçeve çizer. Read/write Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. Read/write Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Aspose.Slides'in ASCII (33..127 kod aralığı) metin için ortak yazı tiplerini gömüp gömmeyeceğini belirler. 127’den büyük karakter kodları için yazı tipleri her zaman gömülür. Ortak yazı tipleri listesi PDF’in temel 14 yazı tipini ve ek olarak kullanıcı tarafından belirtilen yazı tiplerini içerir. Read/write Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gradyanın görsel stilini döndürür veya ayarlar. Read/write [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Görüntünün saydam rengini alır veya ayarlar. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | `true` ise sunumdan gelen tüm OLE verilerini sonuç PDF’te gömülü dosyalara dönüştürür. Read/write Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Read-only [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. Read/write Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | PDF belgesini korumak için kullanıcı parolasını ayarlar. Read/write String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Kaydetme ilerleme güncellemelerini yüzde olarak bildiren bir geri çağırma nesnesini temsil eder. [`IProgressCallback`](../../aspose.slides/iprogresscallback) bakınız. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF’e kaydedilip kaydedilmeyeceğini gösterir. Bu yöntem belirli yazı tiplerinde sonuç PDF’de metin kalitesini artırabilir. Read/write Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | `true` ise bir sunumda kullanılan tüm metafile’ları PNG görüntülerine dönüştürür. Read/write Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Sunumu kaydederken JavaScript çağrıları içeren bağlantıların atlanıp atlanmayacağını belirler. Read/write Boolean. Varsayılan değer **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Belgedeki tüm metin içeriği için kullanılacak sıkıştırma türünü belirler. Read/write [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. Read/write [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Örnekler

The following example shows how to convert PowerPoint to PDF with custom options.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions sınıfını örnekler
	PdfOptions pdfOptions = new PdfOptions();
	// Jpeg kalitesini ayarlar
	pdfOptions.JpegQuality = 90;
	// Metafile'ların davranışını ayarlar
	pdfOptions.SaveMetafilesAsPng = true;
	// Metin sıkıştırma seviyesini ayarlar
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// PDF standardını tanımlar
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Sunumu PDF olarak kaydeder
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

The following example shows how to convert PowerPoint to PDF with hidden slides.

```csharp
[C#]
// Bir PowerPoint dosyasını temsil eden Presentation sınıfını örnekler
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions sınıfını örnekler
	PdfOptions pdfOptions = new PdfOptions();
	// Gizli slaytları ekler
	pdfOptions.ShowHiddenSlides = true;
	// Sunumu PDF olarak kaydeder
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

The following example shows how to convert PowerPoint to password protected PDF.

```csharp
[C#]
// Bir PowerPoint dosyasını temsil eden Presentation nesnesini örnekler
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// PdfOptions sınıfını örnekler
	PdfOptions pdfOptions = new PdfOptions();
	// PDF parolasını ve erişim izinlerini ayarlar
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Sunumu PDF olarak kaydeder
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

The following example shows how to convert PowerPoint to PDF with notes.

```csharp
[C#]
// Bir sunum dosyasını temsil eden Presentation nesnesini örnekler
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Slayt Türünü ve Boyutunu Ayarlama
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Diğer Bağlantılar

* sınıf [SaveOptions](../saveoptions)
* arayüz [IPdfOptions](../ipdfoptions)
* ad alanı [Aspose.Slides.Export](../../aspose.slides.export)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->