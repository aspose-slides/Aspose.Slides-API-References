---
title: X509Certificate2Collection
second_title: Aspose.Slides per l'API di riferimento C++
description: "Raccolta di oggetti certificato X509. Gli oggetti di questa classe devono essere allocati esclusivamente utilizzando la funzione System::MakeObject(). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e utilizzare tale puntatore per passarla alle funzioni come argomento."
type: docs
weight: 53
url: /it/system.security.cryptography.x509certificates/x509certificate2collection/
---
## X509Certificate2Collection classe

Raccolta di oggetti certificato X509. Gli oggetti di questa classe devono essere allocati esclusivamente mediante la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usare tale puntatore per passarla alle funzioni come argomento.

```cpp
class X509Certificate2Collection : public System::Collections::Generic::List<SharedPtr<X509Certificate2>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [_add_range](../../system.collections.generic/list/_add_range/)(std::initializer_list\<T\>) | Specifico C++. |
| void [Add](../../system.collections.generic/list/add/)(const T\&) override | Aggiunge l'elemento alla fine dell'elenco. |
| void [AddInitializer](../../system.collections.generic/list/addinitializer/)(int, const T *) | Aggiunge elementi all'elenco; usato durante la traduzione degli inizializzatori. |
| void [AddRange](../../system.collections.generic/list/addrange/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Aggiunge tutti gli elementi dalla collezione (o da sé) alla fine dell'elenco attuale. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../../system.collections.generic/list/asreadonly/)() | Ottiene un riferimento di sola lettura a questa collezione. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/list/begin/)() | Ottiene un iteratore al primo elemento della collezione. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/list/begin/)() const | Ottiene un iteratore al primo elemento della collezione qualificata come const. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&) const | Cerca l'elemento in un elenco ordinato. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Cerca l'elemento in un elenco ordinato. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | Cerca l'elemento in un elenco ordinato. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/list/cbegin/)() const | Ottiene un iteratore al primo elemento qualificato const della collezione. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/list/cend/)() const | Ottiene un iteratore per un elemento const non esistente dopo la fine della collezione. |
| void [Clear](../../system.collections.generic/list/clear/)() override | Elimina tutti gli elementi. |
| **bool** [Contains](../../system.collections.generic/list/contains/)(const T\&) const override | Verifica se l'elemento è presente nell'elenco. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<OutputType\>\> [ConvertAll](../../system.collections.generic/list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Crea un elenco di elementi convertiti in un tipo diverso. |
| void [CopyTo](../../system.collections.generic/list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Copia gli elementi dell'elenco in elementi di array esistenti. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Copia tutti gli elementi in elementi di array esistenti. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Copia gli elementi a partire dall'indice specificato in elementi di array esistenti. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crbegin](../../system.collections.generic/list/crbegin/)() const | Ottiene un iteratore inverso all'ultimo elemento qualificato const della collezione (primo in ordine inverso). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crend](../../system.collections.generic/list/crend/)() const | Ottiene un iteratore inverso per un elemento const non esistente prima dell'inizio della collezione. |
| [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() | Funzione di accesso alla struttura dati sottostante. |
| const [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() const | Funzione di accesso alla struttura dati sottostante. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/list/end/)() | Ottiene un iteratore per un elemento non esistente dopo la fine della collezione. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/list/end/)() const | Ottiene un iteratore per un elemento non esistente dopo la fine della collezione qualificata come const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| **bool** [Exists](../../system.collections.generic/list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Verifica se un elemento che soddisfa un predicato specifico esiste nell'elenco. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| T [Find](../../system.collections.generic/list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Cerca l'elemento che soddisfa un predicato specifico. |
| [ListPtr](../../system.collections.generic/listptr/)\<T\> [FindAll](../../system.collections.generic/list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Cerca gli elementi che soddisfano un predicato specifico. |
| int [FindIndex](../../system.collections.generic/list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Cerca l'elemento che soddisfa un predicato specifico. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Cerca l'elemento che soddisfa un predicato specifico. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Cerca l'elemento che soddisfa un predicato specifico. |
| T [FindLast](../../system.collections.generic/list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Cerca l'ultimo elemento che soddisfa un predicato specifico. |
| void [ForEach](../../system.collections.generic/list/foreach/)([System::Action](../../system/action/)\<T\>) | Applica un'azione a tutti gli elementi dell'elenco. |
| int [get_Capacity](../../system.collections.generic/list/get_capacity/)() const | Ottiene la capacità attuale dell'elenco. |
| int [get_Count](../../system.collections.generic/list/get_count/)() const override | Ottiene il numero di elementi nell'elenco attuale. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Verifica se la collezione è di dimensione fissa. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | Verifica se la collezione è di sola lettura. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Ottiene l'oggetto attraverso il quale la collezione è sincronizzata. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| [IEnumeratorPtr](../../system.collections.generic/list/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/list/getenumerator/)() override | Ottiene un enumeratore per iterare attraverso gli elementi dell'elenco. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| **ThisPtr** [GetRange](../../system.collections.generic/list/getrange/)(int, int) | Crea una sezione dell'elenco. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Costruttore predefinito. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Costruttore di copia. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Costruttore di spostamento. |
| T [idx_get](../../system.collections.generic/list/idx_get/)(int) const override | Ottiene l'elemento in una posizione specifica. |
| void [idx_set](../../system.collections.generic/list/idx_set/)(int, T) override | Imposta l'elemento in una posizione specifica. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&) const override | Ottiene il primo indice dell'elemento specifico. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&, int) const | Cerca un elemento specifico nell'elenco. |
| void [Insert](../../system.collections.generic/list/insert/)(int, const T\&) override | Inserisce l'elemento nella posizione specificata. |
| void [InsertRange](../../system.collections.generic/list/insertrange/)(int, [IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Inserisce un intervallo di dati in una posizione specifica. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&) const | Cerca l'oggetto specificato e restituisce l'indice base zero dell'ultima occorrenza nell'intero elenco. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**) const | Cerca l'oggetto specificato e restituisce l'indice base zero dell'ultima occorrenza nell'intervallo di elementi nella [List](../../system.collections.generic/list/) che si estende dal primo elemento fino all'indice specificato. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Cerca l'oggetto specificato e restituisce l'indice base zero dell'ultima occorrenza nell'intervallo di elementi nella [List](../../system.collections.generic/list/) che contiene il numero specificato di elementi e termina all'indice specificato. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Applica una funzione accumulatore su una sequenza. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina se tutti gli elementi di una sequenza soddisfano una condizione. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Determina se una sequenza contiene elementi. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina se esiste qualche elemento in una sequenza o se soddisfa una condizione. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Calcola la media di una sequenza di valori numerici. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Calcola la media di una sequenza di valori ottenuti invocando una funzione di trasformazione su ogni elemento della sequenza di input. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Esegue il cast degli elementi al tipo specificato. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Concatena due sequenze. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Determina se una sequenza contiene un valore specificato. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Restituisce il numero di elementi nella sequenza (calcolato tramite conteggio diretto). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Restituisce il numero di elementi nella sequenza che soddisfano la condizione specificata. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Restituisce l'elemento a un indice specificato in una sequenza. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Restituisce l'elemento a un indice specificato in una sequenza. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Restituisce il primo elemento di una sequenza. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Restituisce il primo elemento di una sequenza che soddisfa la condizione specificata. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Restituisce il primo elemento di una sequenza, o un valore predefinito se la sequenza è vuota. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Restituisce il primo elemento della sequenza che soddisfa una condizione o un valore predefinito se nessun elemento viene trovato. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Raggruppa gli elementi di una sequenza. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Raggruppa gli elementi di una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Restituisce l'ultimo elemento di una sequenza. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Restituisce l'ultimo elemento di una sequenza, o un valore predefinito se la sequenza è vuota. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca una funzione di trasformazione su ogni elemento di una sequenza generica e restituisce il valore massimo risultante. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca una funzione di trasformazione su ogni elemento di una sequenza generica e restituisce il valore minimo risultante. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtra gli elementi della sequenza in base al tipo specificato. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordina gli elementi di una sequenza in ordine crescente secondo i valori chiave selezionati da keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordina gli elementi di una sequenza in ordine decrescente secondo i valori chiave selezionati da keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Inverte l'ordine degli elementi in una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Trasforma gli elementi di una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Trasforma ogni elemento di una sequenza in una nuova forma incorporando l'indice dell'elemento. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Proietta ogni elemento di una sequenza e combina le sequenze risultanti in una sola sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Salta un numero specificato di elementi contigui dall'inizio di una sequenza e restituisce il resto. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Restituisce un numero specificato di elementi contigui dall'inizio di una sequenza. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Crea un array da una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Crea una List<T> da una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra una sequenza in base al predicato specificato. |
|  [List](../../system.collections.generic/list/list/)() | Crea un elenco vuoto. |
|  [List](../../system.collections.generic/list/list/)(int) | Crea un elenco con capacità predefinita. |
|  [List](../../system.collections.generic/list/list/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | Costruttore di copia. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza il nuovo oggetto e consente la costruzione di copie nelle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza il nuovo oggetto e consente la costruzione di copie nelle sottoclassi. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Operatore di assegnazione di spostamento. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Operatore di assegnazione di spostamento. |
| vector_t::reference [operator[]](../../system.collections.generic/list/operator[]/)(int) | Funzione di accesso. |
| vector_t::const_reference [operator[]](../../system.collections.generic/list/operator[]/)(int) const | Funzione di accesso. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() | Ottiene un iteratore inverso all'ultimo elemento della collezione (primo in ordine inverso). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() const | Ottiene un iteratore inverso all'ultimo elemento della collezione qualificata const (primo in ordine inverso). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| **bool** [Remove](../../system.collections.generic/list/remove/)(const T\&) override | Rimuove la prima istanza dell'elemento specifico dall'elenco. |
| int [RemoveAll](../../system.collections.generic/list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Rimuove tutti gli elementi che corrispondono a un predicato specifico. |
| void [RemoveAt](../../system.collections.generic/list/removeat/)(int) override | Rimuove l'elemento nella posizione specificata. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [RemoveRange](../../system.collections.generic/list/removerange/)(int, int) | Rimuove una sezione dell'elenco. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() | Ottiene un iteratore inverso per un elemento non esistente prima dell'inizio della collezione. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() const | Ottiene un iteratore inverso per un elemento non esistente prima dell'inizio della collezione qualificata const. |
| void [Reverse](../../system.collections.generic/list/reverse/)() | Inverte l'ordine degli elementi dell'intero elenco. |
| void [Reverse](../../system.collections.generic/list/reverse/)(int, int) | Inverte l'ordine degli elementi della sezione dell'elenco. |
| void [set_Capacity](../../system.collections.generic/list/set_capacity/)(int) | Imposta la capacità dell'elenco. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (invece di condiviso). Permette di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore attuale del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [Sort](../../system.collections.generic/list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Ordina gli elementi nella lista. |
| void [Sort](../../system.collections.generic/list/sort/)() | Ordina gli elementi nella lista usando il comparatore predefinito. |
| void [Sort](../../system.collections.generic/list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>) | Ordina gli elementi nella sezione della lista. |
| void [Sort](../../system.collections.generic/list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Ordina gli elementi nella lista. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../../system.collections.generic/list/toarray/)() const | Converte la lista in array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| void [TrimExcess](../../system.collections.generic/list/trimexcess/)() | Adatta la capacità della lista alla sua dimensione. |
| **bool** [TrueForAll](../../system.collections.generic/list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Determina se ogni elemento della collezione soddisfa le condizioni definite dal predicato specificato. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.generic/list/virtualizebeginconstiterator/)() const override | Ottiene l'implementazione dell'iteratore begin const per il contenitore corrente. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.generic/list/virtualizebeginiterator/)() override | Ottiene l'implementazione dell'iteratore begin per il contenitore corrente. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.generic/list/virtualizeendconstiterator/)() const override | Ottiene l'implementazione dell'iteratore end const per il contenitore corrente. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.generic/list/virtualizeenditerator/)() override | Ottiene l'implementazione dell'iteratore end per il contenitore corrente. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Distruttore. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [List](../../system.collections.generic/list/)
* Spazio dei nomi [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.Slides](../../)