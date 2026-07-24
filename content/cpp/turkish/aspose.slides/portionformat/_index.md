---
title: PortionFormat
second_title: Aspose.Slides için C++ API Referansı
description: Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. IPortionFormatEffectiveData'dan farklı olarak, bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 4811
url: /tr/aspose.slides/portionformat/
---
## PortionFormat sınıfı


Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. [IPortionFormatEffectiveData](../iportionformateffectivedata/)'in aksine, bu sınıfın tüm özellikleri yazılabilir.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Belirtilen nesneyle karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı çift hassasiyetli kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili kullanım içindir. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | Alternatif bir dilin kimliğini döndürür. Oku [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | Yer işareti kimliğini döndürür. Oku [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | Karmaşık betik yazı tipi bilgisini döndürür. Null, yazı tipinin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Oku [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | Doğu Asya yazı tipi bilgisini döndürür. Null, yazı tipinin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Oku [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | Metin [EffectFormat](../effectformat/) özelliklerini döndürür. Devralma uygulanmaz. Sadece okunabilir [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | Üst yazı veya alt yazı metnini döndürür. Değer -%100 (alt yazı) ile %100 (üst yazı) arasındadır. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Okur **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | Metin [FillFormat](../fillformat/) özelliklerini döndürür. Devralma uygulanmaz. Sadece okunabilir [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | Yazı tipinin kalın olup olmadığını belirler. Devralma uygulanmaz. Okur [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | Bir bölümün yazı tipi yüksekliğini döndürür. **std::numeric_limits<float>::quiet_NaN()** yüksekliğin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Okur **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | Yazı tipinin italik olup olmadığını belirler. Devralma uygulanmaz. Okur [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | Metin alt çizgi tipini döndürür. Devralma uygulanmaz. Okur [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | Metni vurgulamak için kullanılan rengi döndürür. Devralma uygulanmaz. Sadece okunabilir [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Fare tıklaması için tanımlanan köprüyü döndürür. Oku [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Köprü yöneticisi. Sadece okunabilir [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Fare üzerindeyken tanımlanan köprüyü döndürür. Oku [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | Alt çizgi stilinin kendine ait [FillFormat](../fillformat/) özellikleri olup olmadığını veya metnin [FillFormat](../fillformat/) özelliklerinden devralınıp devralmadığını belirler. Oku [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | Alt çizgi stilinin kendine ait [LineFormat](../lineformat/) özellikleri olup olmadığını veya metnin [LineFormat](../lineformat/) özelliklerinden devralınıp devralmadığını belirler. Oku [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | Kerningi etkinleştirilecek minimal yazı tipi boyutunu döndürür. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Okur **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | Sayıların metnin doğu dilleri özel dikey metin düzenini görmezden gelmesi gerekip gerekmediğini belirler. Devralma uygulanmaz. Okur [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | Denetim dilinin kimliğini döndürür. Yazım ve dilbilgisi denetimi için kullanılır. Oku [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | Latin yazı tipi bilgisini döndürür. Null, yazı tipinin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Oku [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | Metin döşeme için [LineFormat](../lineformat/) özelliklerini döndürür. Devralma uygulanmaz. Sadece okunabilir [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Devralma uygulanmaz. Okur [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate nesnesini döndürür. Sadece okunabilir [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Üst [IPresentationComponent](../ipresentationcomponent/) nesnesini döndürür. Sadece okunabilir [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | Metnin denetlenmemesi gerekip gerekmediğini belirler. Devralma uygulanmaz. Okur [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | Akıllı etiketin temizlenip temizlenmeyeceğini belirler. Devralma uygulanmaz. Okur **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | Karakterler arası boşluk artışını döndürür. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Okur **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | Metin bölümü için imla denetiminin etkin olup olmadığını gösteren bir değeri alır. Bu özellik false olarak ayarlandığında, metin öğeleri için imla denetimi bastırılır. True olarak ayarlandığında, imla denetimine izin verilir. Varsayılan değer **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | Metnin üzeri çizili tipini döndürür. Devralma uygulanmaz. Okur [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | Sembolik yazı tipi bilgisini döndürür. Null, yazı tipinin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Oku [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | Metin büyük/küçük harf türünü döndürür. Devralma uygulanmaz. Okur [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | Alt çizgi satır [FillFormat](../fillformat/) özelliklerini döndürür. Devralma uygulanmaz. Sadece okunabilir [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | Alt çizgi satırını çerçevelemek için kullanılan [LineFormat](../lineformat/) özelliklerini döndürür. Devralma uygulanmaz. Sadece okunabilir [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | Devralma uygulanan etkili bölüm biçimlendirme verisini alır. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Karma kodunu döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
|  [PortionFormat](./portionformat/)() | [PortionFormat](./) sınıfının yeni bir örneğini başlatır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize ve nullptr durumuna özelleşmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize durumuna özelleşmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | Alternatif bir dilin kimliğini ayarlar. Yaz [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | Yer işareti kimliğini ayarlar. Yaz [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Karmaşık betik yazı tipi bilgisini ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Yaz [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Doğu Asya yazı tipi bilgisini ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Yaz [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | Üst yazı veya alt yazı metnini ayarlar. Değer -%100 (alt yazı) ile %100 (üst yazı) arasındadır. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Yaz **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | Yazı tipinin kalın olup olmadığını belirler. Devralma uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | Bir bölümün yazı tipi yüksekliğini ayarlar. **std::numeric_limits<float>::quiet_NaN()** yüksekliğin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Yaz **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | Yazı tipinin italik olup olmadığını belirler. Devralma uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Metin alt çizgi tipini ayarlar. Devralma uygulanmaz. Yaz [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Fare tıklaması için tanımlanan köprüyü ayarlar. Yaz [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Fare üzerindeyken tanımlanan köprüyü ayarlar. Yaz [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Alt çizgi stilinin kendine ait [FillFormat](../fillformat/) özellikleri olup olmadığını veya metnin [FillFormat](../fillformat/) özelliklerinden devralınıp devralmadığını belirler. Yaz [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Alt çizgi stilinin kendine ait [LineFormat](../lineformat/) özellikleri olup olmadığını veya metnin [LineFormat](../lineformat/) özelliklerinden devralınıp devralmadığını belirler. Yaz [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | Kerningi etkinleştirilecek minimal yazı tipi boyutunu ayarlar. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Yaz **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | Sayıların metnin doğu dilleri özel dikey metin düzenini görmezden gelmesi gerekip gerekmediğini belirler. Devralma uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | Denetim dilinin kimliğini ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Yaz [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Latin yazı tipi bilgisini ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Yaz [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Devralma uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | Metnin denetlenmemesi gerekip gerekmediğini belirler. Devralma uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | Akıllı etiketin temizlenip temizlenmeyeceğini belirler. Devralma uygulanmaz. Yaz **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | Karakterler arası boşluk artışını ayarlar. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Yaz **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | Metin bölümü için imla denetiminin etkin olup olmadığını gösteren bir değeri ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için imla denetimi bastırılır. True olarak ayarlandığında, imla denetimine izin verilir. Varsayılan değer **false**. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Metnin üzeri çizili tipini ayarlar. Devralma uygulanmaz. Yaz [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Sembolik yazı tipi bilgisini ayarlar. Null, yazı tipinin tanımsız olduğu ve Ana'dan devralınması gerektiği anlamına gelir. Yaz [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Metin büyük/küçük harf türünü ayarlar. Devralma uygulanmaz. Yaz [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n.'inci şablon argümanını paylaşılan yerine zayıf gösterici olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını arttırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını arttırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Açıklamalar


Bu sınıf, belirli bir bölüm için tanımlanan metin bölümü biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken devralmanın uygulanmadığı anlamına gelir, bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler elde edersiniz.

Devralma dahil etkili biçimlendirme parametre değerlerini elde etmek için [PortionFormat::GetEffective](./geteffective/) yöntemini kullanmanız gerekir; bu yöntem bir [IPortionFormatEffectiveData](../iportionformateffectivedata/) örneği döndürür.

Aşağıdaki örnekler, PowerPoint [Presentation](../presentation/) içinde bir [Paragraph](../paragraph/)'nin bölümü için Latin yazı tipini nasıl atayacağınızı gösterir.
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides bu özel tanımlayıcıları kullanır (PowerPoint'te kullanılanlara benzer):
// +mn-lt - Gövde Yazı Tipi Latin (Küçük Latin Yazı Tipi)
// +mj-lt - Başlık Yazı Tipi Latin (Büyük Latin Yazı Tipi)
// +mn-ea - Gövde Yazı Tipi Doğu Asya (Küçük Doğu Asya Yazı Tipi)
// +mj-ea - Gövde Yazı Tipi Doğu Asya (Küçük Doğu Asya Yazı Tipi)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## Bakınız

* Sınıf [BasePortionFormat](../baseportionformat/)
* Sınıf [IPortionFormat](../iportionformat/)
* İsim alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)