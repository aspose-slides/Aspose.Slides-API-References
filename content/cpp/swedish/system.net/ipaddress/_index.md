---
title: IPAddress
second_title: Aspose.Slides för C++ API-referens
description: "Representerar IP-adressen. Objekt av denna klass bör bara allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 326
url: /sv/system.net/ipaddress/
---
## IPAddress-klass


Representerar IP-adressen. Objekt av denna klass bör bara allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class IPAddress : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiterar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiterar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Returnerar adressfamiljen. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Returnerar ett värde som indikerar om adressen är en IPv4-adress och är mappad till en IPv6-adress. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Returnerar ett värde som indikerar om adressen är en IPv6-link-local-adress. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | Returnerar ett värde som indikerar om adressen är en global IPv6-multicast-adress. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Returnerar ett värde som indikerar om adressen är en IPv6-site-local-adress. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | Returnerar ett värde som indikerar om adressen är en IPv6-Teredo-adress. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | Hämtar räckviddsidentifieraren för IPv6-adressen. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | Returnerar en byte-array av IP-adressen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Returnerar en pekare till implementationen. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska objektetypen. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | Konverterar den angivna värdadressordningen till motsvarande nätverksordning. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | Konverterar den angivna värdadressordningen till motsvarande nätverksordning. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | Konverterar den angivna värdadressordningen till motsvarande nätverksordning. |
|  [IPAddress](./ipaddress/)(**int64_t**) | Skapar en ny instans. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | Skapar en ny instans. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Skapar en ny instans. |
|  [IPAddress](./ipaddress/)() | Skapar en ny instans. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | Returnerar ett värde som indikerar om den angivna adressen är en loopback-adress. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satser. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | Mappar adressen till IPv4-adressen. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | Mappar adressen till IPv6-adressen. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | Konverterar den angivna nätverksordningen till motsvarande värdadressordning. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | Konverterar den angivna nätverksordningen till motsvarande värdadressordning. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | Konverterar den angivna nätverksordningen till motsvarande värdadressordning. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | Konverterar en given sträng till en instans av klassen [IPAddress](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referenräknare med angivet värde. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | Sätter räckviddsidentifieraren för IPv6-adressen. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | Sätter en pekare till implementationen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | Försöker konvertera en given sträng till en instans av klassen [IPAddress](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning enligt C# lock()-satser. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Any](./any/) | IPv4-adressen som indikerar om servern ska lyssna på alla nätverksgränssnitt. |
| static [Broadcast](./broadcast/) | IPv4-broadcastadressen. |
| static [IPv6Any](./ipv6any/) | IPv6-adressen som indikerar om servern ska lyssna på alla nätverksgränssnitt. |
| static [IPv6Loopback](./ipv6loopback/) | IPv6-loopback-adressen. |
| static [IPv6None](./ipv6none/) | IPv6-adressen som indikerar att servern inte ska lyssna på något nätverksgränssnitt. |
| static [Loopback](./loopback/) | IPv4-loopback-adressen. |
| static [None](./none/) | IPv4-adressen som indikerar att servern inte ska lyssna på något nätverksgränssnitt. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [ImplPtr](./implptr/) | En pekare till implementationstypen. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Net](../)
* Bibliotek [Aspose.Slides](../../)