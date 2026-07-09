---
title: IParagraphFormat
second_title: Aspose.Sildes .NET API Referansı
description: Bu sınıf paragraf biçimlendirme özelliklerini içerir. IParagraphFormatEffectiveData./iparagraphformateffectivedata dışında bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 6590
url: /tr/aspose.slides/iparagraphformat/
---
## IParagraphFormat arayüz

This class contains the paragraph formatting properties. Unlike [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), all properties of this class are writeable.

```csharp
public interface IParagraphFormat
```

## Özellikler

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Bir paragrafta kalıtım olmadan metin hizalamasını alır veya ayarlar. Okuma/yazma [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Paragrafın madde işareti biçimini döndürür. Salt okunur [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Bir paragrafın varsayılan bölüm biçimini döndürür. Kalıtım uygulanmaz. Salt okunur [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Kalıtım olmadan varsayılan sekme boyutunu alır veya ayarlar. Okuma/yazma Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Paragrafın derinliğini alır veya ayarlar. Değer 0 tanımsız anlamına gelir. Okuma/yazma Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Paragrafta Doğu Asya satır sonunun kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okuma/yazma [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Kalıtım olmadan bir paragrafta yazı tipi hizalamasını alır veya ayarlar. Okuma/yazma [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Paragrafta asılı noktalama işaretlerinin kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okuma/yazma [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Kalıtım olmadan paragrafın İlk Satır Girintisi/Asılı Girintisini alır veya ayarlar. Asılı Girinti negatif değerlerle tanımlanabilir. Okuma/yazma Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Paragrafta Latin satır sonunun kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okuma/yazma [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Kalıtım olmadan bir paragrafta sol kenar boşluğunu alır veya ayarlar. Okuma/yazma Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Kalıtım olmadan bir paragrafta sağ kenar boşluğunu alır veya ayarlar. Okuma/yazma Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Okuma/yazma [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Kalıtım olmadan bir paragrafta son satırdan sonraki boşluk miktarını alır veya ayarlar. Pozitif değer, beyaz boşluğun yazı tipi boyutunun yüzde olarak ne kadar olacağını belirtir. Negatif değer, beyaz boşluğun punto cinsinden boyutunu belirtir. Okuma/yazma Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Kalıtım olmadan bir paragrafta ilk satırdan önceki boşluk miktarını alır veya ayarlar. Pozitif değer, beyaz boşluğun yazı tipi boyutunun yüzde olarak ne kadar olacağını belirtir. Negatif değer, beyaz boşluğun punto cinsinden boyutunu belirtir. Okuma/yazma Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Paragrafta temel satırlar arasındaki boşluk miktarını alır veya ayarlar. Pozitif değer yüzde, negatif değer ise punto cinsinden boyuttur. Kalıtım uygulanmaz. Okuma/yazma Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Bir paragrafın sekmelerini döndürür. Kalıtım uygulanmaz. Salt okunur [`ITabCollection`](../itabcollection). |

## Yöntemler

| Name | Description |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Kalıtım uygulandığında etkili paragraf biçimlendirme verilerini alır. |

### Açıklamalar

Bu sınıf, belirli bir paragraf için tanımlanan paragraf biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken hiçbir kalıtım uygulanmadığı ve çoğu durumda "tanımsız" anlamına gelen değerler elde edeceğiniz anlamına gelir.

Kalıtım dahil olmak üzere etkili biçimlendirme parametre değerlerini almak için [`GetEffective`](./geteffective) metodunu kullanmanız gerekir; bu metod bir [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) örneği döndürür.

### Diğer Bağlantılar

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->