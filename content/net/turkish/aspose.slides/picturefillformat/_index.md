---
title: PictureFillFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Bir resim doldurma stilini temsil eder.
type: docs
weight: 9390
url: /tr/aspose.slides/picturefillformat/
---
## PictureFillFormat sınıfı

Bir resim doldurma stilini temsil eder.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arayüzünü almaya izin verir. Salt okunur [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Resmin alt kısmından kırpılan gerçek görüntü yüksekliğinin yüzde miktarını döndürür veya ayarlar. Okunabilir/Yazılabilir Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Resmin sol kısmından kırpılan gerçek görüntü genişliğinin yüzde miktarını döndürür veya ayarlar. Okunabilir/Yazılabilir Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Resmin sağ kısmından kırpılan gerçek görüntü genişliğinin yüzde miktarını döndürür veya ayarlar. Okunabilir/Yazılabilir Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Resmin üst kısmından kırpılan gerçek görüntü yüksekliğinin yüzde miktarını döndürür veya ayarlar. Okunabilir/Yazılabilir Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Resmi doldurmak için kullanılan dpi değerini döndürür veya ayarlar. Okunabilir/Yazılabilir Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Resmi döndürür. Salt okunur [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Resim doldurma modunu döndürür veya ayarlar. Okunabilir/Yazılabilir [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Şeklin sınırlayıcı kutusunun alt kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin alt kenarını döndürür veya ayarlar. Pozitif yüzde bir girinti, negatif yüzde bir dışarı çıkış belirtir. Okunabilir/Yazılabilir Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Şeklin sınırlayıcı kutusunun sol kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin sol kenarını döndürür veya ayarlar. Pozitif yüzde bir girinti, negatif yüzde bir dışarı çıkış belirtir. Okunabilir/Yazılabilir Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin sağ kenarını döndürür veya ayarlar. Pozitif yüzde bir girinti, negatif yüzde bir dışarı çıkış belirtir. Okunabilir/Yazılabilir Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Şeklin sınırlayıcı kutusunun üst kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin üst kenarını döndürür veya ayarlar. Pozitif yüzde bir girinti, negatif yüzde bir dışarı çıkış belirtir. Okunabilir/Yazılabilir Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Doku şekil içinde nasıl hizalanacağını döndürür veya ayarlar. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl tekrar edeceğini kontrol eder. Okunabilir/Yazılabilir [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Dokunun yatay, dikey veya her iki eksende çevrilmesini sağlar. Okunabilir/Yazılabilir [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Dokunun şeklin orijininden puan cinsinden yatay ofsetini döndürür veya ayarlar. Pozitif değer dokuyu sağa, negatif değer sola kaydırır. Okunabilir/Yazılabilir Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Dokunun şeklin orijininden puan cinsinden dikey ofsetini döndürür veya ayarlar. Pozitif değer dokuyu aşağı, negatif değer yukarı kaydırır. Okunabilir/Yazılabilir Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Doku doldurmanın yatay ölçeğini yüzde olarak döndürür veya ayarlar. Okunabilir/Yazılabilir Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Doku doldurmanın dikey ölçeğini yüzde olarak döndürür veya ayarlar. Okunabilir/Yazılabilir Single. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Görüntüyü şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu azaltarak sıkıştırır. İsteğe bağlı olarak, kırpılmış alanları da siler. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Görüntüyü şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu azaltarak sıkıştırır. İsteğe bağlı olarak, kırpılmış alanları da siler. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Doldurma resmi üzerindeki kırpılmış alanları siler. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesneyle karşılaştırır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Karma kodunu döndürür. |

### Ayrıca Bakınız

* sınıf [PVIObject](../pviobject)
* arayüz [IPictureFillFormat](../ipicturefillformat)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->