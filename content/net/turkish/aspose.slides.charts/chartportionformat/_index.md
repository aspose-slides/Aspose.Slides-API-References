---
title: ChartPortionFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Bu sınıf, grafiklerde kullanılan chart portion biçimlendirme özelliklerini içerir. IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata'dan farklı olarak bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 1440
url: /tr/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat sınıfı

Bu sınıf, grafiklerde kullanılan chart portion biçimlendirme özelliklerini içerir. [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)'den farklı olarak bu sınıfın tüm özellikleri yazılabilir.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Alternatif bir dilin Id'sini döndürür veya ayarlar. Okunur/yazılır String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arayüzünü almayı sağlar. Sadece okunur [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Karmaşık script yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Doğu Asya yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Metin EffectFormat özelliklerini döndürür. Devralma uygulanmaz. Sadece okunur [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Üst simge veya alt simge metnini döndürür veya ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. **float.NaN** değerin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Metin FillFormat özelliklerini döndürür. Devralma uygulanmaz. Sadece okunur [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Yazı tipinin kalın olup olmadığını belirler. Devralma uygulanmaz. Okunur/yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **float.NaN** yüksekliğin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Yazı tipinin italik olup olmadığını belirler. Devralma uygulanmaz. Okunur/yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Metin altı çizgi tipini döndürür veya ayarlar. Devralma uygulanmaz. Okunur/yazılır [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Metni vurgulamak için kullanılan rengi döndürür. Devralma uygulanmaz. Sadece okunur [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden devralınıp alınmadığını belirler. Okunur/yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden devralınıp alınmadığını belirler. Okunur/yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür veya ayarlar. **float.NaN** değerin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Sayıların metnin Doğu dili özel dikey metin yerleşimini görmezden gelip gelmemesini belirler. Devralma uygulanmaz. Okunur/yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Denetleme dili Id'sini döndürür veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Okunur/yazılır String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Latin yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Metin kenarlığı için LineFormat özelliklerini döndürür. Devralma uygulanmaz. Sadece okunur [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Devralma uygulanmaz. Okunur/yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Metnin denetlenmemesi gerektiğini belirler. Devralma uygulanmaz. Okunur/yazılır [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Karakterler arası boşluk artışını döndürür veya ayarlar. **float.NaN** değerin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Metin bölümü için yazım denetiminin etkin olup olmadığını belirten bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimi bastırılır. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Metnin üstü çizili tipini döndürür veya ayarlar. Devralma uygulanmaz. Okunur/yazılır [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Sembolik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Metnin büyük/küçük harf türünü döndürür veya ayarlar. Devralma uygulanmaz. Okunur/yazılır [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Alt çizgi satırının FillFormat özelliklerini döndürür. Devralma uygulanmaz. Sadece okunur [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Alt çizgi satırını kenarlıklamak için kullanılan LineFormat özelliklerini döndürür. Devralma uygulanmaz. Sadece okunur [`ILineFormat`](../../aspose.slides/ilineformat). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesne ile karşılaştırır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Karma (hash) kodunu döndürür. |

### Açıklamalar

Bu sınıf, belirli bir bölüm için tanımlanmış metin bölümü biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken devralmanın uygulanmadığı anlamına gelir, bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler elde edersiniz.

Devralınan değerler dahil etkili biçimlendirme parametre değerlerini almak için [`GetEffective`](../../aspose.slides/portionformat/geteffective) yöntemini kullanmanız gerekir; bu yöntem bir [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) örneği döndürür.

### Ayrıca Bakınız

* sınıf [BasePortionFormat](../../aspose.slides/baseportionformat)
* arayüz [IChartPortionFormat](../ichartportionformat)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->