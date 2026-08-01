---
title: XPathNavigator
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt een cursormodel voor het navigeren en bewerken van XML-gegevens.
type: docs
weight: 66
url: /nl/system.xml.xpath/xpathnavigator/
---
## XPathNavigator klasse

Biedt een cursormodel voor het navigeren en bewerken van XML-gegevens.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Retourneert een [XmlWriter](../../system.xml/xmlwriter/) object dat wordt gebruikt om een of meer nieuwe kindknopen te maken aan het einde van de lijst met kindknopen van de huidige knoop. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Maakt een nieuwe kindknoop aan het einde van de lijst met kindknopen van de huidige knoop met behulp van de opgegeven XML-gegevensreeks. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Maakt een nieuwe kindknoop aan het einde van de lijst met kindknopen van de huidige knoop met behulp van de XML-inhoud van het opgegeven [XmlReader](../../system.xml/xmlreader/) object. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Maakt een nieuwe kindknoop aan het einde van de lijst met kindknopen van de huidige knoop met behulp van de knopen in de opgegeven [XPathNavigator](./). |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Maakt een nieuw kindelementknoop aan het einde van de lijst met kindknopen van de huidige knoop met behulp van het opgegeven namespace-prefix, lokale naam en namespace-URI met de opgegeven waarde. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Controleert of de XML-gegevens in de [XPathNavigator](./) voldoen aan de opgegeven XML [Schema](../../system.xml.schema/) definitietaal (XSD) schema. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | Wanneer overschreven in een afgeleide klasse, maakt een nieuw [XPathNavigator](./) aan dat zich op dezelfde knoop bevindt als deze [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Vergelijkt de positie van de huidige [XPathNavigator](./) met de positie van de opgegeven [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Compileert een tekenreeks die een [XPath](../) expressie vertegenwoordigt en retourneert een [XPathExpression](../xpathexpression/) object. |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Maakt een attribuutsnode op de huidige elementenode met behulp van het opgegeven namespace-prefix, lokale naam en namespace-URI met de opgegeven waarde. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Retourneert een [XmlWriter](../../system.xml/xmlwriter/) object dat wordt gebruikt om nieuwe attributen op het huidige element te maken. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Retourneert een kopie van de [XPathNavigator](./). |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Verwijdert een reeks broedernodes van de huidige knoop tot de opgegeven knoop. |
| virtual void [DeleteSelf](./deleteself/)() | Verwijdert de huidige knoop en zijn kindknopen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagelijken waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagelijken waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Evalueert de opgegeven [XPath](../) expressie en retourneert het getypte resultaat. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Evalueert de opgegeven [XPath](../) expressie en retourneert het getypte resultaat, met behulp van het opgegeven [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) object om namespace-prefixen in de [XPath](../) expressie op te lossen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Evalueert de [XPathExpression](../xpathexpression/) en retourneert het getypte resultaat. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Gebruikt de geleverde context om de [XPathExpression](../xpathexpression/) te evalueren en retourneert het getypte resultaat. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Wanneer overschreven in een afgeleide klasse, haalt de basis-URI op voor de huidige knoop. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Retourneert een waarde die aangeeft of de [XPathNavigator](./) de onderliggende XML-gegevens kan bewerken. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Retourneert een waarde die aangeeft of de huidige knoop attributen heeft. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Retourneert een waarde die aangeeft of de huidige knoop kindknopen heeft. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Retourneert de markup die de kindknopen van de huidige knoop vertegenwoordigt. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Wanneer overschreven in een afgeleide klasse, haalt een waarde op die aangeeft of de huidige knoop een leeg element is zonder een eind-element-tag. |
| **bool** [get_IsNode](./get_isnode/)() override | Retourneert een waarde die aangeeft of de huidige knoop een [XPath](../) knoop voorstelt. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Wanneer overschreven in een afgeleide klasse, haalt de [XPathNavigator::get_Name](./get_name/) op van de huidige knoop zonder namespace-prefix. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Wanneer overschreven in een afgeleide klasse, haalt de gekwalificeerde naam van de huidige knoop op. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Wanneer overschreven in een afgeleide klasse, haalt de namespace-URI van de huidige knoop op. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Wanneer overschreven in een afgeleide klasse, haalt de [XmlNameTable](../../system.xml/xmlnametable/) op van de [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Retourneert een [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) die wordt gebruikt voor gelijkheidsvergelijking van [XPathNavigator](./) objecten. |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | Wanneer overschreven in een afgeleide klasse, haalt het XPathNodeType op van de huidige knoop. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Retourneert de markup die de opening- en sluit-tags van de huidige knoop en zijn kindknopen vertegenwoordigt. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Wanneer overschreven in een afgeleide klasse, haalt het namespace-prefix op dat is geassocieerd met de huidige knoop. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Retourneert de schemasinformatie die aan de huidige knoop is toegewezen als resultaat van schemavalidatie. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Retourneert de huidige knoop als een geboxte object van het meest geschikte type. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | Wordt gebruikt door [XPathNavigator](./) implementaties die een \"gevirtualiseerde\" XML-weergave over een opslag bieden, om toegang te geven tot onderliggende objecten. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | Wanneer overschreven in een afgeleide klasse, haalt de **string** waarde van het item op. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Retourneert de waarde van de huidige knoop als een [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Retourneert de waarde van de huidige knoop als een [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Retourneert de waarde van de huidige knoop als een [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Retourneert de waarde van de huidige knoop als een [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Retourneert de waarde van de huidige knoop als een [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Retourneert het type van de huidige knoop. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Retourneert de **xml:lang** scope voor de huidige knoop. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Retourneert de XmlSchemaType-informatie voor de huidige knoop. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Retourneert de waarde van het attribuut met de opgegeven lokale naam en namespace-URI. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Retourneert de waarde van de namespace-knoop die overeenkomt met de opgegeven lokale naam. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Retourneert de in-scope namespaces van de huidige knoop. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Retourneert een [XmlWriter](../../system.xml/xmlwriter/) object dat wordt gebruikt om een nieuwe broer-knoop te maken na de momenteel geselecteerde knoop. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Maakt een nieuwe broer-knoop aan na de momenteel geselecteerde knoop met behulp van de opgegeven XML-reeks. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Maakt een nieuwe broer-knoop aan na de momenteel geselecteerde knoop met behulp van de XML-inhoud van het opgegeven [XmlReader](../../system.xml/xmlreader/) object. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Maakt een nieuwe broer-knoop aan na de momenteel geselecteerde knoop met behulp van de knopen in het opgegeven [XPathNavigator](./) object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Retourneert een [XmlWriter](../../system.xml/xmlwriter/) object dat wordt gebruikt om een nieuwe broer-knoop vóór de momenteel geselecteerde knoop te maken. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Maakt een nieuwe broer-knoop vóór de momenteel geselecteerde knoop met behulp van de opgegeven XML-reeks. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Maakt een nieuwe broer-knoop vóór de momenteel geselecteerde knoop met behulp van de XML-inhoud van het opgegeven [XmlReader](../../system.xml/xmlreader/) object. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Maakt een nieuwe broer-knoop vóór de momenteel geselecteerde knoop met behulp van de knopen in het opgegeven [XPathNavigator](./). |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Maakt een nieuw broer-element aan na de huidige knoop met het opgegeven namespace-prefix, lokale naam en namespace-URI, met de opgegeven waarde. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Maakt een nieuw broer-element vóór de huidige knoop met het opgegeven namespace-prefix, lokale naam en namespace-URI, met de opgegeven waarde. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van de C# 'is' operator. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Bepaalt of de opgegeven [XPathNavigator](./) een afstammeling is van de huidige [XPathNavigator](./). |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Wanneer overschreven in een afgeleide klasse, bepaalt of de huidige [XPathNavigator](./) zich op dezelfde positie bevindt als de opgegeven [XPathNavigator](./). |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) wachto-object. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Retourneert de namespace-URI voor het opgegeven prefix. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Retourneert het voor het opgegeven namespace-URI gedeclareerde prefix. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Bepaalt of de huidige knoop overeenkomt met de opgegeven [XPathExpression](../xpathexpression/). |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Bepaalt of de huidige knoop overeenkomt met de opgegeven [XPath](../) expressie. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Wanneer overschreven in een afgeleide klasse, verplaatst de [XPathNavigator](./) naar dezelfde positie als de opgegeven [XPathNavigator](./). |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Verplaatst de [XPathNavigator](./) naar het attribuut met de overeenkomende lokale naam en namespace-URI. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | Verplaatst de [XPathNavigator](./) naar de kindknoop met de opgegeven lokale naam en namespace-URI. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | Verplaatst de [XPathNavigator](./) naar de kindknoop van het opgegeven XPathNodeType. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | Verplaatst de [XPathNavigator](./) naar de eerste broer-knoop van de huidige knoop. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Wanneer overschreven in een afgeleide klasse, verplaatst de [XPathNavigator](./) naar het eerste attribuut van de huidige knoop. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | Wanneer overschreven in een afgeleide klasse, verplaatst de [XPathNavigator](./) naar het eerste kind van de huidige knoop. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Wanneer overschreven in een afgeleide klasse, verplaatst de [XPathNavigator](./) naar de eerste namespace-knoop die overeenkomt met de opgegeven XPathNamespaceScope. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Verplaatst de [XPathNavigator](./) naar het eerste namespaceknooppunt van het huidige knooppunt. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Verplaatst de [XPathNavigator](./) naar het element met de opgegeven lokale naam en namespace-URI in documentvolgorde. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Verplaatst de [XPathNavigator](./) naar het element met de opgegeven lokale naam en namespace-URI, naar de opgegeven begrenzing, in documentvolgorde. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Verplaatst de [XPathNavigator](./) naar het volgende element van het opgegeven XPathNodeType in documentvolgorde. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Verplaatst de [XPathNavigator](./) naar het volgende element van het opgegeven XPathNodeType, naar de opgegeven begrenzing, in documentvolgorde. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | Wanneer overschreven in een afgeleide klasse, verplaatst naar het knooppunt dat een attribuut van type **ID** heeft waarvan de waarde overeenkomt met de opgegeven [String](../../system/string/). |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Verplaatst de [XPathNavigator](./) naar het namespaceknooppunt met het opgegeven namespace-voorvoegsel. |
| virtual **bool** [MoveToNext](./movetonext/)() | Wanneer overschreven in een afgeleide klasse, verplaatst de [XPathNavigator](./) naar het volgende broederknooppunt van het huidige knooppunt. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Verplaatst de [XPathNavigator](./) naar het volgende broederknooppunt met de opgegeven lokale naam en namespace-URI. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Verplaatst de [XPathNavigator](./) naar het volgende broederknooppunt van het huidige knooppunt dat overeenkomt met het opgegeven XPathNodeType. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Wanneer overschreven in een afgeleide klasse, verplaatst de [XPathNavigator](./) naar het volgende attribuut. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Wanneer overschreven in een afgeleide klasse, verplaatst de [XPathNavigator](./) naar het volgende namespaceknooppunt dat overeenkomt met de opgegeven XPathNamespaceScope. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Verplaatst de [XPathNavigator](./) naar het volgende namespaceknooppunt. |
| virtual **bool** [MoveToParent](./movetoparent/)() | Wanneer overschreven in een afgeleide klasse, verplaatst de [XPathNavigator](./) naar het bovenliggende knooppunt van het huidige knooppunt. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | Wanneer overschreven in een afgeleide klasse, verplaatst de [XPathNavigator](./) naar het vorige broederknooppunt van het huidige knooppunt. |
| virtual void [MoveToRoot](./movetoroot/)() | Verplaatst de [XPathNavigator](./) naar het rootknooppunt waartoe het huidige knooppunt behoort. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, echt niet, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt niet, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Retourneert een [XmlWriter](../../system.xml/xmlwriter/)-object dat wordt gebruikt om een nieuw kindknooppunt aan het begin van de lijst met kindknooppunten van het huidige knooppunt te maken. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Maakt een nieuw kindknooppunt aan het begin van de lijst met kindknooppunten van het huidige knooppunt met behulp van de opgegeven XML-string. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Maakt een nieuw kindknooppunt aan het begin van de lijst met kindknooppunten van het huidige knooppunt met behulp van de XML-inhoud van het opgegeven [XmlReader](../../system.xml/xmlreader/)-object. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Maakt een nieuw kindknooppunt aan het begin van de lijst met kindknooppunten van het huidige knooppunt met behulp van de knooppunten in het opgegeven [XPathNavigator](./)-object. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Maakt een nieuw kindelement aan het begin van de lijst met kindknooppunten van het huidige knooppunt met behulp van het opgegeven namespace-voorvoegsel, de lokale naam en de namespace-URI, samen met de opgegeven waarde. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Retourneert een [XmlReader](../../system.xml/xmlreader/)-object dat het huidige knooppunt en zijn kindknooppunten bevat. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van een string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Vervangt een bereik van broederknooppunten van het huidige knooppunt tot het opgegeven knooppunt. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Vervangt het huidige knooppunt door de inhoud van de opgegeven string. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Vervangt het huidige knooppunt door de inhoud van het opgegeven [XmlReader](../../system.xml/xmlreader/)-object. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Vervangt het huidige knooppunt door de inhoud van het opgegeven [XPathNavigator](./)-object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Selecteert een knoopset met behulp van de opgegeven [XPath](../)-expressie. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Selecteert een knoopset met behulp van de opgegeven [XPath](../)-expressie met het opgegeven [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-object om namespace-voorvoegsels op te lossen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Selecteert een knoopset met behulp van de opgegeven [XPathExpression](../xpathexpression/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Selecteert alle voorouderknooppunten van het huidige knooppunt die overeenkomen met het opgegeven XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Selecteert alle voorouderknooppunten van het huidige knooppunt die de opgegeven lokale naam en namespace-URI hebben. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Selecteert alle kindknooppunten van het huidige knooppunt die overeenkomen met het opgegeven XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Selecteert alle kindknooppunten van het huidige knooppunt die de opgegeven lokale naam en namespace-URI hebben. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Selecteert alle afstammingsknooppunten van het huidige knooppunt die overeenkomen met het opgegeven XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Selecteert alle afstammingsknooppunten van het huidige knooppunt die de opgegeven lokale naam en namespace-URI hebben. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Selecteert een enkel knooppunt in de [XPathNavigator](./) met de opgegeven [XPath](../)-query. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Selecteert een enkel knooppunt in het [XPathNavigator](./)-object met de opgegeven [XPath](../)-query en het opgegeven [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-object om namespace-voorvoegsels op te lossen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Selecteert een enkel knooppunt in de [XPathNavigator](./) met het opgegeven [XPathExpression](../xpathexpression/)-object. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Stelt de markup in die de kindknooppunten van het huidige knooppunt vertegenwoordigt. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Stelt de markup in die de opening- en sluit-tags van het huidige knooppunt en zijn kindknooppunten vertegenwoordigt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloon-argument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Stelt de getypeerde waarde van het huidige knooppunt in. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Stelt de waarde van het huidige knooppunt in. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Retourneert de tekstwaarde van het huidige knooppunt. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Retourneert de waarde van het huidige knooppunt als het opgegeven type, met gebruik van het opgegeven [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)-object om namespace-voorvoegsels op te lossen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Retourneert de waarde van het item als het opgegeven type. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Streamt het huidige knooppunt en zijn kindknooppunten naar het opgegeven [XmlWriter](../../system.xml/xmlwriter/)-object. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een gedeelde pointer naar een instantie van deze klasse. |

## Zie ook

* Klasse [XPathItem](../xpathitem/)
* Klasse [IXPathNavigable](../ixpathnavigable/)
* Klasse [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Naamruimte [System::Xml::XPath](../)
* Bibliotheek [Aspose.Slides](../../)