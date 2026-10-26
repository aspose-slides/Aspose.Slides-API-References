---
title: List
second_title: Odniesienie API Aspose.Slides dla C++
description: Deklaracja w przód List.
type: docs
weight: 430
url: /pl/system.collections.generic/list/
---
## Klasa List

[List](./) deklaracja w przód.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu. |
## Metody

| Metoda | Opis |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | Specyficzne dla C++. |
| void [Add](./add/)(const T\&) override | Dodaje element na koniec listy. |
| void [AddInitializer](./addinitializer/)(int, const T *) | Dodaje elementy do listy; używane przy translacji inicjalizatorów. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | Dodaje wszystkie elementy z kolekcji (lub samej siebie) na koniec bieżącej listy. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | Zwraca referencję tylko do odczytu do tej kolekcji. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Zwraca iterator do pierwszego elementu kolekcji. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Zwraca iterator do pierwszego elementu kolekcji oznaczonej jako const. |
| int [BinarySearch](./binarysearch/)(const T\&) const | Wyszukuje element w posortowanej liście. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Wyszukuje element w posortowanej liście. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Wyszukuje element w posortowanej liście. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Zwraca iterator do pierwszego elementu kolekcji oznaczonego jako const. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Zwraca iterator do nieistniejącego elementu const za końcem kolekcji. |
| void [Clear](./clear/)() override | Usuwa wszystkie elementy. |
| **bool** [Contains](./contains/)(const T\&) const override | Sprawdza, czy element jest obecny na liście. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Tworzy listę elementów przekonwertowanych na inny typ. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Kopiuje elementy listy do istniejących elementów tablicy. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Kopiuje wszystkie elementy do istniejących elementów tablicy. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Kopiuje elementy zaczynając od określonego indeksu do istniejących elementów tablicy. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Zwraca iterator odwrotny do ostatniego elementu kolekcji oznaczonego jako const (pierwszy w odwróceniu). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Zwraca iterator odwrotny do nieistniejącego elementu const przed początkiem kolekcji. |
| [vector_t](./vector_t/)\& [data](./data/)() | Funkcja dostępu do wewnętrznej struktury danych. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | Funkcja dostępu do wewnętrznej struktury danych. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Zwraca iterator do nieistniejącego elementu za końcem kolekcji. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Zwraca iterator do nieistniejącego elementu za końcem kolekcji oznaczonej jako const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | Sprawdza, czy w liście istnieje element spełniający określony predykat. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | Wyszukuje element spełniający określony predykat. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | Wyszukuje elementy spełniające określony predykat. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Wyszukuje element spełniający określony predykat. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Wyszukuje element spełniający określony predykat. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Wyszukuje element spełniający określony predykat. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Wyszukuje ostatni element spełniający określony predykat. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | Zastosowuje akcję do wszystkich elementów listy. |
| int [get_Capacity](./get_capacity/)() const | Zwraca bieżącą pojemność listy. |
| int [get_Count](./get_count/)() const override | Zwraca liczbę elementów w bieżącej liście. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Sprawdza, czy kolekcja ma stały rozmiar. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Sprawdza, czy kolekcja jest tylko do odczytu. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Zwraca obiekt, przez który synchronizowana jest kolekcja. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę danych licznika referencji powiązaną z obiektem. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Zwraca enumerator do iteracji po elementach listy. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | Tworzy wycinek listy. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Konstruktor domyślny. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Konstruktor kopiujący. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Konstruktor przenoszący. |
| T [idx_get](./idx_get/)(int) const override | Zwraca element na określonej pozycji. |
| void [idx_set](./idx_set/)(int, T) override | Ustawia element na określonej pozycji. |
| int [IndexOf](./indexof/)(const T\&) const override | Zwraca pierwszy indeks określonego elementu. |
| int [IndexOf](./indexof/)(const T\&, int) const | Wyszukuje określony element w liście. |
| void [Insert](./insert/)(int, const T\&) override | Wstawia element na określonej pozycji. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | Wstawia zakres danych na określonej pozycji. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | Wyszukuje określony obiekt i zwraca indeks zerowy ostatniego wystąpienia w całej liście. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | Wyszukuje określony obiekt i zwraca indeks zerowy ostatniego wystąpienia w zakresie elementów [List](./) rozciągającym się od pierwszego elementu do określonego indeksu. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Wyszukuje określony obiekt i zwraca indeks zerowy ostatniego wystąpienia w zakresie elementów [List](./) zawierającym określoną liczbę elementów i kończącym się na określonym indeksie. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Stosuje funkcję akumulatora na sekwencji. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Określa, czy wszystkie elementy sekwencji spełniają warunek. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Określa, czy sekwencja zawiera jakiekolwiek elementy. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Określa, czy istnieje jakikolwiek element sekwencji lub spełnia warunek. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Oblicza średnią ciągu wartości numerycznych. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Oblicza średnią ciągu wartości, które są uzyskiwane przez wywołanie funkcji transformującej na każdym elemencie ciągu wejściowego. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Rzutuje elementy na określony typ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Konkatenacja dwóch sekwencji. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Określa, czy sekwencja zawiera określoną wartość. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Zwraca liczbę elementów w sekwencji (obliczaną poprzez bezpośrednie liczenie). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Zwraca liczbę elementów w sekwencji, które spełniają określony warunek. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Zwraca element o określonym indeksie w sekwencji. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Zwraca element o określonym indeksie w sekwencji. |
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
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Wywołuje funkcję transformującą na każdym elemencie ogólnej sekwencji i zwraca maksymalną otrzymaną wartość. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Wywołuje funkcję transformującą na każdym elemencie ogólnej sekwencji i zwraca minimalną otrzymaną wartość. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtruje elementy sekwencji według określonego typu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortuje elementy sekwencji rosnąco według wartości klucza wybranego przez keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortuje elementy sekwencji malejąco według wartości klucza wybranego przez keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Odwraca kolejność elementów w sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformuje elementy sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformuje każdy element sekwencji do nowej formy, uwzględniając indeks elementu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projektyuje każdy element sekwencji i łączy otrzymane sekwencje w jedną. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Pomija określoną liczbę kolejnych elementów od początku sekwencji i zwraca resztę. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Zwraca określoną liczbę kolejnych elementów od początku sekwencji. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Tworzy tablicę z sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Tworzy List<T> z sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtruje sekwencję według określonego predykatu. |
|  [List](./list/)() | Tworzy pustą listę. |
|  [List](./list/)(int) | Tworzy listę o zdefiniowanej wcześniej pojemności. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | Konstruktor kopiujący. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operator przypisania przenoszącego. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operator przypisania przenoszącego. |
| vector_t::reference [operator[]](./operator[]/)(int) | Funkcja dostępowa. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Funkcja dostępowa. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Zwraca iterator odwrotny do ostatniego elementu kolekcji (pierwszy w odwróceniu). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Zwraca iterator odwrotny do ostatniego elementu kolekcji oznaczonej jako const (pierwszy w odwróceniu). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| **bool** [Remove](./remove/)(const T\&) override | Usuwa pierwsze wystąpienie określonego elementu z listy. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Usuwa wszystkie elementy spełniające określony predykat. |
| void [RemoveAt](./removeat/)(int) override | Usuwa element na określonej pozycji. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| void [RemoveRange](./removerange/)(int, int) | Usuwa wycinek listy. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Zwraca iterator odwrotny do nieistniejącego elementu przed początkiem kolekcji. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Zwraca iterator odwrotny do nieistniejącego elementu przed początkiem kolekcji oznaczonej jako const. |
| void [Reverse](./reverse/)() | Odwraca kolejność elementów całej listy. |
| void [Reverse](./reverse/)(int, int) | Odwraca kolejność elementów wycinka listy. |
| void [set_Capacity](./set_capacity/)(int) | Ustawia pojemność listy. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Sortuje elementy w liście. |
| void [Sort](./sort/)() | Sortuje elementy w liście używając domyślnego komparatora. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Sortuje wycinek listy. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Sortuje elementy w liście. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Konwertuje listę na tablicę. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na łańcuch znaków. |
| void [TrimExcess](./trimexcess/)() | Dopasowuje pojemność listy do jej rozmiaru. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Określa, czy każdy element w kolekcji spełnia warunki określone przez podany predykat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Zwraca implementację iteratora początkowego const dla bieżącego kontenera. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Zwraca implementację iteratora początkowego dla bieżącego kontenera. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Zwraca implementację iteratora końcowego const dla bieżącego kontenera. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Zwraca implementację iteratora końcowego dla bieżącego kontenera. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Alias typu | Opis |
| --- | --- |
| [ValueType](./valuetype/) | Ten typ. |
| [BaseType](./basetype/) | Typ interfejsu. |
| [vector_t](./vector_t/) | Podstawowy typ danych. |
| [iterator](./iterator/) | Typ iteratora. |
| [const_iterator](./const_iterator/) | Typ iteratora stałego. |
| [reverse_iterator](./reverse_iterator/) | Typ iteratora odwróconego. |
| [const_reverse_iterator](./const_reverse_iterator/) | Typ stałego iteratora odwróconego. |
| [IEnumerablePtr](./ienumerableptr/) | Kontener przechowujący elementy tego samego typu co nasz. |
| [IEnumeratorPtr](./ienumeratorptr/) | Typ **Enumerator**. |

## Uwagi

[List](./) - wrapper around std::vector to be used in translated code. Requires operator == to be impemented for element type. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Utwórz pierwszą listę.
  auto list1 = MakeObject<List<int>>();

  // Wypełnij pierwszą listę.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Posortuj pierwszą listę.
  // Elementy pierwszej listy będą: {-5, 1, 3, 8}
  list1->Sort();

  // Usuń element o indeksie 2.
  // Elementy pierwszej listy będą: {-5, 1, 8}
  list1->RemoveAt(2);

  // Wstaw element na indeks 1.
  // Elementy pierwszej listy będą: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Utwórz drugą listę.
  auto list2 = MakeObject<List<int>>();

  // Wypełnij drugą listę.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Dołącz elementy z drugiej listy do pierwszej.
  list1->AddRange(list2);

  // Wypisz elementy pierwszej listy.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
- 5 15 1 8 10 20 30
*/
```

## Zobacz także

* Klasa [Object](../../system/object/)
* Klasa [IList](../ilist/)
* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)