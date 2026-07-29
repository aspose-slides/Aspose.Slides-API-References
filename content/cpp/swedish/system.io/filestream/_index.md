---
title: FileStream
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en filström som stödjer synkrona och asynkrona läs- och skrivoperationer. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Inslut alltid denna klass i en System::SmartPtr pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 287
url: /sv/system.io/filestream/
---
## FileStream klass


Representerar en filström som stödjer synkrona och asynkrona läs- och skrivrutiner. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körningsfel och/eller påståendefel. Inslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class FileStream : public System::IO::Stream
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron läsoperation. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron skrivoperation. |
| void [Close](./close/)() override | Stänger det aktuella [FileStream](./)-objektet. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopierar byte till den angivna strömmen. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopierar byte till den angivna strömmen med den angivna buffertstorleken. |
| void [Dispose](../stream/dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger strömmen. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Väntar tills den angivna asynkrona läsoperationen slutförs. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Avslutar en asynkron skrivoperation. Väntar tills den angivna asynkrona skrivoperationen slutförs. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Skapar en ny instans av klassen [FileStream](./) och initierar den med de angivna parametrarna. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, [FileOptions](../fileoptions/)) | Skapar en ny instans av klassen [FileStream](./) och initierar den med de angivna parametrarna. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, **bool**) | Skapar en ny instans av klassen [FileStream](./) och initierar den med de angivna parametrarna. |
|  [FileStream](./filestream/)(const [FileStream](./)\&) |  |
| void [Flush](./flush/)() override | Rensar den här strömmens buffertar och skriver all buffrad data till den underliggande filen. |
| void [Flush](./flush/)(**bool**) | Rensar den här strömmens buffertar och skriver all buffrad data till den underliggande filen. Synonym för metoden [Flush()](./flush/). |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Asynkront rensar alla buffertar för denna ström, får all bufferad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Asynkront rensar alla buffertar för denna ström, får all bufferad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar. |
| **bool** [get_CanRead](./get_canread/)() const override | Avgör om strömmen är läsbar. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Avgör om strömmen stödjer sökning. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Hämtar ett värde som avgör om den aktuella strömmen kan få tidsgräns. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Avgör om strömmen är skrivbar. |
| **int64_t** [get_Length](./get_length/)() const override | Returnerar strömmens längd i byte. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Returnerar filens namn som kapslas in av det aktuella [FileStream](./)-objektet. |
| **int64_t** [get_Position](./get_position/)() const override | Returnerar strömmens aktuella position. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Hämtar ett värde, i millisekunder, som avgör hur länge strömmen kommer att försöka läsa innan tidsgränsen nås. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Hämtar ett värde, i millisekunder, som avgör hur länge strömmen kommer att försöka skriva innan tidsgränsen nås. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är knuten till objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [FileStream](./)\& [operator=](./operator_equal/)(const [FileStream](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Läser det angivna antalet byte från strömmen och skriver dem till det angivna byteintervall. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Läser asynkront en sekvens av byte från den aktuella strömmen, flyttar positionen i strömmen med antalet lästa byte och övervakar avbokningsförfrågningar. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Läser asynkront en sekvens av byte från den aktuella strömmen, flyttar positionen i strömmen med antalet lästa byte och övervakar avbokningsförfrågningar. |
| **int32_t** [ReadByte](./readbyte/)() override | Läser en enda byte från strömmen och returnerar ett 32-bitars heltalsvärde som motsvarar värdet på den lästa byten. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Ställer in positionen för strömmen som representeras av det aktuella objektet. |
| void [set_Position](./set_position/)(**int64_t**) override | Spolar strömmen och sätter sedan strömmens position. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Ställer in ett värde som avgör om den aktuella strömmen kan få tidsgräns. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Ställer in ett värde, i millisekunder, som avgör hur länge strömmen kommer att försöka läsa innan tidsgränsen nås. |
| void [SetLength](./setlength/)(**int64_t**) override | Ställer in längden på strömmen som representeras av det aktuella objektet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde på delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräkningen. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräkningen. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av byte från den angivna bytearrayen till strömmen. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Skriver det angivna delintervallet av byte från det angivna byteintervall till strömmen. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Skriver asynkront en sekvens av byte till den aktuella strömmen, flyttar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbokningsförfrågningar. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Skriver asynkront en sekvens av byte till den aktuella strömmen, flyttar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbokningsförfrågningar. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Skriver det angivna osignerade 8-bitars heltalsvärdet till strömmen. |
|  [~FileStream](./~filestream/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | Standardvärde för antalet byte som buffras under läs- och skrivoperationer. |
| static [Null](../stream/null/) | En ström utan underliggande lagring. |

## Se också

* Klass [Stream](../stream/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)