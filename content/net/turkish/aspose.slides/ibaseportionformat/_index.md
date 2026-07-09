---
title: IBasePortionFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. IPortionFormatEffectiveData./iportionformateffectivedata'ye kıyasla, bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 5310
url: /tr/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat arayüz

Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. [`IPortionFormatEffectiveData`](../iportionformateffectivedata) dışındakiler gibi, bu sınıfın tüm özellikleri yazılabilir.

```csharp
public interface IBasePortionFormat
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Alternatif bir dilin kimliğini döndürür veya ayarlar. Okunur/yazılır String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Karmaşık betik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Doğu Asya yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Metin EffectFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca-okunur [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Üst/büste metnini döndürür veya ayarlar. Değer -%100 (alt) ile %100 (üst) arasındadır. **float.NaN** değerin tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. Okunur/yazılır Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Metin FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca-okunur [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **float.NaN** yükseklik tanımsızdır ve Master'dan kalıtılması gerekir. Okunur/yazılır Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Yazı tipinin itallic olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Metin alt çizgi tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılır [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Metni vurgulamak için kullanılan rengi döndürür. Kalıtım uygulanmaz. Yalnızca-okunur [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden devralınıp devralınmadığını belirler. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden devralınıp devralınmadığını belirler. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür veya ayarlar. **float.NaN** değer tanımsızdır ve Master'dan kalıtılması gerekir. Okunur/yazılır Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Sayıların, metnin doğu diline özgü dikey metin düzenini görmezden gelip gelmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Denetim dilinin kimliğini döndürür veya ayarlar. Yazım ve dil bilgisi denetimi için kullanılır. Okunur/yazılır String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Latin yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Metin kenarlığı için LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca-okunur [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Metnin denetlenip denetlenmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/yazılır [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Karakterler arası boşluk artışını döndürür veya ayarlar. **float.NaN** değer tanımsızdır ve Master'dan kalıtılması gerekir. Okunur/yazılır Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Metin bölümü için imla denetiminin etkin olup olmadığını belirtir. Bu özellik false olarak ayarlandığında metin öğeleri için imla denetimi bastırılır. True olarak ayarlandığında imla denetimi izin verilir. Varsayılan değer `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Metnin üstü çizili tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılır [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Sembolik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. Okunur/yazılır [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Metnin büyük/küçük harf tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okunur/yazılır [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Alt çizgi satırının FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca-okunur [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Alt çizgi satırını kenarlamak için kullanılan LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca-okunur [`ILineFormat`](../ilineformat). |

### Açıklamalar

Bu sınıf, belirli bölüm için tanımlanan metin bölümü biçimlendirme özelliklerini döndürmek ve manipüle etmek için kullanılır. Bu, değerler alınırken kalıtımın uygulanmadığı anlamına gelir, bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler alırsınız.

Kalıtım dahil olmak üzere etkili biçimlendirme parametre değerlerini almak için [`GetEffective`](../iportionformat/geteffective) yöntemini kullanmanız gerekir; bu yöntem bir [`IPortionFormatEffectiveData`](../iportionformateffectivedata) örneği döndürür.

### Ayrıca Bakınız

* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->