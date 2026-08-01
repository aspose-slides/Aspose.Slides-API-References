---
title: IStreamWrapper
second_title: Aspose.Slides voor C++ API-referentie
description: Aspose.IO.Stream-wrapper voor COM-interface.
type: docs
weight: 3875
url: /nl/aspose.slides/istreamwrapper/
---
## IStreamWrapper klasse


Aspose.IO.Stream-wrapper voor COM-interface.

```cpp
class IStreamWrapper : public System::IDisposable
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual void [Close](./close/)() | Sluit de huidige stroom en geeft alle bronnen vrij. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Doet niets. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekomma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekomma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual void [Flush](./flush/)() | Leegt alle buffers voor deze stroom en zorgt ervoor dat gebufferde gegevens naar het onderliggende apparaat worden geschreven. |
| virtual **bool** [get_CanRead](./get_canread/)() | Retourneert een waarde die aangeeft of de huidige stroom lezen ondersteunt. Alleen-lezen **bool**. |
| virtual **bool** [get_CanSeek](./get_canseek/)() | Retourneert een waarde die aangeeft of de huidige stroom zoeken ondersteunt. Alleen-lezen **bool**. |
| virtual **bool** [get_CanWrite](./get_canwrite/)() | Retourneert een waarde die aangeeft of de huidige stroom schrijven ondersteunt. Alleen-lezen **bool**. |
| virtual **int64_t** [get_Length](./get_length/)() | Retourneert de lengte in bytes van de stroom. Alleen-lezen **int64_t**. |
| virtual **int64_t** [get_Position](./get_position/)() | Retourneert de positie binnen de huidige stroom. Alleen-lezen **int64_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [get_Stream](./get_stream/)() | Retourneert een stroom. Alleen-lezen [System::IO::Stream](../../system.io/stream/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Retourneert de referentieteller-gegevensstructuur geassocieerd met het object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashberekening van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Retourneert het werkelijke type van het object. Analog van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analog van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert slechts een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert slechts een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| virtual void [Read](./read/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Leest een reeks bytes van de huidige stroom en verschuift de positie binnen de stroom met het aantal gelezen bytes. |
| virtual **int32_t** [ReadByte](./readbyte/)() | Leest een byte van de stroom en verschuift de positie binnen de stroom met één byte, of retourneert -1 als het einde van de stroom is bereikt. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual **int64_t** [Seek](./seek/)(**int64_t**, [System::IO::SeekOrigin](../../system.io/seekorigin/)) | Stelt de positie binnen de huidige stroom in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te veranderen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Retourneert de huidige waarde van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Zou niet rechtstreeks aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Zou niet rechtstreeks aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Zou niet rechtstreeks aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Zou niet rechtstreeks aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [Write](./write/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Schrijft een reeks bytes naar de huidige stroom en verschuift de huidige positie binnen deze stroom met het aantal geschreven bytes. |
| virtual void [WriteByte](./writebyte/)(**uint8_t**) | Schrijft een byte naar de huidige positie in de stroom en verschuift de positie binnen de stroom met één byte. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [IDisposable](../../system/idisposable/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)