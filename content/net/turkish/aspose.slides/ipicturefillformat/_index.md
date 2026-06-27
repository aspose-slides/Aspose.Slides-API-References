---
title: IPictureFillFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Bir resim dolgu stilini temsil eder.
type: docs
weight: 6630
url: /tr/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat arayüz

Bir resim dolgu stilini temsil eder.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Temel IFillParamSource arayüzünü almayı sağlar. Yalnızca okuma [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Resmin alt kısmından kırpılan gerçek görüntü yüksekliğinin yüzde oranını döndürür veya ayarlar. Okuma/yazma Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Resmin sol kısmından kırpılan gerçek görüntü genişliğinin yüzde oranını döndürür veya ayarlar. Okuma/yazma Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Resmin sağ kısmından kırpılan gerçek görüntü genişliğinin yüzde oranını döndürür veya ayarlar. Okuma/yazma Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Resmin üst kısmından kırpılan gerçek görüntü yüksekliğinin yüzde oranını döndürür veya ayarlar. Okuma/yazma Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Resmi doldurmak için kullanılan DPI değerini döndürür veya ayarlar. Okuma/yazma Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Resmi döndürür. Yalnızca okuma [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Resim dolgu modunu döndürür veya ayarlar. Okuma/yazma [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Şeklin sınırlayıcı kutusunun alt kenarından yüzde ofsetle tanımlanan dolgu dikdörtgeninin alt kenarını döndürür veya ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. Okuma/yazma Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Şeklin sınırlayıcı kutusunun sol kenarından yüzde ofsetle tanımlanan dolgu dikdörtgeninin sol kenarını döndürür veya ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. Okuma/yazma Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde ofsetle tanımlanan dolgu dikdörtgeninin sağ kenarını döndürür veya ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. Okuma/yazma Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Şeklin sınırlayıcı kutusunun üst kenarından yüzde ofsetle tanımlanan dolgu dikdörtgeninin üst kenarını döndürür veya ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. Okuma/yazma Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Dokusunun şekil içinde nasıl hizalandığını döndürür veya ayarlar. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl tekrarlandığını kontrol eder. Okuma/yazma [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Doku döşemesini yatay, dikey veya her iki eksende çevirir. Okuma/yazma [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Doku kaynağının şekilden yatay ofsetini puan cinsinden döndürür veya ayarlar. Pozitif değer dokuyu sağa, negatif değer sola kaydırır. Okuma/yazma Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Dokunun şekilden dikey ofsetini puan cinsinden döndürür veya ayarlar. Pozitif değer dokuyu aşağı, negatif değer yukarı kaydırır. Okuma/yazma Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Dokunun yatay ölçeğini yüzde olarak döndürür veya ayarlar. Okuma/yazma Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Dokunun dikey ölçeğini yüzde olarak döndürür veya ayarlar. Okuma/yazma Single. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Şekil boyutuna ve belirtilen çözünürlüğe göre görüntünün boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak kırpılmış alanları da siler. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Şekil boyutuna ve belirtilen çözünürlüğe göre görüntünün boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak kırpılmış alanları da siler. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Dolgu Resminin kırpılmış alanlarını sil. |

### Ayrıca Bakınız

* arayüz [IFillParamSource](../ifillparamsource)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->