---
title: "System::Xml"
second_title: Aspose.Slides pro C++ – referenční příručka API
description:
type: docs
weight: 1119
url: /cs/system.xml/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [Details_XmlException](./details_xmlexception/) | Vrací podrobné informace o poslední výjimce. |
| [IApplicationResourceStreamResolver](./iapplicationresourcestreamresolver/) | Představuje řešitel proudu prostředků aplikace. |
| [IHasXmlNode](./ihasxmlnode/) | Umožňuje třídě vrátit [XmlNode](./xmlnode/) z aktuálního kontextu nebo pozice. |
| [IXmlLineInfo](./ixmllineinfo/) | Poskytuje rozhraní, které umožňuje třídě vracet informace o řádku a pozici. |
| [IXmlNamespaceResolver](./ixmlnamespaceresolver/) | Poskytuje pouze pro čtení přístup k sadě mapování prefixů a jmenných prostorů. |
| [NameTable](./nametable/) | Implementuje jednovláknový [XmlNameTable](./xmlnametable/). |
| [XmlAttribute](./xmlattribute/) | Představuje atribut. Platné a výchozí hodnoty pro atribut jsou definovány v definici typu dokumentu (DTD) nebo schématu. |
| [XmlAttributeCollection](./xmlattributecollection/) | Představuje kolekci atributů, které lze přistupovat pomocí názvu nebo indexu. |
| [XmlCDataSection](./xmlcdatasection/) | Představuje sekci CDATA. |
| [XmlCharacterData](./xmlcharacterdata/) | Poskytuje metody pro manipulaci s textem, které používá několik tříd. |
| [XmlCharType](./xmlchartype/) | Pro interní účely. Nepoužívejte tuto třídu přímo. |
| [XmlComment](./xmlcomment/) | Představuje obsah XML komentáře. |
| [XmlConvert](./xmlconvert/) | Kóduje a dekóduje názvy XML a poskytuje metody pro převod mezi typy za běhu a typy definice XML [Schema](../system.xml.schema/) (XSD). Při převodu datových typů jsou vrácené hodnoty nezávislé na locale. |
| [XmlDeclaration](./xmldeclaration/) | Představuje uzel deklarace XML **<?xml version='1.0'...?>**. |
| [XmlDocument](./xmldocument/) | Představuje XML dokument. Tuto třídu můžete použít k načtení, validaci, úpravě, přidání a umístění XML v dokumentu. |
| [XmlDocumentFragment](./xmldocumentfragment/) | Představuje lehký objekt, který je užitečný pro operace vkládání do stromu. |
| [XmlDocumentType](./xmldocumenttype/) | Představuje deklaraci typu dokumentu. |
| [XmlElement](./xmlelement/) | Představuje prvek. |
| [XmlEntity](./xmlentity/) | Představuje deklaraci entity, například **<!ENTITY... >**. |
| [XmlEntityReference](./xmlentityreference/) | Představuje uzel reference entity. |
| [XmlImplementation](./xmlimplementation/) | Definuje kontext pro sadu objektů [XmlDocument](./xmldocument/). |
| [XmlLinkedNode](./xmllinkednode/) | Vrací uzel okamžitě předchozí nebo následující tomuto uzlu. |
| [XmlNamedNodeMap](./xmlnamednodemap/) | Představuje kolekci uzlů, které lze přistupovat pomocí názvu nebo indexu. |
| [XmlNamespaceManager](./xmlnamespacemanager/) | Rozpoznává, přidává a odstraňuje jmenné prostory v kolekci a poskytuje správu rozsahu pro tyto jmenné prostory. |
| [XmlNameTable](./xmlnametable/) | Tabulka atomizovaných řetězcových objektů. |
| [XmlNode](./xmlnode/) | Představuje jediný uzel v XML dokumentu. |
| [XmlNodeChangedEventArgs](./xmlnodechangedeventargs/) | Poskytuje data pro události **XmlDocument::NodeChanged**, **XmlDocument::NodeChanging**, **XmlDocument::NodeInserted**, **XmlDocument::NodeInserting**, **XmlDocument::NodeRemoved** a **XmlDocument::NodeRemoving**. |
| [XmlNodeList](./xmlnodelist/) | Představuje uspořádanou kolekci uzlů. |
| [XmlNodeReader](./xmlnodereader/) | Představuje čtečku, která poskytuje rychlý, nekešovaný jednosměrný přístup k XML datům v [XmlNode](./xmlnode/). |
| [XmlNotation](./xmlnotation/) | Představuje deklaraci notace, například **<!NOTATION... >**. |
| [XmlParserContext](./xmlparsercontext/) | Poskytuje veškeré kontextové informace potřebné [XmlReader](./xmlreader/) k analýze XML fragmentu. |
| [XmlProcessingInstruction](./xmlprocessinginstruction/) | Představuje zpracovatelský instrukční prvek, který XML definuje pro uchování procesorově specifických informací v textu dokumentu. |
| [XmlQualifiedName](./xmlqualifiedname/) | Představuje kvalifikovaný název XML. |
| [XmlReader](./xmlreader/) | Představuje čtečku, která poskytuje rychlý, nekešovaný jednosměrný přístup k XML datům. |
| [XmlReaderSettings](./xmlreadersettings/) | Určuje sadu funkcí, které mají být podporovány na objektu [XmlReader](./xmlreader/) vytvořeném metodou [XmlReader::Create](./xmlreader/create/). |
| [XmlResolver](./xmlresolver/) | Rozpoznává externí XML zdroje pojmenované Uniform Resource Identifier (URI). |
| [XmlSecureResolver](./xmlsecureresolver/) | Pomáhá zabezpečit jinou implementaci [XmlResolver](./xmlresolver/) zabalením objektu [XmlResolver](./xmlresolver/) a omezením zdrojů, ke kterým má podkladový [XmlResolver](./xmlresolver/) přístup. |
| [XmlSignificantWhitespace](./xmlsignificantwhitespace/) | Představuje bílé znaky mezi značkami v uzlu smíšeného obsahu nebo bílé znaky v rozsahu **xml:space='preserve'**. To se také označuje jako významné bílé znaky. |
| [XmlText](./xmltext/) | Představuje textový obsah prvku nebo atributu. |
| [XmlTextReader](./xmltextreader/) | Představuje čtečku, která poskytuje rychlý, nekešovaný jednosměrný přístup k XML datům. |
| [XmlTextWriter](./xmltextwriter/) | Představuje zapisovač, který poskytuje rychlý, nekešovaný jednosměrný způsob generování proudů nebo souborů obsahujících XML data, která vyhovují specifikaci W3C Extensible Markup Language (XML) 1.0 a doporučením Namespaces in XML. |
| [XmlUrlResolver](./xmlurlresolver/) | Rozpoznává externí XML zdroje pojmenované Uniform Resource Identifier (URI). |
| [XmlValidatingReader](./xmlvalidatingreader/) | Představuje čtečku, která poskytuje validaci definice typu dokumentu (DTD), schématu XML-Data Reduced (XDR) a definice jazyka XML [Schema](../system.xml.schema/) (XSD). |
| [XmlWhitespace](./xmlwhitespace/) | Představuje bílé znaky v obsahu prvku. |
| [XmlWriter](./xmlwriter/) | Představuje zapisovač, který poskytuje rychlý, nekešovaný jednosměrný způsob generování proudů nebo souborů obsahujících XML data. |
| [XmlWriterSettings](./xmlwritersettings/) | Určuje sadu funkcí, které mají být podporovány na objektu [XmlWriter](./xmlwriter/) vytvořeném metodou [XmlWriter::Create](./xmlwriter/create/). |

