---
title: "System::Xml"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 1119
url: /sv/system.xml/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Details_XmlException](./details_xmlexception/) | Returnerar detaljerad information om det senaste undantaget. |
| [IApplicationResourceStreamResolver](./iapplicationresourcestreamresolver/) | Representerar en lösare för applikationsresursströmmar. |
| [IHasXmlNode](./ihasxmlnode/) | Gör det möjligt för en klass att returnera ett [XmlNode](./xmlnode/) från det aktuella sammanhanget eller positionen. |
| [IXmlLineInfo](./ixmllineinfo/) | Tillhandahåller ett gränssnitt för att möjliggöra att en klass returnerar rad- och positionsinformation. |
| [IXmlNamespaceResolver](./ixmlnamespaceresolver/) | Tillhandahåller skrivskyddad åtkomst till en uppsättning prefix- och namnrymdsmappningar. |
| [NameTable](./nametable/) | Implementerar en enkeltrådad [XmlNameTable](./xmlnametable/). |
| [XmlAttribute](./xmlattribute/) | Representerar ett attribut. Giltiga och standardvärden för attributet definieras i en dokumenttypdefinition (DTD) eller ett schema. |
| [XmlAttributeCollection](./xmlattributecollection/) | Representerar en samling attribut som kan nås via namn eller index. |
| [XmlCDataSection](./xmlcdatasection/) | Representerar en CDATA-sektion. |
| [XmlCharacterData](./xmlcharacterdata/) | Tillhandahåller textmanipuleringsmetoder som används av flera klasser. |
| [XmlCharType](./xmlchartype/) | För interna ändamål. Använd inte den här klassen direkt. |
| [XmlComment](./xmlcomment/) | Representerar innehållet i en XML-kommentar. |
| [XmlConvert](./xmlconvert/) | Kodar och avkodar XML-namn samt tillhandahåller metoder för att konvertera mellan körtidstyper och XML [Schema](../system.xml.schema/) definition language (XSD)-typer. Vid konvertering av datatyper är de returnerade värdena oberoende av lokala inställningar. |
| [XmlDeclaration](./xmldeclaration/) | Representerar XML-deklarationsnoden **<?xml version='1.0'...?>**. |
| [XmlDocument](./xmldocument/) | Representerar ett XML-dokument. Du kan använda den här klassen för att läsa in, validera, redigera, lägga till och placera XML i ett dokument. |
| [XmlDocumentFragment](./xmldocumentfragment/) | Representerar ett lättviktigt objekt som är användbart för trädinsättningsoperationer. |
| [XmlDocumentType](./xmldocumenttype/) | Representerar dokumenttypdeklarationen. |
| [XmlElement](./xmlelement/) | Representerar ett element. |
| [XmlEntity](./xmlentity/) | Representerar en enhetsdeklaration, såsom **<!ENTITY... >**. |
| [XmlEntityReference](./xmlentityreference/) | Representerar en enhetsreferensnod. |
| [XmlImplementation](./xmlimplementation/) | Definierar kontexten för en uppsättning [XmlDocument](./xmldocument/)-objekt. |
| [XmlLinkedNode](./xmllinkednode/) | Returnerar noden som omedelbart föregår eller följer denna nod. |
| [XmlNamedNodeMap](./xmlnamednodemap/) | Representerar en samling noder som kan nås via namn eller index. |
| [XmlNamespaceManager](./xmlnamespacemanager/) | Löser, lägger till och tar bort namnrymder i en samling samt tillhandahåller omfångshantering för dessa namnrymder. |
| [XmlNameTable](./xmlnametable/) | Tabell med atomiserade strängobjekt. |
| [XmlNode](./xmlnode/) | Representerar en enskild nod i XML-dokumentet. |
| [XmlNodeChangedEventArgs](./xmlnodechangedeventargs/) | Tillhandahåller data för händelserna **XmlDocument::NodeChanged**, **XmlDocument::NodeChanging**, **XmlDocument::NodeInserted**, **XmlDocument::NodeInserting**, **XmlDocument::NodeRemoved** och **XmlDocument::NodeRemoving**. |
| [XmlNodeList](./xmlnodelist/) | Representerar en ordnad samling av noder. |
| [XmlNodeReader](./xmlnodereader/) | Representerar en läsare som ger snabb, icke-cachad framåtriktad åtkomst till XML-data i ett [XmlNode](./xmlnode/). |
| [XmlNotation](./xmlnotation/) | Representerar en notationsdeklaration, såsom **<!NOTATION... >**. |
| [XmlParserContext](./xmlparsercontext/) | Tillhandahåller all kontextinformation som krävs av [XmlReader](./xmlreader/) för att parsra ett XML-fragment. |
| [XmlProcessingInstruction](./xmlprocessinginstruction/) | Representerar en processinstruktion, som XML definierar för att behålla processor-specifik information i dokumentets text. |
| [XmlQualifiedName](./xmlqualifiedname/) | Representerar ett XML-kvalificerat namn. |
| [XmlReader](./xmlreader/) | Representerar en läsare som erbjuder snabb, icke-cachad, framåtriktad åtkomst till XML-data. |
| [XmlReaderSettings](./xmlreadersettings/) | Anger en uppsättning funktioner att stödja på [XmlReader](./xmlreader/)-objektet som skapas av [XmlReader::Create](./xmlreader/create/)-metoden. |
| [XmlResolver](./xmlresolver/) | Löser externa XML-resurser som benämns av en Uniform Resource Identifier (URI). |
| [XmlSecureResolver](./xmlsecureresolver/) | Hjälper till att säkra en annan implementation av [XmlResolver](./xmlresolver/) genom att kapsla in [XmlResolver](./xmlresolver/)-objektet och begränsa de resurser som den underliggande [XmlResolver](./xmlresolver/) har åtkomst till. |
| [XmlSignificantWhitespace](./xmlsignificantwhitespace/) | Representerar blanksteg mellan markup i en blandad innehållsnod eller blanksteg inom ett **xml:space='preserve'**-omfång. Detta kallas också betydande blanksteg. |
| [XmlText](./xmltext/) | Representerar textinnehållet i ett element eller attribut. |
| [XmlTextReader](./xmltextreader/) | Representerar en läsare som ger snabb, icke-cachad, framåtriktad åtkomst till XML-data. |
| [XmlTextWriter](./xmltextwriter/) | Representerar en skribent som tillhandahåller ett snabbt, icke-cachat, framåtriktat sätt att generera strömmar eller filer som innehåller XML-data som följer W3C Extensible Markup Language (XML) 1.0 och rekommendationerna för Namespaces in XML. |
| [XmlUrlResolver](./xmlurlresolver/) | Löser externa XML-resurser som benämns av en Uniform Resource Identifier (URI). |
| [XmlValidatingReader](./xmlvalidatingreader/) | Representerar en läsare som tillhandahåller dokumenttypdefinition (DTD), XML-Data Reduced (XDR) schema och XML [Schema](../system.xml.schema/) definition language (XSD)-validering. |
| [XmlWhitespace](./xmlwhitespace/) | Representerar blanksteg i elementinnehåll. |
| [XmlWriter](./xmlwriter/) | Representerar en skribent som tillhandahåller ett snabbt, icke-cachat, framåtriktat sätt att generera strömmar eller filer som innehåller XML-data. |
| [XmlWriterSettings](./xmlwritersettings/) | Anger en uppsättning funktioner att stödja på [XmlWriter](./xmlwriter/)-objektet som skapas av [XmlWriter::Create](./xmlwriter/create/)-metoden. |

