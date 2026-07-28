---
title: BaseKVCollection
second_title: Aspose.Slides C++ API-referencia
description: "Közös kódot tartalmaz kulcs- vagy értékgyűjteményekhez. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként történő függvényhíváshoz."
type: docs
weight: 79
url: /hu/system.collections.generic/basekvcollection/
---
## BaseKVCollection osztály

Közös kódot tartalmaz a kulcs- vagy értékgyűjteményekhez. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként történő függvényhíváshoz.

```cpp
template<typename Dict,typename KV>class BaseKVCollection : public System::Collections::Generic::IKVCollection<KV>
```

### Template parameters

| Parameter | Description |
| --- | --- |
| Dict | [Dictionary](../dictionary/) type. |
| KV | Key or value type, whichever the interface is used for. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [Add](../ikvcollection/add/)(const T\&) override | Elemet ad a tárolóhoz. |
| [BaseKVCollection](./basekvcollection/)(const typename Dict::Ptr\&) | Gyűjteményt hoz létre. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Visszaad egy iterátort, amely a gyűjtemény első (ha van) elemére mutat. Ez az iterátor nem használható a hivatkozott objektum módosítására, mivel a [GetEnumerator()](../ienumerable/getenumerator/) egy T másolat-objektumot ad vissza. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Visszaad egy iterátort, amely a gyűjtemény const-kvalifikált példányának első (ha van) elemére mutat. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Visszaad egy iterátort, amely a gyűjtemény első const-kvalifikált (ha van) elemére mutat. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Visszaad egy iterátort, amely a gyűjtemény utolsó const-kvalifikált elemét követően mutat (ha van). |
| void [Clear](../ikvcollection/clear/)() override | Az összes elemet törli a tárolóból. |
| **bool** [Contains](../ikvcollection/contains/)(const T\&) const override | Ellenőrzi, hogy az elem jelen van-e a tárolóban. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<KV\>, int) override | Adatot másol a meglévő tömb elemeibe. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Visszaad egy iterátort, amely a gyűjtemény utolsó (ha van) elemét követően mutat. Ez az iterátor nem használható a hivatkozott objektum módosítására, mivel a [GetEnumerator()](../ienumerable/getenumerator/) egy T másolat-objektumot ad vissza. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Visszaad egy iterátort, amely a gyűjtemény const-kvalifikált példányának utolsó (ha van) elemét követően mutat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| int [get_Count](./get_count/)() const override | Az elemek számát adja vissza. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Ellenőrzi, hogy a gyűjtemény rögzített méretű-e. |
| **bool** [get_IsReadOnly](../ikvcollection/get_isreadonly/)() const override | Ellenőrzi, hogy a tároló csak olvasható-e. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Visszaadja azt az objektumot, amelyen keresztül a gyűjtemény szinkronizálva van. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektummal társított referenciacsökkentő adatstruktúrát adja vissza. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](../ikvcollection/getenumerator/)() | Visszaad egy enumerátort a tárolóhoz. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) módszer analógja. Engedélyezi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [ICollection](../icollection/icollection/)() | Alapértelmezett konstruktor. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Másoló konstruktor. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Mozgató konstruktor. |
| virtual T [idx_get](../ikvcollection/idx_get/)(int) const | Értékadó (getter) függvény. |
| void [idx_set](../ikvcollection/idx_set/)(int, T) override | Értékbeállító (setter) függvény. |
| int [IndexOf](../ikvcollection/indexof/)(const T\&) const override | Az elem indexét adja vissza a tárolóban. |
| void [Insert](../ikvcollection/insert/)(int, const T\&) override | Beszúr egy elemet a megadott pozícióba. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Akkumulátor függvényt alkalmaz egy sorozatra. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat minden eleme teljesíti-e a feltételt. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Megállapítja, hogy a sorozat tartalmaz-e elemeket. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat bármely eleme létezik-e vagy teljesíti-e a feltételt. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Kiszámítja egy numerikus értékek sorozatának átlagát. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Kiszámítja egy olyan értékek sorozatának átlagát, amelyet minden bemeneti elemre egy transzformáló függvény meghívásával kapunk. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Az elemeket a megadott típusra konvertálja. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Két sorozatot fűz össze. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Megállapítja, hogy a sorozat tartalmaz-e egy megadott értéket. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálással). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat azon elemeinek számát, amelyek megfelelnek a megadott feltételnek. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | A sorozat megadott indexű elemét adja vissza. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | A sorozat megadott indexű elemét adja vissza. |
| T [LINQ_First](../ienumerable/linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat első elemét, amely megfelel a megadott feltételnek. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Visszaadja a sorozat első olyan elemét, amely teljesíti a feltételt, vagy egy alapértelmezett értéket, ha nincs ilyen elem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | A sorozat elemeit csoportosítja. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | A sorozat elemeit csoportosítja. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Visszaadja a sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Visszaadja a sorozat utolsó elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden általános sorozat elemére egy transzformáló függvényt hív meg, és visszaadja a maximális eredményt. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden általános sorozat elemére egy transzformáló függvényt hív meg, és visszaadja a minimális eredményt. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | A sorozat elemeit a megadott típus alapján szűri. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | A sorozat elemeit növekvő sorrendbe rendezi a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | A sorozat elemeit csökkenő sorrendbe rendezi a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Megfordítja a sorozat elemeinek sorrendjét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Átalakítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Minden sorozat elemet új formába alakít át az elem indexének felhasználásával. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Minden sorozat elemét projekcióval egy sorozatba vetíti, és az eredményül kapott sorozatokat egybe fűzi. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Kihagy egy megadott számú egymást követő elemet a sorozat elejéről, és a maradékot adja vissza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | A sorozat elejéről visszaad egy megadott számú egymást követő elemet. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Tömböt hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | List<T>-t hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | A sorozatot a megadott predikátum alapján szűri. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Engedélyezi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Mozgató értékadási operátor. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Mozgató értékadási operátor. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az érték típusú objektumot a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) string és nullptr esetére specializálása. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) stringek esetére specializálása. |
| **bool** [Remove](../ikvcollection/remove/)(const T\&) override | Eltávolít egy elemet a tárolóból. |
| void [RemoveAt](../ikvcollection/removeat/)(int) override | Eltávolít egy elemet a megadott pozícióból. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Lehetővé teszi a fordítást, de valójában nem csinál semmit, mivel ez a struktúra nem birtokol adatot. |
| int [SharedCount](../../system/object/sharedcount/)() const | Az aktuális megosztott referenciaszámláló értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette okos mutatókat vagy ThisProtector-t kell használni. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette okos mutatókat vagy ThisProtector-t kell használni. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Visszaadja a jelenlegi tároló begin const iterátorának implementációját. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Visszaadja a jelenlegi tároló begin iterátorának implementációját. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Visszaadja a jelenlegi tároló end const iterátorának implementációját. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Visszaadja a jelenlegi tároló end iterátorának implementációját. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette okos mutatókat vagy ThisProtector-t kell használni. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette okos mutatókat vagy ThisProtector-t kell használni. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IKVCollection](../ikvcollection/)
* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)