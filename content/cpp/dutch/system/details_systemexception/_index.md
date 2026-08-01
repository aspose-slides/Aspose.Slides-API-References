---
title: Details_SystemException
second_title: Aspose.Slides voor C++ API-referentie
description: "Een basisklasse voor klassen die systeem (in plaats van toepassings) uitzonderingen vertegenwoordigen. Maak nooit handmatig instanties van deze klasse. Gebruik in plaats daarvan de SystemException-klasse. Verpak de instanties van de SystemException-klasse nooit in System::SmartPtr."
type: docs
weight: 703
url: /nl/system/details_systemexception/
---
## Details_SystemException klasse

Een basisklasse voor klassen die systeem (in plaats van toepassings) uitzonderingen vertegenwoordigen. Maak nooit handmatig instanties van deze klasse. Gebruik in plaats daarvan de SystemException-klasse. Verpak de SystemException-klasse-instanties nooit in [System::SmartPtr](../smartptr/).

```cpp
class Details_SystemException : public System::Details_Exception
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Retourneert een dictionary met aangepaste exceptiegegevens. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Retourneert een 32-bit geheel getal dat een HRESULT-code is, gekoppeld aan de uitzondering die door het huidige object wordt vertegenwoordigd. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Retourneert een referentie naar het object dat de interne uitzondering vertegenwoordigt. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Retourneert de tekenreeks die de foutbeschrijving bevat. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Retourneert de tekenreeks die de stack-trace bevat. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Retourneert een kopie van het Exception-object dat de meest interne uitzondering vertegenwoordigt. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haalt de referentieteller-datastructuur die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../object/gettype/)-aanroep. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implementeert het vergrendelen van de C# lock()-instructie. Roep direct aan of gebruik het [LockContext](../lockcontext/)-bewakingsobject. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopie-constructor. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopiëren-constructie van subklassen mogelijk. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopiëren-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Stelt HRESULT in, een gecodeerde numerieke waarde die aan een specifieke uitzondering wordt toegewezen. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in op een zwakke pointer (in plaats van een gedeelde). Stelt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Retourneert de tekenreeksrepresentatie van het huidige object. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-instructie. Roep direct aan of gebruik het [LockContext](../lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementeert de [what()](../details_exception/what/)-methode die wordt aangeroepen door de [ExceptionWrapper](../exceptionwrapper/)-klasse. Ondanks het feit dat deze klasse niet is geërfd van std::exception, kunnen afgeleide klassen beschermde/private leden gebruiken om hun logica te implementeren. Het verplaatsen van deze methode-implementatie naar de [ExceptionWrapper](../exceptionwrapper/) kan die logica breken. |
| virtual  [~Object](../object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Details_Exception](../details_exception/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)