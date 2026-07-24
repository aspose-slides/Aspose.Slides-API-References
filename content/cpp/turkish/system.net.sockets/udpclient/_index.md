---
title: UdpClient
second_title: Aspose.Slides için C++ API Referansı
description: "User Datagram Protocol (UDP) ağ hizmetleri sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tür bir örneği yığında veya new operatörü ile asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr göstergecisine sarın ve bu göstergeci fonksiyonlara argüman olarak geçirin."
type: docs
weight: 92
url: /tr/system.net.sockets/udpclient/
---
## UdpClient sınıfı

User Datagram Protocol (UDP) ağ hizmetleri sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu türden bir örnek yığını üzerinde veya new operatörü ile asla oluşturulmamalıdır, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıf her zaman bir [System::SmartPtr](../../system/smartptr/) göstergesine sarılmalı ve bu gösterge fonksiyonlara argüman olarak geçirilmelidir.

```cpp
class UdpClient : public System::IDisposable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [Close](./close/)() | UDP bağlantısını kapatır. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Belirtilen ana bilgisayarda belirtilen bağlantı noktasına bir bağlantı kurar. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Belirtilen adresteki ana bilgisayar ile belirtilen bağlantı noktasında bir bağlantı kurar. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Uzak bir uç noktaya bağlantı kurar. |
| void [Dispose](./dispose/)() override | [UdpClient](./) tarafından kullanılan yönetilen ve yönetilmeyen kaynakları serbest bırakır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) anlambilimi kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# stilinde kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# stilinde kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | Alttaki ağ soketini sağlamak için kullanılır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin bir analogudur. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının bir analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün bir analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruyucu nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin bir analogudur. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekten hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekten hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>\&) | Sunucu tarafından gönderilen bir datagramı döndürür. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Uzak uç noktadaki ana bilgisayara bir UDP datagramı gönderir. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [String](../../system/string/), **int32_t**) | Belirtilen uzak ana bilgisayarda belirtilen bağlantı noktasına bir UDP datagramı gönderir. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**) | Uzak bir ana bilgisayara UDP datagramı gönderir. |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | Alttaki ağ soketini sağlamak için kullanılır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf bir gösterge olarak ayarlar. Kapsayıcılardaki göstergelerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin bir analogudur. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
|  [UdpClient](./udpclient/)() | [UdpClient](./) sınıfının yeni bir örneğini başlatır. |
|  [UdpClient](./udpclient/)([AddressFamily](../addressfamily/)) | [UdpClient](./) sınıfının yeni bir örneğini başlatır. |
|  [UdpClient](./udpclient/)(**int32_t**) | [UdpClient](./) sınıfının yeni bir örneğini başlatır. |
|  [UdpClient](./udpclient/)(**int32_t**, [AddressFamily](../addressfamily/)) | [UdpClient](./) sınıfının yeni bir örneğini başlatır. |
|  [UdpClient](./udpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | [UdpClient](./) sınıfının yeni bir örneğini başlatır. param local EP UDP bağlantısını bağladığınız yerel uç nokta. |
|  [UdpClient](./udpclient/)([String](../../system/string/), **int32_t**) | [UdpClient](./) sınıfının yeni bir örneğini oluşturur ve belirtilen uzaktaki ana bilgisayara belirtilen bağlantı noktasında bağlanır. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruyucu nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IDisposable](../../system/idisposable/)
* Ad alanı [System::Net::Sockets](../)
* Kütüphane [Aspose.Slides](../../)