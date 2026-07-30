---
title: SortedDictionary
second_title: Aspose.Slides pro C++ - reference API
description: Deklarace typu seřazeného slovníku.
type: docs
weight: 521
url: /cs/system.collections.generic/sorteddictionary/
---
## SortedDictionary třída

Deklarace typu seřazeného slovníku.

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
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
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Získá iterátor ukazující na první prvek (pokud existuje) kolekce. Tento iterátor nelze použít ke změně odkazovaného objektu, protože [GetEnumerator()](../ienumerable/getenumerator/) vrací kopii objektu typu T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Získá iterátor ukazující na první prvek (pokud existuje) konstantní instance kolekce. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Získá iterátor ukazující na první konstantní prvek (pokud existuje) kolekce. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Získá iterátor ukazující těsně za posledním konstantním prvkem (pokud existuje) kolekce. |
| virtual void [Clear](../icollection/clear/)() | Odstraní všechny prvky z kolekce. |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | Kontroluje, zda je prvek přítomen v kolekci. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey&) const | Kontroluje, zda kontejner obsahuje klíč. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../keyvaluepair/)<TKey, TValue>>, int) override | Zkopíruje obsah slovníku do existujících prvků pole. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Získá reverzní iterátor na poslední konstantní prvek kolekce (první v reverzním pořadí). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Získá reverzní iterátor na neexistující konstantní prvek před začátkem kolekce. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Získá iterátor ukazující těsně za posledním prvkem (pokud existuje) kolekce. Tento iterátor nelze použít ke změně odkazovaného objektu, protože [GetEnumerator()](../ienumerable/getenumerator/) vrací kopii objektu typu T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Získá iterátor ukazující těsně za posledním prvkem (pokud existuje) konstantní instance kolekce. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T1>::value&&\![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | Emuluje porovnání s dvojitou přesností (double) ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Pouze pro interní použití. |
| [SharedPtr](../../system/sharedptr/)<[System::Collections::Generic::IComparer](../icomparer/)<TKey>> [get_Comparer](./get_comparer/)() const | Získá IComparer<TKey> používaný k řazení prvků SortedDictionary<TKey,TValue>. |
| virtual int [get_Count](../icollection/get_count/)() const | Získá počet prvků v kolekci. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | Kontroluje, zda je velikost kolekce pevná. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Kontroluje, zda je kolekce pouze pro čtení. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | Kontroluje, zda je kontejner bezpečný pro více vláken. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TKey>> [get_Keys](../idictionary/get_keys/)() const | Přistupuje ke kolekci klíčů. |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | Získá objekt, přes který je kolekce synchronizována. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TValue>> [get_Values](../idictionary/get_values/)() const | Přistupuje ke kolekci hodnot. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| static [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>> [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | Funkce přístupu k jedinečné instanci (singleton). |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Získá enumerátor pro iteraci přes aktuální slovník. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&) const | Vrátí hodnotu, pokud je nalezena; jinak **Value()**. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&, const TValue&) const | Vrátí hodnotu, pokud je nalezena; jinak **defaultValue**. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey&) const | Vrátí hodnotu, pokud je nalezena; jinak **null**, má smysl jen pro referenční typy. |
|  [ICollection](../icollection/icollection/)() | Výchozí konstruktor. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | Kopírovací konstruktor. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | Konstruktor přesunu. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey&) const | Funkce pro získání hodnoty (getter). |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey&, TValue) | Funkce pro nastavení hodnoty (setter). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | Aplikuje akumulátorovou funkci na sekvenci. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | Určuje, zda všechny prvky sekvence splňují podmínku. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Určuje, zda sekvence obsahuje nějaké prvky. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | Určuje, zda existuje libovolný prvek sekvence nebo splňuje podmínku. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Vypočítá průměr sekvence číselných hodnot. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | Vypočítá průměr sekvence hodnot získaných voláním transformační funkce na každý prvek vstupní sekvence. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | Přetypuje prvky na zadaný typ. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>) | Spojí dvě sekvence. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Určuje, zda sekvence obsahuje specifikovanou hodnotu. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Vrátí počet prvků v sekvenci (vypočítáno přímým počítáním). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | Vrátí počet prvků v sekvenci, které splňují zadanou podmínku. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Vrátí prvek na určeném indexu v sekvenci. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Vrátí prvek na určeném indexu v sekvenci. |
| T [LINQ_First](../ienumerable/linq_first/)() | Vrátí první prvek sekvence. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | Vrátí první prvek sekvence, který splňuje zadanou podmínku. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Vrátí první prvek sekvence, nebo výchozí hodnotu, pokud je sekvence prázdná. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | Vrátí první prvek sekvence, který splňuje podmínku, nebo výchozí hodnotu, pokud takový prvek neexistuje. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | Skupinuje prvky sekvence. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | Skupinuje prvky sekvence. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Vrátí poslední prvek sekvence. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Vrátí poslední prvek sekvence, nebo výchozí hodnotu, pokud je sekvence prázdná. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | Vyvolá transformační funkci pro každý prvek obecné sekvence a vrátí maximální vzniklou hodnotu. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | Vyvolá transformační funkci pro každý prvek obecné sekvence a vrátí minimální vzniklou hodnotu. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtruje prvky sekvence podle zadaného typu. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | Řadí prvky sekvence vzestupně podle hodnot klíčů vybraných pomocí keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | Řadí prvky sekvence sestupně podle hodnot klíčů vybraných pomocí keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Obrátí pořadí prvků v sekvenci. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | Transformuje prvky sekvence. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | Transformuje každý prvek sekvence do nové podoby za použití indexu prvku. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> &) | Projektuje každý prvek sekvence a kombinuje vzniklé sekvence do jedné sekvence. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Přeskočí zadaný počet sousedních prvků od začátku sekvence a vrátí zbytek. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Vrátí zadaný počet sousedních prvků od začátku sekvence. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Vytvoří pole ze sekvence. |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | Vytvoří List<T> ze sekvence. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | Filtruje sekvenci podle zadaného predikátu. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | Operátor přiřazení přesunu. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | Operátor přiřazení přesunu. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Získá reverzní iterátor na poslední prvek kolekce (první v reverzním pořadí). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Získá reverzní iterátor na poslední prvek konstantní kolekce (první v reverzním pořadí). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey&) | Odstraní klíč z kontejneru. |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | Odstraní prvek z kolekce. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Získá reverzní iterátor na neexistující prvek před začátkem kolekce. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Získá reverzní iterátor na neexistující prvek před začátkem konstantní kolekce. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
|  [SortedDictionary](./sorteddictionary/)() | Vytvoří prázdný slovník. |
|  [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>>&) | Vytvoří prázdný slovník. |
|  [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>&) | Kopírovací konstruktor. |
|  [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>&, const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>>&) | Kopírovací konstruktor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey&, TValue&) const | Hledá hodnotu a získá ji, pokud je nalezena. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Získá implementaci začátku konstantního iterátoru pro aktuální kontejner. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Získá implementaci začátku iterátoru pro aktuální kontejner. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Získá implementaci konce konstantního iterátoru pro aktuální kontejner. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Získá implementaci konce iterátoru pro aktuální kontejner. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Definice typů

| Typedef | Popis |
| --- | --- |
| [KeyCollection](./keycollection/) | Typ kolekce klíčů. |
| [ValueCollection](./valuecollection/) | Typ kolekce hodnot. |
| [map_t](./map_t/) | Základní datový typ. |
| [this_t](./this_t/) | Typ vlastního objektu. |
| [Ptr](./ptr/) | Typ ukazatele. |
| [KVPair](./kvpair/) | Typ páru klíč-hodnota. |
| [IEnumerablePtr](./ienumerableptr/) | Kolekce stejných prvků. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** typ. |
| [iterator](./iterator/) | Typ iterátoru. |
| [const_iterator](./const_iterator/) | Typ konstantního iterátoru. |
| [reverse_iterator](./reverse_iterator/) | Typ reverzního iterátoru. |
| [const_reverse_iterator](./const_reverse_iterator/) | Typ konstantního reverzního iterátoru. |

## Poznámky

Třída SortedDictionary, která obaluje STL map. Objektů této třídy by se měly alokovat pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám během běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a používejte tento ukazatel k předávání jako argument funkcím.

## Viz také

* Třída [BaseDictionary](../basedictionary/)
* Jmenný prostor [System::Collections::Generic](../)
* Knihovna [Aspose.Slides](../../)