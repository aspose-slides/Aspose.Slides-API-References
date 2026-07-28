---
title: SortedDictionary
second_title: Referencja API Aspose.Slides dla C++
description: Deklaracja w przód typu posortowanego słownika.
type: docs
weight: 521
url: /pl/system.collections.generic/sorteddictionary/
---
## SortedDictionary klasa

Deklaracja w przód typu posortowanego słownika.

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TKey | Typ klucza. |
| TValue | Typ wartości. |

## Metody

| Metoda | Opis |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey\&, const TValue\&) | Dodaje parę klucz-wartość do kontenera. |
| virtual void [Add](../icollection/add/)(const T\&) | Dodaje element do kolekcji. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Zwraca iterator wskazujący na pierwszy element (jeśli istnieje) kolekcji. Ten iterator nie może być używany do zmiany referencjonowanego obiektu, ponieważ [GetEnumerator()](../ienumerable/getenumerator/) zwraca kopię obiektu typu T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Zwraca iterator wskazujący na pierwszy element (jeśli istnieje) stałej wersji (const-qualified) kolekcji. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Zwraca iterator wskazujący na pierwszy element o stałej kwalifikacji (jeśli istnieje) kolekcji. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Zwraca iterator wskazujący bezpośrednio po ostatnim elemencie o stałej kwalifikacji (jeśli istnieje) kolekcji. |
| virtual void [Clear](../icollection/clear/)() | Usuwa wszystkie elementy z kolekcji. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | Sprawdza, czy element znajduje się w kolekcji. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey\&) const | Sprawdza, czy kontener zawiera klucz. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | Kopiuje zawartość słownika do istniejących elementów tablicy. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Zwraca iterator odwrócony do ostatniego elementu o stałej kwalifikacji w kolekcji (pierwszy w kolejności odwróconej). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Zwraca iterator odwrócony do nieistniejącego elementu o stałej kwalifikacji znajdującego się przed początkiem kolekcji. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Zwraca iterator wskazujący bezpośrednio po ostatnim elemencie (jeśli istnieje) kolekcji. Ten iterator nie może być używany do zmiany referencjonowanego obiektu, ponieważ [GetEnumerator()](../ienumerable/getenumerator/) zwraca kopię obiektu typu T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Zwraca iterator wskazujący bezpośrednio po ostatnim elemencie (jeśli istnieje) stałej wersji (const-qualified) kolekcji. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych podwójnej precyzji w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<TKey\>\> [get_Comparer](./get_comparer/)() const | Zwraca IComparer<TKey> używany do porządkowania elementów SortedDictionary<TKey,TValue>. |
| virtual int [get_Count](../icollection/get_count/)() const | Zwraca liczbę elementów w kolekcji. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | Sprawdza, czy rozmiar kolekcji jest stały. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Sprawdza, czy kolekcja jest tylko do odczytu. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | Sprawdza, czy kontener jest bezpieczny wątkowo. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](../idictionary/get_keys/)() const | Uzyskuje dostęp do kolekcji kluczy. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Zwraca obiekt, przez który kolekcja jest synchronizowana. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](../idictionary/get_values/)() const | Uzyskuje dostęp do kolekcji wartości. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę licznika odniesień powiązaną z obiektem. |
| static [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<typename BasePointerType\<TKey\>::type\>\> [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | Funkcja dostępu do singletona. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Zwraca enumerator do iteracji po bieżącym słowniku. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Analogiczny wywołanie C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&) const | Zwraca wartość, jeśli znaleziona; w przeciwnym razie **Value()**. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&, const TValue\&) const | Zwraca wartość, jeśli znaleziona; w przeciwnym razie **defaultValue**. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey\&) const | Zwraca wartość, jeśli znaleziona; w przeciwnym razie **null**, ma sens tylko dla typów referencyjnych. |
|  [ICollection](../icollection/icollection/)() | Konstruktor domyślny. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Konstruktor kopiujący. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Konstruktor przenoszący. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey\&) const | Funkcja pobierająca (getter). |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey\&, TValue) | Funkcja ustawiająca (setter). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Zastosowuje funkcję akumulatora na sekwencji. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Określa, czy wszystkie elementy sekwencji spełniają warunek. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Określa, czy sekwencja zawiera jakiekolwiek elementy. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Określa, czy istnieje element sekwencji lub czy spełnia warunek. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Oblicza średnią sekwencji wartości numerycznych. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Oblicza średnią sekwencji wartości uzyskanych poprzez wywołanie funkcji transformującej na każdym elemencie sekwencji wejściowej. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Rzutuje elementy na określony typ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Konkatenacja dwóch sekwencji. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Określa, czy sekwencja zawiera określoną wartość. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Zwraca liczbę elementów w sekwencji (obliczoną poprzez bezpośrednie zliczanie). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Zwraca liczbę elementów w sekwencji spełniających określony warunek. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Zwraca element o podanym indeksie w sekwencji. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Zwraca element o podanym indeksie w sekwencji. |
| T [LINQ_First](../ienumerable/linq_first/)() | Zwraca pierwszy element sekwencji. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Zwraca pierwszy element sekwencji spełniający określony warunek. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Zwraca pierwszy element sekwencji lub domyślną wartość, jeśli sekwencja jest pusta. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Zwraca pierwszy element sekwencji spełniający warunek lub domyślną wartość, jeśli taki element nie istnieje. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Grupuje elementy sekwencji. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Grupuje elementy sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Zwraca ostatni element sekwencji. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Zwraca ostatni element sekwencji lub domyślną wartość, jeśli sekwencja jest pusta. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Wywołuje funkcję transformującą na każdym elemencie ogólnej sekwencji i zwraca maksymalną otrzymaną wartość. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Wywołuje funkcję transformującą na każdym elemencie ogólnej sekwencji i zwraca minimalną otrzymaną wartość. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtruje elementy sekwencji na podstawie określonego typu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortuje elementy sekwencji rosnąco według wartości klucza wybranego przez keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortuje elementy sekwencji malejąco według wartości klucza wybranego przez keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Odwraca kolejność elementów w sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformuje elementy sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformuje każdy element sekwencji w nową postać, uwzględniając indeks elementu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projektuje każdy element sekwencji i łączy otrzymane sekwencje w jedną sekwencję. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Pomija określoną liczbę kolejnych elementów od początku sekwencji i zwraca resztę. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Zwraca określoną liczbę kolejnych elementów od początku sekwencji. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Tworzy tablicę z sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Tworzy List<T> z sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtruje sekwencję na podstawie określonego predykatu. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę (lock) języka C#. Wywołuj bezpośrednio lub użyj obiektu stróża [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operator przypisania przenoszącego. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operator przypisania przenoszącego. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Zwraca iterator odwrócony do ostatniego elementu kolekcji (pierwszy w kolejności odwróconej). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Zwraca iterator odwrócony do ostatniego elementu stałej kolekcji (pierwszy w kolejności odwróconej). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey\&) | Usuwa klucz z kontenera. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | Usuwa element z kolekcji. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Zwraca iterator odwrócony do nieistniejącego elementu przed początkiem kolekcji. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Zwraca iterator odwrócony do nieistniejącego elementu przed początkiem stałej (const-qualified) kolekcji. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączyć wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [SortedDictionary](./sorteddictionary/)() | Tworzy pusty słownik. |
|  [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\&) | Tworzy pusty słownik. |
|  [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&) | Konstruktor kopiujący. |
|  [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\&) | Konstruktor kopiujący. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję niestandardowych obiektów na łańcuch. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey\&, TValue\&) const | Wyszukuje wartość i zwraca ją, jeśli znaleziona. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie (unlock) języka C#. Wywołuj bezpośrednio lub użyj obiektu stróża [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Zwraca implementację iteratora begin const dla bieżącego kontenera. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Zwraca implementację iteratora begin dla bieżącego kontenera. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Zwraca implementację iteratora end const dla bieżącego kontenera. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Zwraca implementację iteratora end dla bieżącego kontenera. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Alias typu | Opis |
| --- | --- |
| [KeyCollection](./keycollection/) | Typ kolekcji kluczy. |
| [ValueCollection](./valuecollection/) | Typ kolekcji wartości. |
| [map_t](./map_t/) | Typ danych bazowych. |
| [this_t](./this_t/) | Typ własny. |
| [Ptr](./ptr/) | Typ wskaźnika. |
| [KVPair](./kvpair/) | Typ pary klucz-wartość. |
| [IEnumerablePtr](./ienumerableptr/) | Kolekcja tych samych elementów. |
| [IEnumeratorPtr](./ienumeratorptr/) | Typ **Enumerator**. |
| [iterator](./iterator/) | Typ iteratora. |
| [const_iterator](./const_iterator/) | Typ iteratora const. |
| [reverse_iterator](./reverse_iterator/) | Typ iteratora odwróconego. |
| [const_reverse_iterator](./const_reverse_iterator/) | Typ stałego iteratora odwróconego. |

## Uwagi

Klasa posortowanego słownika opakowująca mapę STL. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani nie używaj operatora new, gdyż spowoduje to błędy wykonania i/lub naruszenia asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika jako argumentu w funkcjach.

## Zobacz także

* Klasa [BaseDictionary](../basedictionary/)
* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)