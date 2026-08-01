---
title: Array
second_title: Aspose.Slides voor C++ API-referentie
description: "Klasse die een array-gegevensstructuur voorstelt. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de System::MakeArray() en System::MakeObject() functies. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Pak deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 14
url: /nl/system/array/
---
## Arrayklasse

Klasse die een array-datastructuur representeert. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functies [System::MakeArray()](../makearray/) en [System::MakeObject()](../makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../smartptr/)-pointer en gebruik deze pointer om hem als argument aan functies door te geven.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type of elements of an array |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Add](./add/)(const T\&) override | Niet ondersteund omdat het array dat door het huidige object wordt weergegeven alleen-lezen is. |
| [Array](./array/)() | Construeert een leeg array. |
| [Array](./array/)(int, const T\&) | Vullende constructor. |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | Vullende constructor. |
| [Array](./array/)(int, const T) | Vullende constructor. |
| [Array](./array/)(**vector_t**\&&) | Move-constructor. |
| [Array](./array/)(const **vector_t**\&) | Copy-constructor. |
| [Array](./array/)(const std::vector\<Q\>\&) | Construeert een [Array](./) object en vult het met waarden gekopieerd van een std::vector object waarvan het type van de waarden hetzelfde is als **T**, maar verschillend van **UnderlyingType**. |
| [Array](./array/)(std::vector\<Q\>\&&) | Construeert een [Array](./) object en vult het met waarden verplaatst van een std::vector object waarvan het type van de waarden hetzelfde is als **T**, maar verschillend van **UnderlyingType**. |
| [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | Construeert een [Array](./) object en vult het met waarden uit de opgegeven initializer-list die elementen van type **UnderlyingType** bevat. |
| [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | Construeert een [Array](./) object en vult het met waarden uit de opgegeven array die elementen van type **UnderlyingType** bevat. |
| [Array](./array/)(std::initializer_list\<**bool**\>, int) | Construeert een [Array](./) object en vult het met waarden uit de opgegeven initializer-list die elementen van type bool bevat. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | Converteert het array naar een alleen-lezen collectie. |
| [iterator](./iterator/) [begin](./begin/)() | Geeft een iterator terug naar het eerste element van de container. Als de container leeg is, is de geretourneerde iterator gelijk aan [end()](./end/). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Geeft een iterator terug naar het eerste element van de const-gekwalificeerde container. Als de container leeg is, is de geretourneerde iterator gelijk aan [end()](./end/). |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | Voert een binaire zoekopdracht uit in het gesorteerde array. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | NIET GEREALISEERD. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Geeft een iterator terug naar het eerste const-gekwalificeerde element van de container. Als de container leeg is, is de geretourneerde iterator gelijk aan [cend()](./cend/). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Geeft een iterator terug naar het element dat volgt op het laatste element van de container. Dit element fungeert als een placeholder; pogingen om het te benaderen leiden tot ongedefinieerd gedrag. |
| void [Clear](./clear/)() override | Niet ondersteund omdat het array dat door het huidige object wordt weergegeven alleen-lezen is. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Vervangt **count** waarden beginnend bij de **startIndex** index in het opgegeven array met standaardwaarden. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | Dupliceert het array. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopieert een bereik van elementen van een [System.Array](./) beginnend bij de opgegeven bron. |
| **bool** [Contains](./contains/)(const T\&) const override | Bepaalt of het opgegeven item zich in het array bevindt. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | Construeert een nieuw [Array](./) object en vult het met elementen van het opgegeven array geconverteerd naar type **OutputType** met behulp van de opgegeven converter-delegate. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | Construeert een nieuw [Array](./) object en vult het met elementen van het opgegeven array geconverteerd naar type **OutputType** met behulp van het opgegeven converter-functiesobject. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopieert het opgegeven aantal elementen van de bron-array naar de doel-array. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopieert het opgegeven aantal elementen van de bron-array-view naar de doel-array. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | Kopieert het opgegeven aantal elementen van de bron-array naar de doel-array-view. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | Kopieert het opgegeven aantal elementen van de bron-array-view naar de doel-array-view. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopieert het opgegeven aantal elementen van de bron-array op de stack naar de doel-array. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | Kopieert het opgegeven aantal elementen van de bron-array naar de doel-array op de stack. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | Kopieert het opgegeven aantal elementen van de bron-array op de stack naar de doel-array op de stack. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopieert een opgegeven aantal elementen van de bron-array beginnend bij de opgegeven index naar de opgegeven positie in de doel-array. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopieert een opgegeven aantal elementen van de bron-array-view beginnend bij de opgegeven index naar de opgegeven positie in de doel-array. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Kopieert een opgegeven aantal elementen van de bron-array beginnend bij de opgegeven index naar de opgegeven positie in de doel-array-view. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Kopieert een opgegeven aantal elementen van de bron-array-view beginnend bij de opgegeven index naar de opgegeven positie in de doel-array-view. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopieert een opgegeven aantal elementen van de bron-array op de stack beginnend bij de opgegeven index naar de opgegeven positie in de doel-array. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | Kopieert een opgegeven aantal elementen van de bron-array beginnend bij de opgegeven index naar de opgegeven positie in de doel-array op de stack. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Kopieert een opgegeven aantal elementen van de bron-array op de stack beginnend bij de opgegeven index naar de opgegeven positie in de doel-array op de stack. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Kopieert een opgegeven aantal elementen van de bron-array-view beginnend bij de opgegeven index naar de opgegeven positie in de doel-array op de stack. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | Kopieert alle elementen van het huidige array naar de opgegeven doel-array. De elementen worden in de doel-array ingevoegd beginnend bij de index die wordt opgegeven door het argument arrayIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | Kopieert alle elementen van het huidige array naar de opgegeven doel-array. De elementen worden in de doel-array ingevoegd beginnend bij de index die wordt opgegeven door het argument dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | Kopieert alle elementen van het huidige array naar de opgegeven doel-array-view. De elementen worden in de doel-array-view ingevoegd beginnend bij de index die wordt opgegeven door het argument dstIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Kopieert een opgegeven aantal elementen van het huidige array beginnend bij de opgegeven positie naar de opgegeven doel-array. De elementen worden in de doel-array ingevoegd beginnend bij de index die wordt opgegeven door het argument dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Kopieert een opgegeven aantal elementen van het huidige array-view beginnend bij de opgegeven positie naar de opgegeven doel-array-view. De elementen worden in de doel-array-view ingevoegd beginnend bij de index die wordt opgegeven door het argument dstIndex. |
| int [Count](./count/)() const | Geeft een getal terug dat het totale aantal elementen in alle dimensies van het array vertegenwoordigt. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Geeft een reverse-iterator terug naar het eerste element van de omgekeerde container. Het correspondeert met het laatste element van de niet-omgekeerde container. Als de container leeg is, is de geretourneerde iterator gelijk aan [crend()](./crend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Geeft een reverse-iterator terug naar het element dat volgt op het laatste element van de omgekeerde container. Het correspondeert met het element dat voorafgaat aan het eerste element van de niet-omgekeerde container. Dit element fungeert als een placeholder; benaderen leidt tot ongedefinieerd gedrag. |
| **vector_t**\& [data](./data/)() | Geeft een referentie terug naar de interne datastructuur die wordt gebruikt om de array-elementen op te slaan. |
| const **vector_t**\& [data](./data/)() const | Geeft een constante referentie terug naar de interne datastructuur die wordt gebruikt om de array-elementen op te slaan. |
| vector_t::pointer [data_ptr](./data_ptr/)() | Geeft een ruwe pointer terug naar het begin van de geheugenbuffer waarin de array-elementen worden opgeslagen. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | Geeft een constante ruwe pointer terug naar het begin van de geheugenbuffer waarin de array-elementen worden opgeslagen. |
| [iterator](./iterator/) [end](./end/)() | Geeft een iterator terug naar het element dat volgt op het laatste element van de container. Dit element fungeert als een placeholder; pogingen om het te benaderen leiden tot ongedefinieerd gedrag. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Geeft een iterator terug naar het element dat volgt op het laatste element van de const-gekwalificeerde container. Dit element fungeert als een placeholder; pogingen om het te benaderen leiden tot ongedefinieerd gedrag. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type-objecten in C#-stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevende-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | Bepaalt of het opgegeven [Array](./) object een element bevat dat voldoet aan de eisen van het opgegeven predicaat. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Zoekt het eerste element in de opgegeven array dat voldoet aan de voorwaarden van het opgegeven predicaat. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Haalt alle elementen op die voldoen aan de door het opgegeven predicaat gedefinieerde voorwaarden. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Zoekt het eerste element in de opgegeven array dat voldoet aan de voorwaarden van het opgegeven predicaat. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | Voert de opgegeven actie uit op elk element van de opgegeven array. |
| int [get_Count](./get_count/)() const override | Retourneert de grootte van de array. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Controleert of de collectie een vaste grootte heeft. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Geeft aan of de array alleen-lezen is. |
| **int32_t** [get_Length](./get_length/)() const override | Retourneert een 32-bit integer die het totale aantal elementen in alle dimensies van de array weergeeft. |
| **int64_t** [get_LongLength](./get_longlength/)() const | Retourneert een 64-bit integer die het totale aantal elementen in alle dimensies van de array weergeeft. |
| **int32_t** [get_Rank](./get_rank/)() const | NIET GEREALISEERD. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Haalt het object op waarmee de collectie wordt gesynchroniseerd. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haalt de referentieteller datastructuur op die aan het object is gekoppeld. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | Retourneert een pointer naar een **Enumerator** object dat een IEnumerator interface biedt voor de elementen van de array die door het huidige object wordt vertegenwoordigd. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../object/gethashcode/) methode. Maakt hashing van aangepaste objecten mogelijk. |
| int [GetLength](./getlength/)(int) | Retourneert het aantal elementen in de opgegeven dimensie. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | Retourneert het aantal elementen in de opgegeven dimensie als 64-bit integer. |
| int [GetLowerBound](./getlowerbound/)(int) const | Retourneert de ondergrens van de opgegeven dimensie. |
| size_t [GetSizeTLength](./getsizetlength/)() const | Retourneert een std::size_t variabele die het totale aantal elementen in alle dimensies van de array weergeeft. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../object/gettype/) aanroep. |
| int [GetUpperBound](./getupperbound/)(int) | Retourneert de bovengrens van de opgegeven dimensie. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Standaardconstructor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Kopieconstructor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Verplaatsingsconstructor. |
| T [idx_get](./idx_get/)(int) const override | Retourneert het item op de opgegeven index. |
| void [idx_set](./idx_set/)(int, T) override | Stelt de opgegeven waarde in als het item van de array op de opgegeven index. |
| int [IndexOf](./indexof/)(const T\&) const override | Bepaalt de index van de eerste voorkomen van het opgegeven item in de array. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Bepaalt de index van de eerste voorkomen van het opgegeven item in de array. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Bepaalt de index van de eerste voorkomen van het opgegeven item in de array beginnend vanaf de opgegeven index. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Bepaalt de index van de eerste voorkomen van het opgegeven item in een bereik van items van de array, gespecificeerd door de startindex en het aantal elementen in het bereik. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | Vult de door het huidige object gerepresenteerde array met de waarden uit de opgegeven array. |
| void [Initialize](./initialize/)() | Vult de array met de standaard geconstrueerde objecten van type **T**. |
| void [Insert](./insert/)(int, const T\&) override | Niet ondersteund omdat de door het huidige object gerepresenteerde array alleen-lezen is. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Controleer of het object een instantie van het type representeert beschreven door targetType. Analoge van C# 'is' operator. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Bepaalt de index van de laatste voorkomen van het opgegeven item in een bereik van items van de array, gespecificeerd door de startindex en het aantal elementen in het bereik. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Bepaalt de index van de laatste voorkomen van het opgegeven item in de array beginnend vanaf de opgegeven index. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Bepaalt de index van de laatste voorkomen van het opgegeven item in de array. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | Past een accumulatorfunctie toe op een reeks. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bepaalt of alle elementen van een reeks voldoen aan een voorwaarde. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Bepaalt of een reeks enige elementen bevat. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bepaalt of een element van een reeks bestaat of voldoet aan een voorwaarde. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Bereken het gemiddelde van een reeks numerieke waarden. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | Bereken het gemiddelde van een reeks waarden die worden verkregen door een transformatiefunctie op elk element van de invoerreeks aan te roepen. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Cast de elementen naar het opgegeven type. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Voegt twee reeksen samen. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Bepaalt of een reeks een opgegeven waarde bevat. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Retourneert het aantal elementen in de reeks (berekend via directe telling). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | Retourneert het aantal elementen in de reeks die voldoen aan de opgegeven voorwaarde. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Retourneert het element op een opgegeven index in een reeks. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Retourneert het element op een opgegeven index in een reeks. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Retourneert het eerste element van een reeks. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | Retourneert het eerste element van een reeks dat voldoet aan de opgegeven voorwaarde. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Retourneert het eerste element van een reeks, of een standaardwaarde als de reeks leeg is. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Retourneert het eerste element van de reeks dat voldoet aan een voorwaarde of een standaardwaarde als geen dergelijk element wordt gevonden. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | Groepeert de elementen van een reeks. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | Groepeert de elementen van een reeks. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Retourneert het laatste element van een reeks. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Retourneert het laatste element van een reeks, of een standaardwaarde als de reeks leeg is. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | Roep een transformatiefunctie aan op elk element van een algemene reeks en retourneert de maximale resulterende waarde. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | Roep een transformatiefunctie aan op elk element van een algemene reeks en retourneert de minimale resulterende waarde. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtert de elementen van de reeks op basis van het opgegeven type. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | Sorteert de elementen van een reeks in oplopende volgorde op basis van de sleutelwaarden geselecteerd door keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | Sorteert de elementen van een reeks in aflopende volgorde op basis van de sleutelwaarden geselecteerd door keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Keert de volgorde van de elementen in een reeks om. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | Transformeert elementen van een reeks. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | Transformeert elk element van een reeks naar een nieuwe vorm door de index van het element mee te nemen. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projetteert elk element van een reeks en combineert de resulterende reeksen tot één reeks. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Sla een opgegeven aantal opeenvolgende elementen over vanaf het begin van een reeks en retourneert de rest. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Retourneert een opgegeven aantal opeenvolgende elementen vanaf het begin van een reeks. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Maakt een array van een reeks. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Maakt een List<T> van een reeks. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtert een reeks op basis van het opgegeven predicaat. |
| void [Lock](../object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik het [LockContext](../lockcontext/) afschermobject. |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | Vindt het grootste element in de array met behulp van [operator<()](../operator_less/) om elementen te vergelijken. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../object/memberwiseclone/) methode. Maakt klonen van aangepaste typen mogelijk. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | Vindt het kleinste element in de array met behulp van [operator<()](../operator_less/) om elementen te vergelijken. |
|  [Object](../object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieconstructor. Kopieert niets, eigenlijk, initialiseert alleen een nieuw object en maakt kopieconstructie van subklassen mogelijk. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Toewijzingsoperator. Kopieert niets, eigenlijk, initialiseert alleen een nieuw object en maakt kopieconstructie van subklassen mogelijk. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Verplaatsings-toewijzingsoperator. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Verplaatsings-toewijzingsoperator. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | Retourneert een item op de opgegeven index. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | Retourneert een item op de opgegeven index. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | Retourneert een pointer naar het eerste element van een eendimensionale array. Voor meer-dimensionale arrays is het resultaat ongedefinieerd. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Retourneert een reverse-iterator naar het eerste element van de omgekeerde container. Het correspondeert met het laatste element van de niet-omgekeerde container. Als de container leeg is, is de geretourneerde iterator gelijk aan [rend()](./rend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Retourneert een reverse-iterator naar het eerste element van de omgekeerde container. Het correspondeert met het laatste element van de niet-omgekeerde container. Als de container leeg is, is de geretourneerde iterator gelijk aan [rend()](./rend/). |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object met nullptr op referentie. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van strings. |
| **bool** [Remove](./remove/)(const T\&) override | Niet ondersteund omdat de door het huidige object gerepresenteerde array alleen-lezen is. |
| void [RemoveAt](./removeat/)(int) override | Niet ondersteund omdat de door het huidige object gerepresenteerde array alleen-lezen is. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Retourneert een reverse-iterator naar het element dat volgt op het laatste element van de omgekeerde container. Het correspondeert met het element dat voorafgaat aan het eerste element van de niet-omgekeerde container. Dit element fungeert als een tijdelijke placeholder; pogingen om het te benaderen resulteren in ongedefinieerd gedrag. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Retourneert een reverse-iterator naar het element dat volgt op het laatste element van de omgekeerde container. Het correspondeert met het element dat voorafgaat aan het eerste element van de niet-omgekeerde container. Dit element fungeert als een tijdelijke placeholder; pogingen om het te benaderen resulteren in ongedefinieerd gedrag. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | Wijzigt de grootte van de opgegeven array naar de opgegeven waarde of maakt een nieuwe array met de opgegeven grootte. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Keert de elementen in de opgegeven array om. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Keert een bereik van elementen in de opgegeven array om. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Laat de array opgeslagen pointers als zwak behandelen (indien van toepassing). |
| void [SetValue](./setvalue/)(const T\&, int) | Stelt de waarde van het element op de opgegeven index in. |
| int [SharedCount](../object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Sorteert de elementen in de opgegeven array met de standaard comparator. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Sorteert een bereik van elementen in de opgegeven array met de standaard comparator. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Sorteert de elementen in de opgegeven array met de opgegeven comparator. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | NIET GEREALISEERD. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | Sorteert de elementen in de opgegeven array met de opgegeven vergelijking. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | Sorteert twee arrays, één met sleutels en de andere met de bijbehorende items, gebaseerd op de waarden van de array met sleutels, waarvan de elementen worden vergeleken met operator<. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | Sorteert twee arrays, één met sleutels en de andere met de bijbehorende items, gebaseerd op de waarden van de array met sleutels, waarvan de elementen met de standaard comparator worden vergeleken. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog van C# [Object.ToString()](../object/tostring/)-methode. Maakt het omzetten van aangepaste objecten naar string mogelijk. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Bepaalt of alle elementen in de opgegeven array voldoen aan de voorwaarden gedefinieerd door het opgegeven predicaat. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementeert C# typeof([System.Object](../object/))-construct. |
| void [Unlock](../object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik [LockContext](../lockcontext/)-wakerobject. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Haalt de implementatie van de begin const-iterator voor de huidige container op. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Haalt de implementatie van de begin-iterator voor de huidige container op. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Haalt de implementatie van de end const-iterator voor de huidige container op. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Haalt de implementatie van de end-iterator voor de huidige container op. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destructor. |
| virtual  [~Object](../object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [ValueType](./valuetype/) | Alias voor het type van de elementen van de array. |
| [UnderlyingType](./underlyingtype/) | Alias voor het type dat wordt gebruikt om elk element van de array te vertegenwoordigen. |
| [EnumerablePtr](./enumerableptr/) | Een alias voor een gedeeld pointertype dat wijst naar een IEnumerable-object met elementen van type **T**. |
| [EnumeratorPtr](./enumeratorptr/) | Een alias voor een gedeeld pointertype dat wijst naar een IEnumerator-object met elementen van type **T**. |
| [iterator](./iterator/) | Iterator-type. |
| [const_iterator](./const_iterator/) | Const-iterator-type. |
| [reverse_iterator](./reverse_iterator/) | Reverse-iterator-type. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const reverse-iterator-type. |
## Opmerkingen



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
  // Maak en vul de array.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Print de array-items.
  Print(arrayPtr);

  // Sorteer de array-items oplopend.
  Array<int32_t>::Sort(arrayPtr);

  // Print de array-items.
  Print(arrayPtr);

  // Print het aantal array-items.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Print de index van het item dat gelijk is aan 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Wijzig de grootte van de array.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Print de array-items.
  Print(arrayPtr);

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende output:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Zie ook

* Klasse [ArrayBase](../arraybase/)
* Klasse [IList](../../system.collections.generic/ilist/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)