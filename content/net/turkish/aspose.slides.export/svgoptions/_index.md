---
title: SVGOptions
second_title: Aspose.Sildes için .NET API Referansı
description: SVG seçeneklerini temsil eder.
type: docs
weight: 4450
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
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | SVGOptions sınıfının, bağlantı gömme denetleyicisi nesnesini belirterek yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Varsayılan ayarları döndürür. Sadece okunabilir [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | En basit ve en küçük SVG dosyası oluşturma ayarlarını döndürür. Sadece okunabilir [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | En doğru SVG dosyası oluşturma ayarlarını döndürür. Sadece okunabilir [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar. Okunabilir/yazılabilir String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmayacağını belirten bir Boolean bayrağı. True ise kırpılmış parçalar kaldırılır, false ise belgenin içinde serileştirilir (bu daha büyük bir dosyaya yol açabilir). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | SVG'de 3D metnin devre dışı bırakılıp bırakılmayacağını belirler. Okunabilir/yazılabilir Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Metnin ligaturalar kullanılmadan render edilip edilmediğini belirten bir değeri alır veya ayarlar. `true` olarak ayarlandığında, ligaturalar çıktıda devre dışı bırakılır. Varsayılan olarak bu özellik `false` olarak ayarlanmıştır. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. Okunabilir/yazılabilir Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1, işaretçiler için iç boşlukları tanımlama yeteneğine sahip değildir. Aspose.Slides SVG yazma motoru bu soruna bir geçici çözüm sunar: okla satır sonunu kırpar, böylece satır işaretçilerin üzerine çıkmaz. Bu seçenek bu davranışı kapatır. Okunabilir/yazılabilir Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Harici yüklenen yazı tiplerinin işlenme şeklini belirler. Okunabilir/yazılabilir [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gradyanın görsel stilini döndürür veya ayarlar. Okunabilir/yazılabilir [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Sadece okunabilir [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | JPEG kodlama kalitesini belirler. Okunabilir/yazılabilir Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Metafile rasterleştirme için alt çözünürlük limitini döndürür veya ayarlar. Okunabilir/yazılabilir Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Resim sıkıştırma seviyesini temsil eder |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Kaydetme ilerleme güncellemelerini yüzde olarak raporlayan bir geri arama nesnesini temsil eder. Bkz. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Kullanıcının şekil dönüştürmeyi kontrol etmesini sağlayan bir geri arama arabirimini döndürür ve ayarlar. Okunabilir/yazılabilir [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Sunumu kaydederken JavaScript çağrıları içeren köprülerin atlanıp atlanmayacağını belirtir. Okunabilir/yazılabilir Boolean. Varsayılan değer **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Render edilirken şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. Okunabilir/yazılabilir Boolean. Varsayılan değer true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Metin çerçevesinin renderleme alanına dahil edilip edilmemeyeceğini belirler. Okunabilir/yazılabilir Boolean. Varsayılan değer false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. Okunabilir/yazılabilir Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. Okunabilir/yazılabilir [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ayrıca Bakın

* sınıf [SaveOptions](../saveoptions)
* arayüz [ISVGOptions](../isvgoptions)
* ad alanı [Aspose.Slides.Export](../../aspose.slides.export)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->