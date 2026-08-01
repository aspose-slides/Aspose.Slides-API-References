---
title: X509ExtensionCollection
second_title: Aspose.Slides voor C++ API-referentie
description: "Collectie van extensie-objecten. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 157
url: /nl/system.security.cryptography.x509certificates/x509extensioncollection/
---
## X509ExtensionCollection klasse

Collectie van extensie-objecten. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om hem als argument aan functies door te geven.

```cpp
class X509ExtensionCollection : public System::Collections::Generic::List<SharedPtr<X509Extension>>
```

## Methoden

| Method | Description |
| --- | --- |
| void [_add_range](../../system.collections.generic/list/_add_range/)(std::initializer_list\<T\>) | Specifiek voor C++. |
| void [Add](../../system.collections.generic/list/add/)(const T\&) override | Voegt een element toe aan het einde van de lijst. |
| void [AddInitializer](../../system.collections.generic/list/addinitializer/)(int, const T *) | Voegt elementen toe aan de lijst; wordt gebruikt bij het vertalen van initializers. |
| void [AddRange](../../system.collections.generic/list/addrange/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Voegt alle elementen uit de collectie (of zichzelf) toe aan het einde van de huidige lijst. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../../system.collections.generic/list/asreadonly/)() | Haalt een alleen-lezen referentie naar deze collectie op. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/list/begin/)() | Haalt een iterator op naar het eerste element van de collectie. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/list/begin/)() const | Haalt een iterator op naar het eerste element van de const-gekwalificeerde collectie. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&) const | Zoekt naar een item in een gesorteerde lijst. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Zoekt naar een item in een gesorteerde lijst. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Zoekt naar een item in een gesorteerde lijst. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/list/cbegin/)() const | Haalt een iterator op naar het eerste const-gekwalificeerde element van de collectie. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/list/cend/)() const | Haalt een iterator op voor een niet-bestaand const-gekwalificeerd element achter het einde van de collectie. |
| void [Clear](../../system.collections.generic/list/clear/)() override | Verwijdert alle elementen. |
| **bool** [Contains](../../system.collections.generic/list/contains/)(const T\&) const override | Controleert of een item aanwezig is in de lijst. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<OutputType\>\> [ConvertAll](../../system.collections.generic/list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Maakt een lijst van elementen geconverteerd naar een ander type. |
| void [CopyTo](../../system.collections.generic/list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Kopieert lijstelementen naar bestaande array-elementen. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Kopieert alle elementen naar bestaande array-elementen. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Kopieert elementen beginnend bij de gespecificeerde index naar bestaande array-elementen. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crbegin](../../system.collections.generic/list/crbegin/)() const | Haalt een reverse-iterator op naar het laatste const-gekwalificeerde element van de collectie (eerste in reverse). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crend](../../system.collections.generic/list/crend/)() const | Haalt een reverse-iterator op voor een niet-bestaand const-gekwalificeerd element vóór het begin van de collectie. |
| [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() | Functie om toegang te krijgen tot de onderliggende datastructuur. |
| const [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() const | Functie om toegang te krijgen tot de onderliggende datastructuur. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/list/end/)() | Haalt een iterator op voor een niet-bestaand element achter het einde van de collectie. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/list/end/)() const | Haalt een iterator op voor een niet-bestaand element achter het einde van de const-gekwalificeerde collectie. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommavergelijking voor double waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| **bool** [Exists](../../system.collections.generic/list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Controleert of een element dat aan een specifieke predicate voldoet, bestaat in de lijst. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| T [Find](../../system.collections.generic/list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Zoekt naar een element dat aan een specifieke predicate voldoet. |
| [ListPtr](../../system.collections.generic/listptr/)\<T\> [FindAll](../../system.collections.generic/list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Zoekt naar elementen die aan een specifieke predicate voldoen. |
| int [FindIndex](../../system.collections.generic/list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Zoekt naar een element dat aan een specifieke predicate voldoet. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Zoekt naar een element dat aan een specifieke predicate voldoet. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Zoekt naar een element dat aan een specifieke predicate voldoet. |
| T [FindLast](../../system.collections.generic/list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Zoekt naar het laatste element dat aan een specifieke predicate voldoet. |
| void [ForEach](../../system.collections.generic/list/foreach/)([System::Action](../../system/action/)\<T\>) | Past een actie toe op alle elementen in de lijst. |
| int [get_Capacity](../../system.collections.generic/list/get_capacity/)() const | Haalt de huidige capaciteit van de lijst op. |
| int [get_Count](../../system.collections.generic/list/get_count/)() const override | Haalt het aantal elementen in de huidige lijst op. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Controleert of de collectie een vaste grootte heeft. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | Controleert of de collectie alleen-lezen is. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Haalt het object op waarmee de collectie gesynchroniseerd wordt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die met het object geassocieerd is. |
| [IEnumeratorPtr](../../system.collections.generic/list/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/list/getenumerator/)() override | Haalt een enumerator op om door de lijst-elementen te itereren. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hash van aangepaste objecten mogelijk. |
| **ThisPtr** [GetRange](../../system.collections.generic/list/getrange/)(int, int) | Creëert een slice van de lijst. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Standaardconstructor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Copy-constructor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Move-constructor. |
| [SharedPtr](../../system/sharedptr/)\<[X509Extension](../x509extension/)\> [idx_get](./idx_get/)(const [String](../../system/string/)\&) const | Accessor. Niet geïmplementeerd. |
| T [idx_get](../../system.collections.generic/list/idx_get/)(int) const override | Haalt element op op een specifieke positie. |
| void [idx_set](../../system.collections.generic/list/idx_set/)(int, T) override | Stelt element in op een specifieke positie. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&) const override | Haalt de eerste index op van een specifiek item. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&, int) const | Zoekt naar een specifiek item in de lijst. |
| void [Insert](../../system.collections.generic/list/insert/)(int, const T\&) override | Voegt een item in op een gespecificeerde positie. |
| void [InsertRange](../../system.collections.generic/list/insertrange/)(int, [IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Voegt een gegevensbereik in op een specifieke positie. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of een object een instantie is van het type beschreven door targetType. Analog van C# 'is' operator. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&) const | Zoekt naar het opgegeven object en retourneert de nulgebaseerde index van het laatste voorkomen in de gehele lijst. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**) const | Zoekt naar het opgegeven object en retourneert de nulgebaseerde index van het laatste voorkomen binnen het bereik van elementen in de [List](../../system.collections.generic/list/) dat zich uitstrekt van het eerste element tot de gespecificeerde index. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Zoekt naar het opgegeven object en retourneert de nulgebaseerde index van het laatste voorkomen binnen het bereik van elementen in de [List](../../system.collections.generic/list/) dat het opgegeven aantal elementen bevat en eindigt op de opgegeven index. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Past een accumulatorfunctie toe over een sequentie. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bepaalt of alle elementen van een sequentie aan een conditie voldoen. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Bepaalt of een sequentie enige elementen bevat. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bepaalt of een element van een sequentie bestaat of aan een conditie voldoet. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Berekent het gemiddelde van een sequentie numerieke waarden. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Berekent het gemiddelde van een sequentie waarden die verkregen worden door een transformatiefunctie toe te passen op elk element van de invoersequentie. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Cast de elementen naar het opgegeven type. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Voegt twee sequenties samen. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Bepaalt of een sequentie een opgegeven waarde bevat. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Retourneert het aantal elementen in de sequentie (berekend via directe telling). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retourneert het aantal elementen in de sequentie dat aan de opgegeven conditie voldoet. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Retourneert het element op een opgegeven index in een sequentie. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Retourneert het element op een opgegeven index in een sequentie. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Retourneert het eerste element van een sequentie. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retourneert het eerste element van een sequentie dat aan de opgegeven conditie voldoet. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Retourneert het eerste element van een sequentie, of een standaardwaarde als de sequentie leeg is. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Retourneert het eerste element van de sequentie dat aan een conditie voldoet of een standaardwaarde als geen dergelijk element gevonden wordt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Groepeert de elementen van een sequentie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Groepeert de elementen van een sequentie. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Retourneert het laatste element van een sequentie. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Retourneert het laatste element van een sequentie, of een standaardwaarde als de sequentie leeg is. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Roept een transformatiefunctie aan op elk element van een generieke sequentie en retourneert de maximale resulterende waarde. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Roept een transformatiefunctie aan op elk element van een generieke sequentie en retourneert de minimale resulterende waarde. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtert de elementen van de sequentie op basis van het opgegeven type. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorteert de elementen van een sequentie in oplopende volgorde volgens de sleutelwaarden geselecteerd door keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorteert de elementen van een sequentie in aflopende volgorde volgens de sleutelwaarden geselecteerd door keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Keert de volgorde van de elementen in een sequentie om. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformeert elementen van een sequentie. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformeert elk element van een sequentie naar een nieuwe vorm door de index van het element te gebruiken. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projetteert elk element van een sequentie en combineert de resulterende sequenties tot één sequentie. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Slaat een opgegeven aantal opeenvolgende elementen over vanaf het begin van een sequentie en retourneert de rest. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Retourneert een opgegeven aantal opeenvolgende elementen vanaf het begin van een sequentie. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Maakt een array aan uit een sequentie. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Maakt een List<T> aan uit een sequentie. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtert een sequentie op basis van de opgegeven predicate. |
|  [List](../../system.collections.generic/list/list/)() | Maakt een lege lijst aan. |
|  [List](../../system.collections.generic/list/list/)(int) | Maakt een lijst met vooraf gedefinieerde capaciteit. |
|  [List](../../system.collections.generic/list/list/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Copy-constructor. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert enkel een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert enkel een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Move-toewijzingsoperator. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Move-toewijzingsoperator. |
| vector_t::reference [operator[]](../../system.collections.generic/list/operator[]/)(int) | Accessor-functie. |
| vector_t::const_reference [operator[]](../../system.collections.generic/list/operator[]/)(int) const | Accessor-functie. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() | Haalt een reverse-iterator op naar het laatste element van de collectie (eerste in reverse). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() const | Haalt een reverse-iterator op naar het laatste element van de const-gekwalificeerde collectie (eerste in reverse). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| **bool** [Remove](../../system.collections.generic/list/remove/)(const T\&) override | Verwijdert de eerste instantie van een specifiek item uit de lijst. |
| int [RemoveAll](../../system.collections.generic/list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Verwijdert alle elementen die voldoen aan de specifieke predicate. |
| void [RemoveAt](../../system.collections.generic/list/removeat/)(int) override | Verwijdert een item op een gespecificeerde positie. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [RemoveRange](../../system.collections.generic/list/removerange/)(int, int) | Verwijdert een slice van de lijst. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() | Haalt een reverse-iterator op voor een niet-bestaand element vóór het begin van de collectie. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() const | Haalt een reverse-iterator op voor een niet-bestaand element vóór het begin van de const-gekwalificeerde collectie. |
| void [Reverse](../../system.collections.generic/list/reverse/)() | Keert de volgorde van de elementen van de gehele lijst om. |
| void [Reverse](../../system.collections.generic/list/reverse/)(int, int) | Keert de volgorde van de elementen van de lijst-slice om. |
| void [set_Capacity](../../system.collections.generic/list/set_capacity/)(int) | Stelt de capaciteit van de lijst in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers te wisselen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [Sort](../../system.collections.generic/list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Sorteert de elementen in de lijst. |
| void [Sort](../../system.collections.generic/list/sort/)() | Sorteert de elementen in de lijst met de standaard comparator. |
| void [Sort](../../system.collections.generic/list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>) | Sorteert de elementen in de lijst-slice. |
| void [Sort](../../system.collections.generic/list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Sorteert de elementen in de lijst. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../../system.collections.generic/list/toarray/)() const | Converteert de lijst naar een array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het omzetten van aangepaste objecten naar een string mogelijk. |
| void [TrimExcess](../../system.collections.generic/list/trimexcess/)() | Past de lijscapaciteit aan zodat deze overeenkomt met de grootte. |
| **bool** [TrueForAll](../../system.collections.generic/list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Bepaalt of elk element in de collectie voldoet aan de voorwaarden gedefinieerd door de opgegeven predicate. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentry object. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.generic/list/virtualizebeginconstiterator/)() const override | Haalt de implementatie op van de begin const iterator voor de huidige container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.generic/list/virtualizebeginiterator/)() override | Haalt de implementatie op van de begin iterator voor de huidige container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.generic/list/virtualizeendconstiterator/)() const override | Haalt de implementatie op van de end const iterator voor de huidige container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.generic/list/virtualizeenditerator/)() override | Haalt de implementatie op van de end iterator voor de huidige container. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [X509ExtensionCollection](./x509extensioncollection/)() | Construeert een lege collectie. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [List](../../system.collections.generic/list/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Bibliotheek [Aspose.Slides](../../)