---
title: AuthenticatedStream
second_title: Aspose.Slides för C++ API-referens
description: "Innehåller metoderna för att skicka autentiseringsuppgifter över en ström. Objekt av den här klassen bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningstidfel och/eller påståendefel. Omslut alltid den här klassen i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 1
url: /sv/system.net.security/authenticatedstream/
---

## AuthenticatedStream klass

Innehåller metoder för att skicka autentiseringsuppgifter över en ström. Objekt av den här klassen bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningstidfel och/eller påståendefel. Omslut alltid den här klassen i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## Metoder

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron läsoperation. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron skrivoperation. |
| virtual void [Close](../../system.io/stream/close/)() | Stänger strömmen. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Kopierar bytes till den angivna strömmen. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Kopierar bytes till den angivna strömmen med den angivna buffertstorleken. |
| void [Dispose](../../system.io/stream/dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger strömmen. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Väntar tills den angivna asynkrona läsoperationen slutförs. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Avslutar en asynkron skrivoperation. Väntar tills den angivna asynkrona skrivoperationen slutförs. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Efterliknar C#-liknande flyttalsjämförelse där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Efterliknar C#-liknande flyttalsjämförelse där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual void [Flush](../../system.io/stream/flush/)() | Rensar denna ströms buffertar och skriver all buffrad data till den underliggande lagringen. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynkront rensar alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbrottsförfrågningar. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Asynkront rensar alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbrottsförfrågningar. |
| virtual **bool** [get_CanRead](../../system.io/stream/get_canread/)() const | Bestämmer om strömmen är läsbar. |
| virtual **bool** [get_CanSeek](../../system.io/stream/get_canseek/)() const | Bestämmer om strömmen stödjer sökning. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | Hämtar ett värde som bestämmer om den aktuella strömmen kan tidsgränsas. |
| virtual **bool** [get_CanWrite](../../system.io/stream/get_canwrite/)() const | Bestämmer om strömmen är skrivbar. |
| virtual **bool** [get_IsAuthenticated](./get_isauthenticated/)() const | Returnerar ett värde som indikerar om autentisering har passerats framgångsrikt. |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() const | Returnerar ett värde som indikerar om data som skickas med denna ström är krypterad. |
| virtual **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | Returnerar ett värde som indikerar om en server och en klient är autentiserade. |
| virtual **bool** [get_IsServer](./get_isserver/)() const | Returnerar ett värde som indikerar om den lokala sidan av anslutningen är servern. |
| virtual **bool** [get_IsSigned](./get_issigned/)() const | Returnerar ett värde som indikerar om data som skickas med denna ström är signerad. |
| **bool** [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | Returnerar den ström som används av de aktuella klassinstanserna för att skicka och ta emot data. |
| virtual **int64_t** [get_Length](../../system.io/stream/get_length/)() const | Returnerar strömmens längd i byte. |
| virtual **int64_t** [get_Position](../../system.io/stream/get_position/)() const | Returnerar den aktuella positionen för strömmen. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | Hämtar ett värde, i millisekunder, som bestämmer hur länge strömmen kommer att försöka läsa innan tidsgränsen nås. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | Hämtar ett värde, i millisekunder, som bestämmer hur länge strömmen kommer att försöka skriva innan tidsgränsen nås. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknare-datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingen

 data, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-spanen. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynkront läser en sekvens av byte från den aktuella strömmen, avancerar positionen i strömmen med antalet lästa byte och övervakar avbrottsförfrågningar. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynkront läser en sekvens av byte från den aktuella strömmen, avancerar positionen i strömmen med antalet lästa byte och övervakar avbrottsförfrågningar. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Läser en enda byte från strömmen och returnerar ett 32-bitars heltalsvärde som motsvarar värdet på den lästa byten. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt ett värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| virtual **int64_t** [Seek](../../system.io/stream/seek/)(**int64_t**, [SeekOrigin](../../system.io/seekorigin/)) | Ställer in positionen för strömmen som representeras av det aktuella objektet. |
| virtual void [set_Position](../../system.io/stream/set_position/)(**int64_t**) | Ställer in strömmens position. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Ställer in ett värde som bestämmer om den aktuella strömmen kan tidsgränsas. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Ställer in ett värde, i millisekunder, som bestämmer hur länge strömmen kommer att försöka läsa innan tidsgränsen nås. |
| virtual void [SetLength](../../system.io/stream/setlength/)(**int64_t**) | Ställer in längden på strömmen som representeras av det aktuella objektet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n:te mallargumentet till en svag pekare (istället för delad). Möjliggör att byta pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör att konvertera anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual void [Write](../../system.io/stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| virtual void [Write](../../system.io/stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Skriver det angivna delintervallet av byte från den angivna byte-spanen till strömmen. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynkront skriver en sekvens av byte till den aktuella strömmen, avancerar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbrottsförfrågningar. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynkront skriver en sekvens av byte till den aktuella strömmen, avancerar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbrottsförfrågningar. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Skriver det angivna unsigned 8-bitars heltalsvärdet till strömmen. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Fält

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | En ström utan underliggande lagring. |

## Se även

* Klass [Stream](../../system.io/stream/)
* Namnrymd [System::Net::Security](../)
* Bibliotek [Aspose.Slides](../../)