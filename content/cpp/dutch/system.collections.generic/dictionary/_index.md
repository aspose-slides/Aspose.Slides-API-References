---
title: Dictionary
second_title: Aspose.Slides voor C++ API Referentie
description: Voorwaartse declaratie van de Dictionary-klasse.
type: docs
weight: 144
url: /nl/system.collections.generic/dictionary/
---
## Dictionary klasse

Forward declaration of [Dictionary](./) class.

```cpp
template<typename TKey,typename TValue>class Dictionary : public System::Collections::Generic::BaseDictionary<std::unordered_map<TKey, TValue, EqualityComparerHashAdapter<TKey>, EqualityComparerAdapter<TKey>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TKey | Sleuteltype. |
| TValue | Waardetype. |

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey\&, const TValue\&) | Voegt een sleutel-waarde paar toe aan de container. |
| virtual void [Add](../icollection/add/)(const T\&) | Voegt een element toe aan de collectie. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Haalt een iterator op die naar het eerste element (indien aanwezig) van de collectie wijst. Deze iterator kan niet worden gebruikt om een verwezen object te wijzigen omdat [GetEnumerator()](../ienumerable/getenumerator/) een kopie-object van T retourneert. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Haalt een iterator op die naar het eerste element (indien aanwezig) van de const-gekwalificeerde instantie van de collectie wijst. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Haalt een iterator op die naar het eerste const-gekwalificeerde element (indien aanwezig) van de collectie wijst. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Haalt een iterator op die direct na het laatste const-gekwalificeerde element (indien aanwezig) van de collectie wijst. |
| virtual void [Clear](../icollection/clear/)() | Verwijdert alle elementen uit de collectie. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | Controleert of het element aanwezig is in de collectie. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey\&) const | Controleert of de container de sleutel bevat. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | Kopieert de inhoud van de dictionary naar bestaande array-elementen. |
| [Dictionary](./dictionary/)() | Maakt een lege dictionary aan. |
| [Dictionary](./dictionary/)(const [map_t](./map_t/)\&) | Kopieert gegevens van de map. |
| [Dictionary](./dictionary/)(int) | Overload die overeenkomt met het maken van een vooraf gealloceerde dictionary; doet eigenlijk geen allocatie. |
| [Dictionary](./dictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&) | Copyconstructor. |
| [Dictionary](./dictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<TKey\>\>\&) | Copyconstructor. |
| [Dictionary](./dictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<TKey\>\>\&) | Maakt een lege dictionary aan. |
| [Dictionary](./dictionary/)(int, const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<TKey\>\>\&) | Maakt een lege dictionary aan. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Haalt een iterator op die direct na het laatste element (indien aanwezig) van de collectie wijst. Deze iterator kan niet worden gebruikt om een verwezen object te wijzigen omdat [GetEnumerator()](../ienumerable/getenumerator/) een kopie-object van T retourneert. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Haalt een iterator op die direct na het laatste element (indien aanwezig) van de const-gekwalificeerde instantie van de collectie wijst. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual int [get_Count](../icollection/get_count/)() const | Haalt het aantal elementen in de collectie op. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | Controleert of de grootte van de collectie vast is. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Controleert of de collectie alleen-lezen is. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | Controleert of de container thread-veilig is. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](../idictionary/get_keys/)() const | Benadert de sleutelcollectie. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Haalt het object op waarmee de collectie wordt gesynchroniseerd. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](../idictionary/get_values/)() const | Benadert de waardecollectie. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Maakt een enumerator-object aan. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&) const | Retourneert de waarde indien gevonden; anders **Value()**. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&, const TValue\&) const | Retourneert de waarde indien gevonden; anders **defaultValue**. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey\&) const | Retourneert de waarde indien gevonden; anders **null**, alleen zinvol voor referentietypen. |
| [ICollection](../icollection/icollection/)() | Standaardconstructor. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Copyconstructor. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Moveconstructor. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey\&) const | Getter-functie. |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey\&, TValue) | Setter-functie. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Past een accumulatorfunctie toe op een reeks. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bepaalt of alle elementen van een reeks aan een voorwaarde voldoen. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Bepaalt of een reeks elementen bevat. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bepaalt of er een element in de reeks bestaat of aan een voorwaarde voldoet. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Berekent het gemiddelde van een reeks numerieke waarden. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Berekent het gemiddelde van een reeks waarden die worden verkregen door een transformatiefunctie op elk element van de invoerreeks aan te roepen. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Cast de elementen naar het opgegeven type. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Voegt twee reeksen samen. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Bepaalt of een reeks een opgegeven waarde bevat. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Retourneert het aantal elementen in de reeks (berekend via directe telling). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retourneert het aantal elementen in de reeks die aan de opgegeven voorwaarde voldoen. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Retourneert het element op een opgegeven index in een reeks. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Retourneert het element op een opgegeven index in een reeks. |
| T [LINQ_First](../ienumerable/linq_first/)() | Retourneert het eerste element van een reeks. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retourneert het eerste element van een reeks dat aan de opgegeven voorwaarde voldoet. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Retourneert het eerste element van een reeks, of een standaardwaarde als de reeks leeg is. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Retourneert het eerste element van de reeks dat aan een voorwaarde voldoet of een standaardwaarde als zo'n element niet wordt gevonden. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Groepeert de elementen van een reeks. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Groepeert de elementen van een reeks. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Retourneert het laatste element van een reeks. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Retourneert het laatste element van een reeks, of een standaardwaarde als de reeks leeg is. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Roept een transformatiefunctie aan op elk element van een generieke reeks en retourneert de maximale resulterende waarde. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Roept een transformatiefunctie aan op elk element van een generieke reeks en retourneert de minimale resulterende waarde. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtert de elementen van de reeks op basis van het opgegeven type. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorteert de elementen van een reeks in oplopende volgorde volgens de sleutelwaarden geselecteerd door keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorteert de elementen van een reeks in aflopende volgorde volgens de sleutelwaarden geselecteerd door keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Keert de volgorde van de elementen in een reeks om. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformeert elementen van een reeks. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformeert elk element van een reeks naar een nieuwe vorm door de index van het element op te nemen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projetteert elk element van een reeks en combineert de resulterende reeksen tot één reeks. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Sla een opgegeven aantal aaneengesloten elementen vanaf het begin van een reeks over en retourneer de rest. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Retourneert een opgegeven aantal aaneengesloten elementen vanaf het begin van een reeks. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Maakt een array van een reeks. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Maakt een List<T> van een reeks. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtert een reeks op basis van het opgegeven predicaat. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
| [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copyconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te copy-constructeren. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Move-toewijzingsoperator. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Move-toewijzingsoperator. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te copy-constructeren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey\&) | Verwijdert de sleutel uit de container. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | Verwijdert het element uit de collectie. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in op een zwakke pointer (in plaats van gedeelde). Stelt toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey\&, TValue\&) const | Zoekt naar de waarde en haalt deze op indien gevonden. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het lock()-statement van C# voor ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Haalt de implementatie van de begin-const-iterator voor de huidige container op. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Haalt de implementatie van de begin-iterator voor de huidige container op. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Haalt de implementatie van de end-const-iterator voor de huidige container op. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Haalt de implementatie van de end-iterator voor de huidige container op. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [KeyCollection](./keycollection/) | Collection of keys to extract. |
| [ValueCollection](./valuecollection/) | Collection of values to extract. |
| [map_t](./map_t/) | Underlying data type. |
| [Ptr](./ptr/) | Pointer type. |
| [KVPair](./kvpair/) | Key-value pair type. |
| [IEnumerablePtr](./ienumerableptr/) | Pointer to enumerable interface. |
| [IEnumeratorPtr](./ienumeratorptr/) | Pointer to enumerator. |

## Opmerkingen

[Dictionary](./) die waarden naar sleutels mappt. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assert-fouten veroorzaakt. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om het door te geven aan functies als argument.

```cpp
#include <system/collections/dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Maak een instantie van de Dictionary-klasse.
  auto dictionary = MakeObject<Dictionary<int, String>>();

  // Vul de dictionary.
  dictionary->Add(0, u"Foo");
  dictionary->Add(1, u"Bar");
  dictionary->Add(2, u"Baz");

  // Print de items van de dictionary.
  for (const auto &pair: dictionary)
  {
    std::cout << pair.get_Key() << " - " << pair.get_Value() << std::endl;
  }

  return 0;
}
/*
Dit codevoorbeeld geeft de volgende output:
0 - Foo
1 - Bar
2 - Baz
*/
```

## Zie ook

* Klasse [BaseDictionary](../basedictionary/)
* Naamruimte [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)