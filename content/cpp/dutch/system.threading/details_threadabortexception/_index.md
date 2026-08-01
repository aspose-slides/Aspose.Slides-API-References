---
title: Details_ThreadAbortException
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 79
url: /nl/system.threading/details_threadabortexception/
---
## Details_ThreadAbortException klasse




```cpp
class Details_ThreadAbortException : public System::Details_SystemException
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-kommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-kommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Retourneert een woordenboek met aangepaste exceptiegegevens. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Retourneert een 32-bits geheel getal dat een HRESULT-code is die is gekoppeld aan de uitzondering die door het huidige object wordt vertegenwoordigd. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Retourneert een referentie naar het object dat de interne uitzondering vertegenwoordigt. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Retourneert de string die de foutbeschrijving bevat. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Retourneert de string die de stacktrace bevat. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Retourneert een kopie van het Exception-object dat de meest interne uitzondering vertegenwoordigt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de gegevensstructuur van de referentieteller op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](./gettype/)() const override | Haalt het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| **bool** [Is](./is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Stelt HRESULT in, een gecodeerde numerieke waarde die aan een specifieke uitzondering wordt toegewezen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een weak-pointer (in plaats van shared). Staat toe om pointers in containers om te schakelen naar weak-modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt de gedeelde referentieteller en retourneert deze. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Retourneert de stringrepresentatie van het huidige object. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de weak-referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de weak-referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implementeert de [what()](../../system/details_exception/what/)-methode die wordt aangeroepen door de [ExceptionWrapper](../../system/exceptionwrapper/)-klasse. Ondanks dat deze klasse niet afstamt van std::exception, kunnen afgeleide klassen beschermde/private leden gebruiken om hun logica te implementeren. Het verplaatsen van deze methode-implementatie naar de [ExceptionWrapper](../../system/exceptionwrapper/) kan die logica breken. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Details_SystemException](../../system/details_systemexception/)
* Naamruimte [System::Threading](../)
* Bibliotheek [Aspose.Slides](../../)