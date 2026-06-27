---
title: BasePortionFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Ortak metin parçası biçimlendirme özellikleri.
type: docs
weight: 950
url: /tr/aspose.slides/baseportionformat/
---
## BasePortionFormat sınıfı

Ortak metin parçası biçimlendirme özellikleri.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Alternatif bir dilin Kimliğini döndürür veya ayarlar. Okunur/yazılır String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arayüzünü almayı sağlar. Salt-okunur [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Karmaşık yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Doğu Asya yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Metin EffectFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Üst/batı yazı tipini döndürür veya ayarlar. Değer -%100 (alt satır) ile %100 (üst satır) arasında. **float.NaN** değerin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Metin FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Parçanın yazı tipi yüksekliğini döndürür veya ayarlar. **float.NaN** yükseklik tanımsızdır ve Master'dan devralınması gerekir. Okunur/yazılır Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Yazı tipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Metin alt çizgi tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılır [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Metni vurgulamak için kullanılan rengi döndürür. Kalıtım uygulanmaz. Salt-okunur [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden devralınıp alınmadığını belirler. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden devralınıp alınmadığını belirler. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Kernleme aktif edilmesi gereken minimal yazı tipi boyutunu döndürür veya ayarlar. **float.NaN** değerin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Sayıların, metnin doğu dili-spesifik dikey metin düzenini göz ardı edip etmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Denetim dilinin Kimliğini döndürür veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Okunur/yazılır String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Latin yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Metin anahatlandırması için LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Metnin denetlenmemesi gerektiğini belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Karakterler arası boşluk artışını döndürür veya ayarlar. **float.NaN** değer tanımsızdır ve Master'dan devralınması gerekir. Okunur/yazılır Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Metin parçası için yazım denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimi bastırılır. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Metnin üstü çizili tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılır [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Sembolik yazı tipi bilgilerini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Metnin büyük harfli olması tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılır [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Alt çizgi satırının FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Alt çizgi satırını anahatlandırmak için kullanılan LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`ILineFormat`](../ilineformat). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesneyle karşılaştırır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Karma kodu döndürür. |

### İlgili

* sınıf [PVIObject](../pviobject)
* arayüz [IBasePortionFormat](../ibaseportionformat)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->