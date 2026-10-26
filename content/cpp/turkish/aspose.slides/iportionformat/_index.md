---
title: IPortionFormat
second_title: C++ için Aspose.Slides API Referansı
description: Bu sınıf, metin kısmı biçimlendirme özelliklerini içerir. IPortionFormatEffectiveData'den farklı olarak, bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 3329
url: /tr/aspose.slides/iportionformat/
---
## IPortionFormat sınıfı


Bu sınıf, metin kısmı biçimlendirme özelliklerini içerir. [IPortionFormatEffectiveData](../iportionformateffectivedata/)'den farklı olarak, bu sınıfın tüm özellikleri yazılabilir.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde başvuru türü nesnelerini karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer türü nesnelerini karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca iç amaçlar için. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | Alternatif bir dilin Id'sini döndürür. [System::String](../../system/string/)'yi okuyun. |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Yer imi tanımlayıcısını döndürür. [System::String](../../system/string/)'yi okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | Karmaşık betik font bilgisini döndürür. Null, fontun tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/)'yi okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | Doğu Asya font bilgisini döndürür. Null, fontun tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/)'yi okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | Metin [EffectFormat](../effectformat/) özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okuma [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | Üst simge veya alt simge metnini döndürür. Değer -%100 (alt simge) ile %100 (üst simge) arasında değişir. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. **float** okur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | Metin [FillFormat](../fillformat/) özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okuma [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | Fontun kalın olup olmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'yi okuyun. |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | Kısmın font yüksekliğini döndürür. **std::numeric_limits<float>::quiet_NaN()** yüksekliğin tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. **float** okur. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | Fontun eğik (italik) olup olmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'yi okuyun. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | Metin alt çizgi türünü döndürür. Kalıtım uygulanmaz. [TextUnderlineType](../textunderlinetype/)'yi okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | Metni vurgulamak için kullanılan rengi döndürür. Kalıtım uygulanmaz. Yalnızca okuma [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Fare tıklaması için tanımlı köprüyü döndürür. [IHyperlink](../ihyperlink/)'yi okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Köprü yöneticisi Yalnızca okuma [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Fare üzerine gelindiğinde tanımlı köprüyü döndürür. [IHyperlink](../ihyperlink/)'yi okuyun. |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | Alt çizgi stilinin kendi [FillFormat](../fillformat/) özelliklerine sahip olup olmadığını veya metnin [FillFormat](../fillformat/) özelliklerinden miras alıp almadığını belirler. [NullableBool](../nullablebool/)'yi okuyun. |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | Alt çizgi stilinin kendi [LineFormat](../lineformat/) özelliklerine sahip olup olmadığını veya metnin [LineFormat](../lineformat/) özelliklerinden miras alıp almadığını belirler. [NullableBool](../nullablebool/)'yi okuyun. |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | Kerning'in açılması gereken en düşük font boyutunu döndürür. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. **float** okur. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | Sayıların, metnin doğu dili-spesifik dikey metin yerleşimini göz ardı edip etmediğini belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'yi okuyun. |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | Denetleme dilinin Id'sini döndürür. Yazım ve dilbilgisi denetimi için kullanılır. [System::String](../../system/string/)'yi okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | Latin font bilgisini döndürür. Null, fontun tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/)'yi okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | Metin kenar çizimi için [LineFormat](../lineformat/) özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okuma [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | Metnin yüksekliğinin normalize edilip edilmemesi gerektiğini belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'yi okuyun. |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | Metnin denetlenmemesi gerektiğini belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'yi okuyun. |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Akıllı etiketin temizlenip temizlenmemesi gerektiğini belirler. Kalıtım uygulanmaz. **bool** okur. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | Karakterler arası boşluk artışını döndürür. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. **float** okur. |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | Metin kısmı için imla denetiminin etkin olup olmadığını gösteren değeri alır. Bu özellik **false** olarak ayarlandığında metin öğeleri için imla denetimi bastırılır. **true** olarak ayarlandığında imla denetimine izin verilir. Varsayılan değer **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | Metnin üstü çizili (strike-through) türünü döndürür. Kalıtım uygulanmaz. [TextStrikethroughType](../textstrikethroughtype/)'yi okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | Sembolik font bilgisini döndürür. Null, fontun tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/)'yi okuyun. |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | Metin büyük/küçük harf stilini döndürür. Kalıtım uygulanmaz. [Slides::TextCapType](../textcaptype/)'yi okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | Alt çizgi çizgi [FillFormat](../fillformat/) özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okuma [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | Alt çizgi çizgisini çerçevelemek için kullanılan [LineFormat](../lineformat/) özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okuma [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | Kalıtım uygulanmış etkili kısım biçimlendirme verisini alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, hedef tip tarafından tanımlanan tipte bir örnek olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans-karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize durumu için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | Alternatif bir dilin Id'sini ayarlar. [System::String](../../system/string/) yazın. |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | Yer imi tanımlayıcısını ayarlar. [System::String](../../system/string/) yazın. |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Karmaşık betik font bilgisini ayarlar. Null, fontun tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/) yazın. |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Doğu Asya font bilgisini ayarlar. Null, fontun tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/) yazın. |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | Üst simge veya alt simge metnini ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasında değişir. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. **float** yazın. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | Fontun kalın olup olmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/) yazın. |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | Kısmın font yüksekliğini ayarlar. **std::numeric_limits<float>::quiet_NaN()** yüksekliğin tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. **float** yazın. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | Fontun eğik (italik) olup olmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/) yazın. |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Metin alt çizgi türünü ayarlar. Kalıtım uygulanmaz. [TextUnderlineType](../textunderlinetype/) yazın. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Fare tıklaması için tanımlı köprüyü ayarlar. [IHyperlink](../ihyperlink/) yazın. |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Fare üzerine gelindiğinde tanımlı köprüyü ayarlar. [IHyperlink](../ihyperlink/) yazın. |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Alt çizgi stilinin kendi [FillFormat](../fillformat/) özelliklerine sahip olup olmadığını veya metnin [FillFormat](../fillformat/) özelliklerinden miras alıp almadığını belirler. [NullableBool](../nullablebool/) yazın. |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Alt çizgi stilinin kendi [LineFormat](../lineformat/) özelliklerine sahip olup olmadığını veya metnin [LineFormat](../lineformat/) özelliklerinden miras alıp almadığını belirler. [NullableBool](../nullablebool/) yazın. |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | Kerning'in açılması gereken en düşük font boyutunu ayarlar. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. **float** yazın. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | Sayıların, metnin doğu dili-spesifik dikey metin yerleşimini göz ardı edip etmediğini belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/) yazın. |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | Denetleme dilinin Id'sini ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. [System::String](../../system/string/) yazın. |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Latin font bilgisini ayarlar. Null, fontun tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/) yazın. |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | Metnin yüksekliğinin normalize edilip edilmemesi gerektiğini belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/) yazın. |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | Metnin denetlenmemesi gerektiğini belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/) yazın. |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | Akıllı etiketin temizlenip temizlenmemesi gerektiğini belirler. Kalıtım uygulanmaz. **bool** yazın. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | Karakterler arası boşluk artışını ayarlar. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. **float** yazın. |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | Metin kısmı için imla denetiminin etkin olup olmadığını gösteren değeri ayarlar. Bu özellik **false** olarak ayarlandığında metin öğeleri için imla denetimi bastırılır. **true** olarak ayarlandığında imla denetimine izin verilir. Varsayılan değer **false**. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Metnin üstü çizili (strike-through) türünü ayarlar. Kalıtım uygulanmaz. [TextStrikethroughType](../textstrikethroughtype/) yazın. |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sembolik font bilgisini ayarlar. Null, fontun tanımsız olduğu ve Master'dan kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/) yazın. |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Metin büyük/küçük harf stilini ayarlar. Kalıtım uygulanmaz. [Slides::TextCapType](../textcaptype/) yazın. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-inci şablon argümanını paylaşılan yerine zayıf gösterici olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçirir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler ya da ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler ya da ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler ya da ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler ya da ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |
## Açıklamalar


Bu sınıf, belirli kısım için tanımlanan metin kısmı biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken hiçbir kalıtımın uygulanmadığı anlamına gelir; bu yüzden çoğu durumda \"undefined\" (tanımsız) anlamına gelen değerler alırsınız.

Kalıtım dahil olmak üzere etkili biçimlendirme parametresi değerlerini elde etmek için [IPortionFormat::GetEffective](./geteffective/) yöntemini kullanmanız gerekir; bu yöntem bir [IPortionFormatEffectiveData](../iportionformateffectivedata/) örneği döndürür.
## Ayrıca Bakınız

* Sınıf [IBasePortionFormat](../ibaseportionformat/)
* Sınıf [IHyperlinkContainer](../ihyperlinkcontainer/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)