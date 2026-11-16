---
title: TiffOptions
second_title: Aspose.Sildes for .NET API Referansı
description: Sunumun TIFF formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.
type: docs
weight: 4590
url: /tr/aspose.slides.export/tiffoptions/
---
## TiffOptions sınıfı

Bir sunumun TIFF formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Yapıcılar

| Name | Description |
| --- | --- |
| [TiffOptions](tiffoptions)() | Varsayılan yapıcı. |

## Özellikler

| Name | Description |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Renkli bir görseli siyah beyaz bir görsele dönüştürme algoritmasını belirtir. Bu seçenek yalnızca [`CompressionType`](./compressiontype) CCITT4 veya CCITT3 olarak ayarlandığında uygulanır. Okunur/Yazılır [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Varsayılan, Varsayılan'dır. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Sıkıştırma türünü belirtir. Okunur/Yazılır [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Kaynak font bulunamadığında kullanılan fontu döndürür veya ayarlar. Okunur/Yazılır String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | İnç başına nokta cinsinden yatay çözünürlüğü belirtir. Okunur/Yazılır UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | İnç başına nokta cinsinden dikey çözünürlüğü belirtir. Okunur/Yazılır UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gradyentin görsel stilini döndürür veya ayarlar. Okunur/Yazılır [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Oluşturulan TIFF görüntüsünün boyutunu belirtir. Varsayılan değer 0x0'dir, bu da oluşturulan görüntü boyutlarının sunum slaytı boyutuna göre hesaplanacağı anlamına gelir. Okunur/Yazılır Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. Sadece Okunur [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Oluşturulan görüntüler için piksel biçimini belirtir. Okunur/Yazılır [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Yüzde cinsinden kaydetme ilerleme güncellemeleri için bir geri çağırma nesnesini temsil eder. Bkz. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlanmayacağını belirtir. Okunur/Yazılır Boolean. Varsayılan değer **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Sunum dışa aktarılırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. Okunur/Yazılır [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Örnekler

Aşağıdaki örnek, PowerPoint'i varsayılan boyutla TIFF'e nasıl dönüştüreceğinizi gösterir.

```csharp
[C#]
// Bir sunum dosyasını temsil eden Presentation nesnesini oluşturur
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Sunumu TIFF belgesine kaydetme
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Aşağıdaki örnek, PowerPoint'i özelleştirilmiş boyutla TIFF'e nasıl dönüştüreceğinizi gösterir.

```csharp
[C#]
// Bir sunum dosyasını temsil eden Presentation nesnesini oluşturur
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // TiffOptions sınıfını oluşturur
    TiffOptions opts = new TiffOptions();
    // Sıkıştırma türünü ayarlama
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Sıkıştırma Türleri
    // Default - Varsayılan sıkıştırma şemasını (LZW) belirtir.
    // None - Sıkıştırma olmadığını belirtir.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Derinlik, sıkıştırma türüne bağlıdır ve manuel olarak ayarlanamaz.
    // Çözünürlük birimi her zaman “2” (inç başına nokta) eşittir.
    // Görüntü DPI'sını ayarlama
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Görüntü Boyutunu Ayarla
    opts.ImageSize = new Size(1728, 1078);
    // Sunumu belirtilen görüntü boyutuyla TIFF olarak kaydet
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Aşağıdaki örnek, PowerPoint'i özelleştirilmiş görüntü piksel biçimiyle TIFF'e nasıl dönüştüreceğinizi gösterir.

```csharp
[C#]
// Bir Presentation dosyasını temsil eden Presentation nesnesini oluşturur
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat aşağıdaki değerleri içerir (belgelerden görülebileceği gibi):
    Format1bppIndexed; // piksel başına 1 bit, indeksli.
    Format4bppIndexed; // piksel başına 4 bit, indeksli.
    Format8bppIndexed; // piksel başına 8 bit, indeksli.
    Format24bppRgb; // piksel başına 24 bit, RGB.
    Format32bppArgb; // piksel başına 32 bit, ARGB.
    */
    // Sunumu belirtilen görüntü boyutuyla TIFF olarak kaydeder
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Diğer Bağlantılar

* sınıf [SaveOptions](../saveoptions)
* arayüz [ITiffOptions](../itiffoptions)
* ad alanı [Aspose.Slides.Export](../../aspose.slides.export)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->