---
title: FileInfo
second_title: Aspose.Slides için C++ API Referansı
description: "Bir dosyaya giden yolu ve bu yol tarafından başvurulan dosyayı temsil eder ve üzerinde işlem yapma yöntemleri sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığıt üzerinde ya da new operatörüyle oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 274
url: /tr/system.io/fileinfo/
---
## FileInfo sınıfı

Bir dosyaya giden yolu ve bu yol tarafından başvurulan dosyayı temsil eder ve üzerinde işlem yapma yöntemleri sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığıt (stack) üzerinde ya da new operatörüyle oluşturmamalısınız; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Yöntemler

| Method | Description |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Mevcut nesne tarafından temsil edilen bir dosyayı, UTF-8 kodlamasını kullanarak metin yazmak için, 'Append' modunda ve paylaşım olmadan açar. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Mevcut nesne tarafından temsil edilen dosyayı belirtilen konuma kopyalar. Hedef dosya zaten mevcutsa, kopyalama başarısız olur. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Mevcut nesne tarafından temsil edilen dosyayı belirtilen konuma kopyalar. Bir parametre, mevcut hedef dosyanın üzerine yazılıp yazılmayacağını belirler. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Mevcut nesne tarafından temsil edilen yolun belirttiği konumda bir dosya oluşturur ve dosyayı okuma-yazma için, truncate modunda ve paylaşım olmadan açar. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Mevcut nesne tarafından temsil edilen yolun belirttiği konumda bir dosya oluşturur ve dosyayı UTF-8 kodlamasını kullanarak metin yazmak için, paylaşım olmadan açar. |
| void [Decrypt](./decrypt/)() | UYGULANMADI. |
| void [Delete](./delete/)() override | Mevcut nesne tarafından temsil edilen dosyayı siler. |
| void [Encrypt](./encrypt/)() | UYGULANMADI. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmaması gerektiği halde, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmaması gerektiği halde, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
|  [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | [FileInfo](./) sınıfının belirtilen dosyayı temsil eden yeni bir örneğini oluşturur. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Hiçbir şey yapmaz. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Mevcut nesne tarafından temsil edilen varlığın özniteliklerini döndürür. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Mevcut nesne tarafından temsil edilen varlığın oluşturulma zamanını yerel zaman olarak döndürür. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Mevcut nesne tarafından temsil edilen varlığın oluşturulma zamanını UTC zamanı olarak döndürür. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | [DirectoryInfo](../directoryinfo/) nesnesini döndürür; bu nesne, mevcut nesne tarafından temsil edilen dosyanın bulunduğu dizini temsil eder. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Mevcut nesne tarafından temsil edilen dosyanın bulunduğu dizinin tam adını döndürür. |
| **bool** [get_Exists](./get_exists/)() override | Dosyanın var olup olmadığını belirten bir değer döndürür. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Mevcut nesne tarafından temsil edilen dosyanın uzantısını döndürür. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Mevcut nesne tarafından temsil edilen varlığın tam adını (yolu dahil) döndürür. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | ReadOnly özniteliğinin ayarlanıp ayarlanmadığını belirten bir değer döndürür. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Mevcut nesne tarafından temsil edilen varlığın son erişim zamanını yerel zaman olarak döndürür. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Mevcut nesne tarafından temsil edilen varlığın son erişim zamanını UTC zamanı olarak döndürür. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Mevcut nesne tarafından temsil edilen varlığın son yazma zamanını yerel zaman olarak döndürür. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Mevcut nesne tarafından temsil edilen varlığın son yazma zamanını UTC zamanı olarak döndürür. |
| **int64_t** [get_Length](./get_length/)() | Dosyanın boyutunu bayt cinsinden döndürür. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Dosyanın adını döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlemesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, hedefTip tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Mevcut nesne tarafından temsil edilen dosyayı belirtilen konuma taşır. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Mevcut nesne tarafından temsil edilen dosyayı belirtilen modda, okuma ve yazma için, paylaşım olmadan açar. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Mevcut nesne tarafından temsil edilen dosyayı belirtilen modda, belirtilen erişim türüyle ve paylaşım olmadan açar. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Mevcut nesne tarafından temsil edilen dosyayı belirtilen modda, belirtilen erişim tür ve paylaşım seçeneğiyle açar. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Mevcut nesne tarafından temsil edilen dosyayı yalnızca okuma için, 'Open' modunda ve okuma için paylaşımlı erişimle açar. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Mevcut nesne tarafından temsil edilen yolun belirttiği konumdaki mevcut dosyayı, UTF-8 kodlamasını kullanarak metin okuma için, paylaşım olmadan açar. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Mevcut nesne tarafından temsil edilen dosyayı yalnızca yazma için, 'OpenOrCreate' modunda ve paylaşım olmadan açar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için özelleştirilmiş hâli. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin stringler durumundaki özelleştirilmiş hâli. |
| void [Refresh](../filesysteminfo/refresh/)() | Mevcut nesnenin durumunu yeniler. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen hedef dosyanın içeriğini mevcut [FileInfo](./) nesnesi tarafından temsil edilen dosyayla değiştirir ve değiştirilen dosyanın bir yedeğini oluşturur. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Belirtilen hedef dosyanın içeriğini mevcut [FileInfo](./) nesnesi tarafından temsil edilen dosyayla değiştirir ve değiştirilen dosyanın bir yedeğini oluşturur. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Mevcut nesne tarafından temsil edilen varlık üzerine belirtilen öznitelikleri ayarlar. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Mevcut nesne tarafından temsil edilen varlığın oluşturulma zamanını yerel zaman olarak ayarlar. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Mevcut nesne tarafından temsil edilen varlığın oluşturulma zamanını UTC zamanı olarak ayarlar. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Dosyadaki ReadOnly özniteliğini ayarlar veya kaldırır. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Mevcut nesne tarafından temsil edilen varlığın son erişim zamanını yerel zaman olarak ayarlar. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Mevcut nesne tarafından temsil edilen varlığın son erişim zamanını UTC zamanı olarak ayarlar. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Mevcut nesne tarafından temsil edilen varlığın son yazma zamanını yerel zaman olarak ayarlar. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Mevcut nesne tarafından temsil edilen varlığın son yazma zamanını UTC zamanı olarak ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | N. şablon argümanını güçlü (shared) yerine zayıf (weak) işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Mevcut nesne tarafından temsil edilen bir yolu döndürür. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [FileSystemInfo](../filesysteminfo/)
* AdAlanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)