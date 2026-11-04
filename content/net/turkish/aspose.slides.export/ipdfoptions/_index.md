---
title: IPdfOptions
second_title: Aspose.Sildes for .NET API Referansı
description: Sunumun Pdf biçiminde nasıl kaydedileceğini kontrol eden seçenekleri sağlar.
type: docs
weight: 4020
url: /tr/aspose.slides.export/ipdfoptions/
---
## IPdfOptions arayüz

Sunumun Pdf biçiminde kaydedilme şeklini kontrol eden seçenekleri sağlar.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Belirtilen erişim izinlerinin belge kullanıcı erişimiyle açıldığında hangi izinlerin verileceğini belirten bir dız bayrağı içerir. Bkz. [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Aspose.Slides tarafından ortak kabul edilmesi gereken, kullanıcı tanımlı yazı tipi aileleri adlarının bir dizisini döndürür veya ayarlar. Okuma/Yazma String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | `true` ise belirtilen şeffaf renk bir görüntüye uygulanır. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | ISaveOptions arayüzünü döndürür. Salt okunur [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Her görüntü için varsayılan yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmeyeceğini gösterir. Boolean.true olarak ayarlanırsa, sunumdaki her görüntü için en uygun sıkıştırma algoritması seçilir ve bu, ortaya çıkan PDF belgesinin daha küçük olmasını sağlar. En iyi görüntü sıkıştırma oranının seçimi hesaplama açısından maliyetlidir ve ek RAM tüketir; bu seçenek varsayılan olarak Boolean.false'tur. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Oluşturulan PDF belgesi için istenen uyumluluk düzeyi. Okuma/Yazma [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | Her slaytın etrafına siyah çerçeve çizmek için true. Okuma/Yazma Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. Okuma/Yazma Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | ASCII karakterleri 32-127 için True Type yazı tiplerini gömmek için true. 127'den büyük karakter kodları için yazı tipleri her zaman gömülür. Okuma/Yazma Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Görüntünün şeffaf rengini alır veya ayarlar. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | Sunumdaki tüm OLE verilerini ortaya çıkan PDF içinde gömülü dosyalara dönüştürmek için true. Okuma/Yazma Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Salt okunur [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. Okuma/Yazma Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | PDF belgesini korumak için kullanıcı parolasını ayarlar. Okuma/Yazma String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirip PDF'ye kaydedilip kaydedilmeyeceğini belirtir. Bu yaklaşım belirli yazı tipleri için ortaya çıkan PDF'deki metin kalitesini artırabilir. Okuma/Yazma Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | Sunumda kullanılan tüm metafile'leri PNG görüntülerine dönüştürmek için true. Okuma/Yazma Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Belgedeki tüm metin içeriği için kullanılacak sıkıştırma tipini belirtir. Okuma/Yazma [`PdfTextCompression`](../pdftextcompression). |

### İlgili

* arayüz [ISaveOptions](../isaveoptions)
* ad alanı [Aspose.Slides.Export](../../aspose.slides.export)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldoccmd for Aspose.Slides.dll -->