---
title: Object
second_title: Riferimento API di Aspose.Slides per C++
description: Classe base che consente l'uso dei metodi disponibili per la classe System.Object in C#. Tutte le classi non banali utilizzate nell'ambiente tradotto dovrebbero ereditare da essa.
type: docs
weight: 1132
url: /it/system/object/
---
## Classe Object


Classe base che consente l'uso dei metodi disponibili per la classe [System.Object](./) in C#. Tutte le classi non triviali utilizzate con l'ambiente tradotto dovrebbero ereditare da essa.

```cpp
class Object
```

## Metodi

| Method | Descrizione |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](./equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](./gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](./gettype/). |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](./lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../lockcontext/). |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](./memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](./object/)() | Crea un oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](./object/)([Object](./) const\&) | Costruttore di copia. Non copia nulla, davvero, ma inizializza un nuovo oggetto e consente la costruzione di copia per le subclass. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Operatore di assegnazione. Non copia nulla, davvero, si limita a inizializzare un nuovo oggetto e consente la costruzione di copia per le subclass. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](./referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializzazione di [Object::ReferenceEquals](./referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento del template come puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](./sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../string/) [ToString](./tostring/)() const | Analogo del metodo C# [Object.ToString()](./tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Implementa il costrutto C# typeof([System.Object](./)). |
| void [Unlock](./unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](./weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](./~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [ptr](./ptr/) | Alias per il tipo di smart pointer. |

## Osservazioni


Oltre ai metodi disponibili nella classe C# [System.Object](./), consente anche il supporto per alcuni concetti specifici dell'ambiente di codice tradotto. Ciò include il conteggio dei riferimenti utilizzato dalle classi di smart pointer ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) e altri servizi relativi alla gestione della memoria, debug, ecc.

Ogni [Object](./) ha due contatori di riferimento: contatore di riferimento condiviso e contatore di riferimento debole. Il contatore di riferimento debole è sempre memorizzato in una struttura dati separata piuttosto che in [Object](./) stesso, il che consente ai puntatori deboli di sopravvivere all'oggetto a cui fanno riferimento. Il contatore di riferimento intelligente è memorizzato o nell'oggetto stesso o nella stessa struttura separata, a seconda dello stato della macro ENABLE_EXTERNAL_REFCOUNT. Per impostazione predefinita, è abilitato nelle build di debug e disabilitato nelle build di rilascio. Se il contatore dello smart pointer è memorizzato nell'oggetto stesso, la struttura dati separata viene creata solo se esistono puntatori deboli verso l'oggetto. Altrimenti, viene creata insieme all'oggetto stesso.

Tutti gli smart pointer utilizzano questi due contatori di riferimento e contribuiscono allo stesso unico gruppo di proprietà.

Se la sottoclasse [Object](./) è creata sullo stack, non possono essere creati smart pointer su di essa, altrimenti si verifica un problema di cancellazione dello stack.

Questo tipo può essere allocato sia sullo stack come tipo valore sia sull'heap usando la funzione [System::MakeObject()](../makeobject/). Una volta che l'oggetto è allocato, non mescolare mai questi due casi d'uso: avere puntatori [SmartPtr](../smartptr/) verso oggetti allocati sullo stack è severamente proibito. 

## Vedi anche

* Namespace [System](../)
* Library [Aspose.Slides](../../)