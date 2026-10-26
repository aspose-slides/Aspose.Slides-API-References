---
title: List
second_title: Riferimento API Aspose.Slides per C++
description: Dichiarazione anticipata di List.
type: docs
weight: 430
url: /it/system.collections.generic/list/
---
## classe List

[List](./) dichiarazione anticipata.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo dell'elemento. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | Specifico C++. |
| void [Add](./add/)(const T\&) override | Aggiunge un elemento alla fine della lista. |
| void [AddInitializer](./addinitializer/)(int, const T *) | Aggiunge elementi alla lista; usato durante la traduzione di inizializzatori. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | Aggiunge tutti gli elementi dalla collezione (o da sé) alla fine della lista corrente. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | Ottiene un riferimento di sola lettura a questa collezione. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Ottiene un iteratore al primo elemento della collezione. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Ottiene un iteratore al primo elemento della collezione qualificata const. |
| int [BinarySearch](./binarysearch/)(const T\&) const | Cerca l'elemento in una lista ordinata. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Cerca l'elemento in una lista ordinata. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Cerca l'elemento in una lista ordinata. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Ottiene un iteratore al primo elemento const-qualificato della collezione. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Ottiene un iteratore per un elemento const-qualificato inesistente oltre la fine della collezione. |
| void [Clear](./clear/)() override | Elimina tutti gli elementi. |
| **bool** [Contains](./contains/)(const T\&) const override | Verifica se l'elemento è presente nella lista. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Crea una lista di elementi convertiti in un tipo diverso. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Copia gli elementi della lista in elementi di un array esistente. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Copia tutti gli elementi in elementi di un array esistente. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Copia gli elementi a partire dall'indice specificato in elementi di un array esistente. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Ottiene un iteratore inverso all'ultimo elemento const-qualificato della collezione (primo in ordine inverso). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Ottiene un iteratore inverso per un elemento const-qualificato inesistente prima dell'inizio della collezione. |
| [vector_t](./vector_t/)\& [data](./data/)() | Funzione di accesso alla struttura dati sottostante. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | Funzione di accesso alla struttura dati sottostante. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Ottiene un iteratore per un elemento inesistente oltre la fine della collezione. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Ottiene un iteratore per un elemento inesistente oltre la fine della collezione const-qualificata. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | Verifica se esiste un elemento che soddisfa un predicato specifico nella lista. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | Cerca un elemento che soddisfa un predicato specifico. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | Cerca elementi che soddisfano un predicato specifico. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Cerca un elemento che soddisfa un predicato specifico. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Cerca un elemento che soddisfa un predicato specifico. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Cerca un elemento che soddisfa un predicato specifico. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Cerca l'ultimo elemento che soddisfa un predicato specifico. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | Applica l'azione a tutti gli elementi della lista. |
| int [get_Capacity](./get_capacity/)() const | Ottiene la capacità corrente della lista. |
| int [get_Count](./get_count/)() const override | Ottiene il numero di elementi nella lista corrente. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Verifica se la collezione ha dimensione fissa. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Verifica se la collezione è di sola lettura. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Ottiene l'oggetto tramite il quale la collezione è sincronizzata. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Ottiene l'enumeratore per iterare attraverso gli elementi della lista. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | Crea una porzione della lista. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Costruttore predefinito. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Costruttore di copia. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Costruttore di spostamento. |
| T [idx_get](./idx_get/)(int) const override | Ottiene l'elemento in una posizione specifica. |
| void [idx_set](./idx_set/)(int, T) override | Imposta l'elemento in una posizione specifica. |
| int [IndexOf](./indexof/)(const T\&) const override | Ottiene il primo indice dell'elemento specifico. |
| int [IndexOf](./indexof/)(const T\&, int) const | Cerca un elemento specifico nella lista. |
| void [Insert](./insert/)(int, const T\&) override | Inserisce l'elemento nella posizione specificata. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | Inserisce un intervallo di dati in una posizione specifica. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | Cerca l'oggetto specificato e restituisce l'indice basato su zero dell'ultima occorrenza nell'intera lista. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | Cerca l'oggetto specificato e restituisce l'indice basato su zero dell'ultima occorrenza nell'intervallo di elementi in [List](./) che si estende dal primo elemento all'indice specificato. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Cerca l'oggetto specificato e restituisce l'indice basato su zero dell'ultima occorrenza nell'intervallo di elementi in [List](./) che contiene il numero specificato di elementi e termina all'indice specificato. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Applica una funzione di accumulatore su una sequenza. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina se tutti gli elementi di una sequenza soddisfano una condizione. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Determina se una sequenza contiene elementi. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina se esiste qualche elemento in una sequenza o se soddisfa una condizione. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Calcola la media di una sequenza di valori numerici. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Calcola la media di una sequenza di valori ottenuti invocando una funzione di trasformazione su ciascun elemento della sequenza di input. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Effettua il cast degli elementi al tipo specificato. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Concatena due sequenze. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Determina se una sequenza contiene un valore specificato. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Restituisce il numero di elementi nella sequenza (calcolato tramite conteggio diretto). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Restituisce il numero di elementi nella sequenza che soddisfano la condizione specificata. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Restituisce l'elemento all'indice specificato in una sequenza. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Restituisce l'elemento all'indice specificato in una sequenza. |
| T [LINQ_First](../ienumerable/linq_first/)() | Restituisce il primo elemento di una sequenza. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Restituisce il primo elemento di una sequenza che soddisfa la condizione specificata. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Restituisce il primo elemento di una sequenza, o un valore predefinito se la sequenza è vuota. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Restituisce il primo elemento della sequenza che soddisfa una condizione o un valore predefinito se nessun elemento corrispondente è stato trovato. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Raggruppa gli elementi di una sequenza. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Raggruppa gli elementi di una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Restituisce l'ultimo elemento di una sequenza. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Restituisce l'ultimo elemento di una sequenza, o un valore predefinito se la sequenza è vuota. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca una funzione di trasformazione su ciascun elemento di una sequenza generica e restituisce il valore massimo risultante. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoca una funzione di trasformazione su ciascun elemento di una sequenza generica e restituisce il valore minimo risultante. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtra gli elementi della sequenza in base al tipo specificato. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordina gli elementi di una sequenza in ordine crescente in base ai valori chiave selezionati da keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordina gli elementi di una sequenza in ordine decrescente in base ai valori chiave selezionati da keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Inverti l'ordine degli elementi in una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Trasforma gli elementi di una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Trasforma ciascun elemento di una sequenza in una nuova forma incorporando l'indice dell'elemento. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Proietta ciascun elemento di una sequenza e combina le sequenze risultanti in un'unica sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Salta un numero specificato di elementi contigui dall'inizio di una sequenza e restituisce il resto. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Restituisce un numero specificato di elementi contigui dall'inizio di una sequenza. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Crea un array da una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Crea una List<T> da una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra una sequenza in base al predicato specificato. |
|  [List](./list/)() | Crea una lista vuota. |
|  [List](./list/)(int) | Crea una lista con capacità predefinita. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | Costruttore di copia. |
| void [Lock](../../system/object/lock/)() | Implementa il lock della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea un oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie per le sottoclassi. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operatore di assegnazione di spostamento. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operatore di assegnazione di spostamento. |
| vector_t::reference [operator[]](./operator[]/)(int) | Funzione di accesso. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Funzione di accesso. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Ottiene un iteratore inverso all'ultimo elemento della collezione (primo in ordine inverso). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Ottiene un iteratore inverso all'ultimo elemento della collezione const-qualificata (primo in ordine inverso). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| **bool** [Remove](./remove/)(const T\&) override | Rimuove la prima istanza dell'elemento specifico dalla lista. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Rimuove tutti gli elementi che corrispondono al predicato specifico. |
| void [RemoveAt](./removeat/)(int) override | Rimuove l'elemento nella posizione specificata. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso di un valore specificato. |
| void [RemoveRange](./removerange/)(int, int) | Rimuove una porzione della lista. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Ottiene un iteratore inverso per un elemento inesistente prima dell'inizio della collezione. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Ottiene un iteratore inverso per un elemento inesistente prima dell'inizio della collezione const-qualificata. |
| void [Reverse](./reverse/)() | Inverte l'ordine degli elementi dell'intera lista. |
| void [Reverse](./reverse/)(int, int) | Inverte l'ordine degli elementi della porzione di lista. |
| void [set_Capacity](./set_capacity/)(int) | Imposta la capacità della lista. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (piuttosto che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Ordina gli elementi nella lista. |
| void [Sort](./sort/)() | Ordina gli elementi nella lista usando il comparatore predefinito. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Ordina gli elementi nella porzione di lista. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Ordina gli elementi nella lista. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Converte la lista in un array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| void [TrimExcess](./trimexcess/)() | Adatta la capacità della lista alla sua dimensione. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Determina se tutti gli elementi della collezione soddisfano le condizioni definite dal predicato specificato. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Ottiene l'implementazione dell'iteratore begin const per il contenitore corrente. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Ottiene l'implementazione dell'iteratore begin per il contenitore corrente. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Ottiene l'implementazione dell'iteratore end const per il contenitore corrente. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Ottiene l'implementazione dell'iteratore end per il contenitore corrente. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Distruttore. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Alias di tipo

| Alias | Descrizione |
| --- | --- |
| [ValueType](./valuetype/) | Questo tipo. |
| [BaseType](./basetype/) | Tipo interfaccia. |
| [vector_t](./vector_t/) | Tipo dati sottostante. |
| [iterator](./iterator/) | Tipo iteratore. |
| [const_iterator](./const_iterator/) | Tipo iteratore const. |
| [reverse_iterator](./reverse_iterator/) | Tipo iteratore inverso. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipo iteratore inverso const. |
| [IEnumerablePtr](./ienumerableptr/) | Container che contiene elementi dello stesso tipo che noi trattiamo. |
| [IEnumeratorPtr](./ienumeratorptr/) | tipo **Enumerator** |
## Osservazioni

[List](./) - wrapper intorno a std::vector da usare nel codice tradotto. Richiede che l'operatore == sia implementato per il tipo di elemento. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Crea la prima lista.
  auto list1 = MakeObject<List<int>>();

  // Riempie la prima lista.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Ordina la prima lista.
  // Gli elementi della prima lista saranno: {-5, 1, 3, 8}
  list1->Sort();

  // Rimuove l'elemento all'indice 2.
  // Gli elementi della prima lista saranno: {-5, 1, 8}
  list1->RemoveAt(2);

  // Inserisce l'elemento all'indice 1.
  // Gli elementi della prima lista saranno: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Crea la seconda lista.
  auto list2 = MakeObject<List<int>>();

  // Riempie la seconda lista.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Aggiunge gli elementi dalla seconda lista alla prima.
  list1->AddRange(list2);

  // Stampa gli elementi della prima lista.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
- 5 15 1 8 10 20 30
*/
```

## Vedi anche

* Classe [Object](../../system/object/)
* Classe [IList](../ilist/)
* Spazio dei nomi [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)