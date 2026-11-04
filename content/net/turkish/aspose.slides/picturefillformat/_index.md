---
title: PictureFillFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Bir resim doldurma stilini temsil eder.
type: docs
weight: 9410
url: /tr/aspose.slides/picturefillformat/
---
## PictureFillFormat sınıfı

Represents a picture fill style.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arayüzünü almaya izin verir. Yalnızca okunabilir [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Gerçek resim yüksekliğinin yüzde kaçının resmin altından kırpıldığını döndürür veya ayarlar. Okunur/yazılır Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Gerçek resim genişliğinin yüzde kaçının resmin solundan kırpıldığını döndürür veya ayarlar. Okunur/yazılır Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Gerçek resim genişliğinin yüzde kaçının resmin sağından kırpıldığını döndürür veya ayarlar. Okunur/yazılır Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Gerçek resim yüksekliğinin yüzde kaçının resmin üstünden kırpıldığını döndürür veya ayarlar. Okunur/yazılır Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Resmi doldurmak için kullanılan dpi'yi döndürür veya ayarlar. Okunur/yazılır Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Resmi döndürür. Yalnızca okunabilir [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Resim doldurma modunu döndürür veya ayarlar. Okunur/yazılır [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Şeklin sınırlayıcı kutusunun alt kenarından yüzde ofsetle tanımlanan doldurma dikdörtgeninin alt kenarını döndürür veya ayarlar. Pozitif yüzde bir iç kenar, negatif yüzde bir dış kenar belirtir. Okunur/yazılır Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Şeklin sınırlayıcı kutusunun sol kenarından yüzde ofsetle tanımlanan doldurma dikdörtgeninin sol kenarını döndürür veya ayarlar. Pozitif yüzde bir iç kenar, negatif yüzde bir dış kenar belirtir. Okunur/yazılır Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde ofsetle tanımlanan doldurma dikdörtgeninin sağ kenarını döndürür veya ayarlar. Pozitif yüzde bir iç kenar, negatif yüzde bir dış kenar belirtir. Okunur/yazılır Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Şeklin sınırlayıcı kutusunun üst kenarından yüzde ofsetle tanımlanan doldurma dikdörtgeninin üst kenarını döndürür veya ayarlar. Pozitif yüzde bir iç kenar, negatif yüzde bir dış kenar belirtir. Okunur/yazılır Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Doku şekil içinde nasıl hizalanacağını döndürür veya ayarlar. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl tekrarlanacağını kontrol eder. Okunur/yazılır [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Doku karosunu yatay, dikey veya her iki eksende çevirir. Okunur/yazılır [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Doku'nun şeklin başlangıcından yatay ofsetini (puan cinsinden) döndürür veya ayarlar. Pozitif değer doku'nu sağa, negatif değer sola hareket ettirir. Okunur/yazılır Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Doku'nun şeklin başlangıcından düşey ofsetini (puan cinsinden) döndürür veya ayarlar. Pozitif değer doku'nu aşağı, negatif değer yukarı hareket ettirir. Okunur/yazılır Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Doku doldurması için yatay ölçeği yüzde olarak döndürür veya ayarlar. Okunur/yazılır Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Doku doldurması için düşey ölçeği yüzde olarak döndürür veya ayarlar. Okunur/yazılır Single. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Şekil boyutuna ve belirtilen çözünürlüğe bağlı olarak boyutunu küçülterek resmi sıkıştırır. İsteğe bağlı olarak, kırpılmış alanları da siler. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Şekil boyutuna ve belirtilen çözünürlüğe bağlı olarak boyutunu küçülterek resmi sıkıştırır. İsteğe bağlı olarak, kırpılmış alanları da siler. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Doldurma resmindeki kırpılmış alanları sil. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesneyle karşılaştırır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Karma kodunu döndürür. |

### Ayrıca Bakınız

* sınıf [PVIObject](../pviobject)
* arayüz [IPictureFillFormat](../ipicturefillformat)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->