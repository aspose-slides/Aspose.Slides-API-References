---
title: Details_BadImageFormatException
second_title: Aspose.Slides voor C++ API Referentie
description: "De uitzondering die wordt gegooid wanneer de bestandsafbeelding van een dynamische linkbibliotheek (DLL) of een uitvoerbaar programma ongeldig is. Maak nooit handmatig exemplaren van deze klasse. Gebruik in plaats daarvan de BadImageFormatException klasse. Wrap de BadImageFormatException klasse-exemplaren nooit in System::SmartPtr."
type: docs
weight: 378
url: /nl/system/details_badimageformatexception/
---
## Details_BadImageFormatException klasse


De uitzondering die wordt gegooid wanneer de bestandsafbeelding van een dynamische linkbibliotheek (DLL) of een uitvoerbaar programma ongeldig is. Maak nooit handmatig exemplaren van deze klasse. Gebruik in plaats daarvan de BadImageFormatException klasse. Wrap de BadImageFormatException klasse-exemplaren nooit in [System::SmartPtr](../smartptr/).

```cpp
class Details_BadImageFormatException : public System::Details_ExceptionWithFilename<Details_SystemException>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Retourneert een woordenboek met aangepaste exceptiegegevens. |
| virtual [String](../string/) [get_FileName](../details_exceptionwithfilename/get_filename/)() const | Haalt de naam op van het bestand dat deze uitzondering veroorzaakt. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Retourneert een 32-bit geheel getal dat een HRESULT-code is die gekoppeld is aan de door het huidige object gerepresenteerde uitzondering. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Retourneert een referentie naar het object dat de interne uitzondering vertegenwoordigt. |
| [String](../string/) [get_Message](../details_exceptionwithfilename/get_message/)() const override |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Retourneert de string die de stacktrace bevat. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Retourneert een kopie van het Exception-object dat de meest interne uitzondering vertegenwoordigt. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../object/gethashcode/) methode. Maakt hashings van aangepaste objecten mogelijk. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](../details_systemexception/gettype/)() const override | Haalt het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../object/gettype/) aanroep. |
| **bool** [Is](../details_systemexception/is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implementeert de C# lock()-statement vergrendeling. Roep direct aan of gebruik het [LockContext](../lockcontext/) wachto-object. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../object/object/)() | Creëert een object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert slechts een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert slechts een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Stelt HRESULT in, een gecodeerde numerieke waarde die aan een specifieke uitzondering wordt toegewezen. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../string/) [ToString](../details_exceptionwithfilename/tostring/)() const override |  |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../details_systemexception/type/)() |  |
| void [Unlock](../object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../lockcontext/) wachto-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementeert de [what()](../details_exception/what/) methode die wordt aangeroepen door de [ExceptionWrapper](../exceptionwrapper/) klasse. Ondanks het feit dat deze klasse niet erft van std::exception, kunnen afgeleide klassen beschermde/private leden gebruiken om hun logica te implementeren. Het verplaatsen van deze methode-implementatie naar de [ExceptionWrapper](../exceptionwrapper/) kan die logica breken. |
| virtual  [~Object](../object/~object/)() | Vernietigt het object. Vrijmaakt alle interne gegevensstructuren. |

## Zie ook

* Klasse [Details_ExceptionWithFilename](../details_exceptionwithfilename/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)