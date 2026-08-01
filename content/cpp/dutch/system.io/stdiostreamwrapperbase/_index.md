---
title: STDIOStreamWrapperBase
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een basisklasse voor System.IO.Stream-achtige wrappers voor. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 352
url: /nl/system.io/stdiostreamwrapperbase/
---
## STDIOStreamWrapperBase klasse


Represents a base class for [System.IO.Stream](../stream/)-like wrappers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T,typename>class STDIOStreamWrapperBase : public System::IO::Stream
```

## Methodes

| Method | Beschrijving |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Start een asynchrone leesbewerking. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Start een asynchrone schrijfbewerking. |
| virtual void [Close](../stream/close/)() | Sluit de stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopieert bytes naar de opgegeven stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopieert bytes naar de opgegeven stream, met de opgegeven buffergrootte. |
| void [Dispose](../stream/dispose/)() override | Vrijgeeft alle resources die door het huidige object worden gebruikt en sluit de stream. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Wacht tot de opgegeven asynchrone leesbewerking is voltooid. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Beëindigt een asynchrone schrijfbewerking. Wacht tot de opgegeven asynchrone schrijfbewerking is voltooid. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met de C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevende-komma-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevende-komma-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual void [Flush](../stream/flush/)() | Leegt de buffers van deze stream en schrijft alle gebufferde gegevens naar de onderliggende opslag. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Leegt asynchroon alle buffers voor deze stream, zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven, en bewaakt annuleringsverzoeken. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Leegt asynchroon alle buffers voor deze stream, zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven, en bewaakt annuleringsverzoeken. |
| **bool** [get_CanRead](./get_canread/)() const override | Bepaalt of de stream lezen ondersteunt. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Bepaalt of de stream zoeken ondersteunt. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Haalt een waarde op die bepaalt of de huidige stream een time-out kan hebben. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Bepaalt of de stream schrijven ondersteunt. |
| **int64_t** [get_Length](./get_length/)() const override | Retourneert de lengte van de stream. |
| **int64_t** [get_Position](./get_position/)() const override | Retourneert de huidige positie van de stream. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Haalt een waarde op, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat er een time-out optreedt. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Haalt een waarde op, in milliseconden, die bepaalt hoe lang de stream zal proberen te schrijven voordat er een time-out optreedt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashberekening van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type dat door targetType wordt beschreven, vertegenwoordigt. Analoge van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [STDIOStreamWrapperBase](./)\& [operator=](./operator_equal/)(const [STDIOStreamWrapperBase](./)\&) | Copy-toewijzingsoperator. Verwijderd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| virtual **int32_t** [Read](../stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array. |
| virtual **int32_t** [Read](../stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-span. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Leest asynchroon een reeks bytes van de huidige stream, verplaatst de positie binnen de stream met het aantal gelezen bytes, en bewaakt annuleringsverzoeken. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Leest asynchroon een reeks bytes van de huidige stream, verplaatst de positie binnen de stream met het aantal gelezen bytes, en bewaakt annuleringsverzoeken. |
| virtual int [ReadByte](../stream/readbyte/)() | Leest één byte van de stream en retourneert een 32-bit geheel getal dat gelijk is aan de waarde van de gelezen byte. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](./thistype/), [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/)) | RTTI-informatie. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Stelt de positie van de stream in die door het huidige object wordt vertegenwoordigd. |
| void [set_Position](./set_position/)(**int64_t**) override | Stelt de positie van de stream in. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Stelt een waarde in die bepaalt of de huidige stream een time-out kan hebben. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Stelt een waarde in, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat er een time-out optreedt. |
| virtual void [SetLength](../stream/setlength/)(**int64_t**) | Stelt de lengte in van de stream die door het huidige object wordt vertegenwoordigd. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
|  [STDIOStreamWrapperBase](./stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](./)\&) | Copy-constructor. Verwijderd. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het lock()-statement van C# voor ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual void [Write](../stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schrijft het opgegeven subbereik van bytes van de opgegeven byte-array naar de stream. |
| virtual void [Write](../stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schrijft het opgegeven subbereik van bytes van de opgegeven byte-array naar de stream. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Schrijft het opgegeven subbereik van bytes van de opgegeven byte-array naar de stream. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Schrijft het opgegeven subbereik van bytes van de opgegeven byte-span naar de stream. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie binnen deze stream met het aantal geschreven bytes, en bewaakt annuleringsverzoeken. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie binnen deze stream met het aantal geschreven bytes, en bewaakt annuleringsverzoeken. |
| virtual void [WriteByte](../stream/writebyte/)(**uint8_t**) | Schrijft de opgegeven onondertekende 8-bit integerwaarde naar de stream. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijmaakt alle interne gegevensstructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Null](../stream/null/) | Een stream zonder onderliggende opslag. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Zie ook

* Klasse [Stream](../stream/)
* Naamruimte [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)