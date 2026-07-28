---
title: Array
second_title: Referencja API Aspose.Slides dla C++
description: "Klasa reprezentująca strukturę danych typu tablica. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeArray() i System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani nie używaj operatora new, ponieważ może to prowadzić do błędów w czasie wykonywania i/lub awarii asercji. Zawsze otaczaj tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu."
type: docs
weight: 14
url: /pl/system/array/
---
## Klasa Array

Klasa reprezentująca strukturę danych tablicy. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeArray()](../makearray/) i [System::MakeObject()](../makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów tablicy |

## Metody

| Metoda | Opis |
| --- | --- |
| void [Add](./add/)(const T\&) override | Nieobsługiwane, ponieważ tablica reprezentowana przez bieżący obiekt jest tylko do odczytu. |
| [Array](./array/)() | Tworzy pustą tablicę. |
| [Array](./array/)(int, const T\&) | Konstruktor wypełniający. |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | Konstruktor wypełniający. |
| [Array](./array/)(int, const T) | Konstruktor wypełniający. |
| [Array](./array/)(**vector_t**\&&) | Konstruktor przenoszący. |
| [Array](./array/)(const **vector_t**\&) | Konstruktor kopiujący. |
| [Array](./array/)(const std::vector\<Q\>\&) | Tworzy obiekt [Array](./) i wypełnia go wartościami skopiowanymi z obiektu std::vector, którego typ wartości jest taki sam jak **T**, ale różny od **UnderlyingType**. |
| [Array](./array/)(std::vector\<Q\>\&&) | Tworzy obiekt [Array](./) i wypełnia go wartościami przeniesionymi z obiektu std::vector, którego typ wartości jest taki sam jak **T**, ale różny od **UnderlyingType**. |
| [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | Tworzy obiekt [Array](./) i wypełnia go wartościami z podanej listy inicjalizacyjnej zawierającej elementy typu **UnderlyingType**. |
| [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | Tworzy obiekt [Array](./) i wypełnia go wartościami z podanej tablicy zawierającej elementy typu **UnderlyingType**. |
| [Array](./array/)(std::initializer_list\<**bool**\>, int) | Tworzy obiekt [Array](./) i wypełnia go wartościami z podanej listy inicjalizacyjnej zawierającej elementy typu bool. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | Rzutuje tablicę na kolekcję tylko do odczytu. |
| [iterator](./iterator/) [begin](./begin/)() | Zwraca iterator do pierwszego elementu kontenera. Jeśli kontener jest pusty, zwrócony iterator będzie równy [end()](./end/). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Zwraca iterator do pierwszego elementu kontenera oznaczonego jako const. Jeśli kontener jest pusty, zwrócony iterator będzie równy [end()](./end/). |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | Wykonuje wyszukiwanie binarne w posortowanej tablicy. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | NIE ZAIMPLEMENTOWANO. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Zwraca iterator do pierwszego elementu kontenera oznaczonego jako const. Jeśli kontener jest pusty, zwrócony iterator będzie równy [cend()](./cend/). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Zwraca iterator do elementu następującego po ostatnim elemencie kontenera. Ten element pełni rolę symbolicznego miejsca; próba jego odczytu skutkuje niezdefiniowanym zachowaniem. |
| void [Clear](./clear/)() override | Nieobsługiwane, ponieważ tablica reprezentowana przez bieżący obiekt jest tylko do odczytu. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Zastępuje **count** wartości począwszy od indeksu **startIndex** w podanej tablicy wartościami domyślnymi. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | Klona tablicę. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopiuje zakres elementów z [System.Array](./) począwszy od określonego źródła. |
| **bool** [Contains](./contains/)(const T\&) const override | Określa, czy podany element znajduje się w tablicy. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | Tworzy nowy obiekt [Array](./) i wypełnia go elementami podanej tablicy przekonwertowanymi na typ **OutputType** przy użyciu określonego delegata konwertera. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | Tworzy nowy obiekt [Array](./) i wypełnia go elementami podanej tablicy przekonwertowanymi na typ **OutputType** przy użyciu określonego obiektu funkcyjnego konwertera. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopiuje określoną liczbę elementów ze źródłowej tablicy do docelowej tablicy. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopiuje określoną liczbę elementów z widoku źródłowej tablicy do docelowej tablicy. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | Kopiuje określoną liczbę elementów ze źródłowej tablicy do widoku docelowej tablicy. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | Kopiuje określoną liczbę elementów z widoku źródłowej tablicy do widoku docelowej tablicy. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopiuje określoną liczbę elementów ze źródłowej tablicy na stosie do tablicy docelowej. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | Kopiuje określoną liczbę elementów ze źródłowej tablicy do tablicy docelowej na stosie. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | Kopiuje określoną liczbę elementów ze źródłowej tablicy na stosie do tablicy docelowej na stosie. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopiuje określoną liczbę elementów ze źródłowej tablicy zaczynając od podanego indeksu do określonej pozycji w tablicy docelowej. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopiuje określoną liczbę elementów z widoku źródłowej tablicy zaczynając od podanego indeksu do określonej pozycji w tablicy docelowej. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Kopiuje określoną liczbę elementów ze źródłowej tablicy zaczynając od podanego indeksu do określonej pozycji w widoku tablicy docelowej. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Kopiuje określoną liczbę elementów z widoku źródłowej tablicy zaczynając od podanego indeksu do określonej pozycji w widoku tablicy docelowej. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopiuje określoną liczbę elementów ze źródłowej tablicy na stosie zaczynając od podanego indeksu do określonej pozycji w tablicy docelowej. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | Kopiuje określoną liczbę elementów ze źródłowej tablicy zaczynając od podanego indeksu do określonej pozycji w tablicy docelowej na stosie. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Kopiuje określoną liczbę elementów ze źródłowej tablicy na stosie zaczynając od podanego indeksu do określonej pozycji w tablicy docelowej na stosie. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Kopiuje określoną liczbę elementów z widoku źródłowej tablicy zaczynając od podanego indeksu do określonej pozycji w tablicy docelowej na stosie. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | Kopiuje wszystkie elementy bieżącej tablicy do podanej tablicy docelowej. Elementy są wstawiane do tablicy docelowej zaczynając od indeksu określonego argumentem arrayIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | Kopiuje wszystkie elementy bieżącej tablicy do podanej tablicy docelowej. Elementy są wstawiane do tablicy docelowej zaczynając od indeksu określonego argumentem dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | Kopiuje wszystkie elementy bieżącej tablicy do podanego widoku tablicy docelowej. Elementy są wstawiane do widoku tablicy docelowej zaczynając od indeksu określonego argumentem dstIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Kopiuje określoną liczbę elementów z bieżącej tablicy zaczynając od podanej pozycji do podanej tablicy docelowej. Elementy są wstawiane do tablicy docelowej zaczynając od indeksu określonego argumentem dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Kopiuje określoną liczbę elementów z bieżącej tablicy zaczynając od podanej pozycji do podanego widoku tablicy docelowej. Elementy są wstawiane do widoku tablicy docelowej zaczynając od indeksu określonego argumentem dstIndex. |
| int [Count](./count/)() const | Zwraca liczbę reprezentującą łączną liczbę wszystkich elementów we wszystkich wymiarach tablicy. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Zwraca odwrotny iterator do pierwszego elementu odwróconego kontenera. Odpowiada on ostatniemu elementowi nieodwróconego kontenera. Jeśli kontener jest pusty, zwrócony iterator jest równy [crend()](./crend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Zwraca odwrotny iterator do elementu następującego po ostatnim elemencie odwróconego kontenera. Odpowiada on elementowi poprzedzającemu pierwszy element nieodwróconego kontenera. Ten element pełni rolę symbolicznego miejsca; próba jego odczytu skutkuje niezdefiniowanym zachowaniem. |
| **vector_t**\& [data](./data/)() | Zwraca odwołanie do wewnętrznej struktury danych używanej do przechowywania elementów tablicy. |
| const **vector_t**\& [data](./data/)() const | Zwraca stałe odwołanie do wewnętrznej struktury danych używanej do przechowywania elementów tablicy. |
| vector_t::pointer [data_ptr](./data_ptr/)() | Zwraca surowy wskaźnik na początek bufora pamięci, w którym przechowywane są elementy tablicy. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | Zwraca stały surowy wskaźnik na początek bufora pamięci, w którym przechowywane są elementy tablicy. |
| [iterator](./iterator/) [end](./end/)() | Zwraca iterator do elementu następującego po ostatnim elemencie kontenera. Ten element pełni rolę symbolicznego miejsca; próba jego odczytu skutkuje niezdefiniowanym zachowaniem. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Zwraca iterator do elementu następującego po ostatnim elemencie kontenera oznaczonego jako const. Ten element pełni rolę symbolicznego miejsca; próba jego odczytu skutkuje niezdefiniowanym zachowaniem. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | Określa, czy wskazany obiekt [Array](./) zawiera element spełniający wymagania określonego predykatu. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Wyszukuje pierwszy element w określonej tablicy, który spełnia warunki określonego predykatu. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Pobiera wszystkie elementy pasujące do warunków zdefiniowanych przez określony predykat. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Wyszukuje pierwszy element w określonej tablicy, który spełnia warunki określonego predykatu. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | Wykonuje określoną akcję na każdym elemencie określonej tablicy. |
| int [get_Count](./get_count/)() const override | Zwraca rozmiar tablicy. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Sprawdza, czy kolekcja ma stały rozmiar. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Wskazuje, czy tablica jest tylko do odczytu. |
| **int32_t** [get_Length](./get_length/)() const override | Zwraca 32-bitową liczbę całkowitą reprezentującą łączną liczbę wszystkich elementów we wszystkich wymiarach tablicy. |
| **int64_t** [get_LongLength](./get_longlength/)() const | Zwraca 64-bitową liczbę całkowitą reprezentującą łączną liczbę wszystkich elementów we wszystkich wymiarach tablicy. |
| **int32_t** [get_Rank](./get_rank/)() const | NIE ZAIMPLEMENTOWANO. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Pobiera obiekt, przez który kolekcja jest synchronizowana. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | Zwraca wskaźnik do obiektu **Enumerator**, który zapewnia interfejs IEnumerator do elementów tablicy reprezentowanej przez bieżący obiekt. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../object/gethashcode/). Umożliwia tworzenie hashy niestandardowych obiektów. |
| int [GetLength](./getlength/)(int) | Zwraca liczbę elementów w określonym wymiarze. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | Zwraca liczbę elementów w określonym wymiarze jako 64-bitową liczbę całkowitą. |
| int [GetLowerBound](./getlowerbound/)(int) const | Zwraca dolny limit określonego wymiaru. |
| size_t [GetSizeTLength](./getsizetlength/)() const | Zwraca zmienną std::size_t, która reprezentuje łączną liczbę wszystkich elementów we wszystkich wymiarach tablicy. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../object/gettype/). |
| int [GetUpperBound](./getupperbound/)(int) | Zwraca górny limit określonego wymiaru. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Konstruktor domyślny. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Konstruktor kopiujący. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Konstruktor przenoszący. |
| T [idx_get](./idx_get/)(int) const override | Zwraca element pod wskazanym indeksem. |
| void [idx_set](./idx_set/)(int, T) override | Ustawia określoną wartość jako element tablicy pod wskazanym indeksem. |
| int [IndexOf](./indexof/)(const T\&) const override | Określa indeks pierwszego wystąpienia określonego elementu w tablicy. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Określa indeks pierwszego wystąpienia określonego elementu w tablicy. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Określa indeks pierwszego wystąpienia określonego elementu w tablicy, rozpoczynając od podanego indeksu. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Określa indeks pierwszego wystąpienia określonego elementu w przedziale elementów tablicy określonym indeksem początkowym i liczbą elementów w przedziale. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | Wypełnia tablicę reprezentowaną przez bieżący obiekt wartościami z określonej tablicy. |
| void [Initialize](./initialize/)() | Wypełnia tablicę domyślnie zbudowanymi obiektami typu **T**. |
| void [Insert](./insert/)(int, const T\&) override | Nieobsługiwane, ponieważ tablica reprezentowana przez bieżący obiekt jest tylko do odczytu. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Określa indeks ostatniego wystąpienia określonego elementu w przedziale elementów tablicy określonym indeksem początkowym i liczbą elementów w przedziale. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Określa indeks ostatniego wystąpienia określonego elementu w tablicy, rozpoczynając od podanego indeksu. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Określa indeks ostatniego wystąpienia określonego elementu w tablicy. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | Stosuje funkcję akumulatora na ciągu. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Określa, czy wszystkie elementy ciągu spełniają warunek. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Określa, czy ciąg zawiera jakiekolwiek elementy. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Określa, czy istnieje jakikolwiek element ciągu lub czy spełnia on warunek. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Oblicza średnią ciągu wartości liczbowych. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | Oblicza średnią ciągu wartości uzyskanych przez wywołanie funkcji transformującej na każdym elemencie ciągu wejściowego. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Rzutuje elementy na określony typ. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Łączy dwa ciągi. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Określa, czy ciąg zawiera określoną wartość. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Zwraca liczbę elementów w ciągu (obliczaną przez bezpośrednie zliczanie). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | Zwraca liczbę elementów w ciągu, które spełniają określony warunek. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Zwraca element pod określonym indeksem w ciągu. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Zwraca element pod określonym indeksem w ciągu. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Zwraca pierwszy element ciągu. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | Zwraca pierwszy element ciągu, który spełnia określony warunek. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Zwraca pierwszy element ciągu lub wartość domyślną, jeśli ciąg jest pusty. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Zwraca pierwszy element ciągu spełniający warunek lub wartość domyślną, jeśli taki element nie zostanie znaleziony. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | Grupuje elementy ciągu. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | Grupuje elementy ciągu. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Zwraca ostatni element ciągu. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Zwraca ostatni element ciągu lub wartość domyślną, jeśli ciąg jest pusty. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | Wywołuje funkcję transformującą na każdym elemencie ogólnego ciągu i zwraca maksymalną otrzymaną wartość. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | Wywołuje funkcję transformującą na każdym elemencie ogólnego ciągu i zwraca minimalną otrzymaną wartość. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtruje elementy ciągu na podstawie określonego typu. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | Sortuje elementy ciągu rosnąco według wartości klucza wybranego przez keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | Sortuje elementy ciągu malejąco według wartości klucza wybranego przez keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Odwraca kolejność elementów w ciągu. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | Transformuje elementy ciągu. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | Transformuje każdy element ciągu w nową formę, uwzględniając indeks elementu. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projektuje każdy element ciągu i łączy powstałe ciągi w jeden ciąg. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Pomija określoną liczbę kolejnych elementów od początku ciągu i zwraca pozostałe. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Zwraca określoną liczbę kolejnych elementów od początku ciągu. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Tworzy tablicę z ciągu. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Tworzy List<T> z ciągu. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtruje ciąg na podstawie określonego predykatu. |
| void [Lock](../object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../lockcontext/). |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | Znajduje największy element w tablicy, używając [operator<()](../operator_less/) do porównywania elementów. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | Znajduje najmniejszy element w tablicy, używając [operator<()](../operator_less/) do porównywania elementów. |
|  [Object](../object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Operator przypisania przenoszącego. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Operator przypisania przenoszącego. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | Zwraca element pod wskazanym indeksem. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | Zwraca element pod wskazanym indeksem. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | Zwraca wskaźnik do pierwszego elementu jednowymiarowej tablicy. Dla tablic wielowymiarowych wynik jest nieokreślony. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Zwraca odwrócony iterator do pierwszego elementu odwróconego kontenera. Odpowiada ostatniemu elementowi nieodwróconego kontenera. Jeśli kontener jest pusty, zwrócony iterator jest równy [rend()](./rend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Zwraca iterator odwrócony do pierwszego elementu odwróconego kontenera. Odpowiada ostatniemu elementowi nieodwróconego kontenera. Jeśli kontener jest pusty, zwrócony iterator jest równy [rend()](./rend/). |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku łańcuchów znaków. |
| **bool** [Remove](./remove/)(const T\&) override | Nieobsługiwane, ponieważ tablica reprezentowana przez bieżący obiekt jest tylko do odczytu. |
| void [RemoveAt](./removeat/)(int) override | Nieobsługiwane, ponieważ tablica reprezentowana przez bieżący obiekt jest tylko do odczytu. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Zwraca iterator odwrócony do elementu następującego po ostatnim elemencie odwróconego kontenera. Odpowiada elementowi poprzedzającemu pierwszy element nieodwróconego kontenera. Ten element pełni funkcję symbolicznego, próba jego użycia skutkuje nieokreślonym zachowaniem. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Zwraca iterator odwrócony do elementu następującego po ostatnim elemencie odwróconego kontenera. Odpowiada elementowi poprzedzającemu pierwszy element nieodwróconego kontenera. Ten element pełni funkcję symbolicznego, próba jego użycia skutkuje nieokreślonym zachowaniem. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | Zmienia rozmiar określonej tablicy na podaną wartość lub tworzy nową tablicę o podanym rozmiarze. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Odwraca elementy w określonej tablicy. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Odwraca zakres elementów w określonej tablicy. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Sprawia, że tablica traktuje przechowywane wskaźniki jako słabe (jeśli ma to zastosowanie). |
| void [SetValue](./setvalue/)(const T\&, int) | Ustawia wartość elementu pod określonym indeksem. |
| int [SharedCount](../object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Sortuje elementy w określonej tablicy przy użyciu domyślnego porównywacza. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Sortuje zakres elementów w określonej tablicy przy użyciu domyślnego porównywacza. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Sortuje elementy w określonej tablicy przy użyciu określonego porównywacza. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | NIE ZAIMPLEMENTOWANE. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | Sortuje elementy w określonej tablicy przy użyciu określonego porównania. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | Sortuje dwie tablice – jedną zawierającą klucze i drugą – odpowiadające elementy, na podstawie wartości tablicy zawierającej klucze, której elementy są porównywane operatorem <. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | Sortuje dwie tablice – jedną zawierającą klucze i drugą – odpowiadające elementy, na podstawie wartości tablicy zawierającej klucze, której elementy są porównywane przy użyciu domyślnego porównywacza. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog metody C# [Object.ToString()](../object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha znaków. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Określa, czy wszystkie elementy w określonej tablicy spełniają warunki określone przez podany predykat. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu stróża [LockContext](../lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Pobiera implementację stałego iteratora begin dla bieżącego kontenera. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Pobiera implementację iteratora begin dla bieżącego kontenera. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Pobiera implementację stałego iteratora end dla bieżącego kontenera. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Pobiera implementację iteratora end dla bieżącego kontenera. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [ValueType](./valuetype/) | Alias dla typu elementów tablicy. |
| [UnderlyingType](./underlyingtype/) | Alias dla typu używanego do reprezentacji każdego elementu tablicy. |
| [EnumerablePtr](./enumerableptr/) | Alias dla typu inteligentnego wskaźnika wskazującego na obiekt IEnumerable zawierający elementy typu **T**. |
| [EnumeratorPtr](./enumeratorptr/) | Alias dla typu inteligentnego wskaźnika wskazującego na obiekt IEnumerator zawierający elementy typu **T**. |
| [iterator](./iterator/) | Typ iteratora. |
| [const_iterator](./const_iterator/) | Typ stałego iteratora. |
| [reverse_iterator](./reverse_iterator/) | Typ iteratora odwróconego. |
| [const_reverse_iterator](./const_reverse_iterator/) | Typ stałego iteratora odwróconego. |

## Uwagi



```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Utwórz i wypełnij tablicę.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Wypisz elementy tablicy.
  Print(arrayPtr);

  // Posortuj elementy tablicy rosnąco.
  Array<int32_t>::Sort(arrayPtr);

  // Wypisz elementy tablicy.
  Print(arrayPtr);

  // Wypisz liczbę elementów tablicy.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Wypisz indeks elementu równego 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Zmień rozmiar tablicy.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Wypisz elementy tablicy.
  Print(arrayPtr);

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Zobacz także

* Klasa [ArrayBase](../arraybase/)
* Klasa [IList](../../system.collections.generic/ilist/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)