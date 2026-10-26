---
title: ParagraphFormat
second_title: Aspose.Slides for C++ API Referansı
description: Bu sınıf paragraf biçimlendirme özelliklerini içerir. IParagraphFormatEffectiveData'dan farklı olarak, bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 4668
url: /tr/aspose.slides/paragraphformat/
---
## ParagraphFormat sınıfı

Bu sınıf paragraf biçimlendirme özelliklerini içerir. [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)'den farklı olarak bu sınıfın tüm özellikleri yazılabilir.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## Yöntemler

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Belirtilen nesneyle karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle eşit olmaması, NaN dahil, olmasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle eşit olmaması, NaN dahil, olmasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | Paragrafta kalıtım olmadan metin hizalamasını döndürür. Oku [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | Kalıtım olmadan varsayılan sekme boyutunu döndürür. Oku **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | Paragrafta Doğu Asya satır sonu kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Oku [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | Paragrafta kalıtım olmadan bir yazı tipi hizalamasını döndürür. Oku [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | Paragrafta asılı noktalama işaretlerinin kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Oku [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | Kalıtım olmadan paragraf İlk Satır Girintisi/Asılı Girinti'yi döndürür. Asılı Girinti negatif değerlerle tanımlanabilir. Oku **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | Paragrafta Latin satır sonu kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Oku [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | Kalıtım olmadan paragraftaki sol kenar boşluğunu döndürür. Oku **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | Kalıtım olmadan paragraftaki sağ kenar boşluğunu döndürür. Oku **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate nesnesini döndürür. Salt-okunur [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Üst [IPresentationComponent](../ipresentationcomponent/) nesnesini döndürür. Salt-okunur [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Oku [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | Kalıtım olmadan paragrafta son satırdan sonra boşluk miktarını döndürür. Pozitif değer, boşluğun yazı tipi boyutunun yüzdesini belirtir. Negatif değer ise boşluğun puan cinsinden büyüklüğünü belirtir. Oku **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | Kalıtım olmadan paragrafta ilk satırdan önceki boşluk miktarını döndürür. Pozitif değer, boşluğun yazı tipi boyutunun yüzde olarak belirtir. Negatif değer ise boşluğun puan cinsinden büyüklüğünü belirtir. Oku **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | Paragrafta temel satırlar arasındaki boşluk miktarını döndürür. Pozitif değer yüzde, negatif değer puan cinsindendir. Kalıtım uygulanmaz. Oku **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | Belirtilen dizinde paragraf sekmesini döndürür. Kalıtım uygulanmaz. Salt-okunur [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | Paragraf sekmelerini döndürür. Kalıtım uygulanmaz. Salt-okunur [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | Kalıtım uygulanmış etkili paragraf biçimlendirme verilerini alır. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Hash kodunu döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, hedefTür tarafından tanımlanan türe ait bir örnek olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesi kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel türlerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
|  [ParagraphFormat](./paragraphformat/)() | [ParagraphFormat](./) sınıfının yeni bir örneğini başlatır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | Paragrafta kalıtım olmadan metin hizalamasını ayarlar. Yaz [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | Kalıtım olmadan varsayılan sekme boyutunu ayarlar. Yaz **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | Paragrafta Doğu Asya satır sonu kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | Paragrafta kalıtım olmadan bir yazı tipi hizalamasını ayarlar. Yaz [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | Paragrafta asılı noktalama işaretlerinin kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | Kalıtım olmadan paragraf İlk Satır Girintisi/Asılı Girinti'yi ayarlar. Asılı Girinti negatif değerlerle tanımlanabilir. Yaz **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | Paragrafta Latin satır sonu kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | Paragrafta sol kenar boşluğunu ayarlar. Yaz **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | Paragrafta sağ kenar boşluğunu ayarlar. Yaz **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. Yaz [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | Kalıtım olmadan paragrafta son satırdan sonra boşluk miktarını ayarlar. Pozitif değer, boşluğun yazı tipi boyutunun yüzde olarak belirtir. Negatif değer ise boşluğun puan cinsinden büyüklüğünü belirtir. Yaz **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | Kalıtım olmadan paragrafta ilk satırdan önceki boşluk miktarını ayarlar. Pozitif değer, boşluğun yazı tipi boyutunun yüzde olarak belirtir. Negatif değer ise boşluğun puan cinsinden büyüklüğünü belirtir. Yaz **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | Paragrafta temel satırlar arasındaki boşluk miktarını ayarlar. Pozitif değer yüzde, negatif değer puan cinsindendir. Kalıtım uygulanmaz. Yaz **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf göstergeci (paylaşımlı değil) olarak ayarlar. Kapsayıcılardaki göstergeçleri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeçler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeçler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesi kilit açma işlemini gerçekleştirir. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeçler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeçler veya ThisProtector kullanılmalıdır. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Açıklamalar

Bu sınıf, belirli bir paragraf için tanımlanmış paragraf biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Değerler alınırken kalıtım uygulanmadığı için çoğu durumda \"tanımsız\" anlamına gelen değerler elde edersiniz.

Kalıtım dahil olmak üzere etkili biçimlendirme parametre değerlerini elde etmek için [ParagraphFormat::GetEffective](./geteffective/) metodunu kullanmanız gerekir; bu metod bir [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) örneği döndürür.

## İlgili Bilgiler

* Sınıf [PVIObject](../pviobject/)
* Sınıf [IParagraphFormat](../iparagraphformat/)
* Sınıf [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* İsim uzayı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)