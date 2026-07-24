---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides for C++ API Referansı
description: Düzen slayt altbilgi, tarih-saat ve sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar düzen slaytı kullanır ve ona bağlıdır.
type: docs
weight: 4317
url: /tr/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager sınıf


Düzen slayt altbilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar düzen slaytı kullanır ve ona bağlıdır.

```cpp
class LayoutSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::ILayoutSlideHeaderFooterManager
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989’a göre NaN’ın hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN’ın eşit kabul edildiği C#-tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989’a göre NaN’ın hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN’ın eşit kabul edildiği C#-tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Bir tarih-saat yer tutucusunun mevcut olduğunu gösteren değeri alır. Oku**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Bir altbilgi yer tutucusunun mevcut olduğunu gösteren değeri alır. Oku **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Bir sayfa numarası yer tutucusunun mevcut olduğunu gösteren değeri alır. Oku**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) nöbetçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeri. Özel türlerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya kurucu ile oluşturulmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya kurucu ile oluşturulmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in stringler durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | Düzen slayt tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar düzen slaytı kullanır ve ona bağlıdır. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | Düzen slayt tarih-saat yer tutucusunun ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar düzen slaytı kullanır ve ona bağlıdır. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Slayt tarih-saat yer tutucusuna metin ayarlar. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Slayt tarih-saat yer tutucusunun görünürlüğünü değiştirir. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | Düzen slayt altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar düzen slaytı kullanır ve ona bağlıdır. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | Düzen slayt altbilgi yer tutucusunun ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar ana slaytı kullanır ve ona bağlıdır. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Slayt altbilgi yer tutucusuna metin ayarlar. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Slayt altbilgi yer tutucusunun görünürlüğünü değiştirir. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | Düzen slayt sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar düzen slaytı kullanır ve ona bağlıdır. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Slayt sayfa numarası yer tutucusunun görünürlüğünü değiştirir. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) nöbetçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* Sınıf [ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/)
* AdAlanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)