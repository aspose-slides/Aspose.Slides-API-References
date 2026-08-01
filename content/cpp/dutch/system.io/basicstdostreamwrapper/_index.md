---
title: BasicSTDOStreamWrapper
second_title: Aspose.Slides voor C++ API-referentie
description: "Vertegenwoordigt een System.IO.Stream-achtige wrapper voor std::basic_ostream en de afgeleide objecten. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject()-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 27
url: /nl/system.io/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper klasse

Stelt een [System.IO.Stream](../stream/)-like wrapper voor std::basic_ostream en zijn afgeleide objecten. Objecten van deze klasse moeten alleen worden gealloceerd met behulp van [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit resulteert in runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
template<typename T,typename>class BasicSTDOStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Construeert een nieuw exemplaar van de [BasicSTDOStreamWrapper](./). |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](./)\&) | Kopieerconstructor. Verwijderd. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Start een asynchrone leesbewerking. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Start een asynchrone schrijfbewerking. |
| virtual void [Close](../stream/close/)() | Sluit de stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopieert bytes naar de opgegeven stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopieert bytes naar de opgegeven stream, met behulp van de opgegeven buffergrootte. |
| void [Dispose](../stream/dispose/)() override | Geeft alle bronnen die door het huidige object worden gebruikt vrij en sluit de stream. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Wacht tot de opgegeven asynchrone leesbewerking voltooid is. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Beëindigt een asynchrone schrijfbewerking. Wacht tot de opgegeven asynchrone schrijfbewerking voltooid is. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevende-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevende-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| void [Flush](./flush/)() override | Leegt de buffers van deze stream en schrijft alle gebufferde gegevens naar de onderliggende opslag. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Leegt asynchroon alle buffers voor deze stream, zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven, en houdt annuleringsverzoeken in de gaten. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Leegt asynchroon alle buffers voor deze stream, zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven, en houdt annuleringsverzoeken in de gaten. |
| **bool** [get_CanRead](../stdiostreamwrapperbase/get_canread/)() const override | Bepaalt of de stream lezen ondersteunt. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Bepaalt of de stream zoeken ondersteunt. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Haalt een waarde op die bepaalt of de huidige stream een time-out kan hebben. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Geeft de lengte van de stream terug. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Geeft de huidige positie van de stream terug. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Haalt een waarde in milliseconden op die bepaalt hoe lang de stream zal proberen te lezen voordat er een time-out optreedt. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Haalt een waarde in milliseconden op die bepaalt hoe lang de stream zal proberen te schrijven voordat er een time-out optreedt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object gekoppeld is. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Equivalent van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Equivalent van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Equivalent van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Equivalent van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [BasicSTDOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDOStreamWrapper](./)\&) | Kopieer-toewijzingsoperator. Verwijderd. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Kopieer-toewijzingsoperator. Verwijderd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Als de wrappermodus binair is, leest het het opgegeven aantal bytes van de stream, anders leest het het opgegeven aantal tekens en converteert ze naar type **uint8_t**. Schrijft het resultaat van het lezen naar de opgegeven byte-array. Niet ondersteund! |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-span. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Leest asynchroon een reeks bytes van de huidige stream, verplaatst de positie in de stream met het aantal gelezen bytes, en houdt annuleringsverzoeken in de gaten. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Leest asynchroon een reeks bytes van de huidige stream, verplaatst de positie in de stream met het aantal gelezen bytes, en houdt annuleringsverzoeken in de gaten. |
| int [ReadByte](./readbyte/)() override | Als de wrappermodus binair is, leest het één byte uit de opslag van het laatst gedecodeerde teken, anders leest het één teken van de stream en converteert het naar type **uint8_t**. Niet ondersteund! |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt per referentie een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | RTTI-informatie. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Stelt de positie van de stream in die wordt vertegenwoordigd door het huidige object. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Stelt de positie van de stream in. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Stelt een waarde in die bepaalt of de huidige stream een time-out kan hebben. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Stelt een waarde in, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat er een time-out optreedt. |
| void [SetLength](./setlength/)(**int64_t**) override | Stelt de lengte van de stream in die door het huidige object wordt vertegenwoordigd. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers te wisselen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Kopieerconstructor. Verwijderd. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Equivalent van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert het C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Als de wrappermodus binair is, schrijft het naar de stream het opgegeven subbereik van bytes uit de opgegeven byte-array, anders converteert het het opgegeven subbereik van bytes uit de opgegeven byte-array naar het type char_type en schrijft vervolgens het resultaat naar de stream. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de stream. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de stream. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-span naar de stream. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en houdt annuleringsverzoeken in de gaten. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en houdt annuleringsverzoeken in de gaten. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Als de wrappermodus binair is, schrijft het naar de stream de opgegeven unsigned 8-bit integer-waarde, anders converteert het naar het type char_type en schrijft vervolgens het resultaat naar de stream. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Null](../stream/null/) | Een stream zonder onderliggende opslag. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## Zie ook

* Klasse [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* Naamruimte [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)