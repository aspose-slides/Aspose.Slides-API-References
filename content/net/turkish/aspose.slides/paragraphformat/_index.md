---
title: ParagraphFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Bu sınıf paragraf biçimlendirme özelliklerini içerir. IParagraphFormatEffectiveData./iparagraphformateffectivedata farklıdır, bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 9310
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
| [ParagraphFormat](paragraphformat)() | Yeni bir [`ParagraphFormat`](../paragraphformat) sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Bir paragrafta kalıtım olmadan metin hizalamasını döndürür veya ayarlar. Okunur/yazılır [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arabirimine erişim sağlar. Yalnızca okunur [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Kalıtım olmadan varsayılan sekme boyutunu döndürür veya ayarlar. Okunur/yazılır Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Bir paragrafta Doğu Asya satır sonunun kullanılıp kullanılmayacağını belirler. Kalandım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Kalıtım olmadan bir paragrafta yazı tipi hizalamasını döndürür veya ayarlar. Okunur/yazılır [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Bir paragrafta asılı noktalama işaretlerinin kullanılıp kullanılmayacağını belirler. Kalandım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Kalıtım olmadan paragrafın İlk Satır Girintisi/Asılı Girintisini döndürür veya ayarlar. Asılı Girinti negatif değerlerle tanımlanabilir. Okunur/yazılır Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Bir paragrafta Latin satır sonunun kullanılıp kullanılmayacağını belirler. Kalandım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Kaldım olmadan bir paragrafta sol kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Kaldım olmadan bir paragrafta sağ kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Bir paragrafta Sağdan Sola yazma kullanımını belirler. Kalandım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Kaldım olmadan bir paragrafta son satırdan sonraki boşluk miktarını döndürür veya ayarlar. Pozitif bir değer, beyaz alanın yazı tipi boyutunun yüzde olarak ne kadar olacağını belirtir. Negatif bir değer ise beyaz alanın punto cinsinden boyutunu belirtir. Okunur/yazılır Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Kaldım olmadan bir paragrafta ilk satırdan önceki boşluk miktarını döndürür veya ayarlar. Pozitif bir değer, beyaz alanın yazı tipi boyutunun yüzde olarak ne kadar olacağını belirtir. Negatif bir değer ise beyaz alanın punto cinsinden boyutunu belirtir. Okunur/yazılır Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Bir paragrafta temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. Pozitif değer yüzde, negatif değer ise puant cinsinden boyuttur. Kalandım uygulanmaz. Okunur/yazılır Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Bir paragrafın sekmelerini döndürür. Kalandım uygulanmaz. Yalnızca okunur [`ITabCollection`](../itabcollection). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesneyle karşılaştırır. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Kalıtım uygulanmış etkili paragraf biçimlendirme verilerini alır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Karma kodu döndürür. |

### Açıklamalar

Bu sınıf, belirli bir paragraf için tanımlanan paragraf biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken herhangi bir kalıtım uygulanmadığı anlamına gelir, bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler alırsınız.

Kalıtım dahil olmak üzere etkili biçimlendirme parametre değerlerini elde etmek için [`GetEffective`](./geteffective) yöntemini kullanmanız gerekir; bu, bir [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) örneği döndürür.

### Ayrıca Bakınız

* sınıf [PVIObject](../pviobject)
* arabirim [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* arabirim [IParagraphFormat](../iparagraphformat)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->