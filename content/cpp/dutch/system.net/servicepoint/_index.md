---
title: ServicePoint
second_title: Aspose.Slides voor C++ API-referentie
description: "Biedt beheer van HTTP-verbindingen. Objecten van deze klasse mogen alleen worden gealloceerd met System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 417
url: /nl/system.net/servicepoint/
---
## ServicePoint klasse


Provides HTTP connection management. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ServicePoint : public System::Object
```

## Methoden

| Method | Description |
| --- | --- |
| **bool** [CloseConnectionGroup](./closeconnectiongroup/)([String](../../system/string/)) | Sluit en verwijdert verbindingen die behoren tot de opgegeven verbindingsgroep. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | Retourneert de server-URI waarmee de huidige instantie verbinding maakt. |
| [BindIPEndPoint](../bindipendpoint/) [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | Haalt de delegate op die wordt gebruikt om lokale [IPEndPoint](../ipendpoint/) met de huidige instantie te associëren. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_Certificate](./get_certificate/)() | Retourneert een certificaat dat door de huidige instantie wordt gebruikt. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_ClientCertificate](./get_clientcertificate/)() | Retourneert het laatste clientcertificaat. |
| **int32_t** [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | Haalt een timeout in milliseconden op waarna actieve [ServicePoint](./) worden gesloten. |
| **int32_t** [get_ConnectionLimit](./get_connectionlimit/)() | Haalt het maximale aantal verbindingen op dat door de huidige instantie is toegestaan. |
| [String](../../system/string/) [get_ConnectionName](./get_connectionname/)() | Retourneert de verbindingsnaam. |
| **int32_t** [get_CurrentConnections](./get_currentconnections/)() | Retourneert het aantal geopende verbindingen. |
| **bool** [get_Expect100Continue](./get_expect100continue/)() | Haalt een waarde op die aangeeft of het 100-Continue-gedrag wordt gebruikt. |
| [DateTime](../../system/datetime/) [get_IdleSince](./get_idlesince/)() | Retourneert de datum en tijd van de nieuwste verbinding met een host. |
| **int32_t** [get_MaxIdleTime](./get_maxidletime/)() | Haalt een tijdsduur in milliseconden op waarna een idle-verbinding wordt gesloten. |
| virtual [Version](../../system/version/) [get_ProtocolVersion](./get_protocolversion/)() | Retourneert de HTTP-versie. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Haalt de grootte van de ontvangbuffer op. |
| **bool** [get_SupportsPipelining](./get_supportspipelining/)() | Retourneert een waarde die aangeeft of de huidige instantie pipeline-verbindingen ondersteunt. |
| **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Haalt een waarde op die aangeeft of het Nagle-algoritme wordt gebruikt door verbindingen die door de huidige instantie worden beheerd. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashgeneratie voor aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analogie van C# [System.Object.GetType()](../../system/object/gettype/)-oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analogie van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
| [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, initialiseert alleen een nieuw object en maakt kopieconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toekenningsoperator. Kopieert niets, initialiseert alleen een nieuw object en maakt kopieconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)([BindIPEndPoint](../bindipendpoint/)) | Stelt de delegate in die wordt gebruikt om lokale [IPEndPoint](../ipendpoint/) met de huidige instantie te associëren. |
| void [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(**int32_t**) | Stelt een timeout in milliseconden in waarna actieve [ServicePoint](./) worden gesloten. |
| void [set_ConnectionLimit](./set_connectionlimit/)(**int32_t**) | Stelt het maximale aantal verbindingen in dat door de huidige instantie is toegestaan. |
| void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Stelt een waarde in die aangeeft of het 100-Continue-gedrag wordt gebruikt. |
| void [set_MaxIdleTime](./set_maxidletime/)(**int32_t**) | Stelt een tijdsduur in milliseconden in waarna een idle-verbinding wordt gesloten. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Stelt de grootte van de ontvangbuffer in. |
| void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Stelt een waarde in die aangeeft of het Nagle-algoritme wordt gebruikt door verbindingen die door de huidige instantie worden beheerd. |
| void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Stelt de waarde in die aangeeft of de 'Keep-Alive'-optie is ingeschakeld. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Hiermee kunnen pointers in containers naar zwakke modus worden geschakeld. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Geeft alle interne datastructuren vrij. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Net](../)
* Bibliotheek [Aspose.Slides](../../)