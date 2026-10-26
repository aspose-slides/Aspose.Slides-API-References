---
title: XPathNavigator
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller en markörmodell för att navigera och redigera XML-data.
type: docs
weight: 66
url: /sv/system.xml.xpath/xpathnavigator/
---
## XPathNavigator klass

Tillhandahåller en markörmodell för att navigera och redigera XML-data.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Returnerar ett [XmlWriter](../../system.xml/xmlwriter/)-objekt som används för att skapa en eller flera nya barnnoder i slutet av listan med barnnoder för den aktuella noden. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Skapar en ny barnnod i slutet av listan med barnnoder för den aktuella noden med den specificerade XML-datasträngen. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Skapar en ny barnnod i slutet av listan med barnnoder för den aktuella noden med XML-innehållet i det specificerade [XmlReader](../../system.xml/xmlreader/)-objektet. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Skapar en ny barnnod i slutet av listan med barnnoder för den aktuella noden med noderna i det specificerade [XPathNavigator](./). |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Skapar en ny barn-elementnod i slutet av listan med barnnoder för den aktuella noden med det angivna namnrymdsprefixet, lokala namnet och namnrymd-URI:n samt det angivna värdet. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Verifierar att XML-data i [XPathNavigator](./) följer det angivna XML [Schema](../../system.xml.schema/)-definitionsspråket (XSD)-schemat. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | När den åsidosätts i en avledd klass skapar den ett nytt [XPathNavigator](./) placerat på samma nod som detta [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Jämför positionen för den aktuella [XPathNavigator](./) med positionen för den specificerade [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Kompilerar en sträng som representerar ett [XPath](../)-uttryck och returnerar ett [XPathExpression](../xpathexpression/)-objekt. |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Skapar en attributnod på den aktuella elementnoden med det angivna namnrymdsprefixet, lokala namnet och namnrymd-URI:n samt det angivna värdet. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Returnerar ett [XmlWriter](../../system.xml/xmlwriter/)-objekt som används för att skapa nya attribut på det aktuella elementet. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Returnerar en kopia av [XPathNavigator](./). |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Raderar ett intervall av syskonnoder från den aktuella noden till den specificerade noden. |
| virtual void [DeleteSelf](./deleteself/)() | Raderar den aktuella noden och dess barnnoder. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Utvärderar det angivna [XPath](../)-uttrycket och returnerar det typade resultatet. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Utvärderar det angivna [XPath](../)-uttrycket och returnerar det typade resultatet, med hjälp av det specificerade [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-objektet för att lösa namnrymdsprefix i [XPath](../)-uttrycket. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Utvärderar [XPathExpression](../xpathexpression/) och returnerar det typade resultatet. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Använder den medföljande kontexten för att utvärdera [XPathExpression](../xpathexpression/) och returnerar det typade resultatet. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | När den åsidosätts i en avledd klass hämtar den bas-URI för den aktuella noden. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Returnerar ett värde som indikerar om [XPathNavigator](./) kan redigera den underliggande XML-datan. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Returnerar ett värde som indikerar om den aktuella noden har några attribut. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Returnerar ett värde som indikerar om den aktuella noden har några barnnoder. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Returnerar markup som representerar barnnoderna för den aktuella noden. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | När den åsidosätts i en avledd klass hämtar den ett värde som indikerar om den aktuella noden är ett tomt element utan ett avslutande element-tag. |
| **bool** [get_IsNode](./get_isnode/)() override | Returnerar ett värde som indikerar om den aktuella noden representerar en [XPath](../)-nod. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | När den åsidosätts i en avledd klass hämtar den [XPathNavigator::get_Name](./get_name/) för den aktuella noden utan något namnrymdsprefix. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | När den åsidosätts i en avledd klass hämtar den det kvalificerade namnet för den aktuella noden. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | När den åsidosätts i en avledd klass hämtar den namnrymd-URI:n för den aktuella noden. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | När den åsidosätts i en avledd klass hämtar den [XmlNameTable](../../system.xml/xmlnametable/) för [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Returnerar ett [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) som används för likhetssammanlänkning av [XPathNavigator](./)-objekt. |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | När den åsidosätts i en avledd klass hämtar den XPathNodeType för den aktuella noden. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Returnerar markup som representerar öppnings- och stängningstags för den aktuella noden och dess barnnoder. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | När den åsidosätts i en avledd klass hämtar den namnrymdsprefixet som är associerat med den aktuella noden. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Returnerar schemainformationen som har tilldelats den aktuella noden som ett resultat av schemavalidering. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Returnerar den aktuella noden som ett paketobjekt av den mest lämpliga typen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | Används av [XPathNavigator](./)-implementationer som tillhandahåller en ”virtualiserad” XML-vy över en lagring, för att ge åtkomst till underliggande objekt. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | När den åsidosätts i en avledd klass hämtar den **string**-värdet för objektet. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Returnerar den aktuella nodens värde som en [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Returnerar den aktuella nodens värde som en [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Returnerar den aktuella nodens värde som en [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Returnerar den aktuella nodens värde som en [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Returnerar den aktuella nodens värde som en [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Returnerar typen för den aktuella noden. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Returnerar **xml:lang**-omfånget för den aktuella noden. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Returnerar XmlSchemaType-informationen för den aktuella noden. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Returnerar värdet för attributet med det specificerade lokala namnet och namnrymd-URI:n. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenstæknar-datastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Returnerar värdet för namnrymdsnoden som motsvarar det specificerade lokala namnet. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Returnerar de namnrymder som är inom räckvidd för den aktuella noden. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Returnerar ett [XmlWriter](../../system.xml/xmlwriter/)-objekt som används för att skapa en ny syskonnod efter den för närvarande markerade noden. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Skapar en ny syskonnod efter den för närvarande markerade noden med den specificerade XML-strängen. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Skapar en ny syskonnod efter den för närvarande markerade noden med XML-innehållet i det specificerade [XmlReader](../../system.xml/xmlreader/)-objektet. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Skapar en ny syskonnod efter den för närvarande markerade noden med noderna i det specificerade [XPathNavigator](./)-objektet. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Returnerar ett [XmlWriter](../../system.xml/xmlwriter/)-objekt som används för att skapa en ny syskonnod före den för närvarande markerade noden. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Skapar en ny syskonnod före den för närvarande markerade noden med den specificerade XML-strängen. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Skapar en ny syskonnod före den för närvarande markerade noden med XML-innehållet i det specificerade [XmlReader](../../system.xml/xmlreader/)-objektet. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Skapar en ny syskonnod före den för närvarande markerade noden med noderna i det specificerade [XPathNavigator](./). |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Skapar ett nytt syskon-element efter den aktuella noden med det angivna namnrymdsprefixet, lokala namnet och namnrymd-URI:n samt det angivna värdet. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Skapar ett nytt syskon-element före den aktuella noden med det angivna namnrymdsprefixet, lokala namnet, namnrymd-URI:n samt det angivna värdet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Avgör om den specificerade [XPathNavigator](./) är en ättling till den aktuella [XPathNavigator](./). |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | När den åsidosätts i en avledd klass avgör den om den aktuella [XPathNavigator](./) är på samma position som den specificerade [XPathNavigator](./). |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Returnerar namnrymd-URI:n för det specificerade prefixet. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Returnerar prefixet som deklarerats för den specificerade namnrymd-URI:n. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Avgör om den aktuella noden matchar den specificerade [XPathExpression](../xpathexpression/). |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Avgör om den aktuella noden matchar det specificerade [XPath](../)-uttrycket. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | När den åsidosätts i en avledd klass flyttar den [XPathNavigator](./) till samma position som den specificerade [XPathNavigator](./). |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Flyttar [XPathNavigator](./) till attributet med matchande lokalt namn och namnrymd-URI. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | Flyttar [XPathNavigator](./) till barnnoden med det specificerade lokala namnet och namnrymd-URI:n. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | Flyttar [XPathNavigator](./) till barnnoden av den specificerade XPathNodeType. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | Flyttar [XPathNavigator](./) till den första syskonnoden för den aktuella noden. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | När den åsidosätts i en avledd klass flyttar den [XPathNavigator](./) till det första attributet för den aktuella noden. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | När den åsidosätts i en avledd klass flyttar den [XPathNavigator](./) till den första barnnoden för den aktuella noden. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | När den åsidosätts i en avledd klass flyttar den [XPathNavigator](./) till den första namnrymdsnoden som matchar den specificerade XPathNamespaceScope. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Flyttar [XPathNavigator](./) till den första namnrymdsnoden för den aktuella noden. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Flyttar [XPathNavigator](./) till elementet med det lokala namnet och namnrymds-URI som specificerats i dokumentordning. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Flyttar [XPathNavigator](./) till elementet med det lokala namnet och namnrymds-URI som specificerats, till den angivna gränsen, i dokumentordning. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Flyttar [XPathNavigator](./) till nästa element av den angivna XPathNodeType i dokumentordning. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Flyttar [XPathNavigator](./) till nästa element av den angivna XPathNodeType, till den angivna gränsen, i dokumentordning. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | När den åsidosätts i en avledd klass, flyttar den till noden som har ett attribut av typen **ID** vars värde matchar det angivna [String](../../system/string/). |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Flyttar [XPathNavigator](./) till namnrymdsnoden med det angivna namnrymdsprefixet. |
| virtual **bool** [MoveToNext](./movetonext/)() | När den åsidosätts i en avledd klass, flyttar den [XPathNavigator](./) till nästa syskonnod till den aktuella noden. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Flyttar [XPathNavigator](./) till nästa syskonnod med det angivna lokala namnet och namnrymds-URI. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Flyttar [XPathNavigator](./) till nästa syskonnod till den aktuella noden som matchar den angivna XPathNodeType. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | När den åsidosätts i en avledd klass, flyttar den [XPathNavigator](./) till nästa attribut. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | När den åsidosätts i en avledd klass, flyttar den [XPathNavigator](./) till nästa namnrymdsnod som matchar den angivna XPathNamespaceScope. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Flyttar [XPathNavigator](./) till nästa namnrymdsnod. |
| virtual **bool** [MoveToParent](./movetoparent/)() | När den åsidosätts i en avledd klass, flyttar den [XPathNavigator](./) till föräldranoden för den aktuella noden. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | När den åsidosätts i en avledd klass, flyttar den [XPathNavigator](./) till den föregående syskonnod till den aktuella noden. |
| virtual void [MoveToRoot](./movetoroot/)() | Flyttar [XPathNavigator](./) till rot-noden som den aktuella noden tillhör. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Returnerar ett [XmlWriter](../../system.xml/xmlwriter/)-objekt som används för att skapa en ny barnnod i början av listan över barnnoder för den aktuella noden. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Skapar en ny barnnod i början av listan över barnnoder för den aktuella noden med den specificerade XML-strängen. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Skapar en ny barnnod i början av listan över barnnoder för den aktuella noden med XML-innehållet i det specificerade [XmlReader](../../system.xml/xmlreader/)-objektet. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Skapar en ny barnnod i början av listan över barnnoder för den aktuella noden med noderna i det specificerade [XPathNavigator](./)-objektet. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Skapar ett nytt barn-element i början av listan över barnnoder för den aktuella noden med namnrymdsprefixet, lokala namnet och namnrymds-URI som specificerats med det angivna värdet. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Returnerar ett [XmlReader](../../system.xml/xmlreader/)-objekt som innehåller den aktuella noden och dess barnnoder. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Ersätter ett intervall av syskonnoder från den aktuella noden till den specificerade noden. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Ersätter den aktuella noden med innehållet i den specificerade strängen. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Ersätter den aktuella noden med innehållet i det specificerade [XmlReader](../../system.xml/xmlreader/)-objektet. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Ersätter den aktuella noden med innehållet i det specificerade [XPathNavigator](./)-objektet. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Väljer en noduppsättning med det specificerade [XPath](../)-uttrycket. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Väljer en noduppsättning med det specificerade [XPath](../)-uttrycket och det specificerade [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-objektet för att lösa namnrymdsprefix. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Väljer en noduppsättning med den specificerade [XPathExpression](../xpathexpression/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Väljer alla föräldranoder till den aktuella noden som har en matchande XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Väljer alla föräldranoder till den aktuella noden som har det specificerade lokala namnet och namnrymds-URI. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Väljer alla barnnoder till den aktuella noden som har en matchande XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Väljer alla barnnoder till den aktuella noden som har det specificerade lokala namnet och namnrymds-URI. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Väljer alla efterföljande noder till den aktuella noden som har en matchande XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Väljer alla efterföljande noder till den aktuella noden med det specificerade lokala namnet och namnrymds-URI. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Väljer en enskild nod i [XPathNavigator](./) med den specificerade [XPath](../)-frågan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Väljer en enskild nod i [XPathNavigator](./)-objektet med den specificerade [XPath](../)-frågan och det specificerade [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-objektet för att lösa namnrymdsprefix. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Väljer en enskild nod i [XPathNavigator](./) med det specificerade [XPathExpression](../xpathexpression/)-objektet. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Ställer in markup som representerar barnnoderna för den aktuella noden. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Ställer in markup som representerar öppnings- och stängningstaggarna för den aktuella noden och dess barnnoder. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter den n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Ställer in det typade värdet för den aktuella noden. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Ställer in värdet för den aktuella noden. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector ändå. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Returnerar textvärdet för den aktuella noden. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Returnerar den aktuella nodens värde som den specificerade typen, med hjälp av det specificerade [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-objektet för att lösa namnrymdsprefix. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Returnerar objektets värde som den specificerade typen. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Strömmar den aktuella noden och dess barnnoder till det specificerade [XmlWriter](../../system.xml/xmlwriter/)-objektet. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |

## Se också

* Klass [XPathItem](../xpathitem/)
* Klass [IXPathNavigable](../ixpathnavigable/)
* Klass [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Namnrymd [System::Xml::XPath](../)
* Bibliotek [Aspose.Slides](../../)