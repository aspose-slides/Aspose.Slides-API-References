---
title: SortedList
second_title: Aspose.Slides pro C++ referenční příručku API
description: "Seřazený seznam obalující strukturu FlatMap. Objektů této třídy by měly být alokovány pouze pomocí funkce System::MakeObject() . Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu ukazatelem System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 547
url: /cs/system.collections.generic/sortedlist/
---
## SortedList třída

Seřazený seznam obalující strukturu FlatMap. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu ukazatelem [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
template<typename TKey,typename TValue>class SortedList : public System::Collections::Generic::SortedListHelper<TKey, TValue>,
                                                          public System::Collections::Generic::BaseDictionary<Detail::FlatMap<TKey, TValue, ComparerAdapter<TKey>>>
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TKey | Typ klíče. |
| TValue | Typ hodnoty. |

## Metody

| Metoda | Popis |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey&, const TValue&) | Přidá dvojici klíč-hodnota do kontejneru. |
| virtual void [Add](../icollection/add/)(const T&) | Přidá prvek do kolekce. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Získá iterátor ukazující na první prvek (pokud existuje) kolekce. Tento iterátor nelze použít ke změně referencovaného objektu, protože [GetEnumerator()](../ienumerable/getenumerator/) vrací kopii objektu typu T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Získá iterátor ukazující na první prvek (pokud existuje) instance kolekce s const kvalifikací. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Získá iterátor ukazující na první const-kvalifikovaný prvek (pokud existuje) kolekce. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Získá iterátor ukazující na prvek těsně za posledním const-kvalifikovaným prvkem (pokud existuje) kolekce. |
| virtual void [Clear](../icollection/clear/)() | Odstraní všechny prvky z kolekce. |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | Kontroluje, zda je prvek přítomen v kolekci. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey&) const | Kontroluje, zda kontejner obsahuje klíč. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../keyvaluepair/)<TKey, TValue>>, int) override | Zkopíruje obsah slovníku do existujících prvků pole. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Získá reverzní iterátor na poslední const-kvalifikovaný prvek kolekce (první v obráceném pořadí). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Získá reverzní iterátor na neexistující const-kvalifikovaný prvek před začátkem kolekce. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Získá iterátor ukazující na prvek těsně za posledním (pokud existuje) kolekce. Tento iterátor nelze použít ke změně referencovaného objektu, protože [GetEnumerator()](../ienumerable/getenumerator/) vrací kopii objektu typu T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Získá iterátor ukazující na prvek těsně za posledním (pokud existuje) const-kvalifikovanou instancí kolekce. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Porovná objekty referenčního typu ve stylu C#. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T1>::value&&![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Porovná objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | Emuluje porovnání plovoucího bodu ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | Emuluje porovnání plovoucího bodu ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Pouze pro interní účely. |
| int [get_Capacity](./get_capacity/)() const | Získá aktuální kapacitu seznamu. |
| virtual int [get_Count](../icollection/get_count/)() const | Získá počet prvků v kolekci. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | Kontroluje, zda je velikost kolekce pevná. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Kontroluje, zda je kolekce jen pro čtení. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | Kontroluje, zda je kontejner vláknově bezpečný. |
| virtual [SharedPtr](../../system/sharedptr/)<[IList](../ilist/)<TKey>> [get_Keys](./get_keys/)() const | Přistupuje ke kolekci klíčů. |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | Získá objekt, skrze který je kolekce synchronizována. |
| virtual [SharedPtr](../../system/sharedptr/)<[IList](../ilist/)<TValue>> [get_Values](./get_values/)() const | Přistupuje ke kolekci hodnot. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Získá enumerátor iterující přes aktuální seznam. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&) const | Vrátí hodnotu, pokud je nalezena; jinak **Value()**. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&, const TValue&) const | Vrátí hodnotu, pokud je nalezena; jinak **defaultValue**. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey&) const | Vrátí hodnotu, pokud je nalezena; jinak **null**, má smysl pouze pro referenční typy. |
| [ICollection](../icollection/icollection/)() | Výchozí konstruktor. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | Kopírovací konstruktor. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | Konstruktor přesunu. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey&) const | Funkce getter. |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey&, TValue) | Funkce setter. |
| int [IndexOfKey](./indexofkey/)(TKey) const | Hledá konkrétní klíč. |
| int [IndexOfValue](./indexofvalue/)(TValue) const | Hledá konkrétní hodnotu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | Aplikuje akumulační funkci na sekvenci. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | Určuje, zda všechny prvky sekvence splňují podmínku. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Určuje, zda sekvence obsahuje nějaké prvky. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | Určuje, zda existuje jakýkoli prvek sekvence nebo zda splňuje podmínku. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Vypočítá průměr sekvence číselných hodnot. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | Vypočítá průměr sekvence hodnot získaných voláním transformační funkce na každý prvek vstupní sekvence. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | Přetypuje prvky na zadaný typ. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>) | Spojí dvě sekvence. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Určuje, zda sekvence obsahuje zadanou hodnotu. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Vrátí počet prvků v sekvenci (vypočítáno přímým počítáním). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | Vrátí počet prvků v sekvenci, které splňují zadanou podmínku. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Vrátí prvek na zadaném indexu v sekvenci. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Vrátí prvek na zadaném indexu v sekvenci. |
| T [LINQ_First](../ienumerable/linq_first/)() | Vrátí první prvek sekvence. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | Vrátí první prvek sekvence, který splňuje zadanou podmínku. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Vrátí první prvek sekvence, nebo výchozí hodnotu, pokud je sekvence prázdná. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | Vrátí první prvek sekvence, který splňuje podmínku, nebo výchozí hodnotu, pokud takový prvek není nalezen. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | Seskupí prvky sekvence. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | Seskupí prvky sekvence. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Vrátí poslední prvek sekvence. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Vrátí poslední prvek sekvence, nebo výchozí hodnotu, pokud je sekvence prázdná. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | Vyvolá transformační funkci na každém prvku obecné sekvence a vrátí maximální výslednou hodnotu. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | Vyvolá transformační funkci na každém prvku obecné sekvence a vrátí minimální výslednou hodnotu. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtruje prvky sekvence podle zadaného typu. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | Řadí prvky sekvence vzestupně podle hodnot klíčů vybraných funkcí keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | Řadí prvky sekvence sestupně podle hodnot klíčů vybraných funkcí keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Obrátí pořadí prvků v sekvenci. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | Transformuje prvky sekvence. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | Transformuje každý prvek sekvence do nové podoby zahrnutím indexu prvku. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> &) | Projektuje každý prvek sekvence a kombinuje výsledné sekvence do jedné sekvence. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Přeskočí zadaný počet sousledných prvků od začátku sekvence a vrátí zbytek. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Vrátí zadaný počet sousledných prvků od začátku sekvence. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Vytvoří pole ze sekvence. |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | Vytvoří List<T> ze sekvence. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | Filtruje sekvenci na základě zadaného predikátu. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | Operátor přiřazení přesunu. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | Operátor přiřazení přesunu. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Získá reverzní iterátor na poslední prvek kolekce (první v opačném směru). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Získá reverzní iterátor na poslední prvek const-kvalifikované kolekce (první v opačném směru). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Porovná objekty podle reference. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Porovná objekty podle reference. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Porovná referenčně objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey&) | Odstraní klíč z kontejneru. |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | Odstraní prvek z kolekce. |
| void [RemoveAt](./removeat/)(int) | Odstraní položku na zadané pozici. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Získá reverzní iterátor na neexistující prvek před začátkem kolekce. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Získá reverzní iterátor na neexistující prvek před začátkem const-kvalifikované kolekce. |
| void [set_Capacity](./set_capacity/)(int) | Nastaví aktuální kapacitu seznamu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do režimu slabých ukazatelů. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| [SortedList](./sortedlist/)() | Vytvoří prázdný seznam. |
| [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<TKey>>) | Vytvoří prázdný seznam. |
| [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>) | Kopírovací konstruktor. |
| [SortedList](./sortedlist/)(const [map_t](./map_t/)&) | Kopírovací konstruktor. |
| [SortedList](./sortedlist/)(int) | Vytvoří prázdný seznam. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey&, TValue&) const | Hledá hodnotu a získá ji, pokud je nalezena. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Získá implementaci begin const iterátoru pro aktuální kontejner. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Získá implementaci begin iterátoru pro aktuální kontejner. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Získá implementaci end const iterátoru pro aktuální kontejner. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Získá implementaci end iterátoru pro aktuální kontejner. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| virtual [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [KeyCollection](./keycollection/) | Typ kolekce klíčů. |
| [ValueCollection](./valuecollection/) | Typ kolekce hodnot. |
| [map_t](./map_t/) | Základní datový typ. |
| [this_t](./this_t/) | Tento typ. |
| [Ptr](./ptr/) | Typ ukazatele. |
| [KVPair](./kvpair/) | Typ dvojice klíč-hodnota. |
| [IEnumerablePtr](./ienumerableptr/) | Typ kolekce stejných dvojic. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** typ. |
| [iterator](./iterator/) | Typ iterátoru. |
| [const_iterator](./const_iterator/) | Typ const iterátoru. |
| [reverse_iterator](./reverse_iterator/) | Typ reverzního iterátoru. |
| [const_reverse_iterator](./const_reverse_iterator/) | Typ const reverzního iterátoru. |

## Viz také

* Třída [SortedListHelper](../sortedlisthelper/)
* Třída [BaseDictionary](../basedictionary/)
* Jmenný prostor [System::Collections::Generic](../)
* Knihovna [Aspose.Slides](../../)