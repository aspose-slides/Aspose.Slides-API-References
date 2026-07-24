---
title: TcpClient
second_title: Aspose.Slides için C++ API Referansı
description: "TCP ağ hizmetleri için bir istemciyi temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu türden bir örnek asla yığına (stack) ya da operator new kullanılarak oluşturulmamalıdır, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına (assertion faults) yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın."
type: docs
weight: 66
url: /tr/system.net.sockets/tcpclient/
---
## TcpClient sınıfı


TCP ağ hizmetleri için bir istemciyi temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu türden bir örnek asla yığına (stack) ya da `operator new` kullanılarak oluşturulmamalıdır, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına (assertion faults) yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class TcpClient : public System::IDisposable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Asenkron bir bağlanma işlemini başlatır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Asenkron bir bağlanma işlemini başlatır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Asenkron bir bağlanma işlemini başlatır. |
| void [Close](./close/)() | Bağlantıyı kapatır ve mevcut örneği yok eder. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Belirtilen uzak ana bilgisayara bir bağlantı kurar. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Belirtilen uzak ana bilgisayara bir bağlantı kurar. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Belirtilen uzak ana bilgisayara bir bağlantı kurar. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | Belirtilen uzak ana bilgisayara bir bağlantı kurar. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Hiçbir şey yapmaz. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Belirtilen asenkron bağlanma işlemi tamamlanana kadar bekler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğine göre karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989’a göre NaN’in hiçbir değere eşit olmaması gerektiği halde, iki NaN’i eşit kabul eden C#-stili kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989’a göre NaN’in hiçbir değere eşit olmaması gerektiği halde, iki NaN’i eşit kabul eden C#-stili kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **int32_t** [get_Available](./get_available/)() | Alınan ve okunmaya hazır olan bayt sayısını döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | Socket'i alır. |
| **bool** [get_Connected](./get_connected/)() | Socket'in uzak ana bilgisayara bağlanıp bağlanmadığını gösteren bir değer döndürür. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Mevcut örneğin bir porta yalnızca bir istemcinin kullanımına izin verip vermediğini gösteren bir değer alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | Socket'in tüm bekleyen veriyi göndermeye çalışırken kapanmayı geciktirip geciktirmeyeceğini gösteren bir değer alır. |
| **bool** [get_NoDelay](./get_nodelay/)() | Mevcut örneğin Nagle algoritmasını kullanıp kullanmadığını gösteren bir değer alır. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Veri alımı için kullanılan tamponun boyutunu alır. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | Veri alımının zaman aşımına uğrayacağı süreyi gösteren bir değer alır. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | Veri gönderimi için kullanılan tamponun boyutunu alır. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | Veri gönderiminin zaman aşımına uğrayacağı süreyi gösteren bir değer alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayaç veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hashlenmesini sağlar. |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkStream](../networkstream/)\> [GetStream](./getstream/)() | Veri gönderimi ve alımı için kullanılan akışı döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTip tarafından tanımlanan türe ait bir örnek olup olmadığını kontrol eder. C# ‘is’ operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# `lock()` ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeri. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve türev sınıfların kopya oluşturulmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve türev sınıfların kopya oluşturulmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi `nullptr` ile referans-karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve `nullptr` durumunda [Object::ReferenceEquals](../../system/object/referenceequals/) için özel implemantasyon. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Stringler için [Object::ReferenceEquals](../../system/object/referenceequals/) özel implemantasyonu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | Socket'i ayarlar. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | Mevcut örneğin bir porta yalnızca bir istemcinin kullanımına izin verip vermediğini belirten bir değer ayarlar. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | Socket'in tüm bekleyen veriyi göndermeye çalışırken kapanmayı geciktirip geciktirmeyeceğini belirten bir değer ayarlar. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | Mevcut örneğin Nagle algoritmasını kullanıp kullanmadığını belirten bir değer ayarlar. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Veri alımı için kullanılan tamponun boyutunu ayarlar. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | Veri alımının zaman aşımına uğrayacağı süreyi belirten bir değer ayarlar. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | Veri gönderimi için kullanılan tamponun boyutunu ayarlar. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | Veri gönderiminin zaman aşımına uğrayacağı süreyi belirten bir değer ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n’inci şablon argümanını zayıf işaretçi (shared yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [TcpClient](./tcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Yeni bir örnek oluşturur. |
|  [TcpClient](./tcpclient/)() | Yeni bir örnek oluşturur. |
|  [TcpClient](./tcpclient/)([AddressFamily](../addressfamily/)) | Yeni bir örnek oluşturur. |
|  [TcpClient](./tcpclient/)([String](../../system/string/), **int32_t**) | Yeni bir örnek oluşturur. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özel nesnelerin string’e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# `typeof([System.Object](../../system/object/))` yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# `lock()` ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |
| virtual  [~TcpClient](./~tcpclient/)() | Mevcut örneği imha eder. |

## Ayrıca Bakınız

* Sınıf [IDisposable](../../system/idisposable/)
* İsim Alanı [System::Net::Sockets](../)
* Kütüphane [Aspose.Slides](../../)