---
title: MemoryStream
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een stream voor die van geheugen leest en ernaar schrijft. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een exemplaar van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik die pointer om deze als argument aan functies door te geven."
type: docs
weight: 326
url: /nl/system.io/memorystream/
---
## MemoryStream klasse

Stelt een stream voor die van geheugen leest en ernaar schrijft. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een exemplaar van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik die pointer om deze als argument aan functies door te geven.

```cpp
class MemoryStream : public System::IO::Stream
```

## Methoden

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Start een asynchrone leesbewerking. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Start een asynchrone schrijfbewerking. |
| void [Close](./close/)() override | Sluit de stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopieert bytes naar de opgegeven stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopieert bytes naar de opgegeven stream, met de opgegeven buffer-grootte. |
| void [Dispose](../stream/dispose/)() override | Vrijgeeft alle resources die door het huidige object worden gebruikt en sluit de stream. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Wacht tot de opgegeven asynchrone leesbewerking voltooid is. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Beëindigt een asynchrone schrijfbewerking. Wacht tot de opgegeven asynchrone schrijfbewerking voltooid is. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl floating-point-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl floating-point-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| void [Flush](./flush/)() override | Doet niets. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Leegt asynchroon alle buffers van deze stream, zorgt ervoor dat alle gebufferde data naar het onderliggende apparaat wordt geschreven, en bewaakt annuleringsverzoeken. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Leegt asynchroon alle buffers van deze stream, zorgt ervoor dat alle gebufferde data naar het onderliggende apparaat wordt geschreven, en bewaakt annuleringsverzoeken. |
| **bool** [get_CanRead](./get_canread/)() const override | Bepaalt of de stream leesbaar is. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Bepaalt of de stream zoeken ondersteunt. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Haalt een waarde op die bepaalt of de huidige stream een time-out kan hebben. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Bepaalt of de stream beschrijfbaar is. |
| int [get_Capacity](./get_capacity/)() | Geeft de huidige capaciteit van de onderliggende geheugenbuffer terug. |
| **int64_t** [get_Length](./get_length/)() const override | Geeft de lengte van de stream in bytes terug. |
| **int64_t** [get_Position](./get_position/)() const override | Geeft de huidige positie van de stream terug. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Haalt een waarde op, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat een time-out optreedt. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Haalt een waarde op, in milliseconden, die bepaalt hoe lang de stream zal proberen te schrijven voordat een time-out optreedt. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBuffer](./getbuffer/)() | Geeft een pointer naar de onderliggende buffer terug. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) wachobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [MemoryStream](./memorystream/)() | Construeert een nieuw exemplaar van de [MemoryStream](./) klasse met een initiële capaciteit gelijk aan 0. |
|  [MemoryStream](./memorystream/)(int) | Construeert een nieuw exemplaar van de [MemoryStream](./) klasse die een stream vertegenwoordigt gebaseerd op een geheugenbuffer van de opgegeven grootte. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | Construeert een nieuw exemplaar van de [MemoryStream](./) klasse die een geheugenstream voorstelt die verbonden is met de opgegeven geheugenbuffer. Een parameter geeft aan of de stream beschrijfbaar is. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int, **bool**, **bool**) | Construeert een nieuw exemplaar van de [MemoryStream](./) klasse die een geheugenstream voorstelt die verbonden is met een segment van de opgegeven geheugenbuffer, beginnend bij de opgegeven index en inclusief het opgegeven aantal elementen. Parameters geven aan of de stream beschrijfbaar is en of de methode GetBytes() kan worden aangeroepen. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert geen gegevens, initialiseert enkel een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert geen gegevens, initialiseert enkel een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-span. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Leest asynchroon een reeks bytes van de huidige stream, verplaatst de positie in de stream met het aantal gelezen bytes, en bewaakt annuleringsverzoeken. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Leest asynchroon een reeks bytes van de huidige stream, verplaatst de positie in de stream met het aantal gelezen bytes, en bewaakt annuleringsverzoeken. |
| int [ReadByte](./readbyte/)() override | Leest één byte uit de stream en retourneert een 32-bit integerwaarde die gelijk is aan de gelezen byte. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Stelt de positie van de stream ingesteld door het huidige object in. |
| void [set_Capacity](./set_capacity/)(int) | Stelt de capaciteit van de onderliggende geheugenbuffer in. |
| void [set_Position](./set_position/)(**int64_t**) override | Stelt de positie van de stream in. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Stelt een waarde in die bepaalt of de huidige stream kan time-outen. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Stelt een waarde in, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat een time-out optreedt. |
| void [SetLength](./setlength/)(**int64_t**) override | Stelt de lengte van de stream ingesteld door het huidige object in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloon-argument in op een zwakke pointer (in plaats van shared). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ToArray](./toarray/)() | Retourneert een kopie van de onderliggende geheugenbuffer als een byte-array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt converteren van aangepaste objecten naar string mogelijk. |
| **bool** [TryGetBuffer](./trygetbuffer/)([ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\&) | Retourneert de array van ongesigneerde bytes waaruit deze stream is gecreëerd. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) wachobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Schrijft het opgegeven subbereik van bytes van de opgegeven byte-array naar de stream. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Schrijft het opgegeven subbereik van bytes van de opgegeven byte-array naar de stream. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Schrijft het opgegeven subbereik van bytes van de opgegeven byte-array naar de stream. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Schrijft het opgegeven subbereik van bytes van de opgegeven byte-span naar de stream. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en bewaakt annuleringsverzoeken. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en bewaakt annuleringsverzoeken. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Schrijft de opgegeven ongesigneerde 8-bit integer-waarde naar de stream. |
| virtual void [WriteTo](./writeto/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>) | Schrijft de inhoud van de onderliggende buffer naar de opgegeven stream. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Velden

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | Een stream zonder onderliggende opslag. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een shared pointer naar zichzelf. |

## Zie ook

* Klasse [Stream](../stream/)
* Namespace [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)