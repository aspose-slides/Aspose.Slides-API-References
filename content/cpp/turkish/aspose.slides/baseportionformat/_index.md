---
title: BasePortionFormat
second_title: Aspose.Slides için C++ API Referansı
description: Ortak metin bölümü biçimlendirme özellikleri.
type: docs
weight: 144
url: /tr/aspose.slides/baseportionformat/
---
## BasePortionFormat sınıfı

Ortak metin bölümü biçimlendirme özellikleri.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Belirtilen nesneyle karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | Alternatif bir dilin kimliğini döndürür. Oku [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | Karmaşık betik yazı tipi bilgisini döndürür. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Oku [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | Doğu Asya yazı tipi bilgisini döndürür. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Oku [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Metin [EffectFormat](../effectformat/) özelliklerini döndürür. Türetilme uygulanmaz. Sadece okunabilir [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | Üst ya da alt simge metnini döndürür. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Oku **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Metin [FillFormat](../fillformat/) özelliklerini döndürür. Türetilme uygulanmaz. Sadece okunabilir [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | Yazı tipinin kalın olup olmadığını belirler. Türetilme uygulanmaz. Oku [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | Bir bölümün yazı tipi yüksekliğini döndürür. **std::numeric_limits<float>::quiet_NaN()** yüksekliğin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Oku **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | Yazı tipinin itallic olup olmadığını belirler. Türetilme uygulanmaz. Oku [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | Metin alt çizgi tipini döndürür. Türetilme uygulanmaz. Oku [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | Metni vurgulamak için kullanılan rengi döndürür. Türetilme uygulanmaz. Sadece okunabilir [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | Alt çizgi stilinin kendi [FillFormat](../fillformat/) özelliklerine sahip olup olmadığını veya metnin [FillFormat](../fillformat/) özelliklerinden devralınıp devralmadığını belirler. Oku [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | Alt çizgi stilinin kendi [LineFormat](../lineformat/) özelliklerine sahip olup olmadığını veya metnin [LineFormat](../lineformat/) özelliklerinden devralınıp devralmadığını belirler. Oku [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | Kerning'in açılması gereken minimum yazı tipi boyutunu döndürür. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Oku **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | Sayıların metnin doğu dili spesifik dikey düzenini görmezden gelmesi gerektiğini belirler. Türetilme uygulanmaz. Oku [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | Denetleme dilinin kimliğini döndürür. Yazım ve dilbilgisi denetimi için kullanılır. Oku [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | Latin yazı tipi bilgisini döndürür. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Oku [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Metin kenarlığı için [LineFormat](../lineformat/) özelliklerini döndürür. Türetilme uygulanmaz. Sadece okunabilir [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Türetilme uygulanmaz. Oku [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate nesnesini döndürür. Sadece okunabilir [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Üst [IPresentationComponent](../ipresentationcomponent/) nesnesini döndürür. Sadece okunabilir [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | Metnin denetlenmemesi gerektiğini belirler. Türetilme uygulanmaz. Oku [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | Karakterler arası boşluk artışını döndürür. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Oku **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | Metin bölümü için imla denetiminin etkin olup olmadığını gösteren bir değer alır. Bu özellik false olarak ayarlandığında, metin öğeleri için imla denetimi devre dışı bırakılır. True olarak ayarlandığında, imla denetimine izin verilir. Varsayılan değer **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | Metnin üstü çizili tipini döndürür. Türetilme uygulanmaz. Oku [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | Sembolik yazı tipi bilgisini döndürür. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Oku [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | Metnin büyük harf kullanım türünü döndürür. Türetilme uygulanmaz. Oku [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | Alt çizgi satırı [FillFormat](../fillformat/) özelliklerini döndürür. Türetilme uygulanmaz. Sadece okunabilir [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | [LineFormat](../lineformat/) özelliklerini döndürür; alt çizgi satırını çerçevelemek için kullanılır. Türetilme uygulanmaz. Sadece okunabilir [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Karma kodunu döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nın dize ve nullptr durumuna özel bir türevidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın dize durumuna özel bir türevidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | Alternatif bir dilin kimliğini ayarlar. Yaz [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Karmaşık betik yazı tipi bilgisini ayarlar. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Yaz [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Doğu Asya yazı tipi bilgisini ayarlar. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Yaz [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | Üst ya da alt simge metnini ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Yaz **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | Yazı tipinin kalın olup olmadığını belirler. Türetilme uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | Bir bölümün yazı tipi yüksekliğini ayarlar. **std::numeric_limits<float>::quiet_NaN()** yüksekliğin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Yaz **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | Yazı tipinin itallic olup olmadığını belirler. Türetilme uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Metin alt çizgi tipini ayarlar. Türetilme uygulanmaz. Yaz [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Alt çizgi stilinin kendi [FillFormat](../fillformat/) özelliklerine sahip olup olmadığını veya metnin [FillFormat](../fillformat/) özelliklerinden devralınıp devralmadığını belirler. Yaz [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Alt çizgi stilinin kendi [LineFormat](../lineformat/) özelliklerine sahip olup olmadığını veya metnin [LineFormat](../lineformat/) özelliklerinden devralınıp devralmadığını belirler. Yaz [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | Kerning'in açılması gereken minimum yazı tipi boyutunu ayarlar. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Yaz **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | Sayıların metnin doğu dili özgü dikey metin düzenini görmezden gelip gelmeyeceğini belirler. Türetilme uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | Denetleme dilinin kimliğini ayarlar. Yazım ve dilbilgisi denetimi için kullanılır. Yaz [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Latin yazı tipi bilgisini ayarlar. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Yaz [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Türetilme uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | Metnin denetlenmemesi gerektiğini belirler. Türetilme uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | Karakterler arası boşluk artışını ayarlar. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğunu ve Master'dan devralınması gerektiğini gösterir. Yaz **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | Metin bölümü için imla denetiminin etkin olup olmadığını gösteren bir değeri ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için imla denetimi devre dışı bırakılır. True olarak ayarlandığında, imla denetimine izin verilir. Varsayılan değer **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Metnin üstü çizili tipini ayarlar. Türetilme uygulanmaz. Yaz [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Sembolik yazı tipi bilgisini ayarlar. Null, yazı tipinin tanımlı olmadığı ve Master'dan devralınması gerektiği anlamına gelir. Yaz [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Metnin büyük harfle yazım türünü ayarlar. Türetilme uygulanmaz. Yaz [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir işaretçiye (paylaşılan yerine) ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidi açma işlevini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakın

* Sınıf [PVIObject](../pviobject/)
* Sınıf [IBasePortionFormat](../ibaseportionformat/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)