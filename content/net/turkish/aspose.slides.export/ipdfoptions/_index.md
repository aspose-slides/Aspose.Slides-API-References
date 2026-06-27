---
title: IPdfOptions
second_title: Aspose.Sildes .NET API Referansı
description: Bir sunumun Pdf formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.
type: docs
weight: 3980
url: /tr/aspose.slides.export/ipdfoptions/
---
## IPdfOptions arayüz

Bir sunumun Pdf formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Belirli erişim izinlerinin, belge kullanıcı erişimi ile açıldığında hangi izinlerin verileceğini belirten bir dizi bayrak içerir. [`PdfAccessPermissions`](../pdfaccesspermissions) adresine bakın. |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Kullanıcı tarafından tanımlanan yazı tipi ailelerinin adlarını içeren bir dizi döndürür veya ayarlar; Aspose.Slides bu yazı tiplerini ortak olarak kabul etmelidir. Okunur/Yazılır String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | `true` ise belirtilen saydam rengi bir görüntüye uygular. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | ISaveOptions arayüzünü döndürür. Sadece okunur [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Her görüntü için varsayılan yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmemesini gösterir. Boolean.true olarak ayarlanırsa, sunumdaki her görüntü için en uygun sıkıştırma algoritması seçilir ve bu, ortaya çıkan PDF belgesinin daha küçük olmasına yol açar. En iyi görüntü sıkıştırma oranının seçilmesi işlem açısından maliyetlidir ve ek RAM tüketir; bu seçenek varsayılan olarak Boolean.false'tur. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Oluşturulan PDF belgesi için istenen uyumluluk seviyesi. Okunur/Yazılır [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | `true` ise her slaytın etrafına siyah çerçeve çizer. Okunur/Yazılır Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. Okunur/Yazılır Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | `true` ise ASCII karakterleri 32-127 için TrueType yazı tipleri gömülür. 127'den büyük karakter kodları için yazı tipleri her zaman gömülür. Okunur/Yazılır Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Görüntünün saydam rengini alır veya ayarlar. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | `true` ise sunumdaki tüm OLE verileri, ortaya çıkan PDF içinde gömülü dosyalara dönüştürülür. Okunur/Yazılır Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Sadece okunur [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. Okunur/Yazılır Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | PDF belgesini korumak için kullanıcı şifresi ayarlar. Okunur/Yazılır String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. Bu yaklaşım belirli yazı tipleri için ortaya çıkan PDF'deki metin kalitesini artırabilir. Okunur/Yazılır Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | `true` ise bir sunumda kullanılan tüm metafile'lar PNG görüntülerine dönüştürülür. Okunur/Yazılır Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Sunumu dışa aktarırken slaytların sayfada yer alacağı modu alır veya ayarlar [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Belgedeki tüm metin içeriği için kullanılacak sıkıştırma tipini belirtir. Okunur/Yazılır [`PdfTextCompression`](../pdftextcompression). |

### Bakınız

* arayüz [ISaveOptions](../isaveoptions)
* ad alanı [Aspose.Slides.Export](../../aspose.slides.export)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->