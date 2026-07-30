---
title: Array
second_title: Riferimento API di Aspose.Slides per C++
description: "Classe che rappresenta una struttura dati array. Gli oggetti di questa classe devono essere allocati solo utilizzando le funzioni System::MakeArray() e System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò proverà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e utilizza questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 14
url: /it/system/array/
---
## Classe Array

Classe che rappresenta una struttura dati array. Gli oggetti di questa classe devono essere allocati solo utilizzando le funzioni [System::MakeArray()](../makearray/) e [System::MakeObject()](../makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un [System::SmartPtr](../smartptr/) puntatore e utilizza questo puntatore per passarlo alle funzioni come argomento.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo degli elementi di un array |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [Add](./add/)(const T\&) override | Non supportato perché l'array rappresentato dall'oggetto corrente è di sola lettura. |
|  [Array](./array/)() | Costruisce un array vuoto. |
|  [Array](./array/)(int, const T\&) | Costruttore di riempimento. |
|  [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | Costruttore di riempimento. |
|  [Array](./array/)(int, const T) | Costruttore di riempimento. |
|  [Array](./array/)(**vector_t**\&&) | Costruttore di spostamento. |
|  [Array](./array/)(const **vector_t**\&) | Costruttore di copia. |
|  [Array](./array/)(const std::vector\<Q\>\&) | Costruisce un oggetto [Array](./) e lo riempie con i valori copiati da un oggetto std::vector il cui tipo di valori è lo stesso di **T** ma diverso da **UnderlyingType**. |
|  [Array](./array/)(std::vector\<Q\>\&&) | Costruisce un oggetto [Array](./) e lo riempie con i valori spostati da un oggetto std::vector il cui tipo di valori è lo stesso di **T** ma diverso da **UnderlyingType**. |
|  [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | Costruisce un oggetto [Array](./) e lo riempie con i valori della lista di inizializzazione specificata contenente elementi di tipo **UnderlyingType**. |
|  [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | Costruisce un oggetto [Array](./) e lo riempie con i valori dell'array specificato contenente elementi di tipo **UnderlyingType**. |
|  [Array](./array/)(std::initializer_list\<**bool**\>, int) | Costruisce un oggetto [Array](./) e lo riempie con i valori della lista di inizializzazione specificata contenente elementi di tipo bool. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | Converte l'array in una collezione di sola lettura. |
| [iterator](./iterator/) [begin](./begin/)() | Restituisce un iteratore al primo elemento del contenitore. Se il contenitore è vuoto, l'iteratore restituito sarà uguale a [end()](./end/). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Restituisce un iteratore al primo elemento del contenitore qualificato come const. Se il contenitore è vuoto, l'iteratore restituito sarà uguale a [end()](./end/). |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | Esegue una ricerca binaria nell'array ordinato. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | NON IMPLEMENTATO. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Restituisce un iteratore al primo elemento qualificato come const del contenitore. Se il contenitore è vuoto, l'iteratore restituito sarà uguale a [cend()](./cend/). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Restituisce un iteratore all'elemento successivo all'ultimo elemento del contenitore. Questo elemento funge da segnaposto; tentare di accedervi provoca un comportamento indefinito. |
| void [Clear](./clear/)() override | Non supportato perché l'array rappresentato dall'oggetto corrente è di sola lettura. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Sostituisce **count** valori a partire dall'indice **startIndex** nell'array specificato con valori predefiniti. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | Clona l'array. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copia un intervallo di elementi da un [System.Array](./) a partire dalla sorgente specificata. |
| **bool** [Contains](./contains/)(const T\&) const override | Determina se l'elemento specificato è presente nell'array. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | Costruisce un nuovo oggetto [Array](./) e lo riempie con gli elementi dell'array specificato convertiti al tipo **OutputType** usando il delegato convertitore specificato. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | Costruisce un nuovo oggetto [Array](./) e lo riempie con gli elementi dell'array specificato convertiti al tipo **OutputType** usando l'oggetto funzione convertitore specificato. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Copia il numero specificato di elementi dall'array di origine all'array di destinazione. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Copia il numero specificato di elementi dalla vista dell'array di origine all'array di destinazione. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | Copia il numero specificato di elementi dall'array di origine alla vista dell'array di destinazione. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | Copia il numero specificato di elementi dalla vista dell'array di origine alla vista dell'array di destinazione. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Copia il numero specificato di elementi dall'array di origine sullo stack all'array di destinazione. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | Copia il numero specificato di elementi dall'array di origine all'array di destinazione sullo stack. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | Copia il numero specificato di elementi dall'array di origine sullo stack all'array di destinazione sullo stack. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copia un numero specificato di elementi dall'array di origine a partire dall'indice specificato alla posizione specificata nell'array di destinazione. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copia un numero specificato di elementi dalla vista dell'array di origine a partire dall'indice specificato alla posizione specificata nell'array di destinazione. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Copia un numero specificato di elementi dall'array di origine a partire dall'indice specificato alla posizione specificata nella vista dell'array di destinazione. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Copia un numero specificato di elementi dalla vista dell'array di origine a partire dall'indice specificato alla posizione specificata nella vista dell'array di destinazione. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copia un numero specificato di elementi dall'array di origine sullo stack a partire dall'indice specificato alla posizione specificata nell'array di destinazione. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | Copia un numero specificato di elementi dall'array di origine a partire dall'indice specificato alla posizione specificata nell'array di destinazione sullo stack. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Copia un numero specificato di elementi dall'array di origine sullo stack a partire dall'indice specificato alla posizione specificata nell'array di destinazione sullo stack. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Copia un numero specificato di elementi dalla vista dell'array di origine a partire dall'indice specificato alla posizione specificata nell'array di destinazione sullo stack. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | Copia tutti gli elementi dell'array corrente nell'array di destinazione specificato. Gli elementi sono inseriti nell'array di destinazione a partire dall'indice specificato dall'argomento arrayIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | Copia tutti gli elementi dell'array corrente nell'array di destinazione specificato. Gli elementi sono inseriti nell'array di destinazione a partire dall'indice specificato dall'argomento dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | Copia tutti gli elementi dell'array corrente nella vista dell'array di destinazione specificata. Gli elementi sono inseriti nella vista dell'array di destinazione a partire dall'indice specificato dall'argomento dstIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Copia un numero specificato di elementi dall'array corrente a partire dalla posizione specificata nell'array di destinazione specificato. Gli elementi sono inseriti nell'array di destinazione a partire dall'indice specificato dall'argomento dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Copia un numero specificato di elementi dall'array corrente a partire dalla posizione specificata nella vista dell'array di destinazione specificata. Gli elementi sono inseriti nella vista dell'array di destinazione a partire dall'indice specificato dall'argomento dstIndex. |
| int [Count](./count/)() const | Restituisce un numero che rappresenta il numero totale di tutti gli elementi in tutte le dimensioni dell'array. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Restituisce un iteratore inverso al primo elemento del contenitore invertito. Corrisponde all'ultimo elemento del contenitore non invertito. Se il contenitore è vuoto, l'iteratore restituito è uguale a [crend()](./crend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Restituisce un iteratore inverso all'elemento successivo all'ultimo elemento del contenitore invertito. Corrisponde all'elemento precedente al primo elemento del contenitore non invertito. Questo elemento funge da segnaposto; tentare di accedervi provoca un comportamento indefinito. |
| **vector_t**\& [data](./data/)() | Restituisce un riferimento alla struttura dati interna usata per memorizzare gli elementi dell'array. |
| const **vector_t**\& [data](./data/)() const | Restituisce un riferimento costante alla struttura dati interna usata per memorizzare gli elementi dell'array. |
| vector_t::pointer [data_ptr](./data_ptr/)() | Restituisce un puntatore grezzo all'inizio del buffer di memoria dove sono memorizzati gli elementi dell'array. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | Restituisce un puntatore grezzo costante all'inizio del buffer di memoria dove sono memorizzati gli elementi dell'array. |
| [iterator](./iterator/) [end](./end/)() | Restituisce un iteratore all'elemento successivo all'ultimo elemento del contenitore. Questo elemento funge da segnaposto; tentare di accedervi provoca un comportamento indefinito. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Restituisce un iteratore all'elemento successivo all'ultimo elemento del contenitore qualificato come const. Questo elemento funge da segnaposto; tentare di accedervi provoca un comportamento indefinito. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | Determina se l'oggetto [Array](./) specificato contiene un elemento che soddisfa i requisiti del predicato specificato. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Cerca il primo elemento nell'array specificato che soddisfa le condizioni del predicato specificato. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Recupera tutti gli elementi che corrispondono alle condizioni definite dal predicato specificato. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Cerca il primo elemento nell'array specificato che soddisfa le condizioni del predicato specificato. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | Esegue l'azione specificata su ogni elemento dell'array specificato. |
| int [get_Count](./get_count/)() const override | Restituisce la dimensione dell'array. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Verifica se la raccolta è di dimensione fissa. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Indica se l'array è di sola lettura. |
| **int32_t** [get_Length](./get_length/)() const override | Restituisce un intero a 32 bit che rappresenta il numero totale di tutti gli elementi in tutte le dimensioni dell'array. |
| **int64_t** [get_LongLength](./get_longlength/)() const | Restituisce un intero a 64 bit che rappresenta il numero totale di tutti gli elementi in tutte le dimensioni dell'array. |
| **int32_t** [get_Rank](./get_rank/)() const | NON IMPLEMENTATO. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Ottiene l'oggetto attraverso il quale la raccolta è sincronizzata. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | Restituisce un puntatore all'oggetto **Enumerator** che fornisce l'interfaccia IEnumerator agli elementi dell'array rappresentato dall'oggetto corrente. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| int [GetLength](./getlength/)(int) | Restituisce il numero di elementi nella dimensione specificata. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | Restituisce il numero di elementi nella dimensione specificata come intero a 64 bit. |
| int [GetLowerBound](./getlowerbound/)(int) const | Restituisce il limite inferiore della dimensione specificata. |
| size_t [GetSizeTLength](./getsizetlength/)() const | Restituisce una variabile std::size_t che rappresenta il numero totale di tutti gli elementi in tutte le dimensioni dell'array. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../object/gettype/). |
| int [GetUpperBound](./getupperbound/)(int) | Restituisce il limite superiore della dimensione specificata. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Costruttore predefinito. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Costruttore di copia. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Costruttore di spostamento. |
| T [idx_get](./idx_get/)(int) const override | Restituisce l'elemento all'indice specificato. |
| void [idx_set](./idx_set/)(int, T) override | Imposta il valore specificato come elemento dell'array all'indice specificato. |
| int [IndexOf](./indexof/)(const T\&) const override | Determina l'indice della prima occorrenza dell'elemento specificato nell'array. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Determina l'indice della prima occorrenza dell'elemento specificato nell'array. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Determina l'indice della prima occorrenza dell'elemento specificato nell'array a partire dall'indice specificato. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Determina l'indice della prima occorrenza dell'elemento specificato in un intervallo di elementi dell'array specificato dall'indice di partenza e dal numero di elementi nell'intervallo. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | Riempie l'array rappresentato dall'oggetto corrente con i valori dell'array specificato. |
| void [Initialize](./initialize/)() | Riempie l'array con gli oggetti di tipo **T** costruiti di default. |
| void [Insert](./insert/)(int, const T\&) override | Non supportato perché l'array rappresentato dall'oggetto corrente è di sola lettura. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Determina l'indice dell'ultima occorrenza dell'elemento specificato in un intervallo di elementi dell'array specificato dall'indice di partenza e dal numero di elementi nell'intervallo. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Determina l'indice dell'ultima occorrenza dell'elemento specificato nell'array a partire dall'indice specificato. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Determina l'indice dell'ultima occorrenza dell'elemento specificato nell'array. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | Applica una funzione di accumulatore su una sequenza. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina se tutti gli elementi di una sequenza soddisfano una condizione. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Determina se una sequenza contiene degli elementi. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina se esiste almeno un elemento in una sequenza o se soddisfa una condizione. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Calcola la media di una sequenza di valori numerici. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | Calcola la media di una sequenza di valori ottenuti invocando una funzione di trasformazione su ogni elemento della sequenza di input. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Esegue il cast degli elementi al tipo specificato. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Concatena due sequenze. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Determina se una sequenza contiene un valore specificato. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Restituisce il numero di elementi nella sequenza (calcolato tramite conteggio diretto). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | Restituisce il numero di elementi nella sequenza che soddisfano la condizione specificata. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Restituisce l'elemento a un indice specificato in una sequenza. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Restituisce l'elemento a un indice specificato in una sequenza. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Restituisce il primo elemento di una sequenza. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | Restituisce il primo elemento di una sequenza che soddisfa la condizione specificata. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Restituisce il primo elemento di una sequenza, o un valore predefinito se la sequenza è vuota. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Restituisce il primo elemento della sequenza che soddisfa una condizione o un valore predefinito se non è stato trovato alcun elemento. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | Raggruppa gli elementi di una sequenza. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | Raggruppa gli elementi di una sequenza. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Restituisce l'ultimo elemento di una sequenza. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Restituisce l'ultimo elemento di una sequenza, o un valore predefinito se la sequenza è vuota. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | Invoca una funzione di trasformazione su ogni elemento di una sequenza generica e restituisce il valore massimo risultante. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | Invoca una funzione di trasformazione su ogni elemento di una sequenza generica e restituisce il valore minimo risultante. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtra gli elementi della sequenza in base al tipo specificato. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | Ordina gli elementi di una sequenza in ordine crescente in base ai valori chiave selezionati da keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | Ordina gli elementi di una sequenza in ordine decrescente in base ai valori chiave selezionati da keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Inverte l'ordine degli elementi in una sequenza. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | Trasforma gli elementi di una sequenza. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | Trasforma ogni elemento di una sequenza in una nuova forma incorporando l'indice dell'elemento. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Proietta ogni elemento di una sequenza e combina le sequenze risultanti in una singola sequenza. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Salta un determinato numero di elementi contigui dall'inizio di una sequenza e restituisce il resto. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Restituisce un numero specificato di elementi contigui dall'inizio di una sequenza. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Crea un array da una sequenza. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Crea una List<T> da una sequenza. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra una sequenza in base al predicato specificato. |
| void [Lock](../object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../lockcontext/). |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | Trova l'elemento più grande nell'array usando [operator<()](../operator_less/) per confrontare gli elementi. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | Trova l'elemento più piccolo nell'array usando [operator<()](../operator_less/) per confrontare gli elementi. |
|  [Object](../object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../object/object/)([Object](../object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la copia dei sottoclassi. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la copia dei sottoclassi. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Operatore di assegnazione di spostamento. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Operatore di assegnazione di spostamento. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | Restituisce un elemento all'indice specificato. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | Restituisce un elemento all'indice specificato. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | Restituisce un puntatore al primo elemento di un array a dimensione singola. Per array multidimensionali il risultato è indefinito. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Restituisce un iteratore inverso al primo elemento del contenitore invertito. Corrisponde all'ultimo elemento del contenitore non invertito. Se il contenitore è vuoto, l'iteratore restituito è uguale a [rend()](./rend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Restituisce un iteratore inverso al primo elemento del contenitore invertito. Corrisponde all'ultimo elemento del contenitore non invertito. Se il contenitore è vuoto, l'iteratore restituito è uguale a [rend()](./rend/). |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringhe. |
| **bool** [Remove](./remove/)(const T\&) override | Non supportato perché l'array rappresentato dall'oggetto corrente è di sola lettura. |
| void [RemoveAt](./removeat/)(int) override | Non supportato perché l'array rappresentato dall'oggetto corrente è di sola lettura. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Restituisce un iteratore inverso all'elemento successivo all'ultimo elemento del contenitore invertito. Corrisponde all'elemento precedente al primo elemento del contenitore non invertito. Questo elemento funge da segnaposto; tentare di accedervi causa un comportamento indefinito. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Restituisce un iteratore inverso all'elemento successivo all'ultimo elemento del contenitore invertito. Corrisponde all'elemento precedente al primo elemento del contenitore non invertito. Questo elemento funge da segnaposto; tentare di accedervi causa un comportamento indefinito. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | Modifica la dimensione dell'array specificato al valore indicato o crea un nuovo array con la dimensione specificata. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Inverte gli elementi nell'array specificato. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Inverte un intervallo di elementi nell'array specificato. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Fa sì che l'array tratti i puntatori memorizzati come deboli (se applicabile). |
| void [SetValue](./setvalue/)(const T\&, int) | Imposta il valore dell'elemento all'indice specificato. |
| int [SharedCount](../object/sharedcount/)() const | Restituisce il valore corrente del contatore di riferimenti condivisi. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare invece smart pointers o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare invece smart pointers o ThisProtector. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Ordina gli elementi nell'array specificato usando il comparatore predefinito. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Ordina un intervallo di elementi nell'array specificato usando il comparatore predefinito. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Ordina gli elementi nell'array specificato usando il comparatore specificato. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | NON IMPLEMENTATO. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | Ordina gli elementi nell'array specificato usando il confronto specificato. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | Ordina due array, uno contenente le chiavi e l'altro gli elementi corrispondenti, basandosi sui valori dell'array contenente le chiavi, i cui elementi sono confrontati usando l'operatore <. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | Ordina due array, uno contenente le chiavi e l'altro gli elementi corrispondenti, basandosi sui valori dell'array contenente le chiavi, i cui elementi sono confrontati usando il comparatore predefinito. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Determina se tutti gli elementi nell'array specificato soddisfano le condizioni definite dal predicato specificato. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa la costruzione C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Ottiene l'implementazione dell'iteratore const begin per il contenitore corrente. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Ottiene l'implementazione dell'iteratore begin per il contenitore corrente. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Ottiene l'implementazione dell'iteratore const end per il contenitore corrente. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Ottiene l'implementazione dell'iteratore end per il contenitore corrente. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; usare invece smart pointers o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; usare invece smart pointers o ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Distruttore. |
| virtual  [~Object](../object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Definizioni di tipo

| Definizione di tipo | Descrizione |
| --- | --- |
| [ValueType](./valuetype/) | Alias per il tipo degli elementi dell'array. |
| [UnderlyingType](./underlyingtype/) | Alias per il tipo usato per rappresentare ogni elemento dell'array. |
| [EnumerablePtr](./enumerableptr/) | Un alias per il tipo puntatore condiviso che punta a un oggetto IEnumerable contenente elementi del tipo **T**. |
| [EnumeratorPtr](./enumeratorptr/) | Un alias per il tipo puntatore condiviso che punta a un oggetto IEnumerator contenente elementi del tipo **T**. |
| [iterator](./iterator/) | Tipo di iteratore. |
| [const_iterator](./const_iterator/) | Tipo di iteratore const. |
| [reverse_iterator](./reverse_iterator/) | Tipo di iteratore inverso. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipo di iteratore inverso const. |

## Osservazioni

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
  // Crea e riempi l'array.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Stampa gli elementi dell'array.
  Print(arrayPtr);

  // Ordina gli elementi dell'array in ordine crescente.
  Array<int32_t>::Sort(arrayPtr);

  // Stampa gli elementi dell'array.
  Print(arrayPtr);

  // Stampa il numero di elementi dell'array.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Stampa l'indice dell'elemento che è uguale a 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Ridimensiona l'array.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Stampa gli elementi dell'array.
  Print(arrayPtr);

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Vedi anche

* Classe [ArrayBase](../arraybase/)
* Classe [IList](../../system.collections.generic/ilist/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)