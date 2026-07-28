---
title: IEnumerable
second_title: Aspose.Slides C++ API referencia
description: Az objektum interfésze, amely enumerátort biztosít a benne lévő elemekhez.
type: docs
weight: 287
url: /hu/system.collections.generic/ienumerable/
---
## IEnumerable osztály


Interface of object providing enumerator on contained elements.

```cpp
template<typename T>class IEnumerable : public virtual System::Object
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Element type. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [iterator](./iterator/) [begin](./begin/)() | Lekéri az iterátort, amely a gyűjtemény első (ha van) elemére mutat. Ez az iterátor nem használható a hivatkozott objektum módosítására, mivel a [GetEnumerator()](./getenumerator/) egy T másolat-objektumot ad vissza. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Lekéri az iterátort, amely a gyűjtemény const-képzett példányának első (ha van) elemére mutat. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Lekéri az iterátort, amely a gyűjtemény első const-képzett (ha van) elemére mutat. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Hozzáfér az iterátorhoz, amely a gyűjtemény utolsó const-képzett (ha van) eleme után helyezkedik el. |
| [iterator](./iterator/) [end](./end/)() | Hozzáfér az iterátorhoz, amely a gyűjtemény utolsó (ha van) eleme után helyezkedik el. Ez az iterátor nem használható a hivatkozott objektum módosítására, mivel a [GetEnumerator()](./getenumerator/) egy T másolat-objektumot ad vissza. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Az iterátort adja vissza, amely a gyűjtemény const-képzett példányának utolsó (ha van) eleme után helyezkedik el. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantikája szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Hivatkozástípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, így a NaN-nal sem. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz társított referencia-számláló adatstruktúrát. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](./getenumerator/)() | Visszaad egy enumerátort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyéni objektumok hasítását. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívásának analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| T [LINQ_Aggregate](./linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Egy akkumulatív függvényt alkalmaz a sorozaton. |
| **bool** [LINQ_All](./linq_all/)(std::function\<**bool**(T)>) | Meghatározza, hogy a sorozat minden eleme teljesíti-e a feltételt. |
| **bool** [LINQ_Any](./linq_any/)() | Meghatározza, hogy a sorozat tartalmaz-e bármilyen elemet. |
| **bool** [LINQ_Any](./linq_any/)(std::function\<**bool**(T)>) | Meghatározza, hogy a sorozat bármely eleme létezik-e vagy teljesíti-e a feltételt. |
| T [LINQ_Average](./linq_average/)() | Kiszámítja egy numerikus értékek sorozatának átlagát. |
| ResultType [LINQ_Average](./linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Kiszámítja egy olyan értékek sorozatának átlagát, amelyet a bemeneti sorozat minden elemére alkalmazott transzformációs függvény ad. |
| ResultType [LINQ_Average](./linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_Cast](./linq_cast/)() | Átkonvertálja az elemeket a megadott típusra. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_Cast](./linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Concat](./linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\>) | Két sorozatot fűz össze. |
| **bool** [LINQ_Contains](./linq_contains/)(T) | Meghatározza, hogy a sorozat tartalmazza-e a megadott értéket. |
| int [LINQ_Count](./linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálással számolva). |
| int [LINQ_Count](./linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat azon elemeinek számát, amelyek megfelelnek a megadott feltételnek. |
| T [LINQ_ElementAt](./linq_elementat/)(int) | Visszaadja a sorozatban a megadott indexű elemet. |
| T [LINQ_ElementAtOrDefault](./linq_elementatordefault/)(int) | Visszaadja a sorozatban a megadott indexű elemet. |
| T [LINQ_First](./linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](./linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat első olyan elemét, amely megfelel a megadott feltételnek. |
| T [LINQ_FirstOrDefault](./linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](./linq_firstordefault/)(std::function\<**bool**(T)>) | Visszaadja a sorozat első, a feltételnek megfelelő elemét, vagy egy alapértelmezett értéket, ha nincs ilyen elem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](./linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Csoportosítja a sorozat elemeit. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](./linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Csoportosítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](./linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](./linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](./linq_last/)() | Visszaadja a sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](./linq_lastordefault/)() | Visszaadja a sorozat utolsó elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](./linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden egyes elemre meghív egy transzformációs függvényt egy generikus sorozatban, és visszaadja a legnagyobb eredményértéket. |
| ResultType [LINQ_Max](./linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](./linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden egyes elemre meghív egy transzformációs függvényt egy generikus sorozatban, és visszaadja a legkisebb eredményértéket. |
| ResultType [LINQ_Min](./linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_OfType](./linq_oftype/)() | Szűri a sorozat elemeit a megadott típus alapján. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_OfType](./linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](./linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Rendezés felfelé (növekvő) sorrendben a keySelector által kiválasztott kulcsértékek szerint. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](./linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](./linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Rendezés csökkenő sorrendben a keySelector által kiválasztott kulcsértékek szerint. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](./linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Reverse](./linq_reverse/)() | Az elemek sorrendjét megfordítja egy sorozatban. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_Select](./linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Átalakítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_Select](./linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Minden egyes elemet új formává alakít át, beépítve az elem indexét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_Select](./linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_Select](./linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_SelectMany](./linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\>\>\&) | Projekciót alkalmaz minden elemre, és a kapott sorozatokat egyesíti egy sorozatba. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_SelectMany](./linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Skip](./linq_skip/)(**int32_t**) | A sorozat elejéről egy meghatározott számú egymást követő elemet kihagy, és a maradékot adja vissza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Take](./linq_take/)(**int32_t**) | A sorozat elejéről egy meghatározott számú egymást követő elemet ad vissza. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](./linq_toarray/)() | Egy tömböt hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](./linq_tolist/)() | Egy List<T>-t hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Where](./linq_where/)(std::function\<**bool**(T)>) | Szűri egy sorozatot a megadott predikátum alapján. |
| void [Lock](../../system/object/lock/)() | Implementálja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolós konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolós konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Hivatkozási összehasonlítás értéktípusú objektum és nullptr között. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablon argumentumot egy gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók módosítását a tárolókban gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementálja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Implementálja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const | Visszaadja a jelenlegi tároló begin const iterátorának implementációját. |
| virtual [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() | Visszaadja a jelenlegi tároló begin iterátorának implementációját. |
| virtual [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const | Visszaadja a jelenlegi tároló end const iterátorának implementációját. |
| virtual [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() | Visszaadja a jelenlegi tároló end iterátorának implementációját. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Typedefek

| Typedef | Leírás |
| --- | --- |
| [IEnumeratorType](./ienumeratortype/) | Enumerátor típus. |
| [ValueType](./valuetype/) |  |
| [iterator](./iterator/) | Iterátor típus. |
| [const_iterator](./const_iterator/) | Const iterátor típus. |
| [virtualized_iterator](./virtualized_iterator/) | Belső iterátor alaptípus. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Belső iterátor elem típus. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)