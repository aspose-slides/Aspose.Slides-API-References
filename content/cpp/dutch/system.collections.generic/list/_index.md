---
title: List
second_title: Aspose.Slides voor C++ API-referentie
description: Forward declaratie van List.
type: docs
weight: 430
url: /nl/system.collections.generic/list/
---
## List klasse

[List](./) forward declaratie.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Elementtype. |

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++ specifiek. |
| void [Add](./add/)(const T\&) override | Voegt een element toe aan het einde van de lijst. |
| void [AddInitializer](./addinitializer/)(int, const T *) | Voegt elementen toe aan de lijst; gebruikt bij het vertalen van initialisatoren. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | Voegt alle elementen uit de collectie (of zichzelf) toe aan het einde van de huidige lijst. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | Haalt een alleen-lezen referentie op naar deze collectie. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Haalt iterator op naar het eerste element van de collectie. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Haalt iterator op naar het eerste element van de const-gekwalificeerde collectie. |
| int [BinarySearch](./binarysearch/)(const T\&) const | Zoekt naar een item in een gesorteerde lijst. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Zoekt naar een item in een gesorteerde lijst. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Zoekt naar een item in een gesorteerde lijst. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Haalt iterator op naar het eerste const-gekwalificeerde element van de collectie. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Haalt iterator op voor een niet-bestaand const-gekwalificeerd element achter het einde van de collectie. |
| void [Clear](./clear/)() override | Verwijdert alle elementen. |
| **bool** [Contains](./contains/)(const T\&) const override | Controleert of een item aanwezig is in de lijst. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Maakt een lijst van elementen die naar een ander type zijn geconverteerd. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Kopieert lijst elementen naar bestaande array-elementen. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Kopieert alle elementen naar bestaande array-elementen. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Kopieert elementen beginnend vanaf de opgegeven index naar bestaande array-elementen. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Haalt een reverse iterator op naar het laatste const-gekwalificeerde element van de collectie (eerste in reverse). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Haalt een reverse iterator op voor een niet-bestaand const-gekwalificeerd element vóór het begin van de collectie. |
| [vector_t](./vector_t/)\& [data](./data/)() | Toegangsfunctie tot onderliggende datastructuur. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | Toegangsfunctie tot onderliggende datastructuur. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Haalt iterator op voor een niet-bestaand element achter het einde van de collectie. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Haalt iterator op voor een niet-bestaand element achter het einde van de const-gekwalificeerde collectie. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | Controleert of een element dat voldoet aan een specifiek predicaat bestaat in de lijst. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | Zoekt naar een element dat voldoet aan een specifiek predicaat. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | Zoekt naar elementen die voldoen aan een specifiek predicaat. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Zoekt naar een element dat voldoet aan een specifiek predicaat. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Zoekt naar een element dat voldoet aan een specifiek predicaat. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Zoekt naar een element dat voldoet aan een specifiek predicaat. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Zoekt naar het laatste element dat voldoet aan een specifiek predicaat. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | Voert een actie uit op alle elementen in de lijst. |
| int [get_Capacity](./get_capacity/)() const | Haalt de huidige capaciteit van de lijst op. |
| int [get_Count](./get_count/)() const override | Haalt het aantal elementen in de huidige lijst op. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Controleert of de collectie een vaste grootte heeft. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Controleert of de collectie alleen-lezen is. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Haalt het object op waarmee de collectie wordt gesynchroniseerd. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Haalt enumerator op om door lijst-elementen te itereren. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Macht hash-generatie voor aangepaste objecten mogelijk. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | Maakt een slice van de lijst. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
|  [ICollection](../icollection/icollection/)() | Standaardconstructor. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Copy-constructor. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Move-constructor. |
| T [idx_get](./idx_get/)(int) const override | Haalt element op op een specifieke positie. |
| void [idx_set](./idx_set/)(int, T) override | Stelt element in op een specifieke positie. |
| int [IndexOf](./indexof/)(const T\&) const override | Haalt de eerste index van een specifiek item op. |
| int [IndexOf](./indexof/)(const T\&, int) const | Zoekt naar een specifiek item in de lijst. |
| void [Insert](./insert/)(int, const T\&) override | Voegt item in op opgegeven positie. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | Voegt een gegevensbereik in op een specifieke positie. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | Zoekt naar het opgegeven object en geeft de nul-gebaseerde index van de laatste voorkoming binnen de gehele lijst terug. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | Zoekt naar het opgegeven object en geeft de nul-gebaseerde index van de laatste voorkoming binnen het bereik van elementen in de [List](./) dat zich uitstrekt van het eerste element tot de opgegeven index terug. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Zoekt naar het opgegeven object en geeft de nul-gebaseerde index van de laatste voorkoming binnen het bereik van elementen in de [List](./) die het opgegeven aantal elementen bevat en eindigt op de opgegeven index terug. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Past een accumulator-functie toe op een reeks. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bepaalt of alle elementen van een reeks aan een voorwaarde voldoen. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Bepaalt of een reeks enige elementen bevat. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bepaalt of een element van een reeks bestaat of aan een voorwaarde voldoet. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Berekent het gemiddelde van een reeks numerieke waarden. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Berekent het gemiddelde van een reeks waarden die verkregen worden door een transformatie-functie op elk element van de invoerreeks aan te roepen. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Cast de elementen naar het opgegeven type. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Voegt twee reeksen samen. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Bepaalt of een reeks een opgegeven waarde bevat. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Retourneert het aantal elementen in de reeks (bepaald via directe telling). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retourneert het aantal elementen in de reeks die voldoen aan de opgegeven voorwaarde. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Retourneert het element op een opgegeven index in een reeks. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Retourneert het element op een opgegeven index in een reeks. |
| T [LINQ_First](../ienumerable/linq_first/)() | Retourneert het eerste element van een reeks. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retourneert het eerste element van een reeks dat voldoet aan de opgegeven voorwaarde. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Retourneert het eerste element van een reeks, of een standaardwaarde als de reeks leeg is. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Retourneert het eerste element van de reeks dat aan een voorwaarde voldoet, of een standaardwaarde als geen dergelijk element wordt gevonden. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Groepeert de elementen van een reeks. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Groepeert de elementen van een reeks. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Retourneert het laatste element van een reeks. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Retourneert het laatste element van een reeks, of een standaardwaarde als de reeks leeg is. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Roept een transformatie-functie aan op elk element van een generieke reeks en retourneert de maximale resulterende waarde. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Roept een transformatie-functie aan op elk element van een generieke reeks en retourneert de minimale resulterende waarde. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtert de elementen van de reeks op basis van het opgegeven type. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorteert de elementen van een reeks in oplopende volgorde volgens de sleutelwaarden geselecteerd door keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorteert de elementen van een reeks in aflopende volgorde volgens de sleutelwaarden geselecteerd door keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Keert de volgorde van de elementen in een reeks om. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformeert elementen van een reeks. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformeert elk element van een reeks in een nieuwe vorm door de index van het element mee te nemen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projiceert elk element van een reeks en combineert de resulterende reeksen tot één reeks. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Slaat een opgegeven aantal aaneengesloten elementen over vanaf het begin van een reeks en retourneert de rest. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Retourneert een opgegeven aantal aaneengesloten elementen vanaf het begin van een reeks. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Maakt een array aan uit een reeks. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Maakt een List<T> aan uit een reeks. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filttert een reeks op basis van het opgegeven predicaat. |
|  [List](./list/)() | Maakt een lege lijst aan. |
|  [List](./list/)(int) | Maakt een lijst aan met vooraf gedefinieerde capaciteit. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | Copy-constructor. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert enkel een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert enkel een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Move-toewijzingsoperator. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Move-toewijzingsoperator. |
| vector_t::reference [operator[]](./operator[]/)(int) | Toegangsfunctie. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Toegangsfunctie. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Haalt een reverse iterator op naar het laatste element van de collectie (eerste in reverse). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Haalt een reverse iterator op naar het laatste element van de const-gekwalificeerde collectie (eerste in reverse). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| **bool** [Remove](./remove/)(const T\&) override | Verwijdert de eerste instantie van een specifiek item uit de lijst. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Verwijdert alle elementen die overeenkomen met een specifiek predicaat. |
| void [RemoveAt](./removeat/)(int) override | Verwijdert item op opgegeven positie. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [RemoveRange](./removerange/)(int, int) | Verwijdert een slice van de lijst. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Haalt een reverse iterator op voor een niet-bestaand element vóór het begin van de collectie. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Haalt een reverse iterator op voor een niet-bestaand element vóór het begin van de const-gekwalificeerde collectie. |
| void [Reverse](./reverse/)() | Keert de volgorde van alle elementen in de lijst om. |
| void [Reverse](./reverse/)(int, int) | Keert de volgorde van de lijst-slice om. |
| void [set_Capacity](./set_capacity/)(int) | Stelt de capaciteit van de lijst in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een weak-pointer (in plaats van shared). Maakt het mogelijk om pointers in containers naar weak-modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Sorteert elementen in de lijst. |
| void [Sort](./sort/)() | Sorteert elementen in de lijst met de standaard comparator. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Sorteert elementen in de lijst-slice. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Sorteert elementen in de lijst. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Converteert lijst naar array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| void [TrimExcess](./trimexcess/)() | Stelt de lijstcapaciteit in op de grootte ervan. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Bepaalt of elk element in de collectie voldoet aan de voorwaarden gedefinieerd door het opgegeven predicaat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Haalt de implementatie van de begin-const-iterator voor de huidige container op. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Haalt de implementatie van de begin-iterator voor de huidige container op. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Haalt de implementatie van de eind-const-iterator voor de huidige container op. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Haalt de implementatie van de eind-iterator voor de huidige container op. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de weak-referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de weak-referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Verwijdert object. Vrijt alle interne datastructuren. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [ValueType](./valuetype/) | Dit type. |
| [BaseType](./basetype/) | Interface-type. |
| [vector_t](./vector_t/) | Onderliggende datatype. |
| [iterator](./iterator/) | Iterator-type. |
| [const_iterator](./const_iterator/) | Const-iterator-type. |
| [reverse_iterator](./reverse_iterator/) | Reverse-iterator-type. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const reverse-iterator-type. |
| [IEnumerablePtr](./ienumerableptr/) | Container die elementen van hetzelfde type bevat als wij. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** type. |

## Opmerkingen

[List](./) - wrapper rond std::vector die gebruikt moet worden in vertaalde code. Vereist operator == om geïmplementeerd te zijn voor het elementtype. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assert-fouten veroorzaakt. Plaats deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Maak de eerste lijst.
  auto list1 = MakeObject<List<int>>();

  // Vul de eerste lijst.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Sorteer de eerste lijst.
  // De items van de eerste lijst zullen zijn: {-5, 1, 3, 8}
  list1->Sort();

  // Verwijder het item op index 2.
  // De items van de eerste lijst zullen zijn: {-5, 1, 8}
  list1->RemoveAt(2);

  // Voeg het item in op index 1.
  // De items van de eerste lijst zullen zijn: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Maak de tweede lijst.
  auto list2 = MakeObject<List<int>>();

  // Vul de tweede lijst.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Voeg elementen van de tweede lijst toe aan de eerste.
  list1->AddRange(list2);

  // Print de items van de eerste lijst.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Dit codevoorbeeld geeft de volgende output:
- 5 15 1 8 10 20 30
*/
```

## Zie ook

* Klasse [Object](../../system/object/)
* Klasse [IList](../ilist/)
* Namespace [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)