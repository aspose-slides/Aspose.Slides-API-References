---
title: IParagraphFormat
second_title: Aspose.Slides için .NET API Referansı
description: Bu sınıf paragraf biçimlendirme özelliklerini içerir. IParagraphFormatEffectiveData./iparagraphformateffectivedata'dan farklı olarak bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 6610
url: /tr/aspose.slides/iparagraphformat/
---
## IParagraphFormat arayüzü

Bu sınıf paragraf biçimlendirme özelliklerini içerir. [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)'in aksine, bu sınıfın tüm özellikleri yazılabilir.

```csharp
public interface IParagraphFormat
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Paragrafta kalıtım olmadan metin hizalamasını alır veya ayarlar. Okunur/Yazılabilir [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Paragrafın madde işareti biçimini döndürür. Salt-okunur [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Paragrafın varsayılan bölüm biçimini döndürür. Kalıtım uygulanmaz. Salt-okunur [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Kalıtım olmadan varsayılan sekme boyutunu alır veya ayarlar. Okunur/Yazılabilir Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Paragrafın derinliğini alır veya ayarlar. Değer 0 tanımsız değeri belirtir. Okunur/Yazılabilir Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Paragrafta Doğu Asya satır sonunun kullanılıp kullanılmayacağını belirler. Kalıtım uygulanmaz. Okunur/Yazılabilir [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Kalıtım olmadan bir paragrafta yazı tipi hizalamasını alır veya ayarlar. Okunur/Yazılabilir [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Paragrafta sarkan noktalama işaretlerinin kullanılıp kullanılmayacağını belirler. Kalıtım uygulanmaz. Okunur/Yazılabilir [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Kalıtım olmadan paragrafın birinci satır girintisini/sarkan girintisini alır veya ayarlar. Sarkan girinti negatif değerlerle tanımlanabilir. Okunur/Yazılabilir Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Paragrafta Latin satır sonunun kullanılıp kullanılmayacağını belirler. Kalıtım uygulanmaz. Okunur/Yazılabilir [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Kalıtım olmadan bir paragrafta sol kenar boşluğunu alır veya ayarlar. Okunur/Yazılabilir Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Kalıtım olmadan bir paragrafta sağ kenar boşluğunu alır veya ayarlar. Okunur/Yazılabilir Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Paragrafta sağdan sola yazımın kullanılıp kullanılmayacağını belirler. Kalıtım uygulanmaz. Okunur/Yazılabilir [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Kalıtım olmadan bir paragrafta son satırdan sonraki boşluk miktarını alır veya ayarlar. Pozitif bir değer, boşluğun yazı tipi boyutunun yüzde olarak ne kadar olacağını belirtir. Negatif bir değer ise boşluğun puan cinsinden boyutunu belirtir. Okunur/Yazılabilir Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Kalıtım olmadan bir paragrafta ilk satırdan önceki boşluk miktarını alır veya ayarlar. Pozitif bir değer, boşluğun yazı tipi boyutunun yüzde olarak ne kadar olacağını belirtir. Negatif bir değer ise boşluğun puan cinsinden boyutunu belirtir. Okunur/Yazılabilir Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Paragrafta temel satırlar arasındaki boşluk miktarını alır veya ayarlar. Pozitif değer yüzde, negatif değer ise puan cinsinden boyuttur. Kalıtım uygulanmaz. Okunur/Yazılabilir Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Paragrafın sekmelerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`ITabCollection`](../itabcollection). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Kalıtım uygulanan etkili paragraf biçimlendirme verilerini alır. |

### Açıklamalar

Bu sınıf, belirli bir paragraf için tanımlanan paragraf biçimlendirme özelliklerini geri döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken hiçbir kalıtım uygulanmadığı anlamına gelir, bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler alırsınız.

Kalıtım dahil olmak üzere etkili biçimlendirme parametre değerlerini elde etmek için [`GetEffective`](./geteffective) yöntemini kullanmanız gerekir; bu yöntem bir [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) örneği döndürür.

### Bakınız

* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->