---
title: SoapDocumentServiceAttribute
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt het standaardformaat in voor de SOAP-verzoeken en -reacties. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit tot runtime-fouten en/of assertiefouten leidt. Omhul deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 66
url: /nl/system.web.services.protocols/soapdocumentserviceattribute/
---
## SoapDocumentServiceAttribute klasse

Stelt het standaardformaat in voor de SOAP-verzoeken en -antwoorden. Objecten van deze klasse mogen alleen worden toegewezen met behulp van de functie [System::MakeObject()](../../system/makeobject/). Maak nooit een instantie van dit type op de stapel of met operator new, omdat dit runtime-fouten en/of assertiefouten kan veroorzaken. Omhul altijd deze klasse in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class SoapDocumentServiceAttribute : public System::Attribute
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Bootst de C#-stijl zwevend-kommagvergelijking na waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Bootst de C#-stijl zwevend-kommagvergelijking na waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [SoapParameterStyle](../soapparameterstyle/) [get_ParameterStyle](./get_parameterstyle/)() | Haalt een waarde op die aangeeft of parameters zijn ingekapseld binnen één XML-element onder het 'Body'-element. |
| [SoapServiceRoutingStyle](../soapserviceroutingstyle/) [get_RoutingStyle](./get_routingstyle/)() | Haalt een waarde op die aangeeft hoe de SOAP-berichten naar de service worden gerouteerd. |
| [Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/) [get_Use](./get_use/)() | Haalt de parameteropmaak op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | Retourneert een aangepast attribuut van een opgegeven type toegepast op het opgegeven type. |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | Retourneert alle aangepaste attributen toegepast op het opgegeven type. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haal het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert het vergrendelen van de C#-lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-sentry-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
| [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, maar initialiseert alleen een nieuw object en maakt het kopiëren van subclasses mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, maar initialiseert alleen een nieuw object en maakt het kopiëren van subclasses mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object referentieel met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_ParameterStyle](./set_parameterstyle/)([SoapParameterStyle](../soapparameterstyle/)) | Stelt een waarde in die aangeeft of parameters zijn ingekapseld binnen één XML-element onder het 'Body'-element. |
| void [set_RoutingStyle](./set_routingstyle/)([SoapServiceRoutingStyle](../soapserviceroutingstyle/)) | Stelt een waarde in die aangeeft hoe de SOAP-berichten naar de service worden gerouteerd. |
| void [set_Use](./set_use/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | Stelt de parameteropmaak in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)() | Construeert een nieuwe instantie. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | Construeert een nieuwe instantie. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/), [SoapParameterStyle](../soapparameterstyle/)) | Construeert een nieuwe instantie. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C#-typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C#-lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-sentry-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijmaakt alle interne datastructuren. |

## Zie ook

* Klasse [Attribute](../../system/attribute/)
* Naamruimte [System::Web::Services::Protocols](../)
* Bibliotheek [Aspose.Slides](../../)