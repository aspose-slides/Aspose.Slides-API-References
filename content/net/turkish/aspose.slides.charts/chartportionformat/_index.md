---
title: ChartPortionFormat
second_title: Aspose.Sildes for .NET API Referansı
description: Bu sınıf, grafiklerde kullanılan grafik bölümü biçimlendirme özelliklerini içerir. IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata'dan farklı olarak, bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 1430
url: /tr/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat sınıfı

This class contains the chart portion formatting properties used in charts. Unlike [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Özellikler

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Alternatif bir dilin Id'sini döndürür veya ayarlar. Okunur/Yazılır String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arayüzünü almayı sağlar. Sadece okunur [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Karmaşık betik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okunur/Yazılır [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Doğu Asya yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okunur/Yazılır [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Metin EffectFormat özelliklerini döndürür. Kalıtım uygulanmaz. Sadece okunur [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Üst simge veya alt simge metnini döndürür veya ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. **float.NaN** değerinin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okunur/Yazılır Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Metin FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Sadece okunur [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **float.NaN** yüksekliğinin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okunur/Yazılır Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Yazı tipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Metin altı çizgi tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılır [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Metni vurgulamak için kullanılan rengi döndürür. Kalıtım uygulanmaz. Sadece okunur [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Altı çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden devralınıp alınmadığını belirler. Okunur/Yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Altı çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden devralınıp alınmadığını belirler. Okunur/Yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | En küçük yazı tipi boyutunu döndürür veya ayarlar; bu boyut için kerning etkinleştirilir. **float.NaN** değerinin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okunur/Yazılır Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Sayıların metnin doğu dilleri için özel dikey yerleşimini göz ardı edip etmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Proofing dilinin Id'sini döndürür veya ayarlar. İmlâ ve dilbilgisi denetimi için kullanılır. Okunur/Yazılır String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Latin yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okunur/Yazılır [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Metin kenarlığı için LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Sadece okunur [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Metin yüksekliğinin normalize edilip edilmemesi gerektiğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Metnin doğrulanmaması gerektiğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Karakterler arası boşluk artışını döndürür veya ayarlar. **float.NaN** değerinin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okunur/Yazılır Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Metin bölümü için imla denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için imla denetimi bastırılır. True olarak ayarlandığında, imla denetimine izin verilir. Varsayılan değer `false`tır. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Metnin üstü çizili tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılır [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Sembolik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okunur/Yazılır [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Metin büyük/küçük harf biçimini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılır [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Alt çizgi çizgisinin FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Sadece okunur [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Alt çizgi çizgisini çerçevelemek için kullanılan LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Sadece okunur [`ILineFormat`](../../aspose.slides/ilineformat). |

## Yöntemler

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesne ile karşılaştırır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Karma kodu döndürür. |

### Açıklamalar

Bu sınıf, belirli bölüm için tanımlanan metin bölümü biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken kalıtımın uygulanmadığı anlamına gelir; bu nedenle çoğu durumda “tanımsız” anlamına gelen değerler elde edersiniz.

Kalıtım dahil olmak üzere etkili biçimlendirme parametre değerlerini elde etmek için [`GetEffective`](../../aspose.slides/portionformat/geteffective) metodunu kullanmanız gerekir; bu metod bir [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) örneği döndürür.

### Ayrıca Bakınız

* sınıf [BasePortionFormat](../../aspose.slides/baseportionformat)
* arayüz [IChartPortionFormat](../ichartportionformat)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->