## Funktioner

| Funktion | Beskrivning |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&, const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&) | Jämför två [XmlQualifiedName](./xmlqualifiedname/)-objekt. |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&, const [SharedPtr](../system/sharedptr/)\<[XmlQualifiedName](./xmlqualifiedname/)\>\&) | Jämför två [XmlQualifiedName](./xmlqualifiedname/)-objekt. |

## Uppräkningar

| Enum | Beskrivning |
| --- | --- |
| [ConformanceLevel](./conformancelevel/) | Anger mängden in- eller utmatningskontroll som [XmlReader](./xmlreader/)- och [XmlWriter](./xmlwriter/)-objekt utför. |
| [DtdProcessing](./dtdprocessing/) | Anger alternativen för bearbetning av DTD:er. DtdProcessing-uppräkningen används av klassen [XmlReaderSettings](./xmlreadersettings/). |
| [EntityHandling](./entityhandling/) | Anger hur [XmlTextReader](./xmltextreader/) eller [XmlValidatingReader](./xmlvalidatingreader/) hanterar enheter. |
| [Formatting](./formatting/) | Anger formateringsalternativ för [XmlTextWriter](./xmltextwriter/). |
| [NamespaceHandling](./namespacehandling/) | Anger om dubblett-namnrymdsdeklarationer ska tas bort i [XmlWriter](./xmlwriter/). |
| [NewLineHandling](./newlinehandling/) | Anger hur radbrytningar ska hanteras. |
| [ReadState](./readstate/) | Anger läsarens tillstånd. |
| [XmlTokenizedType](./xmltokenizedtype/) | Representerar XML-typen för strängen. Detta gör att strängen kan läsas som en viss XML-typ, till exempel en CDATA-sektionstyp. |
| [ValidationType](./validationtype/) | Anger vilken typ av validering som ska utföras. |
| [WhitespaceHandling](./whitespacehandling/) | Anger hur blanksteg hanteras. |
| [WriteState](./writestate/) | Anger tillståndet för [XmlWriter](./xmlwriter/). |
| [ExceptionType](./exceptiontype/) |  |
| [XmlDateTimeSerializationMode](./xmldatetimeserializationmode/) | Anger hur tidsvärdet ska behandlas vid konvertering mellan sträng och [DateTime](../system/datetime/). |
| [XmlNamespaceScope](./xmlnamespacescope/) | Definierar namnrymdens omfattning. |
| [XmlNodeChangedAction](./xmlnodechangedaction/) | Anger typen av nodändring. |
| [XmlNodeOrder](./xmlnodeorder/) | Beskriver dokumentordningen för en nod i förhållande till en andra nod. |
| [XmlNodeType](./xmlnodetype/) | Anger nodens typ. |
| [XmlOutputMethod](./xmloutputmethod/) | Anger metoden som används för att serialisera [XmlWriter](./xmlwriter/)-utdata. |
| [XmlSpace](./xmlspace/) | Anger det aktuella **xml:space**-omfånget. |
| [TriState](./tristate/) |  |
| [XmlStandalone](./xmlstandalone/) |  |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [XmlException](./xmlexception/) |  |
| [XmlNodeChangedEventHandler](./xmlnodechangedeventhandler/) | Representerar metoden som hanterar händelserna **XmlDocument::NodeChanged**, **XmlDocument::NodeChanging**, **XmlDocument::NodeInserted**, **XmlDocument::NodeInserting**, **XmlDocument::NodeRemoved** och **XmlDocument::NodeRemoving**. |