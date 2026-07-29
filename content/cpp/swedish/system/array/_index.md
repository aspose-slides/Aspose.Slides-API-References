---
title: Array
second_title: Aspose.Slides för C++ API-referens
description: "Klass som representerar en array-datastruktur. Objekt av denna klass bör endast allokeras med funktionerna System::MakeArray() och System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertionfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 14
url: /sv/system/array/
---
## Array-klass

Klass som representerar en array-datastruktur. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeArray()](../makearray/) och [System::MakeObject()](../makeobject/) funktioner. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körruntidsfel och/eller påståendefel. Inkapsla alltid denna klass i en [System::SmartPtr](../smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av element i en array |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Add](./add/)(const T\&) override | Stöds inte eftersom arrayen som representeras av det aktuella objektet är skrivskyddad. |
|  [Array](./array/)() | Skapar en tom array. |
|  [Array](./array/)(int, const T\&) | Fyllningskonstruktor. |
|  [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | Fyllningskonstruktor. |
|  [Array](./array/)(int, const T) | Fyllningskonstruktor. |
|  [Array](./array/)(**vector_t**\&&) | Flyttkonstruktor. |
|  [Array](./array/)(const **vector_t**\&) | Kopieringskonstruktor. |
|  [Array](./array/)(const std::vector\<Q\>\&) | Skapar ett [Array](./)-objekt och fyller det med värden kopierade från ett std::vector-objekt vars värdetyp är samma som **T** men annorlunda än **UnderlyingType**. |
|  [Array](./array/)(std::vector\<Q\>\&&) | Skapar ett [Array](./)-objekt och fyller det med värden flyttade från ett std::vector-objekt vars värdetyp är samma som **T** men annorlunda än **UnderlyingType**. |
|  [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | Skapar ett [Array](./)-objekt och fyller det med värden från den angivna initializer-listan som innehåller element av typen **UnderlyingType**. |
|  [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | Skapar ett [Array](./)-objekt och fyller det med värden från den angivna arrayen som innehåller element av typen **UnderlyingType**. |
|  [Array](./array/)(std::initializer_list\<**bool**\>, int) | Skapar ett [Array](./)-objekt och fyller det med värden från den angivna initializer-listan som innehåller element av typen bool. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | Kastar arrayen till en skrivskyddad samling. |
| [iterator](./iterator/) [begin](./begin/)() | Returnerar en iterator till det första elementet i behållaren. Om behållaren är tom kommer den returnerade iteratorn att vara lika med [end()](./end/). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Returnerar en iterator till det första elementet i den const-kvalificerade behållaren. Om behållaren är tom kommer den returnerade iteratorn att vara lika med [end()](./end/). |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | Utför binärsökning i den sorterade arrayen. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | INTE IMPLEMENTERAD. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Returnerar en iterator till det första const-kvalificerade elementet i behållaren. Om behållaren är tom kommer den returnerade iteratorn att vara lika med [cend()](./cend/). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Returnerar en iterator till elementet efter det sista elementet i behållaren. Detta element fungerar som en platshållare; försök att komma åt det resulterar i odefinierat beteende. |
| void [Clear](./clear/)() override | Stöds inte eftersom arrayen som representeras av det aktuella objektet är skrivskyddad. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Ersätter **count** värden med början vid index **startIndex** i den angivna arrayen med standardvärden. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | Klonar arrayen. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopierar ett intervall av element från ett [System.Array](./) med början vid den angivna källan. |
| **bool** [Contains](./contains/)(const T\&) const override | Bestämmer om det angivna objektet finns i arrayen. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | Skapar ett nytt [Array](./)-objekt och fyller det med element från den angivna arrayen konverterade till typen **OutputType** med hjälp av den angivna konverteringsdelegeringen. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | Skapar ett nytt [Array](./)-objekt och fyller det med element från den angivna arrayen konverterade till typen **OutputType** med hjälp av det angivna konverteringsfunktionsobjektet. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopierar det angivna antalet element från källarrayen till destinationsarrayen. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopierar det angivna antalet element från källarrayvyn till destinationsarrayen. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | Kopierar det angivna antalet element från källarrayen till destinationsarrayvyn. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | Kopierar det angivna antalet element från källarrayvyn till destinationsarrayvyn. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopierar det angivna antalet element från källarrayen på stacken till destinationsarrayen. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | Kopierar det angivna antalet element från källarrayen till destinationsarrayen på stacken. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | Kopierar det angivna antalet element från källarrayen på stacken till destinationsarrayen på stacken. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopierar ett angivet antal element från källarrayen med början vid det specifika indexet till den angivna positionen i destinationsarrayen. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopierar ett angivet antal element från källarrayvyn med början vid det specifika indexet till den angivna positionen i destinationsarrayen. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Kopierar ett angivet antal element från källarrayen med början vid det specifika indexet till den angivna positionen i destinationsarrayvyn. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Kopierar ett angivet antal element från källarrayvyn med början vid det specifika indexet till den angivna positionen i destinationsarrayvyn. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopierar ett angivet antal element från källarrayen på stacken med början vid det specifika indexet till den angivna positionen i destinationsarrayen. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | Kopierar ett angivet antal element från källarrayen med början vid det specifika indexet till den angivna positionen i destinationsarrayen på stacken. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Kopierar ett angivet antal element från källarrayen på stacken med början vid det specifika indexet till den angivna positionen i destinationsarrayen på stacken. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Kopierar ett angivet antal element från källarrayvyn med början vid det specifika indexet till den angivna positionen i destinationsarrayen på stacken. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayen. Elementen sätts in i destinationsarrayen med början vid indexet som anges av argumentet arrayIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayen. Elementen sätts in i destinationsarrayen med början vid indexet som anges av argumentet dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayvyn. Elementen sätts in i destinationsarrayvyn med början vid indexet som anges av argumentet dstIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Kopierar ett angivet antal element från den aktuella arrayen med början vid den specificerade positionen till den specificerade destinationsarrayen. Elementen sätts in i destinationsarrayen med början vid indexet som anges av argumentet dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Kopierar ett angivet antal element från den aktuella arrayen med början vid den specificerade positionen till den specificerade destinationsarrayvyn. Elementen sätts in i destinationsarrayvyn med början vid indexet som anges av argumentet dstIndex. |
| int [Count](./count/)() const | Returnerar ett tal som representerar det totala antalet element i samtliga dimensioner av arrayen. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Returnerar en bakåtriktad iterator till det första elementet i den omvända behållaren. Den motsvarar det sista elementet i den icke-omvända behållaren. Om behållaren är tom är den returnerade iteratorn lika med [crend()](./crend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Returnerar en bakåtriktad iterator till elementet efter det sista elementet i den omvända behållaren. Den motsvarar elementet som föregår det första elementet i den icke-omvända behållaren. Detta element fungerar som en platshållare; försök att komma åt det resulterar i odefinierat beteende. |
| **vector_t**\& [data](./data/)() | Returnerar en referens till den interna datastrukturen som används för att lagra arrayens element. |
| const **vector_t**\& [data](./data/)() const | Returnerar en konstant referens till den interna datastrukturen som används för att lagra arrayens element. |
| vector_t::pointer [data_ptr](./data_ptr/)() | Returnerar en rå pekare till början av minnesbufferten där arrayens element lagras. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | Returnerar en konstant rå pekare till början av minnesbufferten där arrayens element lagras. |
| [iterator](./iterator/) [end](./end/)() | Returnerar en iterator till elementet efter det sista elementet i behållaren. Detta element fungerar som en platshållare; försök att komma åt det resulterar i odefinierat beteende. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Returnerar en iterator till elementet efter det sista elementet i den const-kvalificerade behållaren. Detta element fungerar som en platshållare; försök att komma åt det resulterar i odefinierat beteende. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Jämför objekt med C# [Object.Equals](../object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | Bestämmer om det angivna [Array](./)-objektet innehåller ett element som uppfyller kraven för det angivna predikatet. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Söker efter det första elementet i den angivna arrayen som uppfyller villkoren för det angivna predikatet. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Hämtar alla element som matchar villkoren som definieras av det angivna predikatet. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Söker efter det första elementet i den angivna arrayen som uppfyller villkoren för det angivna predikatet. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | Utför den angivna handlingen på varje element i den angivna arrayen. |
| int [get_Count](./get_count/)() const override | Returnerar storleken på arrayen. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Kontrollerar om samlingen har fast storlek. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Anger om arrayen är skrivskyddad. |
| **int32_t** [get_Length](./get_length/)() const override | Returnerar ett 32-bit heltal som representerar det totala antalet element i alla dimensioner av arrayen. |
| **int64_t** [get_LongLength](./get_longlength/)() const | Returnerar ett 64-bit heltal som representerar det totala antalet element i alla dimensioner av arrayen. |
| **int32_t** [get_Rank](./get_rank/)() const | INTE IMPLEMENTERAD. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Hämtar objektet som samlingen synkroniseras genom. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | Returnerar en pekare till **Enumerator**-objektet som tillhandahåller IEnumerator-gränssnittet till element i arrayen som representeras av det aktuella objektet. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| int [GetLength](./getlength/)(int) | Returnerar antalet element i den angivna dimensionen. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | Returnerar antalet element i den angivna dimensionen som ett 64-bit heltal. |
| int [GetLowerBound](./getlowerbound/)(int) const | Returnerar den lägre gränsen för den angivna dimensionen. |
| size_t [GetSizeTLength](./getsizetlength/)() const | Returnerar en std::size_t-variabel som representerar det totala antalet element i alla dimensioner av arrayen. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../object/gettype/)-anrop. |
| int [GetUpperBound](./getupperbound/)(int) | Returnerar den övre gränsen för den angivna dimensionen. |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | Standardkonstruktor. |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Kopieringskonstruktor. |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Flyttkonstruktor. |
| T [idx_get](./idx_get/)(int) const override | Returnerar objektet på det angivna indexet. |
| void [idx_set](./idx_set/)(int, T) override | Sätter det angivna värdet som element i arrayen på det angivna indexet. |
| int [IndexOf](./indexof/)(const T\&) const override | Bestämmer indexet för den första förekomsten av det angivna objektet i arrayen. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Bestämmer indexet för den första förekomsten av det angivna objektet i arrayen. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Bestämmer indexet för den första förekomsten av det angivna objektet i arrayen med start från det angivna indexet. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Bestämmer indexet för den första förekomsten av det angivna objektet i ett intervall av element i arrayen som specificeras av startindexet och antalet element i intervallet. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | Fyller arrayen som representeras av det aktuella objektet med värdena från den angivna arrayen. |
| void [Initialize](./initialize/)() | Fyller arrayen med de standardkonstruktade objekten av typen **T**. |
| void [Insert](./insert/)(int, const T\&) override | Stöds inte eftersom arrayen som representeras av det aktuella objektet är skrivskyddad. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Bestämmer indexet för den sista förekomsten av det angivna objektet i ett intervall av element i arrayen som specificeras av startindexet och antalet element i intervallet. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Bestämmer indexet för den sista förekomsten av det angivna objektet i arrayen med start från det angivna indexet. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Bestämmer indexet för den sista förekomsten av det angivna objektet i arrayen. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | Applicerar en ackumulatorfunktion över en sekvens. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bestämmer om alla element i en sekvens uppfyller ett villkor. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Bestämmer om en sekvens innehåller några element. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bestämmer om något element i en sekvens existerar eller uppfyller ett villkor. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Beräknar medelvärdet av en sekvens av numeriska värden. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | Beräknar medelvärdet av en sekvens av värden som erhålls genom att anropa en transform-funktion på varje element i insekvensen. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Typomvandlar elementen till den angivna typen. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Sammanfogar två sekvenser. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Bestämmer om en sekvens innehåller ett angivet värde. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Returnerar antalet element i sekvensen (beräknat via direkt uppräkning). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | Returnerar antalet element i sekvensen som uppfyller det angivna villkoret. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Returnerar elementet på ett angivet index i en sekvens. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Returnerar elementet på ett angivet index i en sekvens. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Returnerar det första elementet i en sekvens. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | Returnerar det första elementet i en sekvens som uppfyller det angivna villkoret. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Returnerar det första elementet i en sekvens, eller ett standardvärde om sekvensen är tom. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Returnerar det första elementet i sekvensen som uppfyller ett villkor eller ett standardvärde om inget sådant element finns. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | Grupperar elementen i en sekvens. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | Grupperar elementen i en sekvens. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Returnerar det sista elementet i en sekvens. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Returnerar det sista elementet i en sekvens, eller ett standardvärde om sekvensen är tom. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | Kallar en transform-funktion på varje element i en generisk sekvens och returnerar det maximala resulterande värdet. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | Kallar en transform-funktion på varje element i en generisk sekvens och returnerar det minsta resulterande värdet. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtrerar elementen i sekvensen baserat på den angivna typen. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | Sorterar elementen i en sekvens i stigande ordning enligt nyckelvärdena som väljs av keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | Sorterar elementen i en sekvens i fallande ordning enligt nyckelvärdena som väljs av keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Vänder på ordningen av elementen i en sekvens. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | Transformerar elementen i en sekvens. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | Transformerar varje element i en sekvens till en ny form genom att ta med elementets index. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projektar varje element i en sekvens och kombinerar de resulterande sekvenserna till en sekvens. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Hoppar över ett angivet antal sammanhängande element från början av en sekvens och returnerar resten. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Returnerar ett angivet antal sammanhängande element från början av en sekvens. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Skapar en array från en sekvens. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Skapar en List<T> från en sekvens. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtrerar en sekvens baserat på det angivna predikatet. |
| void [Lock](../object/lock/)() | Implementerar låsning enligt C# lock()-satser. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktsobjekt. |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | Hittar det största elementet i arrayen med hjälp av [operator<()](../operator_less/) för att jämföra element. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | Hittar det minsta elementet i arrayen med hjälp av [operator<()](../operator_less/) för att jämföra element. |
| [Object](../object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
| [Object](../object/object/)([Object](../object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, den initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, den initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Flyttilldelningsoperator. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Flyttilldelningsoperator. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | Returnerar ett element på det angivna indexet. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | Returnerar ett element på det angivna indexet. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | Returnerar en pekare till det första elementet i en endimensionell array. För flerdimensionella arrayer är resultatet odefinierat. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Returnerar en omvänd iterator till det första elementet i den omvända behållaren. Den motsvarar det sista elementet i den icke-omvända behållaren. Om behållaren är tom är den returnerade iteratorn lika med [rend()](./rend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Returnerar en omvänd iterator till det första elementet i den omvända behållaren. Den motsvarar det sista elementet i den icke-omvända behållaren. Om behållaren är tom, är den returnerade iteratorn lika med [rend()](./rend/). |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr genom referens. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet med strängar. |
| **bool** [Remove](./remove/)(const T\&) override | Stöds inte eftersom arrayen som representeras av det aktuella objektet är skrivskyddad. |
| void [RemoveAt](./removeat/)(int) override | Stöds inte eftersom arrayen som representeras av det aktuella objektet är skrivskyddad. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Minskar delad referensräkning med det angivna värdet. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Returnerar en omvänd iterator till elementet efter det sista elementet i den omvända behållaren. Det motsvarar elementet före det första elementet i den icke-omvända behållaren. Detta element fungerar som en platshållare; ett försök att komma åt det resulterar i odefinierat beteende. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Returnerar en omvänd iterator till elementet efter det sista elementet i den omvända behållaren. Det motsvarar elementet före det första elementet i den icke-omvända behållaren. Detta element fungerar som en platshållare; ett försök att komma åt det resulterar i odefinierat beteende. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | Ändrar storleken på den angivna arrayen till det angivna värdet eller skapar en ny array med den angivna storleken. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Vänder på elementen i den angivna arrayen. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Vänder på ett intervall av element i den angivna arrayen. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Får arrayen att behandla lagrade pekare som svaga (om tillämpligt). |
| void [SetValue](./setvalue/)(const T\&, int) | Sätter värdet på elementet på angivet index. |
| int [SharedCount](../object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Sorterar element i den angivna arrayen med standardjämförare. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Sorterar ett intervall av element i den angivna arrayen med standardjämförare. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Sorterar element i den angivna arrayen med angiven jämförare. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | INTE IMPLEMENTERAD. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | Sorterar element i den angivna arrayen med specificerad jämförelse. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | Sorterar två arrayer, en innehållande nycklar och den andra motsvarande objekt, baserat på värdena i nyckelarrayen, vars element jämförs med operator<. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | Sorterar två arrayer, en innehållande nycklar och den andra motsvarande objekt, baserat på värdena i nyckelarrayen, vars element jämförs med standardjämförare. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog till C# [Object.ToString()](../object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Bestämmer om alla element i den angivna arrayen uppfyller de villkor som definieras av det angivna predikatet. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementerar C# typeof([System.Object](../object/))-konstruktionen. |
| void [Unlock](../object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktsobjekt. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin-const-iterator för den aktuella behållaren. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella behållaren. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end-const-iterator för den aktuella behållaren. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end-iterator för den aktuella behållaren. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [ValueType](./valuetype/) | Alias för typen av elementen i arrayen. |
| [UnderlyingType](./underlyingtype/) | Alias för typen som används för att representera varje element i arrayen. |
| [EnumerablePtr](./enumerableptr/) | Ett alias för en delad pekartyp som pekar på ett IEnumerable-objekt som innehåller element av typen **T**. |
| [EnumeratorPtr](./enumeratorptr/) | Ett alias för en delad pekartyp som pekar på ett IEnumerator-objekt som innehåller element av typen **T**. |
| [iterator](./iterator/) | Iterator-typ. |
| [const_iterator](./const_iterator/) | Const-iterator-typ. |
| [reverse_iterator](./reverse_iterator/) | Omvänd iterator-typ. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const omvänd iterator-typ. |
## Anmärkningar



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
  // Skapa och fyll arrayen.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Skriv ut arrayens element.
  Print(arrayPtr);

  // Sortera arrayens element i stigande ordning.
  Array<int32_t>::Sort(arrayPtr);

  // Skriv ut arrayens element.
  Print(arrayPtr);

  // Skriv ut antalet element i arrayen.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Skriv ut index för elementet som är lika med 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Ändra storlek på arrayen.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Skriv ut arrayens element.
  Print(arrayPtr);

  return 0;
}
/*
Detta kodexempel ger följande utskrift:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Se också

* Klass [ArrayBase](../arraybase/)
* Klass [IList](../../system.collections.generic/ilist/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)