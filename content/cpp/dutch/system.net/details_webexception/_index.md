---
title: Details_WebException
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt de uitzondering voor die wordt gegooid door WebRequest wanneer er een fout optreedt. Maak nooit handmatig exemplaren van deze klasse aan. Gebruik in plaats daarvan de WebException-klasse. Wrap nooit de exemplaren van de WebException-klasse in System::SmartPtr."
type: docs
weight: 92
url: /nl/system.net/details_webexception/
---
## Details_WebException klasse


Stelt de uitzondering voor die wordt gegooid door [WebRequest](../webrequest/) wanneer er een fout optreedt. Maak nooit handmatig exemplaren van deze klasse. Gebruik in plaats daarvan de WebException klasse. Wrap nooit de exemplaren van de WebException klasse in [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_WebException : public System::Details_InvalidOperationException
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [Exception](../../system/exception/) [CreateCompatibleException](./createcompatibleexception/)([Exception](../../system/exception/)) | Is niet geïmplementeerd. |
|  [Details_WebException](./details_webexception/)() | Maakt een nieuw exemplaar aan. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/)) | Maakt een nieuw exemplaar aan. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [Exception](../../system/exception/)) | Maakt een nieuw exemplaar aan. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [WebExceptionStatus](../webexceptionstatus/)) | Maakt een nieuw exemplaar aan. |
|  [Details_WebException](./details_webexception/)([String](../../system/string/), [Exception](../../system/exception/), [WebExceptionStatus](../webexceptionstatus/), [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\>) | Maakt een nieuw exemplaar aan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Retourneert een woordenboek met aangepaste exceptiegegevens. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Retourneert een 32-bits geheel getal dat een HRESULT-code is die gekoppeld is aan de uitzondering die wordt vertegenwoordigd door het huidige object. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Retourneert een referentie naar het object dat de innerlijke uitzondering vertegenwoordigt. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Retourneert de string die de foutbeschrijving bevat. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [get_Response](./get_response/)() | Retourneert de webrespons waarmee de huidige uitzondering is geassocieerd. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Retourneert de string die de stacktrace bevat. |
| [WebExceptionStatus](../webexceptionstatus/) [get_Status](./get_status/)() | Retourneert de statuscode. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Retourneert een kopie van het Exception-object dat de binnenste uitzondering vertegenwoordigt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt het hash'en van aangepaste objecten mogelijk. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_invalidoperationexception/gettype/)() const override | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| **bool** [Is](../../system/details_invalidoperationexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren via copy-constructie. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert enkel een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr per referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Stelt HRESULT in, een gecodeerde numerieke waarde die aan een specifieke uitzondering wordt toegewezen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th template-argument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Retourneert de stringrepresentatie van het huidige object. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_invalidoperationexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implementeert [what()](../../system/details_exception/what/) methode die wordt aangeroepen door [ExceptionWrapper](../../system/exceptionwrapper/) klasse. Ondanks het feit dat deze klasse niet is geërfd van std::exception kunnen afgeleide klassen beschermd/private leden gebruiken om hun logica te implementeren. Het verplaatsen van deze methodimplementatie naar [ExceptionWrapper](../../system/exceptionwrapper/) kan die logica breken. |
| virtual  [~Details_WebException](./~details_webexception/)() | Vernietigt de huidige instantie. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [Details_InvalidOperationException](../../system/details_invalidoperationexception/)
* Naamruimte [System::Net](../)
* Bibliotheek [Aspose.Slides](../../)