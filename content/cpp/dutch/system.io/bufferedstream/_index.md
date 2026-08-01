---
title: BufferedStream
second_title: Aspose.Slides voor C++ API-referentie
description: "Voegt een bufferlaag toe bovenop een andere stream. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Pak deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze aan functies als argument door te geven."
type: docs
weight: 118
url: /nl/system.io/bufferedstream/
---
## BufferedStream klasse

Voegt een bufferlaag toe bovenop een andere stream. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Pak deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze aan functies als argument door te geven.

```cpp
class BufferedStream : public System::IO::Stream
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Start een asynchrone leesoperatie. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Start een asynchrone schrijfoperatie. |
|  [BufferedStream](./bufferedstream/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Construeert een [BufferedStream](./) object dat de opgegeven stream omsluit en een buffer van 4096 bytes gebruikt. |
|  [BufferedStream](./bufferedstream/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, int) | Construeert een [BufferedStream](./) object dat de opgegeven stream omsluit en een buffer van de opgegeven grootte gebruikt. |
| virtual void [Close](../stream/close/)() | Sluit de stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopieert bytes naar de opgegeven stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopieert bytes naar de opgegeven stream, met gebruik van de opgegeven buffer-grootte. |
| void [Dispose](../stream/dispose/)() override | Geeft alle bronnen vrij die door het huidige object worden gebruikt en sluit de stream. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Wacht tot de opgegeven asynchrone leesbewerking voltooid is. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Beëindigt een asynchrone schrijfbewerking. Wacht tot de opgegeven asynchrone schrijfbewerking voltooid is. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert zwevend-punt vergelijking in C#-stijl waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert zwevend-punt vergelijking in C#-stijl waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| void [Flush](./flush/)() override | Schrijft de inhoud van de buffer naar de onderliggende stream. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Verwijdert asynchroon alle buffers voor deze stream, zorgt ervoor dat alle gebufferde data naar het onderliggende apparaat wordt geschreven, en houdt annuleringsverzoeken in de gaten. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Verwijdert asynchroon alle buffers voor deze stream, zorgt ervoor dat alle gebufferde data naar het onderliggende apparaat wordt geschreven, en houdt annuleringsverzoeken in de gaten. |
| **bool** [get_CanRead](./get_canread/)() const override | Bepaalt of de stream leesbaar is. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Bepaalt of de stream zoeken ondersteunt. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Haalt een waarde op die bepaalt of de huidige stream een time-out kan hebben. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Bepaalt of de stream beschrijfbaar is. |
| **int64_t** [get_Length](./get_length/)() const override | Retourneert de lengte van de stream. |
| **int64_t** [get_Position](./get_position/)() const override | Retourneert de huidige positie van de stream. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Haalt een waarde op, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat er een time-out optreedt. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Haalt een waarde op, in milliseconden, die bepaalt hoe lang de stream zal proberen te schrijven voordat er een time-out optreedt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van de C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement locken. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) bewaakobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert geen gegevens, initialiseert gewoon een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignatie-operator. Kopieert geen gegevens, initialiseert gewoon een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Leest het opgegeven aantal bytes van de onderliggende stream en schrijft ze naar de opgegeven byte-array. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Leest het opgegeven aantal bytes van de onderliggende stream en schrijft ze naar de opgegeven byte-array. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-array. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Leest het opgegeven aantal bytes van de stream en schrijft ze naar de opgegeven byte-span. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchroon lezen van een reeks bytes van de huidige stream, de positie in de stream verplaatsen met het aantal gelezen bytes, en annuleringsverzoeken in de gaten houden. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchroon lezen van een reeks bytes van de huidige stream, de positie in de stream verplaatsen met het aantal gelezen bytes, en annuleringsverzoeken in de gaten houden. |
| int [ReadByte](./readbyte/)() override | Leest een enkel byte van de onderliggende stream en retourneert een 32-bit geheel getal dat overeenkomt met de waarde van het gelezen byte. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Stelt de positie van de stream in die wordt gerepresenteerd door het huidige object. |
| void [set_Position](./set_position/)(**int64_t**) override | Leegt de buffer naar de onderliggende stream en stelt daarna de positie van de stream in. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Stelt een waarde in die bepaalt of de huidige stream een time-out kan hebben. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Stelt een waarde in, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat er een time-out optreedt. |
| void [SetLength](./setlength/)(**int64_t**) override | Stelt de lengte van de stream in die wordt gerepresenteerd door het huidige object. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van shared). Stelt het mogelijk om pointers in containers te wisselen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) bewaakobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de onderliggende stream. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de onderliggende stream. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de stream. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-span naar de stream. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchroon schrijven van een reeks bytes naar de huidige stream, de huidige positie in deze stream verplaatsen met het aantal geschreven bytes, en annuleringsverzoeken in de gaten houden. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchroon schrijven van een reeks bytes naar de huidige stream, de huidige positie in deze stream verplaatsen met het aantal geschreven bytes, en annuleringsverzoeken in de gaten houden. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Schrijft de opgegeven ongetekende 8-bit gehele waarde naar de onderliggende stream. |
| virtual  [~BufferedStream](./~bufferedstream/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Null](../stream/null/) | Een stream zonder onderliggende opslag. |

## Zie ook

* Klasse [Stream](../stream/)
* Namespace [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)