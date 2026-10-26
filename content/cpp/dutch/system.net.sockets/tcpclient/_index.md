---
title: TcpClient
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een client voor de TCP-netwerkservices voor. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten zal veroorzaken. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 66
url: /nl/system.net.sockets/tcpclient/
---
## TcpClient klasse

Stelt een client voor de TCP-netwerkservices voor. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class TcpClient : public System::IDisposable
```

## Methoden

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initieert een asynchrone verbindingsoperatie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initieert een asynchrone verbindingsoperatie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initieert een asynchrone verbindingsoperatie. |
| void [Close](./close/)() | Sluit de verbinding en verwijdert de huidige instantie. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Stelt een verbinding tot stand met de opgegeven externe host. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Stelt een verbinding tot stand met de opgegeven externe host. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Stelt een verbinding tot stand met de opgegeven externe host. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | Stelt een verbinding tot stand met de opgegeven externe host. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Doet niets. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Wacht totdat de opgegeven asynchrone verbindingsoperatie voltooid is. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **int32_t** [get_Available](./get_available/)() | Geeft het aantal bytes terug die ontvangen zijn en klaar om gelezen te worden. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | Haalt de socket op. |
| **bool** [get_Connected](./get_connected/)() | Geeft een waarde terug die aangeeft of de socket is verbonden met de externe host. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Haalt een waarde op die aangeeft of de huidige instantie slechts één client toelaat een poort te gebruiken. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | Haalt een waarde op die aangeeft of de socket het sluiten zal uitstellen in een poging alle in afwachting zijnde gegevens te versturen. |
| **bool** [get_NoDelay](./get_nodelay/)() | Haalt een waarde op die aangeeft of de huidige instantie het Nagle-algoritme gebruikt. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Haalt de grootte op van de buffer die wordt gebruikt voor het ontvangen van gegevens. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | Haalt een waarde op die aangeeft na hoeveel tijd het ontvangen van gegevens een time-out krijgt. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | Haalt de grootte op van de buffer die wordt gebruikt voor het verzenden van gegevens. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | Haalt een waarde op die aangeeft na hoeveel tijd het verzenden van gegevens een time-out krijgt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkStream](../networkstream/)\> [GetStream](./getstream/)() | Geeft de stream terug die wordt gebruikt voor het verzenden en ontvangen van gegevens. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, eigenlijk, initialiseert slechts een nieuw object en maakt het mogelijk subclass-kopieconstructie. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, eigenlijk, initialiseert slechts een nieuw object en maakt het mogelijk subclass-kopieconstructie. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | Stelt de socket in. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | Stelt een waarde in die aangeeft of de huidige instantie slechts één client toelaat een poort te gebruiken. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | Stelt een waarde in die aangeeft of de socket het sluiten zal uitstellen in een poging alle wachtende gegevens te verzenden. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | Stelt een waarde in die aangeeft of de huidige instantie het Nagle-algoritme gebruikt. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Stelt de grootte in van de buffer die wordt gebruikt voor het ontvangen van gegevens. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | Stelt een waarde in die aangeeft na hoeveel tijd het ontvangen van gegevens een time-out krijgt. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | Stelt de grootte in van de buffer die wordt gebruikt voor het verzenden van gegevens. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | Stelt een waarde in die aangeeft na hoeveel tijd het verzenden van gegevens een time-out krijgt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th template-argument in op een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en geeft de gedeelde referentieteller terug. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
|  [TcpClient](./tcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Construeert een nieuwe instantie. |
|  [TcpClient](./tcpclient/)() | Construeert een nieuwe instantie. |
|  [TcpClient](./tcpclient/)([AddressFamily](../addressfamily/)) | Construeert een nieuwe instantie. |
|  [TcpClient](./tcpclient/)([String](../../system/string/), **int32_t**) | Construeert een nieuwe instantie. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het lock()-statement van C# voor ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |
| virtual  [~TcpClient](./~tcpclient/)() | Destructeert de huidige instantie. |

## Zie ook

* Klasse [IDisposable](../../system/idisposable/)
* Naamruimte [System::Net::Sockets](../)
* Bibliotheek [Aspose.Slides](../../)