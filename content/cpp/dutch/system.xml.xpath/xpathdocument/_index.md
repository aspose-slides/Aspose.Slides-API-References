---
title: XPathDocument
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt een snelle, alleen-lezen, in-memory weergave van een XML-document door gebruik te maken van het XPath-gegevensmodel.
type: docs
weight: 27
url: /nl/system.xml.xpath/xpathdocument/
---
## XPathDocument klasse

Biedt een snelle, alleen-lezen, in-memory weergave van een XML-document door gebruik te maken van het [XPath](../) gegevensmodel.

```cpp
class XPathDocument : public System::Xml::XPath::IXPathNavigable
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](../xpathnavigator/)\> [CreateNavigator](./createnavigator/)() override | Initialiseert een alleen-lezen [XPathNavigator](../xpathnavigator/)-object voor het navigeren door knooppunten in deze [XPathDocument](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert een C#-achtige floating-point vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert een C#-achtige floating-point vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haal de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge aan de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge aan de C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van een string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haal de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het lock()-statement van C# voor ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [XPathDocument](./xpathdocument/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | Initialiseert een nieuwe instantie van de [XPathDocument](./)-klasse vanuit de XML-gegevens die zijn opgenomen in het opgegeven [XmlReader](../../system.xml/xmlreader/)-object. |
|  [XPathDocument](./xpathdocument/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [XmlSpace](../../system.xml/xmlspace/)) | Initialiseert een nieuwe instantie van de [XPathDocument](./)-klasse vanuit de XML-gegevens die zijn opgenomen in het opgegeven [XmlReader](../../system.xml/xmlreader/)-object met de opgegeven whitespace-afhandeling. |
|  [XPathDocument](./xpathdocument/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Initialiseert een nieuwe instantie van de [XPathDocument](./)-klasse vanuit de XML-gegevens die zijn opgenomen in het opgegeven TextReader-object. |
|  [XPathDocument](./xpathdocument/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Initialiseert een nieuwe instantie van de [XPathDocument](./)-klasse vanuit de XML-gegevens in het opgegeven Stream-object. |
|  [XPathDocument](./xpathdocument/)(const [String](../../system/string/)\&) | Initialiseert een nieuwe instantie van de [XPathDocument](./)-klasse vanuit de XML-gegevens in het opgegeven bestand. |
|  [XPathDocument](./xpathdocument/)(const [String](../../system/string/)\&, [XmlSpace](../../system.xml/xmlspace/)) | Initialiseert een nieuwe instantie van de [XPathDocument](./)-klasse vanuit de XML-gegevens in het opgegeven bestand met de opgegeven whitespace-afhandeling. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een gedeelde pointer naar een instantie van deze klasse. |

## Opmerkingen

Objecten van deze klasse mogen alleen worden toegewezen met behulp van de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit instanties van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertie-fouten veroorzaakt. Omhul altijd deze klasse in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om het als argument aan functies door te geven. 

## Zie ook

* Klasse [IXPathNavigable](../ixpathnavigable/)
* Namespace [System::Xml::XPath](../)
* Bibliotheek [Aspose.Slides](../../)