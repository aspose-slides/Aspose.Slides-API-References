---
title: IBasePortionFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. IPortionFormatEffectiveData./iportionformateffectivedata'dan farklı olarak, bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 5330
url: /tr/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat arayüz

Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. [`IPortionFormatEffectiveData`](../iportionformateffectivedata)'den farklı olarak, bu sınıfın tüm özellikleri yazılabilir.

```csharp
public interface IBasePortionFormat
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Alternatif bir dilin Id'sini döndürür veya ayarlar. Okuma/Yazma String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Karmaşık betik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okuma/Yazma [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Doğu Asya yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okuma/Yazma [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Metin EffectFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Üst simge veya alt simge metnini döndürür veya ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. **float.NaN** değerin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okuma/Yazma Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Metin FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okuma/Yazma [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **float.NaN** yüksekliğin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okuma/Yazma Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Yazı tipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. Okuma/Yazma [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Metin alt çizgi tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okuma/Yazma [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Metni vurgulamak için kullanılan rengi döndürür. Kalıtım uygulanmaz. Salt-okunur [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden devralınıp alınmadığını belirler. Okuma/Yazma [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden devralınıp alınmadığını belirler. Okuma/Yazma [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür veya ayarlar. **float.NaN** değerin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okuma/Yazma Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Sayıların, metnin doğu diline özgü dikey metin düzenini yok sayıp saymaması gerektiğini belirler. Kalıtım uygulanmaz. Okuma/Yazma [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Denetleme dilinin Id'sini döndürür veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Okuma/Yazma String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Latin yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okuma/Yazma [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Metin dış hatları için LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Kalıtım uygulanmaz. Okuma/Yazma [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Metnin denetlenmemesi gerektiğini belirler. Kalıtım uygulanmaz. Okuma/Yazma [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Karakterler arası boşluk artışını döndürür veya ayarlar. **float.NaN** değerin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okuma/Yazma Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Metin bölümü için imla denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için imla denetimleri bastırılır. True olarak ayarlandığında, imla denetimine izin verilir. Varsayılan değer `false`'dur. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Metnin üzerini çizme tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okuma/Yazma [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Sembolik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan devralınması gerektiği anlamına gelir. Okuma/Yazma [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Metin büyük/küçük harf biçimini döndürür veya ayarlar. Kalıtım uygulanmaz. Okuma/Yazma [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Alt çizgi satırının FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Alt çizgi satırını dış hatlamak için kullanılan LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Salt-okunur [`ILineFormat`](../ilineformat). |

### Açıklamalar

Bu sınıf, belirli bölüm için tanımlanan metin bölümü biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken kalıtımın uygulanmadığı anlamına gelir; bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler elde edersiniz.

Kalıtım dahil olmak üzere geçerli biçimlendirme parametresi değerlerini elde etmek için [`GetEffective`](../iportionformat/geteffective) metodunu kullanmanız gerekir; bu metod bir [`IPortionFormatEffectiveData`](../iportionformateffectivedata) örneği döndürür.

### Ayrıca Bakınız

* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->