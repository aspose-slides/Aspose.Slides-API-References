---
title: XPathNavigator
second_title: Aspose.Slides C++ API Referencia
description: Kurzor modellt biztosít az XML adatok navigálásához és szerkesztéséhez.
type: docs
weight: 66
url: /hu/system.xml.xpath/xpathnavigator/
---
## XPathNavigator osztály

Kurzor-modellt biztosít az XML adatok navigálásához és szerkesztéséhez.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Visszaad egy [XmlWriter](../../system.xml/xmlwriter/) objektumot, amelyet a jelenlegi node gyermekcsomópontjainak listájának végén egy vagy több új gyermeknode létrehozására használnak. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Új gyermeknode-ot hoz létre a jelenlegi node gyermekcsomópontjainak listájának végén a megadott XML adatkarakterlánc használatával. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Új gyermeknode-ot hoz létre a jelenlegi node gyermekcsomópontjainak listájának végén a megadott [XmlReader](../../system.xml/xmlreader/) objektum XML tartalma alapján. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Új gyermeknode-ot hoz létre a jelenlegi node gyermekcsomópontjainak listájának végén a megadott [XPathNavigator](./) csomópontok alapján. |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Új gyermekelem-node-ot hoz létre a jelenlegi node gyermekcsomópontjainak listájának végén a megadott névtér előtag, helyi név és névtér URI értékekkel. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Ellenőri, hogy a [XPathNavigator](./) XML adatai megfelelnek-e a megadott XML [Schema](../../system.xml.schema/) definíciós nyelv (XSD) sémának. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | Ha egy származtatott osztályban felül van definiálva, új [XPathNavigator](./)-t hoz létre, amely ugyanazon node-on helyezkedik el, mint ez a [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Összehasonlítja a jelenlegi [XPathNavigator](./) pozícióját a megadott [XPathNavigator](./) pozíciójával. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Összeállít egy karakterláncot, amely egy [XPath](../) kifejezést képvisel, és visszaad egy [XPathExpression](../xpathexpression/) objektumot. |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Attribútum-node-ot hoz létre a jelenlegi elem-node-on a megadott névtér előtag, helyi név és névtér URI értékekkel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Visszaad egy [XmlWriter](../../system.xml/xmlwriter/) objektumot, amelyet a jelenlegi elemhez új attribútumok létrehozására használnak. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Visszaad egy másolatot a [XPathNavigator](./)-ról. |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Töröl egy tartományt a testvérnode-okból a jelenlegi node-otól a megadott node-ig. |
| virtual void [DeleteSelf](./deleteself/)() | Törli a jelenlegi node-ot és annak gyermeknode-jait. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C#-stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C#-stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Kiértékeli a megadott [XPath](../) kifejezést, és visszaadja a típusos eredményt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Kiértékeli a megadott [XPath](../) kifejezést, és visszaadja a típusos eredményt, a [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) objektum használatával a [XPath](../) kifejezésben lévő névtér előtagok feloldásához. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Kiértékeli a [XPathExpression](../xpathexpression/)-t, és visszaadja a típusos eredményt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | A megadott kontextust használja a [XPathExpression](../xpathexpression/) kiértékeléséhez, és visszaadja a típusos eredményt. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Ha egy származtatott osztályban felül van definiálva, lekéri a jelenlegi node alap-URI-ját. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Visszaad egy értéket, amely jelzi, hogy a [XPathNavigator](./) szerkesztheti-e a háttér XML adatokat. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Visszaad egy értéket, amely jelzi, hogy a jelenlegi node rendelkezik-e attribútumokkal. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Visszaad egy értéket, amely jelzi, hogy a jelenlegi node rendelkezik-e gyermeknode-okkal. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Visszaadja a jelölőnyelvet, amely a jelenlegi node gyermeknode-jait ábrázolja. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Ha egy származtatott osztályban felül van definiálva, lekéri azt az értéket, amely jelzi, hogy a jelenlegi node egy üres elem-e, záró elemcímke nélkül. |
| **bool** [get_IsNode](./get_isnode/)() override | Visszaad egy értéket, amely jelzi, hogy a jelenlegi node egy [XPath](../) node-ot képvisel-e. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Ha egy származtatott osztályban felül van definiálva, lekéri a jelenlegi node [XPathNavigator::get_Name](./get_name/)-jét névtér előtag nélkül. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Ha egy származtatott osztályban felül van definiálva, lekéri a jelenlegi node minősített nevét. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Ha egy származtatott osztályban felül van definiálva, lekéri a jelenlegi node névtér URI-ját. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Ha egy származtatott osztályban felül van definiálva, lekéri a [XPathNavigator](./) [XmlNameTable](../../system.xml/xmlnametable/)-jét. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Visszaad egy [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) objektumot, amelyet a [XPathNavigator](./) objektumok egyenlőség összehasonlításához használnak. |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | Ha egy származtatott osztályban felül van definiálva, lekéri a jelenlegi node XPathNodeType-át. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Visszaadja a jelölőnyelvet, amely a jelenlegi node és gyermeknode-jainak nyitó és záró címkéit ábrázolja. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Ha egy származtatott osztályban felül van definiálva, lekéri a jelenlegi node-hoz kapcsolódó névtér előtagot. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Visszaadja a sémainformációt, amely a séma-validálás eredményeként a jelenlegi node-hoz lett hozzárendelve. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Visszaadja a jelenlegi node-ot a legmegfelelőbb típusú dobozolt objektumként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | A [XPathNavigator](./) megvalósítások használják, amelyek egy „virtualizált” XML nézetet biztosítanak egy tároló felett, hogy hozzáférést biztosítsanak a mögöttes objektumokhoz. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | Ha egy származtatott osztályban felül van definiálva, lekéri az elem **string** értékét. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Visszaadja a jelenlegi node értékét [Boolean](../../system/boolean/)-ként. |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Visszaadja a jelenlegi node értékét [DateTime](../../system/datetime/)-ként. |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Visszaadja a jelenlegi node értékét [Double](../../system/double/)-ként. |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Visszaadja a jelenlegi node értékét [Int32](../../system/int32/)-ként. |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Visszaadja a jelenlegi node értékét [Int64](../../system/int64/)-ként. |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Visszaadja a jelenlegi node típusát. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Visszaadja a **xml:lang** hatókört a jelenlegi node-hoz. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Visszaadja a XmlSchemaType információt a jelenlegi node-hoz. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Visszaadja a megadott helyi név és névtér URI alapján az attribútum értékét. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Visszaadja a megadott helyi névhez tartozó névtér node értékét. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Visszaadja a jelenlegi node hatókörében lévő névtereket. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Visszaad egy [XmlWriter](../../system.xml/xmlwriter/) objektumot, amelyet az aktuálisan kiválasztott node után új testvérnode létrehozásához használnak. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Új testvérnode-ot hoz létre a jelenleg kiválasztott node után a megadott XML karakterlánc használatával. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Új testvérnode-ot hoz létre a jelenleg kiválasztott node után a megadott [XmlReader](../../system.xml/xmlreader/) objektum XML tartalma alapján. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Új testvérnode-ot hoz létre a jelenleg kiválasztott node után a megadott [XPathNavigator](./) objektum csomópontjainak felhasználásával. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Visszaad egy [XmlWriter](../../system.xml/xmlwriter/) objektumot, amelyet az aktuálisan kiválasztott node előtt új testvérnode létrehozásához használnak. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Új testvérnode-ot hoz létre a jelenleg kiválasztott node előtt a megadott XML karakterlánc használatával. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Új testvérnode-ot hoz létre a jelenleg kiválasztott node előtt a megadott [XmlReader](../../system.xml/xmlreader/) objektum XML tartalma alapján. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Új testvérnode-ot hoz létre a jelenleg kiválasztott node előtt a megadott [XPathNavigator](./) csomópontok felhasználásával. |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Új testvér elem-node-ot hoz létre a jelenlegi node után a megadott névtér előtag, helyi név és névtér URI értékekkel, a megadott értékkel. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Új testvér elem-node-ot hoz létre a jelenlegi node előtt a megadott névtér előtag, helyi név és névtér URI értékekkel, a megadott értékkel. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példány-e a targetType által leírt típusnak. A C# 'is' operátor analógja. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Megállapítja, hogy a megadott [XPathNavigator](./) a jelenlegi [XPathNavigator](./) leszármazottja-e. |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Ha egy származtatott osztályban felül van definiálva, megállapítja, hogy a jelenlegi [XPathNavigator](./) ugyanazon a pozíción van-e, mint a megadott [XPathNavigator](./). |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Visszaadja a megadott előtaghoz tartozó névtér URI-t. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Visszaadja a megadott névtér URI-hez deklarált előtagot. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Megállapítja, hogy a jelenlegi node megfelel-e a megadott [XPathExpression](../xpathexpression/)-nek. |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Megállapítja, hogy a jelenlegi node megfelel-e a megadott [XPath](../) kifejezésnek. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Ha egy származtatott osztályban felül van definiálva, a [XPathNavigator](./)-t a megadott [XPathNavigator](./)-val megegyező pozícióba helyezi. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | A [XPathNavigator](./)-t áthelyezi a megfelelő helyi névvel és névtér URI-val rendelkező attribútumra. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | A [XPathNavigator](./)-t áthelyezi a megadott helyi névvel és névtér URI-val rendelkező gyermeknode-ra. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | A [XPathNavigator](./)-t áthelyezi a megadott XPathNodeType-hoz tartozó gyermeknode-ra. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | A [XPathNavigator](./)-t áthelyezi a jelenlegi node első testvérnode-ára. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Ha egy származtatott osztályban felül van definiálva, a [XPathNavigator](./)-t a jelenlegi node első attribútumára helyezi. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | Ha egy származtatott osztályban felül van definiálva, a [XPathNavigator](./)-t a jelenlegi node első gyermeknode-ára helyezi. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Ha egy származtatott osztályban felül van definiálva, a [XPathNavigator](./)-t a megadott XPathNamespaceScope-nek megfelelő első névtér node-ra helyezi. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Áthelyezi a [XPathNavigator](./)-t az aktuális csomópont első névtér csomópontjára. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Áthelyezi a [XPathNavigator](./)-t a dokumentum sorrendjében megadott helyi névvel és névtér URI-vel rendelkező elemhez. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Áthelyezi a [XPathNavigator](./)-t a megadott helyi névvel és névtér URI-vel rendelkező elemhez, a megadott határba, a dokumentumsorrendben. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Áthelyezi a [XPathNavigator](./)-t a megadott XPathNodeType következő eleméhez a dokumentumsorrendben. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Áthelyezi a [XPathNavigator](./)-t a megadott XPathNodeType következő eleméhez, a megadott határba, a dokumentumsorrendben. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | Felülírva egy leszármazott osztályban, a megadott [String](../../system/string/) értékkel megegyező **ID** típusú attribútummal rendelkező csomópontra lép. |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Áthelyezi a [XPathNavigator](./)-t a megadott névtér előtaggal rendelkező névtér csomópontra. |
| virtual **bool** [MoveToNext](./movetonext/)() | Felülírva egy leszármazott osztályban, a [XPathNavigator](./)-t az aktuális csomópont következő testvércsomópontjára mozgatja. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Áthelyezi a [XPathNavigator](./)-t a megadott helyi névvel és névtér URI-vel rendelkező következő testvércsomópontra. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Áthelyezi a [XPathNavigator](./)-t az aktuális csomópont megadott XPathNodeType-nek megfelelő következő testvércsomópontjára. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Felülírva egy leszármazott osztályban, a [XPathNavigator](./)-t a következő attribútumra mozgatja. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Felülírva egy leszármazott osztályban, a [XPathNavigator](./)-t a megadott XPathNamespaceScope-nek megfelelő következő névtér csomópontra mozgatja. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Áthelyezi a [XPathNavigator](./)-t a következő névtér csomópontra. |
| virtual **bool** [MoveToParent](./movetoparent/)() | Felülírva egy leszármazott osztályban, a [XPathNavigator](./)-t az aktuális csomópont szülőcsomópontjára mozgatja. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | Felülírva egy leszármazott osztályban, a [XPathNavigator](./)-t az aktuális csomópont előző testvércsomópontjára mozgatja. |
| virtual void [MoveToRoot](./movetoroot/)() | Áthelyezi a [XPathNavigator](./)-t az aktuális csomópontot tartalmazó gyökércsomópontra. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Visszaad egy [XmlWriter](../../system.xml/xmlwriter/) objektumot, amelyet az aktuális csomópont gyerekcsomópont-listájának elejére új gyerekcsomópont létrehozásához használnak. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Új gyerekcsomópontot hoz létre a megadott XML karakterláncot felhasználva az aktuális csomópont gyerekcsomópont-listájának elején. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Új gyerekcsomópontot hoz létre a megadott [XmlReader](../../system.xml/xmlreader/) objektum XML tartalmát felhasználva az aktuális csomópont gyerekcsomópont-listájának elején. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Új gyerekcsomópontot hoz létre a megadott [XPathNavigator](./) objektum csomópontjait felhasználva az aktuális csomópont gyerekcsomópont-listájának elején. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Új gyerek elemet hoz létre az aktuális csomópont gyerekcsomópont-listájának elején a megadott névtér előtag, helyi név és névtér URI értékek felhasználásával. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Visszaad egy [XmlReader](../../system.xml/xmlreader/) objektumot, amely az aktuális csomópontot és annak gyerekcsomópontjait tartalmazza. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referencia alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referencia alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia alapján hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámot a megadott értékkel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Lecseréli a testvércsomópontok egy tartományát az aktuális csomóponttól a megadott csomópontig. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Az aktuális csomópontot a megadott karakterlánc tartalmával helyettesíti. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Az aktuális csomópontot a megadott [XmlReader](../../system.xml/xmlreader/) objektum tartalmával helyettesíti. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Az aktuális csomópontot a megadott [XPathNavigator](./) objektum tartalmával helyettesíti. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Kiválaszt egy csomópontkészletet a megadott [XPath](../) kifejezés segítségével. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Kiválaszt egy csomópontkészletet a megadott [XPath](../) kifezés használatával, a [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) objektummal a névtér előtagok feloldásához. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Kiválaszt egy csomópontkészletet a megadott [XPathExpression](../xpathexpression/) használatával. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Kiválaszt az aktuális csomópont összes olyan őscsomópontját, amelynek megegyező XPathNodeType típusa van. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Kiválaszt az aktuális csomópont összes olyan őscsomópontját, amelynek a megadott helyi neve és névtér URI-je van. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Kiválaszt az aktuális csomópont összes olyan gyerekcsomópontját, amelynek megegyező XPathNodeType típusa van. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Kiválaszt az aktuális csomópont összes olyan gyerekcsomópontját, amelynek a megadott helyi neve és névtér URI-je van. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Kiválaszt az aktuális csomópont összes olyan leszármazott csomópontját, amelynek megegyező XPathNodeType típusa van. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Kiválaszt az aktuális csomópont összes olyan leszármazott csomópontját, amelynek a megadott helyi neve és névtér URI-je van. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Kiválaszt egyetlen csomópontot a [XPathNavigator](./)-ban a megadott [XPath](../) lekérdezés használatával. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Kiválaszt egyetlen csomópontot a [XPathNavigator](./) objektumban a megadott [XPath](../) lekérdezés és a [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) objektum használatával a névtér előtagok feloldásához. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Kiválaszt egyetlen csomópontot a [XPathNavigator](./)-ban a megadott [XPathExpression](../xpathexpression/) objektum segítségével. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Beállítja az aktuális csomópont gyerekcsomópontjait ábrázoló markup-ot. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Beállítja az aktuális csomópont és annak gyerekcsomópontjainak nyitó és záró címkéit ábrázoló markup-ot. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerben történő gyenge módra váltását. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Beállítja az aktuális csomópont típusos értékét. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Beállítja az aktuális csomópont értékét. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott hivatkozásszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Visszaadja az aktuális csomópont szöveges értékét. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() állítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) védőobjektumot. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Visszaadja az aktuális csomópont értékét a megadott típusként, a [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) objektum használatával a névtér előtagok feloldásához. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Visszaadja az elem értékét a megadott típusban. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Az aktuális csomópontot és annak gyerekcsomópontjait a megadott [XmlWriter](../../system.xml/xmlwriter/) objektumba streameli. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Typedefek

| Typedef | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Az osztály egy példányára mutató megosztott mutató aliasa. |

## Lásd még

* Osztály [XPathItem](../xpathitem/)
* Osztály [IXPathNavigable](../ixpathnavigable/)
* Osztály [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Névterület [System::Xml::XPath](../)
* Könyvtár [Aspose.Slides](../../)