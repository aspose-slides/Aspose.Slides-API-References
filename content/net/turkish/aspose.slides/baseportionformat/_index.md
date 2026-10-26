---
title: BasePortionFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Ortak metin bölümü biçimlendirme özellikleri.
type: docs
weight: 970
url: /tr/aspose.slides/baseportionformat/
---
## BasePortionFormat sınıfı

Ortak metin bölümü biçimlendirme özellikleri.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Alternatif bir dilin Id'sini döndürür veya ayarlar. Okunur/yazılır String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arabirimini almayı sağlar. Salt okunur [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Karmaşık betik yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımlı olmadığı ve Ana'dan miras alınması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Doğu Asya yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımlı olmadığı ve Ana'dan miras alınması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Metnin EffectFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Üst metin ya da alt metin değerini döndürür veya ayarlar. Değer -%100 (alt metin) ile %100 (üst metin) arasında olabilir. **float.NaN** değerin tanımsız olduğu ve Ana'dan miras alınması gerektiği anlamına gelir. Okunur/yazılır Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Metnin FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **float.NaN** yüksekliğin tanımsız olduğu ve Ana'dan miras alınması gerektiği anlamına gelir. Okunur/yazılır Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Yazı tipinin itallic olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Metnin alt çizgi türünü döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılır [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Metni vurgulamak için kullanılan rengi döndürür. Kalıtım uygulanmaz. Salt okunur [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden miras alıp almadığını belirler. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden miras alıp almadığını belirler. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Kerning'in etkinleştirileceği minimal yazı tipi boyutunu döndürür veya ayarlar. **float.NaN** değerin tanımsız olduğu ve Ana'dan miras alınması gerektiği anlamına gelir. Okunur/yazılır Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Sayıların metnin Doğu dili özgü dikey metin düzenini göz ardı edip etmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Bir düzeltme dilinin Id'sini döndürür veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Okunur/yazılır String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Latin yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan miras alınması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Metin konturlama için LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Metnin düzeltme yapılmaması gerekir mi belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Karakterler arası boşluk artışını döndürür veya ayarlar. **float.NaN** değerin tanımsız olduğu ve Ana'dan miras alınması gerektiği anlamına gelir. Okunur/yazılır Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Metin bölümü için yazım denetiminin etkin olup olmadığını belirten bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimi engellenir. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Metnin üstü çizili (strikethrough) türünü döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılır [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Sembolik yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan miras alınması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Metnin büyük/küçük harf tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılır [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Alt çizgi satırının FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Alt çizgi satırını konturlamak için kullanılan LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt okunur [`ILineFormat`](../ilineformat). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesneyle karşılaştırır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Karma kodunu döndürür. |

### Ayrıca Bakınız

* sınıf [PVIObject](../pviobject)
* arabirim [IBasePortionFormat](../ibaseportionformat)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->