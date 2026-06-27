---
title: PortionFormat
second_title: Aspose.Slides için .NET API Referansı
description: Bu sınıf, metin bölüm biçimlendirme özelliklerini içerir. IPortionFormatEffectiveData./iportionformateffectivedata aksine bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 9470
url: /tr/aspose.slides/portionformat/
---
## PortionFormat sınıfı

Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. [`IPortionFormatEffectiveData`](../iportionformateffectivedata)'in aksine, bu sınıfın tüm özellikleri yazılabilir.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PortionFormat](portionformat)() | Yeni bir [`PortionFormat`](../portionformat) sınıfı örneği oluşturur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Alternatif bir dilin Id'sini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arabirimine erişim sağlar. Salt-okunur [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Yer imi tanımlayıcısını alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Karmaşık betik yazı tipi bilgisini alır veya ayarlar. Null, yazı tipinin tanımlı olmadığını ve Ana'dan miras alınması gerektiğini gösterir. Okunabilir/Yazılabilir [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Doğu Asya yazı tipi bilgisini alır veya ayarlar. Null, yazı tipinin tanımlı olmadığını ve Ana'dan miras alınması gerektiğini gösterir. Okunabilir/Yazılabilir [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Metin EffectFormat özelliklerini döndürür. Herhangi bir miras uygulanmaz. Salt-okunur [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Üst simge veya alt simge metnini alır veya ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasında olabilir. **float.NaN** değerin tanımlı olmadığını ve Ana'dan miras alınması gerektiğini gösterir. Okunabilir/Yazılabilir Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Metin FillFormat özelliklerini döndürür. Herhangi bir miras uygulanmaz. Salt-okunur [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Yazı tipinin kalın olup olmadığını belirler. Herhangi bir miras uygulanmaz. Okunabilir/Yazılabilir [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Bir bölümün yazı tipi yüksekliğini alır veya ayarlar. **float.NaN** yüksekliğin tanımlı olmadığını ve Ana'dan miras alınması gerektiğini gösterir. Okunabilir/Yazılabilir Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Yazı tipinin italik olup olmadığını belirler. Herhangi bir miras uygulanmaz. Okunabilir/Yazılabilir [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Metin altı çizgi tipini alır veya ayarlar. Herhangi bir miras uygulanmaz. Okunabilir/Yazılabilir [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Metni vurgulamak için kullanılan rengi döndürür. Herhangi bir miras uygulanmaz. Salt-okunur [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyü alır veya ayarlar. Okunabilir/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Köprü yöneticisi. Salt-okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Fare üzerindeyken tanımlanan köprüyü alır veya ayarlar. Okunabilir/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Altı çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden miras alıp almadığını belirler. Okunabilir/Yazılabilir [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Altı çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden miras alıp almadığını belirler. Okunabilir/Yazılabilir [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Kerning'in etkinleştirileceği minimum yazı tipi boyutunu alır veya ayarlar. **float.NaN** değerin tanımlı olmadığını ve Ana'dan miras alınması gerektiğini gösterir. Okunabilir/Yazılabilir Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Sayıların metnin doğu dili özel dikey metin düzenini göz ardı edip etmeyeceğini belirler. Herhangi bir miras uygulanmaz. Okunabilir/Yazılabilir [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Denetleme dilinin Id'sini alır veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Okunabilir/Yazılabilir String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Latin yazı tipi bilgisini alır veya ayarlar. Null, yazı tipinin tanımlı olmadığını ve Ana'dan miras alınması gerektiğini gösterir. Okunabilir/Yazılabilir [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Metin konturlama için LineFormat özelliklerini döndürür. Herhangi bir miras uygulanmaz. Salt-okunur [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Metin yüksekliğinin normalize edilip edilmemesi gerektiğini belirler. Herhangi bir miras uygulanmaz. Okunabilir/Yazılabilir [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Metnin denetlenmemesi gerektiğini belirler. Herhangi bir miras uygulanmaz. Okunabilir/Yazılabilir [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Akıllı etiketin temizlenip temizlenmeyeceğini belirler. Herhangi bir miras uygulanmaz. Okunabilir/Yazılabilir Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Karakterler arası boşluk artışını alır veya ayarlar. **float.NaN** değerin tanımlı olmadığını ve Ana'dan miras alınması gerektiğini gösterir. Okunabilir/Yazılabilir Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Metin bölümü için yazım denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimi engellenir. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Metnin üzerini çizme tipini alır veya ayarlar. Herhangi bir miras uygulanmaz. Okunabilir/Yazılabilir [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Sembolik yazı tipi bilgisini alır veya ayarlar. Null, yazı tipinin tanımlı olmadığını ve Ana'dan miras alınması gerektiğini gösterir. Okunabilir/Yazılabilir [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Metin büyük/küçük harf tipini alır veya ayarlar. Herhangi bir miras uygulanmaz. Okunabilir/Yazılabilir [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Altı çizgi çizgisinin FillFormat özelliklerini döndürür. Herhangi bir miras uygulanmaz. Salt-okunur [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Altı çizgi çizgisini konturlamak için kullanılan LineFormat özelliklerini döndürür. Herhangi bir miras uygulanmaz. Salt-okunur [`ILineFormat`](../ilineformat). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesne ile karşılaştırır. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Miras uygulanan etkili bölüm biçimlendirme verilerini alır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Karma kodu döndürür. |

### Açıklamalar

Bu sınıf, belirli bir bölüm için tanımlanan metin bölümü biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alındığında hiçbir miras uygulanmadığı anlamına gelir; bu nedenle çoğu durumda "tanımsız" anlamına gelen değerler alırsınız.

Miras dahil etkili biçimlendirme parametre değerlerini elde etmek için [`GetEffective`](./geteffective) yöntemini kullanmanız gerekir; bu yöntem bir [`IPortionFormatEffectiveData`](../iportionformateffectivedata) örneği döndürür.

### Örnekler

Aşağıdaki örnekler, PowerPoint Sunumu bir Paragraf'ın bölümüne Latin yazı tipini nasıl atayacağınızı gösterir.

```csharp
[C#]
//Bir sunum dosyasını temsil eden bir sunum nesnesi oluşturur
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides bu özel tanımlayıcıları kullanır (PowerPoint'te kullanılanlara benzer):
// +mn-lt - Ana Yazı Tipi Latin (Küçük Latin Yazı Tipi)
// +mj-lt - Başlık Yazı Tipi Latin (Büyük Latin Yazı Tipi)
// +mn-ea - Ana Yazı Tipi Doğu Asya (Küçük Doğu Asya Yazı Tipi)
// +mj-ea - Ana Yazı Tipi Doğu Asya (Küçük Doğu Asya Yazı Tipi)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Ayrıca Bakınız

* sınıf [BasePortionFormat](../baseportionformat)
* arabirim [IPortionFormat](../iportionformat)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->