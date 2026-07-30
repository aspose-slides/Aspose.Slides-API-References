---
title: HolderInitializer
second_title: Riferimento API di Aspose.Slides per C++
description: Questa classe viene utilizzata per ottenere un riferimento persistente all'istanza dell'oggetto, sia che sia un lvalue sia un rvalue. Per ottenere tale riferimento, utilizzare il metodo 'HoldIfTemporary', che ha tre overload. Due di essi accettano un rvalue come parametro e restituiscono semplicemente il riferimento a esso. Il terzo, al contrario, accetta un lvalue come parametro, crea una copia del puntatore e restituisce il riferimento a quella copia. Inoltre, la classe possiede il metodo 'Hold' per mantenere il valore passato incondizionatamente (usato per copiare i valori di variabili locali sullo stack o i relativi riferimenti figli)
type: docs
weight: 1639
url: /it/system/holderinitializer/
---
## HolderInitializer struct


Questa classe viene utilizzata per ottenere un riferimento persistente all'istanza dell'oggetto, sia che sia un lvalue sia un rvalue. Per ottenere tale riferimento, usa il metodo 'HoldIfTemporary', che ha tre overload. Due di essi accettano un rvalue come parametro e restituiscono semplicemente il riferimento a esso. Il terzo, al contrario, accetta un lvalue come parametro, crea una copia del puntatore e restituisce il riferimento a quella copia. Inoltre, la classe possiede il metodo 'Hold' per mantenere il valore passato incondizionatamente (usato per copiare i valori di variabili locali nello stack o i relativi riferimenti figli)

```cpp
template<typename T,bool>class HolderInitializer
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo dell'oggetto da tenere. |
| R | Vero, se T è un tipo di riferimento (specializzazione [SmartPtr](../smartptr/) o tipo [System::String](../string/)), e il mantenimento di riferimenti temporanei è effettivamente necessario, falso altrimenti. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | Copia il lvalue passato nel contenitore, quindi restituisce il riferimento al contenitore. Il chiamante dovrebbe usare questo metodo per mantenere il valore passato incondizionatamente. |
|  [HolderInitializer](./holderinitializer/)(T\&) | Inizializza il riferimento del contenitore con quello passato. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | Restituisce il riferimento al rvalue (const). |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | Restituisce il riferimento al rvalue (non const). |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | Copia il lvalue passato nel contenitore, quindi restituisce il riferimento al contenitore. |

## Vedi anche

* Namespace [System](../)
* Library [Aspose.Slides](../../)