---
title: ISet
second_title: Aspose.Slides a C++ API referencia
description: "Gyűjtemény interfésze, amely egyedi elemek halmazát tartalmazza. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mert ez futásidejű hibákat és/vagy assert hibákat eredményez. Mindig csomagolja be ezt az osztályt System::SmartPtr mutatóba, és használja ezt a mutatót argumentumként a függvényekhez."
type: docs
weight: 352
url: /hu/system.collections.generic/iset/
---
## ISet osztály


Interface of collection containing a set of unique elements. Objects of this osztály should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this osztály into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class ISet : public System::Collections::Generic::ICollection<T>
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | Element type. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual void [Add](../icollection/add/)(const T\&) | Elemet ad a gyűjteményhez. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Iterátort ad, amely a gyűjtemény első (ha van) elemére mutat. Ez az iterátor nem használható a hivatkozott objektum módosítására, mivel [GetEnumerator()](../ienumerable/getenumerator/) egy T másolatát adja vissza. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Iterátort ad, amely a gyűjtemény const-kvalifikált példányának első (ha van) elemére mutat. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Iterátort ad, amely a gyűjtemény első const-kvalifikált (ha van) elemére mutat. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Iterátort ad, amely a gyűjtemény utolsó const-kvalifikált (ha van) elemét követő pozícióra mutat. |
| virtual void [Clear](../icollection/clear/)() | Az összes elemet törli a gyűjteményből. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | Ellenőrzi, hogy az elem megtalálható-e a gyűjteményben. |
| virtual void [CopyTo](../icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | Az összes gyűjteményelemet meglévő tömb elemeire másolja. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Iterátort ad, amely a gyűjtemény utolsó (ha van) elemét követő pozícióra mutat. Ez az iterátor nem használható a hivatkozott objektum módosítására, mivel [GetEnumerator()](../ienumerable/getenumerator/) egy T másolatát adja vissza. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Iterátort ad, amely a const-kvalifikált példány utolsó (ha van) elemét követő pozícióra mutat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít a C# [Object.Equals](../../system/object/equals/) szintaxisával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual void [ExceptWith](./exceptwith/)([IEnumerablePtr](./ienumerableptr/)) | Elemcsoportot távolít el. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual int [get_Count](../icollection/get_count/)() const | Az elemek számát adja a gyűjteményben. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Ellenőrzi, hogy a gyűjtemény csak olvasható-e. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Az objektumot adja vissza, amelyen keresztül a gyűjtemény szinkronizálva van. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát adja. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](../ienumerable/getenumerator/)() | Enumerátort ad. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
|  [ICollection](../icollection/icollection/)() | Alapértelmezett konstruktor. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Másoló konstruktor. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Mozgató konstruktor. |
| virtual void [IntersectWith](./intersectwith/)([IEnumerablePtr](./ienumerableptr/)) | Eltávolítja azokat az elemeket, amelyek nincsenek jelen egy másik tárolóban. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| virtual **bool** [IsProperSubsetOf](./ispropersubsetof/)([IEnumerablePtr](./ienumerableptr/)) | Ellenőrzi, hogy a jelenlegi halmaz szigorú részhalmaza-e a másik tárolónak. |
| virtual **bool** [IsProperSupersetOf](./ispropersupersetof/)([IEnumerablePtr](./ienumerableptr/)) | Ellenőrzi, hogy a jelenlegi halmaz szigorú fölhalmaza-e a másik tárolónak. |
| virtual **bool** [IsSubsetOf](./issubsetof/)([IEnumerablePtr](./ienumerableptr/)) | Ellenőrzi, hogy a jelenlegi halmaz részhalmaza-e a másik tárolónak. |
| virtual **bool** [IsSupersetOf](./issupersetof/)([IEnumerablePtr](./ienumerableptr/)) | Ellenőrzi, hogy a jelenlegi halmaz fölhalmaza-e a másik tárolónak. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Akumulátor függvényt alkalmaz egy sorozatra. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat minden eleme megfelel-e a feltételnek. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Megállapítja, hogy a sorozat tartalmaz-e elemeket. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozatban létezik-e olyan elem, amely megfelel a feltételnek. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Kiszámítja a numerikus értékek sorozatának átlagát. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Kiszámítja egy sorozat értékeinek átlagát, amelyeket egy transzformáló függvény alkalmazásával nyerünk minden bemeneti elemre. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Átalakítja az elemeket a megadott típusra. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Két sorozatot összefűz. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Megállapítja, hogy a sorozat tartalmazza-e a megadott értéket. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálással). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat azon elemeinek számát, amelyek megfelelnek a megadott feltételnek. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Visszaadja a sorozat adott indexű elemét. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Visszaadja a sorozat adott indexű elemét. |
| T [LINQ_First](../ienumerable/linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat első olyan elemét, amely megfelel a megadott feltételnek. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Visszaadja a sorozat első, a feltételt teljesítő elemét, vagy egy alapértelmezett értéket, ha nincs ilyen elem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Csoportosítja a sorozat elemeit. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Csoportosítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Visszaadja a sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Visszaadja a sorozat utolsó elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden általános sorozat elemére meghív egy transzformáló függvényt, és visszaadja a legnagyobb eredményt. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden általános sorozat elemére meghív egy transzformáló függvényt, és visszaadja a legkisebb eredményt. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | A sorozat elemeit szűri a megadott típus alapján. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Rendezi a sorozat elemeit növekvő sorrendbe a keySelector által kiválasztott kulcsértékek szerint. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Rendezi a sorozat elemeit csökkenő sorrendbe a keySelector által kiválasztott kulcsértékek szerint. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Megfordítja a sorozat elemeinek sorrendjét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Átalakítja egy sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Minden sorozat elemet új formába alakít át, miközben beépíti az elem indexét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Minden sorozat elemét projekciózza, és az eredményül kapott sorozatokat egyetlen sorozatba egyesíti. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Kihagy egy megadott számú egymást követő elemet a sorozat elejéről, majd visszaadja a maradékot. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Visszaad egy megadott számú egymást követő elemet a sorozat elejéről. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Tömböt hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | List<T>-t hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Szűri a sorozatot a megadott predikátum alapján. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) jelző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi a leszármazottak másoló konstruktorát. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Mozgató hozzárendelő operátor. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Mozgató hozzárendelő operátor. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelő operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi a leszármazottak másoló konstruktorát. |
| virtual **bool** [Overlaps](./overlaps/)([IEnumerablePtr](./ienumerableptr/)) | Ellenőrzi, hogy a halmaz átfed-e egy másik tárolóval. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja az értéktípusú objektumot a nullptr-tél. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetén. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | Törli az elemet a gyűjteményből. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual **bool** [SetEquals](./setequals/)([IEnumerablePtr](./ienumerableptr/)) | Ellenőrzi, hogy a halmaz és a tároló ugyanazokat az elemeket tartalmazzák-e. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá (a megosztott helyett) állítja. Lehetővé teszi a mutatók konténerekben gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referenciaszámláló aktuális értékét adja. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual void [SymmetricExceptWith](./symmetricexceptwith/)([IEnumerablePtr](./ienumerableptr/)) | Kiszámítja két tároló szimmetrikus differenciáját. Eltávolítja a mindkét tárolóban jelen lévő elemeket, de eközben hozzáadja a **other**-ben jelen lévő, de a jelenlegi halmazban hiányzó elemeket. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| virtual void [UnionWith](./unionwith/)([IEnumerablePtr](./ienumerableptr/)) | Hozzáadja a megadott gyűjtemény olyan elemeit, amelyek még nem szerepelnek a jelenlegi halmazban. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) jelző objektumot. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | A jelenlegi tároló begin const iterátorának implementációját adja. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | A jelenlegi tároló begin iterátorának implementációját adja. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | A jelenlegi tároló end const iterátorának implementációját adja. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | A jelenlegi tároló end iterátorának implementációját adja. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~ICollection](../icollection/~icollection/)() | Felszabadító (destruktor). |
| virtual  [~ISet](./~iset/)() | Felszabadító (destruktor). |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Enumerable type to compare contents of current set to. |
## Lásd még

* Osztály [ICollection](../icollection/)
* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)