## Funkce

| Funkce | Popis |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&, const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&) | Porovnává dva objekty [XmlQualifiedName](./xmlqualifiedname/). |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&, const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&) | Porovnává dva objekty [XmlQualifiedName](./xmlqualifiedname/). |

## Výčty

| Výčet | Popis |
| --- | --- |
| [ConformanceLevel](./conformancelevel/) | Určuje míru kontroly vstupu nebo výstupu, kterou provádějí objekty [XmlReader](./xmlreader/) a [XmlWriter](./xmlwriter/). |
| [DtdProcessing](./dtdprocessing/) | Určuje možnosti zpracování DTD. Výčet DtdProcessing je používán třídou [XmlReaderSettings](./xmlreadersettings/). |
| [EntityHandling](./entityhandling/) | Určuje, jak [XmlTextReader](./xmltextreader/) nebo [XmlValidatingReader](./xmlvalidatingreader/) zacházejí s entitami. |
| [Formatting](./formatting/) | Určuje možnosti formátování pro [XmlTextWriter](./xmltextwriter/). |
| [NamespaceHandling](./namespacehandling/) | Určuje, zda odstranit duplicitní deklarace jmenných prostorů v [XmlWriter](./xmlwriter/). |
| [NewLineHandling](./newlinehandling/) | Určuje, jak zacházet s konci řádků. |
| [ReadState](./readstate/) | Určuje stav čtečky. |
| [XmlTokenizedType](./xmltokenizedtype/) | Představuje XML typ pro řetězec. To umožňuje číst řetězec jako konkrétní XML typ, například typ sekce CDATA. |
| [ValidationType](./validationtype/) | Určuje typ validace, která se provede. |
| [WhitespaceHandling](./whitespacehandling/) | Určuje, jak jsou bílé znaky zpracovány. |
| [WriteState](./writestate/) | Určuje stav [XmlWriter](./xmlwriter/). |
| [ExceptionType](./exceptiontype/) |  |
| [XmlDateTimeSerializationMode](./xmldatetimeserializationmode/) | Určuje, jak zacházet s časovou hodnotou při převodu mezi řetězcem a [DateTime](../system/datetime/). |
| [XmlNamespaceScope](./xmlnamespacescope/) | Definuje rozsah jmenného prostoru. |
| [XmlNodeChangedAction](./xmlnodechangedaction/) | Určuje typ změny uzlu. |
| [XmlNodeOrder](./xmlnodeorder/) | Popisuje pořadí dokumentu uzlu ve srovnání s druhým uzlem. |
| [XmlNodeType](./xmlnodetype/) | Určuje typ uzlu. |
| [XmlOutputMethod](./xmloutputmethod/) | Určuje metodu použitou k serializaci výstupu [XmlWriter](./xmlwriter/). |
| [XmlSpace](./xmlspace/) | Určuje aktuální rozsah **xml:space**. |
| [TriState](./tristate/) |  |
| [XmlStandalone](./xmlstandalone/) |  |

## Předefinice typů

| Předefinice typu | Popis |
| --- | --- |
| [XmlException](./xmlexception/) |  |
| [XmlNodeChangedEventHandler](./xmlnodechangedeventhandler/) | Představuje metodu, která zpracovává události **XmlDocument::NodeChanged**, **XmlDocument::NodeChanging**, **XmlDocument::NodeInserted**, **XmlDocument::NodeInserting**, **XmlDocument::NodeRemoved** a **XmlDocument::NodeRemoving**. |