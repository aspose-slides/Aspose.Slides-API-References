---
title: Stream
second_title: Aspose.Slides för C++ API-referens
description: "En bas-klass för en mängd olika strömimplementationer. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 365
url: /sv/system.io/stream/
---
## Stream-klass


En bas-klass för en mängd olika strömimplementationer. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körningsfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Stream : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron läsoperation. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron skrivoperation. |
| virtual void [Close](./close/)() | Stänger strömmen. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&) | Kopierar byte till den angivna strömmen. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&, **int32_t**) | Kopierar byte till den angivna strömmen med den angivna buffertstorleken. |
| void [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger strömmen. |
| virtual int [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Väntar tills den angivna asynkrona läsoperationen slutförs. |
| virtual void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Avslutar en asynkron skrivoperation. Väntar tills den angivna asynkrona skrivoperationen slutförs. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| virtual void [Flush](./flush/)() | Rensar strömmens buffertar och skriver all buffrad data till den underliggande lagringen. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbruksförfrågningar. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)() | Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbruksförfrågningar. |
| virtual **bool** [get_CanRead](./get_canread/)() const | Bestämmer om strömmen är läsbar. |
| virtual **bool** [get_CanSeek](./get_canseek/)() const | Bestämmer om strömmen stöder sökning. |
| virtual **bool** [get_CanTimeout](./get_cantimeout/)() const | Hämtar ett värde som avgör om den aktuella strömmen kan tidsas. |
| virtual **bool** [get_CanWrite](./get_canwrite/)() const | Bestämmer om strömmen är skrivbar. |
| virtual **int64_t** [get_Length](./get_length/)() const | Returnerar strömmens längd i byte. |
| virtual **int64_t** [get_Position](./get_position/)() const | Returnerar strömmens aktuella position. |
| virtual int [get_ReadTimeout](./get_readtimeout/)() const | Hämtar ett värde i millisekunder som bestämmer hur länge strömmen kommer att försöka läsa innan den tidsas. |
| virtual int [get_WriteTimeout](./get_writetimeout/)() const | Hämtar ett värde i millisekunder som bestämmer hur länge strömmen kommer att försöka skriva innan den tidsas. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog av C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog av C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog av C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-väktarobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog av C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| virtual **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen. |
| virtual **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen. |
| **int32_t** [Read](./read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen. |
| virtual **int32_t** [Read](./read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-spanen. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Läser asynkront en sekvens av byte från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa byte och övervakar avbruksförfrågningar. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Läser asynkront en sekvens av byte från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa byte och övervakar avbruksförfrågningar. |
| virtual int [ReadByte](./readbyte/)() | Läser en enda byte från strömmen och returnerar ett 32-bitars heltalsvärde som motsvarar värdet på den lästa byten. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| virtual **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) | Sätter positionen för strömmen som representeras av det aktuella objektet. |
| virtual void [set_Position](./set_position/)(**int64_t**) | Sätter strömmens position. |
| virtual void [set_ReadTimeout](./set_readtimeout/)(int) | Sätter ett värde som bestämmer om den aktuella strömmen kan tidsas. |
| virtual void [set_WriteTimeout](./set_writetimeout/)(int) | Sätter ett värde i millisekunder som bestämmer hur länge strömmen kommer att försöka läsa innan den tidsas. |
| virtual void [SetLength](./setlength/)(**int64_t**) | Sätter längden på strömmen som representeras av det aktuella objektet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'ta mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog av C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-väktarobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av byte från den angivna byte-arrayen till strömmen. |
| virtual void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av byte från den angivna byte-arrayen till strömmen. |
| void [Write](./write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av byte från den angivna byte-arrayen till strömmen. |
| virtual void [Write](./write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Skriver det angivna delintervallet av byte från den angivna byte-spanen till strömmen. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Skriver asynkront en sekvens av byte till den aktuella strömmen, förflyttar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbruksförfrågningar. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Skriver asynkront en sekvens av byte till den aktuella strömmen, förflyttar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbruksförfrågningar. |
| virtual void [WriteByte](./writebyte/)(**uint8_t**) | Skriver det angivna unsigned 8-bitars heltalsvärdet till strömmen. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Null](./null/) | En ström utan underliggande lagring. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till denna klass. |

## Se även

* Klass [IDisposable](../../system/idisposable/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)