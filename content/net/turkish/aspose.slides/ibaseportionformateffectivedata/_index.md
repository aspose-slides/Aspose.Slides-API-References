---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes for .NET API Referansı
description: Etkili metin bölümü biçimlendirme özelliklerini içeren değiştirilemez nesneler için temel arayüz.
type: docs
weight: 5300
url: /tr/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData arayüzü

Etkili metin bölümü biçimlendirme özelliklerini içeren, değiştirilemez nesneler için temel arayüz.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Alternatif bir dilin Id'sini döndürür. Salt okunur String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Kompleks script yazı tipi bilgilerini döndürür. Salt okunur [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Doğu Asya yazı tipi bilgilerini döndürür. Salt okunur [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Metnin EffectFormat özelliklerini döndürür. Salt okunur [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Üst simge veya alt simge metnini döndürür. Değer -%100 (alt simge) ile %100 (üst simge) arasında. Salt okunur Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Metnin FillFormat özelliklerini döndürür. Salt okunur [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Yazı tipinin kalın olup olmadığını belirler. Salt okunur Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Metin bölümünün yazı tipi yüksekliğini puan cinsinden döndürür. Salt okunur Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Yazı tipinin italik olup olmadığını belirler. Salt okunur Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Metin alt çizgi tipini döndürür. Salt okunur [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Metni vurgulamak için kullanılan rengi döndürür. Salt okunur Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerini devralıp almadığını belirler. Salt okunur Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerini devralıp almadığını belirler. Salt okunur Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Kerninge başlaması gereken minimum yazı tipi boyutunu döndürür. Salt okunur Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Sayıların metnin Doğu dili özgü dikey metin yerleşimini görmezden gelmesi gerekip gerekmediğini belirler. Salt okunur Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Bir dilin Id'sini döndürür. Salt okunur String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Latin yazı tipi bilgilerini döndürür. Salt okunur [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Metin kenarlığı için LineFormat özelliklerini döndürür. Salt okunur [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Metin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Salt okunur Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Metnin denetlenmemesi gerektiğini belirler. Salt okunur Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Akıllı etiketin temizlenip temizlenmeyeceğini belirler. Salt okunur Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Karakterler arası boşluk artışını puan cinsinden döndürür. Salt okunur Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Metnin üstü çizili tipini döndürür. Salt okunur [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Sembolik yazı tipi bilgilerini döndürür. Salt okunur [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Metnin büyük harf döndürme tipini döndürür. Salt okunur [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Alt çizgi satırının FillFormat özelliklerini döndürür. Salt okunur [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Alt çizgi satırını çerçevelemek için kullanılan LineFormat özelliklerini döndürür. Salt okunur [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Diğer Bilgiler

* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->