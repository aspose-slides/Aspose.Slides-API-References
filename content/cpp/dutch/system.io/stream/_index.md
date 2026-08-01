---
title: Stream
second_title: Aspose.Slides voor C++ API-referentie
description: "Een basisklasse voor verschillende stream-implementaties. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Pak deze klasse altijd in een System::SmartPtr pointer en gebruik die pointer om deze als argument aan functies door te geven."
type: docs
weight: 365
url: /nl/system.io/stream/
---
## Stream klasse


Een basisklasse voor verschillende stream-implementaties. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten zal veroorzaken. Pak deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik die pointer om deze als argument aan functies door te geven.

```cpp
class Stream : public System::IDisposable
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initieert een asynchrone leesbewerking. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initieert een asynchrone schrijfbewerking. |
| virtual void [Close](./close/)() | Sluit de stream. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&) | Kopieert bytes naar de opgegeven stream. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&, **int32_t**) | Kopieert bytes naar de opgegeven stream, met de opgegeven buffer-grootte. |
| void [Dispose](./dispose/)() override | Vrijgeeft alle resources die door het huidige object worden gebruikt en sluit de stream. |
| virtual int [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Wacht tot de opgegeven asynchrone leesbewerking voltooid is. |
| virtual void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Beëindigt een asynchrone schrijfbewerking. Wacht tot de opgegeven asynchrone schrijfbewerking voltooid is. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert een C#-achtige floating-point-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert een C#-achtige floating-point-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual void [Flush](./flush/)() | Leegt de buffers van deze stream en schrijft alle gebufferde data naar de onderliggende opslag. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Wis asynchroon alle buffers voor deze stream, zorgt ervoor dat gebufferde data naar het onderliggende apparaat wordt geschreven, en bewaakt annuleringsverzoeken. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)() | Wis asynchroon alle buffers voor deze stream, zorgt ervoor dat gebufferde data naar het onderliggende apparaat wordt geschreven, en bewaakt annuleringsverzoeken. |
| virtual **bool** [get_CanRead](./get_canread/)() const | Bepaalt of de stream leesbaar is. |
| virtual **bool** [get_CanSeek](./get_canseek/)() const | Bepaalt of de stream zoeken ondersteunt. |
| virtual **bool** [get_CanTimeout](./get_cantimeout/)() const | Haalt een waarde op die bepaalt of de huidige stream kan time-outen. |
| virtual **bool** [get_CanWrite](./get_canwrite/)() const | Bepaalt of de stream beschrijfbaar is. |
| virtual **int64_t** [get_Length](./get_length/)() const | Retourneert de lengte van de stream in bytes. |
| virtual **int64_t** [get_Position](./get_position/)() const | Retourneert de huidige positie van de stream. |
| virtual int [get_ReadTimeout](./get_readtimeout/)() const | Haalt een waarde op, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat een time-out optreedt. |
| virtual int [get_WriteTimeout](./get_writetimeout/)() const | Haalt een waarde op, in milliseconden, die bepaalt hoe lang de stream zal proberen te schrijven voordat een time-out optreedt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert gewoon een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignatie-operator. Kopieert niets echt, initialiseert gewoon een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| virtual **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar het opgegeven byte-array. |
| virtual **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar het opgegeven byte-array. |
| **int32_t** [Read](./read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar het opgegeven byte-array. |
| virtual **int32_t** [Read](./read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-span. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Leest asynchroon een reeks bytes uit de huidige stream, verplaatst de positie in de stream met het aantal gelezen bytes, en bewaakt annuleringsverzoeken. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Leest asynchroon een reeks bytes uit de huidige stream, verplaatst de positie in de stream met het aantal gelezen bytes, en bewaakt annuleringsverzoeken. |
| virtual int [ReadByte](./readbyte/)() | Leest één byte uit de stream en retourneert een 32-bit-integerwaarde die gelijk is aan de gelezen byte. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) | Stelt de positie van de stream in die wordt voorgesteld door het huidige object in. |
| virtual void [set_Position](./set_position/)(**int64_t**) | Stelt de positie van de stream in. |
| virtual void [set_ReadTimeout](./set_readtimeout/)(int) | Stelt een waarde in die bepaalt of de huidige stream kan time-outen. |
| virtual void [set_WriteTimeout](./set_writetimeout/)(int) | Stelt een waarde in, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat een time-out optreedt. |
| virtual void [SetLength](./setlength/)(**int64_t**) | Stelt de lengte van de stream in die wordt voorgesteld door het huidige object in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Stelt toe dat pointers in containers naar zwakke modus worden omgezet. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schrijft het opgegeven subbereik van bytes uit het opgegeven byte-array naar de stream. |
| virtual void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schrijft het opgegeven subbereik van bytes uit het opgegeven byte-array naar de stream. |
| void [Write](./write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Schrijft het opgegeven subbereik van bytes uit het opgegeven byte-array naar de stream. |
| virtual void [Write](./write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-span naar de stream. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en bewaakt annuleringsverzoeken. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en bewaakt annuleringsverzoeken. |
| virtual void [WriteByte](./writebyte/)(**uint8_t**) | Schrijft de opgegeven unsigned 8-bit integerwaarde naar de stream. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijmaakt alle interne datastructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Null](./null/) | Een stream zonder onderliggende opslag. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een shared pointer naar deze klasse. |

## Zie ook

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)