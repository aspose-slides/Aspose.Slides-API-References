---
title: List
second_title: Aspose.Slides C++ API Referenciája
description: List előre deklaráció.
type: docs
weight: 430
url: /hu/system.collections.generic/list/
---
## List osztály

[List](./) előre deklaráció.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | Elem típusa. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++ specifikus. |
| void [Add](./add/)(const T\&) override | Elemet ad a lista végéhez. |
| void [AddInitializer](./addinitializer/)(int, const T *) | Elemeket ad a listához; inicializálók fordításához használják. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | Az összes elemet a gyűjteményből (vagy önmagából) a jelenlegi lista végéhez adja. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | Olvasásra csak hivatkozást kap ehhez a gyűjteményhez. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Iterátort kap a gyűjtemény első eleméhez. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Iterátort kap a const minősített gyűjtemény első eleméhez. |
| int [BinarySearch](./binarysearch/)(const T\&) const | Elemet keres egy rendezett listában. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Elemet keres egy rendezett listában. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Elemet keres egy rendezett listában. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Iterátort kap a gyűjtemény első const minősített eleméhez. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Iterátort kap egy nem létező, const minősített elemhez, ami a gyűjtemény vége mögött van. |
| void [Clear](./clear/)() override | Az összes elemet törli. |
| **bool** [Contains](./contains/)(const T\&) const override | Ellenőrzi, hogy az elem jelen van-e a listában. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Létrehoz egy listát, amely elemei más típusra konvertálva vannak. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | A listaelemeket meglévő tömb elemeibe másolja. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Az összes elemet meglévő tömb elemeibe másolja. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Az elemeket a megadott indextől kezdve meglévő tömb elemeibe másolja. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Fordított iterátort kap a gyűjtemény utolsó const minősített eleméhez (az első fordított sorrendben). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Fordított iterátort kap egy nem létező, const minősített elemhez, ami a gyűjtemény eleje előtt van. |
| [vector_t](./vector_t/)\& [data](./data/)() | Az alapszerkezet elérési függvénye. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | Az alapszerkezet elérési függvénye. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Iterátort kap egy nem létező elemhez, ami a gyűjtemény vége mögött van. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Iterátort kap egy nem létező elemhez, ami a const minősített gyűjtemény vége mögött van. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantikával hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C# stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C# stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | Ellenőrzi, hogy létezik-e olyan elem a listában, amely megfelel egy adott feltételnek. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | Kikeresi a megadott feltételnek megfelelő elemet. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | Kikeresi a megadott feltételnek megfelelő elemeket. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Kikeresi a megadott feltételnek megfelelő elemet. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Kikeresi a megadott feltételnek megfelelő elemet. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Kikeresi a megadott feltételnek megfelelő elemet. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Kikeresi a megadott feltételnek megfelelő elemet. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | Műveletet hajt végre a lista összes elemén. |
| int [get_Capacity](./get_capacity/)() const | Lekéri a lista aktuális kapacitását. |
| int [get_Count](./get_count/)() const override | Lekéri az aktuális lista elemeinek számát. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Ellenőrzi, hogy a gyűjtemény rögzített méretű-e. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Ellenőrzi, hogy a gyűjtemény csak olvasható-e. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Lekéri az objektumot, amelyen keresztül a gyűjtemény szinkronizálva van. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Lekéri a felsorolót a listaelemek bejárásához. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi egyedi objektumok hash-ét. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | A lista egy szeletét hozza létre. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
|  [ICollection](../icollection/icollection/)() | Alapértelmezett konstruktor. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Másoló konstruktor. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Áthelyező konstruktor. |
| T [idx_get](./idx_get/)(int) const override | Lekéri az elemet egy adott pozícióban. |
| void [idx_set](./idx_set/)(int, T) override | Beállítja az elemet egy adott pozícióban. |
| int [IndexOf](./indexof/)(const T\&) const override | Lekéri egy adott elem első indexét. |
| int [IndexOf](./indexof/)(const T\&, int) const | Kikeresi a meghatározott elemet a listában. |
| void [Insert](./insert/)(int, const T\&) override | Beilleszti az elemet a megadott pozícióba. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | Adattartományt illeszt be egy adott pozícióba. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | Keres egy megadott objektumot és visszaadja a nulla-alapú indexet a teljes listában a legutóbbi előfordulásra. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | Keres egy megadott objektumot és visszaadja a nulla-alapú indexet a legutóbbi előfordulásra a [List](./) elemeinek azt a tartományában, amely az első elemtől a megadott indexig terjed. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Keres egy megadott objektumot és visszaadja a nulla-alapú indexet a legutóbbi előfordulásra a [List](./) elemeinek azt a tartományában, amely a megadott elemszámot tartalmazza és a megadott indexnél ér véget. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Alkalmaz egy akkumulátor függvényt egy sorozaton. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat minden eleme kielégíti-e a feltételt. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Megállapítja, hogy a sorozat tartalmaz-e bármely elemet. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat bármely eleme létezik-e vagy megfelel-e a feltételnek. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Kiszámítja egy numerikus értékekből álló sorozat átlagát. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Kiszámítja egy olyan értéksorozat átlagát, amelyet a bemeneti sorozat minden elemére alkalmazott transzformáló függvény eredményez. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Átkonvertálja az elemeket a megadott típusra. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Két sorozatot fűz össze. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Megállapítja, hogy a sorozat tartalmaz-e egy megadott értéket. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálással számítva). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozatban a megadott feltételt kielégítő elemek számát. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_First](../ienumerable/linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat első olyan elemét, amely kielégíti a megadott feltételt. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Visszaadja a sorozat első olyan elemét, amely kielégíti a feltételt, vagy alapértelmezett értéket, ha nincs ilyen elem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Csoportosítja a sorozat elemeit. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Csoportosítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Visszaadja a sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Visszaadja a sorozat utolsó elemét, vagy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden generikus sorozat elemére transzformáló függvényt hív meg, és visszaadja a legnagyobb eredményt. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden generikus sorozat elemére transzformáló függvényt hív meg, és visszaadja a legkisebb eredményt. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | A sorozat elemeit a megadott típus alapján szűri. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | A sorozat elemeit növekvő sorrendbe rendezi a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | A sorozat elemeit csökkenő sorrendbe rendezi a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Megfordítja a sorozat elemeinek sorrendjét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Átalakítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Minden sorozat elemet új formába alakít át, a elem indexét felhasználva. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projekcióval dolgoz fel minden sorozati elemet, és a kapott sorozatokat egybe egyesíti. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Kihagy egy megadott számú egymást követő elemet a sorozat elejéről, és a maradékot adja vissza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Visszaad egy megadott számú egymást követő elemet a sorozat elejéről. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Tömböt hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | List<T>-t hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Sorozatot szűr a megadott predikátum alapján. |
|  [List](./list/)() | Üres listát hoz létre. |
|  [List](./list/)(int) | Előre meghatározott kapacitással hoz létre listát. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | Másoló konstruktor. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Engedélyezi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Áthelyező értékadási operátor. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Áthelyező értékadási operátor. |
| vector_t::reference [operator[]](./operator[]/)(int) | Elérő függvény. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Elérő függvény. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Fordított iterátort kap a gyűjtemény utolsó eleméhez (az első fordított sorrendben). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Fordított iterátort kap a const minősített gyűjtemény utolsó eleméhez (az első fordított sorrendben). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot nullptr-el hasonlít össze referencia szerint. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| **bool** [Remove](./remove/)(const T\&) override | Eltávolítja a lista első előfordulását a megadott elemből. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Eltávolítja az összes elemet, amelyek megfelelnek a megadott feltételnek. |
| void [RemoveAt](./removeat/)(int) override | Eltávolítja a megadott pozícióban lévő elemet. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót egy megadott értékkel. |
| void [RemoveRange](./removerange/)(int, int) | Eltávolít egy listaszeletet. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Fordított iterátort kap egy nem létező elemhez, ami a gyűjtemény eleje előtt van. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Fordított iterátort kap egy nem létező elemhez, ami a const minősített gyűjtemény eleje előtt van. |
| void [Reverse](./reverse/)() | Megfordítja a teljes lista elemeinek sorrendjét. |
| void [Reverse](./reverse/)(int, int) | Megfordítja a lista szelet elemeinek sorrendjét. |
| void [set_Capacity](./set_capacity/)(int) | Beállítja a lista kapacitását. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóként állítja be (a megosztott helyett). Lehetővé teszi a konténerekben lévő mutatók weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Rendezi a lista elemeit. |
| void [Sort](./sort/)() | Rendezi a lista elemeit az alapértelmezett összehasonlítóval. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Rendezi a lista szelet elemeit. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Rendezi a lista elemeit. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Átalakítja a listát tömbbé. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Engedélyezi egyedi objektumok stringgé alakítását. |
| void [TrimExcess](./trimexcess/)() | A lista kapacitását a méretéhez igazítja. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Megállapítja, hogy a gyűjtemény minden eleme megfelel-e a megadott predikátum által definiált feltételeknek. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Lekéri az aktuális tároló begin const iterátorának megvalósítását. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Lekéri az aktuális tároló begin iterátorának megvalósítását. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Lekéri az aktuális tároló end const iterátorának megvalósítását. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Lekéri az aktuális tároló end iterátorának megvalósítását. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual  [~ICollection](../icollection/~icollection/)() | Megsemmisítő. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [ValueType](./valuetype/) | Ez a típus. |
| [BaseType](./basetype/) | Interfész típus. |
| [vector_t](./vector_t/) | Alap adat típus. |
| [iterator](./iterator/) | Iterátor típus. |
| [const_iterator](./const_iterator/) | Const iterátor típus. |
| [reverse_iterator](./reverse_iterator/) | Fordított iterátor típus. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const fordított iterátor típus. |
| [IEnumerablePtr](./ienumerableptr/) | Konténer, amely ugyanabban a típusban tárol elemeket, mint mi. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerátor** típus. |

## Megjegyzések

[List](./) – wrapper a std::vector köré, amelyet lefordított kódban kell használni. Megköveteli az operator == implementálását az elem típusához. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad példányosítani. Sose hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Létrehozza az első listát.
  auto list1 = MakeObject<List<int>>();

  // Feltölti az első listát.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Rendezi az első listát.
  // Az első lista elemei: {-5, 1, 3, 8}
  list1->Sort();

  // Eltávolítja a 2. indexű elemet.
  // Az első lista elemei: {-5, 1, 8}
  list1->RemoveAt(2);

  // Beszúrja az elemet az 1. indexre.
  // Az első lista elemei: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Létrehozza a második listát.
  auto list2 = MakeObject<List<int>>();

  // Feltölti a második listát.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Hozzáfűzi a második lista elemeit az elsőhöz.
  list1->AddRange(list2);

  // Kiírja az első lista elemeit.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Ez a kódrészlet a következő kimenetet adja:
- 5 15 1 8 10 20 30
*/
```

## Lásd még

* Osztály [Object](../../system/object/)
* Osztály [IList](../ilist/)
* Névtere [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)