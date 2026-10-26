---
title: SVGOptions
second_title: Aspose.Sildes .NET API Referansı
description: SVG seçeneklerini temsil eder.
type: docs
weight: 4430
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
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Bağlantı gömme denetleyicisi nesnesini belirterek SVGOptions sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Varsayılan ayarları döndürür. Yalnızca okunabilir [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | En basit ve en küçük SVG dosyası oluşturma ayarlarını döndürür. Yalnızca okunabilir [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | En doğru SVG dosyası oluşturma ayarlarını döndürür. Yalnızca okunabilir [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar. Okunur/yazılır String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmayacağını belirten bir Boolean bayrağı. true ise kırpılmış parçalar kaldırılır, false ise belge içinde serileştirilir (bu, daha büyük bir dosyaya yol açabilir). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | SVG'de 3D metnin devre dışı bırakılıp bırakılmayacağını belirler. Okunur/yazılır Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Metnin ligatürler kullanılmadan işlenip işlenmeyeceğini gösteren bir değeri alır veya ayarlar. `true` olarak ayarlandığında, ligatürler işlenen çıktı içinde devre dışı bırakılır. Varsayılan olarak bu özellik `false` değerindedir. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. Okunur/yazılır Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1, işaretçiler için iç kenar boşluklarını tanımlama yeteneğine sahip değildir. Aspose.Slides SVG yazma motoru bu sorun için bir çözüm sunar: oklu çizgi sonunu kırpar, böylece çizgi işaretçilerin üzerine binmez. Bu seçenek bu davranışı devre dışı bırakır. Okunur/yazılır Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Harici yüklenen yazı tiplerinin işlenme şeklini belirler. Okunur/yazılır [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gradyanın görsel stilini döndürür veya ayarlar. Okunur/yazılır [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Yalnızca okunabilir [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | JPEG kodlama kalitesini belirler. Okunur/yazılır Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Metafile rasterleştirme için alt çözünürlük sınırını döndürür veya ayarlar. Okunur/yazılır Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Resim sıkıştırma seviyesini temsil eder |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | İlerleme güncellemelerini yüzde olarak kaydetmek için bir geri çağırma nesnesini temsil eder. Bakınız [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Kullanıcının şekil dönüşümünü kontrol etmesini sağlayan bir geri çağırma arayüzünü döndürür ve ayarlar. Okunur/yazılır [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Sunumu kaydederken JavaScript çağrıları içeren köprülerin atlanıp atlanmayacağını belirtir. Okunur/yazılır Boolean. Varsayılan değer **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Render sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. Okunur/yazılır Boolean. Varsayılan değer true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Metin çerçevesinin render alanına dahil edilip edilmeyeceğini belirler. Okunur/yazılır Boolean. Varsayılan değer false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. Okunur/yazılır Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. Okunur/yazılır [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Diğer Bağlantılar

* sınıf [SaveOptions](../saveoptions)
* arayüz [ISVGOptions](../isvgoptions)
* ad alanı [Aspose.Slides.Export](../../aspose.slides.export)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->