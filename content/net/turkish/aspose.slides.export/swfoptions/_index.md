---
title: SwfOptions
second_title: Aspose.Sildes için .NET API Referansı
description: Bir sunumun Swf formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.
type: docs
weight: 4510
url: /tr/aspose.slides.export/swfoptions/
---
## SwfOptions sınıfı

Sunumun Swf formatında kaydedilmesini kontrol eden seçenekleri sağlar.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SwfOptions](swfoptions)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirtir. Varsayılan `true` değeridir. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar. Okunabilir-yazılabilir String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Bağlam menüsünü etkinleştirir/devre dışı bırakır. Varsayılan true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gradyanın görsel stilini döndürür veya ayarlar. Okunabilir-yazılabilir [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | JPEG görüntülerinin kalitesini belirtir. Varsayılan 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek görüntü. Görüntü 32x64 piksel PNG olmalıdır, aksi takdirde logo düzgün görüntülenmeyebilir. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Logo için tam hiperlink adresini alır veya ayarlar. Yalnızca bir [`LogoImageBytes`](./logoimagebytes) belirtilmişse etkili olur. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri çağırma nesnesini temsil eder. Bakınız [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Alt bölmeyi göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Tam ekran düğmesini göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Sol bölmeyi göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirtir. Varsayılan true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Sayfa adım sayacını göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Arama bölümünü göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Tam üst bölmeyi göster/gizle. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Sunumu kaydederken JavaScript çağrıları içeren hiperlinklerin atlanıp atlanmayacağını belirtir. Okunabilir-yazılabilir Boolean. Varsayılan değer **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Sunumu [`ISlidesLayoutOptions`](../islideslayoutoptions) dışa aktarırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar. Bu özellik [`HandoutLayoutingOptions`](../handoutlayoutingoptions) türündeki nesnelerin atanmasını desteklemez. |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Açık sol bölme ile başlar. flashvars içinde geçersiz kılınabilir. Varsayılan false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Oluşturulan SWF belgesinin bütünleşik belge görüntüleyiciyi içerip içermeyeceğini belirtir. Varsayılan `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. Okunabilir-yazılabilir [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Örnekler

Aşağıdaki örnek, PowerPoint'i SWF Flash'e nasıl dönüştüreceğinizi gösterir.

```csharp
[C#]
// Bir sunum dosyasını temsil eden Presentation nesnesini oluşturun
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Sunumu ve not sayfalarını kaydediyor
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### İlgili

* sınıf [SaveOptions](../saveoptions)
* arayüz [ISwfOptions](../iswfoptions)
* ad alanı [Aspose.Slides.Export](../../aspose.slides.export)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->