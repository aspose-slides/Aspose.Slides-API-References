---
title: PortionFormat
second_title: Aspose.Sildes için .NET API Referansı
description: Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. IPortionFormatEffectiveData./iportionformateffectivedata'dan farklı olarak bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 9510
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
| [PortionFormat](portionformat)() | Yeni bir [`PortionFormat`](../portionformat) sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Alternatif bir dilin kimliğini döndürür veya ayarlar. Okuma/yazma String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arayüzüne erişim sağlar. Yalnızca okunabilir [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Yer imi tanımlayıcısını döndürür veya ayarlar. Okuma/yazma String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Karmaşık betik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okuma/yazma [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Doğu Asya yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okuma/yazma [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Metin EffectFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Üst simge veya alt simge metnini döndürür veya ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. **float.NaN** değerinin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okuma/yazma Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Metin FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Yazı tipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. Okuma/yazma [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Bir bölümün yazı tipi yüksekliğini döndürür veya ayarlar. **float.NaN** yüksekliğin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okuma/yazma Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Yazı tipinin itallic olup olmadığını belirler. Kalıtım uygulanmaz. Okuma/yazma [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Metin alt çizgi tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okuma/yazma [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Metni vurgulamak için kullanılan rengi döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar. Okuma/yazma [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Köprü yöneticisi. Yalnızca okunabilir [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlanan köprüyü döndürür veya ayarlar. Okuma/yazma [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden miras alıp almadığını belirler. Okuma/yazma [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden miras alıp almadığını belirler. Okuma/yazma [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür veya ayarlar. **float.NaN** değerin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okuma/yazma Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Sayıların metnin doğu dili özelliğine özgü dikey düzeni yok sayması gerekip gerekmediğini belirler. Kalıtım uygulanmaz. Okuma/yazma [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | İmla denetimi dili kimliğini döndürür veya ayarlar. Yazım ve dilbilgisi kontrolü için kullanılır. Okuma/yazma String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Latin yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okuma/yazma [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Metin kenarlaması için LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Kalıtım uygulanmaz. Okuma/yazma [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Metnin denetlenmemesi gerekip gerekmediğini belirler. Kalıtım uygulanmaz. Okuma/yazma [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Akıllı etiketin temizlenip temizlenmeyeceğini belirler. Kalıtım uygulanmaz. Okuma/yazma Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Karakterler arası boşluk artışını döndürür veya ayarlar. **float.NaN** değerin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okuma/yazma Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Metin bölümü için imla denetiminin etkin olup olmadığını belirten bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için imla denetimi bastırılır. True olarak ayarlandığında, imla denetimine izin verilir. Varsayılan değer `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Metnin üstü çizili tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okuma/yazma [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Sembolik yazı tipi bilgisini döndürür veya ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan kalıtılması gerektiği anlamına gelir. Okuma/yazma [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Metnin büyük harf kullanım tipini döndürür veya ayarlar. Kalıtım uygulanmaz. Okuma/yazma [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Alt çizgi satırının FillFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Alt çizgi satırının kenarlığı için kullanılan LineFormat özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [`ILineFormat`](../ilineformat). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesneyle karşılaştırır. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Kalıtım uygulanmış etkili bölüm biçimlendirme verilerini alır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Karma kodu döndürür. |

### Açıklamalar

Bu sınıf, belirli bölüm için tanımlanan metin bölümü biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken hiçbir kalıtım uygulanmadığı anlamına gelir, bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler alırsınız.

Kalıtım dahil olmak üzere etkili biçimlendirme parametre değerlerini almak için [`GetEffective`](./geteffective) yöntemini kullanmanız gerekir; bu yöntem bir [`IPortionFormatEffectiveData`](../iportionformateffectivedata) örneği döndürür.

### Örnekler

Aşağıdaki örnekler, PowerPoint Sunumu bir Paragraf'ın bölümüne Latin yazı tipini nasıl atayacağınızı gösterir.

```csharp
[C#]
//Sunum dosyasını temsil eden bir sunum nesnesi oluşturur
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides bu özel tanımlayıcıları kullanır (PowerPoint'te kullanılanlara benzer):
// +mn-lt - Gövde Yazı Tipi Latin (Küçük Latin Yazı Tipi)
// +mj-lt - Başlık Yazı Tipi Latin (Büyük Latin Yazı Tipi)
// +mn-ea - Gövde Yazı Tipi Doğu Asya (Küçük Doğu Asya Yazı Tipi)
// +mj-ea - Gövde Yazı Tipi Doğu Asya (Küçük Doğu Asya Yazı Tipi)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Ayrıca Bakınız

* sınıf [BasePortionFormat](../baseportionformat)
* arayüz [IPortionFormat](../iportionformat)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->