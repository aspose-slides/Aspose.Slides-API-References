---
title: SoapHeaderCollection
second_title: Aspose.Slides C++ API referencia
description: A SoapHeader osztály példányainak gyűjteményét tartalmaz.
type: docs
weight: 105
url: /hu/system.web.services.protocols/soapheadercollection/
---
## SoapHeaderCollection osztály


A [SoapHeader](../soapheader/) osztály példányainak gyűjteményét tartalmazza.

```cpp
class SoapHeaderCollection : public System::Collections::Generic::List<System::SharedPtr<SoapHeader>>
```

## Metódusok

| Method | Description |
| --- | --- |
| void [_add_range](../../system.collections.generic/list/_add_range/)(std::initializer_list\<T\>) | C++ specifikus. |
| void [Add](../../system.collections.generic/list/add/)(const T\&) override | Elemét adja a lista végéhez. |
| void [AddInitializer](../../system.collections.generic/list/addinitializer/)(int, const T *) | Elem(ek) hozzáadása a listához; inicializálók fordításakor használatos. |
| void [AddRange](../../system.collections.generic/list/addrange/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Az összes elemet a gyűjteményből (vagy önmagából) hozzáadja a jelenlegi lista végéhez. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../../system.collections.generic/list/asreadonly/)() | Olvasás-csakra szóló hivatkozást ad a gyűjteményhez. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/list/begin/)() | Iterátort ad a gyűjtemény első eleméhez. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/list/begin/)() const | Iterátort ad a const-minősített gyűjtemény első eleméhez. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&) const | Megkeresi az elemet egy rendezett listában. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Megkeresi az elemet egy rendezett listában. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Megkeresi az elemet egy rendezett listában. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/list/cbegin/)() const | Iterátort ad a gyűjtemény első const-minősített eleméhez. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/list/cend/)() const | Iterátort ad egy nem létező const-minősített elemhez a gyűjtemény végén. |
| void [Clear](../../system.collections.generic/list/clear/)() override | Minden elemet töröl. |
| **bool** [Contains](../../system.collections.generic/list/contains/)(const T\&) const override | Ellenőrzi, hogy az elem jelen van-e a listában. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<OutputType\>\> [ConvertAll](../../system.collections.generic/list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Létrehoz egy listát az elemek különböző típusra konvertált változataival. |
| void [CopyTo](../../system.collections.generic/list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | A listaelemeket meglévő tömelelemekbe másolja. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Az összes elemet meglévő tömelelemekbe másolja. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Az adott indextől kezdődő elemeket meglévő tömelelemekbe másolja. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crbegin](../../system.collections.generic/list/crbegin/)() const | Visszafelé iterátort ad a gyűjtemény utolsó const-minősített eleméhez (az első fordított irányban). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crend](../../system.collections.generic/list/crend/)() const | Visszafelé iterátort ad egy nem létező const-minősített elemhez a gyűjtemény eleje előtt. |
| [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() | Az alapszerkezet elérésére szolgáló függvény. |
| const [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() const | Az alapszerkezet elérésére szolgáló függvény. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/list/end/)() | Iterátort ad egy nem létező elemhez a gyűjtemény végén. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/list/end/)() const | Iterátort ad egy nem létező elemhez a const-minősített gyűjtemény végén. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia-típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték-típusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-szerű lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-szerű lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| **bool** [Exists](../../system.collections.generic/list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Ellenőrzi, hogy létezik-e a listában a megadott feltételnek megfelelő elem. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| T [Find](../../system.collections.generic/list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Megkeresi a megadott feltételnek megfelelő elemet. |
| [ListPtr](../../system.collections.generic/listptr/)\<T\> [FindAll](../../system.collections.generic/list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Megkeresi a megadott feltételnek megfelelő elemeket. |
| int [FindIndex](../../system.collections.generic/list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Megkeresi a megadott feltételnek megfelelő elemet. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Megkeresi a megadott feltételnek megfelelő elemet. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Megkeresi a megadott feltételnek megfelelő elemet. |
| T [FindLast](../../system.collections.generic/list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Megkeresi az utolsó elemet, amely megfelel a megadott feltételnek. |
| void [ForEach](../../system.collections.generic/list/foreach/)([System::Action](../../system/action/)\<T\>) | Műveletet alkalmaz az összes listaelemre. |
| int [get_Capacity](../../system.collections.generic/list/get_capacity/)() const | Lekéri a lista jelenlegi kapacitását. |
| int [get_Count](../../system.collections.generic/list/get_count/)() const override | Lekéri a lista elemeinek számát. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Ellenőrzi, hogy a gyűjtemény rögzített méretű-e. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | Ellenőrzi, hogy a gyűjtemény csak olvasható-e. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Lekéri azt az objektumot, amelyen keresztül a gyűjtemény szinkronizálva van. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| [IEnumeratorPtr](../../system.collections.generic/list/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/list/getenumerator/)() override | Lekéri a felsorolót a listaelemek bejárásához. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| **ThisPtr** [GetRange](../../system.collections.generic/list/getrange/)(int, int) | Lista szeletet hoz létre. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Alapértelmezett konstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Másoló konstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Áthelyező konstruktor. |
| T [idx_get](../../system.collections.generic/list/idx_get/)(int) const override | Lekéri az adott pozícióban lévő elemet. |
| void [idx_set](../../system.collections.generic/list/idx_set/)(int, T) override | Beállítja az elemet a megadott pozíción. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&) const override | Lekéri a megadott elem első indexét. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&, int) const | Megkeresi a megadott elemet a listában. |
| void [Insert](../../system.collections.generic/list/insert/)(int, const T\&) override | Beszúr egy elemet a megadott pozícióba. |
| void [InsertRange](../../system.collections.generic/list/insertrange/)(int, [IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Adattartományt szúr be a megadott pozícióba. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&) const | Megkeresi a megadott objektumot, és visszaadja a teljes listában szereplő utolsó előfordulás nulláról induló indexét. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**) const | Megkeresi a megadott objektumot, és visszaadja a [List](../../system.collections.generic/list/) elemeinek adott tól-tól (az első elemtől a megadott indexig) terjedő tartományban lévő utolsó előfordulás nulláról induló indexét. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Megkeresi a megadott objektumot, és visszaadja a [List](../../system.collections.generic/list/) elemeinek azon tartományában, amely meghatározott számú elemet tartalmaz és a megadott indexnél ér véget, az utolsó előfordulás nulláról induló indexét. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Akumulátor függvényt alkalmaz egy sorozaton. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat minden eleme megfelel-e a feltételnek. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Megállapítja, hogy a sorozat tartalmaz-e elemeket. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat bármely eleme létezik-e vagy megfelel-e a feltételnek. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Kiszámítja egy numerikus értékekből álló sorozat átlagát. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Kiszámítja egy sorozat értékeinek átlagát, amelyeket az input sorozat minden elemén egy transzformáló függvény alkalmazásával kap. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Az elemeket a megadott típusra konvertálja. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Két sorozatot fűz össze. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Megállapítja, hogy a sorozat tartalmaz-e egy megadott értéket. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálással kiszámítva). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat azon elemeinek számát, amelyek megfelelnek a megadott feltételnek. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat első olyan elemét, amely megfelel a megadott feltételnek. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Visszaadja a sorozat első olyan elemét, amely megfelel egy feltételnek, vagy alapértelmezett értéket, ha ilyen elem nem található. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | A sorozat elemeit csoportosítja. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | A sorozat elemeit csoportosítja. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Visszaadja a sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Visszaadja a sorozat utolsó elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden egyes elemre meghívja a transzformáló függvényt egy általános sorozatban, és visszaadja a kapott értékek közül a legnagyobbat. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden egyes elemre meghívja a transzformáló függvényt egy általános sorozatban, és visszaadja a kapott értékek közül a legkisebbet. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | A sorozat elemeit a megadott típus alapján szűri. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | A sorozat elemeit növekvő sorrendbe rendezi a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | A sorozat elemeit csökkenő sorrendbe rendezi a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Megfordítja a sorozat elemeinek sorrendjét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Átalakítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | A sorozat minden elemét új formába alakítja át az indexét felhasználva. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | A sorozat minden elemét projektálja, és az eredményül kapott sorozatokat egy sorozatba egyesíti. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Kihagy egy meghatározott számú szomszédos elemet a sorozat elejéről, és visszaadja a maradékot. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Visszaad egy meghatározott számú szomszédos elemet a sorozat elejéről. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Tömböt hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | List<T>-t hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Szűri a sorozatot a megadott predikátum alapján. |
|  [List](../../system.collections.generic/list/list/)() | Üres listát hoz létre. |
|  [List](../../system.collections.generic/list/list/)(int) | Listát hoz létre előre meghatározott kapacitással. |
|  [List](../../system.collections.generic/list/list/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Másoló konstruktor. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Nem másol valóban semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Nem másol valóban semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Áthelyező értékadási operátor. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Áthelyező értékadási operátor. |
| vector_t::reference [operator[]](../../system.collections.generic/list/operator[]/)(int) | Hozzáférő függvény. |
| vector_t::const_reference [operator[]](../../system.collections.generic/list/operator[]/)(int) const | Hozzáférő függvény. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() | Visszafelé iterátort ad a gyűjtemény utolsó eleméhez (az első fordítottban). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() const | Visszafelé iterátort ad a const-minősített gyűjtemény utolsó eleméhez (az első fordítottban). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípust hasonlít össze hivatkozással a nullptr-gal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetén. |
| **bool** [Remove](../../system.collections.generic/list/remove/)(const T\&) override |Eltávolítja az első előfordulását a megadott elemnek a listából. |
| int [RemoveAll](../../system.collections.generic/list/removeall/)([Predicate](../../system/predicate/)\<T\>) |Eltávolítja az összes olyan elemet, amely megfelel a megadott predikátumnak. |
| void [RemoveAt](../../system.collections.generic/list/removeat/)(int) override |Eltávolítja a megadott pozícióban lévő elemet. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) |Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [RemoveRange](../../system.collections.generic/list/removerange/)(int, int) |Eltávolít egy lista szeletet. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() |Visszafelé iterátort ad egy nem létező elemhez a gyűjtemény eleje előtt. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() const |Visszafelé iterátort ad egy nem létező elemhez a const-minősített gyűjtemény eleje előtt. |
| void [Reverse](../../system.collections.generic/list/reverse/)() |Megfordítja a teljes lista elemeinek sorrendjét. |
| void [Reverse](../../system.collections.generic/list/reverse/)(int, int) |Megfordítja a lista szelet elemeinek sorrendjét. |
| void [set_Capacity](../../system.collections.generic/list/set_capacity/)(int) |Beállítja a lista kapacitását. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) |Az n-edik sablonargumentumot gyenge mutatóként állítja be (a shared helyett). Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const |Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() |Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() |Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [SoapHeaderCollection](./soapheadercollection/)() |Inicializál egy új példányt a [SoapHeaderCollection](./) osztályból. |
| void [Sort](../../system.collections.generic/list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Rendezi a lista elemeit. |
| void [Sort](../../system.collections.generic/list/sort/)() | Rendezi a lista elemeit az alapértelmezett összehasonlítóval. |
| void [Sort](../../system.collections.generic/list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>) | Rendezi a lista szelet elemeit. |
| void [Sort](../../system.collections.generic/list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Rendezi a lista elemeit. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../../system.collections.generic/list/toarray/)() const |A listát tömbbé konvertálja. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const |A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| void [TrimExcess](../../system.collections.generic/list/trimexcess/)() |A lista kapacitását a méretéhez igazítja. |
| **bool** [TrueForAll](../../system.collections.generic/list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) |Megállapítja, hogy a gyűjtemény minden eleme megfelel-e a megadott predikátumnak. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() |Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() |Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.generic/list/virtualizebeginconstiterator/)() const override |Lekéri a jelenlegi tároló begin const iterátorának megvalósítását. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.generic/list/virtualizebeginiterator/)() override |Lekéri a jelenlegi tároló begin iterátorának megvalósítását. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.generic/list/virtualizeendconstiterator/)() const override |Lekéri a jelenlegi tároló end const iterátorának megvalósítását. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.generic/list/virtualizeenditerator/)() override |Lekéri a jelenlegi tároló end iterátorának megvalósítását. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() |Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() |Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() |Destruktor. |
| virtual  [~Object](../../system/object/~object/)() |Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [List](../../system.collections.generic/list/)
* Névtér [System::Web::Services::Protocols](../)
* Könyvtár [Aspose.Slides](../../)