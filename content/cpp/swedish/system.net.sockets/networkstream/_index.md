---
title: NetworkStream
second_title: Aspose.Slides för C++ API-referens
description: "Tillhandahåller den underliggande strömmen av data för nätverksåtkomst. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller assertionfel. Wrapa alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 40
url: /sv/system.net.sockets/networkstream/
---
## NetworkStream klass

Tillhandahåller den underliggande strömmen av data för nätverksåtkomst. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningsfel och/eller assertionfel. Wrapa alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class NetworkStream : public System::IO::Stream
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Initierar en asynkron läsoperation. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron läsoperation. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Initierar en asynkron skrivoperation. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron skrivoperation. |
| void [Close](./close/)(int) | Stänger den aktuella instansen efter den specificerade tiden har löpt ut. |
| virtual void [Close](../../system.io/stream/close/)() | Stänger strömmen. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Kopierar byte till den angivna strömmen. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Kopierar byte till den angivna strömmen, med angiven buffertstorlek. |
| void [Dispose](../../system.io/stream/dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger strömmen. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Väntar tills den specificerade asynkrona läsoperationen slutförs. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Väntar tills den specificerade asynkrona läsoperationen slutförs. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Avslutar en asynkron skrivoperation. Väntar tills den specificerade asynkrona skrivoperationen slutförs. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Avslutar en asynkron skrivoperation. Väntar tills den specificerade asynkrona skrivoperationen slutförs. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| void [Flush](./flush/)() override | Rensar denna ströms buffertar och skriver all buffrad data till den underliggande lagringen. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar. |
| **bool** [get_CanRead](./get_canread/)() const override | Bestämmer om strömmen är läsbar. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Bestämmer om strömmen stöder sökning. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Hämtar ett värde som bestämmer om den aktuella strömmen kan tidsgränsas. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Bestämmer om strömmen är skrivbar. |
| **bool** [get_DataAvailable](./get_dataavailable/)() const | Returnerar ett värde som indikerar om det finns tillgänglig data att läsa. |
| **int64_t** [get_Length](./get_length/)() const override | Returnerar strömmens längd i byte. |
| **int64_t** [get_Position](./get_position/)() const override | Returnerar strömmens aktuella position. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Hämtar ett värde i millisekunder som bestämmer hur länge strömmen ska försöka läsa innan den tidsgränsas. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\> [get_Socket](./get_socket/)() | Hämtar den underliggande [Socket](../socket/). |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Hämtar ett värde i millisekunder som bestämmer hur länge strömmen ska försöka skriva innan den tidsgränsas. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Gör det möjligt att hash:a anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropar direkt eller använder [LockContext](../../system/lockcontext/)-vaktsobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Gör det möjligt att klona anpassade typer. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>) | Skapar en ny instans. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, [System::IO::FileAccess](../../system.io/fileaccess/), **bool**) | Skapar en ny instans. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, **bool**) | Skapar en ny instans. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-spanen. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Läser asynkront en sekvens av byte från den aktuella strömmen, avancerar positionen i strömmen med antalet lästa byte och övervakar avbokningsförfrågningar. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Läser asynkront en sekvens av byte från den aktuella strömmen, avancerar positionen i strömmen med antalet lästa byte och övervakar avbokningsförfrågningar. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Läser en enda byte från strömmen och returnerar ett 32-bits heltalsvärde motsvarande den lästa byten. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensvis ett värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Anger positionen för den ström som representeras av det aktuella objektet. |
| void [set_Position](./set_position/)(**int64_t**) override | Anger strömmens position. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Anger ett värde som bestämmer om den aktuella strömmen kan tidsgränsas. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Anger ett värde som bestämmer om den aktuella strömmen kan tidsgränsas. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Anger ett värde i millisekunder som bestämmer hur länge strömmen ska försöka läsa innan den tidsgränsas. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Anger ett värde i millisekunder som bestämmer hur länge strömmen ska försöka läsa innan den tidsgränsas. |
| void [SetLength](./setlength/)(**int64_t**) override | Anger längden på den ström som representeras av det aktuella objektet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör ej anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör ej anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Gör det möjligt att konvertera anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropar direkt eller använder [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör ej anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör ej anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Skriver den angivna delintervallet av byte från den specificerade byte-arrayen till strömmen. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Skriver den angivna delintervallet av byte från den specificerade byte-arrayen till strömmen. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Skriver den angivna delintervallet av byte från den specificerade byte-arrayen till strömmen. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Skriver det angivna delintervallet av byte från den specificerade byte-spanen till strömmen. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Skriver asynkront en sekvens av byte till den aktuella strömmen, avancerar den aktuella positionen i strömmen med antalet skrivna byte och övervakar avbokningsförfrågningar. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Skriver asynkront en sekvens av byte till den aktuella strömmen, avancerar den aktuella positionen i strömmen med antalet skrivna byte och övervakar avbokningsförfrågningar. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Skriver det angivna osignerade 8-bitars heltalsvärdet till strömmen. |
| virtual  [~NetworkStream](./~networkstream/)() | Destruerar den aktuella instansen. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Null](../../system.io/stream/null/) | En ström utan underliggande lagring. |

## Se även

* Klass [Stream](../../system.io/stream/)
* Namnutrymme [System::Net::Sockets](../)
* Bibliotek [Aspose.Slides](../../)