---
title: IBasePortionFormat
second_title: Aspose.Slides için C++ API Referansı
description: Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. IPortionFormatEffectiveData'dan farklı olarak, bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 1457
url: /tr/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat sınıfı


Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. [IPortionFormatEffectiveData](../iportionformateffectivedata/)'in aksine, bu sınıfın tüm özellikleri yazılabilir.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğine göre karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipindeki nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# stilindeki kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# stilindeki çift hassasiyetli kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Alternatif bir dilin kimliğini döndürür. [System::String](../../system/string/)'ı okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Karmaşık yazıtipi bilgilerini döndürür. Null, yazıtipinin tanımsız olduğu ve Üst'ten kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/)'i okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Doğu Asya yazıtipi bilgilerini döndürür. Null, yazıtipinin tanımsız olduğu ve Üst'ten kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/)'yi okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Metin [EffectFormat](../effectformat/) özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Üst ya da alt simge metnini döndürür. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğunu ve Üst'ten kalıtılması gerektiğini gösterir. **float** okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Metin [FillFormat](../fillformat/) özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Yazıtipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'ı okuyun. |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Bir bölümün yazıtipi yüksekliğini döndürür. **std::numeric_limits<float>::quiet_NaN()** yükseklik tanımsızdır ve Üst'ten kalıtılması gerekir. **float** okunur. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Yazıtipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'ı okuyun. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Metin altı çizgi tipini döndürür. Kalıtım uygulanmaz. [TextUnderlineType](../textunderlinetype/)'i okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Metni vurgulamak için kullanılan rengi döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Altı çizgi stilinin kendi [FillFormat](../fillformat/) özelliklerine sahip olup olmadığını veya metnin [FillFormat](../fillformat/) özelliklerinden miras alıp almadığını belirler. [NullableBool](../nullablebool/)'yi okuyun. |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Altı çizgi stilinin kendi [LineFormat](../lineformat/) özelliklerine sahip olup olmadığını veya metnin [LineFormat](../lineformat/) özelliklerinden miras alıp almadığını belirler. [NullableBool](../nullablebool/)'yi okuyun. |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Kerning'in açılması gereken en küçük yazıtipi boyutunu döndürür. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğunu ve Üst'ten kalıtılması gerektiğini gösterir. **float** okunur. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Sayıların metnin doğu diline özgü dikey metin düzenini görmezden gelmesi gerektiğini belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'i okuyun. |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Denetleme dilinin kimliğini döndürür. Yazım ve dil bilgisi denetimi için kullanılır. [System::String](../../system/string/)'ı okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Latin yazıtipi bilgilerini döndürür. Null, yazıtipinin tanımsız olduğu ve Üst'ten kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/)'yi okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Metin taslağı için [LineFormat](../lineformat/) özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'i okuyun. |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Metnin denetlenmemesi gerektiğini belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'ü okuyun. |
| virtual **float** [get_Spacing](./get_spacing/)() | Karakterler arası boşluk artışını döndürür. **std::numeric_limits<float>::quiet_NaN()** değerin tanımsız olduğunu ve Üst'ten kalıtılması gerektiğini gösterir. **float** okunur. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Metin bölümü için yazım denetiminin etkin olup olmadığını gösteren bir değer alır. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimi bastırılır. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Bir metnin üstü çizili tipini döndürür. Kalıtım uygulanmaz. [TextStrikethroughType](../textstrikethroughtype/)'yu okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Sembolik yazıtipi bilgilerini döndürür. Null, yazıtipinin tanımsız olduğu ve Üst'ten kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/)'yi okuyun. |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Metin büyük/küçük harf tipini döndürür. Kalıtım uygulanmaz. [Slides::TextCapType](../textcaptype/)'i okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Altı çizgi satır [FillFormat](../fillformat/) özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Altı çizgi satırını taslaklamak için kullanılan [LineFormat](../lineformat/) özelliklerini döndürür. Kalıtım uygulanmaz. Yalnızca okunabilir [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özelleştirilmiş nesnelerin karmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, hedefTip tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeri. Özelleştirilmiş tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın dize ve nullptr durumu için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın dize durumu için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Alternatif bir dilin kimliğini ayarlar. [System::String](../../system/string/)'ı yazın. |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Karmaşık yazıtipi bilgilerini ayarlar. Null, yazıtipinin tanımsız olduğu ve Üst'ten kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/)'i yazın. |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Doğu Asya yazıtipi bilgilerini ayarlar. Null, yazıtipinin tanımsız olduğu ve Üst'ten kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/)'i yazın. |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Üst ya da alt simge metnini ayarlar. Değer -%100 (alt simge) ile %100 (üst simge) arasındadır. **std::numeric_limits<float>::quiet_NaN()** değer tanımsızdır ve Üst'ten kalıtılması gerekir. **float**'ı yazın. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Yazıtipinin kalın olup olmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'ı yazın. |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Bir bölümün yazıtipi yüksekliğini ayarlar. **std::numeric_limits<float>::quiet_NaN()** yükseklik tanımsızdır ve Üst'ten kalıtılması gerekir. **float**'ı yazın. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Yazıtipinin italik olup olmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'i yazın. |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Metin altı çizgi tipini ayarlar. Kalıtım uygulanmaz. [TextUnderlineType](../textunderlinetype/)'yi yazın. |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Altı çizgi stilinin kendi [FillFormat](../fillformat/) özelliklerine sahip olup olmadığını veya metnin [FillFormat](../fillformat/) özelliklerinden miras alıp almadığını belirler. [NullableBool](../nullablebool/)'ü yazın. |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Altı çizgi stilinin kendi [LineFormat](../lineformat/) özelliklerine sahip olup olmadığını veya metnin [LineFormat](../lineformat/) özelliklerinden miras alıp almadığını belirler. [NullableBool](../nullablebool/)'yi yazın. |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Kerning'in açılması gereken en küçük yazıtipi boyutunu ayarlar. **std::numeric_limits<float>::quiet_NaN()** değer tanımsızdır ve Üst'ten kalıtılması gerekir. **float**'ı yazın. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Sayıların metnin doğu diline özgü dikey metin düzenini görmezden gelmesini belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'yi yazın. |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Denetleme dilinin kimliğini ayarlar. Yazım ve dil bilgisi denetimi için kullanılır. [System::String](../../system/string/)'yi yazın. |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Latin yazıtipi bilgilerini ayarlar. Null, yazıtipinin tanımsız olduğu ve Üst'ten kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/)'yi yazın. |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Metnin yüksekliğinin normalleştirilip normalleştirilmeyeceğini belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'i yazın. |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Metnin denetlenmemesi gerektiğini belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/)'yu yazın. |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Karakterler arası boşluk artışını ayarlar. **std::numeric_limits<float>::quiet_NaN()** değer tanımsızdır ve Üst'ten kalıtılması gerekir. **float**'ı yazın. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Metin bölümü için yazım denetiminin etkin olup olmadığını gösteren bir değer ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimi bastırılır. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Bir metnin üstü çizili tipini ayarlar. Kalıtım uygulanmaz. [TextStrikethroughType](../textstrikethroughtype/)'u yazın. |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sembolik yazıtipi bilgilerini ayarlar. Null, yazıtipinin tanımsız olduğu ve Üst'ten kalıtılması gerektiği anlamına gelir. [IFontData](../ifontdata/)'i yazın. |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Metin büyük/küçük harf tipini ayarlar. Kalıtım uygulanmaz. [Slides::TextCapType](../textcaptype/)'i yazın. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (shared yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özelleştirilmiş nesneleri dizeye dönüştürmeyi sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Açıklamalar

Bu sınıf, belirli bölüm için tanımlanmış metin bölümü biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken kalıtım uygulanmadığı anlamına gelir; bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler elde edersiniz.

Kalıtım da dahil olmak üzere etkili biçimlendirme parametresi değerlerini elde etmek için [IPortionFormat::GetEffective](../iportionformat/geteffective/) yöntemini kullanmanız gerekir; bu yöntem bir [IPortionFormatEffectiveData](../iportionformateffectivedata/) örneği döndürür.

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)