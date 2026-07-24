---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides için C++ API Referansı
description: Altbilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar düzen slaytı kullanır ve ona bağımlıdır.
type: docs
weight: 2666
url: /tr/aspose.slides/ilayoutslideheaderfootermanager/
---
## ILayoutSlideHeaderFooterManager sınıf

Düzen slayt altbilgisi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar düzen slaytı kullanır ve ona bağımlıdır.

```cpp
class ILayoutSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseSlideHeaderFooterManager
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | Bir tarih-saat yer tutucusunun mevcut olduğunu gösteren değeri alır. Read**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | Bir altbilgi yer tutucusunun mevcut olduğunu gösteren değeri alır. Read **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | Bir sayfa numarası yer tutucusunun mevcut olduğunu gösteren değeri alır. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize ve nullptr durumuna özgülleşmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize durumuna özgülleşmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | Düzen slayt tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar düzen slaytı kullanır ve ona bağımlıdır. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | Düzen slayt tarih-saat yer tutucusunun ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar düzen slaytı kullanır ve ona bağımlıdır. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | Slayt tarih-saat yer tutucusuna metin ayarlar. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | Slayt tarih-saat yer tutucusunun görünürlüğünü değiştirir. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | Düzen slayt altbilgi yer tutucusuna ve tüm alt altbilgi yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar düzen slaytı kullanır ve ona bağımlıdır. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | Düzen slayt altbilgi yer tutucusunun ve tüm alt altbilgi yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar ana slaytı (master slide) kullanır ve ona bağımlıdır. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | Slayt altbilgi yer tutucusuna metin ayarlar. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | Slayt altbilgi yer tutucusunun görünürlüğünü değiştirir. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | Düzen slayt sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı slaytlarda bulunan yer tutucular anlamına gelir. Bağımlı slaytlar düzen slaytı kullanır ve ona bağımlıdır. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | Slayt sayfa numarası yer tutucusunun görünürlüğünü değiştirir. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını ortak (shared) yerine zayıf (weak) işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açmayı uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
## Bakınız

* Sınıf [IBaseSlideHeaderFooterManager](../ibaseslideheaderfootermanager/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)