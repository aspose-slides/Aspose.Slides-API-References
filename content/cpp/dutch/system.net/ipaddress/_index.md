---
title: IPAddress
second_title: Aspose.Slides voor C++ API Referentie
description: "Representeert het IP-adres. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze aan functies als argument door te geven."
type: docs
weight: 326
url: /nl/system.net/ipaddress/
---
## IPAddress klasse

Representeert het IP-adres. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze aan functies als argument door te geven.

```cpp
class IPAddress : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevende-kommapunten vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevende-kommapunten vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Geeft de adresfamilie terug. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Geeft een waarde terug die aangeeft of het adres een IPv4-adres is en gemapt is naar een IPv6-adres. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Geeft een waarde terug die aangeeft of het adres een IPv6-link-local adres is. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | Geeft een waarde terug die aangeeft of het adres een globaal IPv6-multicast-adres is. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Geeft een waarde terug die aangeeft of het adres een IPv6-site-local adres is. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | Geeft een waarde terug die aangeeft of het adres een IPv6-Teredo-adres is. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | Haalt de scope-identificatie van het IPv6-adres op. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | Geeft een byte-array van het IP-adres terug. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Geeft een pointer naar de implementatie terug. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | Converteert de opgegeven host-byte-order naar de overeenkomstige netwerk-byte-order. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | Converteert de opgegeven host-byte-order naar de overeenkomstige netwerk-byte-order. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | Converteert de opgegeven host-byte-order naar de overeenkomstige netwerk-byte-order. |
|  [IPAddress](./ipaddress/)(**int64_t**) | Construeert een nieuwe instantie. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | Construeert een nieuwe instantie. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Construeert een nieuwe instantie. |
|  [IPAddress](./ipaddress/)() | Construeert een nieuwe instantie. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type dat wordt beschreven door targetType. Analog van C# 'is' operator. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | Geeft een waarde terug die aangeeft of het opgegeven adres een loopback-adres is. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) wachtoject. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | Mappt het adres naar het IPv4-adres. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | Mappt het adres naar het IPv6-adres. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste typen mogelijk. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | Converteert de opgegeven netwerk-byte-order naar de overeenkomstige host-byte-order. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | Converteert de opgegeven netwerk-byte-order naar de overeenkomstige host-byte-order. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | Converteert de opgegeven netwerk-byte-order naar de overeenkomstige host-byte-order. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | Converteert een meegegeven string naar een instantie van de [IPAddress](./) klasse. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt per referentie een value-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | Stelt de scope-identificatie van het IPv6-adres in. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | Stelt een pointer naar de implementatie in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | Probeert een meegegeven string naar een instantie van de [IPAddress](./) klasse te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) wachtoject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Any](./any/) | Het IPv4-adres dat aangeeft of de server op alle netwerkinterfaces moet luisteren. |
| static [Broadcast](./broadcast/) | Het IPv4-broadcast-adres. |
| static [IPv6Any](./ipv6any/) | Het IPv6-adres dat aangeeft of de server op alle netwerkinterfaces moet luisteren. |
| static [IPv6Loopback](./ipv6loopback/) | Het IPv6-loopback-adres. |
| static [IPv6None](./ipv6none/) | Het IPv6-adres dat aangeeft of de server op geen enkele netwerkinterface mag luisteren. |
| static [Loopback](./loopback/) | Het IPv4-loopback-adres. |
| static [None](./none/) | Het IPv4-adres dat aangeeft of de server op geen enkele netwerkinterface mag luisteren. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [ImplPtr](./implptr/) | Een pointer naar het implementatietype. |

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [System::Net](../)
* Bibliotheek [Aspose.Slides](../../)