---
title: IPdfOptions
second_title: Aspose.Sildes için .NET API Referansı
description: Bir sunumun Pdf formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.
type: docs
weight: 4000
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
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Belge kullanıcı erişimiyle açıldığında verilmesi gereken erişim izinlerini belirten bayrakların bir kümesini içerir. Bkz. [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Aspose.Slides'ın ortak olarak kabul etmesi gereken yazı tipi ailelerinin kullanıcı tanımlı adlarını içeren bir dizi döndürür veya ayarlar. Okunur/Yazılabilir String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Belirtilen şeffaf rengi bir görüntüye uygular, `true` ise. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | ISaveOptions arayüzünü döndürür. Salt okunur [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Her görüntü için varsayılan yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmeyeceğini gösterir. Boolean.true olarak ayarlanırsa, sunumdaki her görüntü için en uygun sıkıştırma algoritması seçilir ve bu, ortaya çıkan PDF belgesinin daha küçük olmasına yol açar. En iyi görüntü sıkıştırma oranı seçimi hesaplama açısından maliyetlidir ve ek RAM kullanır; bu seçenek varsayılan olarak Boolean.false'tur. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Oluşturulan PDF belgesi için istenen uyumluluk seviyesi. Okunur/Yazılabilir [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | Her slaytın etrafına siyah çerçeve çizmek için True. Okunur/Yazılabilir Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömüleceğini belirler. Okunur/Yazılabilir Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | ASCII karakterleri 32-127 için TrueType yazı tiplerini gömmek için True. 127'den büyük karakter kodları için yazı tipleri her zaman gömülür. Okunur/Yazılabilir Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Görüntünün şeffaf rengini alır veya ayarlar. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | Sunumdan tüm OLE verilerini ortaya çıkan PDF'de gömülü dosyalara dönüştürmek için True. Okunur/Yazılabilir Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Salt okunur [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. Okunur/Yazılabilir Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | PDF belgesini korumak için kullanıcı şifresi ayarlar. Okunur/Yazılabilir String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini belirtir. Bu yaklaşım belirli yazı tiplerinde ortaya çıkan PDF'deki metin kalitesini artırabilir. Okunur/Yazılabilir Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | Sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için True. Okunur/Yazılabilir Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Sunum dışa aktarılırken slaytların sayfada yer alacağı modu alır veya ayarlar [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Belgedeki tüm metin içeriği için kullanılacak sıkıştırma türünü belirtir. Okunur/Yazılabilir [`PdfTextCompression`](../pdftextcompression). |

### Bakınız

* arayüz [ISaveOptions](../isaveoptions)
* ad alanı [Aspose.Slides.Export](../../aspose.slides.export)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->