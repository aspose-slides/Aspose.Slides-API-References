---
title: DirectoryInfo
second_title: Aspose.Slides for C++ API Referansı
description: "Bir dosya sistemi yolunu, bu yol tarafından referans edilen bir dizini temsil eder ve dizinleri manipüle etmek için örnek yöntemler sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Yığını (stack) üzerinde veya new operatörü ile bu tipin bir örneğini oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 248
url: /tr/system.io/directoryinfo/
---
## DirectoryInfo sınıfı

Represents a file system path, a directory referred to by this path and provides instance methods for manipulating directories. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| void [Create](./create/)() | Geçerli nesne tarafından temsil edilen yolda bir dizin oluşturur. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | Belirtilen yolda alt dizinler oluşturur. |
| void [Delete](./delete/)() override | Geçerli nesnenin temsil ettiği yol tarafından referans edilen dizin, eğer boş ise kaldırılır. |
| void [Delete](./delete/)(**bool**) | Geçerli nesnenin temsil ettiği yol tarafından referans edilen dizini kaldırır. Bir parametre, dizin boş değilse içeriğin yinelemeli olarak kaldırılıp kaldırılmayacağını belirtir. |
| [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | Belirtilen yolda [DirectoryInfo](./) sınıfının bir örneğini oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dizinleri içeren yinelenebilir bir koleksiyon döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dizinleri arar. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Geçerli nesne tarafından temsil edilen dizinde veya o dizinden köklenen tüm dizin ağacında belirtilen arama kriterlerini karşılayan dizinleri arar. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosyaları içeren yinelenebilir bir koleksiyon döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dosyaları arar. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Geçerli nesne tarafından temsil edilen dizinde veya o dizinden köklenen tüm dizin ağacında belirtilen arama kriterlerini karşılayan dosyaları arar. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosya ve dizinleri içeren yinelenebilir bir koleksiyon döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Geçerli nesne tarafından temsil edilen dizinde veya o dizinden köklenen tüm dizin ağacında belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) semantiği ile karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı çift duyarlıklı (double) kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Hiçbir şey yapmaz. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Geçerli nesne tarafından temsil edilen varlığın özelliklerini döndürür. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Geçerli nesne tarafından temsil edilen varlığın oluşturma zamanını yerel zaman olarak döndürür. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Geçerli nesne tarafından temsil edilen varlığın oluşturma zamanını UTC zamanı olarak döndürür. |
| **bool** [get_Exists](./get_exists/)() override | Geçerli nesne tarafından temsil edilen yolun var olan bir dizine işaret edip etmediğini belirler. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Geçerli nesne tarafından temsil edilen dosyanın uzantısını döndürür. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Geçerli nesne tarafından temsil edilen varlığın tam adını (yolu dahil) döndürür. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Geçerli nesne tarafından temsil edilen varlığın son erişim zamanını yerel zaman olarak döndürür. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Geçerli nesne tarafından temsil edilen varlığın son erişim zamanını UTC zamanı olarak döndürür. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Geçerli nesne tarafından temsil edilen varlığın son yazma zamanını yerel zaman olarak döndürür. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Geçerli nesne tarafından temsil edilen varlığın son yazma zamanını UTC zamanı olarak döndürür. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Geçerli nesne tarafından temsil edilen yolun işaret ettiği varlığın adını döndürür. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | [DirectoryInfo](./) nesnesine bir paylaşımlı işaretçi döndürür; bu nesne geçerli nesne tarafından temsil edilen dizinin üst dizinine işaret eden bir yolu temsil eder. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | [DirectoryInfo](./) nesnesine bir paylaşımlı işaretçi döndürür; bu nesne geçerli nesne tarafından temsil edilen dizinin kök dizinine işaret eden bir yolu temsil eder. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dizinleri temsil eden [DirectoryInfo](./) nesnelerine paylaşımlı işaretçiler içeren bir dizi döndürür. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dizinleri arar. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Geçerli nesne tarafından temsil edilen dizinde veya o dizinden köklenen tüm dizin ağacında belirtilen arama kriterlerini karşılayan dizinleri arar. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dizinleri temsil eden [FileInfo](../fileinfo/) nesnelerine paylaşımlı işaretçiler içeren bir dizi döndürür. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dosyaları arar. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Geçerli nesne tarafından temsil edilen dizinde veya o dizinden köklenen tüm dizin ağacında belirtilen arama kriterlerini karşılayan dosyaları arar. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosya ve dizinleri temsil eden [FileSystemInfo](../filesysteminfo/) nesnelerine paylaşımlı işaretçiler içeren bir dizi döndürür. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Geçerli nesne tarafından temsil edilen dizinde veya o dizinden köklenen tüm dizin ağacında belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | [Object.GetHashCode()](../../system/object/gethashcode/) metodunun C# analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını (klonlamasını) sağlar. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Geçerli nesne tarafından temsil edilen dizini ve tüm içeriğini belirtilen konuma taşır. |
| [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapıları başlatılır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmalarını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmalarını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nın string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nın stringler durumu için özelleştirmesi. |
| void [Refresh](../filesysteminfo/refresh/)() | Geçerli nesnenin durumunu yeniler. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşımlı referans sayacını belirtilen değer kadar azaltır. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Geçerli nesne tarafından temsil edilen varlığın belirtilen özelliklerini ayarlar. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Geçerli nesne tarafından temsil edilen varlığın oluşturma zamanını yerel zaman olarak ayarlar. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Geçerli nesne tarafından temsil edilen varlığın oluşturma zamanını UTC zamanı olarak ayarlar. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Geçerli nesne tarafından temsil edilen varlığın son erişim zamanını yerel zaman olarak ayarlar. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Geçerli nesne tarafından temsil edilen varlığın son erişim zamanını UTC zamanı olarak ayarlar. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Geçerli nesne tarafından temsil edilen varlığın son yazma zamanını yerel zaman olarak ayarlar. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Geçerli nesne tarafından temsil edilen varlığın son yazma zamanını UTC zamanı olarak ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf bir işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Geçerli nesne tarafından temsil edilen yolu içeren bir dize döndürür. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapıları serbest bırakılır. |

## Ayrıca Bakınız

* Sınıf [FileSystemInfo](../filesysteminfo/)
* Ad Alanı [System::IO](../)
* Library [Aspose.Slides](../../)