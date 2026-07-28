---
title: XmlEntity
second_title: Aspose.Slides C++ API referencia
description: Entitásdeklarációt képvisel, például <!ENTITY... >.
type: docs
weight: 235
url: /hu/system.xml/xmlentity/
---
## XmlEntity osztály

Egy entitásdeklarációt képvisel, például **<!ENTITY... >**.

```cpp
class XmlEntity : public System::Xml::XmlNode
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | A megadott csomópontot a gyermekcsomópontok listájának végére adja, ennél a csomópontnál. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Lekéri az iterátort, amely az első elemet (ha van) a gyűjteményben mutatja. Ez az iterátor nem használható a hivatkozott objektum módosítására, mivel a [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T típusú másolat-objektumot ad vissza. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Lekéri az iterátort, amely a gyűjtemény const-kvalifikált példányának első elemére (ha van) mutat. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Lekéri az iterátort, amely a gyűjtemény első const-kvalifikált elemére (ha van) mutat. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Lekéri az iterátort, amely a gyűjtemény utolsó const-kvalifikált eleme után (ha van) mutat. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | Létrehoz egy másolatot erről a csomópontról. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | Létrehoz egy másolatot erről a csomópontról. Az entitás csomópontok nem klónozhatók. Ennek a metódusnak egy [XmlEntity](./) objektumon történő hívása kivételt dob. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | XPathNavigator-t hoz létre ennek az objektumnak a navigálásához. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Lekéri az iterátort, amely a gyűjtemény utolsó eleme után (ha van) mutat. Ez az iterátor nem használható a hivatkozott objektum módosítására, mert a [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T típusú másolat-objektumot ad vissza. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Lekéri az iterátort, amely a gyűjtemény const-kvalifikált példányának utolsó eleme után (ha van) mutat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumok összehasonlítása C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia-típusú objektumok összehasonlítása C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték-típusú objektumok összehasonlítása C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN egyetlen értékhez sem egyenlő, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN semmilyen értékhez, köztük a NaN-hez sem egyenlő. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | Visszaad egy [XmlAttributeCollection](../xmlattributecollection/)-t, amely a csomópont attribútumait tartalmazza. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Visszaad az aktuális csomópont alap Uniform Resource Identifier (URI) értékét. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | Visszaad a csomópont összes gyermekcsomópontját. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | Visszaad a csomópont első gyermekét. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | Visszaad egy értéket, amely jelzi, hogy a csomópont rendelkezik-e gyermekcsomópontokkal. |
| [String](../../system/string/) [get_InnerText](./get_innertext/)() override | Visszaadja az entitás csomópont és összes gyermekének összefűzött értékeit. |
| [String](../../system/string/) [get_InnerXml](./get_innerxml/)() override | Visszaadja a csomópont gyermekeit ábrázoló jelölőnyelvet. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() override | Visszaad egy értéket, amely jelzi, hogy a csomópont csak olvasható-e. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | Visszaad a csomópont utolsó gyermekét. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Visszaad a csomópont nevét a névtér előtag nélkül. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Visszaad a csomópont nevét. |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | Visszaad a csomópont névtér URI-ját. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | Visszaadja a csomópontot, amely közvetlenül ezt követi. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Visszaadja a csomópont típusát. |
| [String](../../system/string/) [get_NotationName](./get_notationname/)() | Visszaadja az entitásdeklarációban lévő opcionális NDATA attribútum nevét. |
| [String](../../system/string/) [get_OuterXml](./get_outerxml/)() override | Visszaadja a csomópontot és minden gyermekét ábrázoló jelölőnyelvet. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](../xmlnode/get_ownerdocument/)() | Visszaadja a [XmlDocument](../xmldocument/)-t, amelyhez ez a csomópont tartozik. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | Visszaadja ennek a csomópontnak a szülőjét (azoknál a csomópontoknál, amelyeknek lehet szülője). |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | Visszaadja a csomópont névtér előtagját. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | Visszaadja a csomópontot, amely közvetlenül ezt megelőzi. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | Visszaadja a szövegcsoportot, amely közvetlenül ezt megelőzi. |
| [String](../../system/string/) [get_PublicId](./get_publicid/)() | Visszaadja a nyilvános azonosító értékét az entitásdeklarációban. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlnode/get_schemainfo/)() | Visszaadja azt a séma validálás utáni információs készletet, amely a séma validálás eredményeként a csomópontra lett hozzárendelve. |
| [String](../../system/string/) [get_SystemId](./get_systemid/)() | Visszaadja a rendszerazonosító értékét az entitásdeklarációban. |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | Visszaadja a csomópont értékét. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított hivatkozásszámláló adatstruktúrát. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | Visszaad egy enumerátort, amely a jelenlegi csomópont gyermekcsomópontjain iterál. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | Megkeresi a legközelebbi **xmlns** deklarációt a megadott előtaghoz, amely a jelenlegi csomópont hatókörében van, és visszaadja a deklarációban szereplő névtér URI-ját. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | Megkeresi a legközelebbi **xmlns** deklarációt a megadott névtér URI-hoz, amely a jelenlegi csomópont hatókörében van, és visszaadja a deklarációban definiált előtagot. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | Visszaadja az első gyermekelemet a megadott [XmlNode::get_Name](../xmlnode/get_name/)-val. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Visszaadja az első gyermekelemet a megadott [XmlNode::get_LocalName](../xmlnode/get_localname/) és [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) értékekkel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Beszúrja a megadott csomópontot közvetlenül a megadott referencia csomópont után. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Beszúrja a megadott csomópontot közvetlenül a megadott referencia csomópont előtt. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Alkalmaz egy akkumulátor függvényt egy sorozaton. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat minden eleme teljesíti-e a feltételt. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Megállapítja, hogy a sorozat tartalmaz-e bármilyen elemet. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat bármely eleme létezik-e vagy teljesíti-e a feltételt. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Kiszámítja egy számszerű értékek sorozatának átlagát. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Kiszámítja egy olyan értékek sorozatának átlagát, amelyeket a bemeneti sorozat minden elemére egy transzformációs függvény hívásával nyernek. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Átalakítja az elemeket a megadott típusra. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Két sorozatot fűz össze. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Megállapítja, hogy a sorozat tartalmazza-e a megadott értéket. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálás alapján). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat azon elemeinek számát, amelyek megfelelnek a megadott feltételnek. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat első olyan elemét, amely megfelel a megadott feltételnek. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Visszaadja a sorozat első olyan elemét, amely megfelel a feltételnek, vagy egy alapértelmezett értéket, ha nincs ilyen elem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Csoportosítja a sorozat elemeit. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Csoportosítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Visszaadja a sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Visszaadja a sorozat utolsó elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Futtat egy transzformációs függvényt egy általános sorozat minden elemén, és visszaadja a legnagyobb eredményt. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Futtat egy transzformációs függvényt egy általános sorozat minden elemén, és visszaadja a legkisebb eredményt. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Szűri a sorozat elemeit a megadott típus alapján. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Rendezi egy sorozat elemeit növekvő sorrendben a keySelector által kiválasztott kulcsértékek szerint. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Rendezi egy sorozat elemeit csökkenő sorrendben a keySelector által kiválasztott kulcsértékek szerint. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Megfordítja egy sorozat elemeinek sorrendjét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Átalakítja egy sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Átalakítja egy sorozat minden elemét egy új formává, beépítve az elem indexét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Leképezi egy sorozat minden elemét, és összevonja a kapott sorozatokat egy sorozatba. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Kihagy egy meghatározott számú egymást követő elemet a sorozat elejéről, és visszaadja a maradékot. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Visszaad egy meghatározott számú egymást követő elemet a sorozat elejéről. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Létrehoz egy tömböt egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Létrehoz egy List<T>-t egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Szűri a sorozatot a megadott feltétel alapján. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| virtual void [Normalize](../xmlnode/normalize/)() | Az összes [XmlText](../xmltext/) csomópontot az ennek a [XmlNode](../xmlnode/) alatti részfa teljes mélységében egy "normál" formába helyezi, ahol csak a jelölőnyelv (azaz címkék, megjegyzések, feldolgozási utasítások, CDATA szakaszok és entitás hivatkozások) választja el a [XmlText](../xmltext/) csomópontokat, vagyis nincsenek szomszédos [XmlText](../xmltext/) csomópontok. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | A megadott csomópontot a gyermekcsomópontok listájának elejére adja ehhez a csomóponthoz. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumok összehasonlítása referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumok összehasonlítása referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Érték-típusú objektum referencia-összehasonlítása nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| virtual void [RemoveAll](../xmlnode/removeall/)() | Eltávolítja az aktuális csomópont összes gyermekcsomópontját és/vagy attribútumát. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Eltávolítja a megadott gyermekcsomópontot. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámlálót a megadott értékkel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Kicseréli a **oldChild** gyermekcsomópontot a **newChild** csomópontra. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | Kiválaszt egy csomópontlistát, amely megfelel a [XPath](../../system.xml.xpath/) kifejezésnek. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Kiválaszt egy csomópontlistát, amely megfelel a [XPath](../../system.xml.xpath/) kifejezésnek. A [XPath](../../system.xml.xpath/) kifejezésben talált előtagokat a megadott [XmlNamespaceManager](../xmlnamespacemanager/) alapján oldja fel. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | Kiválasztja az első [XmlNode](../xmlnode/)-t, amely megfelel a [XPath](../../system.xml.xpath/) kifejezésnek. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Kiválasztja az első [XmlNode](../xmlnode/)-t, amely megfelel a [XPath](../../system.xml.xpath/) kifejezésnek. A [XPath](../../system.xml.xpath/) kifejezésben talált előtagokat a megadott [XmlNamespaceManager](../xmlnamespacemanager/) alapján oldja fel. |
| void [set_InnerText](./set_innertext/)([String](../../system/string/)) override | Beállítja az entitás csomópont és összes gyermekének összefűzött értékeit. |
| void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) override | Beállítja ennek a csomópontnak a gyermekeket ábrázoló jelölőnyelvet. |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | Beállítja ennek a csomópontnak a névtér előtagját. |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | Beállítja a csomópont értékét. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerben történő weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | Megteszteli, hogy a DOM implementáció támogat-e egy adott funkciót. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Lekéri a jelenlegi konténer begin const iterátorának megvalósítását. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Lekéri a jelenlegi konténer begin iterátorának megvalósítását. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Lekéri a jelenlegi konténer end const iterátorának megvalósítását. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Lekéri a jelenlegi konténer end iterátorának megvalósítását. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Elmenti a csomópont összes gyermekét a megadott [XmlWriter](../xmlwriter/)-ba. [XmlEntity](./) csomópontok esetén ez a metódus nem hat. |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Elmenti a csomópontot a megadott [XmlWriter](../xmlwriter/)-ba. [XmlEntity](./) csomópontok esetén ez a metódus nem hat. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmísíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Egy alias a megosztott mutatóhoz, amely ennek az osztálynak egy példányára mutat. |

## Megjegyzések

Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányokat a stack-en vagy a new operátorral, mivel ez futási időbeli hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és ezt a mutatót használja a függvények argumentumaként való átadáshoz.

## Lásd még

* Osztály [XmlNode](../xmlnode/)
* Névtér [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)