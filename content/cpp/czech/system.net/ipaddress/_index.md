---
title: IPAddress
second_title: Aspose.Slides pro C++ API Reference
description: "Reprezentuje IP adresu. Objektů této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám během běhu a/nebo selháním aserce. Vždy obalte tuto třídu ukazatelem System::SmartPtr a použijte tento ukazatel k předávání jako argument funkcím."
type: docs
weight: 326
url: /cs/system.net/ipaddress/
---
## IPAddress třída

Represents the IP address. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IPAddress : public System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání floating-point ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání floating-point ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Vrací rodinu adres. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Vrací hodnotu, která označuje, zda je adresa IPv4 adresa a je mapována na IPv6 adresu. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Vrací hodnotu, která označuje, zda je adresa IPv6 link-local adresa. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | Vrací hodnotu, která označuje, zda je adresa globální IPv6 multicast adresa. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Vrací hodnotu, která označuje, zda je adresa IPv6 site-local adresa. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | Vrací hodnotu, která označuje, zda je adresa IPv6 Teredo adresa. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | Získává identifikátor rozsahu IPv6 adresy. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | Vrací pole bajtů IP adresy. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla odkazů spojenou s objektem. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Vrací ukazatel na implementaci. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | Převádí zadané pořadí bajtů hostitele na odpovídající pořadí bajtů sítě. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | Převádí zadané pořadí bajtů hostitele na odpovídající pořadí bajtů sítě. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | Převádí zadané pořadí bajtů hostitele na odpovídající pořadí bajtů sítě. |
| [IPAddress](./ipaddress/)(**int64_t**) | Vytváří novou instanci. |
| [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | Vytváří novou instanci. |
| [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Vytváří novou instanci. |
| [IPAddress](./ipaddress/)() | Vytváří novou instanci. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | Vrací hodnotu, která označuje, zda je zadaná adresa smyčkovou (loopback) adresou. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání příkazem C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | Mapuje adresu na IPv4 adresu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | Mapuje adresu na IPv6 adresu. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | Převádí zadané pořadí bajtů sítě na odpovídající pořadí bajtů hostitele. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | Převádí zadané pořadí bajtů sítě na odpovídající pořadí bajtů hostitele. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | Převádí zadané pořadí bajtů sítě na odpovídající pořadí bajtů hostitele. |
| [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny interní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Skutečně nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci kopií podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Skutečně nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci kopií podtříd. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | Převádí předaný řetězec na instanci třídy [IPAddress](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává objekt typu hodnoty s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený počitadlo odkazů o zadanou hodnotu. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | Nastavuje identifikátor rozsahu IPv6 adresy. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | Nastavuje ukazatel na implementaci. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného počitadla odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílené počitadlo odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílené počitadlo odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | Pokouší se převést předaný řetězec na instanci třídy [IPAddress](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí příkazem C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabé počitadlo odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabé počitadlo odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niči objekt. Uvolňuje všechny interní datové struktury. |

## Pole

| Pole | Popis |
| --- | --- |
| static [Any](./any/) | IPv4 adresa, která označuje, že server má poslouchat na všech síťových rozhraních. |
| static [Broadcast](./broadcast/) | IPv4 broadcast adresa. |
| static [IPv6Any](./ipv6any/) | IPv6 adresa, která označuje, že server má poslouchat na všech síťových rozhraních. |
| static [IPv6Loopback](./ipv6loopback/) | IPv6 loopback adresa. |
| static [IPv6None](./ipv6none/) | IPv6 adresa, která označuje, že server nesmí poslouchat žádné síťové rozhraní. |
| static [Loopback](./loopback/) | IPv4 loopback adresa. |
| static [None](./none/) | IPv4 adresa, která označuje, že server nesmí poslouchat žádné síťové rozhraní. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [ImplPtr](./implptr/) | Ukazatel na typ implementace. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Net](../)
* Knihovna [Aspose.Slides](../../)