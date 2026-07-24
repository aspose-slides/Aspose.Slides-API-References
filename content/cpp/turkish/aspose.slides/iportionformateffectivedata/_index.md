---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides için C++ API Referansı
description: Etkili metin bölümü biçimlendirme özelliklerini içeren değiştirilemez nesne.
type: docs
weight: 3342
url: /tr/aspose.slides/iportionformateffectivedata/
---
## IPortionFormatEffectiveData sınıfı

Değiştirilemez nesne; etkili metin bölümü biçimlendirme özelliklerini içerir.

```cpp
class IPortionFormatEffectiveData : public virtual Aspose::Slides::IBasePortionFormatEffectiveData
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN değeri eşit kabul edilir, ancak IEC 60559:1989 standardına göre NaN herhangi bir değerle, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN değeri eşit kabul edilir, ancak IEC 60559:1989 standardına göre NaN herhangi bir değerle, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformateffectivedata/get_alternativelanguageid/)() | Alternatif bir dilin kimliğini döndürür. Yalnızca okunur [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Yer imi tanımlayıcısını döndürür. Yalnızca okunur [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformateffectivedata/get_complexscriptfont/)() | Karmaşık betik yazı tipi bilgilerini döndürür. Yalnızca okunur [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformateffectivedata/get_eastasianfont/)() | Doğu Asya yazı tipi bilgilerini döndürür. Yalnızca okunur [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](../ibaseportionformateffectivedata/get_effectformat/)() | Metnin [EffectFormat](../effectformat/) özelliklerini döndürür. Yalnızca okunur [IEffectFormatEffectiveData](../ieffectformateffectivedata/). |
| virtual **float** [get_Escapement](../ibaseportionformateffectivedata/get_escapement/)() | Üst simge ya da alt simge metnini döndürür. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. Yalnızca okunur **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](../ibaseportionformateffectivedata/get_fillformat/)() | Metnin [FillFormat](../fillformat/) özelliklerini döndürür. Yalnızca okunur [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual **bool** [get_FontBold](../ibaseportionformateffectivedata/get_fontbold/)() | Yazı tipinin kalın olup olmadığını belirler. Yalnızca okunur **bool**. |
| virtual **float** [get_FontHeight](../ibaseportionformateffectivedata/get_fontheight/)() | Metin bölümünün yazı tipi yüksekliğini puan cinsinden döndürür. Yalnızca okunur **float**. |
| virtual **bool** [get_FontItalic](../ibaseportionformateffectivedata/get_fontitalic/)() | Yazı tipinin eğik olup olmadığını belirler. Yalnızca okunur **bool**. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformateffectivedata/get_fontunderline/)() | Metnin alt çizgi tipini döndürür. Yalnızca okunur [TextUnderlineType](../textunderlinetype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](../ibaseportionformateffectivedata/get_highlightcolor/)() | Metni vurgulamak için kullanılan rengi döndürür. Yalnızca okunur [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() | Fare tıklaması için tanımlanan köprüyü döndürür. Yalnızca okunur [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() | Fare üzerine gelindiğinde tanımlanan köprüyü döndürür. Yalnızca okunur [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsHardUnderlineFill](../ibaseportionformateffectivedata/get_ishardunderlinefill/)() | Alt çizgi stilinin kendi [FillFormat](../fillformat/) özelliklerine sahip olup olmadığını ya da metnin [FillFormat](../fillformat/) özelliklerinden devralıp devralmadığını belirler. Yalnızca okunur **bool**. |
| virtual **bool** [get_IsHardUnderlineLine](../ibaseportionformateffectivedata/get_ishardunderlineline/)() | Alt çizgi stilinin kendi [LineFormat](../lineformat/) özelliklerine sahip olup olmadığını ya da metnin [LineFormat](../lineformat/) özelliklerinden devralıp devralmadığını belirler. Yalnızca okunur **bool**. |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformateffectivedata/get_kerningminimalsize/)() | Kerning'in etkinleştirilmesi gereken minimum yazı tipi boyutunu döndürür. Yalnızca okunur **float**. |
| virtual **bool** [get_Kumimoji](../ibaseportionformateffectivedata/get_kumimoji/)() | Sayıların metnin doğu dili özgü dikey metin düzenini görmezden gelip gelmeyeceğini belirler. Yalnızca okunur **bool**. |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformateffectivedata/get_languageid/)() | Bir dilin kimliğini döndürür. Yalnızca okunur [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformateffectivedata/get_latinfont/)() | Latin yazı tipi bilgilerini döndürür. Yalnızca okunur [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](../ibaseportionformateffectivedata/get_lineformat/)() | Metin taslağı için [LineFormat](../lineformat/) özelliklerini döndürür. Yalnızca okunur [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| virtual **bool** [get_NormaliseHeight](../ibaseportionformateffectivedata/get_normaliseheight/)() | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Yalnızca okunur **bool**. |
| virtual **bool** [get_ProofDisabled](../ibaseportionformateffectivedata/get_proofdisabled/)() | Metnin denetlenmemesi gerekip gerekmediğini belirler. Yalnızca okunur **bool**. |
| virtual **bool** [get_SmartTagClean](../ibaseportionformateffectivedata/get_smarttagclean/)() | Akıllı etiketin temizlenip temizlenmeyeceğini belirler. Yalnızca okunur **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformateffectivedata/get_spacing/)() | Karakterler arası boşluk artışını puan cinsinden döndürür. Yalnızca okunur **float**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformateffectivedata/get_strikethroughtype/)() | Metnin üstü çizili tipini döndürür. Yalnızca okunur [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformateffectivedata/get_symbolfont/)() | Sembolik yazı tipi bilgilerini döndürür. Yalnızca okunur [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformateffectivedata/get_textcaptype/)() | Metnin büyük harf kullanım tipini döndürür. Yalnızca okunur [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](../ibaseportionformateffectivedata/get_underlinefillformat/)() | Alt çizgi satır [FillFormat](../fillformat/) özelliklerini döndürür. Yalnızca okunur [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](../ibaseportionformateffectivedata/get_underlinelineformat/)() | [LineFormat](../lineformat/) özelliklerini alt çizgi satırını taslaklamak için döndürür. Yalnızca okunur [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTip tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapılandırmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapılandırmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) ifadesini uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Açıklamalar

Bu arabirim, [IPortionFormat](../iportionformat/) arabirimiyle birlikte, kalıtım uygulanmış etkili biçimlendirme değerlerini döndürmek için kullanılmaktadır.

## Bakınız

* Sınıf [IBasePortionFormatEffectiveData](../ibaseportionformateffectivedata/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)