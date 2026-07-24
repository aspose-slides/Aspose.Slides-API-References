---
title: IBlobManagementOptions
second_title: Aspose.Slides for C++ API Referansı
description: Binary Large Object (BLOB), tek bir varlık olarak depolanan ikili veridir; yani BLOB bir ses, video ya da sunumun kendisi olabilir. BLOB'larla çalışırken bellek tüketimini optimize etmek için çeşitli teknikler kullanılır; BLOB'lar zaten sunumda depolanmış ya da daha sonra programmatically eklenebilir. IBlobManagementOptions kullanarak, IPresentation örneğinin ömrü boyunca BLOB işleme ile ilgili davranış yönlerini değiştirebilirsiniz.
type: docs
weight: 1535
url: /tr/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions sınıf


A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself. A number of techniques are used to optimize memory consumption while working with BLOBs - which was already stored in the presentation or be added later programmatically. Using [IBlobManagementOptions](./) you can change a different behavior aspects regarding BLOBs handling for the [IPresentation](../ipresentation/) instance lifetime.

```cpp
class IBlobManagementOptions : public virtual System::Object
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN değeri IEC 60559:1989 standardına göre NaN herhangi bir değere, NaN dahil, eşit değildir ancak burada eşit kabul edilir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN değeri IEC 60559:1989 standardına göre NaN herhangi bir değere, NaN dahil, eşit değildir ancak burada eşit kabul edilir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() | Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını belirler; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerekir. |
| virtual **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() | Bellekte tüm BLOB'ların kaplayabileceği maksimum toplam boyutu (bayt olarak) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu limit aşıldığında yalnızca geçici dosyalar gibi alternatif mekanizmalar devreye girer. BLOB'ları bellek içinde tutmak performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın. |
| virtual [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() | Bu özellik, [Presentation](../presentation/) sınıfının bir örneğinin yaşam süresi boyunca kaynak - dosya veya akışın sahibi olup olamayacağını belirler. Eğer örnek sahibi ise, kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı artırmaya yardımcı olur, ancak kaynak (akış veya dosya) [Presentation](../presentation/)'ın yaşam süresi boyunca değiştirilemez. İşte bir örnek: |
| virtual [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() | Geçici dosyaların oluşturulacağı kök yol. [System](../../system/) geçici dizini varsayılan olarak kullanılacaktır. Barındırma süreci burada dosya ve klasör oluşturma izinlerine sahip olmalıdır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analogudur. Özelleştirilmiş nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogudur. Özelleştirilmiş tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirilmiş versiyonu. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirilmiş versiyonu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) | Bu özellik, BLOB'larla çalışırken geçici dosyaların oluşturulup oluşturulamayacağını belirler; bu, bellek tüketimini büyük ölçüde azaltır ancak dosya oluşturma izinleri gerekir. |
| virtual void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) | Bellekte tüm BLOB'ların kaplayabileceği maksimum toplam boyutu (bayt olarak) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu limit aşıldığında yalnızca geçici dosyalar gibi alternatif mekanizmalar devreye girer. BLOB'ları bellek içinde tutmak performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın. |
| virtual void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) | Bu özellik, [Presentation](../presentation/) sınıfının bir örneğinin yaşam süresi boyunca kaynak - dosya veya akışın sahibi olup olamayacağını belirler. Eğer örnek sahibi ise, kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı artırmaya yardımcı olur, ancak kaynak (akış veya dosya) [Presentation](../presentation/)'ın yaşam süresi boyunca değiştirilemez. İşte bir örnek: |
| virtual void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) | Geçici dosyaların oluşturulacağı kök yol. [System](../../system/) geçici dizini varsayılan olarak kullanılacaktır. Barındırma süreci burada dosya ve klasör oluşturma izinlerine sahip olmalıdır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf gösterici olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişine olanak tanır. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının şu anki değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analogudur. Özelleştirilmiş nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidi kaldırma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapıları serbest bırakılır. |

## Bakınız

* Sınıf [Object](../../system/object/)
* AdAlanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)