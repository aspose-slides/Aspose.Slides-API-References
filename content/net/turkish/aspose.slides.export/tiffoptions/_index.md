---
title: TiffOptions
second_title: Aspose.Sildes for .NET API Referansı
description: Bir sunumun TIFF formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.
type: docs
weight: 4570
url: /tr/aspose.slides.export/tiffoptions/
---
## TiffOptions sınıfı

Bir sunumun TIFF formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [TiffOptions](tiffoptions)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Renkli bir görüntüyü siyah beyaz bir görüntüye dönüştürmek için kullanılan algoritmayı belirtir. Bu seçenek yalnızca [`CompressionType`](./compressiontype) CCITT4 veya CCITT3 olarak ayarlandığında uygulanır. Varsayılan, Default'tır. Read/write [`BlackWhiteConversionMode`](../blackwhiteconversionmode). |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Sıkıştırma türünü belirtir. Read/write [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar. Read-write String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | İnç başına nokta cinsinden yatay çözünürlüğü belirtir. Read/write UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | İnç başına nokta cinsinden dikey çözünürlüğü belirtir. Read/write UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gradyanın görsel stilini döndürür veya ayarlar. Read/write [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Oluşturulan TIFF görüntüsünün boyutunu belirtir. Varsayılan değer 0x0'dır; bu, oluşturulan görüntü boyutlarının sunum slaytı boyutuna göre hesaplanacağı anlamına gelir. Read/write Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Read-only [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Oluşturulan görüntüler için piksel biçimini belirtir. Read/write [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Kaydetme ilerleme güncellemelerini yüzde olarak bildiren bir geri çağırma nesnesini temsil eder. Bkz [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan `false`'tur. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Sunumu kaydederken JavaScript çağrısı içeren bağlantıların atlanıp atlanmayacağını belirtir. Read/write Boolean. Varsayılan değer **false**'dur. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. Read/write [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Örnekler

Aşağıdaki örnek, PowerPoint'i varsayılan boyutla TIFF'e nasıl dönüştüreceğinizi gösterir.

```csharp
[C#]
// Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Sunumu TIFF belgesine kaydediyor
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Aşağıdaki örnek, PowerPoint'i özel boyutla TIFF'e nasıl dönüştüreceğinizi gösterir.

```csharp
[C#]
// Bir Presentation dosyasını temsil eden Presentation nesnesi oluşturur
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // TiffOptions sınıfını oluşturur
    TiffOptions opts = new TiffOptions();
    // Sıkıştırma türü ayarlanıyor
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Sıkıştırma Türleri
    // Default - Varsayılan sıkıştırma şemasını (LZW) belirtir.
    // None - Sıkıştırma yapılmadığını belirtir.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Derinlik sıkıştırma türüne bağlıdır ve manuel olarak ayarlanamaz.
    // Çözünürlük birimi her zaman “2” (dots per inch) eşittir.
    // Görüntü DPI'sı ayarlanıyor
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Görüntü Boyutunu Ayarla
    opts.ImageSize = new Size(1728, 1078);
    // Save the presentation to TIFF with specified image size
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Aşağıdaki örnek, PowerPoint'i özel görüntü piksel biçimiyle TIFF'e nasıl dönüştüreceğinizi gösterir.

```csharp
[C#]
// Bir Presentation dosyasını temsil eden Presentation nesnesi oluşturur
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat aşağıdaki değerleri içerir (belgelerden görüldüğü gibi):
    Format1bppIndexed; // 1 bit/piksel, indeksli.
    Format4bppIndexed; // 4 bit/piksel, indeksli.
    Format8bppIndexed; // 8 bit/piksel, indeksli.
    Format24bppRgb; // 24 bit/piksel, RGB.
    Format32bppArgb; // 32 bit/piksel, ARGB.
    */
    // Sunumu belirtilen görüntü boyutuyla TIFF formatında kaydeder
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Ayrıca Bakınız

* sınıf [SaveOptions](../saveoptions)
* arayüz [ITiffOptions](../itiffoptions)
* ad alanı [Aspose.Slides.Export](../../aspose.slides.export)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->