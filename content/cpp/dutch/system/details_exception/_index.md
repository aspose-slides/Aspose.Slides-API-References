---
title: Details_Exception
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een uitzondering voor. Maak nooit handmatig instanties van deze klasse aan. Gebruik in plaats daarvan de Exception-klasse. Plaats nooit de Exception-klasse-instanties in System::SmartPtr."
type: docs
weight: 417
url: /nl/system/details_exception/
---
## Details_Exception klasse


Stelt een uitzondering voor. Maak nooit handmatig instanties van deze klasse aan. Gebruik in plaats daarvan de Exception klasse. Plaats nooit de Exception klasse-instanties in [System::SmartPtr](../smartptr/).

```cpp
class Details_Exception : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual void [DoThrow](./dothrow/)(const [ExceptionPtr](../exceptionptr/)\&) const | Gooit een uitzonderingsexemplaar dat door een exceptiewrapper is ingepakt. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type-objecten in C#-stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-achtige zwevendekommagelijkdigheidsvergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-achtige zwevendekommagelijkdigheidsvergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](./get_data/)() | Retourneert een woordenboek met aangepaste exceptie-gegevens. |
| **int32_t** [get_HResult](./get_hresult/)() const | Retourneert een 32-bit geheel getalwaarde die een HRESULT-code is gekoppeld aan de uitzondering die wordt weergegeven door het huidige object. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [get_InnerException](./get_innerexception/)() const | Retourneert een referentie naar het object dat de innerlijke uitzondering vertegenwoordigt. |
| virtual [String](../string/) [get_Message](./get_message/)() const | Retourneert de tekenreeks met de foutbeschrijving. |
| virtual [String](../string/) [get_StackTrace](./get_stacktrace/)() const | Retourneert de tekenreeks met de stacktrace. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [GetBaseException](./getbaseexception/)() const | Retourneert een kopie van het Exception-object dat de meest interne uitzondering vertegenwoordigt. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../object/gethashcode/) methode. Stelt het hashen van aangepaste objecten in staat. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../object/gettype/) aanroep. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Controleert of het object een exemplaar is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../lockcontext/) bewakingsobject. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../object/memberwiseclone/) methode. Stelt het klonen van aangepaste types in staat. |
|  [Object](../object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copyconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt copy-construeren van subklassen mogelijk. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt copy-construeren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentie van waarde-typedobject met nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_HResult](./set_hresult/)(**int32_t**) | Stelt HRESULT in, een gecodeerde numerieke waarde die aan een specifieke uitzondering wordt toegewezen. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Retourneert de tekenreeksrepresentatie van het huidige object. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementeert C# typeof([System.Object](../object/)) construct. |
| void [Unlock](../object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual const char * [what](./what/)() const | Implementeert [what()](./what/) methode die wordt aangeroepen door [ExceptionWrapper](../exceptionwrapper/) klasse. Ondanks het feit dat deze klasse niet is geërfd van std::exception, kunnen afgeleide klassen beschermde/privé-leden gebruiken om hun logica te implementeren. Het verplaatsen van deze methode-implementatie naar de [ExceptionWrapper](../exceptionwrapper/) kan die logica breken. |
| virtual  [~Object](../object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../object/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)