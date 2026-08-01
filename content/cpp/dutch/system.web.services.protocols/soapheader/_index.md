---
title: SoapHeader
second_title: "Aspose.Slides voor C++ API-referentie"
description: "Stelt de inhoud van de SOAP-header voor. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik die pointer om deze aan functies als argument door te geven."
type: docs
weight: 79
url: /nl/system.web.services.protocols/soapheader/
---
## SoapHeader klasse

Stelt de inhoud van de SOAP-header voor. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik die pointer om het door te geven aan functies als argument.

```cpp
class SoapHeader : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt value-type-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [String](../../system/string/) [get_Actor](./get_actor/)() | Haalt de URI op van de SOAP-headerontvanger wanneer SOAP-versie 1.1 wordt gebruikt. |
| **bool** [get_DidUnderstand](./get_didunderstand/)() | Haalt een waarde op die aangeeft of de SOAP-header correct is verwerkt. |
| [String](../../system/string/) [get_EncodedMustUnderstand](./get_encodedmustunderstand/)() | Haalt de waarde op van het 'mustUnderstand'-attribuut wanneer SOAP-versie 1.1 wordt gebruikt. |
| [String](../../system/string/) [get_EncodedMustUnderstand12](./get_encodedmustunderstand12/)() | Haalt de waarde op van het 'mustUnderstand'-attribuut wanneer SOAP-versie 1.2 wordt gebruikt. |
| [String](../../system/string/) [get_EncodedRelay](./get_encodedrelay/)() | Haalt een tekenreeksrepresentatie op van de waarde van het 'relay'-attribuut. |
| **bool** [get_MustUnderstand](./get_mustunderstand/)() | Haalt een waarde op die aangeeft of de SOAP-header begrepen moet worden. |
| **bool** [get_Relay](./get_relay/)() | Haalt de waarde op van het 'relay'-attribuut. |
| [String](../../system/string/) [get_Role](./get_role/)() | Haalt de URI op van de SOAP-headerontvanger wanneer SOAP-versie 1.2 wordt gebruikt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Schakelt hashen van aangepaste objecten in. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analog van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van de C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Schakelt klonen van aangepaste typen in. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een value-type-object op referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Actor](./set_actor/)([String](../../system/string/)) | Stelt de URI in van de SOAP-headerontvanger wanneer SOAP-versie 1.1 wordt gebruikt. |
| void [set_DidUnderstand](./set_didunderstand/)(**bool**) | Stelt een waarde in die aangeeft of de SOAP-header correct is verwerkt. |
| void [set_EncodedMustUnderstand](./set_encodedmustunderstand/)([String](../../system/string/)) | Stelt de waarde in van het 'mustUnderstand'-attribuut wanneer SOAP-versie 1.1 wordt gebruikt. |
| void [set_EncodedMustUnderstand12](./set_encodedmustunderstand12/)([String](../../system/string/)) | Stelt de waarde in van het 'mustUnderstand'-attribuut wanneer SOAP-versie 1.2 wordt gebruikt. |
| void [set_EncodedRelay](./set_encodedrelay/)([String](../../system/string/)) | Stelt een tekenreeksrepresentatie in van de waarde van het 'relay'-attribuut. |
| void [set_MustUnderstand](./set_mustunderstand/)(**bool**) | Stelt een waarde in die aangeeft of de SOAP-header begrepen moet worden. |
| void [set_Relay](./set_relay/)(**bool**) | Stelt de waarde in van het 'relay'-attribuut. |
| void [set_Role](./set_role/)([String](../../system/string/)) | Stelt de URI in van de SOAP-headerontvanger wanneer SOAP-versie 1.2 wordt gebruikt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Hiermee kan men pointers in containers naar zwakke modus omschakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [SoapHeader](./soapheader/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlElement](../../system.xml/xmlelement/)\>) | Construeert een nieuwe instantie. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Schakelt omzetten van aangepaste objecten naar string in. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Web::Services::Protocols](../)
* Bibliotheek [Aspose.Slides](../../)