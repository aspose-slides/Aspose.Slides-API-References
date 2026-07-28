---
title: ListExt
second_title: Aspose.Slides C++ API referencia
description: általános List osztály, amely megvalósítja az IListWrapper interfészt
type: docs
weight: 443
url: /hu/system.collections.generic/listext/
---
## ListExt osztály


generic [List](../list/) osztály that implements [IListWrapper](../../system.collections/ilistwrapper/) interfész

```cpp
template<typename T>class ListExt : public System::Collections::Generic::List<T>,
                                    public System::Collections::IListWrapper
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| void [_add_range](../list/_add_range/)(std::initializer_list\<T\>) | C++ specifikus. |
| void [Add](../list/add/)(const T\&) override | Elemet ad hozzá a lista végéhez. |
| void [AddInitializer](../list/addinitializer/)(int, const T *) | Elemeket ad hozzá a listához; inicializálók lefordításakor használják. |
| void [AddRange](../list/addrange/)([IEnumerablePtr](../list/ienumerableptr/)) | Az összes elemet a gyűjteményből (vagy önmagából) hozzáadja az aktuális lista végéhez. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../list/asreadonly/)() | Lekéri a csak-olvasásra szóló referenciát ehhez a gyűjteményhez. |
| [iterator](../ienumerable/iterator/) [begin](../list/begin/)() | Lekéri az iterátort a gyűjtemény első eleméhez. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../list/begin/)() const | Lekéri az iterátort a const-képes gyűjtemény első eleméhez. |
| int [BinarySearch](../list/binarysearch/)(const T\&) const | Elemet keres egy rendezett listában. |
| int [BinarySearch](../list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Elemet keres egy rendezett listában. |
| int [BinarySearch](../list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Elemet keres egy rendezett listában. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../list/cbegin/)() const | Lekéri az iterátort a gyűjtemény első const-képes eleméhez. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../list/cend/)() const | Lekéri az iterátort egy nem létező const-képes elemhez, amely a gyűjtemény vége mögött található. |
| void [Clear](../list/clear/)() override | Törli az összes elemet. |
| **bool** [Contains](../list/contains/)(const T\&) const override | Ellenőrzi, hogy az elem jelen van-e a listában. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<OutputType\>\> [ConvertAll](../list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Létrehoz egy listát az elemekből, amelyek más típusra vannak konvertálva. |
| void [CopyTo](../list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Másolja a listaelemeket meglévő tömb elemeibe. |
| void [CopyTo](../list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Az összes elemet meglévő tömb elemeibe másolja. |
| void [CopyTo](../list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Az elemeket a megadott indextől kezdődően meglévő tömb elemeibe másolja. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crbegin](../list/crbegin/)() const | Lekéri a fordított iterátort a gyűjtemény utolsó const-képes eleméhez (az első a fordított sorrendben). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CreateIListWrapper](./createilistwrapper/)() override | [IListWrapper](../../system.collections/ilistwrapper/) interfész megvalósítása. |
| std::enable_if\<[System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) implementációs segédreferenciatípusokhoz. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[System::IsBoxable](../../system/isboxable/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) implementációs segéd az értéktípusokhoz. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![System::IsBoxable](../../system/isboxable/)\<T\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) implementációs segéd más típusokhoz. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crend](../list/crend/)() const | Lekéri a fordított iterátort egy nem létező const-képes elemhez a gyűjtemény eleje előtt. |
| [vector_t](../list/vector_t/)\& [data](../list/data/)() | Az alapul szolgáló adatstruktúra hozzáférési függvénye. |
| const [vector_t](../list/vector_t/)\& [data](../list/data/)() const | Az alapul szolgáló adatstruktúra hozzáférési függvénye. |
| [iterator](../ienumerable/iterator/) [end](../list/end/)() | Lekéri az iterátort egy nem létező elemhez, amely a gyűjtemény vége mögött van. |
| [const_iterator](../ienumerable/const_iterator/) [end](../list/end/)() const | Lekéri az iterátort egy nem létező elemhez, amely a const-képes gyűjtemény vége mögött van. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít a C# [Object.Equals](../../system/object/equals/) szemantikai szabályok szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| **bool** [Exists](../list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Ellenőrzi, hogy létezik-e olyan elem a listában, amely megfelel a megadott feltételnek. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| T [Find](../list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Keresi a megadott feltételnek megfelelő elemet. |
| [ListPtr](../listptr/)\<T\> [FindAll](../list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Keresi a megadott feltételnek megfelelő elemeket. |
| int [FindIndex](../list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Keresi a megadott feltételnek megfelelő elemet. |
| int [FindIndex](../list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Keresi a megadott feltételnek megfelelő elemet. |
| int [FindIndex](../list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Keresi a megadott feltételnek megfelelő elemet. |
| T [FindLast](../list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Keresi az utolsó elemet, amely megfelel a megadott feltételnek. |
| void [ForEach](../list/foreach/)([System::Action](../../system/action/)\<T\>) | Minden elemre a listában alkalmaz egy műveletet. |
| int [get_Capacity](../list/get_capacity/)() const | Lekéri a lista jelenlegi kapacitását. |
| int [get_Count](../list/get_count/)() const override | Lekéri az aktuális lista elemeinek számát. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Ellenőrzi, hogy a gyűjmentény fix méretű-e. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Ellenőrzi, hogy a gyűjtemény csak olvasható-e. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Lekéri azt az objektumot, amelyen keresztül a gyűjtemény szinkronizálva van. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri a objektumhoz társított referencia számláló adatstruktúrát. |
| [IEnumeratorPtr](../list/ienumeratorptr/) [GetEnumerator](../list/getenumerator/)() override | Lekéri az enumerátort, amellyel a listaelemeket bejárhatja. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| **ThisPtr** [GetRange](../list/getrange/)(int, int) | Lista szeletet hoz létre. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum valós típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
|  [ICollection](../icollection/icollection/)() | Alapértelmezett konstruktor. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Másoló konstruktor. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Mozgató konstruktor. |
| T [idx_get](../list/idx_get/)(int) const override | Lekéri az elemet egy adott pozíción. |
| void [idx_set](../list/idx_set/)(int, T) override | Beállítja az elemet egy adott pozíción. |
| int [IndexOf](../list/indexof/)(const T\&) const override | Lekéri egy adott elem első indexét. |
| int [IndexOf](../list/indexof/)(const T\&, int) const | Keres egy adott elemet a listában. |
| void [Insert](../list/insert/)(int, const T\&) override | Beszúr egy elemet a megadott pozícióba. |
| void [InsertRange](../list/insertrange/)(int, [IEnumerablePtr](../list/ienumerableptr/)) | Adattartományt szúr be egy adott pozícióba. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példány-e a targetType által leírt típusból. A C# 'is' operátor analógja. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&) const | Megkeresi a megadott objektumot, és visszaadja a nulla-alapú indexet az utolsó előfordulásnak az egész listában. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**) const | Megkeresi a megadott objektumot, és visszaadja a nulla-alapú indexet az utolsó előfordulásnak a [List](../list/) elemeinek tartományában, amely az első elemtől a megadott indexig terjed. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Megkeresi a megadott objektumot, és visszaadja a nulla-alapú indexet az utolsó előfordulásnak a [List](../list/) elemeinek tartományában, amely a megadott számú elemet tartalmazza és a megadott indexnél ér véget. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Akkumulátor függvényt alkalmaz egy sorozatra. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat minden eleme megfelel-e a feltételnek. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Megállapítja, hogy a sorozat tartalmaz-e elemeket. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat bármely eleme létezik-e vagy megfelel-e egy feltételnek. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Kiszámítja egy numerikus értékek sorozatának átlagát. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Kiszámítja egy értéksorozat átlagát, amelyet a bemeneti sorozat minden elemére alkalmazott transzformáló függvény eredményez. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Átkonvertálja az elemeket a megadott típusra. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Összefűzi a két sorozatot. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Megállapítja, hogy a sorozat tartalmaz-e egy megadott értéket. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálással kiszámítva). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat elemeinek számát, amelyek megfelelnek a megadott feltételnek. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_First](../ienumerable/linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat első olyan elemét, amely megfelel a megadott feltételnek. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Visszaadja a sorozat első olyan elemét, amely teljesíti a feltételt, vagy alapértelmezett értéket, ha nincs ilyen elem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Csoportosítja a sorozat elemeit. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Csoportosítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Visszaadja a sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Visszaadja a sorozat utolsó elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden egyes elemre egy általános sorozaton egy transzformáló függvényt hív meg, és visszaadja a legnagyobb eredményértéket. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden egyes elemre egy általános sorozaton egy transzformáló függvényt hív meg, és visszaadja a legkisebb eredményértéket. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Szűri a sorozat elemeit a megadott típus alapján. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Rendezi a sorozat elemeit növekvő sorrendben a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Rendezi a sorozat elemeit csökkenő sorrendben a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Megfordítja egy sorozat elemeinek sorrendjét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Átalakítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Minden sorozat elemet egy új formába alakít át, az elem indexét felhasználva. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projekcióval egyesíti a sorozat elemeit, és a kapott sorozatokat egyetlen sorozattá fűzi. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Kihagy egy meghatározott számú egymást követő elemet a sorozat elejéről, és visszaadja a maradékot. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Visszaad egy meghatározott számú egymást követő elemet a sorozat elejéről. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Tömböt hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | List<T>-t hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Szűri a sorozatot a megadott predikátum alapján. |
|  [List](../list/list/)() | Üres listát hoz létre. |
|  [List](../list/list/)(int) | Listát hoz létre előre meghatározott kapacitással. |
|  [List](../list/list/)([IEnumerablePtr](../list/ienumerableptr/)) | Másoló konstruktor. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást zároláshoz. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Mozgató értékadó operátor. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Mozgató értékadó operátor. |
| vector_t::reference [operator[]](../list/operator[]/)(int) | Elérőfüggvény. |
| vector_t::const_reference [operator[]](../list/operator[]/)(int) const | Elérőfüggvény. |
| [reverse_iterator](../list/reverse_iterator/) [rbegin](../list/rbegin/)() | Lekéri a fordított iterátort a gyűjtemény utolsó eleméhez (az első a fordított sorrendben). |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rbegin](../list/rbegin/)() const | Lekéri a fordított iterátort a const-képes gyűjtemény utolsó eleméhez (az első a fordított sorrendben). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja az értéktípusú objektumot a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| **bool** [Remove](../list/remove/)(const T\&) override | Eltávolítja a lista első előfordulását egy adott elemnek. |
| int [RemoveAll](../list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Eltávolít minden olyan elemet, amely megfelel a megadott feltételnek. |
| void [RemoveAt](../list/removeat/)(int) override | Eltávolít egy elemet a megadott pozícióban. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámot a megadott értékkel. |
| void [RemoveRange](../list/removerange/)(int, int) | Eltávolít egy szeletet a listából. |
| [reverse_iterator](../list/reverse_iterator/) [rend](../list/rend/)() | Lekéri a fordított iterátort egy nem létező elemhez a gyűjtemény eleje előtt. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rend](../list/rend/)() const | Lekéri a fordított iterátort egy nem létező elemhez a const-képes gyűjtemény eleje előtt. |
| void [Reverse](../list/reverse/)() | Megfordítja az egész lista elemeinek sorrendjét. |
| void [Reverse](../list/reverse/)(int, int) | Megfordítja a lista szelet elemeinek sorrendjét. |
| void [set_Capacity](../list/set_capacity/)(int) | Beállítja a lista kapacitását. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá állítja (a megosztott helyett). Lehetővé teszi a konténerekben lévő mutatók gyenge módra való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Sort](../list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Rendezi a lista elemeit. |
| void [Sort](../list/sort/)() | Alapértelmezett összehasonlítóval rendezi a lista elemeit. |
| void [Sort](../list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Rendezi a lista szelet elemeit. |
| void [Sort](../list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Rendezi a lista elemeit. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../list/toarray/)() const | Átalakítja a listát tömbbé. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| void [TrimExcess](../list/trimexcess/)() | A lista kapacitását a méretéhez igazítja. |
| **bool** [TrueForAll](../list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Megállapítja, hogy a gyűjtemény minden eleme megfelel-e a megadott predikátum feltételeinek. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../list/virtualizebeginconstiterator/)() const override | Lekéri a begin const iterátor megvalósítását a jelenlegi tárolóhoz. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../list/virtualizebeginiterator/)() override | Lekéri a begin iterátor megvalósítását a jelenlegi tárolóhoz. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../list/virtualizeendconstiterator/)() const override | Lekéri az end const iterátor megvalósítását a jelenlegi tárolóhoz. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../list/virtualizeenditerator/)() override | Lekéri az end iterátor megvalósítását a jelenlegi tárolóhoz. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~ICollection](../icollection/~icollection/)() | Megsemmisítő. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [ThisType](./thistype/) |  |
| [ListType](./listtype/) |  |
| [BaseTypes](./basetypes/) |  |
| [ValueType](./valuetype/) |  |
| [BaseType](./basetype/) |  |

## Lásd még

* Osztály [List](../list/)
* Osztály [IListWrapper](../../system.collections/ilistwrapper/)
* Névtere [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)