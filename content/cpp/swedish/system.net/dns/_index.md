---
title: Dns
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller metoder för att arbeta med DNS.
type: docs
weight: 105
url: /sv/system.net/dns/
---
## Dns klass

Tillhandahåller metoder för att arbeta med DNS.

```cpp
class Dns : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostAddresses](./begingethostaddresses/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med den angivna strängen som innehåller ett värdnamn eller en IP-adress. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostByName](./begingethostbyname/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med det angivna värdnamnet. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostEntry](./begingethostentry/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med den angivna strängen som innehåller ett värdnamn eller en IP-adress. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostEntry](./begingethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med den angivna IP-adressen. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginResolve](./beginresolve/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Initierar en asynkron operation för att skapa en ny IPHostEntry-klassinstans med det angivna värdnamnet. |
|  [Dns](./dns/)() | Den borttagna standardkonstruktorn. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>\> [EndGetHostAddresses](./endgethostaddresses/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry-klassinstans är klar. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndGetHostByName](./endgethostbyname/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry-klassinstans är klar. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndGetHostEntry](./endgethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry-klassinstans är klar. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndResolve](./endresolve/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry-klassinstans är klar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalssjämförelse där två NaN-värden anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalssjämförelse där två NaN-värden anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är kopplad till objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>\> [GetHostAddresses](./gethostaddresses/)([String](../../system/string/)) | Returnerar en samling IP-adresser för det angivna värdnamnet eller IP-adressen. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByAddress](./gethostbyaddress/)([String](../../system/string/)) | Skapar en ny IPHostEntry-klassinstans med den angivna strängrepresentationen av en IP-adress. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByAddress](./gethostbyaddress/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>) | Skapar en ny IPHostEntry-klassinstans med den angivna IP-adressen. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByName](./gethostbyname/)([String](../../system/string/)) | Skapar en ny IPHostEntry-klassinstans med det angivna värdnamnet. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostEntry](./gethostentry/)([String](../../system/string/)) | Skapar en ny IPHostEntry-klassinstans med den angivna strängen som innehåller ett värdnamn eller en IP-adress. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostEntry](./gethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>) | Skapar en ny IPHostEntry-klassinstans med den angivna IP-adressen. |
| static [String](../../system/string/) [GetHostName](./gethostname/)() | Returnerar maskinens lokala värdnamn. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropas direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt ett värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [Resolve](./resolve/)([String](../../system/string/)) | Skapar en ny IPHostEntry-klassinstans med det angivna värdnamnet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Möjliggör byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropas direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Net](../)
* Bibliotek [Aspose.Slides](../../)