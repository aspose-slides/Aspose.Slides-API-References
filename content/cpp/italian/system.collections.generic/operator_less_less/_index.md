---
title: operator<<()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisci i dati nello stream usando la codifica UTF-8.
type: docs
weight: 716
url: /it/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) funzione

Inserisci i dati nello stream usando la codifica UTF-8.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Tipo della chiave. |
| TValue | Tipo del valore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | std::ostream\& | Stream di output su cui inserire i dati. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) da inserire. |

### Valore restituito

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) funzione

Inserisci i dati nello stream.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TKey | Tipo della chiave. |
| TValue | Tipo del valore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | std::wostream\& | Stream di output su cui inserire i dati. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) da inserire. |

### Valore restituito

**stream**.

## Vedi anche

* Classe [KeyValuePair](../keyvaluepair/)
* Spazio dei nomi [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)