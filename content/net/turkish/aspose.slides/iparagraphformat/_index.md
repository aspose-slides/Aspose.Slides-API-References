---
title: IParagraphFormat
second_title: Aspose.Sildes .NET için API Referansı
description: Bu sınıf paragraf biçimlendirme özelliklerini içerir. IParagraphFormatEffectiveData./iparagraphformateffectivedata'dan farklı olarak bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 6570
url: /tr/aspose.slides/iparagraphformat/
---
## IParagraphFormat arayüz

Bu sınıf, paragraf biçimlendirme özelliklerini içerir. [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)'in aksine, bu sınıfın tüm özellikleri yazılabilir.

```csharp
public interface IParagraphFormat
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Paragrafta, kalıtım olmadan metin hizalamasını alır veya ayarlar. Okunur/Yazılır [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Paragrafın madde işareti biçimini döndürür. Salt okunur [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Paragrafın varsayılan bölüm biçimini döndürür. Kalmıtım uygulanmaz. Salt okunur [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Kalmıtım olmadan varsayılan sekme boyutunu alır veya ayarlar. Okunur/Yazılır Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Paragrafın derinliğini alır veya ayarlar. 0 değeri tanımsız değeri belirtir. Okunur/Yazılır Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Paragrafta Doğu Asya satır sonu kullanımını belirler. Kalmıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Kalmıtım olmadan paragrafta bir yazı tipi hizalamasını alır veya ayarlar. Okunur/Yazılır [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Paragrafta sarkan noktalama işaretlerinin kullanılıp kullanılmayacağını belirler. Kalmıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Kalmıtım olmadan paragrafın İlk Satır Girintisi/Sarkan Girintisini alır veya ayarlar. Sarkan Girinti negatif değerlerle tanımlanabilir. Okunur/Yazılır Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Paragrafta Latin satır sonu kullanımını belirler. Kalmıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Kalmıtım olmadan paragrafta sol kenar boşluğunu alır veya ayarlar. Okunur/Yazılır Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Kalmıtım olmadan paragrafta sağ kenar boşluğunu alır veya ayarlar. Okunur/Yazılır Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Paragrafta sağdan sola yazımın kullanılıp kullanılmadığını belirler. Kalmıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Kalmıtım olmadan paragrafta son satırdan sonraki boşluk miktarını alır veya ayarlar. Pozitif değer, boşluğun yazı tipi boyutunun yüzde olarak ne kadar olacağını belirtir. Negatif değer, boşluğun nokta cinsinden boyutunu belirtir. Okunur/Yazılır Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Kalmıtım olmadan paragrafta ilk satırdan önceki boşluk miktarını alır veya ayarlar. Pozitif değer, boşluğun yazı tipi boyutunun yüzde olarak ne kadar olacağını belirtir. Negatif değer, boşluğun nokta cinsinden boyutunu belirtir. Okunur/Yazılır Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Paragrafta temel satırlar arasındaki boşluk miktarını alır veya ayarlar. Pozitif değer yüzde, negatif değer nokta cinsinden boyuttur. Kalmıtım uygulanmaz. Okunur/Yazılır Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Paragrafta sekme ayarlarını döndürür. Kalmıtım uygulanmaz. Salt okunur [`ITabCollection`](../itabcollection). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Kalıtım uygulanan etkili paragraf biçimlendirme verilerini alır. |

### Açıklamalar

Bu sınıf, belirli bir paragraf için tanımlanan paragraf biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken kalıtım uygulanmadığı anlamına gelir, bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler elde edersiniz.

Kalıtım dahil olmak üzere etkili biçimlendirme parametre değerlerini almak için [`GetEffective`](./geteffective) yöntemini kullanmanız gerekir; bu yöntem bir [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) örneği döndürür.

### Diğer Bağlantılar

* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->