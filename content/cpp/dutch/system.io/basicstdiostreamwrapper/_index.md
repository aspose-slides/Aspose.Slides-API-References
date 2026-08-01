---
title: BasicSTDIOStreamWrapper
second_title: Aspose.Slides voor C++ API-referentie
description: "Vertegenwoordigt een System.IO.Stream-achtige wrapper voor std::basic_iostream en zijn afgeleide objecten. Objecten van deze klasse mogen alleen worden gealloceerd met de functie System::MakeObject(). Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Wrap deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 1
url: /nl/system.io/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper klasse


Vertegenwoordigt een [System.IO.Stream](../stream/)-achtige wrapper voor std::basic_iostream en zijn afgeleide objecten. Objecten van deze klasse mogen alleen worden gealloceerd met de functie [System::MakeObject()](../../system/makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten oplevert. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
template<typename T,typename>class BasicSTDIOStreamWrapper : public System::IO::BasicSTDIStreamWrapper<T>,
                                                             public System::IO::BasicSTDOStreamWrapper<T>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(std::basic_iostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/), [STDIOStreamPositionPreference](../stdiostreampositionpreference/)) | Construeert een nieuw exemplaar van de [BasicSTDIOStreamWrapper](./). |
|  [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(const [BasicSTDIOStreamWrapper](./)\&) | Copy-constructor. Verwijderd. |
|  [BasicSTDIStreamWrapper](../basicstdistreamwrapper/basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Construeert een nieuw exemplaar van de [BasicSTDIStreamWrapper](../basicstdistreamwrapper/). |
|  [BasicSTDIStreamWrapper](../basicstdistreamwrapper/basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\&) | Copy-constructor. Verwijderd. |
|  [BasicSTDOStreamWrapper](../basicstdostreamwrapper/basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Construeert een nieuw exemplaar van de [BasicSTDOStreamWrapper](../basicstdostreamwrapper/). |
|  [BasicSTDOStreamWrapper](../basicstdostreamwrapper/basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\&) | Copy-constructor. Verwijderd. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Start een asynchrone leesoperatie. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Start een asynchrone schrijfbewerking. |
| virtual void [Close](../stream/close/)() | Sluit de stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopieert bytes naar de opgegeven stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopieert bytes naar de opgegeven stream, met de opgegeven buffergrootte. |
| void [Dispose](../stream/dispose/)() override | Release al de resources die door het huidige object worden gebruikt en sluit de stream. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Wacht tot de opgegeven asynchrone leesoperatie voltooid is. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Beëindigt een asynchrone schrijfoperatie. Wacht tot de opgegeven asynchrone schrijfoperatie voltooid is. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl floating-point vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl floating-point vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| void [Flush](./flush/)() override | Leegt de buffers van deze stream en schrijft alle gebufferde data naar de onderliggende opslag. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Maakt asynchroon alle buffers voor deze stream leeg, zorgt ervoor dat alle gebufferde data naar het onderliggende apparaat wordt geschreven, en bewaakt annuleringsverzoeken. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Maakt asynchroon alle buffers voor deze stream leeg, zorgt ervoor dat alle gebufferde data naar het onderliggende apparaat wordt geschreven, en bewaakt annuleringsverzoeken. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Bepaalt of de stream zoeken ondersteunt. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Krijgt een waarde die bepaalt of de huidige stream kan time-out. |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | Bepaalt of de stream schrijven ondersteunt. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Retourneert de lengte van de stream. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Retourneert de huidige positie van de stream. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Krijgt een waarde, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat een time-out optreedt. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Krijgt een waarde, in milliseconden, die bepaalt hoe lang de stream zal proberen te schrijven voordat een time-out optreedt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Krijgt de referentieteller-datastructuur die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Stelt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Krijgt het werkelijke type van het object. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, eigenlijk, initialiseert alleen nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [BasicSTDIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIOStreamWrapper](./)\&) | Copy-assignement-operator. Verwijderd. |
| [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\& [operator=](../basicstdistreamwrapper/operator_equal/)(const [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\&) | Copy-assignement-operator. Verwijderd. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Copy-assignement-operator. Verwijderd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignement-operator. Kopieert niets, eigenlijk, initialiseert alleen nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\& [operator=](../basicstdostreamwrapper/operator_equal/)(const [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\&) | Copy-assignement-operator. Verwijderd. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Als de wrap-modus binair is, leest het het opgegeven aantal bytes uit de stream, anders leest het het opgegeven aantal tekens en converteert ze naar type **uint8_t**. Schrijft het resultaat van het lezen naar de opgegeven byte-array. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-span. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Leest asynchroon een reeks bytes van de huidige stream, verplaatst de positie in de stream met het aantal gelezen bytes, en bewaakt annuleringsverzoeken. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Leest asynchroon een reeks bytes van de huidige stream, verplaatst de positie in de stream met het aantal gelezen bytes, en bewaakt annuleringsverzoeken. |
| int [ReadByte](./readbyte/)() override | Als de wrap-modus binair is, leest het één byte uit de laatst gedecodeerde tekenopslag, anders leest het één teken uit de stream en converteert het naar type **uint8_t**. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | RTTI-informatie. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Stelt de positie van de stream in die wordt weergegeven door het huidige object. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Stelt de positie van de stream in. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Stelt een waarde in die bepaalt of de huidige stream kan time-out. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Stelt een waarde in, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat een time-out optreedt. |
| void [SetLength](./setlength/)(**int64_t**) override | Stelt de lengte van de stream in die wordt weergegeven door het huidige object. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Krijgt de huidige waarde van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Copy-constructor. Verwijderd. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Stelt converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Als de wrap-modus binair is, schrijft het naar de stream het gespecificeerde deel van bytes uit de opgegeven byte-array, anders converteert het het gespecificeerde deel van bytes uit de opgegeven byte-array naar type char_type en schrijft vervolgens het resultaat naar de stream. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Schrijft het gespecificeerde deel van bytes uit de opgegeven byte-array naar de stream. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Schrijft het gespecificeerde deel van bytes uit de opgegeven byte-array naar de stream. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Schrijft het gespecificeerde deel van bytes uit de opgegeven byte-span naar de stream. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en bewaakt annuleringsverzoeken. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en bewaakt annuleringsverzoeken. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Als de wrap-modus binair is, schrijft het naar de stream de opgegeven unsigned 8-bit geheel getalwaarde, anders converteert het naar type char_type en schrijft vervolgens het resultaat naar de stream. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Bevrijdt alle interne datastructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Null](../stream/null/) | Een stream zonder onderliggende opslag. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [BaseIType](./baseitype/) |  |
| [BaseOType](./baseotype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## Zie ook

* Klasse [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)
* Klasse [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)
* Namespace [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)