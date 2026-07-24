---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides için C++ API Referansı
description: Ana slayt altbilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar ana slaytı kullanır ve ona bağlıdır.
type: docs
weight: 4499
url: /tr/aspose.slides/masterslideheaderfootermanager/
---
## MasterSlideHeaderFooterManager sınıf

Ana slayt altbilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar ana slaytı kullanır ve ona bağlıdır.

```cpp
class MasterSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::IMasterSlideHeaderFooterManager
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN değeri eşit kabul edilen C#-stilinde kayan nokta karşılaştırması yapar; IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN değeri eşit kabul edilen C#-stilinde kayan nokta karşılaştırması yapar; IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Bir tarih-saat yer tutucusunun mevcut olduğunu gösteren değeri alır. Oku**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Bir altbilgi yer tutucusunun mevcut olduğunu gösteren değeri alır. Oku **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Bir sayfa numarası yer tutucusunun mevcut olduğunu gösteren değeri alır. Oku**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin karma (hash) oluşturmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, hedefTip tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# ‘is’ operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans-karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | Ana slayt tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar ana slaytı kullanır ve ona bağlıdır. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | Ana slayt tarih-saat yer tutucusunun ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar ana slaytı kullanır ve ona bağlıdır. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Slayt tarih-saat yer tutucusuna metin ayarlar. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Slayt tarih-saat yer tutucusunun görünürlüğünü değiştirir. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | Ana slayt altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar ana slaytı kullanır ve ona bağlıdır. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | Ana slayt altbilgi yer tutucusunun ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar ana slaytı kullanır ve ona bağlıdır. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Slayt altbilgi yer tutucusuna metin ayarlar. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Slayt altbilgi yer tutucusunun görünürlüğünü değiştirir. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | Ana slayt sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı düzen slaytları ve bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı düzen slaytları ve slaytlar ana slaytı kullanır ve ona bağlıdır. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Slayt sayfa numarası yer tutucusunun görünürlüğünü değiştirir. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-inci şablon argümanını paylaşılan yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapıları serbest bırakılır. |

## Ayrıca Bakınız

* Sınıf [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* Sınıf [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)
* Ad Alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)