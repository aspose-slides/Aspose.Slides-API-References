---
title: ServicePointManager
second_title: Aspose.Slides voor C++ API-referentie
description: "Beheert de levenscyclusfasen (aanmaken, onderhouden en verwijderen) van ServicePoint-klasse-instanties. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject()-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wrap deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 430
url: /nl/system.net/servicepointmanager/
---
## ServicePointManager klasse

Beheert de levenscyclusfasen (aanmaken, onderhouden, en verwijderen) van de [ServicePoint](../servicepoint/) klasse-instanties. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze aan functies te doorgeven als argument.

```cpp
class ServicePointManager : public System::Object
```

## Methoden

| Method | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | Verkrijgt een certificaatbeleid. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Verkrijgt een waarde die aangeeft of het certificaat moet worden gecontroleerd tegen de intrekkingslijst van de certificaatautoriteit. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Verkrijgt het maximale aantal gelijktijdige verbindingen dat is toegestaan voor de ServicePoint-klasse-instanties. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Verkrijgt een time-out in milliseconden waarvoor een DNS-resolutie als geldig wordt beschouwd. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Verkrijgt een waarde die aangeeft of een DNS-resolutie roteert tussen de toepasselijke IP-adressen. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | Retourneert het encryptiebeleid dat door de huidige instantie wordt gebruikt. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | Verkrijgt een waarde die aangeeft of de ServicePoint-klasse-instanties het 100-Continue-gedrag gebruiken. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Verkrijgt de maximale idle-tijd van de ServicePoint-klasse-instanties. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | Verkrijgt het maximale aantal ServicePoint-klasse-instanties dat door de huidige instantie kan worden beheerd. |
| static **bool** [get_ReusePort](./get_reuseport/)() | Verkrijgt een waarde die aangeeft of de sockets van uitgaande verbindingen de 'SO_REUSE_UNICASTPORT'-optie gebruiken. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | Verkrijgt het type beveiligingsprotocol dat door de ServicePoint-klasse-instanties wordt gebruikt die door de huidige instantie worden beheerd. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Verkrijgt de callback die wordt gebruikt om een servercertificaat te valideren. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Verkrijgt een waarde die aangeeft of de ServicePoint-klasse-instanties het Nagle-algoritme gebruiken. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haal de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Schakelt hashen van aangepaste objecten in. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haal het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie vertegenwoordigt van het type dat door targetType wordt beschreven. Analog van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Schakelt klonen van aangepaste types in. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopiërende constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en schakelt het kopiëren van subklassen in. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en schakelt het kopiëren van subklassen in. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt per referentie een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | Stelt een certificaatbeleid in. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | Stelt een waarde in die aangeeft of het certificaat moet worden gecontroleerd tegen de intrekkingslijst van de certificaatautoriteit. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | Stelt het maximale aantal gelijktijdige verbindingen in dat is toegestaan voor de ServicePoint-klasse-instanties. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | Stelt een time-out in milliseconden in waarvoor een DNS-resolutie als geldig wordt beschouwd. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | Stelt een waarde in die aangeeft of een DNS-resolutie roteert tussen de toepasselijke IP-adressen. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | Stelt een waarde in die aangeeft of de ServicePoint-klasse-instanties het 100-Continue-gedrag gebruiken. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | Stelt de maximale idle-tijd van de ServicePoint-klasse-instanties in. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | Stelt het maximale aantal ServicePoint-klasse-instanties in dat door de huidige instantie kan worden beheerd. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | Stelt een waarde in die aangeeft of de sockets van uitgaande verbindingen de 'SO_REUSE_UNICASTPORT'-optie gebruiken. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | Stelt het type beveiligingsprotocol in dat door de ServicePoint-klasse-instanties wordt gebruikt die door de huidige instantie worden beheerd. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | Stelt de callback in die wordt gebruikt om een servercertificaat te valideren. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | Stelt een waarde in die aangeeft of de ServicePoint-klasse-instanties het Nagle-algoritme gebruiken. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | Stelt de waarde in die aangeeft of de 'Keep-Alive'-optie is ingeschakeld. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haal de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Schakelt omzetten van aangepaste objecten naar string in. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het lock()-statement van C# voor ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Velden

| Field | Beschrijving |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | Het standaard aantal niet-persistente verbindingen. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | Het standaard aantal persistente verbindingen. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Net](../)
* Bibliotheek [Aspose.Slides](../../)