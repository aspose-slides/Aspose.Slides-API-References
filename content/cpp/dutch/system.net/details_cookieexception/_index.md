---
title: Details_CookieException
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een uitzondering voor die wordt gegooid wanneer de grootte van CookieContainer groter is dan de waarde van de MaxCookieSize-eigenschap. Maak nooit handmatig exemplaren van deze klasse aan. Gebruik in plaats daarvan de CookieException-klasse. Wikkel de CookieException-klasse-exemplaren nooit in System::SmartPtr."
type: docs
weight: 79
url: /nl/system.net/details_cookieexception/
---
## Details_CookieException klasse

Stelt een uitzondering voor die wordt gegooid wanneer de grootte van [CookieContainer](../cookiecontainer/) groter is dan de waarde van de MaxCookieSize-eigenschap. Maak nooit handmatig exemplaren van deze klasse aan. Gebruik in plaats daarvan de CookieException-klasse. Wikkel de CookieException-klasse-exemplaren nooit in [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_CookieException : public System::Details_FormatException
```

## Methoden

| Method | Description |
| --- | --- |
|  [Details_CookieException](./details_cookieexception/)() | Construeert een nieuw exemplaar. |
|  [Details_CookieException](./details_cookieexception/)(std::nullptr_t) | Construeert een nieuw exemplaar. |
|  [Details_CookieException](./details_cookieexception/)([String](../../system/string/)) | Construeert een nieuw exemplaar. |
|  [Details_CookieException](./details_cookieexception/)([String](../../system/string/), [Exception](../../system/exception/)) | Construeert een nieuw exemplaar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-achtige floating-point-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-achtige floating-point-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Retourneert een woordenboek met aangepaste exceptiedata. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Retourneert een 32-bit geheel getal dat een HRESULT-code is die is geassocieerd met de exceptie die door het huidige object wordt weergegeven. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Retourneert een referentie naar het object dat de inner-exception weergeeft. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Retourneert de tekenreeks met de foutbeschrijving. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Retourneert de tekenreeks met de stack-trace. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Retourneert een kopie van het Exception-object dat de meest interne exceptie weergeeft. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_formatexception/gettype/)() const override | Haalt het daadwerkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| **bool** [Is](../../system/details_formatexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | Implementeert het vergrendelen van de C# lock()-instructie. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets werkelijk, initialiseert enkel een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets werkelijk, initialiseert enkel een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van een string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Stelt de HRESULT in, een gecodeerde numerieke waarde die aan een specifieke exceptie wordt toegewezen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-template-argument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Retourneert de tekenreeksrepresentatie van het huidige object. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_formatexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-instructie. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implementeert de [what()](../../system/details_exception/what/)-methode die wordt aangeroepen door de [ExceptionWrapper](../../system/exceptionwrapper/)-klasse. Ondanks het feit dat deze klasse niet is geërfd van std::exception, kunnen afgeleide klassen beschermde/private leden gebruiken om hun logica te implementeren. Het verplaatsen van deze methode-implementatie naar de [ExceptionWrapper](../../system/exceptionwrapper/) kan die logica breken. |
| virtual  [~Details_CookieException](./~details_cookieexception/)() | Vernietigt de huidige instantie. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Wis alle interne datastructuren. |

## Zie ook

* Klasse [Details_FormatException](../../system/details_formatexception/)
* Naamruimte [System::Net](../)
* Library [Aspose.Slides](../../)