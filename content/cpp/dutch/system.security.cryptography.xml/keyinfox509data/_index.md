---
title: KeyInfoX509Data
second_title: Aspose.Slides voor C++ API-referentie
description: "Vertegenwoordigt een 'X509Data'-element. Bevat X.509v3-certificaatinformatie gerelateerd aan de validatie- of encryptiesleutel. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject()-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten oplevert. Omhul deze klasse altijd in een System::SmartPtr-pointer en gebruik die pointer om deze als argument aan functies door te geven."
type: docs
weight: 66
url: /nl/system.security.cryptography.xml/keyinfox509data/
---
## KeyInfoX509Data klasse


Stelt een 'X509Data'-element voor. Bevat X.509v3-certificaatinformatie gerelateerd aan de validatie- of encryptiesleutel. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Omhul deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik die pointer om deze aan functies als argument door te geven.

```cpp
class KeyInfoX509Data : public System::Security::Cryptography::Xml::KeyInfoClause
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [AddCertificate](./addcertificate/)([SharedPtr](../../system/sharedptr/)\<[X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\>) |  |
| void [AddIssuerSerial](./addissuerserial/)([String](../../system/string/), [String](../../system/string/)) |  |
| void [AddSubjectKeyId](./addsubjectkeyid/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) |  |
| void [AddSubjectName](./addsubjectname/)([String](../../system/string/)) |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert een C#-achtige vergelijking van zwevende-komma-waarden waarbij twee NaN-waarden als gelijk worden beschouwd, zelfs hoewel NaN volgens IEC 60559:1989 niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert een C#-achtige vergelijking van double-waarden waarbij twee NaN-waarden als gelijk worden beschouwd, zelfs hoewel NaN volgens IEC 60559:1989 niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SharedPtr](../../system/sharedptr/)\<[X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\>\>\> [get_Certificates](./get_certificates/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[X509IssuerSerial](../x509issuerserial/)\>\> [get_IssuerSerials](./get_issuerserials/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\>\> [get_SubjectKeyIds](./get_subjectkeyids/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[String](../../system/string/)\>\> [get_SubjectNames](./get_subjectnames/)() |  |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlElement](../../system.xml/xmlelement/)\> [GetXml](./getxml/)() override |  |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlElement](../../system.xml/xmlelement/)\> [GetXml](./getxml/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlDocument](../../system.xml/xmldocument/)\>) override |  |
| void [InternalAddIssuerSerial](./internaladdissuerserial/)([String](../../system/string/), [String](../../system/string/)) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van de C#-operator 'is'. |
|  [KeyInfoX509Data](./keyinfox509data/)() |  |
| void [LoadXml](./loadxml/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlElement](../../system.xml/xmlelement/)\>) override |  |
| void [Lock](../../system/object/lock/)() | Implementeert de lock()-statement van C#. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren via copy-constructie. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren via copy-constructie. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van een string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het mogelijk aangepaste objecten naar een string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert het C#-construct typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Verwijdert het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [KeyInfoClause](../keyinfoclause/)
* Naamruimte [System::Security::Cryptography::Xml](../)
* Bibliotheek [Aspose.Slides](../../)