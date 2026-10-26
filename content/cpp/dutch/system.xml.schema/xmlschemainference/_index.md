---
title: XmlSchemaInference
second_title: Aspose.Slides for C++ API-referentie
description: Berekent een XML Schema Definition Language (XSD)-schema van een XML-document. De XmlSchemaInference-klasse kan niet geërfd worden.
type: docs
weight: 508
url: /nl/system.xml.schema/xmlschemainference/
---
## XmlSchemaInference klasse


Berekent een XML [Schema](../) Definition Language (XSD)-schema van een XML-document. De [XmlSchemaInference](./) klasse kan niet geërfd worden.

```cpp
class XmlSchemaInference : public System::Object
```

## Methods

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekomma-vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekomma-vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [XmlSchemaInference::InferenceOption](./inferenceoption/) [get_Occurrence](./get_occurrence/)() | Retourneert de [XmlSchemaInference::InferenceOption](./inferenceoption/)-waarde die invloed heeft op schema-voorkomensdeclinaties die zijn afgeleid van het XML-document. |
| [XmlSchemaInference::InferenceOption](./inferenceoption/) [get_TypeInference](./get_typeinference/)() | Retourneert de [XmlSchemaInference::InferenceOption](./inferenceoption/)-waarde die invloed heeft op typen die zijn afgeleid van het XML-document. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haal de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haal het werkelijke type van het object op. Analog van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\> [InferSchema](./inferschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | Berekent een XML [Schema](../) Definition Language (XSD)-schema van het XML-document dat zich bevindt in het opgegeven [XmlReader](../../system.xml/xmlreader/)-object. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\> [InferSchema](./inferschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\>) | Berekent een XML [Schema](../) Definition Language (XSD)-schema van het XML-document dat zich bevindt in het opgegeven [XmlReader](../../system.xml/xmlreader/)-object, en verfijnt het afgeleide schema met behulp van een bestaand schema in het opgegeven [XmlSchemaSet](../xmlschemaset/)-object met dezelfde doel-namespace. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie is van het type beschreven door targetType. Analog van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-sentry-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object via referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Occurrence](./set_occurrence/)([XmlSchemaInference::InferenceOption](./inferenceoption/)) | Stelt de [XmlSchemaInference::InferenceOption](./inferenceoption/)-waarde in die invloed heeft op schema-voorkomensdeclinaties die zijn afgeleid van het XML-document. |
| void [set_TypeInference](./set_typeinference/)([XmlSchemaInference::InferenceOption](./inferenceoption/)) | Stelt de [XmlSchemaInference::InferenceOption](./inferenceoption/)-waarde in die invloed heeft op typen die zijn afgeleid van het XML-document. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloon-argument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haal de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het unlock-statement van C# lock(). Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-sentry-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [XmlSchemaInference](./xmlschemainference/)() | Initialiseert een nieuwe instantie van de [XmlSchemaInference](./) klasse. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |
## Enumeraties

| Enumeratie | Beschrijving |
| --- | --- |
| [InferenceOption](./inferenceoption/) | Beïnvloedt voorkomens- en type-informatie die door de [XmlSchemaInference](./) klasse wordt afgeleid voor elementen en attributen in een XML-document. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een gedeelde pointer naar een instantie van deze klasse. |
## Opmerkingen



Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie [System::MakeObject()](../../system/makeobject/). Maak nooit instanties van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten oplevert. Verpak deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik die pointer om het aan functies als argument door te geven. 

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Xml::Schema](../)
* Bibliotheek [Aspose.Slides](../../)