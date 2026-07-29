---
title: XmlCDataSection
second_title: Aspose.Slides för C++ API-referens
description: Representerar en CDATA-sektion.
type: docs
weight: 105
url: /sv/system.xml/xmlcdatasection/
---
## XmlCDataSection klass

Representerar en CDATA-sektion.

```cpp
class XmlCDataSection : public System::Xml::XmlCharacterData
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Lägger till den angivna noden i slutet av listan med undernoder för denna nod. |
| virtual void [AppendData](../xmlcharacterdata/appenddata/)([String](../../system/string/)) | Lägger till den angivna strängen i slutet av teckendata för noden. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Hämtar en iterator som pekar på det första elementet (om något) i samlingen. Denna iterator kan inte användas för att ändra ett refererat objekt eftersom [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) returnerar ett kopierat objekt av T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Hämtar en iterator som pekar på det första elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Hämtar en iterator som pekar på det första konstantkvalificerade elementet (om något) i samlingen. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Hämtar en iterator som pekar direkt efter det sista konstantkvalificerade elementet (om något) i samlingen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | Skapar en duplikat av denna nod. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | Skapar en duplikat av denna nod. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | Skapar en XPathNavigator för att navigera i detta objekt. |
| virtual void [DeleteData](../xmlcharacterdata/deletedata/)(**int32_t**, **int32_t**) | Tar bort ett intervall av tecken från noden. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Hämtar en iterator som pekar direkt efter det sista elementet (om något) i samlingen. Denna iterator kan inte användas för att ändra ett refererat objekt eftersom [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) returnerar ett kopierat objekt av T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Hämtar en iterator som pekar direkt efter det sista elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | Returnerar en [XmlAttributeCollection](../xmlattributecollection/) som innehåller attributen för denna nod. |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | Returnerar bas-URI för den aktuella noden. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | Returnerar alla undernoder till noden. |
| virtual [String](../../system/string/) [get_Data](../xmlcharacterdata/get_data/)() | Returnerar nodens data. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | Returnerar den första undernoden till noden. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | Returnerar ett värde som indikerar om denna nod har några undernoder. |
| [String](../../system/string/) [get_InnerText](../xmlcharacterdata/get_innertext/)() override | Returnerar de sammanslagna värdena för noden och alla dess undernoder. |
| virtual [String](../../system/string/) [get_InnerXml](../xmlnode/get_innerxml/)() | Returnerar markup som endast representerar nodens undernoder. |
| virtual **bool** [get_IsReadOnly](../xmlnode/get_isreadonly/)() | Returnerar ett värde som indikerar om noden är skrivskyddad. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | Returnerar den sista undernoden till noden. |
| virtual **int32_t** [get_Length](../xmlcharacterdata/get_length/)() | Returnerar datans längd i tecken. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på noden. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på noden. |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | Returnerar namnrymdens URI för denna nod. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | Returnerar noden som omedelbart följer denna nod. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Returnerar typen av den aktuella noden. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | Returnerar markup som innehåller denna nod och alla dess undernoder. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](../xmlnode/get_ownerdocument/)() | Returnerar den [XmlDocument](../xmldocument/) som denna nod tillhör. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | Returnerar föräldern till denna nod (för noder som kan ha föräldrar). |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | Returnerar namnrymdsprfixen för denna nod. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | Returnerar noden som omedelbart föregår denna nod. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](./get_previoustext/)() override | Returnerar textnoden som omedelbart föregår denna nod. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlnode/get_schemainfo/)() | Returnerar post-schema-validerings-infosätt som har tilldelats denna nod som ett resultat av schema-validering. |
| [String](../../system/string/) [get_Value](../xmlcharacterdata/get_value/)() override | Returnerar nodens värde. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är kopplad till objektet. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | Returnerar en enumerator som itererar genom undernoderna i den aktuella noden. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av egna objekt. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | Söker upp den närmaste **xmlns**-deklarationen för den angivna prefixen som är i räckhåll för den aktuella noden och returnerar namnrymdens URI i deklarationen. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | Söker upp den närmaste **xmlns**-deklarationen för den angivna namnrymds-URI:n som är i räckhåll för den aktuella noden och returnerar prefixet som definierats i den deklarationen. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska objektets typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | Returnerar det första underelementet med det angivna [XmlNode::get_Name](../xmlnode/get_name/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Returnerar det första underelementet med de angivna [XmlNode::get_LocalName](../xmlnode/get_localname/)- och [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/)-värdena. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Infogar den angivna noden direkt efter den angivna referensnoden. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Infogar den angivna noden direkt före den angivna referensnoden. |
| virtual void [InsertData](../xmlcharacterdata/insertdata/)(**int32_t**, [String](../../system/string/)) | Infogar den angivna strängen på den angivna teckenoffseten. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Tillämpar en ackumulatorfunktion över en sekvens. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Avgör om alla element i en sekvens uppfyller ett villkor. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Avgör om en sekvens innehåller några element. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Avgör om något element i en sekvens finns eller uppfyller ett villkor. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Beräknar medelvärdet av en sekvens av numeriska värden. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Beräknar medelvärdet av en sekvens av värden som erhålls genom att anropa en transformfunktion på varje element i ingångssekvensen. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Kastar elementen till den angivna typen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Konkatenar två sekvenser. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Avgör om en sekvens innehåller ett angivet värde. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Returnerar antalet element i sekvensen (beräknat genom direkt uppräkning). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Returnerar antalet element i sekvensen som uppfyller det angivna villkoret. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Returnerar elementet på ett angivet index i en sekvens. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Returnerar elementet på ett angivet index i en sekvens. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Returnerar det första elementet i en sekvens. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Returnerar det första elementet i en sekvens som uppfyller det angivna villkoret. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Returnerar det första elementet i en sekvens, eller ett standardvärde om sekvensen är tom. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Returnerar det första elementet i sekvensen som uppfyller ett villkor eller ett standardvärde om inget sådant element hittas. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Grupperar elementen i en sekvens. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Grupperar elementen i en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Returnerar det sista elementet i en sekvens. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Returnerar det sista elementet i en sekvens, eller ett standardvärde om sekvensen är tom. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Anropar en transformfunktion på varje element i en generell sekvens och returnerar det maximala resulterande värdet. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Anropar en transformfunktion på varje element i en generell sekvens och returnerar det minsta resulterande värdet. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtrerar elementen i sekvensen baserat på den angivna typen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorterar elementen i en sekvens i stigande ordning enligt nyckelvärdena som valts av keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorterar elementen i en sekvens i fallande ordning enligt nyckelvärdena som valts av keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Vänder på ordningen av elementen i en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformerar element i en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformerar varje element i en sekvens till en ny form genom att införliva elementets index. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projicerar varje element i en sekvens och kombinerar de resulterande sekvenserna till en enda sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Hoppar över ett angivet antal intilliggande element från början av en sekvens och returnerar resten. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Returnerar ett angivet antal intilliggande element från början av en sekvens. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Skapar en array från en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Skapar en List<T> från en sekvens. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtrerar en sekvens baserat på det angivna predikatet. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av egna typer. |
| virtual void [Normalize](../xmlnode/normalize/)() | Sätter alla [XmlText](../xmltext/)-noder i hela djupet av delträdet under denna [XmlNode](../xmlnode/) i ett "normalt" format där endast markup (det vill säga taggar, kommentarer, processinstruktioner, CDATA-sektioner och entitetsreferenser) separerar [XmlText](../xmltext/)-noder, det vill säga, det finns inga intilliggande [XmlText](../xmltext/)-noder. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopierande konstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopierande konstruktion av underklasser. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Lägger till den angivna noden i början av listan med undernoder för denna nod. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens av värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| virtual void [RemoveAll](../xmlnode/removeall/)() | Tar bort alla undernoder och/eller attribut för den aktuella noden. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Tar bort angiven undernod. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Ersätter undernoden **oldChild** med **newChild**-noden. |
| virtual void [ReplaceData](../xmlcharacterdata/replacedata/)(**int32_t**, **int32_t**, [String](../../system/string/)) | Ersätter det angivna antalet tecken med början vid den angivna offseten med den angivna strängen. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | Väljer en lista med noder som matchar [XPath](../../system.xml.xpath/)-uttrycket. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Väljer en lista med noder som matchar [XPath](../../system.xml.xpath/)-uttrycket. Alla prefix som finns i [XPath](../../system.xml.xpath/)-uttrycket löses upp med den angivna [XmlNamespaceManager](../xmlnamespacemanager/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | Väljer den första [XmlNode](../xmlnode/) som matchar [XPath](../../system.xml.xpath/)-uttrycket. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Väljer den första [XmlNode](../xmlnode/) som matchar [XPath](../../system.xml.xpath/)-uttrycket. Alla prefix som finns i [XPath](../../system.xml.xpath/)-uttrycket löses upp med den angivna [XmlNamespaceManager](../xmlnamespacemanager/). |
| virtual void [set_Data](../xmlcharacterdata/set_data/)([String](../../system/string/)) | Sätter nodens data. |
| void [set_InnerText](../xmlcharacterdata/set_innertext/)([String](../../system/string/)) override | Sätter de sammanslagna värdena för noden och alla dess undernoder. |
| virtual void [set_InnerXml](../xmlnode/set_innerxml/)([String](../../system/string/)) | Sätter markup som endast representerar nodens undernoder. |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | Sätter namnrymdsprfixen för denna nod. |
| void [set_Value](../xmlcharacterdata/set_value/)([String](../../system/string/)) override | Sätter nodens värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n-te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [Substring](../xmlcharacterdata/substring/)(**int32_t**, **int32_t**) | Hämtar en delsträng av hela strängen från det angivna intervallet. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | Testar om DOM-implementeringen implementerar en specifik funktion. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av egna objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Hämtar implementeringen av begin-konst-iterator för den aktuella behållaren. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Hämtar implementeringen av begin-iterator för den aktuella behållaren. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Hämtar implementeringen av end-konst-iterator för den aktuella behållaren. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Hämtar implementeringen av end-iterator för den aktuella behållaren. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Sparar nodens undernoder till den angivna [XmlWriter](../xmlwriter/). |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Sparar noden till den angivna [XmlWriter](../xmlwriter/). |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigir alla interna datastrukturer. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för delad pekare till en instans av denna klass. |

## Anmärkningar

Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller assert-fel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument. 

## Se även

* Klass [XmlCharacterData](../xmlcharacterdata/)
* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)