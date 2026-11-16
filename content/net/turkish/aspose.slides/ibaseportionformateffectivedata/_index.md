---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes için .NET API Referansı
description: Etkili metin bölümü biçimlendirme özelliklerini içeren değiştirilemez nesneler için temel arayüz.
type: docs
weight: 5340
url: /tr/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData arayüz

Etkili metin bölümü biçimlendirme özelliklerini içeren değiştirilemez nesneler için temel arayüz.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Alternatif bir dilin kimliğini döndürür. Yalnızca okunabilir String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Kompleks betik yazı tipi bilgisini döndürür. Yalnızca okunabilir [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Doğu Asya yazı tipi bilgisini döndürür. Yalnızca okunabilir [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Metin EffectFormat özelliklerini döndürür. Yalnızca okunabilir [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Üst simge ya da alt simge metnini döndürür. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. Yalnızca okunabilir Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Metin FillFormat özelliklerini döndürür. Yalnızca okunabilir [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Yazı tipinin kalın olup olmadığını belirler. Yalnızca okunabilir Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Metin bölümünün yazı tipi yüksekliğini puan cinsinden döndürür. Yalnızca okunabilir Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Yazı tipinin italik olup olmadığını belirler. Yalnızca okunabilir Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Metin alt çizgi tipini döndürür. Yalnızca okunabilir [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Metni vurgulamak için kullanılan rengi döndürür. Yalnızca okunabilir Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını ya da metnin FillFormat özelliklerinden devralınıp alınmadığını belirler. Yalnızca okunabilir Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını ya da metnin LineFormat özelliklerinden devralınıp alınmadığını belirler. Yalnızca okunabilir Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür. Yalnızca okunabilir Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Sayıların, metnin doğu dili özellikli dikey metin yerleşimini göz ardı edip etmeyeceğini belirler. Yalnızca okunabilir Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Bir dilin kimliğini döndürür. Yalnızca okunabilir String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Latin yazı tipi bilgisini döndürür. Yalnızca okunabilir [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Metin anahatlandırması için LineFormat özelliklerini döndürür. Yalnızca okunabilir [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Bir metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Yalnızca okunabilir Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Metnin düzeltme yapılmaması gerekip gerekmediğini belirler. Yalnızca okunabilir Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Akıllı etiketin temizlenip temizlenmeyeceğini belirler. Yalnızca okunabilir Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Karakterler arası boşluk artışını puan cinsinden döndürür. Yalnızca okunabilir Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Bir metnin üstü çizili tipini döndürür. Yalnızca okunabilir [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Sembolik yazı tipi bilgini döndürür. Yalnızca okunabilir [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Metin büyük/küçük harf tipini döndürür. Yalnızca okunabilir [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Alt çizgi satırı FillFormat özelliklerini döndürür. Yalnızca okunabilir [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Alt çizgi satırını anahatlandırmak için kullanılan LineFormat özelliklerini döndürür. Yalnızca okunabilir [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### İlgili

* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->