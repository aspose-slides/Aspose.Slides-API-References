---
title: BehaviorPropertyCollection
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Reprezentuje časové vlastnosti pro chování efektu.
type: docs
weight: 66
url: /cs/aspose.slides.animation/behaviorpropertycollection/
---
## BehaviorPropertyCollection třída

Represents timing properties for the effect behavior.

```cpp
class BehaviorPropertyCollection : public Aspose::Slides::Animation::IBehaviorPropertyCollection
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [Add](./add/)(const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) override | Přidá novou vlastnost do kolekce. |
| void [Add](./add/)(const [System::String](../../system/string/)\&) override | Přidá novou vlastnost do kolekce. |
| [iterator](./iterator/) [begin](./begin/)() | Získá iterátor ukazující na první prvek (je-li nějaký) kolekce. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Získá iterátor ukazující na první prvek (je-li nějaký) instance kolekce kvalifikované jako const. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Získá iterátor ukazující na první const-kvalifikovaný prvek (je-li nějaký) kolekce. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Získá iterátor ukazující těsně za posledním const-kvalifikovaným prvkem (je-li nějaký) kolekce. |
| void [Clear](./clear/)() override | Odstraní všechny vlastnosti z kolekce. |
| **bool** [Contains](./contains/)(const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) const override | Určuje, zda [ICollection](../../system.collections.generic/icollection/) obsahuje konkrétní hodnotu. |
| **bool** [Contains](./contains/)(const [System::String](../../system/string/)\&) const override | Určuje, zda [ICollection](../../system.collections.generic/icollection/) obsahuje konkrétní hodnotu. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\>, **int32_t**) override | Kopíruje prvky [ICollection](../../system.collections.generic/icollection/) do [System::Array](../../system/array/), počínaje konkrétním indexem [System::Array](../../system/array/). |
| virtual void [CopyTo](../../system.collections.generic/icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | Kopíruje všechny prvky kolekce do existujících prvků pole. |
| [iterator](./iterator/) [end](./end/)() | Získá iterátor ukazující těsně za posledním prvkem (je-li nějaký) kolekce. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Získá iterátor ukazující těsně za posledním prvkem (je-li nějaký) instance kolekce kvalifikované jako const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **int32_t** [get_Count](./get_count/)() const override | Vrací počet vlastností uložených v kolekci. Pouze pro čtení **int32_t**. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Kontroluje, zda je kolekce pevné velikosti. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Získá hodnotu indikující, zda je [ICollection](../../system.collections.generic/icollection/) pouze pro čtení. Pouze pro čtení **bool**. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Získá objekt, skrze který je kolekce synchronizována. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\>\> [GetEnumerator](./getenumerator/)() override | Vrací enumerátor, který prochází kolekcí. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Výchozí konstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Kopírovací konstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Přesunovací konstruktor. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\> [idx_get](./idx_get/)(**int32_t**) const override | Vrací vlastnost na zadaném indexu. |
| virtual T [idx_get](../../system.collections.generic/ilist/idx_get/)(int) const | Získá prvek na zadaném indexu. |
| void [idx_set](./idx_set/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>) override | Vrací vlastnost na zadaném indexu. |
| virtual void [idx_set](../../system.collections.generic/ilist/idx_set/)(int, T) | Nastaví prvek na zadaném indexu. |
| **int32_t** [IndexOf](./indexof/)(const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) const override | Určuje index konkrétní položky v [IList](../../system.collections.generic/ilist/). |
| **int32_t** [IndexOf](./indexof/)(const [System::String](../../system/string/)\&) const override | Určuje index konkrétní položky podle hodnoty vlastnosti v [IList](../../system.collections.generic/ilist/). |
| void [Insert](./insert/)(**int32_t**, const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) override | Vloží novou vlastnost do kolekce na zadaném indexu. |
| void [Insert](./insert/)(**int32_t**, [System::String](../../system/string/)) override | Vloží novou vlastnost (s danou hodnotou vlastnosti) do kolekce na zadaném indexu. |
| virtual void [Insert](../../system.collections.generic/ilist/insert/)(int, const T\&) | Vloží prvek do zadané pozice, posouvá ostatní prvky. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie C# operátoru 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Použije akumulační funkci na sekvenci. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Určuje, zda všechny prvky sekvence splňují podmínku. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Určuje, zda sekvence obsahuje nějaké prvky. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Určuje, zda existuje jakýkoli prvek sekvence nebo splňuje podmínku. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Vypočítá průměr sekvence číselných hodnot. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Vypočítá průměr sekvence hodnot získaných voláním transformační funkce na každém prvku vstupní sekvence. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Přetypuje prvky na zadaný typ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Spojí dvě sekvence. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Určuje, zda sekvence obsahuje zadanou hodnotu. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Vrací počet prvků v sekvenci (vypočítáno přímým počítáním). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Vrací počet prvků v sekvenci, které splňují zadanou podmínku. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Vrací prvek na zadaném indexu v sekvenci. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Vrací prvek na zadaném indexu v sekvenci. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Vrací první prvek sekvence. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Vrací první prvek sekvence, který splňuje zadanou podmínku. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Vrací první prvek sekvence, nebo výchozí hodnotu, pokud je sekvence prázdná. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Vrací první prvek sekvence, který splňuje podmínku, nebo výchozí hodnotu, pokud žádný takový prvek neexistuje. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Skupinuje prvky sekvence. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Skupinuje prvky sekvence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Vrací poslední prvek sekvence. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Vrací poslední prvek sekvence, nebo výchozí hodnotu, pokud je sekvence prázdná. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Vyvolá transformační funkci na každém prvku obecné sekvence a vrátí maximální vzniklou hodnotu. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Vyvolá transformační funkci na každém prvku obecné sekvence a vrátí minimální vzniklou hodnotu. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtruje prvky sekvence podle zadaného typu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Řadí prvky sekvence vzestupně podle hodnot klíčů vybraných pomocí keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Řadí prvky sekvence sestupně podle hodnot klíčů vybraných pomocí keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Obrátí pořadí prvků v sekvenci. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformuje prvky sekvence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformuje každý prvek sekvence do nového tvaru zahrnutím indexu prvku. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projektuje každý prvek sekvence a kombinuje vzniklé sekvence do jedné sekvence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Přeskočí zadaný počet souvislých prvků od začátku sekvence a vrátí zbytek. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Vrací zadaný počet souvislých prvků od začátku sekvence. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Vytvoří pole ze sekvence. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Vytvoří List<T> ze sekvence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtruje sekvenci podle zadaného predikátu. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Volat přímo nebo použít objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Operátor přiřazení přesunu. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Operátor přiřazení přesunu. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| **bool** [Remove](./remove/)(const [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorProperty](../ibehaviorproperty/)\>\&) override | Odstraní zadanou vlastnost z kolekce. |
| **bool** [Remove](./remove/)(const [System::String](../../system/string/)\&) override | Odstraní zadanou vlastnost z kolekce. |
| void [RemoveAt](./removeat/)(**int32_t**) override | Odstraní vlastnost na zadaném indexu. |
| virtual void [RemoveAt](../../system.collections.generic/ilist/removeat/)(int) | Odstraní prvek na zadaném indexu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Volat přímo nebo použít objekt [LockContext](../../system/lockcontext/). |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Získá iterátor ukazující na první prvek (je-li nějaký)instance kolekce kvalifikované jako const. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Získá iterátor ukazující na první prvek (je-li nějaký) kolekce. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Získá iterátor ukazující těsně za posledním prvkem (je-li nějaký)instance kolekce kvalifikované jako const. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() override | Získá iterátor ukazující těsně za posledním prvkem (je-li nějaký) kolekce. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Definice typů

| Typedef | Popis |
| --- | --- |
| [iterator_holder_type](./iterator_holder_type/) | Typ kolekce, jejíž typy iterátorů se používají jako typy iterátorů v aktuální kolekci. |
| [iterator](./iterator/) | Typ iterátoru. |
| [const_iterator](./const_iterator/) | Typ konstantního iterátoru. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Virtualizovaný typ prvku. |
| [virtualized_iterator](./virtualized_iterator/) | Virtualizovaný typ. |

## Viz také

* Třída [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)
* Jmenný prostor [Aspose::Slides::Animation](../)
* Knihovna [Aspose.Slides](../../)