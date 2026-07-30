---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta una raccolta di delegati. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 1093
url: /it/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> classe

Rappresenta una raccolta di delegati. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non usare mai la classe [System::SmartPtr](../smartptr/) per gestire oggetti di questo tipo.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ReturnType | Tipo di ritorno delle entità invocabili puntate da ciascun delegato nella raccolta |
| ArgumentTypes | Elenco di argomenti delle entità invocabili puntate da ciascun delegato nella raccolta |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | NOT IMPLEMENTED. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Aggiunge il delegato specificato alla raccolta. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Aggiunge l'oggetto funzione specificato alla raccolta di delegati. L'oggetto funzione è convertito al tipo delegato Callback prima di essere aggiunto alla raccolta. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Aggiunge l'oggetto MulticastDelegate specificato alla raccolta di delegati. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Aggiunge il metodo non statico specificato dell'oggetto specificato alla raccolta di delegati. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Aggiunge il metodo non statico specificato dell'oggetto specificato alla raccolta di delegati. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Rimuove il delegato specificato dalla raccolta di delegati. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Rimuove il metodo non statico specificato dell'oggetto specificato dalla raccolta di delegati. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Rimuove il metodo non statico specificato dell'oggetto specificato dalla raccolta di delegati. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Rimuove l'oggetto MulticastDelegate specificato dalla raccolta di delegati. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Rimuove tutti i delegati dalla raccolta di delegati. |
| **bool** [empty](./empty/)() const | Determina se la raccolta di delegati è vuota. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | NOT IMPLEMENTED. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Invoca tutti i delegati attualmente presenti nella raccolta di delegati. I delegati sono invocati nello stesso ordine in cui sono stati aggiunti alla raccolta. Il metodo blocca l'esecuzione finché i delegati non hanno terminato. |
| **bool** [IsNull](./isnull/)() const | Determina se la raccolta di delegati è vuota. |
| [MulticastDelegate](./multicastdelegate/)() | Costruisce una raccolta vuota. |
| [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Equivalente al costruttore di default. |
| [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Esegue una copia superficiale della raccolta di delegati. |
| [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Costruttore di spostamento. |
| [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Costruisce un'istanza e aggiunge il delegato specificato alla raccolta di delegati. |
| [MulticastDelegate](./multicastdelegate/)(T) | Costruisce un'istanza e aggiunge il valore specificato alla raccolta di delegati. |
| [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Costruisce un'istanza e aggiunge il valore specificato alla raccolta di delegati. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Determina se la raccolta di delegati non è vuota. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Determina se due istanze di MulticastDelegate - l'oggetto corrente e l'oggetto specificato - sono non uguali. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Invoca tutti i delegati attualmente presenti nella raccolta di delegati. I delegati sono invocati nello stesso ordine in cui sono stati aggiunti alla raccolta. L'operatore blocca l'esecuzione finché i delegati non hanno terminato. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Aggiunge il delegato specificato alla raccolta. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Rimuove il delegato specificato dalla raccolta di delegati. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Assegna la raccolta di delegati rappresentata dall'oggetto specificato all'oggetto corrente. Di conseguenza entrambi gli oggetti puntano alla stessa raccolta di delegati. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Operatore di assegnazione di spostamento. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Determina se la raccolta di delegati è vuota. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Determina se due istanze di MulticastDelegate - l'oggetto corrente e l'oggetto specificato - sono uguali. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Pulisce i callback contenuti che sono vuoti (non chiamano realmente nulla). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Restituisce un riferimento all'oggetto [TypeInfo](../typeinfo/) che rappresenta le informazioni di tipo della classe MulticastDelegate. |
| [~MulticastDelegate](./~multicastdelegate/)() | Distruttore. |

## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [Callback](./callback/) | Il tipo dei delegati rappresentato dalla classe MulticastDelegate. |
| [Function](./function/) | Il tipo della funzione relativo alla firma del delegato. |

## Vedi anche

* Spazio dei nomi [System](../)
* Library [Aspose.Slides](../../)