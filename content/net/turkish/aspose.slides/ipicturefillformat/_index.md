---
title: IPictureFillFormat
second_title: Aspose.Sildes .NET API Referansı
description: Bir resim doldurma stilini temsil eder.
type: docs
weight: 6670
url: /tr/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat arayüzü

Represents a picture fill style.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Temel IFillParamSource arayüzünü almayı sağlar. Salt okunur [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Gerçek resim yüksekliğinin yüzde kaçının resmin alt kısmından kırpıldığını döndürür veya ayarlar. Okunabilir/Yazılabilir Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Gerçek resim genişliğinin yüzde kaçının resmin sol tarafından kırpıldığını döndürür veya ayarlar. Okunabilir/Yazılabilir Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Gerçek resim genişliğinin yüzde kaçının resmin sağ tarafından kırpıldığını döndürür veya ayarlar. Okunabilir/Yazılabilir Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Gerçek resim yüksekliğinin yüzde kaçının resmin üstünden kırpıldığını döndürür veya ayarlar. Okunabilir/Yazılabilir Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Bir resmi doldurmak için kullanılan dpi değerini döndürür veya ayarlar. Okunabilir/Yazılabilir Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Resmi döndürür. Salt okunur [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Resim doldurma modunu döndürür veya ayarlar. Okunabilir/Yazılabilir [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Dolgu dikdörtgeninin alt kenarını, şeklin sınırlayıcı kutusunun alt kenarından yüzde offset ile tanımlanan şekilde döndürür veya ayarlar. Pozitif yüzde iç girinti, negatif yüzde dış çıkıntı belirtir. Okunabilir/Yazılabilir Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Dolgu dikdörtgeninin sol kenarını, şeklin sınırlayıcı kutusunun sol kenarından yüzde offset ile tanımlanan şekilde döndürür veya ayarlar. Pozitif yüzde iç girinti, negatif yüzde dış çıkıntı belirtir. Okunabilir/Yazılabilir Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Dolgu dikdörtgeninin sağ kenarını, şeklin sınırlayıcı kutusunun sağ kenarından yüzde offset ile tanımlanan şekilde döndürür veya ayarlar. Pozitif yüzde iç girinti, negatif yüzde dış çıkıntı belirtir. Okunabilir/Yazılabilir Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Dolgu dikdörtgeninin üst kenarını, şeklin sınırlayıcı kutusunun üst kenarından yüzde offset ile tanımlanan şekilde döndürür veya ayarlar. Pozitif yüzde iç girinti, negatif yüzde dış çıkıntı belirtir. Okunabilir/Yazılabilir Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Doku şekil içinde nasıl hizalanacağını döndürür veya ayarlar. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl tekrarlandığını kontrol eder. Okunabilir/Yazılabilir [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Doku karoselini yatay, dikey veya her iki eksende çevirir. Okunabilir/Yazılabilir [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Dokunun şekil kökeninden yatay offsetini puan cinsinden döndürür veya ayarlar. Pozitif değer dokuyu sağa, negatif değer sola kaydırır. Okunabilir/Yazılabilir Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Dokunun şekil kökeninden dikey offsetini puan cinsinden döndürür veya ayarlar. Pozitif değer dokuyu aşağı, negatif değer yukarı kaydırır. Okunabilir/Yazılabilir Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Doku doldurmanın yatay ölçeğini yüzde olarak döndürür veya ayarlar. Okunabilir/Yazılabilir Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Doku doldurmanın dikey ölçeğini yüzde olarak döndürür veya ayarlar. Okunabilir/Yazılabilir Single. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Görüntüyü, şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu azaltarak sıkıştırır. İsteğe bağlı olarak kırpılmış alanları da siler. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Görüntüyü, şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu azaltarak sıkıştırır. İsteğe bağlı olarak kırpılmış alanları da siler. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Doldurma resminin kırpılmış alanlarını siler. |

### Bakınız

* arayüz [IFillParamSource](../ifillparamsource)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->