---
title: ParagraphFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Bu sınıf paragraf biçimlendirme özelliklerini içerir. IParagraphFormatEffectiveData./iparagraphformateffectivedata'nin aksine, bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 9290
url: /tr/aspose.slides/paragraphformat/
---
## ParagraphFormat sınıfı

Bu sınıf paragraf biçimlendirme özelliklerini içerir. [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)'in aksine, bu sınıfın tüm özellikleri yazılabilir.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | [`ParagraphFormat`](../paragraphformat) sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Paragrafta kalıtım olmadan metin hizalamasını döndürür veya ayarlar. Okunur/yazılır [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arayüzünü almayı sağlar. Sadece okunur [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Kalıtım olmadan varsayılan sekme boyutunu döndürür veya ayarlar. Okunur/yazılır Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Paragrafta Doğu Asya satır sonunun kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Kalıtım olmadan paragrafta bir yazı tipi hizalamasını döndürür veya ayarlar. Okunur/yazılır [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Paragrafta asılı noktalama işaretinin kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Kalıtım olmadan paragrafın İlk Satır Girintisi/Asılı Girinti değerini döndürür veya ayarlar. Asılı Girinti negatif değerlerle tanımlanabilir. Okunur/yazılır Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Paragrafta Latin satır sonunun kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Kalıtım olmadan paragraftaki sol kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Kalıtım olmadan paragraftaki sağ kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Kalıtım olmadan paragraftaki son satırın ardından gelen boşluk miktarını döndürür veya ayarlar. Pozitif değer, beyaz boşluğun olması gereken yazı tipi boyutunun yüzde oranını belirtir. Negatif değer ise beyaz boşluğun nokta cinsinden boyutunu belirtir. Okunur/yazılır Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Kalıtım olmadan paragraftaki ilk satırın öncesindeki boşluk miktarını döndürür veya ayarlar. Pozitif değer, beyaz boşluğun olması gereken yazı tipi boyutunun yüzde oranını belirtir. Negatif değer ise beyaz boşluğun nokta cinsinden boyutunu belirtir. Okunur/yazılır Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Paragraftaki temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. Pozitif değer yüzde, negatif değer ise puan cinsinden boyut demektir. Kalıtım uygulanmaz. Okunur/yazılır Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Paragrafın sekmelerini döndürür. Kalıtım uygulanmaz. Sadece okunur [`ITabCollection`](../itabcollection). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesneyle karşılaştırır. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Kalıtım uygulanmış etkili paragraf biçimlendirme verilerini alır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Karma kodu döndürür. |

### Açıklamalar

Bu sınıf, belirli bir paragraf için tanımlanan paragraf biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken herhangi bir kalıtım uygulanmadığı anlamına gelir; bu nedenle çoğu durumda "tanımsız" anlamına gelen değerler alırsınız.

Kalıtım dahil olmak üzere etkili biçimlendirme parametresi değerlerini almak için, [`GetEffective`](./geteffective) yöntemini kullanmanız gerekir; bu yöntem bir [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) örneği döndürür.

### Bakınız

* sınıf [PVIObject](../pviobject)
* arabirim [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* arabirim [IParagraphFormat](../iparagraphformat)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->