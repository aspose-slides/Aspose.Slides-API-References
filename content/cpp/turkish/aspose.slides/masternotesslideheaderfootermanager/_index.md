---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides için C++ API Referansı
description: Ana not slaytı altbilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları ana not slaytını kullanır ve ona bağımlıdır.
type: docs
weight: 4460
url: /tr/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager sınıfı

Ana not slaytı altbilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları ana not slaytını kullanır ve ona bağımlıdır.

```cpp
class MasterNotesSlideHeaderFooterManager : public Aspose::Slides::BaseHandoutNotesSlideHeaderFooterManager,
                                            public Aspose::Slides::IMasterNotesSlideHeaderFooterManager
```

## Metotlar

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Tarih-saat yer tutucusunun mevcut olduğunu gösteren değeri alır. Oku**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Altbilgi yer tutucusunun mevcut olduğunu gösteren değeri alır. Oku **bool**. |
| **bool** [get_IsHeaderVisible](../basehandoutnotesslideheaderfootermanager/get_isheadervisible/)() override | Üstbilgi yer tutucusunun mevcut olduğunu gösteren değeri alır. Oku **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Sayfa numarası yer tutucusunun mevcut olduğunu gösteren değeri alır. Oku**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin karmasını (hash) sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını ilklendirir. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi ilklendirir ve alt sınıfların kopya yapılandırılmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi ilklendirir ve alt sınıfların kopya yapılandırılmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumu için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | Metni ana slayt tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına ayarlar. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları ana not slaytını kullanır ve ona bağımlıdır. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | Ana slayt tarih-saat yer tutucusunun ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları ana not slaytını kullanır ve ona bağımlıdır. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Metni slayt tarih-saat yer tutucusuna ayarlar. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Slayt tarih-saat yer tutucusunun görünürlüğünü değiştirir. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | Metni ana slayt altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına ayarlar. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları ana not slaytını kullanır ve ona bağımlıdır. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | Ana slayt altbilgi yer tutucusunun ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları ana not slaytını kullanır ve ona bağımlıdır. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Metni slayt altbilgi yer tutucusuna ayarlar. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Slayt altbilgi yer tutucusunun görünürlüğünü değiştirir. |
| void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) override | Metni ana not slaytı üstbilgi yer tutucusuna ve tüm alt üstbilgi yer tutucularına ayarlar. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları ana not slaytını kullanır ve ona bağımlıdır. |
| void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) override | Ana not slaytı üstbilgi yer tutucusunun ve tüm alt üstbilgi yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları ana not slaytını kullanır ve ona bağımlıdır. |
| void [SetHeaderText](../basehandoutnotesslideheaderfootermanager/setheadertext/)([System::String](../../system/string/)) override | Metni slayt üstbilgi yer tutucusuna ayarlar. |
| void [SetHeaderVisibility](../basehandoutnotesslideheaderfootermanager/setheadervisibility/)(**bool**) override | Slayt üstbilgi yer tutucusunun görünürlüğünü değiştirir. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | Ana slayt sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları ana not slaytını kullanır ve ona bağımlıdır. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Slayt sayfa numarası yer tutucusunun görünürlüğünü değiştirir. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (shared yerine) olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçirmeye izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager/)
* Sınıf [IMasterNotesSlideHeaderFooterManager](../imasternotesslideheaderfootermanager/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)