---
title: BasicSTDIStreamWrapper
second_title: "Aspose.Slides för C++ API-referens"
description: "Representerar ett System.IO.Stream-liknande omslag för std::basic_istream och dess avledda objekt. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 14
url: /sv/system.io/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper klass


Representerar en [System.IO.Stream](../stream/)-liknande omslag för std::basic_istream och dess avledda objekt. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
template<typename T,typename>class BasicSTDIStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Metoder

| Method | Description |
| --- | --- |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Skapar en ny instans av [BasicSTDIStreamWrapper](./). |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](./)\&) | Kopieringskonstruktor. Borttagen. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron läsoperation. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron skrivoperation. |
| virtual void [Close](../stream/close/)() | Stänger strömmen. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopierar byte till den angivna strömmen. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopierar byte till den angivna strömmen, med den angivna buffertstorleken. |
| void [Dispose](../stream/dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger strömmen. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Väntar tills den angivna asynkrona läsoperationen är klar. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Avslutar en asynkron skrivoperation. Väntar tills den angivna asynkrona skrivoperationen är klar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| void [Flush](./flush/)() override | Rensar denna ströms buffertar och skriver all buffrad data till underliggande lagring. Stöds inte! |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Avgör om strömmen stöder sökning. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Hämtar ett värde som avgör om den aktuella strömmen kan timeout. |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | Avgör om strömmen stöder skrivning. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Returnerar strömmens längd. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Returnerar strömmens aktuella position. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Hämtar ett värde i millisekunder som avgör hur länge strömmen kommer att försöka läsa innan timeout. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Hämtar ett värde i millisekunder som avgör hur länge strömmen kommer att försöka skriva innan timeout. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av egna objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsen låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av egna typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [BasicSTDIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIStreamWrapper](./)\&) | Kopieringsoperator för tilldelning. Borttagen. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Kopieringsoperator för tilldelning. Borttagen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Om omslagsläget är binärt läser den angivna antalet byte från strömmen, annars läser den angivna antalet tecken och konverterar dem till **uint8_t**-typ. Skriver läsresultatet till den angivna bytearrayen. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-spannet. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Läser asynkront en sekvens av byte från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa byte och övervakar avbokningsförfrågningar. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Läser asynkront en sekvens av byte från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa byte och övervakar avbokningsförfrågningar. |
| int [ReadByte](./readbyte/)() override | Om omslagsläget är binärt läser den en enda byte från den senast avkodade teckenslagringen, annars läser den ett enda tecken från strömmen och konverterar det till **uint8_t**-typ. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | RTTI-information. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Ställer in positionen för strömmen som representeras av det aktuella objektet. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Ställer in strömmens position. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Ställer in ett värde som avgör om den aktuella strömmen kan timeout. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Ställer in ett värde i millisekunder som avgör hur länge strömmen kommer att försöka läsa innan timeout. |
| void [SetLength](./setlength/)(**int64_t**) override | Ställer in längden på strömmen som representeras av det aktuella objektet. Stöds inte! |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Kopieringskonstruktor. Borttagen. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av egna objekt till string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsen upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Om omslagsläget är binärt skriver den till strömmen det angivna delintervallet av byte från den angivna bytearrayen, annars konverterar den det angivna delintervallet av byte från den angivna bytearrayen till char_type-typ och skriver sedan resultatet till strömmen. Stöds inte! |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Skriver det angivna delintervallet av byte från det angivna byte-spannet till strömmen. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Skriver asynkront en sekvens av byte till den aktuella strömmen, förflyttar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbokningsförfrågningar. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Skriver asynkront en sekvens av byte till den aktuella strömmen, förflyttar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbokningsförfrågningar. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Om omslagsläget är binärt skriver den till strömmen det angivna osignerade 8-bitars heltalsvärdet, annars konverterar den det till char_type-typ och skriver sedan resultatet till strömmen. Stöds inte! |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Fält

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | En ström utan underliggande lagring. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## Se också

* Klass [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)