---
title: XPathNavigator
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Poskytuje model kurzoru pro procházení a úpravu XML dat.
type: docs
weight: 66
url: /cs/system.xml.xpath/xpathnavigator/
---
## XPathNavigator třída

Poskytuje model kurzoru pro procházení a úpravu XML dat.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Vrací objekt [XmlWriter](../../system.xml/xmlwriter/) použitý k vytvoření jednoho nebo více nových poduzlů na konci seznamu poduzlů aktuálního uzlu. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Vytvoří nový poduzel na konci seznamu poduzlů aktuálního uzlu pomocí zadaného řetězce XML dat. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Vytvoří nový poduzel na konci seznamu poduzlů aktuálního uzlu pomocí XML obsahu zadaného objektu [XmlReader](../../system.xml/xmlreader/). |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Vytvoří nový poduzel na konci seznamu poduzlů aktuálního uzlu pomocí uzlů v zadaném [XPathNavigator](./). |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Vytvoří nový poduzel elementu na konci seznamu poduzlů aktuálního uzlu pomocí zadaného prefixu jmenného prostoru, lokálního názvu a URI jmenného prostoru s určenou hodnotou. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Ověřuje, že XML data v [XPathNavigator](./) odpovídají jazyku definice XML [Schema](../../system.xml.schema/) (XSD) schématu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | Když je přepsána v odvozené třídě, vytvoří nový [XPathNavigator](./) umístěný ve stejném uzlu jako tento [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Porovnává pozici aktuálního [XPathNavigator](./) s pozicí zadaného [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Sestaví řetězec představující výraz [XPath](../) a vrací objekt [XPathExpression](../xpathexpression/). |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Vytvoří uzel atributu na aktuálním elementovém uzlu pomocí zadaného prefixu jmenného prostoru, lokálního jména a URI jmenného prostoru s určenou hodnotou. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Vrací objekt [XmlWriter](../../system.xml/xmlwriter/) použitý k vytvoření nových atributů na aktuálním elementu. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Vrací kopii [XPathNavigator](./). |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Smaže rozsah sourozeneckých uzlů od aktuálního uzlu po zadaný uzel. |
| virtual void [DeleteSelf](./deleteself/)() | Smaže aktuální uzel a jeho poduzly. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Napodobuje porovnání floating point ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Napodobuje porovnání floating point ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Vyhodnotí zadaný výraz [XPath](../) a vrátí typovaný výsledek. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Vyhodnotí zadaný výraz [XPath](../) a vrátí typovaný výsledek, přičemž použije zadaný objekt [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) k rozřešení prefixů jmenných prostorů ve výrazu [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Vyhodnotí [XPathExpression](../xpathexpression/) a vrátí typovaný výsledek. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Používá dodaný kontext k vyhodnocení [XPathExpression](../xpathexpression/) a vrací typovaný výsledek. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Když je přepsána v odvozené třídě, získá základní URI pro aktuální uzel. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Vrací hodnotu, která udává, zda [XPathNavigator](./) může upravovat podkladová XML data. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Vrací hodnotu, která udává, zda aktuální uzel má nějaké atributy. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Vrací hodnotu, která udává, zda aktuální uzel má poduzly. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Vrací značkový kód představující poduzly aktuálního uzlu. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Když je přepsána v odvozené třídě, získá hodnotu, která udává, zda je aktuální uzel prázdný element bez uzavíracího tagu. |
| **bool** [get_IsNode](./get_isnode/)() override | Vrací hodnotu, která udává, zda aktuální uzel představuje [XPath](../) uzel. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Když je přepsána v odvozené třídě, získá [XPathNavigator::get_Name](./get_name/) aktuálního uzlu bez jakéhokoli prefixu jmenného prostoru. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Když je přepsána v odvozené třídě, získá kvalifikovaný název aktuálního uzlu. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Když je přepsána v odvozené třídě, získá URI jmenného prostoru aktuálního uzlu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Když je přepsána v odvozené třídě, získá [XmlNameTable](../../system.xml/xmlnametable/) [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Vrací [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) používaný pro porovnání rovnosti objektů [XPathNavigator](./). |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | Když je přepsána v odvozené třídě, získá XPathNodeType aktuálního uzlu. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Vrací značkový kód představující otevírací a zavírací tagy aktuálního uzlu a jeho poduzlů. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Když je přepsána v odvozené třídě, získá prefix jmenného prostoru přiřazený aktuálnímu uzlu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Vrací informace o schématu, které byly přiřazeny aktuálnímu uzlu v důsledku validace schématu. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Vrací aktuální uzel jako zabalený objekt nejvhodnějšího typu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | Používá se v implementacích [XPathNavigator](./), které poskytují „virtualizovaný“ XML pohled nad úložištěm, aby poskytly přístup k podkladovým objektům. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | Když je přepsána v odvozené třídě, získá **string** hodnotu položky. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Vrací hodnotu aktuálního uzlu jako [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Vrací hodnotu aktuálního uzlu jako [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Vrací hodnotu aktuálního uzlu jako [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Vrací hodnotu aktuálního uzlu jako [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Vrací hodnotu aktuálního uzlu jako [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Vrací typ aktuálního uzlu. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Vrací **xml:lang** rozsah pro aktuální uzel. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Vrací informace XmlSchemaType pro aktuální uzel. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Vrací hodnotu atributu se zadaným lokálním názvem a URI jmenného prostoru. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Vrací hodnotu uzlu jmenného prostoru odpovídajícího zadanému lokálnímu názvu. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Vrací v rozsahu platnosti jmenné prostory aktuálního uzlu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Vrací objekt [XmlWriter](../../system.xml/xmlwriter/) použitý k vytvoření nového sourozeneckého uzlu po aktuálně vybraném uzlu. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Vytvoří nový sourozenecký uzel po aktuálně vybraném uzlu pomocí zadaného XML řetězce. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Vytvoří nový sourozenecký uzel po aktuálně vybraném uzlu pomocí XML obsahu zadaného objektu [XmlReader](../../system.xml/xmlreader/). |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Vytvoří nový sourozenecký uzel po aktuálně vybraném uzlu pomocí uzlů v zadaném objektu [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Vrací objekt [XmlWriter](../../system.xml/xmlwriter/) použitý k vytvoření nového sourozeneckého uzlu před aktuálně vybraným uzlem. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Vytvoří nový sourozenecký uzel před aktuálně vybraným uzlem pomocí zadaného XML řetězce. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Vytvoří nový sourozenecký uzel před aktuálně vybraným uzlem pomocí XML obsahu zadaného objektu [XmlReader](../../system.xml/xmlreader/). |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Vytvoří nový sourozenecký uzel před aktuálně vybraným uzlem pomocí uzlů v zadaném [XPathNavigator](./). |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Vytvoří nový sourozenecký element po aktuálním uzlu pomocí zadaného prefixu jmenného prostoru, lokálního názvu a URI jmenného prostoru s určenou hodnotou. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Vytvoří nový sourozenecký element před aktuálním uzlem pomocí zadaného prefixu jmenného prostoru, lokálního názvu a URI jmenného prostoru s určenou hodnotou. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Určuje, zda zadaný [XPathNavigator](./) je potomkem aktuálního [XPathNavigator](./). |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Když je přepsána v odvozené třídě, určuje, zda aktuální [XPathNavigator](./) je ve stejné pozici jako zadaný [XPathNavigator](./). |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Volat přímo nebo použít objekt [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Vrací URI jmenného prostoru pro zadaný prefix. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Vrací prefix deklarovaný pro zadané URI jmenného prostoru. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Určuje, zda aktuální uzel odpovídá zadanému [XPathExpression](../xpathexpression/). |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Určuje, zda aktuální uzel odpovídá zadanému výrazu [XPath](../). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Když je přepsána v odvozené třídě, přesune [XPathNavigator](./) do stejné pozice jako zadaný [XPathNavigator](./). |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Přesune [XPathNavigator](./) na atribut s odpovídajícím lokálním názvem a URI jmenného prostoru. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | Přesune [XPathNavigator](./) na poduzel s určeným lokálním názvem a URI jmenného prostoru. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | Přesune [XPathNavigator](./) na poduzel specifikovaného XPathNodeType. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | Přesune [XPathNavigator](./) na první sourozenecký uzel aktuálního uzlu. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Když je přepsána v odvozené třídě, přesune [XPathNavigator](./) na první atribut aktuálního uzlu. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | Když je přepsána v odvozené třídě, přesune [XPathNavigator](./) na první poduzel aktuálního uzlu. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Když je přepsána v odvozené třídě, přesune [XPathNavigator](./) na první uzel jmenného prostoru, který odpovídá zadanému XPathNamespaceScope. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Přesune [XPathNavigator](./) na první uzel jmenného prostoru aktuálního uzlu. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Přesune [XPathNavigator](./) na prvek s lokálním názvem a URI jmenného prostoru určeným v pořadí dokumentu. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Přesune [XPathNavigator](./) na prvek s určeným lokálním názvem a URI jmenného prostoru, na určenou hranici, v pořadí dokumentu. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Přesune [XPathNavigator](./) na následující prvek typu XPathNodeType určený v pořadí dokumentu. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Přesune [XPathNavigator](./) na následující prvek typu XPathNodeType, na určenou hranici, v pořadí dokumentu. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | Při přepsání v odvozené třídě přesune na uzel, který má atribut typu **ID** s hodnotou odpovídající zadanému [String](../../system/string/). |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Přesune [XPathNavigator](./) na uzel jmenného prostoru se zadaným předponou jmenného prostoru. |
| virtual **bool** [MoveToNext](./movetonext/)() | Při přepsání v odvozené třídě přesune [XPathNavigator](./) na následující sourozenecký uzel aktuálního uzlu. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Přesune [XPathNavigator](./) na následující sourozenecký uzel s určeným lokálním názvem a URI jmenného prostoru. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Přesune [XPathNavigator](./) na následující sourozenecký uzel aktuálního uzlu, který odpovídá určenému typu XPathNodeType. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Při přepsání v odvozené třídě přesune [XPathNavigator](./) na následující atribut. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Při přepsání v odvozené třídě přesune [XPathNavigator](./) na následující uzel jmenného prostoru odpovídající určenému XPathNamespaceScope. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Přesune [XPathNavigator](./) na následující uzel jmenného prostoru. |
| virtual **bool** [MoveToParent](./movetoparent/)() | Při přepsání v odvozené třídě přesune [XPathNavigator](./) na nadřazený uzel aktuálního uzlu. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | Při přepsání v odvozené třídě přesune [XPathNavigator](./) na předchozí sourozenecký uzel aktuálního uzlu. |
| virtual void [MoveToRoot](./movetoroot/)() | Přesune [XPathNavigator](./) na kořenový uzel, ke kterému aktuální uzel patří. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Vrací objekt [XmlWriter](../../system.xml/xmlwriter/) použitý k vytvoření nového potomka na začátku seznamu potomků aktuálního uzlu. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Vytvoří nový poduzel na začátku seznamu potomků aktuálního uzlu pomocí zadaného řetězce XML. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Vytvoří nový poduzel na začátku seznamu potomků aktuálního uzlu pomocí XML obsahu zadaného objektu [XmlReader](../../system.xml/xmlreader/). |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Vytvoří nový poduzel na začátku seznamu potomků aktuálního uzlu pomocí uzlů v zadaném objektu [XPathNavigator](./). |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Vytvoří nový poduzel na začátku seznamu potomků aktuálního uzlu pomocí zadané předpony jmenného prostoru, lokálního názvu a URI jmenného prostoru s určenou hodnotou. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Vrací objekt [XmlReader](../../system.xml/xmlreader/) obsahující aktuální uzel a jeho potomky. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Nahrazuje rozsah sourozeneckých uzlů od aktuálního uzlu po určený uzel. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Nahrazuje aktuální uzel obsahem zadaného řetězce. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Nahrazuje aktuální uzel obsahem zadaného objektu [XmlReader](../../system.xml/xmlreader/). |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Nahrazuje aktuální uzel obsahem zadaného objektu [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Vybere množinu uzlů pomocí zadaného výrazu [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Vybere množinu uzlů pomocí zadaného výrazu [XPath](../) s objektem [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) určeným k rozlišení předpon jmenných prostorů. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Vybere množinu uzlů pomocí zadaného [XPathExpression](../xpathexpression/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Vybere všechny předky aktuálního uzlu, které mají odpovídající typ XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Vybere všechny předky aktuálního uzlu, které mají určený lokální název a URI jmenného prostoru. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Vybere všechny potomky aktuálního uzlu, které mají odpovídající typ XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Vybere všechny potomky aktuálního uzlu, které mají určený lokální název a URI jmenného prostoru. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Vybere všechny podřízené uzly aktuálního uzlu, které mají odpovídající typ XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Vybere všechny podřízené uzly aktuálního uzlu s určeným lokálním názvem a URI jmenného prostoru. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Vybere jediný uzel v [XPathNavigator](./) pomocí zadaného dotazu [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Vybere jediný uzel v objektu [XPathNavigator](./) pomocí zadaného dotazu [XPath](../) s objektem [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) určeným k rozlišení předpon jmenných prostorů. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Vybere jediný uzel v [XPathNavigator](./) pomocí zadaného objektu [XPathExpression](../xpathexpression/). |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Nastavuje značkování reprezentující poduzly aktuálního uzlu. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Nastavuje značkování představující otevírací a uzavírací tagy aktuálního uzlu a jeho poduzlů. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Nastaví typizovanou hodnotu aktuálního uzlu. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Nastaví hodnotu aktuálního uzlu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Vrací textovou hodnotu aktuálního uzlu. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Vrací hodnotu aktuálního uzlu jako určený typ, pomocí objektu [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) určeného k rozlišení předpon jmenných prostorů. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Vrací hodnotu položky jako určený typ. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Přenáší aktuální uzel a jeho poduzly do zadaného objektu [XmlWriter](../../system.xml/xmlwriter/). |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |

## Viz také

* Třída [XPathItem](../xpathitem/)
* Třída [IXPathNavigable](../ixpathnavigable/)
* Třída [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Jmenný prostor [System::Xml::XPath](../)
* Knihovna [Aspose.Slides](../../)