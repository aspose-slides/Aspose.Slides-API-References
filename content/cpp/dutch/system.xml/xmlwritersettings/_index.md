---
title: XmlWriterSettings
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert een reeks functies die ondersteund moeten worden op het XmlWriter-object dat is gecreëerd door de XmlWriter::Create-methode."
type: docs
weight: 586
url: /nl/system.xml/xmlwritersettings/
---
## XmlWriterSettings klasse


Specificeert een set van functies die ondersteund moeten worden op het [XmlWriter](../xmlwriter/) object dat is aangemaakt door de [XmlWriter::Create](../xmlwriter/create/) methode.

```cpp
class XmlWriterSettings : public System::Object
```

## Methoden

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Maakt een kopie van de [XmlWriterSettings](./) instantie. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Retourneert een waarde die aangeeft of de XML-schrijver moet controleren of alle tekens in het document voldoen aan de "2.2 Characters" sectie van de W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Retourneert een waarde die aangeeft of de [XmlWriter](../xmlwriter/) ook de onderliggende stream of TextWriter moet sluiten wanneer de [XmlWriter::Close](../xmlwriter/close/)-methode wordt aangeroepen. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Retourneert het conformiteitsniveau dat de XML-schrijver controleert voor de XML-uitvoer. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Retourneert een waarde die aangeeft of de [XmlWriter](../xmlwriter/) geen URI-attributen escape. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Retourneert het type tekstcodering dat moet worden gebruikt. |
| **bool** [get_Indent](./get_indent/)() | Retourneert een waarde die aangeeft of elementen moeten worden ingesprongen. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Retourneert de tekenreeks die moet worden gebruikt bij inspringen. Deze instelling wordt gebruikt wanneer de [XmlWriterSettings::set_Indent](./set_indent/)-waarde is ingesteld op **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Retourneert een waarde die aangeeft of de [XmlWriter](../xmlwriter/) dubbele namespace-declaraties moet verwijderen bij het schrijven van XML-inhoud. Het standaardgedrag is dat de schrijver alle namespace-declaraties uitvoert die aanwezig zijn in de namespace-resolver van de schrijver. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Retourneert de tekenreeks die moet worden gebruikt voor regeleinden. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Retourneert een waarde die aangeeft of regeleinden in de uitvoer genormaliseerd moeten worden. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Retourneert een waarde die aangeeft of attributen op een nieuwe regel moeten worden geschreven. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Retourneert een waarde die aangeeft of een XML-declaratie moet worden weggelaten. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Retourneert de methode die wordt gebruikt om de [XmlWriter](../xmlwriter/)-uitvoer te serialiseren. |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Retourneert een waarde die aangeeft of de [XmlWriter](../xmlwriter/) sluit-tags zal toevoegen aan alle niet-gesloten element-tags wanneer de [XmlWriter::Close](../xmlwriter/close/)-methode wordt aangeroepen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr per referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [Reset](./reset/)() | Herstelt de leden van de instellingenklasse naar hun standaardwaarden. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Stelt een waarde in die aangeeft of de XML-schrijver moet controleren of alle tekens in het document voldoen aan de "2.2 Characters" sectie van de W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Stelt een waarde in die aangeeft of de [XmlWriter](../xmlwriter/) ook de onderliggende stream of TextWriter moet sluiten wanneer de [XmlWriter::Close](../xmlwriter/close/)-methode wordt aangeroepen. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Stelt het conformiteitsniveau in dat de XML-schrijver controleert voor de XML-uitvoer. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Stelt een waarde in die aangeeft of de [XmlWriter](../xmlwriter/) geen URI-attributen escape. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Stelt het type tekstcodering in dat moet worden gebruikt. |
| void [set_Indent](./set_indent/)(**bool**) | Stelt een waarde in die aangeeft of elementen moeten worden ingesprongen. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Stelt de tekenreeks in die moet worden gebruikt bij inspringen. Deze instelling wordt gebruikt wanneer de [XmlWriterSettings::set_Indent](./set_indent/)-waarde is ingesteld op **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Stelt een waarde in die aangeeft of de [XmlWriter](../xmlwriter/) dubbele namespace-declaraties moet verwijderen bij het schrijven van XML-inhoud. Het standaardgedrag is dat de schrijver alle namespace-declaraties uitvoert die aanwezig zijn in de namespace-resolver van de schrijver. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Stelt de tekenreeks in die moet worden gebruikt voor regeleinden. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Stelt een waarde in die aangeeft of regeleinden in de uitvoer genormaliseerd moeten worden. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Stelt een waarde in die aangeeft of attributen op een nieuwe regel moeten worden geschreven. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Stelt een waarde in die aangeeft of een XML-declaratie moet worden weggelaten. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Stelt een waarde in die aangeeft of de [XmlWriter](../xmlwriter/) sluit-tags zal toevoegen aan alle niet-gesloten element-tags wanneer de [XmlWriter::Close](../xmlwriter/close/)-methode wordt aangeroepen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Stelt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt omzetting van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [XmlWriterSettings](./xmlwritersettings/)() | Initialiseert een nieuwe instantie van de [XmlWriterSettings](./) klasse. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een gedeelde pointer naar een instantie van deze klasse. |

## Opmerkingen



Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit instanties van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Plaats deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om hem als argument aan functies door te geven. 

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)