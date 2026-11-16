---
title: SwfOptions
second_title: Aspose.Sildes for .NET API Referansı
description: Sunumun Swf formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
weight: 4550
url: /tr/aspose.slides.export/swfoptions/
---
## SwfOptions sınıfı

Sunumun Swf formatında kaydedilmesini kontrol eden seçenekler sağlar.

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
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirler. Varsayılan `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Kaynak font bulunamadığında kullanılan fontu alır veya ayarlar. Okunabilir-yazılabilir String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Bağlam menüsünü etkinleştirir/devre dışı bırakır. Varsayılan `true`. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gradyanın görsel stilini alır veya ayarlar. Okunabilir-yazılabilir [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | JPEG görüntülerinin kalitesini belirler. Varsayılan 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek görüntü. Görüntü 32x64 piksel PNG olmalıdır, aksi takdirde logo düzgün görüntülenmeyebilir. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Logoya tam hiperlink adresini alır veya ayarlar. Yalnızca bir [`LogoImageBytes`](./logoimagebytes) belirtilmişse etkili olur. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri çağırma nesnesi temsil eder. Bakınız [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Alt bölmeyi gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan `true`. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Tam ekran düğmesini gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan `true`. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Sol bölmeyi gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan `true`. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Sayfaların etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirler. Varsayılan `true`. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Sayfa adımlayıcısını gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan `true`. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Arama bölümünü gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan `true`. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Tüm üst bölmeyi gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan `true`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Sunumu kaydederken JavaScript çağrısı içeren hiperlinklerin atlanıp atlanmayacağını belirler. Okunabilir-yazılabilir Boolean. Varsayılan değer **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Sunumu [`ISlidesLayoutOptions`](../islideslayoutoptions) dışa aktarırken slaytların sayfaya nasıl yerleştirileceği modunu alır veya ayarlar. Bu özellik [`HandoutLayoutingOptions`](../handoutlayoutingoptions) türündeki nesnelerin atanmasını desteklemez. |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Açık sol bölme ile başlar. flashvars içinde geçersiz kılınabilir. Varsayılan `false`. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Oluşturulan SWF belgesinin bütünleşik belge görüntüleyicisini içerip içermeyeceğini belirler. Varsayılan `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar. Okunabilir-yazılabilir [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Örnekler

Aşağıdaki örnek PowerPoint'i SWF Flash'e nasıl dönüştüreceğini gösterir.

```csharp
[C#]
// Sunum dosyasını temsil eden bir Presentation nesnesi oluşturur
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Sunumu ve not sayfalarını kaydeder
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Ayrıca Bakınız

* sınıf [SaveOptions](../saveoptions)
* arayüz [ISwfOptions](../iswfoptions)
* ad alanı [Aspose.Slides.Export](../../aspose.slides.export)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->