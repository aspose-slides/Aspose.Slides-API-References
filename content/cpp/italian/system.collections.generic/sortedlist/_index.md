---
title: SortedList
second_title: Riferimento API di Aspose.Slides per C++
description: "Lista ordinata che avvolge la struttura FlatMap. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e utilizza questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 547
url: /it/system.collections.generic/sortedlist/
---
## SortedList classe

Sorted list wrapping FlatMap structure. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename TKey,typename TValue>class SortedList : public System::Collections::Generic::SortedListHelper<TKey, TValue>,
                                                          public System::Collections::Generic::BaseDictionary<Detail::FlatMap<TKey, TValue, ComparerAdapter<TKey>>>
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Tipo chiave. |
| TValue | Tipo valore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey&, const TValue&) | Aggiunge una coppia chiave-valore nel contenitore. |
| virtual void [Add](../icollection/add/)(const T&) | Aggiunge un elemento alla collezione. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Ottiene un iteratore che punta al primo elemento (se presente) della collezione. Questo iteratore non può essere usato per modificare l'oggetto referenziato perché [GetEnumerator()](../ienumerable/getenumerator/) restituisce una copia dell'oggetto T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Ottiene un iteratore che punta al primo elemento (se presente) dell'istanza qualificata const della collezione. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Ottiene un iteratore che punta al primo elemento qualificato const (se presente) della collezione. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Ottiene un iteratore che punta subito dopo l'ultimo elemento qualificato const (se presente) della collezione. |
| virtual void [Clear](../icollection/clear/)() | Elimina tutti gli elementi dalla collezione. |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | Verifica se l'elemento è presente nella collezione. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey&) const | Verifica se il contenitore contiene la chiave. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../keyvaluepair/)<TKey, TValue>>, int) override | Copia il contenuto del dizionario negli elementi di un array esistente. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Ottiene un iteratore inverso all'ultimo elemento qualificato const della collezione (primo in ordine inverso). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Ottiene un iteratore inverso per un elemento const non esistente prima dell'inizio della collezione. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Ottiene un iteratore che punta subito dopo l'ultimo elemento (se presente) della collezione. Questo iteratore non può essere usato per modificare l'oggetto referenziato perché [GetEnumerator()](../ienumerable/getenumerator/) restituisce una copia dell'oggetto T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Ottiene un iteratore che punta subito dopo l'ultimo elemento (se presente) dell'istanza qualificata const della collezione. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T1>::value&&\![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali, anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali, anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Solo per uso interno. |
| int [get_Capacity](./get_capacity/)() const | Ottiene la capacità attuale della lista. |
| virtual int [get_Count](../icollection/get_count/)() const | Ottiene il numero di elementi nella collezione. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | Verifica se la dimensione della collezione è fissa. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Verifica se la collezione è di sola lettura. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | Verifica se il contenitore è thread-safe. |
| virtual [SharedPtr](../../system/sharedptr/)<[IList](../ilist/)<TKey>> [get_Keys](./get_keys/)() const | Accede alla collezione delle chiavi. |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | Ottiene l'oggetto attraverso cui la collezione è sincronizzata. |
| virtual [SharedPtr](../../system/sharedptr/)<[IList](../ilist/)<TValue>> [get_Values](./get_values/)() const | Accede alla collezione dei valori. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Ottiene l'enumeratore che itera la lista corrente. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&) const | Restituisce il valore se trovato; altrimenti **Value()**. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&, const TValue&) const | Restituisce il valore se trovato; altrimenti **defaultValue**. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey&) const | Restituisce il valore se trovato; altrimenti **null**, ha senso solo per tipi di riferimento. |
| [ICollection](../icollection/icollection/)() | Costruttore predefinito. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | Costruttore di copia. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | Costruttore di spostamento. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey&) const | Funzione getter. |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey&, TValue) | Funzione setter. |
| int [IndexOfKey](./indexofkey/)(TKey) const | Cerca una chiave specifica. |
| int [IndexOfValue](./indexofvalue/)(TValue) const | Cerca un valore specifico. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | Applica una funzione accumulatore su una sequenza. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | Determina se tutti gli elementi di una sequenza soddisfano una condizione. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Determina se una sequenza contiene elementi. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | Determina se esiste un elemento in una sequenza o se soddisfa una condizione. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Calcola la media di una sequenza di valori numerici. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | Calcola la media di una sequenza di valori ottenuti invocando una funzione di trasformazione su ciascun elemento della sequenza di input. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | Esegue il cast degli elementi al tipo specificato. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> ) | Concatena due sequenze. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Determina se una sequenza contiene un valore specificato. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Restituisce il numero di elementi nella sequenza (calcolato tramite conteggio diretto). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | Restituisce il numero di elementi nella sequenza che soddisfano la condizione specificata. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Restituisce l'elemento a un indice specificato in una sequenza. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Restituisce l'elemento a un indice specificato in una sequenza. |
| T [LINQ_First](../ienumerable/linq_first/)() | Restituisce il primo elemento di una sequenza. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | Restituisce il primo elemento di una sequenza che soddisfa la condizione specificata. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Restituisce il primo elemento di una sequenza, o un valore predefinito se la sequenza è vuota. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | Restituisce il primo elemento della sequenza che soddisfa una condizione o un valore predefinito se non viene trovato alcun elemento. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | Raggruppa gli elementi di una sequenza. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | Raggruppa gli elementi di una sequenza. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Restituisce l'ultimo elemento di una sequenza. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Restituisce l'ultimo elemento di una sequenza, o un valore predefinito se la sequenza è vuota. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | Invoca una funzione di trasformazione su ciascun elemento di una sequenza generica e restituisce il valore massimo risultante. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | Invoca una funzione di trasformazione su ciascun elemento di una sequenza generica e restituisce il valore minimo risultante. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtra gli elementi della sequenza in base al tipo specificato. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | Ordina gli elementi di una sequenza in ordine ascendente secondo i valori chiave selezionati da keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | Ordina gli elementi di una sequenza in ordine discendente secondo i valori chiave selezionati da keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Inverte l'ordine degli elementi in una sequenza. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | Trasforma gli elementi di una sequenza. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | Trasforma ciascun elemento di una sequenza in una nuova forma includendo l'indice dell'elemento. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> &) | Proietta ciascun elemento di una sequenza e combina le sequenze risultanti in una sola sequenza. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Salta un numero specificato di elementi consecutivi dall'inizio di una sequenza e restituisce il resto. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Restituisce un numero specificato di elementi consecutivi dall'inizio di una sequenza. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Crea un array da una sequenza. |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | Crea una List<T> da una sequenza. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | Filtra una sequenza in base al predicato specificato. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | Costruttore di copia. Non copia realmente nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | Operatore di assegnazione di spostamento. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | Operatore di assegnazione di spostamento. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Operatore di assegnazione. Non copia realmente nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Ottiene un iteratore inverso all'ultimo elemento della collezione (primo in ordine inverso). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Ottiene un iteratore inverso all'ultimo elemento della collezione qualificata const (primo in ordine inverso). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey&) | Rimuove la chiave dal contenitore. |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | Elimina l'elemento dalla collezione. |
| void [RemoveAt](./removeat/)(int) | Rimuove l'elemento nella posizione specificata. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso di un valore specificato. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Ottiene un iteratore inverso per un elemento non esistente prima dell'inizio della collezione. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Ottiene un iteratore inverso per un elemento non esistente prima dell'inizio della collezione qualificata const. |
| void [set_Capacity](./set_capacity/)(int) | Imposta la capacità attuale della lista. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore weak (invece di shared). Consente di cambiare i puntatori nei contenitori in modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore attuale del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| [SortedList](./sortedlist/)() | Costruisce una lista vuota. |
| [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<TKey>>&) | Costruisce una lista vuota. |
| [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>&) | Costruttore di copia. |
| [SortedList](./sortedlist/)(const [map_t](./map_t/)&) | Costruttore di copia. |
| [SortedList](./sortedlist/)(int) | Costruisce una lista vuota. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey&, TValue&) const | Cerca il valore e lo recupera se trovato. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Ottiene l'implementazione dell'iteratore const begin per il contenitore corrente. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Ottiene l'implementazione dell'iteratore begin per il contenitore corrente. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Ottiene l'implementazione dell'iteratore const end per il contenitore corrente. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Ottiene l'implementazione dell'iteratore end per il contenitore corrente. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| virtual [~ICollection](../icollection/~icollection/)() | Distruttore. |
| virtual [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [KeyCollection](./keycollection/) | Tipo collezione chiavi. |
| [ValueCollection](./valuecollection/) | Tipo collezione valori. |
| [map_t](./map_t/) | Tipo di dati sottostante. |
| [this_t](./this_t/) | Questo tipo. |
| [Ptr](./ptr/) | Tipo puntatore. |
| [KVPair](./kvpair/) | Tipo coppia chiave-valore. |
| [IEnumerablePtr](./ienumerableptr/) | Tipo collezione di coppie identiche. |
| [IEnumeratorPtr](./ienumeratorptr/) | Tipo **Enumerator**. |
| [iterator](./iterator/) | Tipo iteratore. |
| [const_iterator](./const_iterator/) | Tipo iteratore const. |
| [reverse_iterator](./reverse_iterator/) | Tipo iteratore inverso. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipo iteratore inverso const. |

## Vedi anche

* Classe [SortedListHelper](../sortedlisthelper/)
* Classe [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)