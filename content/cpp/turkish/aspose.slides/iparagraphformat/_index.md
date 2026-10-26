---
title: IParagraphFormat
second_title: Aspose.Slides için C++ API Referansı
description: Bu sınıf paragraf biçimlendirme özelliklerini içerir. IParagraphFormatEffectiveData'nin aksine, bu sınıfın tüm özellikleri yazılabilir.
type: docs
weight: 3147
url: /tr/aspose.slides/iparagraphformat/
---
## IParagraphFormat sınıf


Bu sınıf paragraf biçimlendirme özelliklerini içerir. [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)'in aksine, bu sınıfın tüm özellikleri yazılabilir.

```cpp
class IParagraphFormat : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Kalıtım uygulanmadan bir paragraftaki metin hizalamasını döndürür. Okuyun [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | Paragrafın madde işareti biçimini döndürür. Salt okunur [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Paragrafın varsayılan bölüm biçimini döndürür. Kalıtım uygulanmaz. Salt okunur [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Kalıtım olmadan varsayılan sekme boyutunu döndürür. **float** okuyun. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Paragrafın derinliğini döndürür. Değer 0 tanımsız değeri ifade eder. **int16_t** okuyun. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Paragrafta Doğu Asya satır sonunun kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/) okuyun. |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Kalıtım olmadan bir paragrafta yazı tipi hizalamasını döndürür. [Slides::FontAlignment](../fontalignment/) okuyun. |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Paragrafta sarkık noktalama işaretlerinin kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/) okuyun. |
| virtual **float** [get_Indent](./get_indent/)() | Kalıtım olmadan paragrafın İlk Satır Girintisi/Sarkık Girintisini döndürür. Sarkık Girinti negatif değerlerle tanımlanabilir. **float** okuyun. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Paragrafta Latin satır sonunun kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/) okuyun. |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Kalıtım olmadan bir paragraftaki sol kenar boşluğunu döndürür. **float** okuyun. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Kalıtım olmadan bir paragraftaki sağ kenar boşluğunu döndürür. **float** okuyun. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/) okuyun. |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Kalıtım olmadan bir paragrafta son satırdan sonraki boşluk miktarını döndürür. Pozitif değer, boşluğun yazı tipi boyutunun yüzde olarak ne kadar olacağını belirtir. Negatif değer, boşluğun nokta boyutunda boyutunu belirtir. **float** okuyun. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Kalıtım olmadan bir paragrafta ilk satırdan önceki boşluk miktarını döndürür. Pozitif değer, boşluğun yazı tipi boyutunun yüzde olarak ne kadar olacağını belirtir. Negatif değer, boşluğun nokta boyutunda boyutunu belirtir. **float** okuyun. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Paragrafta temel satırlar arasındaki boşluk miktarını döndürür. Pozitif değer yüzde, negatif değer ise nokta cinsinden boyuttur. Kalıtım uygulanmaz. **float** okuyun. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Belirtilen indeksde bir paragrafın sekmesini döndürür. Kalıtım uygulanmaz. Salt okunur [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | Paragrafın sekmelerini döndürür. Kalıtım uygulanmaz. Salt okunur [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | Kalıtım uygulanmış etkili paragraf biçimlendirme verilerini alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin C# analogudur. Özel nesnelerin karmasını (hash) etkinleştirir. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogudur. Özel türlerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmalarını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmalarını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumundaki özelleşmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumundaki özelleşmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | Kalıtım olmadan bir paragraftaki metin hizalamasını ayarlar. [TextAlignment](../textalignment/) yazın. |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Kalıtım olmadan varsayılan sekme boyutunu ayarlar. **float** yazın. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | Paragrafın derinliğini ayarlar. Değer 0 tanımsız değeri ifade eder. **int16_t** yazın. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | Paragrafta Doğu Asya satır sonunun kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/) yazın. |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | Kalıtım olmadan bir paragrafta yazı tipi hizalamasını ayarlar. [Slides::FontAlignment](../fontalignment/) yazın. |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | Paragrafta sarkık noktalama işaretlerinin kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/) yazın. |
| virtual void [set_Indent](./set_indent/)(**float**) | Kalıtım olmadan paragrafın İlk Satır Girintisi/Sarkık Girintisini ayarlar. Sarkık Girinti negatif değerlerle tanımlanabilir. **float** yazın. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | Paragrafta Latin satır sonunun kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/) yazın. |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Kalıtım olmadan bir paragraftaki sol kenar boşluğunu ayarlar. **float** yazın. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Kalıtım olmadan bir paragraftaki sağ kenar boşluğunu ayarlar. **float** yazın. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz. [NullableBool](../nullablebool/) yazın. |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Kalıtım olmadan bir paragrafta son satırdan sonraki boşluk miktarını ayarlar. Pozitif değer, boşluğun yazı tipi boyutunun yüzde olarak ne kadar olacağını belirtir. Negatif değer, boşluğun nokta boyutunda boyutunu belirtir. **float** yazın. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Kalıtım olmadan bir paragrafta ilk satırdan önceki boşluk miktarını ayarlar. Pozitif değer, boşluğun yazı tipi boyutunun yüzde olarak ne kadar olacağını belirtir. Negatif değer, boşluğun nokta boyutunda boyutunu belirtir. **float** yazın. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Paragrafta temel satırlar arasındaki boşluk miktarını ayarlar. Pozitif değer yüzde, negatif değer nokta cinsinden boyuttur. Kalıtım uygulanmaz. **float** yazın. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılarda işaretçileri zayıf moda geçiş yapmayı sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | [Object.ToString()](../../system/object/tostring/) yönteminin C# analogudur. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Açıklamalar

Bu sınıf belirli bir paragraf için tanımlanan paragraf biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerleri alırken kalıtım uygulanmadığı anlamına gelir, bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler alırsınız.

Kalıtım dahil olmak üzere etkili biçimlendirme parametresi değerlerini almak için [IParagraphFormat::GetEffective](./geteffective/) yöntemini kullanmanız gerekir; bu yöntem bir [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) örneği döndürür.

## İlgili

* Sınıf [Object](../../system/object/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)