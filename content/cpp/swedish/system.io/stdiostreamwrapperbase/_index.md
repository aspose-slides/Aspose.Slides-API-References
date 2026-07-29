---
title: STDIOStreamWrapperBase
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en basklass för System.IO.Stream-liknande omslag. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertionsfel. Omslut alltid den här klassen i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 352
url: /sv/system.io/stdiostreamwrapperbase/
---
## STDIOStreamWrapperBase klass

Representerar en basklass för [System.IO.Stream](../stream/)-liknande omslag. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename T,typename>class STDIOStreamWrapperBase : public System::IO::Stream
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron läsoperation. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron skrivoperation. |
| virtual void [Close](../stream/close/)() | Stänger strömmen. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopierar bytes till den angivna strömmen. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopierar bytes till den angivna strömmen med angiven buffertstorlek. |
| void [Dispose](../stream/dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger strömmen. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Väntar tills den angivna asynkrona läsoperationen är klar. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Avslutar en asynkron skrivoperation. Väntar tills den angivna asynkrona skrivoperationen är klar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual void [Flush](../stream/flush/)() | Rensar den här strömmens buffertar och skriver all buffrad data till det underliggande lagret. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Rensar asynkront alla buffertar för den här strömmen, får all buffrad data att skrivas till den underliggande enheten och övervakar avbrytningsförfrågningar. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Rensar asynkront alla buffertar för den här strömmen, får all buffrad data att skrivas till den underliggande enheten och övervakar avbrytningsförfrågningar. |
| **bool** [get_CanRead](./get_canread/)() const override | Avgör om strömmen stöder läsning. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Avgör om strömmen stöder sökning. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Hämtar ett värde som bestämmer om den aktuella strömmen kan timea ut. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Avgör om strömmen stöder skrivning. |
| **int64_t** [get_Length](./get_length/)() const override | Returnerar strömmens längd. |
| **int64_t** [get_Position](./get_position/)() const override | Returnerar strömmens aktuella position. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Hämtar ett värde i millisekunder som bestämmer hur länge strömmen kommer att försöka läsa innan den timear ut. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Hämtar ett värde i millisekunder som bestämmer hur länge strömmen kommer att försöka skriva innan den timear ut. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-uttalandets låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion för underklasser. |
| [STDIOStreamWrapperBase](./)\& [operator=](./operator_equal/)(const [STDIOStreamWrapperBase](./)\&) | Kopieringstilldelningsoperator. Borttagen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion för underklasser. |
| virtual **int32_t** [Read](../stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Läser det angivna antalet bytes från strömmen och skriver dem till den angivna byte-arrayen. |
| virtual **int32_t** [Read](../stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Läser det angivna antalet bytes från strömmen och skriver dem till den angivna byte-arrayen. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Läser det angivna antalet bytes från strömmen och skriver dem till den angivna byte-arrayen. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Läser det angivna antalet bytes från strömmen och skriver dem till den angivna byte-spannen. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Läser asynkront en sekvens av bytes från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa bytes och övervakar avbrytningsförfrågningar. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Läser asynkront en sekvens av bytes från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa bytes och övervakar avbrytningsförfrågningar. |
| virtual int [ReadByte](../stream/readbyte/)() | Läser en enda byte från strömmen och returnerar ett 32-bitars heltalsvärde som motsvarar värdet på den lästa byten. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypsobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](./thistype/), [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/)) | RTTI-information. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Ställer in positionen för den ström som representeras av det aktuella objektet. |
| void [set_Position](./set_position/)(**int64_t**) override | Ställer in strömmens position. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Ställer in ett värde som bestämmer om den aktuella strömmen kan timea ut. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Ställer in ett värde i millisekunder som bestämmer hur länge strömmen kommer att försöka läsa innan den timear ut. |
| virtual void [SetLength](../stream/setlength/)(**int64_t**) | Ställer in längden på den ström som representeras av det aktuella objektet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te templateargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
|  [STDIOStreamWrapperBase](./stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](./)\&) | Kopieringskonstruktor. Borttagen. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-uttalandets upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual void [Write](../stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av bytes från den angivna byte-arrayen till strömmen. |
| virtual void [Write](../stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av bytes från den angivna byte-arrayen till strömmen. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av bytes från den angivna byte-arrayen till strömmen. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Skriver det angivna delintervallet av bytes från den angivna byte-spannen till strömmen. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Skriver asynkront en sekvens av bytes till den aktuella strömmen, förflyttar den aktuella positionen i strömmen med antalet skrivna bytes och övervakar avbrytningsförfrågningar. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Skriver asynkront en sekvens av bytes till den aktuella strömmen, förflyttar den aktuella positionen i strömmen med antalet skrivna bytes och övervakar avbrytningsförfrågningar. |
| virtual void [WriteByte](../stream/writebyte/)(**uint8_t**) | Skriver det angivna osignerade 8-bitars heltalsvärdet till strömmen. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Null](../stream/null/) | En ström utan underliggande lagring. |
## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |
## Se även

* Klass [Stream](../stream/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)