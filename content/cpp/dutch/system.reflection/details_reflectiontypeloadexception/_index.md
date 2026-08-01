---
title: Details_ReflectionTypeLoadException
second_title: Aspose.Slides voor C++ API-referentie
description: "ReflectionTypeLoadException wordt gegooid door de Module.GetTypes methode als een van de klassen in een module niet kan worden geladen. Maak nooit handmatig instanties van deze klasse aan. Gebruik in plaats daarvan de ReflectionTypeLoadException klasse. Verpak de ReflectionTypeLoadException klasse-instanties nooit in System::SmartPtr."
type: docs
weight: 66
url: /nl/system.reflection/details_reflectiontypeloadexception/
---
## Details_ReflectionTypeLoadException klasse

ReflectionTypeLoadException wordt gegooid door de Module.GetTypes methode als een van de klassen in een module niet kan worden geladen. Maak nooit handmatig instanties van deze klasse aan. Gebruik in plaats daarvan de ReflectionTypeLoadException klasse. Verpak de ReflectionTypeLoadException klasse-instanties nooit in [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_ReflectionTypeLoadException : public System::Details_Exception
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl drijvende-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl drijvende-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Retourneert een woordenboek met aangepaste exceptie-gegevens. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Retourneert een 32-bit geheel getal dat een HRESULT-code is die gekoppeld is aan de exceptie die wordt vertegenwoordigd door het huidige object. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Retourneert een referentie naar het object dat de interne exceptie vertegenwoordigt. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::Exception](../../system/exception/)\> [get_LoaderExceptions](./get_loaderexceptions/)() const | Retourneert de excepties die deze exceptie veroorzaken. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Retourneert de tekenreeks die de foutbeschrijving bevat. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Retourneert de tekenreeks die de stack-trace bevat. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::TypeInfo](../../system/typeinfo/)\> [get_Types](./get_types/)() const | Retourneert de type-informatie van de oorzaken van de exceptie. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Retourneert een kopie van het Exception-object dat de innerlijkste exceptie vertegenwoordigt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haal de gegevensstructuur van de referentieteller op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haal het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie is van het type beschreven door targetType. Analoge van de C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Voert het vergrendelen van de C# lock() instructie uit. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewaker-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, maar initialiseert een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, maar initialiseert een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Stelt HRESULT in, een gecodeerde numerieke waarde die aan een specifieke exceptie wordt toegewezen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te templates argument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haal de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Retourneert de tekenreeksrepresentatie van het huidige object. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Voert het ontgrendelen van de C# lock() instructie uit. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewaker-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implementeert de [what()](../../system/details_exception/what/) methode die wordt aangeroepen door de [ExceptionWrapper](../../system/exceptionwrapper/) klasse. Ondanks het feit dat deze klasse niet erft van std::exception, kunnen afgeleide klassen beschermde/private leden gebruiken om hun logica te implementeren. Het verplaatsen van deze methodimplementatie naar de [ExceptionWrapper](../../system/exceptionwrapper/) kan die logica breken. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Details_Exception](../../system/details_exception/)
* Naamruimte [System::Reflection](../)
* Bibliotheek [Aspose.Slides](../../)