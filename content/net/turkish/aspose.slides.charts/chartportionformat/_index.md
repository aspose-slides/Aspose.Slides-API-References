---
title: ChartPortionFormat
second_title: Aspose.Sildes .NET API Referansı
description: Bu sınıf, grafiklerde kullanılan grafik bölümü biçimlendirme özelliklerini içerir. Unlike IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata tüm özellikleri yazılabilir.
type: docs
weight: 1410
url: /tr/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat sınıfı

Bu sınıf, grafiklerde kullanılan grafik bölümü biçimlendirme özelliklerini içerir. [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)'nin aksine, bu sınıfın tüm özellikleri yazılabilir.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Alternatif bir dilin Id değerini alır veya ayarlar. Okunur/Yazılabilir String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arayüzünü almayı sağlar. Salt-okunur [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Karmaşık script yazı tipi bilgisini alır veya ayarlar. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Okunur/Yazılabilir [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Doğu Asya yazı tipi bilgisini alır veya ayarlar. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Okunur/Yazılabilir [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Metin EffectFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Üst simge ya da alt simge metnini alır veya ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasında değişir. **float.NaN** değerin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Okunur/Yazılabilir Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Metin FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/Yazılabilir [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Bir bölümün yazı tipi yüksekliğini alır veya ayarlar. **float.NaN** değerin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okunur/Yazılabilir Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Yazı tipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/Yazılabilir [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Metin alt çizgi tipini alır veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılabilir [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Metni vurgulamak için kullanılan rengi alır. Kalıtım uygulanmaz. Salt-okunur [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden devralınıp alınmadığını belirler. Okunur/Yazılabilir [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden devralınıp alınmadığını belirler. Okunur/Yazılabilir [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Kerningi açılması gereken minimal yazı tipi boyutunu alır veya ayarlar. **float.NaN** değerin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okunur/Yazılabilir Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Sayıların metnin doğu dilleri için özel dikey metin düzenini göz ardı edip etmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/Yazılabilir [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Düzeltme dili Id'sini alır veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Okunur/Yazılabilir String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Latin yazı tipi bilgisini alır veya ayarlar. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Okunur/Yazılabilir [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Metin kenarlığı için LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Metnin yüksekliğinin normalleştirilip normalize edilmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/Yazılabilir [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Metnin denetlenmemesi gerektiğini belirler. Kalıtım uygulanmaz. Okunur/Yazılabilir [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Karakterler arası boşluk artışını alır veya ayarlar. **float.NaN** değerin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okunur/Yazılabilir Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Metin bölümünde yazım denetiminin etkin olup olmadığını belirten bir değer alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimi bastırılır. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Metnin üstü çizili tipini alır veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılabilir [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Sembolik yazı tipi bilgisini alır veya ayarlar. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Okunur/Yazılabilir [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Metin büyük/küçük harf durumunun tipini alır veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılabilir [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Alt çizgi hattının FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Alt çizgi hattını çerçevelemek için kullanılan LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`ILineFormat`](../../aspose.slides/ilineformat). |

## Metotlar

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesneyle karşılaştırır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Hash kodunu döndürür. |

### Açıklamalar

Bu sınıf, belirli bölüm için tanımlanan metin bölümü biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değer alırken hiçbir kalıtım uygulanmadığı anlamına gelir; bu nedenle çoğu durumda "tanımsız" anlamına gelen değerler elde edersiniz.

Kalıtımlı dahil olmak üzere etkili biçimlendirme parametresi değerlerini almak için [`GetEffective`](../../aspose.slides/portionformat/geteffective) metodunu kullanmanız gerekir; bu metot bir [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) örneği döndürür.

### Ayrıca Bakınız

* sınıf [BasePortionFormat](../../aspose.slides/baseportionformat)
* arayüz [IChartPortionFormat](../ichartportionformat)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->