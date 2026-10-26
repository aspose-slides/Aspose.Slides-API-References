---
title: IPAddress
second_title: Aspose.Slides için C++ API Referansı
description: "IP adresini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tür bir örnek, yığına (stack) veya operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 326
url: /tr/system.net/ipaddress/
---
## IPAddress sınıfı


Represents the IP address. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IPAddress : public System::Object
```

## Yöntemler

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değerle eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C#-stilinde kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değerle eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C#-stilinde kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Adres ailesini döndürür. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Adresin bir IPv4 adresi olduğunu ve bir IPv6 adresine eşlendiğini gösteren bir değer döndürür. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Adresin bir IPv6 link-local adresi olduğunu gösteren bir değer döndürür. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | Adresin küresel bir IPv6 multicast adresi olduğunu gösteren bir değer döndürür. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Adresin bir IPv6 site-local adresi olduğunu gösteren bir değer döndürür. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | Adresin bir IPv6 Teredo adresi olduğunu gösteren bir değer döndürür. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | IPv6 adresinin kapsam tanımlayıcısını alır. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | IP adresinin bayt dizisini döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Uygulamaya bir gösterici döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | Belirtilen ana bilgisayar bayt sırasını karşılık gelen ağ bayt sırasına dönüştürür. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | Belirtilen ana bilgisayar bayt sırasını karşılık gelen ağ bayt sırasına dönüştürür. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | Belirtilen ana bilgisayar bayt sırasını karşılık gelen ağ bayt sırasına dönüştürür. |
|  [IPAddress](./ipaddress/)(**int64_t**) | Yeni bir örnek oluşturur. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | Yeni bir örnek oluşturur. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Yeni bir örnek oluşturur. |
|  [IPAddress](./ipaddress/)() | Yeni bir örnek oluşturur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipte bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | Belirtilen adresin bir loopback adresi olup olmadığını gösteren bir değer döndürür. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini gerçekleştirir. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | Adresi IPv4 adresine eşler. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | Adresi IPv6 adresine eşler. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | Belirtilen ağ bayt sırasını karşılık gelen ana bilgisayar bayt sırasına dönüştürür. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | Belirtilen ağ bayt sırasını karşılık gelen ana bilgisayar bayt sırasına dönüştürür. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | Belirtilen ağ bayt sırasını karşılık gelen ana bilgisayar bayt sırasına dönüştürür. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | Verilen dizeyi [IPAddress](./) sınıfının bir örneğine dönüştürür. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesnesi ile nullptr'ı referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Dize ve nullptr durumları için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Dize durumları için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | IPv6 adresinin kapsam tanımlayıcısını ayarlar. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | Uygulama göstericisini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici olarak ayarlar (paylaşımlı değil). Kapsayıcılardaki göstericileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | Verilen dizeyi [IPAddress](./) sınıfının bir örneğine dönüştürmeye çalışır. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını gerçekleştirir. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
## Alanlar

| Field | Description |
| --- | --- |
| static [Any](./any/) | Sunucunun tüm ağ arabirimlerini dinlemesi gerektiğini gösteren IPv4 adresi. |
| static [Broadcast](./broadcast/) | IPv4 yayın adresi. |
| static [IPv6Any](./ipv6any/) | Sunucunun tüm ağ arabirimlerini dinlemesi gerektiğini gösteren IPv6 adresi. |
| static [IPv6Loopback](./ipv6loopback/) | IPv6 döngü adresi. |
| static [IPv6None](./ipv6none/) | Sunucunun hiçbir ağ arabirimini dinlememesi gerektiğini gösteren IPv6 adresi. |
| static [Loopback](./loopback/) | IPv4 döngü adresi. |
| static [None](./none/) | Sunucunun hiçbir ağ arabirimini dinlememesi gerektiğini gösteren IPv4 adresi. |
## Typedef'lar

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | Uygulama tipine bir gösterici. |
## İlgili

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Net](../)
* Kütüphane [Aspose.Slides](../../)