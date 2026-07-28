---
title: SortedList
second_title: Aspose.Slides C++ API-referencia
description: "FlatMap struktúrát körülvevő rendezett lista. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként való átadáshoz a függvényeknek."
type: docs
weight: 547
url: /hu/system.collections.generic/sortedlist/
---
## SortedList osztály

A FlatMap struktúrát körülvevő rendezett lista. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként történő átadásra.

```cpp
template<typename TKey,typename TValue>class SortedList : public System::Collections::Generic::SortedListHelper<TKey, TValue>,
                                                          public System::Collections::Generic::BaseDictionary<Detail::FlatMap<TKey, TValue, ComparerAdapter<TKey>>>
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | Kulcs típusa. |
| TValue | Érték típusa. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey\&, const TValue\&) | Kulcs-érték párt ad a tárolóba. |
| virtual void [Add](../icollection/add/)(const T\&) | Elemet ad a gyűjteményhez. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Lekér egy iterátort, amely az első elemre (ha van) mutat a gyűjteményben. Ezt az iterátort nem lehet használni a hivatkozott objektum módosítására, mivel a [GetEnumerator()](../ienumerable/getenumerator/) T másolat-objektumot ad vissza. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Lekér egy iterátort, amely a gyűjtemény const-kijelölt példányának első elemére (ha van) mutat. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Lekér egy iterátort, amely a gyűjtemény első const-kijelölt elemére (ha van) mutat. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Lekér egy iterátort, amely a gyűjtemény utolsó const-kijelölt eleme utánra (ha van) mutat. |
| virtual void [Clear](../icollection/clear/)() | Törli a gyűjtemény összes elemét. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | Ellenőrzi, hogy az elem jelen van-e a gyűjteményben. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey\&) const | Ellenőrzi, hogy a tároló tartalmazza-e a kulcsot. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | A szótár tartalmát meglévő tömb elemeibe másolja. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Lekér egy fordított iterátort az utolsó const-kijelölt elemhez a gyűjteményben (első a visszafelé haladásnál). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Lekér egy fordított iterátort egy nem létező const-kijelölt elemhez a gyűjtemény eleje előtt. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Lekér egy iterátort, amely a gyűjtemény utolsó eleme utánra (ha van) mutat. Ezt az iterátort nem lehet használni a hivatkozott objektum módosítására, mivel a [GetEnumerator()](../ienumerable/getenumerator/) T másolat-objektumot ad vissza. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Lekér egy iterátort, amely a const-kijelölt gyűjtemény példány utolsó eleme utánra (ha van) mutat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, noha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, noha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| int [get_Capacity](./get_capacity/)() const | Lekéri a lista aktuális kapacitását. |
| virtual int [get_Count](../icollection/get_count/)() const | Lekéri a gyűjtemény elemeinek számát. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | Ellenőrzi, hogy a gyűjtemény mérete fix-e. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Ellenőrzi, hogy a gyűjtemény csak olvasható-e. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | Ellenőrzi, hogy a tároló szálbiztos-e. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IList](../ilist/)\<TKey\>\> [get_Keys](./get_keys/)() const | Hozzáfér a kulcsgyűjteményhez. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Lekéri azt az objektumot, amelyen keresztül a gyűjtemény szinkronizált. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IList](../ilist/)\<TValue\>\> [get_Values](./get_values/)() const | Hozzáfér az értékgyűjteményhez. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Lekéri a jelenlegi listán iteráló enumerátort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&) const | Visszaadja az értéket, ha megtalálja; egyébként **Value()**. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&, const TValue\&) const | Visszaadja az értéket, ha megtalálja; egyébként **defaultValue**. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey\&) const | Visszaadja az értéket, ha megtalálja; egyébként **null**, ami csak referencia típusoknál értelmezhető. |
| [ICollection](../icollection/icollection/)() | Alapértelmezett konstruktor. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Másoló konstruktor. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Áthelyező konstruktor. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey\&) const | Getter függvény. |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey\&, TValue) | Setter függvény. |
| int [IndexOfKey](./indexofkey/)(TKey) const | Keres egy adott kulcsot. |
| int [IndexOfValue](./indexofvalue/)(TValue) const | Keres egy adott értéket. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Akumulátor függvényt alkalmaz egy sorozatra. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Meghatározza, hogy a sorozat összes eleme megfelel-e a feltételnek. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Meghatározza, hogy a sorozat tartalmaz-e elemeket. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Meghatározza, hogy a sorozat bármely eleme létezik-e vagy megfelel-e a feltételnek. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Kiszámítja egy numerikus értékek sorozatának átlagát. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Kiszámítja egy olyan sorozat értékeinek átlagát, amelyet egy transzformációs függvény alkalmazásával kapunk a bemeneti sorozat minden elemére. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Átkonvertálja az elemeket a megadott típusra. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Két sorozatot konkatenál. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Meghatározza, hogy a sorozat tartalmazza-e a megadott értéket. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálással számolva). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat elemeinek számát, amelyek megfelelnek a megadott feltételnek. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Visszaadja a sorozat egy adott indexű elemét. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Visszaadja a sorozat egy adott indexű elemét. |
| T [LINQ_First](../ienumerable/linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja azt az első elemet a sorozatból, amely megfelel a megadott feltételnek. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Visszaadja a sorozat első elemet, amely teljesíti a feltételt, vagy egy alapértelmezett értéket, ha nincs ilyen elem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Csoportosítja a sorozat elemeit. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Csoportosítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Visszaadja a sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Visszaadja a sorozat utolsó elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden elemre meghív egy transzformációs függvényt egy általános sorozatban, és visszaadja a legnagyobb eredményt. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden elemre meghív egy transzformációs függvényt egy általános sorozatban, és visszaadja a legkisebb eredményt. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Szűri a sorozat elemeit a megadott típus szerint. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Rendezi a sorozat elemeit növekvő sorrendben a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Rendezi a sorozat elemeit csökkenő sorrendben a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Megfordítja a sorozat elemeinek sorrendjét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Átalakítja egy sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Minden elem egy új formára alakítja a sorozatban, beleértve az elem indexét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Minden elemet projekcióval dolgoz fel, és a kapott sorozatokat egyetlen sorozatba egyesíti. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Kihagy egy meghatározott számú egymást követő elemet a sorozat elejéről, és visszaadja a maradékot. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Visszaad egy meghatározott számú egymást követő elemet a sorozat elejéről. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Tömböt hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | List<T>-et hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Szűri a sorozatot a megadott predikátum alapján. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() nyilatkozat zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktálását. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Áthelyező hozzárendelési operátor. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Áthelyező hozzárendelési operátor. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktálását. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Lekér egy fordított iterátort a gyűjtemény utolsó eleméhez (első a visszafelé haladásnál). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Lekér egy fordított iterátort a const-kijelölt gyűjmenté utolsó eleméhez (első a visszafelé haladásnál). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat összehasonlít referenciaként. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat összehasonlít referenciaként. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia módon hasonlítja össze az értéktípusú objektumot a nullptr-al. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetén. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey\&) | Eltávolítja a kulcsot a tárolóból. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | Törli az elemet a gyűjteményből. |
| void [RemoveAt](./removeat/)(int) | Eltávolít egy elemet a megadott pozíción. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Lekér egy fordított iterátort egy nem létező elemhez a gyűjtemény eleje előtt. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Lekér egy fordított iterátort egy nem létező elemhez a const-kijelölt gyűjtemény eleje előtt. |
| void [set_Capacity](./set_capacity/)(int) | Beállítja a lista aktuális kapacitását. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett) állítja. Lehetővé teszi a mutatók átállítását gyenge módra a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [SortedList](./sortedlist/)() | Üres listát hoz létre. |
| [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<TKey\>\>\&) | Üres listát hoz létre. |
| [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&) | Másoló konstruktor. |
| [SortedList](./sortedlist/)(const [map_t](./map_t/)\&) | Másoló konstruktor. |
| [SortedList](./sortedlist/)(int) | Üres listát hoz létre. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey\&, TValue\&) const | Megkeresi az értéket és visszaadja, ha megtalálja. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() nyilatkozat feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Lekéri a jelenlegi tároló begin const iterátorának implementációját. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Lekéri a jelenlegi tároló begin iterátorának implementációját. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Lekéri a jelenlegi tároló end const iterátorának implementációját. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Lekéri a jelenlegi tároló end iterátorának implementációját. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [KeyCollection](./keycollection/) | Kulcsgyűjtemény típusa. |
| [ValueCollection](./valuecollection/) | Értékgyűjtemény típusa. |
| [map_t](./map_t/) | Alap adat típus. |
| [this_t](./this_t/) | Ez a típus. |
| [Ptr](./ptr/) | Mutató típus. |
| [KVPair](./kvpair/) | Kulcs-érték pár típus. |
| [IEnumerablePtr](./ienumerableptr/) | Azonos párok gyűjteménye típusa. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** típus. |
| [iterator](./iterator/) | Iterátor típus. |
| [const_iterator](./const_iterator/) | Const iterátor típus. |
| [reverse_iterator](./reverse_iterator/) | Fordított iterátor típus. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const fordított iterátor típus. |

## Lásd még

* Osztály [SortedListHelper](../sortedlisthelper/)
* Osztály [BaseDictionary](../basedictionary/)
* Névterület [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)