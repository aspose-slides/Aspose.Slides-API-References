---
title: ListExt
second_title: Aspose.Slides dla C++ – dokumentacja API
description: ogólna klasa List, która implementuje interfejs IListWrapper
type: docs
weight: 443
url: /pl/system.collections.generic/listext/
---
## ListExt klasa

generic [List](../list/) class that implements [IListWrapper](../../system.collections/ilistwrapper/) interface

```cpp
template<typename T>class ListExt : public System::Collections::Generic::List<T>,
                                    public System::Collections::IListWrapper
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [_add_range](../list/_add_range/)(std::initializer_list\<T\>) | Specyficzne dla C++. |
| void [Add](../list/add/)(const T\&) override | Dodaje element na koniec listy. |
| void [AddInitializer](../list/addinitializer/)(int, const T *) | Dodaje elementy do listy; używane przy tłumaczeniu inicjalizatorów. |
| void [AddRange](../list/addrange/)([IEnumerablePtr](../list/ienumerableptr/)) | Dodaje wszystkie elementy z kolekcji (lub z samej siebie) na koniec bieżącej listy. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../list/asreadonly/)() | Zwraca referencję tylko do odczytu do tej kolekcji. |
| [iterator](../ienumerable/iterator/) [begin](../list/begin/)() | Zwraca iterator do pierwszego elementu kolekcji. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../list/begin/)() const | Zwraca iterator do pierwszego elementu kolekcji oznaczonej jako const. |
| int [BinarySearch](../list/binarysearch/)(const T\&) const | Wyszukuje element w posortowanej liście. |
| int [BinarySearch](../list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Wyszukuje element w posortowanej liście. |
| int [BinarySearch](../list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Wyszukuje element w posortowanej liście. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../list/cbegin/)() const | Zwraca iterator do pierwszego elementu kolekcji oznaczonego jako const. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../list/cend/)() const | Zwraca iterator do nieistniejącego elementu oznaczonego jako const za końcem kolekcji. |
| void [Clear](../list/clear/)() override | Usuwa wszystkie elementy. |
| **bool** [Contains](../list/contains/)(const T\&) const override | Sprawdza, czy element znajduje się na liście. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<OutputType\>\> [ConvertAll](../list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Tworzy listę elementów przekonwertowanych na inny typ. |
| void [CopyTo](../list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Kopiuje elementy listy do istniejących elementów tablicy. |
| void [CopyTo](../list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Kopiuje wszystkie elementy do istniejących elementów tablicy. |
| void [CopyTo](../list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Kopiuje elementy zaczynając od określonego indeksu do istniejących elementów tablicy. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crbegin](../list/crbegin/)() const | Zwraca iterator odwrotny do ostatniego elementu oznaczonego jako const w kolekcji (pierwszy w odwróconym porządku). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CreateIListWrapper](./createilistwrapper/)() override | [IListWrapper](../../system.collections/ilistwrapper/) implementacja interfejsu. |
| std::enable_if\<[System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) pomocnik implementacji dla typów referencyjnych. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[System::IsBoxable](../../system/isboxable/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) pomocnik implementacji dla typów wartościowych. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![System::IsBoxable](../../system/isboxable/)\<T\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) pomocnik implementacji dla innych typów. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crend](../list/crend/)() const | Zwraca iterator odwrotny do nieistniejącego elementu oznaczonego jako const przed początkiem kolekcji. |
| [vector_t](../list/vector_t/)\& [data](../list/data/)() | Funkcja dostępu do podstawowej struktury danych. |
| const [vector_t](../list/vector_t/)\& [data](../list/data/)() const | Funkcja dostępu do podstawowej struktury danych. |
| [iterator](../ienumerable/iterator/) [end](../list/end/)() | Zwraca iterator do nieistniejącego elementu za końcem kolekcji. |
| [const_iterator](../ienumerable/const_iterator/) [end](../list/end/)() const | Zwraca iterator do nieistniejącego elementu za końcem kolekcji oznaczonej jako const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| **bool** [Exists](../list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Sprawdza, czy element spełniający określony predykat istnieje na liście. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| T [Find](../list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Wyszukuje element spełniający określony predykat. |
| [ListPtr](../listptr/)\<T\> [FindAll](../list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Wyszukuje elementy spełniające określony predykat. |
| int [FindIndex](../list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Wyszukuje element spełniający określony predykat. |
| int [FindIndex](../list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Wyszukuje element spełniający określony predykat. |
| int [FindIndex](../list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Wyszukuje element spełniający określony predykat. |
| T [FindLast](../list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Wyszukuje ostatni element spełniający określony predykat. |
| void [ForEach](../list/foreach/)([System::Action](../../system/action/)\<T\>) | Zastosowuje akcję do wszystkich elementów na liście. |
| int [get_Capacity](../list/get_capacity/)() const | Zwraca aktualną pojemność listy. |
| int [get_Count](../list/get_count/)() const override | Zwraca liczbę elementów w bieżącej liście. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Sprawdza, czy kolekcja ma stały rozmiar. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Sprawdza, czy kolekcja jest tylko do odczytu. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Zwraca obiekt, przez który kolekcja jest synchronizowana. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę danych licznika referencji powiązaną z obiektem. |
| [IEnumeratorPtr](../list/ienumeratorptr/) [GetEnumerator](../list/getenumerator/)() override | Zwraca enumerator do iteracji po elementach listy. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda do C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| **ThisPtr** [GetRange](../list/getrange/)(int, int) | Tworzy wycinek listy. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Analogiczna metoda do wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Konstruktor domyślny. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Konstruktor kopiujący. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Konstruktor przenoszący. |
| T [idx_get](../list/idx_get/)(int) const override | Zwraca element na określonej pozycji. |
| void [idx_set](../list/idx_set/)(int, T) override | Ustawia element na określonej pozycji. |
| int [IndexOf](../list/indexof/)(const T\&) const override | Zwraca pierwszy indeks określonego elementu. |
| int [IndexOf](../list/indexof/)(const T\&, int) const | Wyszukuje określony element na liście. |
| void [Insert](../list/insert/)(int, const T\&) override | Wstawia element na określonej pozycji. |
| void [InsertRange](../list/insertrange/)(int, [IEnumerablePtr](../list/ienumerableptr/)) | Wstawia zakres danych na określonej pozycji. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny operator C# 'is'. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&) const | Wyszukuje określony obiekt i zwraca indeks zerowy ostatniego wystąpienia w całej liście. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**) const | Wyszukuje określony obiekt i zwraca indeks zerowy ostatniego wystąpienia w przedziale elementów w [List](../list/), rozciągającym się od pierwszego elementu do określonego indeksu. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Wyszukuje określony obiekt i zwraca indeks zerowy ostatniego wystąpienia w przedziale elementów w [List](../list/), który zawiera określoną liczbę elementów i kończy się na podanym indeksie. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Zastosowuje funkcję akumulatora na sekwencji. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Określa, czy wszystkie elementy sekwencji spełniają warunek. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Określa, czy sekwencja zawiera jakiekolwiek elementy. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Określa, czy istnieje jakikolwiek element sekwencji lub czy spełnia warunek. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Oblicza średnią z sekwencji wartości numerycznych. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Oblicza średnią z sekwencji wartości uzyskanych poprzez wywołanie funkcji przekształcającej na każdym elemencie sekwencji wejściowej. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Rzutuje elementy na określony typ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Łączy dwie sekwencje. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Określa, czy sekwencja zawiera określoną wartość. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Zwraca liczbę elementów w sekwencji (obliczoną przez bezpośrednie zliczanie). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Zwraca liczbę elementów w sekwencji, które spełniają określony warunek. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Zwraca element pod określonym indeksem w sekwencji. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Zwraca element pod określonym indeksem w sekwencji. |
| T [LINQ_First](../ienumerable/linq_first/)() | Zwraca pierwszy element sekwencji. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Zwraca pierwszy element sekwencji, który spełnia określony warunek. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Zwraca pierwszy element sekwencji lub wartość domyślną, jeśli sekwencja jest pusta. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Zwraca pierwszy element sekwencji spełniający warunek lub wartość domyślną, jeśli nie znaleziono takiego elementu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Grupuje elementy sekwencji. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Grupuje elementy sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Zwraca ostatni element sekwencji. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Zwraca ostatni element sekwencji lub wartość domyślną, jeśli sekwencja jest pusta. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Wywołuje funkcję przekształcającą na każdym elemencie generycznej sekwencji i zwraca maksymalną otrzymaną wartość. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Wywołuje funkcję przekształcającą na każdym elemencie generycznej sekwencji i zwraca minimalną otrzymaną wartość. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtruje elementy sekwencji na podstawie określonego typu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortuje elementy sekwencji w kolejności rosnącej według wartości klucza wybranego przez keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortuje elementy sekwencji w kolejności malejącej według wartości klucza wybranego przez keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Odwraca kolejność elementów w sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Przekształca elementy sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Przekształca każdy element sekwencji w nową formę, uwzględniając indeks elementu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projektuje każdy element sekwencji i łączy otrzymane sekwencje w jedną sekwencję. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Pomiętuje określoną liczbę kolejnych elementów od początku sekwencji i zwraca resztę. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Zwraca określoną liczbę kolejnych elementów od początku sekwencji. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Tworzy tablicę z sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Tworzy List<T> z sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtruje sekwencję na podstawie określonego predykatu. |
|  [List](../list/list/)() | Tworzy pustą listę. |
|  [List](../list/list/)(int) | Tworzy listę z uprzednio określoną pojemnością. |
|  [List](../list/list/)([IEnumerablePtr](../list/ienumerableptr/)) | Konstruktor kopiujący. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda do C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operator przypisania przenoszącego. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operator przypisania przenoszącego. |
| vector_t::reference [operator[]](../list/operator[]/)(int) | Funkcja dostępowa. |
| vector_t::const_reference [operator[]](../list/operator[]/)(int) const | Funkcja dostępowa. |
| [reverse_iterator](../list/reverse_iterator/) [rbegin](../list/rbegin/)() | Zwraca iterator odwrotny do ostatniego elementu kolekcji (pierwszy w odwróconym porządku). |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rbegin](../list/rbegin/)() const | Zwraca iterator odwrotny do ostatniego elementu kolekcji oznaczonej jako const (pierwszy w odwróconym porządku). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| **bool** [Remove](../list/remove/)(const T\&) override | Usuwa pierwsze wystąpienie określonego elementu z listy. |
| int [RemoveAll](../list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Usuwa wszystkie elementy spełniające określony predykat. |
| void [RemoveAt](../list/removeat/)(int) override | Usuwa element na określonej pozycji. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| void [RemoveRange](../list/removerange/)(int, int) | Usuwa wycinek listy. |
| [reverse_iterator](../list/reverse_iterator/) [rend](../list/rend/)() | Zwraca iterator odwrotny do nieistniejącego elementu przed początkiem kolekcji. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rend](../list/rend/)() const | Zwraca iterator odwrotny do nieistniejącego elementu przed początkiem kolekcji oznaczonej jako const. |
| void [Reverse](../list/reverse/)() | Odwraca kolejność elementów całej listy. |
| void [Reverse](../list/reverse/)(int, int) | Odwraca kolejność elementów wycinka listy. |
| void [set_Capacity](../list/set_capacity/)(int) | Ustawia pojemność listy. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako wskaźnik słaby (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [Sort](../list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Sortuje elementy w liście. |
| void [Sort](../list/sort/)() | Sortuje elementy w liście używając domyślnego komparatora. |
| void [Sort](../list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Sortuje elementy w wycinku listy. |
| void [Sort](../list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Sortuje elementy w liście. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../list/toarray/)() const | Konwertuje listę na tablicę. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda do C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na ciąg znaków. |
| void [TrimExcess](../list/trimexcess/)() | Ustawia pojemność listy tak, aby pasowała do jej rozmiaru. |
| **bool** [TrueForAll](../list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Określa, czy każdy element w kolekcji spełnia warunki określone przez podany predykat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../list/virtualizebeginconstiterator/)() const override | Zwraca implementację iteratora begin const dla bieżącego kontenera. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../list/virtualizebeginiterator/)() override | Zwraca implementację iteratora begin dla bieżącego kontenera. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../list/virtualizeendconstiterator/)() const override | Zwraca implementację iteratora end const dla bieżącego kontenera. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../list/virtualizeenditerator/)() override | Zwraca implementację iteratora end dla bieżącego kontenera. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [ThisType](./thistype/) |  |
| [ListType](./listtype/) |  |
| [BaseTypes](./basetypes/) |  |
| [ValueType](./valuetype/) |  |
| [BaseType](./basetype/) |  |

## Zobacz także

* Klasa [List](../list/)
* Klasa [IListWrapper](../../system.collections/ilistwrapper/)
* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)