---
title: BaseDictionary
second_title: Aspose.Slides for C++ – Dokumentacja API
description: "Implementuje wspólny kod dla różnych struktur danych podobnych do słownika (np. Dictionary, SortedDictionary). Nie powinno się używać bezpośrednio, poza dziedziczeniem przy definiowaniu kontenerów. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciem operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę we wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go do funkcji jako argument."
type: docs
weight: 53
url: /pl/system.collections.generic/basedictionary/
---
## BaseDictionary klasa

Implementuje wspólny kod dla różnych struktur danych podobnych do słownika (np. [Dictionary](../dictionary/), [SortedDictionary](../sorteddictionary/)). Nie powinno się używać bezpośrednio, poza dziedziczeniem przy definiowaniu kontenerów. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument.

```cpp
template<typename Map>class BaseDictionary : public System::Collections::Generic::IDictionary<Map::key_type, Map::mapped_type>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Map | Underlying map type. |

## Metody

| Metoda | Opis |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<typename Map::value_type\>) | Specyficzne dla C++. |
| void [Add](./add/)(const key_t\&, const mapped_t\&) override | Dodaje parę klucz-wartość do słownika. |
| [BaseDictionary](./basedictionary/)() | Tworzy pustą strukturę danych. |
| [BaseDictionary](./basedictionary/)(int, const Args\&...) | Konstruktor przekazujący argumenty do konstruktora mapy podstawowej. |
| [BaseDictionary](./basedictionary/)([BaseType](./basetype/) *, const Args\&...) | Konstruktor kopiujący. |
| [BaseDictionary](./basedictionary/)([BaseType](./basetype/) *) | Konstruktor kopiujący. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Zwraca iterator do opakowania KVPair dla elementu klucz-wartość kontenera. Implementowane w stylu C# – iterator powinien zwracać obiekt KVPair z interfejsem get_Key() i get_Value(). Jeśli kontener jest pusty, zwrócony iterator będzie równy [end()](../ienumerable/end/). |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Zwraca iterator wskazujący na pierwszy element (jeśli istnieje) kolekcji. Ten iterator nie może być użyty do zmiany referowanego obiektu, ponieważ [GetEnumerator()](../ienumerable/getenumerator/) zwraca kopię obiektu typu T. |
| stl_const_iterator [cbegin](./cbegin/)() const | Zwraca iterator do pierwszego elementu kontenera. Implementowane w stylu STL. Jeśli kontener jest pusty, zwrócony iterator będzie równy [end()](../ienumerable/end/). |
| stl_const_iterator [cend](./cend/)() const | Zwraca iterator do elementu następującego po ostatnim elemencie kontenera. Implementowane w stylu STL. Ten element pełni rolę placeholdera; próba jego dostępu skutkuje niezdefiniowanym zachowaniem. |
| void [Clear](./clear/)() override | Usuwa wszystkie elementy. |
| **bool** [ContainsKey](./containskey/)(const key_t\&) const override | Sprawdza, czy klucz jest obecny w słowniku. |
| **bool** [ContainsValue](./containsvalue/)(const mapped_t\&) | Sprawdza, czy wartość jest obecna w słowniku. Używa operatora == do porównywania wartości. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | Kopiuje zawartość słownika do istniejących elementów tablicy. |
| Map\& [data](./data/)() | Dostęp do podstawowego magazynu danych. |
| const Map\& [data](./data/)() const | Dostęp do podstawowego magazynu danych. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Zwraca iterator do opakowania KVPair dla elementu klucz-wartość następującego po ostatnim elemencie kontenera. Implementowane w stylu C# – iterator powinien zwracać obiekt KVPair z interfejsem get_Key() i get_Value(). Ten element pełni rolę placeholdera; próba jego dostępu skutkuje niezdefiniowanym zachowaniem. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Zwraca iterator wskazujący bezpośrednio po ostatnim elemencie (jeśli istnieje) kolekcji. Ten iterator nie może być użyty do zmiany referowanego obiektu, ponieważ [GetEnumerator()](../ienumerable/getenumerator/) zwraca kopię obiektu typu T. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwie wartości NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych typu double w stylu C#, gdzie dwie wartości NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **int32_t** [get_Count](./get_count/)() const override | Zwraca liczbę elementów. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | Sprawdza, czy rozmiar kolekcji jest stały. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Sprawdza, czy kolekcja jest tylko do odczytu. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | Sprawdza, czy kontener jest bezpieczny wątkowo. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](../idictionary/get_keys/)() const | Uzyskuje dostęp do kolekcji kluczy. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Zwraca obiekt, przez który synchronizowana jest kolekcja. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](../idictionary/get_values/)() const | Uzyskuje dostęp do kolekcji wartości. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę licznika referencji powiązaną z obiektem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<[KeyValuePair](../keyvaluepair/)\<key_t, mapped_t\>\>\> [GetEnumerator](./getenumerator/)() | Tworzy instancję enumeratora, powinien być zaimplementowany w podklasie. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna do metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie obiektów niestandardowych. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Analogiczna do wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| mapped_t [GetValueOrDefault](./getvalueordefault/)(const key_t\&) const override | Zwraca wartość, jeśli znaleziona; w przeciwnym razie **Value()**. |
| mapped_t [GetValueOrDefault](./getvalueordefault/)(const key_t\&, const mapped_t\&) const override | Zwraca wartość, jeśli znaleziona; w przeciwnym razie **defaultValue**. |
| mapped_t [GetValueOrNull](./getvalueornull/)(const key_t\&) const override | Zwraca wartość, jeśli znaleziona; w przeciwnym razie **null**. Ma sens tylko dla typów referencyjnych. |
| [ICollection](../icollection/icollection/)() | Konstruktor domyślny. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Konstruktor kopiujący. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Konstruktor przenoszący. |
| mapped_t [idx_get](./idx_get/)(const key_t\&) const override | Funkcja getter dla klucza. |
| void [idx_set](./idx_set/)(const key_t\&, mapped_t) override | Funkcja setter dla klucza. Zmienia lub tworzy element. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny do operatora C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Zastosowuje funkcję akumulatora na sekwencji. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Określa, czy wszystkie elementy sekwencji spełniają warunek. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Określa, czy sekwencja zawiera jakiekolwiek elementy. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Określa, czy istnieje element sekwencji lub czy spełnia on warunek. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Oblicza średnią z sekwencji wartości numerycznych. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Oblicza średnią sekwencji wartości uzyskanych przez wywołanie funkcji transformującej na każdym elemencie sekwencji wejściowej. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Rzutuje elementy na określony typ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Łączy dwie sekwencje. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Określa, czy sekwencja zawiera określoną wartość. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Zwraca liczbę elementów w sekwencji (obliczaną przez bezpośrednie liczenie). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Zwraca liczbę elementów w sekwencji, które spełniają określony warunek. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Zwraca element pod określonym indeksem w sekwencji. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Zwraca element pod określonym indeksem w sekwencji. |
| T [LINQ_First](../ienumerable/linq_first/)() | Zwraca pierwszy element sekwencji. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Zwraca pierwszy element sekwencji spełniający określony warunek. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Zwraca pierwszy element sekwencji lub wartość domyślną, jeśli sekwencja jest pusta. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Zwraca pierwszy element sekwencji spełniający warunek lub wartość domyślną, jeśli taki element nie istnieje. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Grupuje elementy sekwencji. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Grupuje elementy sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Zwraca ostatni element sekwencji. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Zwraca ostatni element sekwencji lub wartość domyślną, jeśli sekwencja jest pusta. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Wywołuje funkcję transformującą na każdym elemencie ogólnej sekwencji i zwraca maksymalną uzyskaną wartość. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Wywołuje funkcję transformującą na każdym elemencie ogólnej sekwencji i zwraca minimalną uzyskaną wartość. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtruje elementy sekwencji w oparciu o określony typ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortuje elementy sekwencji rosnąco według wartości kluczy wybranych przez keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortuje elementy sekwencji malejąco według wartości kluczy wybranych przez keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Odwraca kolejność elementów w sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformuje elementy sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformuje każdy element sekwencji w nową formę, uwzględniając indeks elementu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projektuje każdy element sekwencji i łączy powstałe sekwencje w jedną sekwencję. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Pomija określoną liczbę kolejnych elementów od początku sekwencji i zwraca resztę. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Zwraca określoną liczbę kolejnych elementów od początku sekwencji. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Tworzy tablicę z sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Tworzy List<T> z sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtruje sekwencję na podstawie określonego predykatu. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę (lock()) przypominającą C#. Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna do metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie w podklasach. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operator przypisania przenoszącego. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operator przypisania przenoszącego. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie w podklasach. |
| virtual mapped_t\& [operator[]](./operator[]/)(const key_t\&) | Funkcja dostępu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| **bool** [Remove](./remove/)(const key_t\&) override | Usuwa określony klucz ze słownika. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(unsigned int) override |  |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna do metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję obiektów niestandardowych na ciąg znaków. |
| **bool** [TryGetValue](./trygetvalue/)(const key_t\&, mapped_t\&) const override | Wyszukuje wartość powiązaną z kluczem i zwraca ją, jeśli znaleziona. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie (lock()) przypominające C#. Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Zwraca implementację iteratora begin const dla bieżącego kontenera. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Zwraca implementację iteratora begin dla bieżącego kontenera. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Zwraca implementację iteratora end const dla bieżącego kontenera. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Zwraca implementację iteratora end dla bieżącego kontenera. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [map_t](./map_t/) | Wewnętrzny typ mapy. |
| [KeyCollection](./keycollection/) | Upewnij się, że używamy właściwego alokatora z typem podstawowego magazynu. |
| [ValueCollection](./valuecollection/) | Zbiór wartości. |
| [KVPair](./kvpair/) | Typ pary klucz-wartość. |
| [BaseType](./basetype/) | Zaimplementowany interfejs. |
| [iterator](./iterator/) | Typ iteratora. |
| [const_iterator](./const_iterator/) | Typ iteratora stałego. |

## Zobacz także

* Klasa [IDictionary](../idictionary/)
* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)