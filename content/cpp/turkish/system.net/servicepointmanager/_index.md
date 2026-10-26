---
title: ServicePointManager
second_title: Aspose.Slides için C++ API Referansı
description: "ServicePoint sınıfı örneklerinin yaşam döngüsü aşamalarını (oluşturma, sürdürme ve silme) yönetir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığında veya new operatörüyle oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Her zaman bu sınıfı System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 430
url: /tr/system.net/servicepointmanager/
---
## ServicePointManager sınıfı


Bu sınıfın [ServicePoint](../servicepoint/) sınıf örneklerinin yaşam döngüsü aşamalarını (oluşturma, sürdürme ve silme) yönetir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) fonksiyonu kullanılarak tahsis edilmelidir. Yığın üzerinde veya new operatörüyle bu tür bir örnek oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya assert hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class ServicePointManager : public System::Object
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanan nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değerle eşit değildir, NaN dahil. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değerle eşit değildir, NaN dahil. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | Bir sertifika politikası alır. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Sertifikanın sertifika otoritesi iptal listesine karşı kontrol edilip edilmemesi gerektiğini gösteren bir değer alır. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | ServicePoint-class örnekleri tarafından izin verilen eşzamanlı bağlantıların azami sayısını alır. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | DNS çözümlemesinin geçerli kabul edildiği milisaniye cinsinden zaman aşımını alır. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | DNS çözümlemesinin uygulanabilir IP adresleri arasında dönüp dönmediğini gösteren bir değer alır. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | Geçerli örnek tarafından kullanılan şifreleme politikasını döndürür. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | ServicePoint-class örneklerinin 100-Continue davranışını kullanıp kullanmadığını gösteren bir değer alır. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | ServicePoint-class örneklerinin azami boşta kalma süresini alır. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | Geçerli örnek tarafından yönetilebilen ServicePoint-class örneklerinin azami sayısını alır. |
| static **bool** [get_ReusePort](./get_reuseport/)() | Çıkış bağlantı soketlerinin 'SO_REUSE_UNICASTPORT' seçeneğini kullanıp kullanmadığını gösteren bir değer alır. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | Geçerli örnek tarafından yönetilen ServicePoint-class örnekleri için kullanılan güvenlik protokolü tipini alır. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Sunucu sertifikasını doğrulamak için kullanılan geri çağırmayı alır. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | ServicePoint-class örneklerinin Nagle algoritmasını kullanıp kullanmadığını gösteren bir değer alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hashlemesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTip tarafından tanımlanan bir tür örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) denetleme nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını ilkleştirir. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans-karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) için dize ve nullptr durumuna özgü özelleştirme. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) için dize durumuna özgü özelleştirme. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | Bir sertifika politikası ayarlar. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | Sertifikanın sertifika otoritesi iptal listesine karşı kontrol edilip edilmemesi gerektiğini belirten bir değer ayarlar. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | ServicePoint-class örnekleri tarafından izin verilen eşzamanlı bağlantıların azami sayısını ayarlar. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | DNS çözümlemesinin geçerli kabul edildiği milisaniye cinsinden zaman aşımını ayarlar. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | DNS çözümlemesinin uygulanabilir IP adresleri arasında dönüp dönmediğini belirten bir değer ayarlar. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | ServicePoint-class örneklerinin 100-Continue davranışını kullanıp kullanmadığını belirten bir değer ayarlar. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | ServicePoint-class örneklerinin azami boşta kalma süresini ayarlar. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | Geçerli örnek tarafından yönetilebilen ServicePoint-class örneklerinin azami sayısını ayarlar. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | Çıkış bağlantı soketlerinin 'SO_REUSE_UNICASTPORT' seçeneğini kullanıp kullanmadığını belirten bir değer ayarlar. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | Geçerli örnek tarafından yönetilen ServicePoint-class örnekleri için kullanılan güvenlik protokolü tipini ayarlar. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | Sunucu sertifikasını doğrulamak için kullanılan geri çağırmayı ayarlar. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | ServicePoint-class örneklerinin Nagle algoritmasını kullanıp kullanmadığını belirten bir değer ayarlar. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | 'Keep-Alive' seçeneğinin etkin olup olmadığını belirten değeri ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir işaretçi (paylaşımlı değil) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin string’e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) denetleme nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | Kalıcı olmayan bağlantıların varsayılan sayısı. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | Kalıcı bağlantıların varsayılan sayısı. |
## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad Alanı [System::Net](../)
* Kütüphane [Aspose.Slides](../../)