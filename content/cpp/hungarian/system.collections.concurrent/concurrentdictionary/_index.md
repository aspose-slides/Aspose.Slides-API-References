---
title: ConcurrentDictionary
second_title: Aspose.Slides C++ API referenciája
description: "Szálbiztonságú szótár implementáció. Ennek az osztálynak az objektumait csak a System::MakeObject() függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényeknek."
type: docs
weight: 1
url: /hu/system.collections.concurrent/concurrentdictionary/
---
## ConcurrentDictionary osztály

Szálbiztonságú szótár implementáció. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) pointerbe, és használja ezt a pointert a függvényeknek argumentumként történő átadásához.

```cpp
template<class TKey,class TValue>class ConcurrentDictionary : public System::Collections::Generic::Dictionary<TKey, TValue>
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | Kulcs típusa. |
| TValue | Érték típusa. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [Add](./add/)(const TKey&, const TValue&) override | Értéket ad hozzá a szótárhoz. |
| virtual void [Add](../../system.collections.generic/idictionary/add/)(const TKey&, const TValue&) | Kulcs-érték párost ad a tárolóba. |
| virtual void [Add](../../system.collections.generic/icollection/add/)(const T&) | Elemet ad a gyűjteményhez. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Iterátort kap, amely az első (ha van) elemet mutatja a gyűjteményben. Ez az iterátor nem használható a hivatkozott objektum módosítására, mivel a [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) egy T másolatát adja vissza. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Iterátort kap, amely a const-kvalifikált példány első elemére mutat. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Iterátort kap, amely a const-kvalifikált gyűjtemény első elemére mutat. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Iterátort kap, amely a const-kvalifikált gyűjtemény utolsó elemét követi. |
| void [Clear](./clear/)() override | Törli a tároló összes elemét. |
| virtual **bool** [Contains](../../system.collections.generic/icollection/contains/)(const T&) const | Ellenőrzi, hogy az elem szerepel-e a gyűjteményben. |
| virtual **bool** [ContainsKey](../../system.collections.generic/idictionary/containskey/)(const TKey&) const | Ellenőrzi, hogy a tároló tartalmazza-e a kulcsot. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)<[System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)<TKey, TValue>>, int) override | A tároló elemeit létező tömb elemeibe másolja. |
| void [CopyTo](../../system.collections.generic/idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../../system.collections.generic/keyvaluepair/)<TKey, TValue>>, int) override | A szótár tartalmát létező tömb elemeibe másolja. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)() | Üres szótárat hoz létre. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [map_t](../../system.collections.generic/dictionary/map_t/)&) | Másolja az adatokat a térképből. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(int) | Túlterhelés, amely előre lefoglalt szótár létrehozásának felel meg; valójában nem hajt végre foglalást. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../../system.collections.generic/idictionary/)<TKey, TValue>> &) | Másoló konstruktor. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../../system.collections.generic/idictionary/)<TKey, TValue>>&, const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)<TKey>>&) | Másoló konstruktor. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)<TKey>> &) | Üres szótárat hoz létre. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(int, const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)<TKey>> &) | Üres szótárat hoz létre. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Iterátort kap, amely az utolsó (ha van) elem után mutat a gyűjteményben. Ez az iterátor nem használható a hivatkozott objektum módosítására, mivel a [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) egy T másolatát adja vissza. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Iterátort kap, amely a const-kvalifikált gyűjtemény utolsó (ha van) eleme után mutat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat C# [Object.Equals](../../system/object/equals/) szemantikai szabályaival hasonlítja össze. |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T1>::value&&![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Érték típusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Csak belső célokra. |
| virtual int [get_Count](../../system.collections.generic/icollection/get_count/)() const | A gyűjtemény elemeinek számát adja vissza. |
| **bool** [get_IsFixedSize](../../system.collections.generic/idictionary/get_isfixedsize/)() const | Ellenőrzi, hogy a gyűjtemény mérete rögzített-e. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | Ellenőrzi, hogy a gyűjtemény csak olvasható-e. |
| **bool** [get_IsSynchronized](../../system.collections.generic/idictionary/get_issynchronized/)() const | Ellenőrzi, hogy a tároló szálbiztonságú-e. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../../system.collections.generic/icollection/)<TKey>> [get_Keys](../../system.collections.generic/idictionary/get_keys/)() const | A kulcsgyűjteményt érheti el. |
| [SharedPtr](../../system/sharedptr/)<typename [ThisType::KeyCollection](../../system.collections.generic/dictionary/keycollection/)> [get_KeysInternal](./get_keysinternal/)() const override | Buborékgyűjteményt kap a szótár kulcsainak eléréséhez. |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Az objektumot adja vissza, amelyen keresztül a gyűjtemény szinkronizálva van. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../../system.collections.generic/icollection/)<TValue>> [get_Values](../../system.collections.generic/idictionary/get_values/)() const | Az értékgyűjteményt érheti el. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz kapcsolódó referencia számláló adatstruktúrát adja vissza. |
| [IEnumeratorPtr](../../system.collections.generic/dictionary/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/dictionary/getenumerator/)() override | Enumerátor objektumot hoz létre. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual TValue [GetValueOrDefault](../../system.collections.generic/idictionary/getvalueordefault/)(const TKey&) const | Visszaadja az értéket, ha megtalálja; egyébként **Value()**-t ad. |
| virtual TValue [GetValueOrDefault](../../system.collections.generic/idictionary/getvalueordefault/)(const TKey&, const TValue&) const | Visszaadja az értéket, ha megtalálja; egyébként **defaultValue**-t ad. |
| virtual TValue [GetValueOrNull](../../system.collections.generic/idictionary/getvalueornull/)(const TKey&) const | Visszaadja az értéket, ha megtalálja; egyébként **null**-t ad, ami csak referenciatípusoknál értelmezhető. |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | Alapértelmezett konstruktor. |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)&) | Másoló konstruktor. |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)&&) | Áthelyező konstruktor. |
| virtual TValue [idx_get](../../system.collections.generic/idictionary/idx_get/)(const TKey&) const | Lekérdező függvény. |
| void [idx_set](./idx_set/)(const TKey&, TValue) override | Beállítja az elemet egy adott pozíción. |
| virtual void [idx_set](../../system.collections.generic/idictionary/idx_set/)(const TKey&, TValue) | Beállító függvény. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# „is” operátor analógja. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | Akkumulátor függvényt alkalmaz egy sorozatra. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function<**bool**(T)>) | Megállapítja, hogy a sorozat minden eleme kielégít-e egy feltételt. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Megállapítja, hogy a sorozat tartalmaz-e bármely elemet. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function<**bool**(T)>) | Megállapítja, hogy van-e bármely elem a sorozatban, vagy egy feltételt kielégít-e. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Számolja ki egy numerikus értékek sorozatának átlagát. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | Kiszámítja egy sorozat értékek átlagát, amelyeket egy transzformáló függvény hívásával kapunk az input sorozat minden elemére. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Az elemeket a megadott típusra konvertálja. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> ) | Két sorozatot fűz össze. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Megállapítja, hogy a sorozat tartalmaz-e egy adott értéket. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálással). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | Visszaadja a sorozat azon elemeinek számát, amelyek megfelelnek a megadott feltételnek. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Visszaadja a sorozat adott indexű elemét. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Visszaadja a sorozat adott indexű elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | Visszaadja a sorozat első olyan elemét, amely megfelel a megadott feltételnek. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | Visszaadja a sorozat első olyan elemét, amely kielégít egy feltételt, vagy alapértelmezett értéket, ha nincs ilyen elem. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | Csoportosítja egy sorozat elemeit. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | Csoportosítja egy sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Visszaadja a sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Visszaadja a sorozat utolsó elemét, vagy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | Minden egyes elemre meghív egy transzformáló függvényt egy általános sorozaton, és visszaadja a legnagyobb eredményt. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | Minden elemre meghív egy transzformáló függvényt egy általános sorozaton, és visszaadja a legkisebb eredményt. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | A sorozat elemeit a megadott típus alapján szűri. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | Rendezi a sorozat elemeit növekvő sorrendbe a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | Rendezi a sorozat elemeit csökkenő sorrendbe a keySelector által kiválasztott kulcsértékek alapján. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Megfordítja egy sorozat elemeinek sorrendjét. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | Átalakítja egy sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | Minden elem új formává alakítja a sorozatban az elem indexének felhasználásával. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>>> &) | Minden elemre projekciót hajt végre a sorozatban és az eredményül kapott sorozatokat egy sorozatba egyesíti. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Kihagy egy meghatározott számú egymást követő elemet a sorozat elejéről, és a maradékot adja vissza. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Visszaad egy meghatározott számú egymást követő elemet a sorozat elejéről. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Tömböt hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)<[List](../../system.collections.generic/list/)<T>> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | List<T>-t hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function<**bool**(T)>) | Szűri a sorozatot a megadott predikátum alapján. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi alosztályok másolókonstrukcióját. |
| [ICollection](../../system.collections.generic/icollection/)& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)&&) | Áthelyező értékadó operátor. |
| [ICollection](../../system.collections.generic/icollection/)& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)&) | Áthelyező értékadó operátor. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Referencia szerint hasonlítja össze az értéktípust a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| **bool** [Remove](./remove/)(const TKey&) override | Eltávolít egy elemet a tárolóból. |
| virtual **bool** [Remove](../../system.collections.generic/idictionary/remove/)(const TKey&) | Eltávolít egy kulcsot a tárolóból. |
| virtual **bool** [Remove](../../system.collections.generic/icollection/remove/)(const T&) | Törli az elemet a gyűjteményből. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (nem megosztottra). Lehetővé teszi a mutatók átváltását gyenge módra a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok string-gé alakítását. |
| **bool** [TryAdd](./tryadd/)(const TKey&, const TValue&) | Megpróbál egy kulcs/érték párost hozzáadni a szótárhoz. |
| virtual **bool** [TryGetValue](../../system.collections.generic/idictionary/trygetvalue/)(const TKey&, TValue&) const | Megkeresi az értéket, és ha megtalálja, lekéri. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) szerkezetet. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Visszaadja a jelenlegi tároló begin const iterátorának implementációját. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Visszaadja a jelenlegi tároló begin iterátorának implementációját. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Visszaadja a jelenlegi tároló end const iterátorának implementációját. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Visszaadja a jelenlegi tároló end iterátorának implementációját. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Megsemmisítő. |
| virtual [~Object](../../system/object/~object/)() | Törli az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Typedef-ek

| Typedef | Leírás |
| --- | --- |
| [ThisType](./thistype/) | Ez a típus. |
| [BaseType](./basetype/) | Implementációs típus. |

## Megjegyzések



```cpp
#include <system/collections/concurrent/concurrent_dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  const int itemsCount = 32;

  // A ConcurrentDictionary osztálypéldány létrehozása.
  auto concurrentDictionary = MakeObject<ConcurrentDictionary<int, int>>();

  // Töltse fel a párhuzamos szótárt.
  for (auto i = 0; i < itemsCount; ++i)
  {
    concurrentDictionary->Add(i, i * i);
  }

  Console::WriteLine(concurrentDictionary->idx_get(3));

  return 0;
}
/*
Ez a kódrészlet a következő kimenetet adja:
9
*/
```

## Lásd még

* Class [Dictionary](../../system.collections.generic/dictionary/)
* Namespace [System::Collections::Concurrent](../)
* Library [Aspose.Slides](../../)