---
title: PdfOptions
second_title: Aspose.Sildes için .NET API Referansı
description: Sunumun PDF formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
weight: 4310
url: /tr/aspose.slides.export/pdfoptions/
---
## PdfOptions sınıfı

Bir sunumun PDF biçiminde kaydedilmesini kontrol eden seçenekleri sağlar.

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
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir dizi bayrak içerir. Bkz. [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Aspose.Slides'in ortak olarak kabul edeceği, kullanıcı tanımlı yazı tipi ailelerinin adlarını içeren bir dizi döndürür veya ayarlar. Okunur/Yazılır String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Belirtilen şeffaf rengi bir görüntüye uygular, eğer `true` ise. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Her görüntü için en etkili sıkıştırmanın (varsayılanın yerine) otomatik olarak seçilip seçilmeyeceğini gösterir. Boolean.true olarak ayarlanırsa, sunumdaki her görüntü için en uygun sıkıştırma algoritması seçilir ve bu da ortaya çıkan PDF belgesinin daha küçük olmasını sağlar. En iyi görüntü sıkıştırma oranının seçilmesi hesaplama açısından maliyetlidir ve ek RAM gerektirir; bu seçenek varsayılan olarak Boolean.false'tur. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Oluşturulan PDF belgesi için istenen uyumluluk seviyesi. Okunur/Yazılır [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Kaynak yazı tipi bulunamadığında kullanılacak yazı tipini döndürür veya ayarlar. Okunur/Yazılır String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | Her slaytın etrafına siyah çerçeve çizmek için true. Okunur/Yazılır Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. Okunur/Yazılır Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Aspose.Slides'in ASCII (33..127 kod aralığı) metin için ortak yazı tiplerini gömeceğini belirler. 127'den büyük karakter kodları için yazı tipleri her zaman gömülür. Ortak yazı tipleri listesi PDF'in temel 14 yazı tipini ve ek olarak kullanıcı tarafından belirtilen yazı tiplerini içerir. Okunur/Yazılır Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gradyanın görsel stilini döndürür veya ayarlar. Okunur/Yazılır [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Görüntünün şeffaf rengini alır veya ayarlar. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | Sunumdaki tüm OLE verilerini oluşan PDF'de gömülü dosyalara dönüştürmek için true. Okunur/Yazılır Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Dışa aktarılan belgede Kalem nesnelerinin görünümünü kontrol eden seçenekler sağlar. Sadece okuma [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | PDF belgesindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. Okunur/Yazılır Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | PDF belgesini korumak için kullanıcı parolasını ayarlar. Okunur/Yazılır String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Kaydetme ilerleme güncellemelerini yüzde olarak bildiren bir geri arama nesnesini temsil eder. Bkz. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. Bu yaklaşım belirli yazı tiplerinde ortaya çıkan PDF'deki metin kalitesini artırabilir. Okunur/Yazılır Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | Sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için true. Okunur/Yazılır Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Sunumu kaydederken JavaScript çağrıları içeren köprülerin atlanıp atlanmayacağını belirtir. Okunur/Yazılır Boolean. Varsayılan değer **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Belgedeki tüm metin içeriği için kullanılacak sıkıştırma türünü belirtir. Okunur/Yazılır [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. Okunur/Yazılır [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Örnekler

Aşağıdaki örnek, PowerPoint'i özel seçeneklerle PDF'e dönüştürmeyi gösterir.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions sınıfının bir örneğini oluşturur
	PdfOptions pdfOptions = new PdfOptions();
	// Jpeg kalitesini ayarlar
	pdfOptions.JpegQuality = 90;
	// Metafile davranışını ayarlar
	pdfOptions.SaveMetafilesAsPng = true;
	// Metin sıkıştırma seviyesini ayarlar
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// PDF standardını tanımlar
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Sunumu PDF olarak kaydeder
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Aşağıdaki örnek, PowerPoint'i gizli slaytlarla PDF'e dönüştürmeyi gösterir.

```csharp
[C#]
// PowerPoint dosyasını temsil eden bir Presentation sınıfının örneği oluşturulur
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions sınıfının bir örneği oluşturulur
	PdfOptions pdfOptions = new PdfOptions();
	// Gizli slaytlar eklenir
	pdfOptions.ShowHiddenSlides = true;
	// Sunum PDF olarak kaydedilir
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Aşağıdaki örnek, PowerPoint'i parola korumalı PDF'e dönüştürmeyi gösterir.

```csharp
[C#]
// PowerPoint dosyasını temsil eden bir Presentation nesnesi oluşturur
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// PdfOptions sınıfının bir örneğini oluşturur
	PdfOptions pdfOptions = new PdfOptions();
	// PDF şifresi ve erişim izinlerini ayarlar
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Sunumu PDF olarak kaydeder
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Aşağıdaki örnek, PowerPoint'i notlarla PDF'e dönüştürmeyi gösterir.

```csharp
[C#]
// Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Slayt tipi ve boyutunu ayarlar
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Ayrıca Bakınız

* sınıf [SaveOptions](../saveoptions)
* arayüz [IPdfOptions](../ipdfoptions)
* ad alanı [Aspose.Slides.Export](../../aspose.slides.export)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->