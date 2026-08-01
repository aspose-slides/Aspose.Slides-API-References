---
title: Details_AggregateException
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een exceptie voor die meerdere interne excepties bevat.
type: docs
weight: 300
url: /nl/system/details_aggregateexception/
---
## Details_AggregateException klasse


Vertegenwoordigt een exceptie die meerdere interne excepties bevat.

```cpp
class Details_AggregateException : public System::Details_Exception
```

## Methods

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevende-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevende-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [AggregateException](../aggregateexception/) [Flatten](./flatten/)() | Vloeit de samengestelde exceptie uit door alle geneste AggregateExceptions te ontvouwen tot een lijst met één niveau. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Retourneert een woordenboek met aangepaste exceptiegegevens. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Retourneert een 32-bits geheel getal dat een HRESULT-code is die aan de door het huidige object vertegenwoordigde exceptie is gekoppeld. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Retourneert een referentie naar het object dat de interne exceptie vertegenwoordigt. |
| **int32_t** [get_InnerExceptionCount](./get_innerexceptioncount/)() | Haal het aantal interne excepties op dat in deze samengestelde exceptie zit. |
| [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[Exception](../exception/)\>\> [get_InnerExceptions](./get_innerexceptions/)() | Haal een alleen-lezen collectie van de interne excepties op. |
| const [ArrayPtr](../arrayptr/)\<[Exception](../exception/)\>\& [get_InternalInnerExceptions](./get_internalinnerexceptions/)() | Retourneert de interne array van interne excepties. |
| [String](../string/) [get_Message](./get_message/)() const override | Overschrijft het basisbericht om geaggregeerde informatie van alle interne excepties op te nemen. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Retourneert de tekenreeks die de stacktrace bevat. |
| [Exception](../exception/) [GetBaseException](./getbaseexception/)() const override | Retourneert de onderliggende oorzaak-exceptie door recursief interne excepties te ontvouwen. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haal de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../object/gethashcode/) methode. Stelt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Haal het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../object/gettype/)-aanroep. |
| void [Handle](./handle/)(const [Func](../func/)\<[Exception](../exception/), **bool**\>\&) | Roept een handler-functie aan voor elke interne exceptie en gooit niet-afgehandelde excepties opnieuw. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Controleer of het object een instantie van het type beschreven door targetType vertegenwoordigt. Analoge van C# 'is' operator. |
| void [Lock](../object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../lockcontext/) bewakingsobject. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../object/memberwiseclone/) methode. Stelt het klonen van aangepaste types mogelijk. |
|  [Object](../object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Stelt HRESULT in, een gecodeerde numerieke waarde die aan een specifieke exceptie wordt toegewezen. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../object/sharedcount/)() const | Haal de huidige waarde van de gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Retourneert een tekenreeksrepresentatie van de exceptie, inclusief alle interne excepties. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementeert C# typeof([System.Object](../object/)) constructie. |
| void [Unlock](../object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementeert [what()](../details_exception/what/) methode die wordt aangeroepen door [ExceptionWrapper](../exceptionwrapper/) klasse. Ondanks dat deze klasse niet erft van std::exception, kunnen afgeleide klassen beschermde/privé-leden gebruiken om hun logica te implementeren. Het verplaatsen van deze methodenimplementatie naar [ExceptionWrapper](../exceptionwrapper/) kan die logica breken. |
| virtual  [~Object](../object/~object/)() | Vernietigt object. Vrijmaakt alle interne datastructuren. |

## Opmerkingen

Deze klasse wordt doorgaans gebruikt om meerdere excepties die gelijktijdig optreden te groeperen, bijvoorbeeld bij parallelle verwerking of asynchrone taakuitvoeringsscenario's. Het stelt gebruikers in staat om de bevatte excepties te onderzoeken, uit te vlakken of selectief af te handelen.

## Zie ook

* Klasse [Details_Exception](../details_exception/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)