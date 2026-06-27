---
title: IBasePortionFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Bu sınıf metin bölümü biçimlendirme özelliklerini içerir. IPortionFormatEffectiveData./iportionformateffectivedata dan farklı olarak, bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 5290
url: /tr/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat arayüz

Bu sınıf metin bölümü biçimlendirme özelliklerini içerir. [`IPortionFormatEffectiveData`](../iportionformateffectivedata)'in aksine, bu sınıfın tüm özellikleri yazılabilir.

```csharp
public interface IBasePortionFormat
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Alternatif bir dilin Kimliğini alır veya ayarlar. Okunur/Yazılır String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Karmaşık betik yazı tipi bilgisini alır veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtım alması gerektiği anlamına gelir. Okunur/Yazılır [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Doğu Asya yazı tipi bilgisini alır veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtım alması gerektiği anlamına gelir. Okunur/Yazılır [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Metnin EffectFormat özelliklerini alır. Kalıtım uygulanmaz. Sadece okunur [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Üst simge veya alt simge metnini alır veya ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. **float.NaN** değerinin tanımsız olduğunu ve Master'dan kalıtım alması gerektiğini gösterir. Okunur/Yazılır Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Metnin FillFormat özelliklerini alır. Kalıtım uygulanmaz. Sadece okunur [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Bir parçanın yazı tipi yüksekliğini alır veya ayarlar. **float.NaN**, yüksekliğin tanımsız olduğunu ve Master'dan kalıtım alması gerektiğini gösterir. Okunur/Yazılır Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Yazı tipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Metin alt çizgi tipini alır veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılır [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Metni vurgulamak için kullanılan rengi alır. Kalıtım uygulanmaz. Sadece okunur [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden kalıtım alıp almadığını belirler. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden kalıtım alıp almadığını belirler. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Kernin etkinleştirilmesi gereken minimum yazı tipi boyutunu alır veya ayarlar. **float.NaN** değerin tanımsız olduğunu ve Master'dan kalıtım alması gerektiğini gösterir. Okunur/Yazılır Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Sayıların, metnin Doğu dili özel dikey metin yerleşimini göz ardı edip etmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Denetleme dili Kimliğini alır veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Okunur/Yazılır String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Latin yazı tipi bilgisini alır veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtım alması gerektiği anlamına gelir. Okunur/Yazılır [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Metin kenarlığı için LineFormat özelliklerini alır. Kalıtım uygulanmaz. Sadece okunur [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Metnin yüksekliğinin normalize edilip edilmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Metnin denetlenmemesi gerekip gerekmediğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Karakterler arası boşluk artışını alır veya ayarlar. **float.NaN** değerin tanımsız olduğunu ve Master'dan kalıtım alması gerektiğini gösterir. Okunur/Yazılır Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Metin bölümü için yazım denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimi bastırılır. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Metnin üstü çizili tipini alır veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılır [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Sembolik yazı tipi bilgisini alır veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Master'dan kalıtım alması gerektiği anlamına gelir. Okunur/Yazılır [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Metin büyük/küçük harf tipini alır veya ayarlar. Kalıtım uygulanmaz. Okunur/Yazılır [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Alt çizgi hattının FillFormat özelliklerini alır. Kalıtım uygulanmaz. Sadece okunur [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Alt çizgi hattını kenarlıkla vurgulamak için kullanılan LineFormat özelliklerini alır. Kalıtım uygulanmaz. Sadece okunur [`ILineFormat`](../ilineformat). |

### Açıklamalar

Bu sınıf, belirli bölüm için tanımlanmış metin bölümü biçimlendirme özelliklerini almak ve değiştirmek için kullanılır. Bu, değerler alınırken kalıtım uygulanmadığı anlamına gelir; bu nedenle çoğu durumda "tanımsız" anlamına gelen değerler elde edersiniz.

Miras alınan dahil olmak üzere geçerli biçimlendirme parametresi değerlerini elde etmek için [`GetEffective`](../iportionformat/geteffective) yöntemini kullanmanız gerekir; bu yöntem bir [`IPortionFormatEffectiveData`](../iportionformateffectivedata) örneği döndürür.

### Ayrıca Bakınız

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->