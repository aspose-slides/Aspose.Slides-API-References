---
title: ListExt
second_title: Riferimento API di Aspose.Slides per C++
description: classe List generica che implementa l'interfaccia IListWrapper
type: docs
weight: 443
url: /it/system.collections.generic/listext/
---
## ListExt classe

classe [List](../list/) generica che implementa l'interfaccia [IListWrapper](../../system.collections/ilistwrapper/)

```cpp
template<typename T>class ListExt : public System::Collections::Generic::List<T>,
                                    public System::Collections::IListWrapper
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [_add_range](../list/_add_range/)(std::initializer_list\<T\>) | Specifico C++. |
| void [Add](../list/add/)(const T\&) override | Aggiunge l'elemento alla fine della lista. |
| void [AddInitializer](../list/addinitializer/)(int, const T *) | Aggiunge elementi alla lista; usato durante la traduzione di inizializzatori. |
| void [AddRange](../list/addrange/)([IEnumerablePtr](../list/ienumerableptr/)) | Aggiunge tutti gli elementi dalla collezione (o se stessa) alla fine della lista corrente. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../list/asreadonly/)() | Ottiene un riferimento di sola lettura a questa collezione. |
| [iterator](../ienumerable/iterator/) [begin](../list/begin/)() | Ottiene un iteratore al primo elemento della collezione. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../list/begin/)() const | Ottiene un iteratore al primo elemento della collezione qualificata come const. |
| int [BinarySearch](../list/binarysearch/)(const T\&) const | Cerca l'elemento in una lista ordinata. |
| int [BinarySearch](../list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Cerca l'elemento in una lista ordinata. |
| int [BinarySearch](../list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Cerca l'elemento in una lista ordinata. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../list/cbegin/)() const | Ottiene un iteratore al primo elemento qualificato const della collezione. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../list/cend/)() const | Ottiene un iteratore per un elemento const non esistente dietro la fine della collezione. |
| void [Clear](../list/clear/)() override | Elimina tutti gli elementi. |
| **bool** [Contains](../list/contains/)(const T\&) const override | Verifica se l'elemento è presente nella lista. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<OutputType\>\> [ConvertAll](../list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Crea una lista di elementi convertiti in un tipo diverso. |
| void [CopyTo](../list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Copia gli elementi della lista in elementi di un array esistente. |
| void [CopyTo](../list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Copia tutti gli elementi in elementi di un array esistente. |
| void [CopyTo](../list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Copia gli elementi a partire dall'indice specificato in elementi di un array esistente. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crbegin](../list/crbegin/)() const | Ottiene un iteratore inverso all'ultimo elemento qualificato const della collezione (primo in ordine inverso). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CreateIListWrapper](./createilistwrapper/)() override | implementazione dell'interfaccia [IListWrapper](../../system.collections/ilistwrapper/). |
| std::enable_if\<[System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | assistente di implementazione per tipi di riferimento [IListWrapper](../../system.collections/ilistwrapper/). |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[System::IsBoxable](../../system/isboxable/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | assistente di implementazione per tipi valore [IListWrapper](../../system.collections/ilistwrapper/). |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![System::IsBoxable](../../system/isboxable/)\<T\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | assistente di implementazione per altri tipi [IListWrapper](../../system.collections/ilistwrapper/). |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crend](../list/crend/)() const | Ottiene un iteratore inverso per un elemento const non esistente prima dell'inizio della collezione. |
| [vector_t](../list/vector_t/)\& [data](../list/data/)() | Funzione di accesso alla struttura dati sottostante. |
| const [vector_t](../list/vector_t/)\& [data](../list/data/)() const | Funzione di accesso alla struttura dati sottostante. |
| [iterator](../ienumerable/iterator/) [end](../list/end/)() | Ottiene un iteratore per un elemento non esistente dietro la fine della collezione. |
| [const_iterator](../ienumerable/const_iterator/) [end](../list/end/)() const | Ottiene un iteratore per un elemento non esistente dietro la fine della collezione qualificata come const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| **bool** [Exists](../list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Verifica se esiste un elemento che soddisfa un predicato specifico nella lista. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| T [Find](../list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Cerca un elemento che soddisfa un predicato specifico. |
| [ListPtr](../listptr/)\<T\> [FindAll](../list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Cerca elementi che soddisfano un predicato specifico. |
| int [FindIndex](../list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Cerca un elemento che soddisfa un predicato specifico. |
| int [FindIndex](../list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Cerca un elemento che soddisfa un predicato specifico. |
| int [FindIndex](../list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Cerca un elemento che soddisfa un predicato specifico. |
| T [FindLast](../list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Cerca l'ultimo elemento che soddisfa un predicato specifico. |
| void [ForEach](../list/foreach/)([System::Action](../../system/action/)\<T\>) | Applica un'azione a tutti gli elementi della lista. |
| int [get_Capacity](../list/get_capacity/)() const | Ottiene la capacità corrente della lista. |
| int [get_Count](../list/get_count/)() const override | Ottiene il numero di elementi nella lista corrente. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Verifica se la collezione ha dimensione fissa. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Verifica se la collezione è di sola lettura. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Ottiene l'oggetto attraverso il quale la collezione è sincronizzata. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| [IEnumeratorPtr](../list/ienumeratorptr/) [GetEnumerator](../list/getenumerator/)() override | Ottiene l'enumeratore per iterare attraverso gli elementi della lista. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| **ThisPtr** [GetRange](../list/getrange/)(int, int) | Crea una sezione della lista. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Costruttore predefinito. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Costruttore di copia. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Costruttore di spostamento. |
| T [idx_get](../list/idx_get/)(int) const override | Ottiene l'elemento in una posizione specifica. |
| void [idx_set](../list/idx_set/)(int, T) override | Imposta l'elemento in una posizione specifica. |
| int [IndexOf](../list/indexof/)(const T\&) const override | Ottiene il primo indice di un elemento specifico. |
| int [IndexOf](../list/indexof/)(const T\&, int) const | Cerca un elemento specifico nella lista. |
| void [Insert](../list/insert/)(int, const T\&) override | Inserisce l'elemento nella posizione specificata. |
| void [InsertRange](../list/insertrange/)(int, [IEnumerablePtr](../list/ienumerableptr/)) | Inserisce un intervallo di dati in una posizione specifica. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&) const | Cerca l'oggetto specificato e restituisce l'indice basato su zero dell'ultima occorrenza all'interno dell'intera lista. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**) const | Cerca l'oggetto specificato e restituisce l'indice basato su zero dell'ultima occorrenza nell'intervallo di elementi in [List](../list/) che si estende dal primo elemento all'indice specificato. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Cerca l'oggetto specificato e restituisce l'indice basato su zero dell'ultima occorrenza nell'intervallo di elementi in [List](../list/) che contiene il numero specificato di elementi e termina all'indice specificato. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Applica una funzione di accumulatore su una sequenza. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina se tutti gli elementi di una sequenza soddisfano una condizione. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Determina se una sequenza contiene elementi. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina se esiste un elemento in una sequenza o se soddisfa una condizione. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Calcola la media di una sequenza di valori numerici. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Calcola la media di una sequenza di valori ottenuti invocando una funzione di trasformazione su ogni elemento della sequenza di ingresso. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Esegue il cast degli elementi al tipo specificato. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Concatena due sequenze. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Determina se una sequenza contiene un valore specificato. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Restituisce il numero di elementi nella sequenza (calcolato tramite conteggio diretto). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Restituisce il numero di elementi nella sequenza che soddisfano la condizione specificata. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Restituisce l'elemento a un indice specificato in una sequenza. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Restituisce l'elemento a un indice specificato in una sequenza. |
| T [LINQ_First](../ienumerable/linq_first/)() | Restituisce il primo elemento di una sequenza. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Restituisce il primo elemento di una sequenza che soddisfa la condizione specificata. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Restituisce il primo elemento di una sequenza, o un valore predefinito se la sequenza è vuota. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Restituisce il primo elemento della sequenza che soddisfa una condizione o un valore predefinito se nessun elemento corrisponde. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Raggruppa gli elementi di una sequenza. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Raggruppa gli elementi di una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Restituisce l'ultimo elemento di una sequenza. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Restituisce l'ultimo elemento di una sequenza, o un valore predefinito se la sequenza è vuota. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca una funzione di trasformazione su ogni elemento di una sequenza generica e restituisce il valore massimo risultante. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca una funzione di trasformazione su ogni elemento di una sequenza generica e restituisce il valore minimo risultante. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtra gli elementi della sequenza in base al tipo specificato. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordina gli elementi di una sequenza in ordine crescente in base ai valori chiave selezionati da keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordina gli elementi di una sequenza in ordine decrescente in base ai valori chiave selezionati da keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Inverte l'ordine degli elementi in una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Trasforma gli elementi di una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Trasforma ciascun elemento di una sequenza in una nuova forma incorporando l'indice dell'elemento. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Proietta ciascun elemento di una sequenza e combina le sequenze risultanti in un'unica sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Salta un numero specificato di elementi contigui dall'inizio di una sequenza e restituisce il resto. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Restituisce un numero specificato di elementi contigui dall'inizio di una sequenza. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Crea un array da una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Crea una List<T> da una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra una sequenza in base al predicato specificato. |
|  [List](../list/list/)() | Crea una lista vuota. |
|  [List](../list/list/)(int) | Crea una lista con capacità predefinita. |
|  [List](../list/list/)([IEnumerablePtr](../list/ienumerableptr/)) | Costruttore di copia. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() statement di C# per il blocco. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea un oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie di subclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie di subclassi. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operatore di assegnazione di spostamento. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operatore di assegnazione di spostamento. |
| vector_t::reference [operator[]](../list/operator[]/)(int) | Funzione di accesso. |
| vector_t::const_reference [operator[]](../list/operator[]/)(int) const | Funzione di accesso. |
| [reverse_iterator](../list/reverse_iterator/) [rbegin](../list/rbegin/)() | Ottiene un iteratore inverso all'ultimo elemento della collezione (primo in ordine inverso). |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rbegin](../list/rbegin/)() const | Ottiene un iteratore inverso all'ultimo elemento della collezione qualificata const (primo in ordine inverso). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| **bool** [Remove](../list/remove/)(const T\&) override | Rimuove la prima occorrenza di un elemento specifico dalla lista. |
| int [RemoveAll](../list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Rimuove tutti gli elementi che corrispondono al predicato specifico. |
| void [RemoveAt](../list/removeat/)(int) override | Rimuove l'elemento nella posizione specificata. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [RemoveRange](../list/removerange/)(int, int) | Rimuove una sezione della lista. |
| [reverse_iterator](../list/reverse_iterator/) [rend](../list/rend/)() | Ottiene un iteratore inverso per un elemento non esistente prima dell'inizio della collezione. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rend](../list/rend/)() const | Ottiene un iteratore inverso per un elemento non esistente prima dell'inizio della collezione qualificata const. |
| void [Reverse](../list/reverse/)() | Inverte l'ordine degli elementi dell'intera lista. |
| void [Reverse](../list/reverse/)(int, int) | Inverte l'ordine degli elementi della sezione della lista. |
| void [set_Capacity](../list/set_capacity/)(int) | Imposta la capacità della lista. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [Sort](../list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Ordina gli elementi nella lista. |
| void [Sort](../list/sort/)() | Ordina gli elementi nella lista usando il comparatore predefinito. |
| void [Sort](../list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Ordina gli elementi nella sezione della lista. |
| void [Sort](../list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Ordina gli elementi nella lista. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../list/toarray/)() const | Converte la lista in un array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| void [TrimExcess](../list/trimexcess/)() | Adatta la capacità della lista alla sua dimensione. |
| **bool** [TrueForAll](../list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Determina se tutti gli elementi nella collezione soddisfano le condizioni definite dal predicato specificato. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del lock() statement di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../list/virtualizebeginconstiterator/)() const override | Ottiene l'implementazione dell'iteratore begin const per il contenitore corrente. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../list/virtualizebeginiterator/)() override | Ottiene l'implementazione dell'iteratore begin per il contenitore corrente. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../list/virtualizeendconstiterator/)() const override | Ottiene l'implementazione dell'iteratore end const per il contenitore corrente. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../list/virtualizeenditerator/)() override | Ottiene l'implementazione dell'iteratore end per il contenitore corrente. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Distruttore. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [ThisType](./thistype/) |  |
| [ListType](./listtype/) |  |
| [BaseTypes](./basetypes/) |  |
| [ValueType](./valuetype/) |  |
| [BaseType](./basetype/) |  |

## Vedi anche

* Classe [List](../list/)
* Classe [IListWrapper](../../system.collections/ilistwrapper/)
* Namespace [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)