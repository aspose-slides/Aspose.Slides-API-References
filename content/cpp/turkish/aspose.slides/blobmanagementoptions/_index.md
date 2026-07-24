---
title: BlobManagementOptions
second_title: Aspose.Slides for C++ API Referansı
description: BLOB işleme kurallarını ve diğer BLOB ayarlarını yönetmek için kullanılabilecek seçenekleri temsil eder.
type: docs
weight: 196
url: /tr/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions sınıf

BLOB işleme kurallarını ve diğer BLOB ayarlarını yönetmek için kullanılabilecek seçenekleri temsil eder.

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | Yeni varsayılan blob yönetim seçenekleri oluşturur. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) anlamı kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN'in hiçbir değerle, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN'in hiçbir değerle, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | Bu özellik, BLOB'larla çalışılırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini önemli ölçüde azaltır ancak dosya oluşturma izinleri gerektirir. |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | Tüm BLOB'ların bellekte kaplayabileceği azami toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu limit aşıldığında yalnızca geçici dosyalar gibi alternatif mekanizmalar devreye girer. BLOB'ları bellekte tutmak performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın. |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | Bu özellik, [Presentation](../presentation/) sınıfının bir örneğinin örnek ömrü boyunca kaynak - dosya veya akışın sahibi olup olamayacağını tanımlar. Örnek bir sahip ise, kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı artırmaya yardımcı olur, ancak kaynak (akış veya dosya) [Presentation](../presentation/)'s örnek ömrü boyunca değiştirilemez. |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | Geçici dosyaların oluşturulacağı kök yol. Varsayılan olarak [System](../../system/) geçici dizini kullanılacak. Barındırma sürecinin burada dosya ve klasör oluşturma izinlerine sahip olması gerekir. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | Bu özellik, BLOB'larla çalışılırken geçici dosyaların oluşturulup oluşturulamayacağını tanımlar; bu, bellek tüketimini önemli ölçüde azaltır ancak dosya oluşturma izinleri gerektirir. |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | Tüm BLOB'ların bellekte kaplayabileceği azami toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu limit aşıldığında yalnızca geçici dosyalar gibi alternatif mekanizmalar devreye girer. BLOB'ları bellekte tutmak performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın. |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | Bu özellik, [Presentation](../presentation/) sınıfının bir örneğinin örnek ömrü boyunca kaynak - dosya veya akışın sahibi olup olamayacağını tanımlar. Örnek bir sahip ise, kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı artırmaya yardımcı olur, ancak kaynak (akış veya dosya) [Presentation](../presentation/)'s örnek ömrü boyunca değiştirilemez. |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | Geçici dosyaların oluşturulacağı kök yol. Varsayılan olarak [System](../../system/) geçici dizini kullanılacak. Barındırma sürecinin burada dosya ve klasör oluşturma izinlerine sahip olması gerekir. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve geri döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IBlobManagementOptions](../iblobmanagementoptions/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)