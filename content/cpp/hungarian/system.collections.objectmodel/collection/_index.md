---
title: Collection
second_title: Aspose.Slides C++ API Referencia
description: "Az általános gyűjtemény alap típusa. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával lehet lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és ezt a mutatót használja az objektum függvényeknek argumentumként történő átadásához."
type: docs
weight: 1
url: /hu/system.collections.objectmodel/collection/
---
## Gyűjtemény osztály

Az általános gyűjtemény alap típusa. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és ezt a mutatót használja az objektum függvényeknek argumentumként történő átadásához.

```cpp
template<class T>class Collection : public System::Collections::Generic::IList<T>
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | Element type. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [Add](./add/)(const T&) override | Értéket ad a tárolóhoz. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Iterátort ad vissza, amely az első elemre (ha van) mutat a gyűjteményben. Ez az iterátor nem használható a hivatkozott objektum módosítására, mivel a [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) egy másolat objektumot ad vissza T-ből. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Iterátort ad vissza, amely az első elemre (ha van) mutat a gyűjtemény const-kvalifikált példányában. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Iterátort ad vissza, amely az első const-kvalifikált elemre (ha van) mutat a gyűjteményben. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Iterátort ad vissza, amely az utolsó const-kvalifikált elem utánra mutat (ha van) a gyűjteményben. |
| void [Clear](./clear/)() override | Eltávolítja az összes elemet. |
| [Collection](./collection/)() | Üres gyűjteményt hoz létre. |
| [Collection](./collection/)([SharedPtr](../../system/sharedptr/)\<[Generic::IList](../../system.collections.generic/ilist/)\<T\>\>) |  |
| **bool** [Contains](./contains/)(const T&) const override | Ellenőrzi, hogy az elem jelen van-e a gyűjteményben. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<T\>, int) override | A gyűjtemény elemeit egy meglévő tömb elemeibe másolja. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Visszafelé mutató iterátort ad vissza az utolsó const-kvalifikált elemhez a gyűjteményben (az első a visszafelé iterálásban). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Visszafelé mutató iterátort ad vissza egy nem létező const-kvalifikált elemhez a gyűjtemény eleje előtt. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Iterátort ad vissza, amely az utolsó elem utánra mutat (ha van) a gyűjteményben. Ez az iterátor nem használható a hivatkozott objektum módosítására, mivel a [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) egy másolatot ad vissza T-ből. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Iterátort ad vissza, amely a const-kvalifikált példány utolsó eleme utánra mutat (ha van) a gyűjteményben. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Csak belső célokra. |
| int [get_Count](./get_count/)() const override | Az elemek számát adja vissza. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Ellenőrzi, hogy a gyűjtemény fix méretű-e. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | Ellenőrzi, hogy a gyűjtemény csak olvasható-e. |
| [SharedPtr](../../system/sharedptr/)\<[Generic::IList](../../system.collections.generic/ilist/)\<T\>\> [get_Items](./get_items/)() | A belső adatstruktúra hozzáférő. |
| const [Generic::ListPtr](../../system.collections.generic/listptr/)\<T\> [get_Items](./get_items/)() const | A belső adatstruktúra hozzáférő. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Az objektumot adja vissza, amelyen keresztül a gyűjtemény szinkronizálva van. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | A objektumhoz kapcsolódó referenciaszámláló adatstruktúrát adja vissza. |
| [SharedPtr](../../system/sharedptr/)\<[Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<T\>\> [GetEnumerator](./getenumerator/)() override | Enumerátort ad vissza a gyűjteményen való iteráláshoz. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Egyedi objektumok hash-elését teszi lehetővé. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | Alapértelmezett konstruktor. |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)&) | Másoló konstruktor. |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)&&) | Mozgató konstruktor. |
| T [idx_get](./idx_get/)(int) const override | A megadott indexű értéket adja vissza. |
| void [idx_set](./idx_set/)(int, T) override | Beállítja a megadott indexű értéket. |
| int [IndexOf](./indexof/)(const T&) const override | Megkeresi az elemet a gyűjteményben. |
| void [Insert](./insert/)(int, const T&) override | Beszúr egy elemet a megadott pozícióba. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | Ellenőrzi, hogy az objektum megfelel-e a targetType által leírt típusú példánynak. A C# 'is' operátor analógja. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | Akumulátor függvényt alkalmaz egy sorozatra. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function<**bool**(T)>) | Megállapítja, hogy a sorozat minden eleme teljesíti-e a feltételt. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Megállapítja, hogy a sorozat tartalmaz-e elemeket. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function<**bool**(T)>) | Megállapítja, hogy a sorozat bármely eleme létezik-e vagy teljesíti-e a feltételt. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Számolja egy numerikus értékekből álló sorozat átlagát. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | Számolja egy olyan sorozat átlagát, amelynek értékeit egy transzformáló függvény minden bemeneti elemre történő hívásával kapjuk. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Az elemeket a megadott típusra alakítja. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>>) | Két sorozatot fűz össze. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Megállapítja, hogy a sorozat tartalmaz-e egy megadott értéket. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálással). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | Visszaadja a sorozat elemeinek számát, amelyek teljesítik a megadott feltételt. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Visszaadja a sorozat egy megadott indexű elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | Visszaadja a sorozat első olyan elemét, amely megfelel a megadott feltételnek. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | Visszaadja a sorozat első olyan elemét, amely teljesíti a feltételt, vagy egy alapértelmezett értéket, ha nincs ilyen elem. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | Csoportosítja egy sorozat elemeit. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | Csoportosítja egy sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Visszaadja egy sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Visszaadja egy sorozat utolsó elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | Minden egyedi sorozat elemre meghív egy transzformáló függvényt, és visszaadja a legnagyobb eredményt. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | Minden egyedi sorozat elemre meghív egy transzformáló függvényt, és visszaadja a legkisebb eredményt. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | A sorozat elemeit a megadott típus alapján szűri. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | A sorozat elemeit növekvő sorrendbe rendezi a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | A sorozat elemeit csökkenő sorrendbe rendezi a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Megfordítja egy sorozat elemeinek sorrendjét. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | Átalakítja egy sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | Minden elemét egy sorozatnak új formává alakítja, a elem indexét felhasználva. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>>> & ) | Minden sorozat elemet leképez, és a keletkezett sorozatokat egybe vonja. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>>> & ) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Kihagy egy megadott számú folytonos elemet a sorozat elejéről, és a maradékot adja vissza. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Visszaad egy megadott számú folytonos elemet a sorozat elejéről. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Tömböt hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)<[List](../../system.collections.generic/list/)<T>> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | List<T>-t hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function<**bool**(T)>) | Szűri a sorozatot a megadott feltétel alapján. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)&&) | Mozgató értékadási operátor. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)&) | Mozgató értékadási operátor. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| T\& [operator[]](./operator[]/)(int) | A megadott indexű értéket adja vissza. |
| const T\& [operator[]](./operator[]/)(int) const | A megadott indexű értéket adja vissza. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Visszafelé mutató iterátort ad vissza a gyűjtemény utolsó eleméhez (az első a visszafelé iterálásban). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Visszafelé mutató iterátort ad vissza a const-kvalifikált gyűjtemény utolsó eleméhez (az első a visszafelé iterálásban). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Objektumokat hivatkozás szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Objektumokat hivatkozás szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Hivatkozásként hasonlítja össze az értéktípusbeli objektumot a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata karakterlánc és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata karakterláncok esetén. |
| **bool** [Remove](./remove/)(const T&) override | Eltávolít egy konkrét elemet. |
| void [RemoveAt](./removeat/)(int) override | Eltávolít egy elemet a megadott pozícióban. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Visszafelé mutató iterátort ad vissza egy nem létező elemhez a gyűjtemény eleje előtt. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Visszafelő mutató iterátort ad vissza egy nem létező elemhez a const-kvalifikált gyűjtemény eleje előtt. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | A tárolt mutatókat gyengévé (weak) teszi (ha alkalmazható). |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referenciaszámláló aktuális értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá alakítását. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | A jelenlegi konténer kezdő const iterátorának megvalósítását adja vissza. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | A jelenlegi konténer kezdő iterátorának megvalósítását adja vissza. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | A jelenlegi konténer vég const iterátorának megvalósítását adja vissza. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | A jelenlegi konténer vég iterátorának megvalósítását adja vissza. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Megsemmisítő. |
| virtual [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Typedefek

| Típusdefiníció | Leírás |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) |  |
| [const_reverse_iterator](./const_reverse_iterator/) |  |

## Lásd még

* Osztály [IList](../../system.collections.generic/ilist/)
* Névtér [System::Collections::ObjectModel](../)
* Könyvtár [Aspose.Slides](../../)