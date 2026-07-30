---
title: Array
second_title: Aspose.Slides pro C++ - referenční API
description: "Třída představující datovou strukturu pole. Objektům této třídy by měla být paměť alokována jen pomocí funkcí System::MakeArray() a System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to může vést k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 14
url: /cs/system/array/
---
## Třída Array

Třída, která představuje datovou strukturu pole. Objekty této třídy by měly být alokovány pouze pomocí funkcí [System::MakeArray()](../makearray/) a [System::MakeObject()](../makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operator new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../smartptr/) a použijte tento ukazatel k předání funkci jako argument.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků pole |

## Metody

| Metoda | Popis |
| --- | --- |
| void [Add](./add/)(const T\&) override | Není podporováno, protože pole reprezentované aktuálním objektem je jen pro čtení. |
|  [Array](./array/)() | Vytvoří prázdné pole. |
|  [Array](./array/)(int, const T\&) | Konstruktor naplňující pole. |
|  [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | Konstruktor naplňující pole. |
|  [Array](./array/)(int, const T) | Konstruktor naplňující pole. |
|  [Array](./array/)(**vector_t**\&&) | Konstruktor přesunu. |
|  [Array](./array/)(const **vector_t**\&) | Kopírovací konstruktor. |
|  [Array](./array/)(const std::vector\<Q\>\&) | Vytvoří objekt [Array](./) a naplní jej hodnotami zkopírovanými ze std::vector objektu, jehož typ hodnot je stejný jako **T**, ale odlišný od **UnderlyingType**. |
|  [Array](./array/)(std::vector\<Q\>\&&) | Vytvoří objekt [Array](./) a naplní jej hodnotami přesunutými ze std::vector objektu, jehož typ hodnot je stejný jako **T**, ale odlišný od **UnderlyingType**. |
|  [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | Vytvoří objekt [Array](./) a naplní jej hodnotami ze zadaného inicializačního seznamu obsahujícího prvky typu **UnderlyingType**. |
|  [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | Vytvoří objekt [Array](./) a naplní jej hodnotami ze zadaného pole obsahujícího prvky typu **UnderlyingType**. |
|  [Array](./array/)(std::initializer_list\<**bool**\>, int) | Vytvoří objekt [Array](./) a naplní jej hodnotami ze zadaného inicializačního seznamu obsahujícího prvky typu bool. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | Přetypuje pole na kolekci jen pro čtení. |
| [iterator](./iterator/) [begin](./begin/)() | Vrací iterátor na první prvek kontejneru. Pokud je kontejner prázdný, vrácený iterátor bude roven [end()](./end/). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Vrací iterátor na první prvek kontejneru s const kvalifikací. Pokud je kontejner prázdný, vrácený iterátor bude roven [end()](./end/). |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | Provádí binární vyhledávání ve seřazeném poli. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | NEIMPLEMENTOVÁNO. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Vrací iterátor na první prvek kontejneru s const kvalifikací. Pokud je kontejner prázdný, vrácený iterátor bude roven [cend()](./cend/). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Vrací iterátor na prvek následující po posledním prvku kontejneru. Tento prvek slouží jako zástupný; pokus o jeho přístup vede k nedefinovanému chování. |
| void [Clear](./clear/)() override | Není podporováno, protože pole reprezentované aktuálním objektem je jen pro čtení. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Nahrazuje **count** hodnot počínaje indexem **startIndex** v určeném poli výchozími hodnotami. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | Klónuje pole. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopíruje rozsah prvků z [System.Array](./) počínaje určeným zdrojem. |
| **bool** [Contains](./contains/)(const T\&) const override | Určuje, zda je zadaná položka v poli. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | Vytvoří nový objekt [Array](./) a naplní jej prvky z určeného pole převedenými na typ **OutputType** pomocí zadaného delegáta konvertoru. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | Vytvoří nový objekt [Array](./) a naplní jej prvky z určeného pole převedenými na typ **OutputType** pomocí zadaného funkčního objektu konvertoru. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopíruje určený počet prvků ze zdrojového pole do cílového pole. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopíruje určený počet prvků ze zdrojového pohledu na pole do cílového pole. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | Kopíruje určený počet prvků ze zdrojového pole do cílového pohledu na pole. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | Kopíruje určený počet prvků ze zdrojového pohledu na pole do cílového pohledu na pole. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopíruje určený počet prvků ze zdrojového pole na zásobníku do cílového pole. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | Kopíruje určený počet prvků ze zdrojového pole do cílového pole na zásobníku. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | Kopíruje určený počet prvků ze zdrojového pole na zásobníku do cílového pole na zásobníku. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopíruje zadaný počet prvků ze zdrojového pole počínaje zadaným indexem na zadanou pozici v cílovém poli. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopíruje zadaný počet prvků ze zdrojového pohledu na pole počínaje zadaným indexem na zadanou pozici v cílovém poli. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Kopíruje zadaný počet prvků ze zdrojového pole počínaje zadaným indexem na zadanou pozici v cílovém pohledu na pole. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Kopíruje zadaný počet prvků ze zdrojového pohledu na pole počínaje zadaným indexem na zadanou pozici v cílovém pohledu na pole. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopíruje zadaný počet prvků ze zdrojového pole na zásobníku počínaje zadaným indexem na zadanou pozici v cílovém poli. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | Kopíruje zadaný počet prvků ze zdrojového pole počínaje zadaným indexem na zadanou pozici v cílovém poli na zásobníku. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Kopíruje zadaný počet prvků ze zdrojového pole na zásobníku počínaje zadaným indexem na zadanou pozici v cílovém poli na zásobníku. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Kopíruje zadaný počet prvků ze zdrojového pohledu na pole počínaje zadaným indexem na zadanou pozici v cílovém poli na zásobníku. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | Kopíruje všechny prvky aktuálního pole do určeného cílového pole. Prvky jsou vloženy do cílového pole počínaje indexem určeným argumentem arrayIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | Kopíruje všechny prvky aktuálního pole do určeného cílového pole. Prvky jsou vloženy do cílového pole počínaje indexem určeným argumentem dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | Kopíruje všechny prvky aktuálního pole do určeného cílového pohledu na pole. Prvky jsou vloženy do cílového pohledu na pole počínaje indexem určeným argumentem dstIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Kopíruje zadaný počet prvků z aktuálního pole počínaje zadanou pozicí do určeného cílového pole. Prvky jsou vloženy do cílového pole počínaje indexem určeným argumentem dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Kopíruje zadaný počet prvků z aktuálního pole počínaje zadanou pozicí do určeného cílového pohledu na pole. Prvky jsou vloženy do cílového pohledu na pole počínaje indexem určeným argumentem dstIndex. |
| int [Count](./count/)() const | Vrací číslo, které představuje celkový počet všech prvků ve všech dimenzích pole. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Vrací reverzní iterátor na první prvek obráceného kontejneru. Odpovídá poslednímu prvku neobráceného kontejneru. Pokud je kontejner prázdný, vrácený iterátor je roven [crend()](./crend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Vrací reverzní iterátor na prvek následující po posledním prvku obráceného kontejneru. Odpovídá prvku předcházejícímu prvnímu prvku neobráceného kontejneru. Tento prvek slouží jako zástupný; pokus o jeho přístup vede k nedefinovanému chování. |
| **vector_t**\& [data](./data/)() | Vrací odkaz na interní datovou strukturu používanou k uložení prvků pole. |
| const **vector_t**\& [data](./data/)() const | Vrací konstantní odkaz na interní datovou strukturu používanou k uložení prvků pole. |
| vector_t::pointer [data_ptr](./data_ptr/)() | Vrací surový ukazatel na začátek paměťového bufferu, kde jsou uloženy prvky pole. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | Vrací konstantní surový ukazatel na začátek paměťového bufferu, kde jsou uloženy prvky pole. |
| [iterator](./iterator/) [end](./end/)() | Vrací iterátor na prvek následující po posledním prvku kontejneru. Tento prvek slouží jako zástupný; pokus o jeho přístup vede k nedefinovanému chování. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Vrací iterátor na prvek následující po posledním prvku kontejneru s const kvalifikací. Tento prvek slouží jako zástupný; pokus o jeho přístup vede k nedefinovanému chování. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | Určuje, zda zadaný objekt [Array](./) obsahuje prvek, který splňuje požadavky zadaného predikátu. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Vyhledá první prvek v zadaném poli, který splňuje podmínky zadaného predikátu. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Načte všechny prvky, které odpovídají podmínkám definovaným zadaným predikátem. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Vyhledá první prvek v zadaném poli, který splňuje podmínky zadaného predikátu. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | Provede zadanou akci na každém prvku zadaného pole. |
| int [get_Count](./get_count/)() const override | Vrací velikost pole. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Kontroluje, zda je kolekce pevné velikosti. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Uvádí, zda je pole pouze ke čtení. |
| **int32_t** [get_Length](./get_length/)() const override | Vrací 32bitové celé číslo, které představuje celkový počet všech prvků ve všech dimenzích pole. |
| **int64_t** [get_LongLength](./get_longlength/)() const | Vrací 64bitové celé číslo, které představuje celkový počet všech prvků ve všech dimenzích pole. |
| **int32_t** [get_Rank](./get_rank/)() const | NEIMPLEMENTOVÁNO. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Získá objekt, přes který je kolekce synchronizována. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | Vrací ukazatel na objekt **Enumerator**, který poskytuje rozhraní IEnumerator pro prvky pole reprezentovaného aktuálním objektem. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogie k metodě C# [Object.GetHashCode()](../object/gethashcode/). Umožňuje hašování vlastních objektů. |
| int [GetLength](./getlength/)(int) | Vrací počet prvků ve zadané dimenzi. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | Vrací počet prvků ve zadané dimenzi jako 64bitové celé číslo. |
| int [GetLowerBound](./getlowerbound/)(int) const | Vrací dolní mez zadané dimenze. |
| size_t [GetSizeTLength](./getsizetlength/)() const | Vrací proměnnou std::size_t, která představuje celkový počet všech prvků ve všech dimenzích pole. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Získá skutečný typ objektu. Analogie k volání C# [System.Object.GetType()](../object/gettype/). |
| int [GetUpperBound](./getupperbound/)(int) | Vrací horní mez zadané dimenze. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Výchozí konstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Kopírovací konstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Konstruktor přesunu. |
| T [idx_get](./idx_get/)(int) const override | Vrací položku na zadaném indexu. |
| void [idx_set](./idx_set/)(int, T) override | Nastaví zadanou hodnotu jako položku pole na zadaném indexu. |
| int [IndexOf](./indexof/)(const T\&) const override | Určuje index prvního výskytu zadané položky v poli. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Určuje index prvního výskytu zadané položky v poli. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Určuje index prvního výskytu zadané položky v poli počínaje zadaným indexem. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Určuje index prvního výskytu zadané položky v rozsahu položek pole určeném počátečním indexem a počtem prvků v rozsahu. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | Vyplní pole reprezentované aktuálním objektem hodnotami ze zadaného pole. |
| void [Initialize](./initialize/)() | Vyplní pole výchozími konstrukcemi objektů typu **T**. |
| void [Insert](./insert/)(int, const T\&) override | Není podporováno, protože pole reprezentované aktuálním objektem je pouze ke čtení. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie k operátoru C# 'is'. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Určuje index posledního výskytu zadané položky v rozsahu položek pole určeném počátečním indexem a počtem prvků v rozsahu. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Určuje index posledního výskytu zadané položky v poli počínaje zadaným indexem. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Určuje index posledního výskytu zadané položky v poli. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | Použije akumulační funkci na sekvenci. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Určuje, zda všechny prvky sekvence splňují podmínku. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Určuje, zda sekvence obsahuje nějaké prvky. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Určuje, zda existuje jakýkoli prvek sekvence nebo zda splňuje podmínku. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Vypočítá průměr sekvence číselných hodnot. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | Vypočítá průměr sekvence hodnot získaných voláním transformační funkce na každém prvku vstupní sekvence. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Přetypuje prvky na zadaný typ. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Spojí dvě sekvence. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Určuje, zda sekvence obsahuje zadanou hodnotu. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Vrací počet prvků v sekvenci (vypočtený přímým počítáním). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | Vrací počet prvků v sekvenci, které splňují zadanou podmínku. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Vrací prvek na zadaném indexu v sekvenci. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Vrací prvek na zadaném indexu v sekvenci. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Vrací první prvek sekvence. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | Vrací první prvek sekvence, který splňuje zadanou podmínku. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Vrací první prvek sekvence nebo výchozí hodnotu, pokud je sekvence prázdná. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Vrací první prvek sekvence, který splňuje podmínku, nebo výchozí hodnotu, pokud takový prvek neexistuje. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | Skupinuje prvky sekvence. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | Skupinuje prvky sekvence. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Vrací poslední prvek sekvence. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Vrací poslední prvek sekvence nebo výchozí hodnotu, pokud je sekvence prázdná. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | Volá transformační funkci na každém prvku obecné sekvence a vrací maximální vzniklou hodnotu. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | Volá transformační funkci na každém prvku obecné sekvence a vrací minimální vzniklou hodnotu. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtruje prvky sekvence podle zadaného typu. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | Řadí prvky sekvence ve vzestupném pořadí podle hodnot klíče vybraných keySelectorem. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | Řadí prvky sekvence v sestupném pořadí podle hodnot klíče vybraných keySelectorem. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Obrací pořadí prvků v sekvenci. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | Transformuje prvky sekvence. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | Transformuje každý prvek sekvence do nové podoby za použití indexu prvku. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projektuje každý prvek sekvence a kombinuje vzniklé sekvence do jedné sekvence. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Přeskočí zadaný počet souvislých prvků od začátku sekvence a vrátí zbytek. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Vrací zadaný počet souvislých prvků od začátku sekvence. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Vytvoří pole ze sekvence. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Vytvoří List<T> ze sekvence. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtruje sekvenci na základě zadaného predikátu. |
| void [Lock](../object/lock/)() | Implementuje zamykání pomocí výrazu C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../lockcontext/). |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | Najde největší prvek v poli pomocí [operator<()](../operator_less/) k porovnání prvků. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogie k metodě C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | Najde nejmenší prvek v poli pomocí [operator<()](../operator_less/) k porovnání prvků. |
|  [Object](../object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Operátor přiřazení přesunem. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Operátor přiřazení přesunem. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | Vrací položku na zadaném indexu. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | Vrací položku na zadaném indexu. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | Vrací ukazatel na první prvek jednorozměrného pole. Pro vícerozměrná pole je výsledek nedefinovaný. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Vrací reverzní iterátor na první prvek obráceného kontejneru. Odpovídá poslednímu prvku neobráceného kontejneru. Pokud je kontejner prázdný, vrácený iterátor je roven [rend()](./rend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Vrací reverzní iterator na první prvek obráceného kontejneru. Odpovídá poslednímu prvku neobráceného kontejneru. Pokud je kontejner prázdný, vrácený iterator je roven [rend()](./rend/). |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězců. |
| **bool** [Remove](./remove/)(const T\&) override | Není podporováno, protože pole reprezentované aktuálním objektem je jen pro čtení. |
| void [RemoveAt](./removeat/)(int) override | Není podporováno, protože pole reprezentované aktuálním objektem je jen pro čtení. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Sníží sdílený referenční čítač o zadanou hodnotu. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Vrací reverzní iterator na prvek následující po posledním prvku obráceného kontejneru. Odpovídá prvku předcházejícímu prvnímu prvku neobráceného kontejneru. Tento prvek slouží jako zástupce; pokus o jeho přístup vede k nedefinovanému chování. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Vrací reverzní iterator na prvek následující po posledním prvku obráceného kontejneru. Odpovídá prvku předcházejícímu prvnímu prvku neobráceného kontejneru. Tento prvek slouží jako zástupce; pokus o jeho přístup vede k nedefinovanému chování. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | Změní velikost zadaného pole na zadanou hodnotu nebo vytvoří nové pole se zadanou velikostí. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Obrátí prvky v zadaném poli. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Obrátí rozsah prvků v zadaném poli. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Způsobí, že pole bude považovat uložené ukazatele za slabé (pokud je to použitelné). |
| void [SetValue](./setvalue/)(const T\&, int) | Nastaví hodnotu prvku na zadaném indexu. |
| int [SharedCount](../object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zvětší sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Seřadí prvky v zadaném poli pomocí výchozího porovnávače. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Seřadí rozsah prvků v zadaném poli pomocí výchozího porovnávače. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Seřadí prvky v zadaném poli pomocí zadaného porovnávače. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | NEIMPLEMENTOVÁNO. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | Seřadí prvky v zadaném poli pomocí zadaného srovnání. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | Seřadí dva pole, jedno obsahující klíče a druhé odpovídající položky, na základě hodnot pole obsahujícího klíče, jehož prvky jsou porovnávány pomocí operátoru <. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | Seřadí dva pole, jedno obsahující klíče a druhé odpovídající položky, na základě hodnot pole obsahujícího klíče, jehož prvky jsou porovnávány pomocí výchozího porovnávače. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analogie k metodě C# [Object.ToString()](../object/tostring/). Umožňuje převádět vlastní objekty na řetězec. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Určuje, zda všechny prvky v zadaném poli splňují podmínky definované zadaným predikátem. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukci C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementuje odblokování příkazu C# lock(). Volat přímo nebo použít objekt hlídky [LockContext](../lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Získá implementaci begin const iteratoru pro aktuální kontejner. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Získá implementaci begin iteratoru pro aktuální kontejner. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Získá implementaci end const iteratoru pro aktuální kontejner. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Získá implementaci end iteratoru pro aktuální kontejner. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zvětší slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Sníží slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Definice typů

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | Alias pro typ prvků pole. |
| [UnderlyingType](./underlyingtype/) | Alias pro typ použitý k reprezentaci každého prvku pole. |
| [EnumerablePtr](./enumerableptr/) | Alias pro typ sdíleného ukazatele směřujícího na objekt IEnumerable obsahující prvky typu **T**. |
| [EnumeratorPtr](./enumeratorptr/) | Alias pro typ sdíleného ukazatele směřujícího na objekt IEnumerator obsahující prvky typu **T**. |
| [iterator](./iterator/) | Typ iteratoru. |
| [const_iterator](./const_iterator/) | Typ konstantního iteratoru. |
| [reverse_iterator](./reverse_iterator/) | Typ reverzního iteratoru. |
| [const_reverse_iterator](./const_reverse_iterator/) | Typ konstantního reverzního iteratoru. |

## Poznámky

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
  // Vytvořte a naplňte pole.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Vytiskněte položky pole.
  Print(arrayPtr);

  // Setříděte položky pole vzestupně.
  Array<int32_t>::Sort(arrayPtr);

  // Vytiskněte položky pole.
  Print(arrayPtr);

  // Vytiskněte počet položek pole.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Vytiskněte index položky, která se rovná 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Změňte velikost pole.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Vytiskněte položky pole.
  Print(arrayPtr);

  return 0;
}
/*
Tento příklad kódu produkuje následující výstup:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Viz také

* Třída [ArrayBase](../arraybase/)
* Třída [IList](../../system.collections.generic/ilist/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)