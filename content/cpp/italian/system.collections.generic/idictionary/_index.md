---
title: IDictionary
second_title: Riferimento API di Aspose.Slides per C++
description: "Interfaccia per contenitori simili a dizionari. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione System::MakeObject(). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò causerà errori di runtime e/o errori di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 274
url: /it/system.collections.generic/idictionary/
---
## IDictionary classe

Interfaccia per contenitori simili a dizionari. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o errori di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
template<typename TKey,typename TValue>class IDictionary : public System::Collections::Generic::ICollection<KeyValuePair<TKey, TValue>>
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| TKey | Tipo della chiave. |
| TValue | Tipo del valore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual void [Add](./add/)(const TKey\&, const TValue\&) | Aggiunge una coppia chiave-valore al contenitore. |
| virtual void [Add](../icollection/add/)(const T\&) | Aggiunge un elemento alla collezione. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Restituisce un iteratore che punta al primo elemento (se presente) della collezione. Questo iteratore non può essere usato per modificare l'oggetto referenziato poiché [GetEnumerator()](../ienumerable/getenumerator/) restituisce un oggetto copia di T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Restituisce un iteratore che punta al primo elemento (se presente) dell'istanza const della collezione. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Restituisce un iteratore che punta al primo elemento const (se presente) della collezione. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Restituisce un iteratore che punta subito dopo l'ultimo elemento const (se presente) della collezione. |
| virtual void [Clear](../icollection/clear/)() | Elimina tutti gli elementi dalla collezione. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | Verifica se l'elemento è presente nella collezione. |
| virtual **bool** [ContainsKey](./containskey/)(const TKey\&) const | Verifica se il contenitore contiene la chiave. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | Copia il contenuto del dizionario negli elementi di un array esistente. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Restituisce un iteratore che punta subito dopo l'ultimo elemento (se presente) della collezione. Questo iteratore non può essere usato per modificare l'oggetto referenziato poiché [GetEnumerator()](../ienumerable/getenumerator/) restituisce un oggetto copia di T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Restituisce un iteratore che punta subito dopo l'ultimo elemento (se presente) dell'istanza const della collezione. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri in virgola mobile in stile C#, dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri in virgola mobile in stile C#, dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual int [get_Count](../icollection/get_count/)() const | Restituisce il numero di elementi nella collezione. |
| **bool** [get_IsFixedSize](./get_isfixedsize/)() const | Verifica se la dimensione della collezione è fissa. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Verifica se la collezione è di sola lettura. |
| **bool** [get_IsSynchronized](./get_issynchronized/)() const | Verifica se il contenitore è thread-safe. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](./get_keys/)() const | Accede alla collezione delle chiavi. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Restituisce l'oggetto attraverso il quale la collezione è sincronizzata. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](./get_values/)() const | Accede alla collezione dei valori. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Restituisce la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](../ienumerable/getenumerator/)() | Restituisce l'enumeratore. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Restituisce il vero tipo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](./getvalueordefault/)(const TKey\&) const | Restituisce il valore se trovato; altrimenti **Value()**. |
| virtual TValue [GetValueOrDefault](./getvalueordefault/)(const TKey\&, const TValue\&) const | Restituisce il valore se trovato; altrimenti **defaultValue**. |
| virtual TValue [GetValueOrNull](./getvalueornull/)(const TKey\&) const | Restituisce il valore se trovato; altrimenti **null**, ha senso solo per tipi di riferimento. |
|  [ICollection](../icollection/icollection/)() | Costruttore predefinito. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Costruttore di copia. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Costruttore di spostamento. |
| virtual TValue [idx_get](./idx_get/)(const TKey\&) const | Funzione getter. |
| virtual void [idx_set](./idx_set/)(const TKey\&, TValue) | Funzione setter. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Applica una funzione accumulatore su una sequenza. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determina se tutti gli elementi di una sequenza soddisfano una condizione. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Determina se una sequenza contiene elementi. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determina se esiste almeno un elemento in una sequenza o se soddisfa una condizione. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Calcola la media di una sequenza di valori numerici. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Calcola la media di una sequenza di valori ottenuti invocando una funzione di trasformazione su ogni elemento della sequenza di input. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Casta gli elementi al tipo specificato. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Concatena due sequenze. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Determina se una sequenza contiene un valore specificato. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Restituisce il numero di elementi nella sequenza (calcolato mediante conteggio diretto). |
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
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordina gli elementi di una sequenza in ordine crescente secondo i valori chiave selezionati da keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Ordina gli elementi di una sequenza in ordine decrescente secondo i valori chiave selezionati da keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Inverte l'ordine degli elementi in una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Trasforma gli elementi di una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Trasforma ogni elemento di una sequenza in una nuova forma includendo l'indice dell'elemento. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Proietta ogni elemento di una sequenza e combina le sequenze risultanti in una singola sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Salta un numero specificato di elementi contigui dall'inizio di una sequenza e restituisce il resto. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Restituisce un numero specificato di elementi contigui dall'inizio di una sequenza. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Crea un array da una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Crea una List<T> da una sequenza. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtra una sequenza in base al predicato specificato. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e permette di costruire copie di sottoclassi. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operatore di assegnazione di spostamento. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operatore di assegnazione di spostamento. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e abilita la costruzione di copie per le subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| virtual **bool** [Remove](./remove/)(const TKey\&) | Rimuove la chiave dal contenitore. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | Elimina l'elemento dalla collezione. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (anziché condiviso). Permette di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Restituisce il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| virtual **bool** [TryGetValue](./trygetvalue/)(const TKey\&, TValue\&) const | Cerca il valore e lo recupera se trovato. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Restituisce l'implementazione dell'iteratore begin const per il contenitore corrente. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Restituisce l'implementazione dell'iteratore begin per il contenitore corrente. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Restituisce l'implementazione dell'iteratore end const per il contenitore corrente. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Restituisce l'implementazione dell'iteratore end per il contenitore corrente. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Distruttore. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Definizioni di tipo

| Definizione di tipo | Descrizione |
| --- | --- |
| [BaseType](./basetype/) | Tipo di interfaccia base. |
| [KeyValuePairType](./keyvaluepairtype/) | Tipo coppia chiave-valore. |

## Vedi anche

* Classe [ICollection](../icollection/)
* Spazio dei nomi [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)