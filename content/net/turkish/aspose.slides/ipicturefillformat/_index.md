---
title: IPictureFillFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Bir resim doldurma stilini temsil eder.
type: docs
weight: 6650
url: /tr/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat arayüz

Bir resim doldurma stilini temsil eder.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Temel IFillParamSource arayüzünü almaya izin verir. Yalnızca okunur [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Resmin gerçek yüksekliğinin yüzde olarak alt kısmından kırpılan miktarını döndürür veya ayarlar. Okunur/Yazılır Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Resmin gerçek genişliğinin yüzde olarak sol kısmından kırpılan miktarını döndürür veya ayarlar. Okunur/Yazılır Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Resmin gerçek genişliğinin yüzde olarak sağ kısmından kırpılan miktarını döndürür veya ayarlar. Okunur/Yazılır Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Resmin gerçek yüksekliğinin yüzde olarak üst kısmından kırpılan miktarını döndürür veya ayarlar. Okunur/Yazılır Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Resmi doldurmak için kullanılan dpi değerini döndürür veya ayarlar. Okunur/Yazılır Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Resmi döndürür. Yalnızca okunur [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Resim doldurma modunu döndürür veya ayarlar. Okunur/Yazılır [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Şeklin sınırlayıcı kutusunun alt kenarından yüzde olarak bir kaydırma ile tanımlanan doldurma dikdörtgeninin alt kenarını döndürür veya ayarlar. Pozitif yüzde içe doğru, negatif yüzde dışa doğru kaydırmayı belirtir. Okunur/Yazılır Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Şeklin sınırlayıcı kutusunun sol kenarından yüzde olarak bir kaydırma ile tanımlanan doldurma dikdörtgeninin sol kenarını döndürür veya ayarlar. Pozitif yüzde içe doğru, negatif yüzde dışa doğru kaydırmayı belirtir. Okunur/Yazılır Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde olarak bir kaydırma ile tanımlanan doldurma dikdörtgeninin sağ kenarını döndürür veya ayarlar. Pozitif yüzde içe doğru, negatif yüzde dışa doğru kaydırmayı belirtir. Okunur/Yazılır Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Şeklin sınırlayıcı kutusunun üst kenarından yüzde olarak bir kaydırma ile tanımlanan doldurma dikdörtgeninin üst kenarını döndürür veya ayarlar. Pozitif yüzde içe doğru, negatif yüzde dışa doğru kaydırmayı belirtir. Okunur/Yazılır Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Dokunun şekil içinde nasıl hizalanacağını döndürür veya ayarlar. Bu ayar doku deseninin başlangıç noktasını ve şekil boyunca nasıl tekrarlanacağını kontrol eder. Okunur/Yazılır [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Dokunun karolarını yatay, dikey ya da her iki eksende çevirir. Okunur/Yazılır [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Dokunun şeklin orijinal noktasından yatay kaydırmasını puan cinsinden döndürür veya ayarlar. Pozitif değer dokuyu sağa, negatif değer sola kaydırır. Okunur/Yazılır Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Dokunun şeklin orijinal noktasından dikey kaydırmasını puan cinsinden döndürür veya ayarlar. Pozitif değer dokuyu aşağı, negatif değer yukarı kaydırır. Okunur/Yazılır Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Doku doldurması için yatay ölçeği yüzde olarak döndürür veya ayarlar. Okunur/Yazılır Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Doku doldurması için dikey ölçeği yüzde olarak döndürür veya ayarlar. Okunur/Yazılır Single. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Şekil boyutu ve belirtilen çözünürlüğe göre görüntünün boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak kırpılan alanları da siler. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Şekil boyutu ve belirtilen çözünürlüğe göre görüntünün boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak kırpılan alanları da siler. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Doldurma Resminin kırpılan alanlarını siler. |

### Ayrıca Bakınız

* arayüz [IFillParamSource](../ifillparamsource)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->