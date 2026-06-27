---
title: SVGOptions
second_title: Aspose.Sildes .NET API Referansı
description: SVG seçeneklerini temsil eder.
type: docs
weight: 4410
url: /tr/aspose.slides.export/svgoptions/
---
## SVGOptions sınıfı

SVG seçeneklerini temsil eder.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | SVGOptions sınıfının yeni bir örneğini başlatır. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Bağlantı gömme denetleyici nesnesini belirterek SVGOptions sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Varsayılan ayarları döndürür. Salt okunur [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | En basit ve en küçük SVG dosyası oluşturma ayarlarını döndürür. Salt okunur [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | En doğru SVG dosyası oluşturma ayarlarını döndürür. Salt okunur [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar. Okunabilir/Yazılabilir String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Kırpılan parçaların belgenin bir parçası olarak kalıp kalmayacağını belirten bir bool bayrağı. true ise kırpılan parçalar kaldırılır, false ise belge içinde serileştirilir (bu daha büyük bir dosyaya yol açabilir). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | SVG içinde 3D metnin devre dışı bırakılıp bırakılmayacağını belirler. Okunabilir/Yazılabilir Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. `true` olarak ayarlandığında, ligatürler çıktı içinde devre dışı bırakılır. Varsayılan olarak bu özellik `false`'a ayarlanmıştır. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. Okunabilir/Yazılabilir Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 işaretçiler için girinti tanımlama yeteneğine sahip değildir. Aspose.Slides SVG yazma motoru bu sorun için bir geçici çözüm sağlar: oklu çizginin sonunu kırpar, böylece çizgi işaretçileri örtüşmez. Bu seçenek bu davranışı kapatır. Okunabilir/Yazılabilir Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Harici yüklenen yazı tiplerinin işlenme şeklini belirler. Okunabilir/Yazılabilir [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gradyanın görsel stilini döndürür veya ayarlar. Okunabilir/Yazılabilir [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Salt okunur [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | JPEG kodlama kalitesini belirler. Okunabilir/Yazılabilir Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Metafile rasterleştirme için alt çözünürlük limitini döndürür veya ayarlar. Okunabilir/Yazılabilir Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Resim sıkıştırma seviyesini temsil eder |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri çağırma nesnesini temsil eder. Bakınız [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Kullanıcının şekil dönüşümünü kontrol etmesine izin veren bir geri çağırma arayüzünü döndürür ve ayarlar. Okunabilir/Yazılabilir [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlamayacağını belirler. Okunabilir/Yazılabilir Boolean. Varsayılan değer **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Render ederken şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. Okunabilir/Yazılabilir Boolean. Varsayılan değer true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Metin çerçevesinin render alanına dahil edilip edilmeyeceğini belirler. Okunabilir/Yazılabilir Boolean. Varsayılan değer false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. Okunabilir/Yazılabilir Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. Okunabilir/Yazılabilir [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ayrıca bakınız

* sınıf [SaveOptions](../saveoptions)
* arayüz [ISVGOptions](../isvgoptions)
* ad alanı [Aspose.Slides.Export](../../aspose.slides.export)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->