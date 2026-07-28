---
title: XmlElement
second_title: Aspose.Slides for C++ API-referencia
description: Egy elemet képvisel.
type: docs
weight: 222
url: /hu/system.xml/xmlelement/
---
## XmlElement osztály

Egy elemet reprezentál.

```cpp
class XmlElement : public System::Xml::XmlLinkedNode
```

## Metódusok

| Módszer | Leírás |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Hozzáadja a megadott csomópontot a gyermekcsomópontok listájának végéhez, ezen a csomóponton. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Visszaad egy iterátort, amely az első (ha van) elemet mutatja a gyűjteményben. Ez az iterátor nem használható a hivatkozott objektum módosítására, mert [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) egy T másolat-objektumot ad vissza. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Visszaad egy iterátort, amely a gyűjtemény const-kvalifikált példányának első (ha van) elemére mutat. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Visszaad egy iterátort, amely a gyűjtemény első const-kvalifikált (ha van) elemére mutat. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Visszaad egy iterátort, amely a gyűjtemény utolsó const-kvalifikált elemét (ha van) követően mutat. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | Létrehoz egy másolatot erről a csomópontról. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | Létrehoz egy másolatot erről a csomópontról. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | Létrehoz egy XPathNavigator-t az objektum bejárásához. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Visszaad egy iterátort, amely a gyűjtemény utolsó elemét (ha van) követően mutat. Ez az iterátor nem használható a hivatkozott objektum módosítására, mert [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) egy T másolat-objektumot ad vissza. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Visszaad egy iterátort, amely a const-kvalifikált példány utolsó elemét (ha van) követően mutat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN semelyik értéknek, köztük NaN-nek sem egyenlő. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN semelyik értéknek, köztük NaN-nek sem egyenlő. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | Visszaad egy [XmlAttributeCollection](../xmlattributecollection/) objektumot, amely ennek a csomópontnak az attribútumait tartalmazza. |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | Visszaad az aktuális csomópont alaptartományát. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | Visszaad a csomópont összes gyermekcsomópontját. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | Visszaad a csomópont első gyermekét. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Visszaad egy **bool** értéket, amely jelzi, hogy az aktuális csomópont rendelkezik-e attribútumokkal. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | Visszaad egy értéket, amely jelzi, hogy ez a csomópont rendelkezik-e gyermekcsomópontokkal. |
| [String](../../system/string/) [get_InnerText](./get_innertext/)() override | Visszaad a csomópont és összes gyermekének összefűzött értékeit. |
| [String](../../system/string/) [get_InnerXml](./get_innerxml/)() override | Visszaad a jelölést, amely csak a csomópont gyermekeit ábrázolja. |
| **bool** [get_IsEmpty](./get_isempty/)() | Visszaad az elem címkeformátumát. |
| virtual **bool** [get_IsReadOnly](../xmlnode/get_isreadonly/)() | Visszaad egy értéket, amely jelzi, hogy a csomópont csak olvasható-e. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | Visszaad a csomópont utolsó gyermekét. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Visszaad az aktuális csomópont helyi nevét. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Visszaad a csomópont minősített nevét. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Visszaad ennek a csomópontnak a névtér-URI-ját. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | Visszaad a csomóponthoz közvetlenül következő csomópontot. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Visszaad az aktuális csomópont típusát. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | Visszaad a jelölést, amely ezt a csomópontot és összes gyermekcsomópontját tartalmazza. |
| [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](./get_ownerdocument/)() override | Visszaad a [XmlDocument](../xmldocument/)-t, amelyhez ez a csomópont tartozik. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | Visszaad ennek a csomópontnak a szülőjét (azoknál a csomópontoknál, amelyeknek lehet szülője). |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Visszaad ennek a csomópontnak a névtér előtagját. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | Visszaad a csomóponthoz közvetlenül megelőző csomópontot. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | Visszaad a szövegcsoportot, amely közvetlenül megelőzi ezt a csomópontot. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Visszaad a sémával való validálás eredményeként a csomópontra rendelt post-séma validációs információkészletet. |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | Visszaadja a csomópont értékét. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | Visszaadja a megadott névű attribútum értékét. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Visszaadja a megadott helyi névű és névtér-URI-jú attribútum értékét. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [GetAttributeNode](./getattributenode/)([String](../../system/string/)) | Visszaadja a megadott névű [XmlAttribute](../xmlattribute/)-t. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [GetAttributeNode](./getattributenode/)([String](../../system/string/), [String](../../system/string/)) | Visszaadja a megadott helyi névű és névtér-URI-jú [XmlAttribute](../xmlattribute/)-t. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekérdezi az objektumhoz tartozó referencia-számláló adatstruktúrát. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/)) | Visszaad egy [XmlNodeList](../xmlnodelist/) objektumot, amely tartalmazza az összes olyan leszármazott elemet, amely megfelel a megadott [XmlElement::get_Name](./get_name/)-nek. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/), [String](../../system/string/)) | Visszaad egy [XmlNodeList](../xmlnodelist/) objektumot, amely tartalmazza az összes olyan leszármazott elemet, amely megfelel a megadott [XmlElement::get_LocalName](./get_localname/) és [XmlElement::get_NamespaceURI](./get_namespaceuri/) értékeknek. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | Visszaad egy enumerátort, amely az aktuális csomópont gyermekcsomópontjain iterál. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | Megkeresi a legközelebbi **xmlns** deklarációt a megadott előtaghoz, amely az aktuális csomópont hatókörében van, és visszaadja a deklarációban szereplő névtér-URI-t. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | Megkeresi a legközelebbi **xmlns** deklarációt a megadott névtér-URI-hoz, amely az aktuális csomópont hatókörében van, és visszaadja a deklarációban definiált előtagot. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekérdezi az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [HasAttribute](./hasattribute/)([String](../../system/string/)) | Megállapítja, hogy az aktuális csomópont rendelkezik-e a megadott névű attribútummal. |
| virtual **bool** [HasAttribute](./hasattribute/)([String](../../system/string/), [String](../../system/string/)) | Megállapítja, hogy az aktuális csomópont rendelkezik-e a megadott helyi névű és névtér-URI-jú attribútummal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](./)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | Visszaad az első gyermekelemet, amely a megadott [XmlNode::get_Name](../xmlnode/get_name/)-t tartalmazza. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](./)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Visszaad az első gyermekelemet, amely a megadott [XmlNode::get_LocalName](../xmlnode/get_localname/) és [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) értékeket tartalmazza. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Beilleszti a megadott csomópontot közvetlenül a megadott hivatkozási csomópont után. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Beilleszti a megadott csomópontot közvetlenül a megadott hivatkozási csomópont előtt. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógiája. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Alkalmaz egy akkumulator függvényt egy sorozaton. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat összes eleme megfelel-e a feltételnek. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Megállapítja, hogy a sorozat tartalmaz-e elemeket. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat bármely eleme létezik-e vagy megfelel-e a feltételnek. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Kiszámítja a numerikus értékek sorozatának átlagát. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Kiszámítja a sorozat értékeinek átlagát, amelyeket a bemeneti sorozat minden elemén egy transzformációs függvény meghívásával érnek el. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Átkonvertálja az elemeket a megadott típusra. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Két sorozatot fűz össze. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Megállapítja, hogy a sorozat tartalmaz-e egy megadott értéket. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálással számítva). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat azon elemeinek számát, amelyek megfelelnek a megadott feltételnek. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat első elemét, amely megfelel a megadott feltételnek. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Visszaadja a sorozat első elemét, amely megfelel egy feltételnek, vagy egy alapértelmezett értéket, ha nincs ilyen elem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Csoportosítja a sorozat elemeit. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Csoportosítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Visszaadja a sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Visszaadja a sorozat utolsó elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Meghív egy transzformációs függvényt a generikus sorozat minden elemén, és visszaadja a legnagyobb eredményértéket. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Meghív egy transzformációs függvényt a generikus sorozat minden elemén, és visszaadja a legkisebb eredményértéket. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Szűri a sorozat elemeit a megadott típus alapján. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Rendezi a sorozat elemeit növekvő sorrendbe a keySelector által kiválasztott kulcsértékek szerint. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Rendezi a sorozat elemeit csökkenő sorrendbe a keySelector által kiválasztott kulcsértékek szerint. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Megfordítja a sorozat elemeinek sorrendjét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Átalakítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Átalakítja a sorozat minden elemét egy új formába, az elem indexének felhasználásával. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Minden elemre egy sorozatot projektál, és az eredményül kapott sorozatokat egy sorozatba egyesíti. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Kihagy egy meghatározott számú egymást követő elemet a sorozat elejéről, és visszaadja a maradékot. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Visszaad egy meghatározott számú egymást követő elemet a sorozat elejéről. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Létrehoz egy tömböt a sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Létrehoz egy List<T>-t a sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Szűri a sorozatot a megadott feltétel alapján. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
| virtual void [Normalize](../xmlnode/normalize/)() | Az összes [XmlText](../xmltext/) csomópontot a [XmlNode](../xmlnode/) alá tartozó részfa teljes mélységében normalizálja, úgy, hogy csak a jelölés (azaz címkék, megjegyzések, feldolgozási instrukciók, CDATA szakaszok és entitás hivatkozások) választja el a [XmlText](../xmltext/) csomópontokat, vagyis nincsenek egymás mellett álló [XmlText](../xmltext/) csomópontok. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi a leszármazott osztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi a leszármazott osztályok másolásos konstrukcióját. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Hozzáadja a megadott csomópontot ennek a csomópontnak a gyermekcsomópontok listájának elejéhez. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciájuk alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciájuk alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata karakterláncokra. |
| void [RemoveAll](./removeall/)() override | Eltávolítja az aktuális csomópont összes megadott attribútumát és gyermekét. Az alapértelmezett attribútumok nem kerülnek eltávolításra. |
| virtual void [RemoveAllAttributes](./removeallattributes/)() | Eltávolítja az elem összes megadott attribútumát. Az alapértelmezett attribútumok nem kerülnek eltávolításra. |
| virtual void [RemoveAttribute](./removeattribute/)([String](../../system/string/)) | Eltávolít egy attribútumot név szerint. |
| virtual void [RemoveAttribute](./removeattribute/)([String](../../system/string/), [String](../../system/string/)) | Eltávolít egy attribútumot a megadott helyi név és névtér URI alapján. (Ha a eltávolított attribútumnak alapértelmezett értéke van, az azonnal helyettesítődik). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveAttributeAt](./removeattributeat/)(**int32_t**) | Eltávolítja a megadott indexű attribútumcsomópontot az elemből. (Ha a eltávolított attribútumnak alapértelmezett értéke van, az azonnal helyettesítődik). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [RemoveAttributeNode](./removeattributenode/)([SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\>) | Eltávolítja a megadott [XmlAttribute](../xmlattribute/)-t. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [RemoveAttributeNode](./removeattributenode/)([String](../../system/string/), [String](../../system/string/)) | Eltávolítja a [XmlAttribute](../xmlattribute/)-t a helyi név és névtér URI alapján. (Ha az eltávolított attribútumnak alapértelmezett értéke van, az azonnal helyettesítődik). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Eltávolítja a megadott gyermekcsomópontot. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Lecseréli a **oldChild** gyermekcsomópontot a **newChild** csomópontra. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | Kiválaszt egy csomópontlistát, amely megfelel a [XPath](../../system.xml.xpath/) kifejezésnek. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Kiválaszt egy csomópontlistát, amely megfelel a [XPath](../../system.xml.xpath/) kifejezésnek. A [XPath](../../system.xml.xpath/) kifejezésben talált előtagok a megadott [XmlNamespaceManager](../xmlnamespacemanager/) segítségével kerülnek feloldásra. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | Kiválasztja az első [XmlNode](../xmlnode/)-t, amely megfelel a [XPath](../../system.xml.xpath/) kifejezésnek. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Kiválasztja az első [XmlNode](../xmlnode/)-t, amely megfelel a [XPath](../../system.xml.xpath/) kifejezésnek. A [XPath](../../system.xml.xpath/) kifejezésben talált előtagok a megadott [XmlNamespaceManager](../xmlnamespacemanager/) segítségével kerülnek feloldásra. |
| void [set_InnerText](./set_innertext/)([String](../../system/string/)) override | Beállítja a csomópont és összes gyermekének összefűzött értékét. |
| void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) override | Beállítja a jelölést, amely csak ennek a csomópontnak a gyermekeit reprezentálja. |
| void [set_IsEmpty](./set_isempty/)(**bool**) | Beállítja az elem címkeformátumát. |
| void [set_Prefix](./set_prefix/)([String](../../system/string/)) override | Beállítja ennek a csomópontnak a névtér előtagját. |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | Beállítja a csomópont értékét. |
| virtual void [SetAttribute](./setattribute/)([String](../../system/string/), [String](../../system/string/)) | Beállítja a megadott névű attribútum értékét. |
| virtual [String](../../system/string/) [SetAttribute](./setattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Beállítja a megadott helyi név és névtér URI alapján az attribútum értékét. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [SetAttributeNode](./setattributenode/)([SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\>) | Hozzáadja a megadott [XmlAttribute](../xmlattribute/)-t. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [SetAttributeNode](./setattributenode/)([String](../../system/string/), [String](../../system/string/)) | Hozzáadja a megadott [XmlAttribute](../xmlattribute/)-t. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonparamétert gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | Megvizsgálja, hogy a DOM megvalósítás támogat-e egy adott funkciót. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Lekéri az aktuális tároló kezdő konstans iterátorának megvalósítását. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Lekéri az aktuális tároló kezdő iterátorának megvalósítását. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Lekéri az aktuális tároló befejező (end) konstans iterátorának megvalósítását. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Lekéri az aktuális tároló befejező (end) iterátorának megvalósítását. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Elmenti a csomópont összes gyermekét a megadott [XmlWriter](../xmlwriter/)-ba. |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Elmenti az aktuális csomópontot a megadott [XmlWriter](../xmlwriter/)-ba. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Egy alias a megosztott mutatóhoz, amely az osztály egy példányát jelöli. |

## Megjegyzések

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## Lásd még

* Osztály [XmlLinkedNode](../xmllinkednode/)
* Névtér [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)