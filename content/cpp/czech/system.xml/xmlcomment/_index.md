---
title: XmlComment
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje obsah XML komentáře.
type: docs
weight: 144
url: /cs/system.xml/xmlcomment/
---
## XmlComment třída

Reprezentuje obsah XML komentáře.

```cpp
class XmlComment : public System::Xml::XmlCharacterData
```

## Metody

| Method | Popis |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Přidá zadaný uzel na konec seznamu podřízených uzlů tohoto uzlu. |
| virtual void [AppendData](../xmlcharacterdata/appenddata/)([String](../../system/string/)) | Přidá zadaný řetězec na konec znakových dat uzlu. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Získá iterátor ukazující na první prvek (pokud existuje) kolekce. Tento iterátor nelze použít ke změně odkazovaného objektu, protože [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) vrací kopii objektu typu T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Získá iterátor ukazující na první prvek (pokud existuje) const-kvalifikované instance kolekce. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Získá iterátor ukazující na první const-kvalifikovaný prvek (pokud existuje) kolekce. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Získá iterátor ukazující těsně za posledním const-kvalifikovaným prvkem (pokud existuje) kolekce. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | Vytvoří duplikát tohoto uzlu. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | Vytvoří duplikát tohoto uzlu. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | Vytvoří XPathNavigator pro procházení tohoto objektu. |
| virtual void [DeleteData](../xmlcharacterdata/deletedata/)(**int32_t**, **int32_t**) | Odstraní rozsah znaků z uzlu. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Získá iterátor ukazující těsně za posledním prvkem (pokud existuje) kolekce. Tento iterátor nelze použít ke změně odkazovaného objektu, protože [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) vrací kopii objektu typu T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Získá iterátor ukazující těsně za posledním prvkem (pokud existuje) const-kvalifikované instance kolekce. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná reference-typové objekty ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná hodnotové typy objektů ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | Vrací [XmlAttributeCollection](../xmlattributecollection/) obsahující atributy tohoto uzlu. |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | Vrací základní URI aktuálního uzlu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | Vrací všechny podřízené uzly uzlu. |
| virtual [String](../../system/string/) [get_Data](../xmlcharacterdata/get_data/)() | Vrací data uzlu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | Vrací první podřízený uzel. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | Vrací hodnotu určující, zda tento uzel má podřízené uzly. |
| [String](../../system/string/) [get_InnerText](../xmlcharacterdata/get_innertext/)() override | Vrací spojené hodnoty uzlu a všech jeho podřízených uzlů. |
| virtual [String](../../system/string/) [get_InnerXml](../xmlnode/get_innerxml/)() | Vrací značkování představující pouze podřízené uzly tohoto uzlu. |
| virtual **bool** [get_IsReadOnly](../xmlnode/get_isreadonly/)() | Vrací hodnotu určující, zda je uzel jen pro čtení. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | Vrací poslední podřízený uzel. |
| virtual **int32_t** [get_Length](../xmlcharacterdata/get_length/)() | Vrací délku dat v počtu znaků. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Vrací lokální název uzlu. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Vrací kvalifikovaný název uzlu. |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | Vrací URI jmenného prostoru tohoto uzlu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | Vrací uzel bezprostředně následující po tomto uzlu. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Vrací typ aktuálního uzlu. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | Vrací značkování obsahující tento uzel a všechny jeho podřízené uzly. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](../xmlnode/get_ownerdocument/)() | Vrací [XmlDocument](../xmldocument/), ke které tento uzel patří. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | Vrací nadřazený uzel (pro uzly, které mohou mít nadřazené). |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | Vrací prefix jmenného prostoru tohoto uzlu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | Vrací uzel bezprostředně předcházející tomuto uzlu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | Vrací textový uzel, který bezprostředně předchází tomuto uzlu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlnode/get_schemainfo/)() | Vrací post-schéma validační infoset přiřazený tomuto uzlu v důsledku schématu validace. |
| [String](../../system/string/) [get_Value](../xmlcharacterdata/get_value/)() override | Vrací hodnotu uzlu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače referencí spojenou s objektem. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | Vrací enumerátor, který iteruje přes podřízené uzly v aktuálním uzlu. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | Vyhledá nejbližší deklaraci **xmlns** pro daný prefix, který je v rozsahu pro aktuální uzel, a vrátí URI jmenného prostoru v deklaraci. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | Vyhledá nejbližší deklaraci **xmlns** pro dané URI jmenného prostoru, který je v rozsahu pro aktuální uzel, a vrátí prefix definovaný v této deklaraci. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie C# [System.Object.GetType()](../../system/object/gettype/) volání. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | Vrací první podřízený prvek s uvedeným [XmlNode::get_Name](../xmlnode/get_name/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Vrací první podřízený prvek s uvedenými hodnotami [XmlNode::get_LocalName](../xmlnode/get_localname/) a [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Vloží zadaný uzel okamžitě za zadaný referenční uzel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Vloží zadaný uzel okamžitě před zadaný referenční uzel. |
| virtual void [InsertData](../xmlcharacterdata/insertdata/)(**int32_t**, [String](../../system/string/)) | Vloží zadaný řetězec na zadaný znakový offset. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ověří, zda objekt představuje instanci typu popsaného targetType. Analogie C# operátoru 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Aplikuje akumulátorovou funkci na sekvenci. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Určuje, zda všechny prvky sekvence splňují podmínku. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Určuje, zda sekvence obsahuje jakékoli prvky. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Určuje, zda existuje prvek sekvence nebo splňuje podmínku. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Vypočítá průměr sekvence číselných hodnot. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Vypočítá průměr sekvence hodnot získaných voláním transformovací funkce na každém prvku vstupní sekvence. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Přetypuje prvky na uvedený typ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Spojí dvě sekvence. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Určuje, zda sekvence obsahuje zadanou hodnotu. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Vrací počet prvků v sekvenci (vypočtený přímým počítáním). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Vrací počet prvků v sekvenci, které splňují zadanou podmínku. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Vrací prvek na zadaném indexu v sekvenci. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Vrací prvek na zadaném indexu v sekvenci. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Vrací první prvek sekvence. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Vrací první prvek sekvence, který splňuje zadanou podmínku. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Vrací první prvek sekvence, nebo výchozí hodnotu, pokud je sekvence prázdná. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Vrací první prvek sekvence, který splňuje podmínku, nebo výchozí hodnotu, pokud takový prvek neexistuje. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Skupinuje prvky sekvence. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Skupinuje prvky sekvence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Vrací poslední prvek sekvence. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Vrací poslední prvek sekvence, nebo výchozí hodnotu, pokud je sekvence prázdná. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Vyvolá transformovací funkci na každém prvku obecné sekvence a vrátí maximální výslednou hodnotu. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Vyvolá transformovací funkci na každém prvku obecné sekvence a vrátí minimální výslednou hodnotu. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtruje prvky sekvence podle zadaného typu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Řadí prvky sekvence ve vzestupném pořadí podle hodnot klíče určených keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Řadí prvky sekvence v sestupném pořadí podle hodnot klíče určených keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Obrátí pořadí prvků v sekvenci. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformuje prvky sekvence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformuje každý prvek sekvence do nové podoby zahrnutím indexu prvku. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projektuje každý prvek sekvence a kombinuje vzniklé sekvence do jedné sekvence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Přeskočí zadaný počet souvislých prvků od začátku sekvence a vrátí zbytek. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Vrací zadaný počet souvislých prvků od začátku sekvence. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Vytvoří pole ze sekvence. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Vytvoří List<T> ze sekvence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtruje sekvenci podle zadané podmínky. |
| void [Lock](../../system/object/lock/)() | Implementuje C# lock() výrok pro zamykání. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
| virtual void [Normalize](../xmlnode/normalize/)() | Umístí všechny [XmlText](../xmltext/) uzly v plné hloubce podstromu pod tímto [XmlNode](../xmlnode/) do „normální“ formy, kde pouze značkování (tzn. tagy, komentáře, instrukce zpracování, sekce CDATA a reference entit) odděluje [XmlText](../xmltext/) uzly, tzn. neexistují sousední [XmlText](../xmltext/) uzly. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Přidá zadaný uzel na začátek seznamu podřízených uzlů pro tento uzel. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovná objekt hodnotového typu s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| virtual void [RemoveAll](../xmlnode/removeall/)() | Odstraní všechny podřízené uzly a/nebo atributy aktuálního uzlu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Odstraní zadaný podřízený uzel. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Nahradí podřízený uzel **oldChild** uzlem **newChild**. |
| virtual void [ReplaceData](../xmlcharacterdata/replacedata/)(**int32_t**, **int32_t**, [String](../../system/string/)) | Nahradí zadaný počet znaků počínaje zadaným offsetem zadaným řetězcem. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | Vybere seznam uzlů odpovídajících výrazu [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Vybere seznam uzlů odpovídajících výrazu [XPath](../../system.xml.xpath/). Všechny prefixy nalezené v výrazu [XPath](../../system.xml.xpath/) jsou rozřešeny pomocí poskytnutého [XmlNamespaceManager](../xmlnamespacemanager/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | Vybere první [XmlNode](../xmlnode/), který odpovídá výrazu [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Vybere první [XmlNode](../xmlnode/), který odpovídá výrazu [XPath](../../system.xml.xpath/). Všechny prefixy nalezené v výrazu [XPath](../../system.xml.xpath/) jsou rozřešeny pomocí poskytnutého [XmlNamespaceManager](../xmlnamespacemanager/). |
| virtual void [set_Data](../xmlcharacterdata/set_data/)([String](../../system/string/)) | Nastaví data uzlu. |
| void [set_InnerText](../xmlcharacterdata/set_innertext/)([String](../../system/string/)) override | Nastaví spojené hodnoty uzlu a všech jeho podřízených uzlů. |
| virtual void [set_InnerXml](../xmlnode/set_innerxml/)([String](../../system/string/)) | Nastaví značkování představující pouze podřízené uzly tohoto uzlu. |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | Nastaví prefix jmenného prostoru tohoto uzlu. |
| void [set_Value](../xmlcharacterdata/set_value/)([String](../../system/string/)) override | Nastaví hodnotu uzlu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý typový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech na slabý režim. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [Substring](../xmlcharacterdata/substring/)(**int32_t**, **int32_t**) | Získá podřetězec z celého řetězce ze zadaného rozsahu. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | Otestuje, zda implementace DOM podporuje konkrétní funkci. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje C# typeof([System.Object](../../system/object/)) konstrukci. |
| void [Unlock](../../system/object/unlock/)() | Implementuje C# lock() výrok pro odemčení. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Získá implementaci begin const iterátoru pro aktuální kontejner. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Získá implementaci begin iterátoru pro aktuální kontejner. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Získá implementaci end const iterátoru pro aktuální kontejner. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Získá implementaci end iterátoru pro aktuální kontejner. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Uloží všechny podřízené uzly do zadaného [XmlWriter](../xmlwriter/). Protože uzly komentáře nemají podřízené, tato metoda nemá žádný účinek. |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Uloží uzel do zadaného [XmlWriter](../xmlwriter/). |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |
## Poznámky

Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. 

## Viz také

* Class [XmlCharacterData](../xmlcharacterdata/)
* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)