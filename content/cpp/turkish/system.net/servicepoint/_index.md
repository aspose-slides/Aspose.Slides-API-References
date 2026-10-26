---
title: ServicePoint
second_title: Aspose.Slides for C++ API Referansı
description: "HTTP bağlantı yönetimini sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tipin örneği hiçbir zaman yığında veya operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 417
url: /tr/system.net/servicepoint/
---
## ServicePoint sınıfı

HTTP bağlantı yönetimini sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) fonksiyonu kullanılarak allocate (ayrılmalıdır). Bu tür bir örnek hiçbir zaman yığında veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class ServicePoint : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| **bool** [CloseConnectionGroup](./closeconnectiongroup/)([String](../../system/string/)) | Belirtilen bağlantı grubuna ait bağlantıları kapatır ve kaldırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit değildir, NaN dahil, ancak iki NaN'ı eşit kabul eden C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit değildir, NaN dahil, ancak iki NaN'ı eşit kabul eden C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | Mevcut örneğin bağlandığı sunucu URI'sını döndürür. |
| [BindIPEndPoint](../bindipendpoint/) [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | Yerel [IPEndPoint](../ipendpoint/) ile mevcut örneği ilişkilendirmek için kullanılan delegeyi alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_Certificate](./get_certificate/)() | Mevcut örnek tarafından kullanılan bir sertifikayı döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_ClientCertificate](./get_clientcertificate/)() | Son istemci sertifikasını döndürür. |
| **int32_t** [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | Aktif [ServicePoint](./)'in kapanacağı milisaniye cinsinden zaman aşımını alır. |
| **int32_t** [get_ConnectionLimit](./get_connectionlimit/)() | Mevcut örnek tarafından izin verilen maksimum bağlantı sayısını alır. |
| [String](../../system/string/) [get_ConnectionName](./get_connectionname/)() | Bağlantı adını döndürür. |
| **int32_t** [get_CurrentConnections](./get_currentconnections/)() | Açılan bağlantı sayısını döndürür. |
| **bool** [get_Expect100Continue](./get_expect100continue/)() | 100-Continue davranışının kullanılıp kullanılmadığını gösteren bir değeri alır. |
| [DateTime](../../system/datetime/) [get_IdleSince](./get_idlesince/)() | Bir ana bilgisayara yapılan en son bağlantının tarih ve saatini döndürür. |
| **int32_t** [get_MaxIdleTime](./get_maxidletime/)() | Boşta kalan bir bağlantının kapanacağı milisaniye cinsinden süreyi alır. |
| virtual [Version](../../system/version/) [get_ProtocolVersion](./get_protocolversion/)() | HTTP sürümünü döndürür. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Alma tamponunun boyutunu alır. |
| **bool** [get_SupportsPipelining](./get_supportspipelining/)() | Mevcut örneğin pipeline bağlantılarını destekleyip desteklemediğini gösteren bir değeri döndürür. |
| **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Mevcut örnek tarafından yönetilen bağlantıların Nagle algoritması kullanıp kullanmadığını gösteren bir değeri alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogu. Özelleştirilmiş nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedef tip tarafından tanımlanan bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özelleştirilmiş tiplerin kopyalanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumu için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string durumları için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)([BindIPEndPoint](../bindipendpoint/)) | Yerel [IPEndPoint](../ipendpoint/) ile mevcut örneği ilişkilendirmek için kullanılan delegeyi ayarlar. |
| void [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(**int32_t**) | Aktif [ServicePoint](./)'in kapanacağı milisaniye cinsinden zaman aşımını ayarlar. |
| void [set_ConnectionLimit](./set_connectionlimit/)(**int32_t**) | Mevcut örnek tarafından izin verilen maksimum bağlantı sayısını ayarlar. |
| void [set_Expect100Continue](./set_expect100continue/)(**bool**) | 100-Continue davranışının kullanılıp kullanılmadığını belirten bir değeri ayarlar. |
| void [set_MaxIdleTime](./set_maxidletime/)(**int32_t**) | Boşta kalan bir bağlantının kapanacağı milisaniye cinsinden süreyi ayarlar. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Alma tamponunun boyutunu ayarlar. |
| void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Mevcut örnek tarafından yönetilen bağlantıların Nagle algoritması kullanıp kullanmadığını belirten bir değeri ayarlar. |
| void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | 'Keep-Alive' seçeneğinin etkin olup olmadığını belirten değeri ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özelleştirilmiş nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Diğer Bağlantılar

* Sınıf [Object](../../system/object/)
* Ad Alanı [System::Net](../)
* Kütüphane [Aspose.Slides](../../)