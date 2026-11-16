---
title: ParagraphFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Bu sınıf paragraf biçimlendirme özelliklerini içerir. IParagraphFormatEffectiveData./iparagraphformateffectivedata'dan farklı olarak, bu sınıftaki tüm özellikler yazılabilir.
type: docs
weight: 9330
url: /tr/aspose.slides/paragraphformat/
---
## ParagraphFormat sınıfı

Bu sınıf, paragraf biçimlendirme özelliklerini içerir. [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)'in aksine, bu sınıftaki tüm özellikler yazılabilir.

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
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Paragrafta kalıtım olmadan metin hizalamasını döndürür veya ayarlar. Okunur/yazılır [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arabirimine erişim sağlar. Sadece okunur [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Kalıtım olmadan varsayılan sekme boyutunu döndürür veya ayarlar. Okunur/yazılır Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Paragrafta Doğu Asya satır sonu kullanımını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Paragrafta kalıtım olmadan yazı tipi hizalamasını döndürür veya ayarlar. Okunur/yazılır [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Paragrafta asılı noktalama işaretinin kullanımını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Paragrafta kalıtım olmadan İlk Satır Girintisi/Asılı Girinti döndürür veya ayarlar. Asılı Girinti negatif değerlerle tanımlanabilir. Okunur/yazılır Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Paragrafta Latin satır sonu kullanımını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Paragrafta kalıtım olmadan sol kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Paragrafta kalıtım olmadan sağ kenar boşluğunu döndürür veya ayarlar. Okunur/yazılır Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Paragrafta sağdan sola yazımın kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Paragrafta kalıtım olmadan son satırdan sonraki boşluk miktarını döndürür veya ayarlar. Pozitif bir değer, boşluğun yazı tipi boyutunun yüzdesini belirtir. Negatif bir değer, boşluğun punto cinsinden boyutunu belirtir. Okunur/yazılır Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Paragrafta kalıtım olmadan ilk satırdan önceki boşluk miktarını döndürür veya ayarlar. Pozitif bir değer, boşluğun yazı tipi boyutunun yüzdesini belirtir. Negatif bir değer, boşluğun punto cinsinden boyutunu belirtir. Okunur/yazılır Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Paragrafta temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. Pozitif değer yüzde, negatif değer punto cinsinden boyut anlamına gelir. Kalıtım uygulanmaz. Okunur/yazılır Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Paragrafın sekmelerini döndürür. Kalıtım uygulanmaz. Sadece okunur [`ITabCollection`](../itabcollection). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesneyle karşılaştırır. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Uygulanan kalıtımla etkili paragraf biçimlendirme verilerini alır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Hash kodunu döndürür. |

### Açıklamalar

Bu sınıf, belirli bir paragraf için tanımlanan paragraf biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken kalıtımın uygulanmadığı anlamına gelir; bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler elde edersiniz.

Kalıtım dahil olmak üzere etkili biçimlendirme parametre değerlerini almak için [`GetEffective`](./geteffective) yöntemini kullanmanız gerekir; bu yöntem bir [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) örneği döndürür.

### Ayrıca Bakınız

* sınıf [PVIObject](../pviobject)
* arayüz [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* arayüz [IParagraphFormat](../iparagraphformat)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->