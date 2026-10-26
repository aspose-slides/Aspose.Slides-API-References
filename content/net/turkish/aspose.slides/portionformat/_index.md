---
title: PortionFormat
second_title: Aspose.Slides için .NET API Referansı
description: Bu sınıf, metin parçası biçimlendirme özelliklerini içerir. IPortionFormatEffectiveData./iportionformateffectivedata gibi değildir, bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 9490
url: /tr/aspose.slides/portionformat/
---
## PortionFormat sınıf

Bu sınıf, metin parçası biçimlendirme özelliklerini içerir. [`IPortionFormatEffectiveData`](../iportionformateffectivedata)'den farklı olarak, bu sınıfın tüm özellikleri yazılabilir.

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
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Alternatif bir dilin Kimliğini döndürür veya ayarlar. Okunur/Yazılır String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Temel IPresentationComponent arayüzünü almayı sağlar. Salt-okunur [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Yer imleri tanımlayıcısını döndürür veya ayarlar. Okunur/Yazılır String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Karmaşık script yazı tipi bilgisini döndürür veya ayarlar. Null değer, yazı tipinin tanımsız olduğunu ve Ana'dan devralınması gerektiğini belirtir. Okunur/Yazılır [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Doğu Asya yazı tipi bilgisini döndürür veya ayarlar. Null değer, yazı tipinin tanımsız olduğunu ve Ana'dan devralınması gerektiğini gösterir. Okunur/Yazılır [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Metin EffectFormat özelliklerini döndürür. Devralma uygulanmaz. Salt-okunur [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Üst simge veya alt simge metnini döndürür veya ayarlar. Değer -100% (alt simge) ile 100% (üst simge) arasında. **float.NaN** değeri tanımsızdır ve Ana'dan devralınmalıdır. Okunur/Yazılır Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Metin FillFormat özelliklerini döndürür. Devralma uygulanmaz. Salt-okunur [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Yazı tipinin kalın olup olmadığını belirler. Devralma uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Bir parçanın yazı tipi yüksekliğini döndürür veya ayarlar. **float.NaN** değeri yüksekliğin tanımsız olduğunu ve Ana'dan devralınması gerektiğini gösterir. Okunur/Yazılır Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Yazı tipinin italik olup olmadığını belirler. Devralma uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Metin alt çizgi tipini döndürür veya ayarlar. Devralma uygulanmaz. Okunur/Yazılır [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Metni vurgulamak için kullanılan rengi döndürür. Devralma uygulanmaz. Salt-okunur [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlı köprüyi (hyperlink) döndürür veya ayarlar. Okunur/Yazılır [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Köprü yöneticisi. Salt-okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlı köprüyü döndürür veya ayarlar. Okunur/Yazılır [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Alt çizgi stilinin kendi FillFormat özelliklerine sahip olup olmadığını veya metnin FillFormat özelliklerinden devralınıp devralınmadığını belirler. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Alt çizgi stilinin kendi LineFormat özelliklerine sahip olup olmadığını veya metnin LineFormat özelliklerinden devralınıp devralınmadığını belirler. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Kerning'in etkinleştirileceği minimum yazı tipi boyutunu döndürür veya ayarlar. **float.NaN** değeri tanımsızdır ve Ana'dan devralınmalıdır. Okunur/Yazılır Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Sayısalların metnin doğu dili özel dikey metin düzenini görmezden gelip gelmeyeceğini belirler. Devralma uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Denetleme dili kimliğini döndürür veya ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Okunur/Yazılır String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Latin yazı tipi bilgisini döndürür veya ayarlar. Null değer, yazı tipinin tanımsız olduğunu ve Ana'dan devralınması gerektiğini gösterir. Okunur/Yazılır [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Metin kenarlığı için LineFormat özelliklerini döndürür. Devralma uygulanmaz. Salt-okunur [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Metin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Devralma uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Metnin denetlenmemesi gerektiğini belirler. Devralma uygulanmaz. Okunur/Yazılır [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Akıllı etiketin temizlenip temizlenmeyeceğini belirler. Devralma uygulanmaz. Okunur/Yazılır Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Karakterler arası boşluk artışını döndürür veya ayarlar. **float.NaN** değeri tanımsızdır ve Ana'dan devralınmalıdır. Okunur/Yazılır Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Metin parçası için yazım denetiminin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimi devre dışı bırakılır. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Metnin üstü çizili tipini döndürür veya ayarlar. Devralma uygulanmaz. Okunur/Yazılır [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Sembolik yazı tipi bilgisini döndürür veya ayarlar. Null değer, yazı tipinin tanımsız olduğunu ve Ana'dan devralınması gerektiğini gösterir. Okunur/Yazılır [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Metnin büyük harf/küçük harf tipini döndürür veya ayarlar. Devralma uygulanmaz. Okunur/Yazılır [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Alt çizgi satırının FillFormat özelliklerini döndürür. Devralma uygulanmaz. Salt-okunur [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Alt çizgi satırını kenarlamak için kullanılan LineFormat özelliklerini döndürür. Devralma uygulanmaz. Salt-okunur [`ILineFormat`](../ilineformat). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Belirtilen nesne ile karşılaştırır. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Devralma uygulanmış etkili bölüm biçimlendirme verilerini alır. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Karma kodunu döndürür. |

### Açıklamalar

Bu sınıf, belirli bir bölüm için tanımlanan metin bölümü biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken devralma uygulanmadığı anlamına gelir; bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler elde edersiniz.

[`GetEffective`](./geteffective) yöntemini kullanmanız gerekir; bu yöntem, [`IPortionFormatEffectiveData`](../iportionformateffectivedata) örneği döndürür.

### Örnekler

Aşağıdaki örnekler, PowerPoint Sunumu bir Paragraf'ın bölümüne Latin yazı tipini atamanın nasıl yapılacağını gösterir.

```csharp
[C#]
// Bir sunum dosyasını temsil eden bir sunum nesnesi oluşturur
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides bu özel tanımlayıcıları (PowerPoint'te kullanılanlara benzer) kullanır:
// +mn-lt - Gövde Yazı Tipi Latin (Küçük Latin Yazı Tipi)
// +mj-lt - Başlık Yazı Tipi Latin (Büyük Latin Yazı Tipi)
// +mn-ea - Gövde Yazı Tipi Doğu Asya (Küçük Doğu Asya Yazı Tipi)
// +mj-ea - Gövde Yazı Tipi Doğu Asya (Küçük Doğu Asya Yazı Tipi)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Diğer Bağlantılar

* sınıf [BasePortionFormat](../baseportionformat)
* arayüz [IPortionFormat](../iportionformat)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->