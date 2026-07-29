---
title: TcpClient
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en klient för TCP-nätverkstjänster. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 66
url: /sv/system.net.sockets/tcpclient/
---
## TcpClient-klass

Representerar en klient för TCP-nätverkstjänster. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class TcpClient : public System::IDisposable
```

## Metoder

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initierar en asynkron anslutningsoperation. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initierar en asynkron anslutningsoperation. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initierar en asynkron anslutningsoperation. |
| void [Close](./close/)() | Stänger anslutningen och frigör den aktuella instansen. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Skapar en anslutning till den angivna fjärrvärden. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Skapar en anslutning till den angivna fjärrvärden. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Skapar en anslutning till den angivna fjärrvärden. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | Skapar en anslutning till den angivna fjärrvärden. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Gör ingenting. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Väntar tills den specificerade asynkrona anslutningsoperationen är klar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| **int32_t** [get_Available](./get_available/)() | Returnerar antalet byte som mottagits och är klara att läsas. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | Hämtar socketen. |
| **bool** [get_Connected](./get_connected/)() | Returnerar ett värde som indikerar om socketen är ansluten till fjärrvärden. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Hämtar ett värde som indikerar om den aktuella instansen tillåter endast en klient att använda en port. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | Hämtar ett värde som indikerar om socketen fördröjer stängning i ett försök att skicka all kvarvarande data. |
| **bool** [get_NoDelay](./get_nodelay/)() | Hämtar ett värde som indikerar om den aktuella instansen använder Nagle-algoritmen. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Hämtar storleken på bufferten som används för att ta emot data. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | Hämtar ett värde som indikerar en tidsperiod efter vilken datamottagning får tidsgräns. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | Hämtar storleken på bufferten som används för att skicka data. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | Hämtar ett värde som indikerar en tidsperiod efter vilken datasändning får tidsgräns. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkStream](../networkstream/)\> [GetStream](./getstream/)() | Returnerar strömmen som används för att skicka och ta emot data. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingen

t, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför ett värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | Ställer in socketen. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | Ställer in ett värde som indikerar om den aktuella instansen tillåter endast en klient att använda en port. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | Ställer in ett värde som indikerar om socketen fördröjer stängning i ett försök att skicka all kvarvarande data. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | Ställer in ett värde som indikerar om den aktuella instansen använder Nagle-algoritmen. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Ställer in storleken på bufferten som används för att ta emot data. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | Ställer in ett värde som indikerar en tidsperiod efter vilken datamottagning får tidsgräns. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | Ställer in storleken på bufferten som används för att skicka data. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | Ställer in ett värde som indikerar en tidsperiod efter vilken datasändning får tidsgräns. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
|  [TcpClient](./tcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Konstruktar en ny instans. |
|  [TcpClient](./tcpclient/)() | Konstruktar en ny instans. |
|  [TcpClient](./tcpclient/)([AddressFamily](../addressfamily/)) | Konstruktar en ny instans. |
|  [TcpClient](./tcpclient/)([String](../../system/string/), **int32_t**) | Konstruktar en ny instans. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
| virtual  [~TcpClient](./~tcpclient/)() | Destruerar den aktuella instansen. |

## Se också

* Klass [IDisposable](../../system/idisposable/)
* Namnrymd [System::Net::Sockets](../)
* Bibliotek [Aspose.Slides](../../)