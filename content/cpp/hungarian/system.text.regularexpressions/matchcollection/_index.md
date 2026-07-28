---
title: MatchCollection
second_title: Aspose.Slides a C++ API hivatkozás
description: "Gyűjtemény a reguláris kifejezést (regexp) ismételt alkalmazásával a karakterláncra végzett találatokból. Ennek az osztálynak az objektumait csak a System::MakeObject() függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy assert hibákhoz vezethet. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és ezt a mutatót használja az argumentumként történő függvényhívásokhoz."
type: docs
weight: 79
url: /hu/system.text.regularexpressions/matchcollection/
---
## MatchCollection osztály

A reguláris kifejezést ismételt alkalmazásával a karakterláncra kapott egyezések gyűjteménye. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként való átadáshoz a függvényeknek.

```cpp
class MatchCollection : public System::Collections::Generic::List<MatchPtr>
```

## Metódusok

| Method | Description |
| --- | --- |
| void [_add_range](../../system.collections.generic/list/_add_range/)(std::initializer_list\<T\>) | C++ specifikus. |
| void [Add](../../system.collections.generic/list/add/)(const T\&) override | Elemet ad a lista végéhez. |
| void [AddInitializer](../../system.collections.generic/list/addinitializer/)(int, const T *) | Elemet ad a listához; inicializálók lefordításakor használatos. |
| void [AddRange](../../system.collections.generic/list/addrange/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Az összes elemet a gyűjteményből (vagy önmagából) hozzáadja a jelenlegi lista végéhez. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../../system.collections.generic/list/asreadonly/)() | Csak olvasható hivatkozást kap erre a gyűjteményre. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/list/begin/)() | Iterátort kap a gyűjtemény első eleméhez. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/list/begin/)() const | Iterátort kap a const-kvalifikált gyűjtemény első eleméhez. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&) const | Elemet keres egy rendezett listában. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Elemet keres egy rendezett listában. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Elemet keres egy rendezett listában. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/list/cbegin/)() const | Iterátort kap a gyűjtemény első const-kvalifikált eleméhez. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/list/cend/)() const | Iterátort kap egy nem létező const-kvalifikált elemhez a gyűjtemény vége mögött. |
| void [Clear](../../system.collections.generic/list/clear/)() override | Az összes elemet törli. |
| **bool** [Contains](../../system.collections.generic/list/contains/)(const T\&) const override | Ellenőrzi, hogy az elem jelen van-e a listában. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<OutputType\>\> [ConvertAll](../../system.collections.generic/list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Létrehoz egy listát az elemekből, amelyeket más típusra konvertál. |
| void [CopyTo](../../system.collections.generic/list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | A lista elemeit meglévő tömb elemeibe másolja. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Az összes elemet meglévő tömb elemeibe másolja. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Az elemeket a megadott indextől kezdve meglévő tömb elemeibe másolja. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crbegin](../../system.collections.generic/list/crbegin/)() const | Visszafelé mutató iterátort kap a gyűjtemény utolsó const-kvalifikált eleméhez (az első visszafelé). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crend](../../system.collections.generic/list/crend/)() const | Visszafelő mutató iterátort kap egy nem létező const-kvalifikált elemhez a gyűjtemény eleje előtt. |
| [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() | Az alapszerkezethez való hozzáférési függvény. |
| const [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() const | Az alapszerkezethez való hozzáférési függvény. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/list/end/)() | Iterátort kap egy nem létező elemhez a gyűjtemény vége mögött. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/list/end/)() const | Iterátort kap egy nem létező elemhez a const-kvalifikált gyűjtemény vége mögött. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN semelyik értékkel, így NaN-nal sem egyenlő. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN semelyik értékkel, így NaN-nal sem egyenlő. |
| **bool** [Exists](../../system.collections.generic/list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Ellenőrzi, hogy a listában létezik-e olyan elem, amely megfelel egy adott predikátumnak. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| T [Find](../../system.collections.generic/list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Megkeresi az elemet, amely megfelel egy adott predikátumnak. |
| [ListPtr](../../system.collections.generic/listptr/)\<T\> [FindAll](../../system.collections.generic/list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Megkeresi az elemeket, amelyek megfelelnek egy adott predikátumnak. |
| int [FindIndex](../../system.collections.generic/list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Megkeresi az elemet, amely megfelel egy adott predikátumnak. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Megkeresi az elemet, amely megfelel egy adott predikátumnak. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Megkeresi az elemet, amely megfelel egy adott predikátumnak. |
| T [FindLast](../../system.collections.generic/list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Megkeresi az utolsó elemet, amely megfelel egy adott predikátumnak. |
| void [ForEach](../../system.collections.generic/list/foreach/)([System::Action](../../system/action/)\<T\>) | Műveletet hajt végre a lista minden elemén. |
| int [get_Capacity](../../system.collections.generic/list/get_capacity/)() const | A list aktuális kapacitását kapja. |
| int [get_Count](../../system.collections.generic/list/get_count/)() const override | A jelenlegi lista elemeinek számát kapja. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Ellenőrzi, hogy a gyűjtemény rögzített méretű-e. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | Ellenőrzi, hogy a gyűjtemény csak olvasható-e. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | A objektumot kapja, amelyen keresztül a gyűjtemény szinkronizálva van. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz társított referencia számláló adatstruktúrát kapja. |
| [IEnumeratorPtr](../../system.collections.generic/list/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/list/getenumerator/)() override | Enumerátort kap, amely a lista elemein iterál. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| **ThisPtr** [GetRange](../../system.collections.generic/list/getrange/)(int, int) | A lista szeletét hozza létre. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát kapja. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Alapértelmezett konstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Másoló konstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Mozgató konstruktor. |
| T [idx_get](../../system.collections.generic/list/idx_get/)(int) const override | Az adott pozícióban lévő elemet kapja. |
| void [idx_set](../../system.collections.generic/list/idx_set/)(int, T) override | Az adott pozícióban lévő elemet állítja. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&) const override | Az adott elem első indexét kapja. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&, int) const | Keres egy adott elemet a listában. |
| void [Insert](../../system.collections.generic/list/insert/)(int, const T\&) override | Elemet szúr be a megadott pozícióba. |
| void [InsertRange](../../system.collections.generic/list/insertrange/)(int, [IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Adattartományt szúr be egy adott pozícióba. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| **bool** [IsReadOnly](./isreadonly/)() const | A gyűjteményt csak olvashatóvá jelöli. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&) const | Keres a megadott objektumra és visszaadja a nulla alapú indexet az utolsó előforduláshoz a teljes listában. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**) const | Keres a megadott objektumra és visszaadja a nulla alapú indexet az utolsó előforduláshoz a [List](../../system.collections.generic/list/) elemeinek tartományában, amely az első elemtől a megadott indexig terjed. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Keres a megadott objektumra és visszaadja a nulla alapú indexet az utolsó előforduláshoz a [List](../../system.collections.generic/list/) elemeinek tartományában, amely a megadott számú elemet tartalmazza és a megadott indexnél ér véget. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Akkumulátor függvényt alkalmaz egy sorozaton. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat minden eleme teljesít-e egy feltételt. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Megállapítja, hogy a sorozat tartalmaz-e bármilyen elemet. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat bármely eleme létezik-e vagy teljesít-e egy feltételt. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Kiszámítja egy numerikus értékek sorozat átlagát. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Kiszámítja egy értéksorozat átlagát, amelyet a bemeneti sorozat minden elemén meghívott transzformáló függvény eredményez. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Átkonvertálja az elemeket a megadott típusra. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Két sorozatot fűz össze. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Megállapítja, hogy a sorozat tartalmaz-e egy adott értéket. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálással számolva). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat azon elemeinek számát, amelyek megfelelnek a megadott feltételnek. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Visszaadja a sorozat adott indexű elemét. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Visszaadja a sorozat adott indexű elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat első olyan elemét, amely megfelel a megadott feltételnek. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Visszaadja a sorozat első olyan elemét, amely teljesíti a feltételt, vagy alapértelmezett értéket, ha ilyen elem nem található. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Csoportosítja a sorozat elemeit. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Csoportosítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Visszaadja a sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Visszaadja a sorozat utolsó elemét, vagy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Meghív egy transzformáló függvényt egy általános sorozat minden elemén, és visszaadja a legnagyobb eredményértéket. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Meghív egy transzformáló függvényt egy általános sorozat minden elemén, és visszaadja a legkisebb eredményértéket. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Szűri a sorozat elemeit a megadott típus alapján. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | A sorozat elemeit növekvő sorrendbe rendezi a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | A sorozat elemeit csökkenő sorrendbe rendezi a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Megfordítja egy sorozat elemeinek sorrendjét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Átalakítja egy sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Átalakítja a sorozat minden elemét egy új formába, beépítve az elem indexét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projektiálja minden sorozat elemét és az eredményül kapott sorozatokat egyetlen sorozatba egyesíti. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Kihagy egy megadott számú folytonos elemet a sorozat elejéről, és visszaadja a maradékot. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Visszaad egy megadott számú folytonos elemet a sorozat elejéről. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Létrehoz egy tömböt egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Létrehoz egy List<T>-t egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Szűri a sorozatot a megadott predikátum alapján. |
|  [List](../../system.collections.generic/list/list/)() | Üres listát hoz létre. |
|  [List](../../system.collections.generic/list/list/)(int) | Listát hoz létre előre meghatározott kapacitással. |
|  [List](../../system.collections.generic/list/list/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Másoló konstruktor. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást a zároláshoz. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Engedélyezi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi alosztályok másoló konstruktorát. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Mozgató értékadó operátor. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Mozgató értékadó operátor. |
| vector_t::reference [operator[]](../../system.collections.generic/list/operator[]/)(int) | Elérő függvény. |
| vector_t::const_reference [operator[]](../../system.collections.generic/list/operator[]/)(int) const | Elérő függvény. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() | Visszafelé mutató iterátort kap a gyűjtemény utolsó eleméhez (az első visszafelé). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() const | Visszafelő mutató iterátort kap a const-kvalifikált gyűjtemény utolsó eleméhez (az első visszafelő). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia alapján hasonlít. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia alapján hasonlít. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot referencia szerint hasonlít a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| **bool** [Remove](../../system.collections.generic/list/remove/)(const T\&) override | Eltávolítja az adott elem első előfordulását a listáról. |
| int [RemoveAll](../../system.collections.generic/list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Eltávolítja az összes elemét, amely megfelel egy adott predikátumnak. |
| void [RemoveAt](../../system.collections.generic/list/removeat/)(int) override | Eltávolít egy elemet a megadott pozícióból. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [RemoveRange](../../system.collections.generic/list/removerange/)(int, int) | Eltávolít egy szeletet a listából. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() | Visszafelő mutató iterátort kap egy nem létező elemhez a gyűjtemény eleje előtt. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() const | Visszafelő mutató iterátort kap egy nem létező elemhez a const-kvalifikált gyűjtemény eleje előtt. |
| void [Reverse](../../system.collections.generic/list/reverse/)() | Megfordítja az egész lista elemeinek sorrendjét. |
| void [Reverse](../../system.collections.generic/list/reverse/)(int, int) | Megfordítja a lista szelet elemeinek sorrendjét. |
| void [set_Capacity](../../system.collections.generic/list/set_capacity/)(int) | Beállítja a lista kapacitását. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók átváltását gyenge módra a konténerekben. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referencia számláló jelenlegi értékét kapja. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Sort](../../system.collections.generic/list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Rendezi a lista elemeit. |
| void [Sort](../../system.collections.generic/list/sort/)() | Rendezi a lista elemeit alapértelmezett összehasonlítóval. |
| void [Sort](../../system.collections.generic/list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>) | Rendezi a lista szelet elemeit. |
| void [Sort](../../system.collections.generic/list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Rendezi a lista elemeit. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../../system.collections.generic/list/toarray/)() const | Átalakítja a listát tömbbé. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| void [TrimExcess](../../system.collections.generic/list/trimexcess/)() | A lista kapacitását a méretéhez igazítja. |
| **bool** [TrueForAll](../../system.collections.generic/list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Megállapítja, hogy a gyűjtemény minden eleme megfelel-e a megadott predikátum által definiált feltételeknek. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítást a feloldáshoz. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.generic/list/virtualizebeginconstiterator/)() const override | A jelenlegi tároló kezdő const iterátorának megvalósítását kapja. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.generic/list/virtualizebeginiterator/)() override | A jelenlegi tároló kezdő iterátorának megvalósítását kapja. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.generic/list/virtualizeendconstiterator/)() const override | A jelenlegi tároló vég const iterátorának megvalósítását kapja. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.generic/list/virtualizeenditerator/)() override | A jelenlegi tároló vég iterátorának megvalósítását kapja. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Dekonstruktor. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [List](../../system.collections.generic/list/)
* Névtere [System::Text::RegularExpressions](../)
* Könyvtár [Aspose.Slides](../../)