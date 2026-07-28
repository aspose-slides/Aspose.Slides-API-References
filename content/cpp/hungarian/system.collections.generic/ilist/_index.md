---
title: IList
second_title: Aspose.Slides for C++ API referencia
description: "Az elemek indexelt tárolójának interfésze. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mivel futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként történő függvényhívásokhoz."
type: docs
weight: 339
url: /hu/system.collections.generic/ilist/
---
## IList osztály

Az indexelt elemek tárolására szolgáló konténer interfésze. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mert az futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvényeknek argumentumként történő átadásához.

```cpp
template<typename T>class IList : public System::Collections::Generic::ICollection<T>
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Elem típusa. |

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual void [Add](../icollection/add/)(const T\&) | Elemet ad a gyűjteményhez. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Visszaad egy iterátort, amely az első (ha van) elemet mutatja a gyűjteményben. Ez az iterátor nem használható a hivatkozott objektum módosítására, mivel a [GetEnumerator()](../ienumerable/getenumerator/) egy T másolatobjektumot ad vissza. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Visszaad egy iterátort, amely a const-ként kvalifikált gyűjtemény példány első (ha van) elemére mutat. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Visszaad egy iterátort, amely a gyűjtemény első (ha van) const-ként kvalifikált elemére mutat. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Visszaad egy iterátort, amely a gyűjtemény utolsó (ha van) const-ként kvalifikált eleme utánra mutat. |
| virtual void [Clear](../icollection/clear/)() | Törli a gyűjtemény összes elemét. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | Ellenőrzi, hogy az elem jelen van-e a gyűjteményben. |
| virtual void [CopyTo](../icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | Átmásolja a gyűjtemény összes elemét a meglévő tömb elemeibe. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Visszaad egy iterátort, amely a gyűjtemény utolsó (ha van) elemét követő pozícióra mutat. Ez az iterátor nem használható a hivatkozott objektum módosítására, mivel a [GetEnumerator()](../ienumerable/getenumerator/) egy T másolatobjektumot ad vissza. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Visszaad egy iterátort, amely a const-ként kvalifikált gyűjtemény példány utolsó (ha van) elemét követő pozícióra mutat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Kizárólag belső célokra. |
| virtual int [get_Count](../icollection/get_count/)() const | Visszaadja a gyűjtemény elemeinek számát. |
| **bool** [get_IsFixedSize](./get_isfixedsize/)() | Ellenőrzi, hogy a gyűjtemény rögzített méretű-e. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Ellenőrzi, hogy a gyűjtemény csak olvasható-e. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Visszaadja azt az objektumot, amelyen keresztül a gyűjtemény szinkronizálva van. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektummal társított referenciacsökkentő adatstruktúrát. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](../ienumerable/getenumerator/)() | Visszaad egy enumerátort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [ICollection](../icollection/icollection/)() | Alapértelmezett konstruktor. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Másoló konstruktor. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Mozgató konstruktor. |
| virtual T [idx_get](./idx_get/)(int) const | Visszaadja a megadott indexű elemet. |
| virtual void [idx_set](./idx_set/)(int, T) | Beállítja a megadott indexű elemet. |
| virtual int [IndexOf](./indexof/)(const T\&) const | Visszaadja az elem első előfordulásának indexét a tárolóban. |
| virtual void [Insert](./insert/)(int, const T\&) | Beszúr egy elemet a megadott pozícióba, eltolva a többi elemet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Akkumulátor függvényt alkalmaz egy sorozatra. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozat minden eleme teljesíti-e a feltételt. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Megállapítja, hogy a sorozat tartalmaz-e elemeket. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Megállapítja, hogy a sorozatban létezik-e olyan elem, amely teljesíti a feltételt. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Számolja ki egy numerikus értékek sorozatának átlagát. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Számolja ki egy sorozat értékek átlagát, amelyeket a bemeneti sorozat elemein egy transzformáló függvény meghívásával kap. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Az elemeket a megadott típusra konvertálja. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Két sorozatot összefűz. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Megállapítja, hogy a sorozat tartalmazza-e a megadott értéket. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Visszaadja a sorozat elemeinek számát (közvetlen számlálással kiszámítva). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat elemeinek számát, amelyek teljesítik a megadott feltételt. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Visszaadja a sorozatban a megadott indexű elemet. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Visszaadja a sorozatban a megadott indexű elemet. |
| T [LINQ_First](../ienumerable/linq_first/)() | Visszaadja a sorozat első elemét. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Visszaadja a sorozat első olyan elemét, amely teljesíti a megadott feltételt. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Visszaadja a sorozat első elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Visszaadja a sorozat első olyan elemét, amely megfelel a feltételnek, vagy egy alapértelmezett értéket, ha nincs ilyen elem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Csoportosítja a sorozat elemeit. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Csoportosítja a sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Visszaadja a sorozat utolsó elemét. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Visszaadja a sorozat utolsó elemét, vagy egy alapértelmezett értéket, ha a sorozat üres. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden elemre egy transzformáló függvényt hív meg egy általános sorozatban, és visszaadja a legnagyobb eredményt. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Minden elemre egy transzformáló függvényt hív meg egy általános sorozatban, és visszaadja a legkisebb eredményt. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | A sorozat elemeit a megadott típus alapján szűri. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | A sorozat elemeit a keySelector által kiválasztott kulcsértékek szerint növekvő sorrendbe rendezi. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | A sorozat elemeit a keySelector által kiválasztott kulcsértékek szerint csökkenő sorrendbe rendezi. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Megfordítja a sorozat elemeinek sorrendjét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Átalakítja egy sorozat elemeit. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Átalakítja a sorozat minden elemét egy új formába, figyelembe véve az elem indexét. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Minden elemről egy sorozatot projekciózza, és az eredményül kapott sorozatokat egybe fűzi egy sorozatba. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Kihagy egy meghatározott számú egymást követő elemet a sorozat elejéről, és visszaadja a maradékot. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Visszaad egy meghatározott számú egymást követő elemet a sorozat elejéről. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Tömböt hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | List<T>-t hoz létre egy sorozatból. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | A sorozatot a megadott feltétel alapján szűri. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstruktorát. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Mozgató hozzárendelési operátor. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Mozgató hozzárendelési operátor. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetén. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | Törli az elemet a gyűjteményből. |
| virtual void [RemoveAt](./removeat/)(int) | Eltávolítja a megadott indexű elemet. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciacsökkentőt a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonparamétert gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók gyenge módra váltását a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referenciacsökkentő aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Megnöveli a megosztott referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Visszaadja a jelenlegi tároló kezdő const iterátorának megvalósítását. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Visszaadja a jelenlegi tároló kezdő iterátorának megvalósítását. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Visszaadja a jelenlegi tároló befejező const iterátorának megvalósítását. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Visszaadja a jelenlegi tároló befejező iterátorának megvalósítását. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Megnöveli a gyenge referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [BaseType](./basetype/) | Alaptípus. |
| [ThisType](./thistype/) | Ez a típus. |
| [ValueType](./valuetype/) | Értéktípus. |

## Lásd még

* Osztály [ICollection](../icollection/)
* Névterület [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)