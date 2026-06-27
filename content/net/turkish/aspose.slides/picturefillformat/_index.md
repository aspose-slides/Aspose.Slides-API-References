---
title: PictureFillFormat
second_title: Aspose.Slides için .NET API Referansı
description: Bir resim doldurma stilini temsil eder.
type: docs
weight: 9370
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
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arayüzünü almaya izin verir. Yalnızca okuma [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Resmin gerçek yüksekliğinin alt kısımdan kırpılan yüzde sayısını döndürür veya ayarlar. Okuma/Yazma Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Resmin gerçek genişliğinin sol taraftan kırpılan yüzde sayısını döndürür veya ayarlar. Okuma/Yazma Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Resmin gerçek genişliğinin sağ taraftan kırpılan yüzde sayısını döndürür veya ayarlar. Okuma/Yazma Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Resmin gerçek yüksekliğinin üst kısımdan kırpılan yüzde sayısını döndürür veya ayarlar. Okuma/Yazma Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Resmi doldurmak için kullanılan dpi'yi döndürür veya ayarlar. Okuma/Yazma Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Resmi döndürür. Yalnızca okuma [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Resim doldurma kipini döndürür veya ayarlar. Okuma/Yazma [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Şeklin sınırlayıcı kutusunun alt kenarından yüzde offset ile tanımlanan dolgu dikdörtgeninin alt kenarını döndürür veya ayarlar. Pozitif yüzde içeri girme, negatif yüzde dışarı çıkma belirtir. Okuma/Yazma Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Şeklin sınırlayıcı kutusunun sol kenarından yüzde offset ile tanımlanan dolgu dikdörtgeninin sol kenarını döndürür veya ayarlar. Pozitif yüzde içeri girme, negatif yüzde dışarı çıkma belirtir. Okuma/Yazma Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde offset ile tanımlanan dolgu dikdörtgeninin sağ kenarını döndürür veya ayarlar. Pozitif yüzde içeri girme, negatif yüzde dışarı çıkma belirtir. Okuma/Yazma Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Şeklin sınırlayıcı kutusunun üst kenarından yüzde offset ile tanımlanan dolgu dikdörtgeninin üst kenarını döndürür veya ayarlar. Pozitif yüzde içeri girme, negatif yüzde dışarı çıkma belirtir. Okuma/Yazma Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Dokunun şekil içinde nasıl hizalanacağını döndürür veya ayarlar. Bu ayar, doku deseninin başlangıç noktasını ve şekil üzerinde nasıl tekrarlandığını kontrol eder. Okuma/Yazma [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Dokuyu yatay, dikey veya her iki eksende çevirir. Okuma/Yazma [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Şeklin orijinalinden puan cinsinden yatay doku kaydırmasını döndürür veya ayarlar. Pozitif değer dokuı sağa, negatif değer sola kaydırır. Okuma/Yazma Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Şeklin orijinalinden puan cinsinden dikey doku kaydırmasını döndürür veya ayarlar. Pozitif değer dokuı aşağı, negatif değer yukarı kaydırır. Okuma/Yazma Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Doku doldurması için yatay ölçeği yüzde olarak döndürür veya ayarlar. Okuma/Yazma Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Doku doldurması için dikey ölçeği yüzde olarak döndürür veya ayarlar. Okuma/Yazma Single. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu azaltarak resmi sıkıştırır. İsteğe bağlı olarak, kırpılan alanları da siler. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu azaltarak resmi sıkıştırır. İsteğe bağlı olarak, kırpılan alanları da siler. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Dolgu resminin kırpılmış alanlarını sil. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesne ile karşılaştırır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Hash kodu döndürür. |

### Ayrıca Bakınız

* sınıf [PVIObject](../pviobject)
* arayüz [IPictureFillFormat](../ipicturefillformat)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->